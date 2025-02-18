

# 
{% for image in site.static_files %}
    {% if image.path contains 'spacestation/loc' %}
        <img src="{{ site.url }}{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}