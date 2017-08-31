## U.S. Monthly Average Precipitation and Snowfall

This is a data visualization project about monthly normal precipitation and snowfall for the 48 mainland states. The data for this project was obtained from <a href="https://www.ncdc.noaa.gov/">NOAA National Centers for Environmental Information</a> (formerly the NCDC). The data can be found on the <a href="https://www.ncdc.noaa.gov/cdo-web/">Climate Data Online</a> page. The goal is to create interactive plots that show changes in percipitation and snowfall throughout the year.

Check out the visualization here: https://nnvutisa.github.io/weather.

### Code
- The code for processing the data is in <code>weather.ipynb</code>.
- The Jupyter notebook file for creating the plots can be viewed in <code>weather_plot.ipynb</code>. 
- Bokeh plots were saved as html files and embedded on the webpage.

### Data 
All the data files are in <code>/data</code>.
- <code>allstations.txt</code> -- information of weather stations from the NCDC
- <code>mly-prcp-normal.txt</code> -- monthly normal precipitation data (1981-2010) from the NCDC
- <code>mly-snow-normal.txt</code> -- monthly normal snowfall data (1981-2010) from the NCDC
- <code>precip_state.csv</code> -- monthly average precipitation data for each state output from <code>weather.ipynb</code>
- <code>snow_state.csv</code> -- monthly average snowfall data for each state output from <code>weather.ipynb</code>

