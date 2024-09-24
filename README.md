# Google-Earth-Engine
Applications with Google Earth Engine


## Applications
While I have many projects with Google Earth Engine, I don't have any applications build. Here I started to produce several applications for my workflow. The first 2 applications are very novice in methodology and programming. The application in in 'Update" category is a more advance application and will be used as a guide for other projects to convert in.

### Projected
-  Continue Updating **Aerosols Examiner** Tool (as this becomes a template for other plan sensing systems)
	-  Add Download Section
 	-  Add Charts Section
 	-  Add Point Extraction Explorer
  	-  Improve Legend and Palette  
  - Apps
  	- Soils
   	- Fire Delineations
    - Hydrological Delinations
    - Topography (Update: Topographic Terrain Inspection Tool)   
### Update
- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/surface-wetland-visualization-tool-v10a) **Surface Wetland Visualization Tool v1.0a**: Google Earth Engine app the tries to evaulate surface wetland or watered region over dense vegetation. This app uses Landsat 9 and 3DEP elevaton date from the United States Geological Survey (USGS) and allows the user to select the region, select the start month and end month, select the year, and adjust a threshold (alots better evalation on flat plains) to estimate a surface wetland evaluation. Remember this is based on sensor data pickup from the LandSat 9 Operational Land Imager 2 (OLI-2). This app is considered a guide and no definite conclusions should be formulated by its results. It is created with an intention to generated a download of the region drawn (pending implimentation).
	- Please allow time for image processing and a smaller footprint might result in better surface wetland returns. **Future Implimentations:** Algorithm on loose vegetation and download image option. Additional research will test the validity of the app's returns.
	- **UPLOAD** Version 1.0a
		- Creation and Testing.


- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/aerosols-examiner-v10c) **Aerosols Examiner v1.0b**: My first complex and advance application. Here 3 datasets are available to be queried over a designated region. The application is currently in testing mode and more modifcations and appendations are required.
 	- **FIXES** Version 1.0c:
  		- Fix the Null Value through statistic reduction
    		- MAJOR ISSUE: MERRA Systems will require a hard code min/max values for all bands (and correct scale value)
 		- Grab Image Stats for Visualization
 		- PENDING: MEERA System Image Stats (Defaults to coded defaults)
 	- **FIXES** Version 1.0b:
  		- Layer name
		- Modifying Panel Text Info
		- Fixing Pop-Up Text Info
	- **UPLOAD** Version 1.0a
		- Testing Version for complex code.
  
### Active
- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/political-country-selection) **Political Country Selection**: Application Allows the Download of various global database political administrative boundaries. Data libraries are from different sources and will be cited. 
	- (HPSCU) - High Precision Single Country Unstandardized[1][a] 
	- (HPSCGS) - High Precision Single Country Globally Standardized[1][a] 
	- (SSCU) - Simplified Single Country Unstandardized[1][a]
	- (SSCGS) - Simplified Single Country Globally Standardized[1][a]
	- (CGAZ) - Comprehensive Global Administrative Zones.[1][a]
	- Author's: [Github](https://github.com/wmgeolab/geoBoundaries)
 	- NOTE: Requires Minor updates to App
  		- Format Subpanel

- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/topographic-inspector)  **Topographic Terrain Inspection Tool**: from the Tagee repository allowing to  produce derivatives of elevation models, here the application takes in GLO30 [3] from the ESA Copernicus system, the FABDEM (Forest and Buildings Removed GLO30) [3], or the USGS 3DEP [4] Model.  
	- Author's [Github](https://github.com/zecojls/tagee), [Literature](https://www.mdpi.com/2220-9964/9/6/400)
 	- European Space Agency's Copernicus Programme [3]
  	- United States Geological Survey 3DEP [4]
  	- NOTE: Requires major update to the App
  		- Improvements on processing
  		- Error Checks
  		- Download Option
  	 	- Format Subpanel

## Remote Sensing Projects 
- Pending Information: Section to be updated and citation needed.

## Citations
[1] Runfola D, Anderson A, Baier H, Crittenden M, Dowker E, Fuhrig S, et al. (2020) geoBoundaries: A global database of political administrative boundaries. PLoS ONE 15(4): e0231866. https://doi.org/10.1371/journal.pone.0231866

[2] Safanelli, J.L.; Poppiel, R.R.; Ruiz, L.F.C.; Bonfatti, B.R.; Mello, F.A.O.; Rizzo, R.; Demattê, J.A.M. Terrain Analysis in Google Earth Engine: A Method Adapted for High-Performance Global-Scale Analysis. ISPRS Int. J. Geo-Inf. 2020, 9, 400. DOI: https://doi.org/10.3390/ijgi9060400

[3] Copernicus Digital Elevation Model (DEM). Accessed on 2023-12-12 from https://spacedata.copernicus.eu/collections/copernicus-digital-elevation-model.

[4] U.S. Geological Survey (USGS) 3D Elevation Program (3DEP). Accessed on 2023-12-12 

## Licenses
[a] Individual data files in the geoBoundaries database are governed by the license or licenses identified within the metadata for each respective boundary and are all variants of partially or completely open licenses. All referenced licenses can be read in their entirety here. Computer code and derivative works generated by the geoBoundaries project are released under the Attribution 4.0 International (CC BY 4.0) license


