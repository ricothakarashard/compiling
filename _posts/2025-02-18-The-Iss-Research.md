
![SPace_OPERATiONS](https://www.nasa.gov/wp-content/uploads/2020/11/iss-7.jpg)

### Space Operations 
#### Mission Directorate
The Space Operations Mission Directorate maintains a continuous human presence in space for the benefit of people on Earth. 

![Org_CHART](https://www.nasa.gov/wp-content/uploads/2023/06/somd-org-chart-2025.png)
[RelatedTweet](https://x.com/genejm29/status/1783503580504195441)
# [EcoStress DataUpdate](https://x.com/RicoThaka/status/1893454797858050098) [RelatedTweet](https://x.com/RicoThaka/status/1893453710568648891) [Elon Musk Calls For SpaceStationDeorbiting](https://x.com/ABC/status/1893441128776581220) [2cents](https://x.com/RicoThaka/status/1893452333113319826)
![ecoStress](https://pbs.twimg.com/media/Gkbm_y1boAACZfw?format=jpg&name=large)
![ECOSTRESS @usgs](https://pbs.twimg.com/media/Gkbl3sfWkAUC3Xz?format=jpg&name=large)
![ECoSTRESS](https://pbs.twimg.com/media/GkbkxS4XUAECq2M?format=jpg&name=large)


[Android OS Documentation](https://source.android.com/docs)
# About the International Space Station
The station was designed between 1984 and 1993. Elements of the station were in construction throughout the US, Canada, Japan, and Europe beginning in the late 1980s. [ReadMore](https://www.nasa.gov/international-space-station/)


<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-62900-62978u.jpg" alt="image" />
          


<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-62900-62981u.jpg" alt="image" />



<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-63400-63497u.jpg" alt="image" />



<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-63500-63504u.jpg" alt="image" />

<img src="https://raw.githubusercontent.com/ricoThaka/compiling/refs/heads/master/assets/spacestation/loc/master-pnp-ppmsca-62600-62669u.jpg" alt="image" />

![SpaceWalk](https://www.nasa.gov/wp-content/uploads/2022/12/51476067951-e10dfb6875-o-1.jpg)
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
