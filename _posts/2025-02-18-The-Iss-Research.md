<img src="https://raw.githubusercontent.com/ricoThaka/compiling/assets/spacestation/loc/master-pnp-ppmsca-62600-62669u.jpg" alt="image" />



<img src="https://raw.githubusercontent.com/ricoThaka/compiling/assets/spacestation/loc/master-pnp-ppmsca-62900-62978u.jpg" alt="image" />



<img src="https://raw.githubusercontent.com/ricoThaka/compiling/assets/spacestation/loc/master-pnp-ppmsca-62900-62981u.jpg" alt="image" />



<img src="https://raw.githubusercontent.com/ricoThaka/compiling/assets/spacestation/loc/master-pnp-ppmsca-63400-63497u.jpg" alt="image" />



    <img src="https://raw.githubusercontent.com/ricoThaka/compiling/assets/spacestation/loc/master-pnp-ppmsca-63500-63504u.jpg" alt="image" />

# 
{% for image in site.static_files %}
    {% if image.path contains 'spacestation/loc' %}
        <img src="https://raw.githubusercontent.com/ricoThaka/{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
