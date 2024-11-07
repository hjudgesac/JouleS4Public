1. Access your S/4HANA Cloud System and launch the **Communication Arrangements** application.</br>
   ![postboosters4](1.jpg)
   
2. Confirm that Communication Arrangements with Scenario ID **SAP_COM_0647** and **SAP_COM_0882** are automatically added by the Joule booster.</br>
   ![postboosters4](2.jpg)
   
3. Click the Communication Arrangement with Scenario ID **SAP_COM_0647** and validate the configuration.  Note that **Exposure Role Selection** is set to **ALL**.</br>
**NOTE**: For more information on this setting, refer to the [help guide](https://help.sap.com/docs/SAP_S4HANA_CLOUD/4fc8d03390c342da8a60f8ee387bca1a/4efaa144b2864db3b49db54242581620.html?locale=de-DEversion=2208.503&version=2408.VAL)
![postboosters4](3.jpg).

4. Launch the **Communication Systems** application.
![postboosters4](4.jpg)

5. Confirm that 4 new Communication Systems are created by the booster.  The System ID and System Names will have cryptic values.</br>
![postboosters4](5.jpg)

6. Under Communication Systems, select the communication system with the name **CUSTOMER_SAP_COM_0193**.  This system should already be available in your S/4HANA Cloud system.</br>
![postboosters4](6.jpg)

7. Click the **Edit** button.</br>
![postboosters4](7.jpg)

8. Under **Users for Inbount Communication**, click **+** button.
![postboosters4](8.jpg)

9. Click **New User** button.</br>
![postboosters4](9.jpg)

10. Specify and **UserName** and **Description** of your choice.  Either type your own password or use the **Propose Password** button to let the system generate a password.  Make a note of the **UserName** and **Password** as this will be required later for SAP Cloud Identity Provisioning setup.  Click the **Create** button.</br>
![postboosters4](10.jpg)

11. Click **OK**.</br>
![postboosters4](11.jpg)

12. Confirm that the user you just created is listed under the **Users for Inbound Communication** area and click **Save**.</br>
![postboosters4](12.jpg)