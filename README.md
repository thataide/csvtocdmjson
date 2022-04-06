# Common Data Model generator
 This application converts a Common Data Model (CDM) definition from CSV to JSON
 
 Defining a new data model using CSV (or Excel) is a user friendly experience. The application will then convert the model defined to a set of CDM compliant JSON files, which can be leveraged on data services that support CDM such as Azure Data Factory, Azure Synapse and Power BI.

Step 1: Define CDM in bin/cdmdefinition.csv using the format [entity],[attribute],[datatype]

Step 2: Execute, results will be shown on screen and output JSON files will be in bin/output

Step 3: Use files to instanciate data model in your chosen data service.

The YouTube video below shows you how to leverage the CDM definition files to perform data ingestion:
[![Click here](https://i9.ytimg.com/vi/eZa2HCrpb7k/maxresdefault.jpg?time=1649278500000&sqp=CKT8t5IG&rs=AOn4CLBYDiTkm2WxR9U1dfdafCs3oqYqZQ)](https://studio.youtube.com/video/eZa2HCrpb7k)

