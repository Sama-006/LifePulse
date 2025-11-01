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
| FR-U-01 | Users can create and manage accounts securely. |
| FR-U-02 | Users register using a valid email and password, with secure reset via email verification. |
| FR-U-03 | Users can input personal and medical information. |
| FR-U-04 | Users can enter health data manually if sensors are unavailable. |
| FR-U-05 | Users can view data over multiple time periods (daily, weekly, monthly). |
| FR-U-06 | Users can filter and compare their health data by date range or metric. |
| FR-U-07 | Allow authorized family members or caregivers to receive notifications. |
| FR-U-08 | Users can download or export their health reports. |
| FR-U-09 | Users can submit feedback for improvements. |
| FR-U-10 | Users can view AI generated health insights. |
| FR-S-01 | Role-based access control enforces permissions for each user type. |
| FR-S-02 | Support main roles: patient, doctor, and admin. |
| FR-S-03 | Administrators can manage users and update system configurations. |
| FR-S-04 | Health data is collected from IoT sensors (heart rate, oxygen level, blood pressure). |
| FR-S-05 | Automatic reconnection occurs if IoT devices lose connection. |
| FR-S-06 | All readings are timestamped for traceability. |
| FR-S-07 | AI algorithms analyze health data to detect anomalies. |
| FR-S-08 | The system generates alerts and recommendations based on analysis results. |
| FR-S-09 | Immediate notifications are sent to users and doctors when abnormal readings are detected. |
| FR-S-10 | Alerts are delivered via email, SMS, or push notifications. |
| FR-S-11 | Real-time health readings are displayed on the dashboard. |
| FR-S-12 | Health data is visualized using color-coded graphs and charts to indicate safe and critical conditions. |
| FR-S-13 | Historical data is stored for long-term monitoring. |
| FR-S-14 | Doctors can compare multiple patients' data trends. |
| FR-S-15 | System automatically refreshes dashboard data with each new reading. |
| FR-S-16 | Doctors can generate summary health reports. |
| FR-S-17 | All alerts, readings, and actions are logged for auditing. |



### User Non-Functional/ System Non-Functional Requirements
| ID | Requirement Description |
|------|--------------------------|
| NFR-U-01 | Interface is clear, intuitive, and simple to navigate. |
| NFR-U-02 | Dashboard adapts responsively to both web and mobile platforms. |
| NFR-U-03 | Includes help and tutorials sections for first-time users. |
| NFR-U-04 | Accessibility options support users with visual or physical impairments. |
| NFR-U-05 | Key tasks (view data, check alerts) should be completed in ≤3 steps. |
| NFR-U-06 | Dashboard uses clear color codes to indicate safe vs critical health readings. |
| NFR-S-01 | Encrypt all personal health data during storage and transmission. |
| NFR-S-02 | Display real-time data updates with minimal delay (within 5 seconds). |
| NFR-S-03 | System complies with healthcare data privacy standards. |
| NFR-S-04 | Automatically back up health data every 24 hours to prevent data loss. |
| NFR-S-05 | Ensure system uptime of at least 99% during operation. |
| NFR-S-06 | System remains responsive and can handle multiple users simultaneously. |
| NFR-S-07 | Provides logs and notifications for system errors or device malfunctions. |
| NFR-S-08 | Uses HTTPS protocol to secure all communications. |
| NFR-S-09 | Only authorized doctors can access patient data. |
| NFR-S-10 | System supports scalability to accommodate additional users, data volume, and sensors. |




### 4. Structured Specification


### 5. Prioritized Requirements
| Requirement | Priority | Justification |
|-------------|----------|--------|
| User can create, manage, and delete accounts securely. | M | Core functionality; without user accounts, the system cannot operate. |
| Role-based access: Patient, Doctor, and Admin. | M | Essential for system security and role differentiation. |
| Authentication required before dashboard access. | M | Prevents unauthorized access; critical for privacy and data protection. |
| Only authorized doctors can access patient data. | M | Ensure patient confidentiality; required by healthcare privacy standards. |
| Administrators can manage system configurations. | N | Useful for maintainability and scalability but not critical at launch. |
| Collect health data from IoT sensors (heart rate, blood pressure, oxygen level). | M | Core functionality; system depends on real-time health data collection.|
| Allow manual data input if sensors are unavailable. | M | Ensures accessibility for users without connected devices. |
| Timestamp all collected readings. | M | Required for data accuracy and traceabiltiy. |
| Reconnect automatically to IoT devices if disconnected. | N | Improves reliability; can be added after MVP. |
| Store data securely in cloud-based database. | M | Core requirement for centralized monitoring and long-term tracking. |
| Maintain historical health data. | M | Supports longitudinal analysis and reporting; key goal of the system. |
| Log alerts, readings and user actions for auditing. | N | Helps in compliance and debugging; not critical initially. |
| Backup all data regularly. | N | Important for risk management; can be implemented later. |
| Use AI to analyze data and detect anomalies. | M | Core differentiator; enables early health insights. |
| Generate health insights/recommendations based on data. | M | Directly supports decision-making; central to system's purpose. |
| Enable doctors to compare multiple patients' health trends. | N | Valuable for advanced functionality; not essential for MVP. |
| Process and display new readings within seconds. | M | Ensures real-time monitoring performance. |
| Visualize data via charts, graphs, and color indicators. | M | Supports easy understanding of health data; essential for dashboard. |
| Filter, compare, and view data over multiple periods. | N | Enhances usability; not mandatory for intial release. |
| Automatically update visualizations. | M | Required for real-time display accuracy. |
| User-friendly interface, mobile, and desktop compatilble | M | Critical for accessibility and user adoption. |
| Notify user and doctors immediately for abnormal readings. | M | critical safety feature; directly impacts health outcomes. |
| Send alerts via email, SMS, or push notifications. | N | Adds convenience; initial version can focus on one channel. |
| User HTTPS and encryption to secure data transimission. | M | Required for privacy, security, and compliance standards. |
| Protect all data with secure login and encryption. | M | Core security requirement; mandatory for sensitive health data. |
| Maintain system uptime of at least 99%. | N | Operational goal; important for reliability but can be optimized over time. |
| Include help/tutorial sections. | S | Helpful for new users; not critical. |
| Record user feedback for future development. | S | Useful for improvement; not necessary for launch. |
| Allow authorized family or caregiver receive notifications. | N | Enhances usability for dependent users; secondary feature. |
| Provide logs and notifications for system errors/device malfunctions. | N | Improves maintainability; not critical for core operation. |
| Support scalability for additional sensors or users | N | Important for future growth; not essential for prototype phase. |
