# UFOs
## Purpose 
### Overview
This analysis was completed to make a website to showcase the UFO sightings. 
The site has a table showing when, where, and descriptions of UFO sightings. 
The host wanted to make sure there were filters for the visitors to use to find specific UFO sightings.

The following tools were used to complete this site:
- JavaScript
- HTML
- Bootstrap
- CSS

### Results
After writing the index.html and app.js files, a website was formed with the UFO data. 
once the codes were ran the following features are displayed:
- Heading/Title
- Article title
- Article Paragraph
- Filters for the Table
- Table of UFO sightings
- dark background
- Heading image

The orignial design had a filter button just for the date. (see image below)

![ufo_mod](https://user-images.githubusercontent.com/105830665/192552348-16f7d616-3d74-4bb5-b652-9bc5a1e4d546.png)

For the updated layout, the filter was changed to include date, city, state, country, and shape.

![ufo1](https://user-images.githubusercontent.com/105830665/192552452-3ede52d4-926d-46f9-ac72-d183bbe6cb3e.png)

The updated site also had a loop created to help filter through the data and create a new table based on the filtered criteria. This could be any combination of dates, cities, states, and shapes. It looks like all the data was based in the US. 

Filtered page with a result.
![test1](https://user-images.githubusercontent.com/105830665/192552529-8441eb9e-3f2b-4949-b7d2-fb4737ffbb39.png)

Filterd page without any results
![test2](https://user-images.githubusercontent.com/105830665/192552675-b676db45-49e6-4de4-8a01-537d9b379e59.png)

### Summary
After several test, the page is functioning as expected. The only dilema with this page is that the filter option can be to specific. As shown in the results, if you do not the exact information for the sighting, you can return a blank table. One recommendation for further development would be to include an "or" option for the filters. This would be similar to what companies use when guest search for a store location. The guest is asked to enter a city and state OR zip code to search. With this visitors of the site would not feel obligated to fill in all the filters. Another recommendation would be to remove the "country" filter. After searching for countries other than the US, there were only two sightings in Canada. So removing this filter could save the code running time.