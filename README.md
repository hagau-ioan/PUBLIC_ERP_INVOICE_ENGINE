# PUBLIC_ERP_INVOICE_ENGINE - Python Project.

Program to read invoices and to extract required information and upload the data to ERP system with automatically login, upload process.

# What was done.

 - We have 100 invoices which need to be processed (some data need to be extracted from these invoices).
 - These data are saved into generated xls file.
 - Next step is to login and to upload the processed data into the ERP system by handling different screen forms inside the ERP.
 - Each error during all the steps mentioned above are triggered and will inform the client.
 - Screen shoots are generated for each ERP step. Client will be able to track down, visualy, the process steps and also to debug some error cases.
 - Each xls file containing the final results of the ERP process steps and the invoices processed data will be archived.
 - Thread system is implemented to monitor the work in progress and to force an emergency exit in case the app got stucked (which should never happen. :) ) 
 - Print feature: special feature support to print each invoice according to their execution order, this business logic is handled on a different thread.

# Screens.

##### CLI interface to show the processed steps ERP INVOICE ENGINE.
![alt text](https://roomwizard.hagau.ro/erp-invoice-screens/cmd-resized.png)

##### Code sample and additional info regarding the ERP INVOICE ENGINE.
![alt text](https://roomwizard.hagau.ro/erp-invoice-screens/code.png)
