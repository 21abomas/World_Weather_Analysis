<div>
  <h1>Weather and Hotel Visualization</h1>
  <p>This project aims to create a visualization of weather data and hotel information based on a user's preferred temperature range. This project utilizes the following libraries: hvplot.pandas, pandas, and requests.</p>
  <p>To start, a CSV file called "cities.csv" is read into a Pandas DataFrame using the pd.read_csv() function. The DataFrame is then visualized on a map using hvplot.points(), with longitude and latitude coordinates as the x and y axes respectively.</p>
  <p>Next, the user is prompted to input their preferred minimum and maximum temperature values. These values are then used to filter the original DataFrame, creating a new DataFrame called "preferred_cities_df" which contains only cities with temperatures within the user's preferred range.</p>
  <p>Then, using the Geoapify Places API, a new DataFrame called "hotel_df" is created which includes the names of hotels in each of the preferred cities. This DataFrame is then visualized on a map using hvplot.points(), with longitude and latitude coordinates as the x and y axes respectively, and the size of the markers representing the maximum temperature of the city.</p>
  <p>Finally, the resulting visualizations are saved as HTML files, which can be accessed and viewed in any web browser.</p>
</div>
