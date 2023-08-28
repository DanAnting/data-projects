# Data Projects
The majority of my data projects were completed in my 16 month co-op at Cenovus Energy. During this work term I learned how to utilize programming languages like Python and R to conduct exploratory data analysis and automate data ingestion through ETL processes.

## Chemical Reporting Program
This project involved the automation of a data ingestion pipeline to error check vendor chemical data and matching corresponding oil production, BFW, produced water, and raw water volumes. The pipeline loaded the vendor data as well as production volumes to an Oracle instance. There, views are generated to grab the latest data per production month, facility and other metrics. Calulations of metrics were also done in the Oracle views. Metrics include chemical cost, chemical consumption, and their respective ratios to production as well as PPM. 

The outcome of this data project provided visiblity and tranparency to the chemical programs for Lloydminster Thermal. This allows the chemical process management team to track historcal dosages, act opportunistically on low-hanging fruit, and ultimtely, reduce chemical expenditures - reducing OPEX.

## SAP & Salesforce Data Quality
The purpose of this project was to email daily errors found between SAP and Salesforce interfaces. It was found that work orders that were changed in the internal SAP system did not always update the Salesforce interface (vendor and contractor use). By setting up a daily pipeline to script data pulls, the error checks of all the work orders for that day can be compared and the errors can be reported. The SAP-Salesforce erros are written to an Oracle instance for BUs to use as KPIs of error checking. Furthermore, the functionality of automated emails were used in this project rather than a dashboard. This eliminates the reliance on TIBCO Spotfire, or PowerBI servers, and simply rely on STMP which is more reliable.

The outcome of this project allowed the business units in Lloyminster to immediately rectify any changes made in Salesforce to match the SAP work order details.