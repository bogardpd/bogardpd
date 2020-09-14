---
title: "Beavercreek Bathrooms"
excerpt: "Playing around with county parcel data to create maps of questionable usefulness."
---

<figure>
  <img src="{{site.baseurl}}/assets/images/posts/map-beavercreek-bathrooms.png" alt="Map of property parcels in Beavercreek, Ohio, color coded by number of bathrooms, which ranges from 1 to 9.">
  <figcaption>Street data &copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors</figcaption>
</figure>

Some of the local neighborhoods that I go on walks through were damaged by the 2019 Memorial Day tornadoes, and I’ve gradually watched some houses be rebuilt. I had an idea of playing around with plotting the path of the property damage, so I went looking for Beavercreek, Ohio property parcel shapefiles.

I came across the Greene County parcel dataset, which in addition to the shapes of properties in the area had quite a bit of data about the structures – including, as it turns out, the number of bathrooms each house in the county.

Temporarily distracted by this newfound data, I fired up QGIS and created a map of the values of the `FULL BATH` field, filtered by residential properties (in the `CLASS` field).