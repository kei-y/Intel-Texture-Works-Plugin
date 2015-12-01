# ITW-Beta-Test
# Welcome to the Intel&reg; Texture Works Beta Program
It this stage we are seeking your testing and feedback on the first version of the plugin

## Getting Started (Installation)
1. Close Photoshop
2. Download the IntelTextureWorks-beta1.zip file and expand it on your local computer
3. Copy the desired plugin from either of the following unzipped folders
	* IntelTextureWorks-beta1\Plugins\x64\IntelTextureWorks.8bi 
	* IntelTextureWorks-beta1\Plugins\Win32\IntelTextureWorks.8bi
4. Paste the plugin into the appropriate Photoshop Plugin folder
	* D:\Program Files\Adobe Photoshop CC 2014\Required\Plug-Ins\File Formats
	* D:\Program Files\Adobe\Adobe Photoshop CS5 (64 Bit)\Plug-ins\File Formats

## Saving Files via Plugin
### Initiating Plugin "Save As"
1. File > Save As
2. Select "Save as type" -> **Intel&reg; Texture Works (\*.DDS;\*.DDS)**
2. Navigate to store location
3. Assign file name 
4. Save
5. Select desired plugin options and preview (pan/zoom), as necessary
6. Ok

### Loading Files Saved via Plugin
Multiple DDS plugin formats can result in a texture display error on load. To avoid this, use the following process to load your saved BCn textures.
1. File > Open As
2. Select **Intel&reg; Texture Works (\*.DDS;\*.DDS)** as type (to the right of "File name" field)
3. Select file
4. Select desired mipmap loading options if applicable
5. Select desired color profile loading options

### Logging Bugs, Enhancements, & Feedback
Use the [GitHub Issue tracking/labeling system](https://github.com/GameTechDev/ITW-Beta-Test/issues) to log bugs, enhancement (requests), and feedback (general impressions appreciated). **Labels really help here - please use them**.

### NOTE:
* Not all authoring apps can read the latest BCn textures. We're keeping a running list of app load status on the [Wiki here](https://github.com/GameTechDev/ITW-Beta-Test/wiki/BCn-App-Support)
* To implement BCn texture compression in your own apps and engines [download the sample source code here](https://software.intel.com/en-us/articles/fast-ispc-texture-compressor-update)
