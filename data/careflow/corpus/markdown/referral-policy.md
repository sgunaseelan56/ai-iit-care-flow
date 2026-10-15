# Referral Management Policy

### Meridian Health Partners — Clinical Operations Policy
**Document ID:** POL-OPS-2024-088  
**Section 3:** Outpatient Referral Management & Specialty Routing Protocols  
**Applicability:** All 14 Meridian Health Partners (MHP) Ambulatory Health Centers  

---

#### 3.1 Policy Purpose and Network Scope
This policy defines mandatory operating standards for the intake, validation, clinical prioritization, and scheduling of patient referrals across all 14 Meridian Health Partners (MHP) ambulatory clinic sites. Central Intake Operations (CIO), ambulatory specialty departments, and primary care medical homes (PCMH) must adhere strictly to these routing workflows.

#### 3.2 Direct Access Specialty Classification
The following specialty services accept direct patient self-referrals or direct non-primary care provider requests without formal primary care clinician sign-off:
*   **3.2.1** Outpatient Behavioral Health & Psychotherapy (adult and pediatric diagnostic evaluations).
*   **3.2.2** Routine Obstetrics and Gynecology (annual preventative screening, prenatal care initiation, contraception management).
*   **3.2.3** General Optometry (routine refraction and non-pathologic screening).
*   **3.2.4** Occupational Health Services (work-related non-emergent injury evaluations and employer fitness-for-duty examinations).

#### 3.3 PCP Sign-Off Specialty Classification
The following subspecialties require an authenticated, documented referral signed by a licensed MHP or contracted primary care physician (MD/DO), physician assistant (PA), or advanced practice registered nurse (APRN) prior to appointment intake:
*   **3.3.1** Cardiology and Interventional Cardiology.
*   **3.3.2** Neurology.
*   **3.3.3** Orthopedic Surgery and Non-Operative Sports Medicine.
*   **3.3.4** Endocrinology and Metabolic Disorders.
*   **3.3.5** Rheumatology.
*   **3.3.6** Gastroenterology and Hepatology.
*   **3.3.7** Medical Oncology and Hematology.
*   **3.3.8** Pulmonology and Critical Care Medicine.

#### 3.4 Primary Care Sign-Off Validation Standards
Referrals routed to specialties identified in clause 3.3 must contain the following minimum electronic health record (EHR) data elements within form MHP-REF-01:
*   **3.4.1** Primary diagnosis code (ICD-10-CM) and secondary contributing clinical factors.
*   **3.4.2** Targeted clinical question or procedure-specific indication.
*   **3.4.3** Relevant diagnostic imaging reports, laboratory values within the trailing 90 calendar days, and current medication reconciliation list.
*   **3.4.4** Verifiable cryptographic or biometric sign-off timestamp from the licensed primary care clinician. Incomplete referrals will be rejected and returned to the ordering clinician within 4 business hours.

#### 3.5 Referral Triage Categories and Service Level Agreements (SLAs)
All inbound referrals accepted by Central Intake Operations must be triaged into one of three operational categories, each governed by an absolute turnaround SLA:
*   **3.5.1 Emergent Referrals (Turnaround SLA: Immediate / 60-Minute Redirection):** Clinical scenarios indicating imminent threat to life, limb, or organ system function (e.g., acute limb ischemia, unstable angina, suspected acute spinal cord compression). Emergent orders bypass standard ambulatory intake. The receiving intake specialist must execute an immediate warm clinical handoff via the dedicated MHP Acute Transfer Line to the designated regional emergency department or urgent specialty receiving unit within 60 minutes of referral receipt.
*   **3.5.2 Urgent Referrals (Turnaround SLA: 24 Hours):** Conditions requiring specialist assessment to avert clinical deterioration, chronic functional loss, or unmanaged severe pain (e.g., severe motor deficits, suspected high-grade endocrine failure, progressive radiculopathy). The initial clinical intake review, payer pre-authorization check, and outbound scheduling contact to the patient must occur within 24 hours of referral transmission. The initial clinic visit must occur within 72 hours of triage completion.
*   **3.5.3 Routine Referrals (Turnaround SLA: 5 Business Days):** Non-rapidly progressive chronic conditions, routine diagnostic evaluations, or initial consultations for non-urgent surgical conditions. Clinical insurance authorization check, intake review, and outreach for appointment scheduling must occur within 5 business days (120 business hours) of receipt. The appointment offer must fall within 21 calendar days of validation.

