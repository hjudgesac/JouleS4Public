## Check S/4 Cloud Destinations setup in BTP Subaccount
1. Access your S/4HANA Cloud System and launch the **Communication Arrangements** application.</br>
   ![postboosters4](1.jpg)  
2. Confirm that Communication Arrangements with Scenario ID **SAP_COM_0647** and **SAP_COM_0882** are automatically added by the Joule booster.</br>
   ![postboosters4](2.jpg)
3. Click the Communication Arrangement with Scenario ID **SAP_COM_0647** and validate the configuration.  Note that **Exposure Role Selection** is set to **ALL**.</br>
![postboosters4](3.jpg)
4. Launch the **Communication Systems** Application.
![postboosters4](4.jpg)
5. Confirm that 4 new Communication Systems are created by the booster.  The System ID and System Names will have cryptic values.
![postboosters4](5.jpg)
## Check Content Provider in SAP Build Work Zone
**NOTE**: The Joule booster automatically creates a content provider for S/4HANA Cloud in SAP Build Work Zone using the Runtime and Designtime destinations mentioned above.
1. From the Navigation Pane in BTP Cockpit, select **Security >> Users** and click the arrow to open user details.</br>
**NOTE**: Make sure to select SAP Cloud Identity User.  User from Default Identity Provider should not be used.</br>
![postboosters4](2-1.jpg)

2. Click **Assign Role Collections**.</br> 
