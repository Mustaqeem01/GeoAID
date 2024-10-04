# GeoAID: A GIS-Driven Framework for Fair Aid Distribution During Flood

## Demonstrative Working Prototype in Website: 
https://urban-utopians.nextgis.com/resource/52/display?panel=layers

## Mobile App Prototype:
https://github.com/Mustaqeem01/GeoAID/blob/main/GeoAID_1_1.0.apk

## Documentation:
Download the files and open the file with qgz extention in QGIS. You can upload the raster and vector datasets and apply various symbologies.

## Methodology

### Step 1: Data Preprocessing in QGIS
1. **Import all data layers into QGIS** (e.g., flood data, road network, DEM, population density, poverty distribution, and built components).
2. **Reproject all layers** to the same coordinate reference system (CRS), such as **EPSG:4326 (WGS84)**.
3. **Normalize and clean the data** where necessary to ensure consistency and comparability across layers.

### Step 2: Analyzing and Correlating Data
1. Develop a **vulnerability index** using weighted analysis using **“The Analytic Hierarchy Process (AHP)” **:
   - Assign weights to each layer (e.g., flood exposure, population density, poverty).
   - Use **QGIS Raster Calculator** or **Python-based** statistical methods to compute vulnerability scores.
2. **Visualize** the results in QGIS by generating a **vulnerability map**.

### Step 3: Prioritization and Aid Distribution
1. **Incorporate the road network data** to assess accessibility to vulnerable regions.
2. Create a **priority map** combining:
   - Vulnerability scores.
   - Accessibility analysis.
   - Aid already received (if available).
3. The priority map will provide a clear visualization of the areas most in need of aid and relief efforts.

### Step 4: Web-Based GIS Visualization
1. **Deploy the final maps** using **NextGIS** for web-based visualizations.
2. Ensure that all maps are **interactive**


## KPI's

### Technical KPI's:

• Completeness and Accessibility of Data: To ensure 100% integration of all collected data and making accessible to all.

• Automation of Processes: All processes to be automated by backend scripts.

• Real-time Data Usage: Shifting to real-time data from archived data.

• Web App Usage: All processes will be shifted to a web app.

• Faster processing time: To ensure processing time less than 5 minutes.


### Operational KPI's:

• Accuracy: To achieve less than 10% deviation from the ground truth data.

• Aid Coverage: To ensure at least 80% of underserved communities recieved aid.

• Faster Response: To ensure aids delivery is at least 30% faster.

• Usage Extension: To apply similar approaches for other natural or manmade disasters.

