
# About the International Space Station
The station was designed between 1984 and 1993. Elements of the station were in construction throughout the US, Canada, Japan, and Europe beginning in the late 1980s. [ReadMore](https://www.nasa.gov/international-space-station/)


<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-62900-62978u.jpg" alt="image" />
          


<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-62900-62981u.jpg" alt="image" />



<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-63400-63497u.jpg" alt="image" />



<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-63500-63504u.jpg" alt="image" />

<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-62600-62669u.jpg" alt="image" />


# 

{% for image in site.static_files %}
    {% if image.path contains 'spacestation/loc' %}
        <img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
<div >
  {% for file in site.static_files %}
      {% if file.path contains 'spacestation/loc' and file.extname == '.jpg' %}
          <img src="{{ file.path }}" alt="Gallery Image">
      {% endif %}
  {% endfor %}
</div>
