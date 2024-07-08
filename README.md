# OnesandZeros_Patima
The Patima application is a project that aimed to restore headless Sri Lankan Buddha Statues, using Generative AI, along with Image Segmentation and Detection AI algorithms. The final product is a Java based Android Mobile Application for end users, and Angular based Admin panel for admin operations. The system will be hosted with Django and MySQL

<h2>Project Deliverables</h2>

<table>
    <tr>
        <th>Project Deliverable</th>
        <th>Covering Functional Req. Number according to EC04 document</th>
        <th>Github Link</th>
        <th>Direct Link</th>
    </tr>
    <tr>
        <td>01. Statue Segmentation Model</td>
        <td>02</td>
        <td><a href="https://github.com/MalinduLiyanage/Buddha_Statue_Segmentation_UNet">Github Link</a></td>
        <td>n/A</td>
    </tr>
    <tr>
        <td>02. Statue Inpainting Model</td>
        <td>01</td>
        <td colspan="2">Under Construction</td>
    </tr>
    <tr>
        <td>03.01 (a) Mobile Application - Cloud Hosted MySQL DB<sup>*</sup></td>
        <td>03, 04, 05, 09, 10, 15, 16, 19, 20, 21, 22</td>
        <td><a href="https://github.com/MalinduLiyanage/Patima_App_Android_Java_YOLOv8_Django">Github Link</a></td>
        <td><a href="https://drive.google.com/file/d/1lvfxl2ISOv-3XA_s27Sfw0QS35n5d30P/view?usp=sharing">Get APK</a></td>
    </tr>
    <tr>
        <td>03.01 (b) Mobile Application - Local SQLite DB<sup>*</sup></td>
        <td>03, 04, 05, 06, 07, 08, 09, 10, 11, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26<sup>**</sup></td>
        <td><a href="https://github.com/MalinduLiyanage/Patima_App_Android_Java_YOLOv8_SQLite">Github Link</a></td>
        <td><a href="https://drive.google.com/file/d/12Yp2csMxbBSmyxkSDktquSzNP9YOmjnn/view?usp=sharing">Get APK</a></td>
    </tr>
    <tr>
        <td>03.02 Admin Panel + Server</td>
        <td>06, 07, 08, 11, 12, 13, 14, 17, 18, 23, 24, 25, 26</td>
        <td><a href="https://github.com/DumiduPramith/patima-backend-django">Github Link</a></td>
        <td><a href="http://140.238.225.128/admin/login">Goto Admin Panel</a></td>
    </tr>
    <tr>
        <td>04. Technical Report</td>
        <td colspan="3">Future Work</td>
    </tr>
</table>

<p style="font-style: italic;"><sup>*</sup> - The Android App is same in these two repos. The only difference is, one is hosted in the cloud server as we planned, and one is working by local SQLite DB. When you are checking for Functional and Non - Functial Requirements for the Mobile Application, if you experience problems, please feel free to choose in between. The admin panel is only affected to the Cloud hosted app, not for the app with local DB.</p><br>
<p style="font-style: italic;"><sup>**</sup> - The App based on the Local Database has all Functional Requirements related to App itself and server side, since it is not relying on a cloud server.</p>

<h2>Sample Data</h2>

<table>
    <tr>
        <th>User Type</th>
        <th>Username</th>
        <th>Password</th>
    </tr>
    <tr>
        <td>General Public</td>
        <td>thush455@gmail.com</td>
        <td>password</td>
    </tr>
    <tr>
        <td>Archaeologist</td>
        <td>hasi878@gmail.com</td>
        <td>password</td>
    </tr>
    <tr>
        <td>Admin</td>
        <td>admin@gmail.com</td>
        <td>password</td>
    </tr>
</table>

<p style="font-style: italic;">Dummy data are also inserted to these logins. Please download the App and use these credentials to see these data. For the Admin Panel, use the given info to login.</p>

<h2>Team - Ones and Zeros</h2>

<table>
    <tr>
        <th>Member</th>
    </tr>
    <tr>
        <td>Malindu Liyanage</td>
    </tr>
    <tr>
        <td>Dumidu Pramith</td>
    </tr>
    <tr>
        <td>Deeshaka Wijewickrama</td>
    </tr>
    <tr>
        <td>Poornima Dissanayake</td>
    </tr>
</table>

<p style="font-style: italic;">This is the final year project for:<br>Dept. of Computing,<br>Faculty of Applied Sciences,<br>Rajarata University of Sri Lanka<br>Year - 19/20 (2024)</p>
