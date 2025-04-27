## 5. Install RAS/NAT

This section covers the installation of Remote Access Server (RAS) with Network Address Translation (NAT). This configuration allows computers connected to the Domain Controller (DC) to access the internet while remaining on a private virtual network.

### Installation Steps:

1. In **Server Manager**, select **Add roles and features**
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_hjLh4aCvI4iMCwkqeF.png width=400px>
3. Click **Next** until you reach the server selection screen, verify the correct server, then click **Next**
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_ZfTkjLsZPOiV8TUEEJ.png width=400px>
5. Select **Remote Access**, then click **Next** until you reach the role services selection screen
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_H0nv0d9BKwqqNtH0YA.png width=400px>
7. Select **Routing** - when the popup appears, select **Add Features**
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_0Yo9d2iqH3Q3D7VWLb.png width=400px>
9. Click **Next** until you reach the installation screen, then click **Install** and **Close** when complete
10. Navigate to **Tools > Routing and Remote Access**
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_Y60CJm0p4KMsIIPJvp.png width=400px>
12. Right-click the DC and select **Configure and Enable Routing and Remote Access**
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_bJrkegCdWmtvEzKjvY.png width=400px>
14. Click **Next**, then select **Network address translation (NAT)** and click **Next**
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_hECVkzDNyVPctzmJ1j.png width=400px>
16. Select the **Internet network interface** to use, then click **Next** and **Finish**

    **Note:** If the interface selection is greyed out, close and reopen from the Tools menu
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_gnWYqTpWsD46EggSHp.png width=400px>

### Verification:

Upon successful configuration, the DC icon will change from red to green, indicating that RAS/NAT is properly configured and enabled. changes from red to green, indicating successful configuration

