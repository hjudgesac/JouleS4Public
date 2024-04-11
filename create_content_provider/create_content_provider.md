## **Create Content Provider in Work Zone**

1. From the Navigation Pane on the left, select **Security >> Users** and click the arrow to open user details.
![create_content_provider](1.jpg)

2. Scroll down to role collections section and click **Additional Details** icon >> **Assign Role Collections**.   
![create_content_provider](2.jpg)   

3. Select the **Launchpad_Admin** and click **Assign Role Collection**.
![create_content_provider](3.jpg) 

5. From the Navigation Pane on the left, select **Instances and Subscriptions***. Click **SAP Build Work Zone, standard edition** to launch the application.   
![create_content_provider](4.jpg) 

6. If prompted to choose the authentication provider, click **Default Identity Provider**.
![create_content_provider](4-1.jpg) 

7. Click **Channel Manager** icon.      
![create_content_provider](5.jpg)  

8. Click **+New**.          
![create_content_provider](6.jpg)

. Add a new content provider using the information below and click **Save**:
  * Title: <-- Title of your choice eg. **SFSF** -->
  * Design-Time Destination: <-- Design time destination created earlier eg. **LPS_SFSF_dt** -->
  * Runtime Destination: <-- Runtime destination creaated by the booster eg. **LPS_SFSF_rt** -->
  * Runtime Destination for Dynamic Data: **Use default runtime destination**                   
**Note**: Make a note of the **ID** that is generated automatically on this screen.  This ID is required when we setup the user provisioning job to SAP Build Work Zone in later steps.                                                                    
![create_content_provider](7.jpg)

9. Confirm the content provider is successfully created.                                       
![create_content_provider](8.jpg)


## **Disable Default Identity Provider**
1. Switch to BTP Cockpit browser tab.
2. From the Navigation Pane on the left, select **Security >> Trust Configuration*** and click the pencil icon next to **Default Identity Provider**.   
![create_content_provider](9.jpg)   

3. Uncheck **Available for User Logon** and click **Save**.         
![run_booster](10.jpg)         
**Note**: This change is made so that user doesn't get prompted to pick an Identity Provider when launching Joule in SuccessFactors.