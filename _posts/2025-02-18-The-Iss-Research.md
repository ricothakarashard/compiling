

# 
{% for image in site.static_files %}
    {% if image.path contains 'spacestation/loc' %}
        <img src="https://raw.githubusercontent.com/ricoThaka/{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}