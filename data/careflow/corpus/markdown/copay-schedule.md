# Co-payment and Cost-Share Schedule

**MERIDIAN HEALTH PARTNERS**  
**OPERATIONS POLICY MANUAL**  
**POLICY REF:** MHP-FIN-804-CS  
**SUBJECT:** 2025 Comprehensive Cost-Share Schedule and Claims Adjudication Rules  
**EFFECTIVE DATE:** January 1, 2025  
**OWNER:** Revenue Cycle & Claims Operations (Director: Thomas Vance)  

---

### 1. PURPOSE AND SCOPE

**1.1** This policy establishes the official annual cost-share schedules, co-pay tiers, deductible thresholds, and coinsurance rates for all four Meridian Health Partners commercial and administrative benefit plans.  
**1.2** The figures mandated in this document are hardcoded into the Meridian Claims Adjudication Engine (CAE) and shall supersede any verbal or unwritten representations.  
**1.3** This policy applies to all 14 Meridian multi-specialty outpatient clinic sites, centralized billing operations, and patient access centers.

---

### 2. PLAN COST-SHARE SCHEDULES

#### 2.1 MERIDIAN-GOLD
* **Annual Deductible:** $500.00  
* **Coinsurance Rate:** 20% (applied to allowable charges after deductible is met)  
* **Out-of-Pocket Maximum:** $25,000.00  
* **Specialist Visit Co-Pay:** $25.00  
* **Telehealth Visit Co-Pay:** $10.00 *(Exact mathematical relation: exactly 40 percent of the in-person specialist co-pay)*  
* **Imaging Co-Pay (Separate):** $75.00  
* **Lab Work Co-Pay (Separate):** $15.00  

#### 2.2 MERIDIAN-SILVER
* **Annual Deductible:** $1,500.00  
* **Coinsurance Rate:** 30% (applied to allowable charges after deductible is met)  
* **Out-of-Pocket Maximum:** $15,000.00  
* **Specialist Visit Co-Pay:** $45.00  
* **Telehealth Visit Co-Pay:** $18.00 *(Exact mathematical relation: exactly 40 percent of the in-person specialist co-pay)*  
* **Imaging Co-Pay (Separate):** $150.00  
* **Lab Work Co-Pay (Separate):** $30.00  

#### 2.3 MERIDIAN-BRONZE
* **Annual Deductible:** $3,000.00  
* **Coinsurance Rate:** 40% (applied to allowable charges after deductible is met)  
* **Out-of-Pocket Maximum:** $8,000.00  
* **Specialist Visit Co-Pay:** $45.00  
* **Telehealth Visit Co-Pay:** $18.00 *(Exact mathematical relation: exactly 40 percent of the in-person specialist co-pay)*  
* **Imaging Co-Pay (Separate):** $250.00  
* **Lab Work Co-Pay (Separate):** $50.00  

#### 2.4 CIVIC-BASE
* **Annual Deductible:** $2,000.00  
* **Coinsurance Rate:** 35% (applied to allowable charges after deductible is met)  
* **Out-of-Pocket Maximum:** $10,000.00  
* **Specialist Visit Co-Pay:** $45.00  
* **Telehealth Visit Co-Pay:** $18.00 *(Exact mathematical relation: exactly 40 percent of the in-person specialist co-pay)*  
* **Imaging Co-Pay (Separate):** $200.00  
* **Lab Work Co-Pay (Separate):** $40.00  

---

### 3. TELEHEALTH CO-PAY RATIO RULE

**3.1** In accordance with Meridian administrative directives, all telehealth consultations shall carry a co-pay equal to exactly 40 percent (0.40) of the corresponding plan’s in-person specialist visit co-pay.  
**3.2** The CAE shall automatically validate and enforce this 40 percent ratio upon claim intake. Any manual override requires written authorization from Revenue Cycle Operations Manager Sarah Jenkins.

---

### 4. WORKED EXAMPLE: PARTIALLY MET DEDUCTIBLE CALCULATION

**4.1 Scenario Parameters:**
* **Plan:** MERIDIAN-SILVER (Deductible: $1,500.00; Coinsurance: 30%)
* **Patient Prior Deductible Met:** $1,200.00
* **Incoming Claim Allowable Charge:** $800.00 (Outpatient specialist procedure, subject to deductible and coinsurance)

**4.2 Step-by-Step Adjudication Calculation:**

1. **Calculate Remaining Deductible:**
   $$\text{Total Deductible} - \text{Prior Deductible Met} = \text{Remaining Deductible}$$
   $$\$1,500.00 - \$1,200.00 = \$300.00$$

2. **Apply Allowable Charge to Remaining Deductible:**
   The incoming claim of $800.00 is first applied against the remaining deductible of $300.00.
   * Patient pays toward deductible: **$300.00**
   * Remaining claim balance eligible for coinsurance: 
     $$\$800.00 - \$300.00 = \$500.00$$

3. **Calculate Coinsurance on Balance:**
   The remaining balance of $500.00 is subject to the MERIDIAN-SILVER coinsurance rate of 30%.
   $$\$500.00 \times 0.30 = \$150.00$$
   * Patient pays toward coinsurance: **$150.00**

4. **Calculate Total Patient Share for Claim:**
   $$\text{Deductible Portion} + \text{Coinsurance Portion} = \text{Total Patient Share}$$
   $$\$300.00 + \$150.00 = \$450.00$$

5. **Final Adjudication Result:**
   * Patient Responsibility: **$450.00**
   * Plan Responsibility: **$350.00**
   * Updated Year-to-Date Deductible Met: **$1,500.00** (Deductible is now fully satisfied for the remainder of the calendar year).
