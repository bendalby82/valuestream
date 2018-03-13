# Value Stream Mapping Tool
A pure client-side web site to quickly generate value stream maps. Tested on Chrome 60.0.3112.101 running on Mac.
[![](https://github.com/bendalby82/valuestream/blob/master/docs/example-value-stream-map.png)](https://bendalby82.github.io/valuestream/)   
Published to [https://bendalby82.github.io/valuestream/](https://bendalby82.github.io/valuestream/)  
## Usage Notes  
1. Set the box color to any valid hex value, and the font box to a suitable web value  
2. Use the 'Tab' key to step through the table. When you leave the final cell in the final row, a new row will be added  
3. The 'Value Stream as Code' textbox will be dynamically updated as you change the table  
4. The 'Value Stream as Code' textbox can also be edited directly - this reverses the flow so that table will update to reflect your changes when you leave the textbox
5. 'Save as PNG' will open a new tab with a 'Save As' dialog for a PNG version of the Value Stream Map 
## Future  
1. Migrate to Raphaël to generate cross-browser images  
2. Specify 'width' of map, with digram 'wrapping' to a new line after 'x' boxes  
3. Compare map to previous map, and indicate trends  
4. Break image generation out into headless service, so that diagrams can be generated via an API  
## Licensing
Value Stream Mapping Tool is freely distributed under the [MIT License](https://opensource.org/licenses/MIT). See LICENSE for details.  

## Contribution
Create a fork of the project into your own reposity. Make all your necessary changes and create a pull request with a description on what was added or removed and details explaining the changes in lines of code. If approved, project owners will merge it.  
  
## Support  
Please file bugs and feature requests on the Github issues page for this project. This is to help keep track and document everything related to this repo. The code and documentation are released with no warranties or SLAs and are intended to be supported through a community driven process.  

