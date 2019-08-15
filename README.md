# IndoorGML2CityGML_PSExtension
Conversion IndoorGML public safety extension to CityGML public safety ADE with Hale studio

## Getting Started
The following tool is required to conversion IndoorGML PS extension to CityGML PS ADE:
* [Hale Studio 3.5](https://www.wetransform.to/downloads/)

## Processing step for conversion
0) Install Hale Studio 3.5 and run it
1) Make a new alignment project 
2) Import a source schema (IndoorGML Public Safety Extension, indoorgmlpsextention.xsd)
3) Import a target schema (CityGML Public Safety Extension, ADE-PublicSafety-ver03_1_2.xsd)
4) Import an alignment (IndoorToCityGML_PSExtension.xml in this repository)
5) Import a source data
6) Export a transformed data
    * Select a XML (Custom root element)
    * Select a destination file for the export
    * Select a "CityModel (http://www.opengis.net/citygml/2.0)"
    * Push a "Finish" button
        * Unify winding order should be no changes
        * If you want to look human-readable XML, check to Pretty print XML. 
