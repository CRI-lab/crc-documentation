---
title: Mangaging Data with UID Tool
description: Information About UID Tool for Data Cataloging
author: Skyler Kimura
---

- Records are the information that represents the datasets in the UID Tool. There is no data or datasets stored inside the UID Tool, so no data will or official metadata will be modified. 
- For any further explaination on the record fields, please refer to [record curation guide](/crc-documentation/data-management/uid-tool/guides/record-curation)

## <a href="https://coastal5.soest.hawaii.edu/uid-tool/data/" target="_blank">Querying Records</a>

![UID Tool](../../../../../assets/uid-tool/uid-tool-15.png)

- As you move through each field on the Filter Form, the record table will update automatically.
- You do not need to click the Search button or hit enter
    - You just need to click off the field in order for the record form to update

### Filter by record name
![Step 1 screenshot](https://images.tango.us/workflows/7c62f4ed-48f1-4ed0-91d7-117698440824/steps/67c89559-07f2-45e5-b3bf-38e6f7f2b792/dd297fdd-98ba-4ea3-b512-923d46a9f3ad.png?crop=focalpoint&fit=crop&fp-x=0.0834&fp-y=0.1779&fp-z=2.2450&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=29&mark-y=296&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zOTImaD01OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

- In the 'Dataset Name' field, you can enter a word or partial word. The filter will display all datasets whose names contain the exact word or partial word you entered, anywhere within the title of the dataset.
- Ex. you type 'sales,' it will show all datasets with names like 'sales_data,' 'monthly_sales,' etc. 

### Filter records by creation date
![Date Filter Fields](../../../../../assets/uid-tool/uid-tool-17.png)
![Filter Calendar Screenshot](../../../../../assets/uid-tool/uid-tool-18.png)

- From Date:
    - The date selected will filter out any data created after the specified date
    - Ex. You select 10/11/2023, it will show all records that have been created after 10/11/2023 12:00 AM
- To Date:
    - The date selected with filter out any data created before but **not including** the specified date
    - Ex. You select 11/3/2023, it will show all records that have been created before 11/3/2023 12:00 AM

### Filter records by creator
![Step 4 screenshot](https://images.tango.us/workflows/7c62f4ed-48f1-4ed0-91d7-117698440824/steps/9873c6e9-7e74-4607-a8f8-1e967f2bdf90/c3ef68d8-f48f-46a0-973a-b1fcccf2e656.png?crop=focalpoint&fit=crop&fp-x=0.0834&fp-y=0.3557&fp-z=2.2450&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=29&mark-y=378&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zOTImaD01OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

- Select the email of the creator who created the record
- Ex. You select skyler8@hawaii.edu, it will show all record created by the user skyler8@hawaii.edu


### Filter records by storage location type
![Step 5 screenshot](https://images.tango.us/workflows/7c62f4ed-48f1-4ed0-91d7-117698440824/steps/7e415dd5-5c48-4595-9a91-4065c7d002af/f80b6dc8-4620-4a8f-8fda-eea69d01bf2c.png?crop=focalpoint&fit=crop&fp-x=0.0834&fp-y=0.4150&fp-z=2.2450&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=29&mark-y=378&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zOTImaD01OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

- The only three data location types are:
    - Locally Stored
    - Coastal6
    - Other
- See [records curation guide](/crc-documentation/data-management/uid-tool/guides/record-curation/) for details on each data location type
- Ex. You select coastal6, then the table will display all data stored on coastal6

### Filter records if indicated as published on Zenodo
![Step 6 screenshot](https://images.tango.us/workflows/7c62f4ed-48f1-4ed0-91d7-117698440824/steps/5f789c34-0632-4400-8e89-e20b0589bc07/91b10bf4-dcd7-4339-984e-6c4611e825a9.png?crop=focalpoint&fit=crop&fp-x=0.0834&fp-y=0.4743&fp-z=2.2450&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=29&mark-y=378&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zOTImaD01OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

- If yes, show records that are published on Zenodo
- If no, show records that are not published on Zenodo
- If left on placeholder (Is it published on Zenodo), shows data that is both published and not published


### Filter records by associated project
![Step 7 screenshot](https://images.tango.us/workflows/7c62f4ed-48f1-4ed0-91d7-117698440824/steps/498de66b-a60b-479d-ae68-01530f56abb0/786a77bc-248b-40ff-8d1c-7b2fbba9c287.png?crop=focalpoint&fit=crop&fp-x=0.0834&fp-y=0.5336&fp-z=2.2450&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=29&mark-y=378&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zOTImaD01OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

- Filter all records based on project 1 and project 2 fields even if you are not part of the project
- Select the project that the record is associated with

### Filter records by CRC UID
![Step 8 screenshot](https://images.tango.us/workflows/7c62f4ed-48f1-4ed0-91d7-117698440824/steps/a3c3ecdd-f6ac-4537-bf85-92411ed2a917/2edd13f6-3cd9-4f96-b8ab-03084bc82618.png?crop=focalpoint&fit=crop&fp-x=0.0834&fp-y=0.5929&fp-z=2.2450&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=29&mark-y=378&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zOTImaD01OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

- A CRC UID is a unique identifier that will be utilized to keep track of CRC associated data
- The UID can be inputted into this field to search for data based on its CRC UID
- Ex. CRC20231024001GDTS
- Format of the UID: CRCYYYYMMDD000XXYY
    - CRC: Identifies that this ID is associated to CRC
    - YYYY: Year that the record for the data has been created
    - MM: Month taht the record for the data has been created
    - DD: Date that the record for the data has been created
    - 000: ID of the record stored within the database
    - XX: Primary Project
    - YY: Secondary Project


### Search button on to submit query
![Step 10 screenshot](https://images.tango.us/workflows/7c62f4ed-48f1-4ed0-91d7-117698440824/steps/8e13515e-0b5e-40b5-a85d-e2e6a3d34c46/ee167c56-a788-45a9-8b49-fd0c11cc4fa9.png?crop=focalpoint&fit=crop&fp-x=0.1324&fp-y=0.6364&fp-z=2.8881&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=379&mark-y=370&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNjAmaD03NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

- Doesn't have any actual functionality
- Only exists as decoration for the filter form

### Clear filter form and query data
![Step 11 screenshot](https://images.tango.us/workflows/7c62f4ed-48f1-4ed0-91d7-117698440824/steps/76d257eb-e4d0-49d5-af27-960a7bec0906/5a13d82d-c459-4a8d-ad80-528732d9b5de.png?crop=focalpoint&fit=crop&fp-x=0.0308&fp-y=0.6364&fp-z=2.9393&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=38&mark-y=369&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNDImaD03NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

- Clear current filters applied to record table
- After clearing, the record table will return back to the table that we started with

<br/>

## Exporting Records to CSV
- Button is located at the top left record table page of the UID Tool
![Full Page](../../../../../assets/uid-tool/uid-tool-19.png)
![Export to CSV](../../../../../assets/uid-tool/uid-tool-11.png)
- **Filter before exporting**
    - Only the information for the record that are filtered and displayed on the table will be exported
<br/>
- Click the button to get a file directory dialog prompt to save the file on your hard drive
![File Directory Dialog](../../../../../assets/uid-tool/uid-tool-12.png)
- Save the output.csv in your desired location

---

## <a href="https://coastal5.soest.hawaii.edu/uid-tool/data/update/" target="_blank">Updating Records</a>
**Must be logged in to update data**

### How to Update Record
![Update Record Table](../../../../../assets/uid-tool/uid-tool-13.png)
- Note: You can only update records from the project that you are assigned. If you do not see a record that you want to change, you are most likely not assigned the project
- If you need access to another projects records, refer back to [accessing uid tool guide](/crc-documentation/data-management/uid-tool/guides/accessing) for instructions on how to get project assignment

### Update Record Form
![Update Record Form](../../../../../assets/uid-tool/uid-tool-14.png)
For more details on the fields checkout the [data curation guide](/crc-documentation/data-management/uid-tool/guides/updating-data)<br>
If needed, you can edit the fields below:
- Dataset name
- Storage medium type that the dataset is stored in
- Specific location that the dataset is stored<br>If the storage medium has been changed, please follow the format explained in [data curation guide](/crc-documentation/data-management/uid-tool/guides/updating-data) for location field
- Description of the dataset
- If the dataset has been moved to Invenio<br>Most likely will not be unchecked because data should stay in Invenio
