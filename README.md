# Google-Earth-Engine
Applications with Google Earth Engine


## Applications
To streamline my workflow, I've begun creating a suite of applications. The initial two applications were relatively basic in terms of methodology and programming. However, the application currently in the "Update" category represents a more advanced approach and will serve as a template for converting other projects into applications

### NEW
- October 2024
	- Soils Visualization (in-Progress v1.0d)

### Projected
- Continue Updating **Soils Visualization** Tool (Template Candidate)
	- Add Slope and Aspect Binning
 	- Corrections to v1.1a Binning Issues
	- Add USDA NCSS Reference Datasets
	- Add Passcode System
	- Add Downloader System Menu
-  Continue Updating **Aerosols Examiner** Tool (Template Candidate)
	-  Add Download Section
 	-  Add Charts Section
 	-  Add Point Extraction Explorer
  	-  Improve Legend and Palette  
  - Apps
   	- Fire Delineations
    - Hydrological Delinations
    - Topography (Update: Topographic Terrain Inspection Tool)   
### Update
- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/soils-exploratory-tool-in-progress-v11a) **Soils Visualization Tool (in-Progress) v1.1a**: This Google Earth Engine application is designed to show various properties of soils on a selected region. It will have two or more reference datasets (known as references) with binning applications such as elevation products and derivatives. The current datasets are the following: Soil Grids 250m v2.0 from the International Soil Reference and Information Centre (ISRIC) and the Soil Properties 800m from the USDA Natural Resources Conservation Service.  The tool (or app) is in working progress and will be consistenly updated.
	- **FIXES** Version 1.0d
 		- Updated: Disclaimer Information
		- Updated: Categorical Legends
  		- Updated: Password Implimentation
  		- Updated: Menu System
  		- Updated: USDA Reference Datasets
  		- Updated: Color Palettes (All Datasets)
	- **FIXES** Version 1.0c
 		- Updated Legend System
   		- Updated Citation System Menu
     	- Updated Menu System
     	- Update Reset System
	- **FIXES** Version 1.0b
		- Updated Imagery Crop
		- Updated Multiple Queue Product Selection
		- Update Menu System
 	- **UPLOAD** Version 1.0a

- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/wetlands-exploratory-tool-in-progress-v10b) **Surface Wetland Visualization Tool v1.0a**: This Google Earth Engine application is designed to identify surface wetlands or irrigated areas within dense vegetation. Using Landsat 9 imagery and 3DEP elevation data from the USGS, it allows users to select a region, specify a time frame (start and end months, year), and adjust a threshold (particularly useful for flat plains) to estimate surface wetland extent.
	- Please note: This application is based on Landsat 9 OLI-2 sensor data and should be considered a tool for preliminary analysis. Definite conclusions should not be drawn solely from its results. Future development includes the ability to download the selected region's data.
	- Please allow time for image processing and a smaller footprint might result in better surface wetland returns.
 	- **Future Implimentations:** Algorithm on loose vegetation and download image option. Additional research will test the validity of the app's returns.
  	- **FIXES** Version 1.0b
  		- Updated: Disclaimer Information
  		- Updated: Passcode Implimentation
	- **UPLOAD** Version 1.0a
		- Creation and Testing.


- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/aerosols-examiner-sensing-tool-v10d) **Aerosols Examiner v1.0d**: My first complex and advance application. Here 3 datasets are available to be queried over a designated region. The application is currently in testing mode and more modifcations and appendations are required.
	- **FIXES** Version 1.0d:
 		- Version Date Corrected
   		- Format Change
     	- ADD: Histograms (Testing; Issue is the number of returns on screen)
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


