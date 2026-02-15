# Cell Data Viewer
## About
This web tool allows anyone to make more out of the CSV files collected by the CellMapper, G-MoN Pro and Tower Collector applications.

It is currently available at: [https://cdv.nerdtech.one](https://cdv.nerdtech.one)

![Cell Data Viewer main screenshot](/assets/documentation/imgs/Screenshot-Main.png)

This web tool lets you view, filter and export the data points you have collected with the CellMapper, G-MoN Pro and Tower Collector applications on your Android device.

### Filters
You can filter hundreds or thousands of data points to be able to focus only on what you actually care about. Available filters include PLMN, network type (LTE and NR), Band, Frequency, (e/g)NodeB (site ID) and cell ID. You can apply filters at once or only a few depending on what you want. Additionally, you can search the filter options to quickly find what you are looking for.

![Cell Data Viewer filters screenshot](/assets/documentation/imgs/Screenshot-Filters.png)

### Visualization
You can visualize the data points that you have collected with the CellMapper and G-MoN Pro applications on a map. You can see each collected data point in detail with information rich tooltips and popups.

![Cell Data Viewer popup screenshot](/assets/documentation/imgs/Screenshot-Popup.png)

### Export
You like what you see on the map. Then you can go ahead and export the map as an HTML file to preserve the currently displayed data points to look at them again later or for sharing with others.

![Cell Data Viewer export screenshot](/assets/documentation/imgs/Screenshot-Export.png)

### Local in browser processing
All processing of the data happens on your device in the browser. The CSV files you select to view, filter and export are not uploaded to any server. The location permission is optional and only used to center the map based on your location. Your location is not shared with anyone!

## FAQ
Some frequently asked questions and answers about the Cell Data Viewer project can be found in the Wiki section of this repository: [Cell Data Viewer Wiki](https://github.com/NerdTech-aut/Cell-Data-Viewer/wiki)

## Third-party software and services
The following third-party software and services are used in this project:
- [Bootstrap](https://getbootstrap.com/) and [Bootstrap Icons](https://icons.getbootstrap.com/) from the [Bootstrap team](https://getbootstrap.com/docs/5.3/about/team/) and contributors under [MIT license](https://github.com/twbs/bootstrap/blob/main/LICENSE)
- [Leaflet](https://leafletjs.com/) from [Volodymyr Agafonkin](https://agafonkin.com/) and contributors under [BSD 2-Clause License](https://github.com/Leaflet/Leaflet/blob/main/LICENSE)
- [OpenStreetMap](https://www.openstreetmap.org/about) from the [OpenStreetMap Foundation](https://osmfoundation.org/) and contributors
- Satellite images by [ESRI](https://www.esri.com/en-us/home) and partners
- my own [arfcn-to-frequency-files](https://github.com/NerdTech-aut/arfcn-to-frequency-files) repository based on ETSI and 3GPP documents
- [jsDelivr](https://www.jsdelivr.com/) CDN service for external resources from Volentio JSD Limited
- [GitHub Pages](https://docs.github.com/en/pages) for the hosting of the web tool and directly associated resources from GitHub Inc

## Disclaimers
CellMapper and CellMapper logo are trademarks of CellMapper Services Limited  
Android, Google and their respective logos are trademarks of Google LLC  
NerdTech and the Cell Data Viewer project are not affiliated with any of these companies.  
NerdTech and the Cell Data Viewer project are not affiliated with any other developers unless explicitly stated.  
Any recommendations for third party software are because I (as in NerdTech) use them and think they are worth sharing in the scope of this project. Please inform yourself about the data collection and data sharing policies of any third-party software.
