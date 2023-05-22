# pdf-extraction-clinical-reports

This project is created by 2023 Feb intake. 
Consist of two parts: extracting data from existing clinical report and generating sythetic report

## extraction
run extract.ipynb would extract information from clinical reports in the following format and save as .json file n the same directory.
```
{
   "patient_info": {
      "Name": "",
      "Lab No": "",
      "Ext Ref": "",
      "Collected": "",
      "Received": "",
      "Specimen": "t",
      "Requester": "",
      "Referral Lab": "",
      "URN": "",
      "DOB": "",
      "Sex": ""
   },
   "reportable_variants": [
      {
         "ASSUMED ORIGIN": "c",
         "GENE": "",
         "VARIANT": "",
         "VRF (%)": "",
         "CLINICAL SIGNIFICANCE IN AML": ""
      },
      .....
   ]
}
```

## generation
run Generation.ipynb, which would generaten 10 .json in generated_json
then run json_to_pdf will generated cythetic reports in report_word and report_pdf

The three docx files, PeterMac.docx,WEHI.docx and testtemplate.docx are layout templates used for the generation.
```
```
