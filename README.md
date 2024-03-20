# WU_scraper
R function to download data from weatherunderground

You need to register and create an API key at https://www.wunderground.com

Example on how to use the function:

`start="2024-01-01"`  
`end="2024-03-01"`  
`output_path="your path"`  
`api_key <- "your API key"`     
`stations=c("IDRESD330","IDRESD25")`    
###you need to use WU map to find stations ID here: https://www.wunderground.com/dashboard/pws/IDRESD322

 `for (station in 1:length(stations)){
   weather_underground_data(start,end,station=stations[station],api_key,export_txt=T,output_path=output_path,verbose=T)  
   }  
 `
  