#### 3.6 SLA Override Authority
Turnaround SLAs may not be modified, downgraded, or extended without explicit, auditable authorization:
*   **3.6.1 Authorized Override Roles:** The only personnel authorized to reclassify a referral to a lower triage category or extend an SLA timeline are:
    *   (a) The Chief Medical Officer (Dr. Evelyn Vance);
    *   (b) The Regional Ambulatory Medical Director (Dr. Marcus O’Shea); or
    *   (c) The designated Specialty Clinic Medical Director responsible for the receiving service line.
*   **3.6.2 Override Documentation Mandate:** The authorizing clinical director must enter an administrative addendum directly into the EHR referral record within 2 hours of modification. The addendum must detail the clinical justification for reclassification, citing specific laboratory, diagnostic, or clinical history markers that confirm the lower acuity.

#### 3.7 Tiered Escalation Ladder for SLA Non-Compliance
If an unassigned or non-scheduled referral approaches an SLA breach, Central Intake Operations and receiving clinic pods must execute the following sequential escalation pathway:
*   **3.7.1 Tier 1 — Central Intake Referral Specialist:** Activated when 50% of the SLA window has elapsed without action (12 hours for Urgent; 2.5 business days for Routine). The Intake Specialist must contact the receiving clinic’s lead scheduler via secure chat and verify document completeness.
*   **3.7.2 Tier 2 — Clinic Intake Supervisory Nurse:** Activated when 75% of the SLA window has elapsed without completed triage (18 hours for Urgent; 3.75 business days for Routine). The Supervisory Nurse must re-evaluate the clinical packet, execute manual insurance clearing if blocked, and reassign the referral queue directly to an available designated provider.
*   **3.7.3 Tier 3 — Ambulatory Practice Operations Manager:** Activated at 100% of SLA elapsed (24 hours for Urgent; 5 business days for Routine). The Practice Operations Manager must adjust clinician clinical slot templates, initiate overbooking protocols within clinic safe-harbor limits, and place a direct telephone call to the patient to confirm the scheduled visit within 2 hours of SLA expiration.
*   **3.7.4 Tier 4 — Regional Ambulatory Medical Director:** Activated if an Urgent referral remains unbooked 4 hours post-SLA breach (28 hours total) or a Routine referral remains unbooked 24 hours post-SLA breach (6 business days total). The Regional Ambulatory Medical Director must arrange external cross-coverage network booking or direct clinical diversion to an emergency or tertiary subspecialty partner within 2 hours of notification.

#### 3.8 Documented Exceptions to the Standard Pathway
Only the three distinct clinical pathways outlined below are exempt from standard primary care pre-authorization sign-off and routing procedures:
*   **3.8.1 Exception 1: Post-Inpatient Discharge Transition Protocol (The 72-Hour Readmission Prevention Pathway):** Patients discharged from an acute inpatient hospital stay within the prior 72 hours who require immediate specialty follow-up (Cardiology, Cardiothoracic Surgery, or Vascular Surgery) do not require a separate PCP sign-off. Specialty intake must be booked directly from the hospital discharge summary packet provided by the inpatient case manager, bypassing routine intake review.
*   **3.8.2 Exception 2: Suspected High-Grade Malignancy Fast-Track Pathway:** Patients presenting with concrete radiologic or histopathologic evidence of malignant disease (e.g., BIRADS-5 breast lesions, computed tomography scans documenting suspicious pulmonary masses >2 cm with spiculation, or verified positive biopsy margins) are exempt from primary care review requirements. Central Intake Operations must bypass routine triage and schedule these patients directly with Medical Oncology or Surgical Oncology within 48 hours of initial imaging/pathology upload.
*   **3.8.3 Exception 3: Direct-to-Procedure Diagnostic Colonoscopy Pathway:** Patients aged 45 to 75 who present with a positive non-invasive fecal immunochemical test (FIT) or positive fecal DNA-marker stool test completed within the prior 45 calendar days are exempt from both PCP sign-off and preliminary specialist office visits. Intake coordinators are authorized to schedule these patients directly into designated endoscopist procedural blocks, provided the patient completes the standard automated telephone nurse pre-procedure sedation clearance questionnaire.
