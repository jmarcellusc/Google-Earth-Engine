# Google-Earth-Engine
Applications with Google Earth Engine

**NOTES:**(9/16/2024) this readme is current being updated. 


## Applications
While I have many projects with Google Earth Engine, I don't have any applications build. Here I started to produce several applications for my workflow. The first 2 applications are very novice in methodology and programming. The application in in 'Update" category is a more advance application and will be used as a guide for other projects to convert in.

### Projected
-  Continue Updating **Aerosols Examiner** Tool (as this becomes a template for other plan sensing systems)
	-  Add Download Section
 	-  Add Charts Section
 	-  Add Point Extraction Explorer
  - Apps
  	- Soils
   	- Fire Delineations
    - Hydrological Delinations
    - Topography (Update: Topographic Terrain Inspection Tool)   
### Update
- **Aerosols Examiner v1.0b**: My first complex and advance application. Here 3 datasets are available to be queried over a designated region. The application is currently in testing mode and more modifcations and appendations are required. 
	- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/aerosols-examiner-v10c)
 	- Version 1.0c Fixes:
  		- Fix the Null Value through statistic reduction
    		- MAJOR ISSUE: MERRA Systems will require a hard code min/max values for all bands (and correct scale value)
 		- Grab Image Stats for Visualization
 		- PENDING: MEERA System Image Stats (Defaults to coded defaults)
 	- Version 1.0b Fixes:
  		- Layer name
    	- Modifying Panel Text Info
      	- Fixing Pop-Up Text Info
    - To Append:
        - Add Statistics Charts
		- Add Implimentation to Skip 100% NULL Region
		- Add Download Option
  		- Improve Legend and Palette   
  
    - 
### Active
- **Political Country Selection**: Application Allows the Download of various global database political administrative boundaries. Data libraries are from different sources and will be cited. 
	- (HPSCU) - High Precision Single Country Unstandardized, 
	- (HPSCGS) - High Precision Single Country Globally Standardized. 
	- (SSCU) - Simplified Single Country Unstandardized.
	- (SSCGS) - Simplified Single Country Globally Standardized.
	- (CGAZ) - Comprehensive Global Administrative Zones.
	- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/political-country-selection) 

- **Topographic Terrain Inspection Tool**: from the Tagee repository allowing to  produce derivatives of elevation models, here the application takes in GLO30 from the ESA Copernicus system, the FABDEM (Forest and Buildings Removed GLO30), or the USGS 3DEP Model. 
	- [Google Earth Engine-App](https://ee-marcelluscampes.projects.earthengine.app/view/topographic-inspector)  

## Remote Sensing Projects 
- Pending Information: Section to be updated and citation needed.
