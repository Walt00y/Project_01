# Atmospheric Environment Intelligent Monitoring System

The system covers eight main functions, which are
* Login
* System Management
* Data Maintenance
* Monitoring & Early Warning
* Fundamental Analysis
* Monitoring Report
* Traceability Analysis
* Monitoring Platform

Next, I will explain one by one. (*Privacy information is coded*)

-------------------------------------------------------------

## Login

This page requires user input, username, password and verification code to log in. (The addition and assignment of user accounts need to be operated in System Management -> User Management)

![Login Page](https://github.com/Walt00y/Project_01/blob/main/pic/login_in.png "Login Page")

-------------------------------------------------------------

## System Management

The system management is oriented to the system administrator of the atmospheric environment intelligent monitoring system, and performs four parts of operation: authority management, role management, user management and login log.

### Role Management

Administrators can set different roles and grant different permissions.

![Role Management](https://github.com/Walt00y/Project_01/blob/main/pic/SysM_RoleM.png "Role")

### User Management

User management is to add and manage the users of the system, including user account, user name, gender, display level, user role and user status. The user status is divided into "normal" and "locked". After the system administrator locks the status of a user, the user does not have permission to log in to the system.

![User Management](https://github.com/Walt00y/Project_01/blob/main/pic/SysM_UserM.png "User")

-------------------------------------------------------------

## Data Maintenance

This section is used for monitoring site management, monitoring area source management and monitoring point source management operations.

### Monitoring Site

In the system, data information such as the point code, latitude and longitude of the monitoring site, belonging company, belonging area, surrounding main emission sources and main functions can be entered in the system. Through the search bar, we can make precise queries by entering the point code or latitude and longitude coordinates of the relevant point. The data entry of newly added points can be performed through the "Add" button. The "Batch Delete" button can delete some points that are no longer in use by checking the square box in the table. At the same time, when the point information changes, you can use the "Modify" button in the first column of the operation bar to modify the data of the relevant point or the "Delete" button to delete it.

![Monitoring site](https://github.com/Walt00y/Project_01/blob/main/pic/DataM_MonitoringSite.png "Site")

### Monitoring Area Sources

We can categorize pollution sources. Each of these categories corresponds to multiple pollution source areas. By collecting and entering the coordinates of multiple points corresponding to each pollution source area, a non-point source of pollution is formed. By selecting different pollution sources, you can see the geographical coordinates of the pollution in this area listed in the table on the right, and connect the non-point sources of pollution of the petrochemical terminal based on these coordinates on the map. Similarly, the operations of adding, modifying, and deleting pollution source areas and adding, modifying, and deleting corresponding surface source coordinate points can be performed through the relevant buttons.

![Monitoring area](https://github.com/Walt00y/Project_01/blob/main/pic/DataM_MonitoringAreaSource.png "Area")

### Announcement Management

By clicking the "Add" button, you can create a new announcement in the pop-up window, and you can also use the "Modify" button to modify the added announcement title and text information, and decide whether to publish it or not.

![Announcement](https://github.com/Walt00y/Project_01/blob/main/pic/DataM_Announcement.png "Announcement")

-------------------------------------------------------------

## Monitoring & Early Warning

### Early Warning

If the monitoring data of a monitoring point exceeds the set alarm threshold, this page will pop up the alarm bar on the right.

![Warning](https://github.com/Walt00y/Project_01/blob/main/pic/Monitoring_EarlyWarning.png "Warning")

### Detail Info of Points

Click on any monitoring point, and the relevant monitoring information will be displayed in the pop-up window on the right.

![Points Info](https://github.com/Walt00y/Project_01/blob/main/pic/Monitoring_Point.png "Points Info")

-------------------------------------------------------------

## Fundamental Analysis

### Data Query

Click any monitoring point on the left, select the start and end dates within a certain time period, and click the search button to view the trend chart of various data of this monitoring point during this period. Click the header button to check different pollutant parameters (TSP, PM2.5, PM10, CO, SO2, NO2, O3, air temperature, humidity, wind speed, wind direction) to view the trend chart.

Click on any point in the figure (click on the circle), you can view the five data records before and after the current time in the table below, and the row marked in yellow in the table is the data of the date and time at the clicked place. In the upper right corner of the chart, there is a download button to download the currently displayed chart. At the same time, you can switch between line charts and bar charts to make data visualization more diverse.

![Query](https://github.com/Walt00y/Project_01/blob/main/pic/FundamentalAnalysis_DataQuery.png "Query")

### Year on Year & Month on Month

Select any point in the station list on the left, select the type of pollutant (TSP, PM2.5, PM10, CO, SO2, NO2, O3) and date (day/week/month) to be queried in the search box, and proceed to Year-on-year queries.

The month-on-month data is a comparison between a certain point (day/week/month) and this (day/week/month), and the data of a certain pollutant type is displayed in a bar chart.

The year-on-year data is a comparison of the data of a certain pollutant type between this year (day/week/month) and this year (day/week/month) at a certain point in the previous year, which is displayed as a bar chart.

![YoY & MoM](https://github.com/Walt00y/Project_01/blob/main/pic/FundamentalAnalysis_YoY_MoM.png "YoY & MoM")

### Calendar

The calendar is to display the monitoring data of the site in the form of a calendar chart. By clicking on a date, the monitoring data information under this date will pop up on the right. Date selections are displayed by month.

![Calendar](https://github.com/Walt00y/Project_01/blob/main/pic/FundamentalAnalysis_Calendar.png "Calendar")

### Meteorological Data

The meteorological data includes three parts: temperature and humidity line graph, wind speed and direction graph, and wind direction rose graph. Select the corresponding point by clicking the site list on the left, and select the time period to search.

#### Line Chart

![Line Chart](https://github.com/Walt00y/Project_01/blob/main/pic/FundamentalAnalysis_MeteorologicalData_LineChart.png "Line Chart")

#### Wind Speed and Direction

![Wind Speed & Direction](https://github.com/Walt00y/Project_01/blob/main/pic/FundamentalAnalysis_MeteorologicalData_WindSpeed&Direction.png "WSD")

#### Wind Rose

![Wind Rose](https://github.com/Walt00y/Project_01/blob/main/pic/FundamentalAnalysis_MeteorologicalData_Wind_Rose.png "WR")


### Data Comparison

By selecting the pollutant type in the drop-down list, select the time range to be viewed, check the points to be viewed in the site list on the left, and click the search button to display the data trend graph in the figure. Cancel the viewing of the corresponding point. You can click the corresponding point in the station list on the left again, or click the corresponding point name in the title box of the graph header. The trend chart of the current comparison point can be downloaded by clicking the download button in the upper right corner.

![Data Comparison](https://github.com/Walt00y/Project_01/blob/main/pic/FundamentalAnalysis_DataComparison.png "DC")

### Historical Data

The historical data page covers all data of all points. We can select a specific time period and measurement site in the search box, query the historical data of each point and each time period, and display it in the form of a data table.

![Historical Data](https://github.com/Walt00y/Project_01/blob/main/pic/FundamentalAnalysis_History.png "HD")

-------------------------------------------------------------

## Monitoring Report

The monitoring report can be searched by selecting a specific point and a specific date through the search box above the table to view the monitoring data of a certain site on a certain day. It is also possible to perform a time range search only to view the data of all points within a specific time range. Click the Export button to export all the data in the current search date range to the local in Excel format.

![Daily Report](https://github.com/Walt00y/Project_01/blob/main/pic/MonitoringReport_Daily.png "DR")

![RealT Report](https://github.com/Walt00y/Project_01/blob/main/pic/MonitoringReport_RealTime.png "RR")

-------------------------------------------------------------

## Traceability Analysis

Find the cause of pollution through data visualization

### Flat

![Flat](https://github.com/Walt00y/Project_01/blob/main/pic/TraceabilityAnalysis_Flat.png "Flat")

### 3D

Traceability analysis The 3D surface map 3D air pollution data in a specific area can visually see the seriously polluted area and compare the data (the X and Y axes show the longitude and latitude respectively, and the Z axis shows the pollution severity) .

Among them, the zoom-in and zoom-out of the 3D image can be controlled by controlling the mouse wheel, the 3D effect display in different directions can be realized by the direction selection box in the upper left corner, and the 3D image display in different directions can be realized by controlling the right mouse button to slide.

Click a location in the heat map on the upper right, and the monitoring range of the clicked location will be displayed on the map on the lower right. Use the slider on the upper right of the map to control the radius to filter suspected pollution sources, and the suspected pollution sources will be displayed in the list on the left.

![3D](https://github.com/Walt00y/Project_01/blob/main/pic/TraceabilityAnalysis_3D.png "3D")

-------------------------------------------------------------

## Monitoring Platform

### Platform

The monitoring platform is an integration of the information covered by the Tianjin Port atmospheric environment monitoring system. Through this platform, users can be presented with intuitive data charts.

![Platform](https://github.com/Walt00y/Project_01/blob/main/pic/Monitoring_platform.png "Platform")

### Announcement

The notification bulletin board can roll out announcements that are allowed to be published. If the announcement exceeds a certain number of words, the excess words will be omitted. You can also click Show All to view the full announcement. As shown in the image below.

![Announcement](https://github.com/Walt00y/Project_01/blob/main/pic/Monitoring_platform_showall.png "Announcement")

-------------------------------------------------------------