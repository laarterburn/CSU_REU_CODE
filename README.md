# CSU_REU_CODE
This is the code for the 2019 CSU REU for atmospheric science. This is the code from Linda's study on particulate matter in central California. The files I coded are uploaded here.Here is a description of all of the data for each of the files in this repository.

*plot_snpp_xarray_all_sites: This is AOD data from the sample code Bonne gave me. I plotted the AOD from the Suomi Npp data for 2019 in this example. I then used cartopy to plot the six different sites and see where they are on the AOD map for California. I just stores all the sites longitudes and lattitudes in variables and plotted them on the plots. I also plotted all of the six sites on the map of the USA to see where they are. This was more so for practice and to see where everything is, as I did not use this data. The data from here is the Suomi Npp data from the NASA website that Bonne got for me. 

*plot_snpp_xarray_pkotting_m_and_f: This is AOD and AE data plotted from November 25, October 20, and October 27 2019. These are all one pannel plots that I used to put on my poster. fresno and Madera are also listed in these plots. I also used this jupyter notebook to see what the daily average for the AOD and AE in Madera and Fresno was for these days (as seen on line 28). The data from here is the Suomi Npp data from the NASA website that Bonne got for me. 

*Introductory_Plots: These are all the plots I made first when I was learning python and got my first set of data from the Fresno EPA-AQS. This file has 2013 Fresno PM2.5 and PM10 plotted, Each year's monthly average and its percentile plotted for Fresno, and diferent graphs displaying the monthly averages of data in Fresno. 

*6_CA_sites_all_annuals: This is a file that has all the annuals for Clovis, Madera, Table Mountain, Sacramento 1390 T Street, Cocoran, and Woodland. The PM2.5/PM10 fraction was taken and averaged per year and put into a bar plot for each site. There are different plots and stacked bar graphs comparing this data at the end of the file. This data is still from the EPA-AQS

*6_CA_sites_analyzed: This is a file that has all the annuals for Clovis, Madera, Table Mountain, Sacramento 1390 T Street, Cocoran, and Woodland. The total mass concentration (PM2.5 plotted next to coarse pm) was taken and averaged per year and put into a bar plot for each site. There are different plots and stacked bar graphs comparing this data at the end of the file that compare the bar graphs for each site. The annual coarse pm fractions were also taken for each year present for each site and bar plots were made for them. For all of these sites, the months september, october, and november were analyzed as well for total mass concentration (pm2.5 and coarse pm for the sust season). This data is still from the EPA-AQS

*CA_Different_Sites_CSV_Downloads_From_EPA: This is just sample code that Bonne gave me to help me call the AQI to download the CSV files for Clovis, Madera, Cocoran, Sacramento, Table Mountain, and Woodland

*Comparing_CPM_AOD_AE: This is a file analyzes the CPM, AOD, and AE between October 15, 2019- November 30, 2019 for Fresno and Madera's daily averages. The scatter plot comparing the daily average CPM, AE, and AOD for Fresno and Madera and the PM2.5, AOD, and AE between October 15, 2019- November 30, 2019 are here as well. This data with the CPM is from the EPA-AQS, and the scatter plot data is from the NASA webiste for the Suomi NPP satellite. 

*Fresno_2019_percentile_graph: Has a time series for the CPM in fresno plotted against the 25th and 75th percentiles.  This data with the CPM is from the EPA-AQS.

The Suomi NPP data is from: 
(daily) https://ladsweb.modaps.eosdis.nasa.gov/archive/allData/5111/AERDB_D3_VIIRS_SNPP/
(monthly) https://ladsweb.modaps.eosdis.nasa.gov/archive/allData/5111/AERDB_M3_VIIRS_SNPP/

EPA AQI info (I have an account through syr.edu email):
https://aqs.epa.gov/aqsweb/documents/data_api.html

EPA AQS maps to see all sites:
https://www.epa.gov/outdoor-air-quality-data/interactive-map-air-quality-monitors
