This program convert column to txt files.
It very useful when you want make text analytics / Sentiment Analysis.
I attached SampleData.txt  that contains fields
Query_ID 
query  - field with text
When program run it create file name according  Query_ID .

How To Run It
Open SAS Enterprise Guide import attach file and load it into SAS Table 
Create new Programs "ConvertRowsToTextFiles"
Copy the code from attach file 
Change code:
When you load to SAS Table by default it created in WORK folder.
I loaded it to DATA.TELCOM_CRM therefore replace all DATA.TELCOM_CRM with your "FOLDER.TABLE_NAME"
Text File path where text file will created  "C:\SasWorkFiles\Telecom\workspace" replace all with your path

If you want to use other data with different columns name
Customer_ID
Customer_Massage

Replace all Query_ID  with Customer_ID

Replace text_field = query 
to 
text_field = Customer_Massage


Now Run It !