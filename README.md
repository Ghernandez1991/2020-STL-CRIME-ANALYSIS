# 2020-STL-CRIME-ANALYSIS



This project combines publicaly available crime data from Saint Louis Metro Police Department into a workable datafile and then converts the geographic data into an easily useable format.

The data is available from the STLMPD here
https://www.slmpd.org/Crimereports.shtml


The programatic problem with the dataset provided by STLMPD is that the geographic coordinates are provided in a relatively(for python applications anyway) uncommon format of State Plane North American Datum 1983 (NAD83) format.
The program converts these coordinates into a WGS84 - World Geodetic System 1984, used in GPS dataset that is added to the master dataframe. 


The visualizations are made in Tableau and can be viewed at the link below. 


https://public.tableau.com/profile/gabriel.hernandez8655#!/vizhome/STL_CRIME_2020/HomicidesandAssault1st










![alt text](https://github.com/Ghernandez1991/2020-STL-CRIME-ANALYSIS/blob/master/Images/Discharging%20Firearms%20in%20City%20Limits.png)





![alt text](https://github.com/Ghernandez1991/2020-STL-CRIME-ANALYSIS/blob/master/Images/Homicides%20and%20Assault%201st.png)
