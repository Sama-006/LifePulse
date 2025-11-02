# Requirement Validation and Risk Analysis

## 1. Validation Approach
####  Requirement validation makes sure all recorded requirements truly reflect what stakeholders want, can be realistically implemented, and align with the system’s objectives.

  -  Methods Employed in Requirement Validation:
      -  Team Review
      -  Test-Case Validation
      -  Stakeholder Validation (Patients, Doctors)

| Validation Method | Description | Application in LifePulse |
|-------------------|-------------|--------------------------|
| Team Review | Team memebers collectively work together to ensure that all requirements are clear, consitant, and complete. | The requirements were reviewed to avoid/remove duplicates, and to confirm alignment between functional and non-functional requirements. |
| Test Case | The requirements were reviewed to ensure that they are measurable and testable. | For essential features such as login verification, IoT data syncing, and alert creation, early test cases were developed to confirm the testability of the requirements. |
| Stakeholder Validation | Conducted addional validation with end users (patients, doctors) to ensure their expectations and requirements were correctly interpreted. | The stakeholders validated that the AI recommendations, alert notifications, and visualization features met their expectations. Feedback was refined on certain requirements. |

<br><br>

## 2. Identified Risks 
#### During validation, key risks were discovered that could influence how accurately requirements are defined, their overall quality, and the project’s success in implementing them. These risks mainly pertain to areas such as data processing, the practical possibilities of the technology, and how clearly requirements are stated.

| Risk ID |	Risk Description | Impact |	Risk Reduction Plan |
|---------|------------------|--------|---------------------|
| RQ-01 – Data Security and Privacy Risk | Handling of sensitive health data requires strict compliance with privacy regulations and encryption standards. Requirements related to data transmission or storage may be incomplete or unclear in terms of security measures. | Potential data breaches or privacy violations; system non-compliance with healthcare standards. |	Strengthen non-functional requirements to explicitly enforce HTTPS, encryption, and access control policies. Conduct a focused security review before implementation. |
| RQ-02 – Ambiguous User Expectations |	Some requirements based on initial interviews may not fully represent what doctors and patients actually need in real use cases. | Misalignment between system features and user expectations; costly redesigns later.	| Conduct requirement walkthroughs and obtain final stakeholder sign-off before the design phase. |
| RQ-03 – IoT Integration and Data Compatibility Risk	| Variations in IoT device firmware and data formats may cause inconsistencies in readings or synchronization delays. | Data mismatches, unreliable monitoring, or loss of trust in system accuracy.	| Define a standard communication protocol and perform early device testing with simulated sensor data. |
| RQ-04 – AI Model Reliability Risk	| The AI algorithm’s accuracy in detecting health anomalies depends on sufficient, high-quality data. | Inaccurate predictions or false health alerts impacting user confidence. | Include AI validation datasets during testing and periodically retrain the model for improved reliability. |

<br><br>

## 3. Consistency and Completeness Check
#### A systematic validation review was performed to ensure that all requirements are consistent, complete, and feasible. Each category of requirement (functional and non-functional) was examined for overlaps, contradictions, and coverage.

| Validation Aspect | Purpose | Findings | Resolution |
|-------------------|---------|----------|------------|
| Consistency Check |	Ensure no conflicting or redundant requirements exist. | All requirements are aligned and logically consistent. The security-related requirements (e.g., HTTPS, encryption) were refined to ensure consistency across all levels. | Reworded FR-S-18 and NFR-S-08 for consistent description of encryption and HTTPS. |
| Completeness Check | Ensure all required functionalities and qualities are included.| All major user and system functions are covered: login/authentication, IoT integration, AI-based analysis, alerts, reports, and feedback. | Added clarification in feedback and alert-related requirements to ensure user-side completeness. |
| Traceability Check | Confirm that every requirement can be traced to a stakeholder or system goal.| Each requirement can be mapped to one or more project objectives identified during elicitation. | Create a formal traceability matrix in the next phase. |
| Feasibility Check |	Validate that requirements can be implemented with available technology. | All requirements are feasible with current web and IoT tools. No unrealistic expectations found. |	Continue feasibility monitoring during the design phase. |

