# imcdb
 Immune Modeling Constants repository
This repo will store biological constants metadata records. 

To enables researchers/modelers to enter their biological constants and related metadata information, we designed a template for the user interface. An example follows in JSON format. 


#
{
  "id": 1,
  "Biological constant symbol": "c1",
  "Biological constant brief description": "expression rate constant for IFNa",
  "models": {
    "type": "ODE",
    "Biological constant Value": 0.0035,
    "Units": "transcripts/min",
    "Source": "moddeling",
    "Submitter" : "Dr. C. Jayaprakash",
    "repository link" : "https://www.ebi.ac.uk/biomodels-main/BIOMD0000000528"
  },
  "GO terms" : []
}
