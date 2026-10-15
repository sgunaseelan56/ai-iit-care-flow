# Patient Intake and Triage Standard Operating Procedure

**MERIDIAN HEALTH PARTNERS**  
**STANDARD OPERATING PROCEDURE: CLINICAL INTAKE AND SCHEDULING**  
**DOCUMENT ID:** SOP-OPS-412-REV4  
**EFFECTIVE DATE:** 14 MARCH 2026  
**OWNER:** Office of Clinical Operations (Dr. Aris Thorne, Operations Policy Lead)  

---

### 1. PURPOSE AND SCOPE
1.1 This Standard Operating Procedure governs the intake, data capture, triage banding, and record creation for all patient contacts across all 14 Meridian Health Partners outpatient facilities.  
1.2 Compliance with this document is mandatory for all Patient Access Representatives (PARs), Triage Nurses, and Front Desk Coordinators.  

### 2. MANDATORY FIELDS ON FIRST CONTACT
2.1 During any initial inbound communication (telephone, web portal, or walk-in), the intake staff member must capture and input the following 10 mandatory data points into the Meridian Electronic Health Record (EHR) system prior to call termination or registration completion:  
&nbsp;&nbsp;&nbsp;&nbsp;a. Full legal first, middle, and last name (Field ID: `PT_NAME_FULL`).  
&nbsp;&nbsp;&nbsp;&nbsp;b. Date of birth in DD/MM/YYYY format (`PT_DOB`).  
&nbsp;&nbsp;&nbsp;&nbsp;c. Primary residential physical address, including postal code (`PT_ADDR_PHYS`).  
&nbsp;&nbsp;&nbsp;&nbsp;d. Primary working telephone number (`PT_TEL_PRIM`).  
&nbsp;&nbsp;&nbsp;&nbsp;e. Secondary or emergency contact name and telephone number (`PT_EMER_CONT`).  
&nbsp;&nbsp;&nbsp;&nbsp;f. Biological sex and gender identity (`PT_SEX_GND`).  
&nbsp;&nbsp;&nbsp;&nbsp;g. Primary spoken and written language (`PT_LANG_PREF`).  
&nbsp;&nbsp;&nbsp;&nbsp;h. Chief complaint or reason for visit in patient’s own words, minimum 15 characters (`CLIN_CHIEF_COMP`).  
&nbsp;&nbsp;&nbsp;&nbsp;i. Primary insurance carrier name and policy/identification number (`FIN_INS_ID`), subject to Section 4 exceptions.  
&nbsp;&nbsp;&nbsp;&nbsp;j. Referring provider NPI (if applicable; otherwise record "Self-Referral" with intake staff ID) (`REF_NPI`).  

### 3. URGENCY BANDING SCHEME AND TARGET RESPONSE TIMES
3.1 Intake staff and triage nurses shall assign an urgency band based strictly on clinical presentation and the presence of specific trigger phrases uttered by the patient or caregiver.  
3.2 The four urgency bands, their mandatory trigger phrases, and the strict operational target first-response times are defined as follows:  

| Urgency Band | Target First-Response Time | Mandatory Trigger Phrases (Exact or Clinical Equivalent) |
| :--- | :--- | :--- |
| **Emergent** | Immediate (Live transfer to clinical staff or dispatch EMS within 90 seconds) | "Chest pain", "sudden weakness on one side", "difficulty breathing", "suicidal intent with plan", "uncontrolled hemorrhage", "sudden loss of vision", "severe allergic reaction/anaphylaxis". |
| **Urgent** | Within 2 Hours | "High fever over 39.4C", "severe acute pain rated 8 out of 10 or higher", "minor head injury with confusion", "vomiting blood", "sudden inability to pass urine", "suspected fracture with visible deformity". |
| **Priority** | Within 24 Business Hours | "Sub-acute worsening of chronic condition", "medication refill running out in less than 48 hours", "moderate persistent pain rated 4 to 7", "post-operative wound redness or discharge", "new lump or mass requiring diagnostic workup". |
| **Routine** | Within 72 Business Hours | "Annual wellness exam", "routine medication review", "stable chronic disease follow-up", "form completion/physicals", "preventive screening request", "mild symptoms lasting more than 14 days without acute change". |

3.3 If a patient uses multiple trigger phrases spanning different bands, the intake staff shall default to the higher (more urgent) band.

### 4. HANDLING PATIENTS WHO DECLINE TO PROVIDE INSURANCE ID
4.1 If a patient or guarantor refuses or is unable to provide their primary insurance identification number (`FIN_INS_ID`) at first contact, the PAR shall execute the following protocol without exception:  
&nbsp;&nbsp;&nbsp;&nbsp;a. **First Notice:** Inform the patient clearly: *"Meridian Health Partners requires insurance information to process claims. Without this, you will be categorized as a self-pay patient for this encounter."*  
&nbsp;&nbsp;&nbsp;&nbsp;b. **Documentation:** If the patient persists in declining, the PAR must select the checkbox `DECLINED_INSURANCE_FLAG` in the EHR and enter the exact phrase in the notes field: *"Patient declined to provide insurance details pursuant to SOP-OPS-412 Section 4."*  
&nbsp;&nbsp;&nbsp;&nbsp;c. **Self-Pay Conversion:** The account shall be automatically designated as **Self-Pay Self-Governance** and subject to the Meridian Standard Outpatient Fee Schedule (Document FIN-SCH-88).  
&nbsp;&nbsp;&nbsp;&nbsp;d. **Financial Counseling Referral:** The PAR must generate an automated task to the Financial Counseling Department (Supervisor: Marcus Vance, Extension 4402) within 15 minutes of call completion. The financial counselor shall contact the patient within 24 business hours to discuss payment options, sliding-scale eligibility, or upfront deposit requirements.  
&nbsp;&nbsp;&nbsp;&nbsp;e. **Exception:** No patient assigned an **Emergent** or **Urgent** urgency band under Section 3 shall be delayed, rescheduled, or denied care due to a refusal or inability to provide insurance details. Financial clearance for urgent/emergent cases is strictly deferred until clinical stabilization.  

### 5. RECORD-KEEPING REQUIREMENTS
5.1 Every intake encounter must generate a permanent electronic audit log within the Meridian EHR.  
5.2 The complete intake record, including audio recordings of telephone interactions (where legally permitted and consented), EHR data entry timestamps, assigned urgency band, and PAR identification number, must be retained in active storage for a minimum of ten (10) years from the date of the last encounter for adult patients, and until the patient reaches the age of twenty-eight (28) for minor patients.  
5.3 Under no circumstances shall intake data be recorded on physical paper logs, sticky notes, or unencrypted local drives. Any temporary scratchpad notes taken during intake must be cross-cut shredded immediately upon entry into the EHR.  
5.4 Monthly compliance audits of 5% of all intake records across all 14 sites shall be conducted by the Quality Assurance Division to verify adherence to mandatory fields, correct urgency banding, and proper execution of the insurance-decline protocol.
