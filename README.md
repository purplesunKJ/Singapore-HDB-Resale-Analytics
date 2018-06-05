# Singapore-HDB-Resale-Analytics

Business Objectives:

To conduct an Exploratory Data Analysis(EDA) to study the relationship between following attributes with HDB resale prices:

- Town (eg, Bishan, Ang Mo Kio...)
- Flat Type (eg. 1-room, 2-room)
- Storey Number (eg. 2, 23,30...)
- Floor Area (sqft)
- Flat Model (eg. new generation, improved, standard...)
- Remaining Lease Year (eg. 98, 78...)
- Distance from MRT station (meters)


To build a machine learning model using existing attributes and derived features to predict HDB resale prices

Dataset Used:

HDB resale transaction from 1990 Q1 to 2018 Q1
Quarterly HDB resale price index from 1990 Q1 to 2018 Q1
Google API used:

Geocoding API - To locate the lat long coordinate of HDB blk from full address string
Place Search API - To locate the lat long coordinate of nearest MRT station
Distance Matrix API- To obtain the distance and duration from a HDB block to nearest MRT station
