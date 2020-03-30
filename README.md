# FME_work
This repository shows a simple data cleaning/transformation task I undertook using FME.
I found a CSV dataset of Airbnb listings in New York City, USA and performed several data 
cleaning operations. The operations I performed include:

1. Checking for valid prices (i.e. prices > $0)
2. Checking for short term listings (minimum stay 30 nights or less)
3. Removing duplicate style listings (many hotels will list individual 
   rooms that are the same type/price, so I filtered these out)
4. Removed entries that didn't have the name for the host or an invalid host name
5. Renamed the attributes to more readable names
6. Exported the data as an ESRI shapefile
