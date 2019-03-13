# Ocean-Engineering-Lim

Summary of Project:
This final project explores the sound velocity profile among different oceans located at three different latitudes. All the real-world data uses the CTD instrument to measure the necessary properties (i.e. temperature, salinity, and pressure) required to calculate the speed of sound. In this project, for the northern part of world, CTD data from Chukchi sea at the Arctic ocean is used to compute the sound velocity using this formula, c = 1449.2+(4.6*T)−(0.055*T*T)+(0.00029*T*T*T)+(1.34−(0.01*T))*(S−35)+(0.016*z), where T = Sea water Temperature in deg C, S = Salinity, and z = depth in meter.
Close to the equator, CTD data from Indonesian sea located at the coastal equatorial pacific will be used to compute the sound velocity as well. Same sound velocity formula is being used.
Last but not least, for the southern part of the world, CTD data from Palmer Station at the Antarctic Ocean will be used to compute the sound velocity.
After computation has been done, sound velocity profile graph can be plotted by Python to see how the sound channel axis differ from oceans at different latitudes. This graph can also provide how fast the sound velocity is near the surface of the sea water. The overall shape of the graph allows us to judge the range of the SOFAR sound channel.

Data recording:
All of the data is taken in the late Summer until beginning of Fall season, except for the one in equatorial seas.

Data acquisition:
Most of the data is downloaded from NODC, part of NOAA website.

Link to Data:
1. Chukchi Sea in Arctic Ocean : https://www.nodc.noaa.gov/cgi-bin/OAS/prd/accession/download/61042
2. Palmer Station in Antartica (Southern) Ocean: https://portal.lternet.edu/nis/dataviewer?packageid=knb-lter-pal.269.2&entityid=1659701543ad8f2105a76d49fa4e56d5
3. Indonesia Sea (equatorial pacific ocean): http://data.nodc.noaa.gov/woa/WOD/XBT_BIAS/CRUISES/42009066/42009066_CTD.csv



