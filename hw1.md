| [home page](https://maggie0811.github.io/Advanced_GIS-/) | [Homework 1](hw1)

# Custom Google Maps for the US Department of Transportation

The color palette for the project was created using the [homepage](https://www.transportation.gov/) for the United States Department of Transportation. The website link was given to ChatGPT, as well as a request to generate five hex codes based on the website. The five colors are as follows:
* Dark Blue #005eb8
* Grey #4a4a4a
* White #ffffff
* Dark Green #006837
* Yellow #fdb813 

Additionally, one extra light blue color was generated manually for the water feature (Light Blue #e5faff).

Here is the source material for the color palette: 

<img src= "https://raw.githubusercontent.com/maggie0811/Advanced_GIS-/main/ChatGPT_Colors.JPG" width = 600/>

Once these colors were selected, various features of the map were changed using the color codes provided. The final results of the map can be seen below, at various zoom levels.

## Level 1 Zoom:

<img src= "https://raw.githubusercontent.com/maggie0811/Advanced_GIS-/main/Map_colors.JPG" width="700"/>

## Level 2 Zoom:

<img src= "https://raw.githubusercontent.com/maggie0811/Advanced_GIS-/main/map_colors2.JPG" width="700"/>

## Level 3 Zoom:

<img src= "https://raw.githubusercontent.com/maggie0811/Advanced_GIS-/main/map_colors3.JPG" width="700"/>

To recreate the map, one should visit the Google Maps styling wizard website at https://mapstyle.withgoogle.com/. From there, click on "Use the legacy JSON styling wizard." This will take the user to a page that allows them to stylize their own map. To import the colors used in this project, first download the JSON file linked on this page. 

[Here is a link to download the JSON file](map_colors.json)

Once the JSON is downloaded, in the Google Maps styling wizard click the three dots located next to "Create Map Style" in the top lefthand corner of the page. This will provide the user with the option to "Import JSON." Copy and paste the downloaded JSON file into the text box and click "Import JSON."

<img src= "https://raw.githubusercontent.com/maggie0811/Advanced_GIS-/main/JSON%20instructions.JPG">

Additionally, each feature that was altered with the corresponding color is provided in the lookup table below.

|Feature Type              |	Element Type    |	Stylers           |
|--------------------------|--------------------|-------------------------|
|All	                   |Geometry	        |Color: Dark Blue #005eb8 |
|All	                   |Labels/ Text Fill   |Color: Grey #4a4a4a      |
|All	                   |Labels/Text Outline |Color: White #ffffff     |
|Land Parcel	           |Geometry	        |Color: Dark Green #006837|
|Land Parcel	           |Labels/ Text Fill	|Color: Grey #4a4a4a      |
|Land Parcel	           |Labels/Text Outline |Color: White #ffffff     |
|Natural	           |Geometry	        |Color: Grey #4a4a4a      |
|Points of Interest	   |Geometry	        |Color: Grey #4a4a4a      |
|Points of Interest	   |Labels/ Text Fill	|Color: Grey #4a4a4a      |
|Business	           |All	                |Color: Dark Green #006837|
|Park	                   |Geometry	        |Color: Dark Green #006837|
|Park	                   |Labels/Text Fill	|Color: Dark Green #006837|
|Park			   |Labels/Text Outline	|Color: White #ffffff     |
|Road			   |Geometry	        |Color: Grey #4a4a4a      |
|Highway	           |Geometry/Stroke	|Color: Yellow #fdb813    |
|Highway	           |Labels/Text Fill	|Color: Grey #4a4a4a      |
|Highway/Controlled Access |Geometry	        |Color: Yellow #fdb813    |
|Arterial	           |Geometry	        |Color: Yellow #fdb813    |
|Arterial          	   |Labels/Text Fill	|Color: Grey #4a4a4a      |
|Local	                   |Geometry	        |Color: Yellow #fdb813    |
|Local	                   |Labels/Text Fill	|Color: Grey #4a4a4a      |
|Transit Line	           |Geometry	        |Color: Grey #4a4a4a      |
|Transit Line	           |Labels/Text Fill	|Color: Grey #4a4a4a      |
|Transit Line	           |Labels/Text Outline	|Color: White #ffffff     |
|Transit Station	   |Geometry	        |Color: Grey #4a4a4a      |
|Water	                   |Fill	        |Color: Light Blue #e5faff|
|Water        	           |Labels/Text Fill	|Color: Grey #4a4a4a      |
        
