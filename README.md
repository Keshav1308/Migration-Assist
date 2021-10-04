# [Azure Sentinel Hackathon 2021]Migration-Assist

Migrating Splunk to sentinel is a bit tedious and complex process. In most of the environment Splunk is stable and running for more than 5-6 years. While doing the migration expectation is to make Azure Sentinel work the way Splunk works.

During initial phase, there will be incident comparison. SOC team will be expecting similar number of incidents generated in the Splunk.

Lot of time we need to migrate the Splunk use cases to Azure Sentinel Incident Rules. After the migration we need to make sure that both the tools are generating same number of the incidents and collecting same amount of data. This involve finetuning.

During finetuning we need to compare the incident generated in the Splunk as well as the incidents generated in the Azure Sentinel.

Idea here is to create workbooks that can do the comparison of the data and help migrating team in completing the finetuning. 
Workbook will project the number of Incident generated in Splunk per Endpoint, Datatype, etc and number of incident generated in Azure Sentinel for same endpoint and datatype.

What it does
----------------------

This will have workbooks that will :-

Compare the incidents generated in the Splunk and incident generated in the Azure Sentinel.
Compare the amount of data collected for each data type in Azure Sentinel as well in Splunk.
Number of incident generated for each Entity.
Number of incident generated for each Datatype.
