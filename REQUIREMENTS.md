# LifePulse
## Requirements Document

### 1. Elicitation Techniques Used

 1. ***Interviews***
    - Conducted with patients (users) and doctors to understand their needs.
    - **Summary of Findings:**
      - Patients want continuous monitoring of vital signs and real-time access to their health data.  
      - Doctors need accurate, specific, and historical data to monitor patients remotely.  
      - Both groups emphasized data privacy, system reliability, and ease of use.  
      - Users want their health data to be displayed as charts and ro recieve summary reports.
      - Doctors highlighted the importance of timely alerts and AI-assisted analysis.  

 2. ***Brainstorming Sessions***
    - Conducted with all team members to identify all possible features and system functions that aligns with the       user's needs.
    - **Summary of Findings:**
      - Integration of IoT devices for automated data collection.  
      - AI algorithms for anomaly detection and health predictions.  
      - A shared dashboard with role-based access (Patient, Doctor, Admin).  
      - Secure cloud storage and backup for all health data.  
      - Cross-platform accessibility (web and mobile).  



### 2. Raw Requirements List

The following requirements were collected through team brainstorming sessions and interviews. They represent      the initial, unfiltered expectations and needs for the system.

  - The system shall allow users to create and manage accounts securely.
  - The system shall allow role-based access for patients, doctors, and admins.
  - The system shall allow doctors to view their patients’ health data.
  - The system shall allow users to input their personal and medical information.
  - The system shall enable the collection of health data from IoT sensors, including heart rate, oxygen level, and blood pressure. 
  - The system shall also allow users to enter health data manually if sensors are unavailable.
  - The system shall store all collected data securely in a cloud-based database.
  - The system shall continuously synchronize and update data from connected devices.
  - The system shall visualize health data through graphs, charts, and indicators.
  - The system shall display real-time health readings on the dashboard.
  - The system shall use AI algorithms to analyze collected data and detect anomalies. 
  - The system shall generate health insights or recommendations based on analyzed data.
  - The system shall notify users and doctors immediately when abnormal readings are detected.
  - The system shall keep a history of all health data for long-term tracking.
  - The system shall allow users to view data over multiple time periods (daily, weekly, monthly).
  - The system shall enable doctors to generate summary health reports for their patients.
  - The system shall allow users to download or export their health reports. 
  - The system shall send alerts and notifications via email, SMS, or push notifications.
  - The system shall timestamp all collected readings for accuracy and tracking. 
  - The system shall ensure that only authorized doctors can access patient data.
  - The system shall protect all data using encryption and secure login protocols.
  - The system shall reconnect automatically to IoT devices if the connection is lost. 
  - The system shall allow administrators to manage and update system configurations. 
  - The system shall log all alerts, readings, and user actions for auditing purposes. 
  - The system shall provide a user-friendly interface that is simple and accessible.
  - The dashboard shall be compatible with both desktop and mobile devices. 
  - The system shall be responsive and capable of handling multiple users simultaneously. 
  - The system shall support scalability to add more sensors or users in the future.
  - The system shall process and display new readings within a few seconds. 
  - The system shall allow users to filter and compare their health data.
  - The system shall use color indicators to represent safe and critical health conditions.
  - The system shall maintain a minimum uptime of 99% during operation. 
  - The system shall back up all data regularly to prevent data loss. 
  - The system shall include help or tutorial sections to guide new users. 
  - The system shall record feedback from users for future development. 
  - The system shall allow family members or caregivers to receive notifications if authorized by the user.
  - The system shall ensure all data visualizations are updated automatically with every new reading.
  - The system shall allow doctors to compare multiple patients’ health data trends.
  - The system shall comply with health data privacy and security standards.
  - The system shall provide logs and notifications for system errors or device malfunctions.   
  - The system shall use the HTTPS protocol to secure all communications. 
  - The system shall allow users to register using a valid email address and password. 
  - The system shall require authentication before granting access to the dashboard. 
  - The system shall validate user credentials securely and prevent unauthorized access.  
  - The system shall allow users to reset their password securely via email verification. 



