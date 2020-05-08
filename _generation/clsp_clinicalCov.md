---
title: Clinical Data Management
last_modified_at: 2018-10-30
main_authors: Rachel Galbraith
primary_reviewers: Rachierizz
---
Whether you need clinical data for a prospective or observational study or need to be able to identify suitable biospecimens associated with a cohort (either available via collaboration with other researchers or via a specimen repository), it is critical to enable the generation of large-scale data sets associated with patient phenotypes.  On this page we describe what data management systems are available to consortium researchers. 

## Medical Record Data from the University of Washington
A feed of commonly desired medical record data from the University of Washington (Caradigm Intelligence Platform, often referred to as "Amalga") is covered by the HIDRA IRB. Data elments for our cancer patient population seen within the UWMC system (which is prescribed by a combination of encounter and diagnosis codes and includes patients seen at UWMC, SCCA, Harborview, and NWMC) are updated either daily or biweekly and include information such as demographics, lab values, encounters, diagnosis codes, radiation oncology, and a variety of unstructured radiology, pathology, and clinical narrative reports.

## Manually Abstracted Data in Caisis
[Caisis](http://www.caisis.org/) is an open source data management platform in use by [STTR](http://www.sttrcancer.org/) to facilitate data abstraction and programmatic resources to support translational research. Abstraction of data into Caisis is covered by the HIDRA IRB and does not require program-specific IRBs until the data is being requested out for research purposes. Caisis is centered around individual patients and helps create a story about their clinical experiences and health status at various times in the course of their treatment at UW Medicine or SCCA. Data entered into Caisis builds upon the discrete data elements available through the Hutch Data Repository. Approximately 30 fields from that data repository are fed directly into Caisis, along with a linkage to SEER data which pulls in death dates when available. Abstracted data elements are recorded in discrete fields, per data dictionaries which are set up by consensus by multiple members of each program. Wherever possible, data elements are standardized across disease programs, enabling data sharing across programs and larger research questions to be answered in the future. All data in Caisis is audited (real-time auditing is performed on at least 10% of patients entered for each program). To view fields and disease-specific data dictionaries, see the [Fred Hutch Ontology Browser](https://ontology.fredhutch.org).


Currently, there are 12 programs with data abstracted into Caisis:
- Brain
- Breast
- Colorectal
- Head & Neck
- Lung
- Liver
- Lymphoma
- Myeloma
- Pancreas
- Prostate
- Sarcoma
- Thyroid
- Leukemia

Many of these have ongoing abstraction. STTR contracts with abstractors through a company called Vasta Global at a cost of $24,000 per abstractor per year. Each group selects and prioritizes the patients for which they would like data abstracted, supplying the abstractors with an updated list on a regular basis. Please note, the contract with Vasta Global only allows them to access the UW/SCCA medical records, not those from outside institutions. The data abstracted into Caisis is available to any interested Consortium investigator, with valid IRB approval or for activities preparatory to research.

## Data Requests
To request data from the Hutch Data Repository, investigators or research coordinators need to fill in the data request form available [here](https://cdsweb07.fhcrc.org/redcap/surveys/?s=WM3CAN33YY). The data request form and instructions can also be found [here](https://extranet.fredhutch.org/en/u/hdc.html). Requests for data can be made for the purposes of research, preparatory for research, operations, quality assurance/quality improvement and clinical care. For research projects, IRB documentation will be requested to verify whether the requestor should be granted access to the requested data.  Requests for identified data in support of preparatory to research activities will be reviewed for potential documentation requirements, such as a confidentiality pledge.

The [Fred Hutch Ontology Browser](https://ontology.fredhutch.org) can be a useful tool in developing data requests as it will help researchers understand how, when and in what format each data element is collected. 
>**Tip:** Before submitting a request, use the Ontology Browser to create an Excel file/csv containing your fields of interest that are already in existence then that file can be uploaded within the data request form.

### Detailed Instructions

1.	If you have access to Centernet, search for and select “HDC Request for Data Services” or go to Centernet page [here.](https://centernet.fredhutch.org/cn/f/hdc/lcex/hdc-data-services.html) If you do not have access to Centernet [go here](https://centernet.fredhutch.org/cn/u/hdc.html) and select “HDC Request for Data Services.”
2.  This page will provide an FAQ, instructions and related documents or forms which may need to be downloaded. 
3.  Select the box “Complete User Access Request VIA REDCap” to open access to the electronic submission form.
4. 	Broadly describe the request. If you are requesting CAISIS data from an STTR supported group (Lymphoma, Myeloma, etc) then you can  select “Yes” to the STTR question. This just means someone on the STTR team will help with identifying the data from our data dictionary.
5.	PHI: Select whether you need identified data or de-identified data
6.	Identify how you intend to use the data, whether for research (or activities preparatory to research), clinical care, etc.
7.	Include the IRB number related to this work. If requested, include the IRB number related to this work. You can search CORE FYI to find the appropriate IRB number.
8.	Confidentiality pledges are no longer required as per a change in Washington State law.
9. The form does not require specific data fields to be selected. You may write in specific data fields, or broadly describe what you want. To request specific fields found within Caisis, you may refer to the existing fields listed in the Fred Hutch Ontology Browser under CAISIS [here](https://translationalgenomics.shinyapps.io/FHOntologyBrowser/). The submission form does NOT link to the Ontology Browser.
10. For the question related to the HDC PHI Data Training Verification, you can get more information [here.](https://centernet.fredhutch.org/cn/f/hdc/lcex/hdc-training.html)
11. If you wish to submit a list of MRN's to identify specific individuals for whom you want data, the request form allows you to upload the list, Excel format perferred.  Password protect all files with identifiable data, including lists of MRNs; the submission form will ask you to provide the password.
12. That’s it! A data analyst from the Hutch Data Core will contact you to discuss the specifics, including how to share identifiable data.

## STTR REDCap Template
In partnership with Fred Hutch Core Data Services, STTR has created a REDCap template which is available to any Fred Hutch investigator. The template provides an opportunity for groups who are interested in abstracting their own patient/participant data (either for a specific study group, or from an outside medical institution). The template includes the fields which are common across programmatic data dictionaries and allows each group to tailor the data collection to their own needs and timeline.

Whether or not a REDCap should be spun up will depend on what the investigator is intending to use the Caisis data for. If investigators will be adding their own data elements (from a survey or additional data abstraction) then spinning up a new REDCap project for their study makes sense. If investigators will be working directly with the data and performing their data cleaning and analysis, then the data should be distributed by depositing it into the investigator's Secure storage. 

There are three primary scenarios where the template may be especially useful:
A group would like to start with existing Caisis data: they could make a data request that would populate the REDCap template and the group would then have an easy interface for entering additional study-specific data.

A group would like to begin data abstraction and wants the benefits of standardized data elements, but does not want to go through the formal process of beginning abstraction into Caisis: the STTR REDCap template will allow groups to being abstraction using common data elements and standards which enable sharing of data across research groups – if a group would like to follow a specific data dictionary, they can request the STTR REDCap template and then modify the interface to match the disease program data dictionary as found in the [Fred Hutch Ontology Browser](https://ontology.fredhutch.org)

If a group starts abstraction using REDCap, but would like to contribute the data back to the institutional database in Caisis at a later date: When the group has finished their data entry into REDCap for their specific project, STTR will provide auditing services to determine the accuracy of the entered data and, if it passes our threshold, we can push the data into Caisis.  

If your team has questions about Caisis, the STTR REDCap template, or data abstraction, please reach out to us by emailing `STTRCancer`.


## Additional Resources
- [REDCap](https://projectredcap.org): REDCap projects are flexible and secure ways to capture multiple types of data, including clinical covariates. REDCap includes version-control and access-restriction features. Fred Hutch has its [own instance](http://research.fhcrc.org/cds/en/redcap.html) of REDCap and offers many [training opportunities](http://research.fhcrc.org/cds/en/redcap-training.html) to support researchers.
