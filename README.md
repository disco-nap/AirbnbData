# Airbnb project
#### By Christina Vavoulis, Raman Dhaliwal , and Julia Napolitano

Our group was interested in creating an interactive map which hosts recent Airbnb data. We used SQL, SQL Alchemy, Python, Pandas, Plotly, Flask, Geojson data, Javascript, Openstreetmap, Leaflet, Particles, HTML, and CSS.

Our dashboard includes many interactive user features. The map shows San Francisco and all of the available homes in san francisco. The different color markers pin point the pricing. Green is for homes less than $100 a night, blue is $100-$200, yellow is $200-$300 and red $300+ a night. When you select a certain home, a pop-up will appear with details about the posting and a link to reserve specific dates through the Airbnb portal. 
<iframe src="https://giphy.com/embed/AhvIq03orDkihZ0dDe" width="480" height="300" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/AhvIq03orDkihZ0dDe">via GIPHY</a></p>

As a user moves the curser around the map, the specific neighborhood under the curser will highlight. When a certain neighborhood is selected, the map will zoom and re-center around the selected neighborhood. This is made possible with a geojson library of multipolygons for each neighborhood. 
<iframe src="https://giphy.com/embed/fLp7CENeUa94kRw8CJ" width="480" height="300" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/fLp7CENeUa94kRw8CJ">via GIPHY</a></p>

Our dashboard also holds 3 vertical bar charts. One of the bar charts shows the amount of homes avaiable in each neighborhood, another shows the average price per home in each neighborhood, another shows the average customer star rating in each neighborhood.
<iframe src="https://giphy.com/embed/20NhvX1MGdxdb19C4J" width="480" height="300" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/20NhvX1MGdxdb19C4J">via GIPHY</a></p>
Lastly, our particles background moves with the cursor.
