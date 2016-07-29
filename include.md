### Storm database event explorer

The Shiny app uses NOAA's storm database to analyse the impact of severe storm events on both public health and economy. Because the complete dataset is approximately 550MB and this project is used to show case shiny and demonstrate shiny skills the app uses a small subset of the original NOAA dataset.

Additional information about the storm database can be found from:  
1. National Weather Service [Storm Data Documentation](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2Fpd01016005curr.pdf)   
2. National Climatic Data Center Storm Events [FAQ](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2FNCDC%20Storm%20Events-FAQ%20Page.pdf)  
3. The complete dataset can be downloaded from NOAA located at [Storm Data](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2) 


#### More about the app  
The app uses are range of Shiny input selectors to make the app highly interactive as follows:
1. A slider is the main input to query all data by year.
2. Checkbox are used to select event types
3. Button controls to select or clear all event selections
4. Radio buttons to select population and economic impact types 
5. Maps and charts displaying filtered query results.


#### Project Links
1. Fork me from [GitHub](https://github.com/TerryGrimaldi/Shiny_Project.git).
2. Run the [Shinyapp](https://terrygrimaldi.shinyapps.io/Shiny_Project/)







