XAMPP is a free and open-source cross-platform web server solution that includes Apache, MySQL (MariaDB), PHP, and Perl. 
Here are the steps to set it up on Windows:
*************************************************************************************************************************
### **Step 1: Download XAMPP**
1. Visit the official XAMPP website: [https://www.apachefriends.org](https://www.apachefriends.org)
2. Click on the **"Download"** button for your operating system (Windows, Linux, or macOS).
3. Select the latest version with PHP compatibility that suits your needs.

### **Step 2: Install XAMPP**
1. Run the downloaded **XAMPP installer (.exe)** file.
2. If you get a **User Account Control (UAC) warning**, click **Yes**.
3. The **Setup Wizard** will open; click **Next**.
4. Choose the components you want to install (by default, all are selected).
   - Essential components: **Apache, MySQL, PHP**
5. Select the installation folder (default: `C:\xampp`).
6. Click **Next** and then **Install**.
7. Wait for the installation to complete and then click **Finish**.

### **Step 3: Start the XAMPP Control Panel**
1. Open **XAMPP Control Panel** from the Start menu or the installation directory.
2. Click **Start** next to:
   - **Apache** (for the web server)
   - **MySQL** (for the database server)
3. The status should turn **green**, indicating that the services are running.

### **Step 4: Verify Installation**
1. Open a web browser and type:
   
   http://localhost/

   - If XAMPP is working correctly, you should see the XAMPP dashboard.
2. To check **PHPMyAdmin** (MySQL database management), visit:
  
   http://localhost/phpmyadmin/


### **Step 5: Configure XAMPP (If Needed)**
- To **change the MySQL password**, go to `phpMyAdmin > User Accounts > Edit Privileges`.
- To **change the Apache port**, edit `httpd.conf` in `C:\xampp\apache\conf\` and modify the `Listen` directive (e.g., `Listen 8080`).

### **Step 6: Create a Project**
1. Navigate to `C:\xampp\htdocs\` (this is the web server's root directory).
2. Create a new folder (e.g., `myproject`).
3. Place your PHP files inside it (e.g., `index.php`).
4. Open a browser and access:

   http://localhost/myproject/
  

Now, XAMPP is successfully set up and ready for local web development. 🚀
***************************************************************************************************
Then setup the project run environment
*****************************************************************************************************
Hostel Management Systen Using PHP and MySQL
Installation Steps(Configuration)
1. Download and Unzip the file on your local system.
2. Put this file inside xampp/htdocs/ .
3. Database Configuration
Open phpmyadmin
Create Database hostel.
Import database hostel.sql
Open Your browser put inside browser “http://localhost/hostel/”
Login Details
To Login as admin put inside browser “http://localhost/hostel”
****************************************************************************************************
Login Details for admin : admin/Test@1234
Login Details for user : test@gmail.com/Test@123
*****************************************************************************************************