### 3. Classified Requirements
 - All requirements are classified according to:
   
   1. **Type**
    - Functional Requirements (FR): Define what the system does, basically the system's core operations and behaviors.
    - Non-Functional Requirements (NFR): Define how the system performs, its constraints and attributes.
  
   2. **Level**
    - System Requirements (SR): Technical details that explain how the system will meet users' requirements.
    - User Requirements (UR): Focuses on what users expect from the system, e.g. patients and doctors.

   
 - Classified Requirements
    - Assigned IDs based on the requirement type:
      - FR-U = Functional Requirement (User)
      - FR-S = Functional Requirement (System)
      - NFR-U = Non-Functional Requirement (User)
      - NFR-S = Non-Functional Requirement (System)

 
### User Functional/ System Functional Requirements
| ID | Requirement Description |
|------|--------------------------|
| FR-U-01 | Allow doctors to view their patients' health data. |
| FR-U-02 | Allow users to input personal and medical information. |
| FR-U-03 | Visualize health data through graphs, charts, and indicators. |
| FR-U-04 | Display real-time health readings on the dashboard. |
| FR-U-05 | Allow users to view data over multiple time periods (daily, weekly, monthly). |
| FR-U-06 | Enable doctors to generate summary health reports for their patient. |
| FR-U-07 | Provide a user-friendly interface that is simple and accessible. |
| FR-U-08 | Allow family members or caregivers to receive notifications if authorized by the user. |
| FR-U-09 | Allow doctors to compare multiple patients' health data trends. |
| FR-U-10 | User color indicators to represent safe or critical conditions. |
| FR-U-11 | Include help or tutorial section to guide users. |
| FR-S-01 | Allow users to create and manage accounts securely. |
| FR-S-02 | Support main roles: patient, doctor, and admin. |
| FR-S-03 | Generate health insights or recommendations based on analyzed data. |
| FR-S-04 | Notify users and doctors immediately when abnormal readings are detected. |
| FR-S-05 | Keep a history of all health data for long-term tracking. |
| FR-S-06 | Send alerts and notfications via email, SMS, or push notifications. |
| FR-S-07 | Ensure only authorized doctors can access patient data. |
| FR-S-08 | Ensure all data visualizations are updated automatically with every new reading. |


### User Non-Functional/ System Non-Functional Requirements
| ID | Requirement Description |
|------|--------------------------|
| NFR-U-01 | Accessible through web browser and mobile devices. |
| NFR-U-02 | Provide an intuitive and easy to navigate interface for users. |
| NFR-S-01 | Encrypt all personal health data during storage and transmission. |
| NFR-S-02 | Display real-time data updates with minimal delay (no more than 2 seconds). |
| NFR-S-03 | Comply with health data privacy and security standards. |
| NFR-S-04 | Automatically back up health data every 24 hours. |
| NFR-S-05 | Ensure system uptime of at least 99% per month. |




### 4. Structured Specification


### 5. Prioritized Requirements
| Requirement | Priority | Reason |
|-------------|----------|--------|
| User can create, manage, and delete accounts securely. | M | Core functionaliy; without user accounts, the system cannot operate. |
| Role-based access: Patient, Doctor, and Admin. | M | Essential for system security and differentiating functionalites. |
| Authentication required before dashboard access. | M | Prevents unauthorized access; critical for privacy and security compliance. |
| Only authorized doctors can access patient data. | M | Ensure patient privacy; required by health data regulations. |
| Adminstrators can manage system configurations. | N | Helpful for maintainability and scalability but not critical at launch. |
| collect health data from IoT sensors (heart rate, BP, oxygen level). | M | Core functionality; system depends on real-time data collection.|
| Allow manual data input if sensors are unavailable. | M | Ensures system works for users without sensors; critical for usability. |
| Timestamp all collected readings. | M | Necessary for accuracy and specification of tracked health data. |
| REconnect automatically to IoT devices if disconnected. | N | Improves reliability but not critical for MVP. |
| Store data securely in cloud-based database. | M | Core requirement for centralized monitoring and long-term tracking. |
| Maintain historical health data. | M | Supports longitudinal analysis and reporting; key goal of the system. |
| Log alerts, readings and user actions for auditing. | N | Helps in compliance and debugging; not immediately critical. |

