# 📋 Pre-registration Information
## AI Interaction Patterns Study

**Lead Investigator:** Samir Baladi  
**Affiliation:** Rite of Renaissance  
**Registration Date:** [To be completed upon OSF registration]  
**Status:** Pre-data collection

---

## 🔗 Registration Links

This study will be pre-registered on multiple platforms before data collection begins:

| Platform | Link | Status | Purpose |
|----------|------|--------|---------|
| **OSF Preregistration** | [To be added] | 🔄 Pending | Official pre-registration |
| **AsPredicted** | [To be added] | 🔄 Optional | Alternative pre-registration |
| **GitHub Repository** | [To be added] | ✅ Active | Living documentation |

**Target Registration Date:** June 2026  
**Data Collection Start:** July 2026

---

## 📅 Timeline

| Event | Date | Status |
|-------|------|--------|
| Protocol Development | May 2026 | ✅ Complete |
| **Pre-registration (OSF)** | **June 2026** | **🔄 In Progress** |
| IRB Submission | June 2026 | ⏳ Planned |
| IRB Approval | June 2026 | ⏳ Awaiting |
| Recruitment | July-August 2026 | ⏳ Planned |
| **Data Collection** | **July-September 2026** | **⏳ Scheduled** |
| Data Analysis | October-November 2026 | ⏳ Scheduled |
| Results Dissemination | December 2026 | ⏳ Scheduled |

**⚠️ CRITICAL:** All registrations will be completed BEFORE data collection begins (June 2026).

---

## 📊 What's Pre-registered

### **1. Study Design**

- **Type:** Cross-sectional observational study with mixed methods
- **Sample Size:** N = 120 adults who use AI for self-reflection
- **Design:** Pre-interaction surveys → AI conversation (logged) → Post-interaction outcomes
- **Timeline:** July-September 2026 (12 weeks data collection)

---

### **2. Research Questions & Hypotheses**

**Primary Research Question:**
> "How do user intentionality (N), structural awareness (W), contemplative patience (S), and interaction depth (M) interact to determine the outcome (R) of AI-mediated self-reflection?"

**Theoretical Model:**
```
R = f(N, W, S, M)

N = Intention Quality
W = Structural Awareness  
S = Contemplative Patience
M = Interaction Depth
R = Outcome (🟢 Treasure / 🟠 Frustration / 🔴 Illusion)
```

---

**Hypotheses:**

**H1 (Treasure Path):**
High N + High W + High S → R = 🟢 Treasure (insight, clarity)

**H2 (Illusion Path):**
Low N + Low W + Low S + High M → R = 🔴 Illusion (dependency, false control)

**H3 (Frustration Path):**
Moderate N + Low W + Low S → R = 🟠 Frustration (disappointment)

**H4 (Moderation):**
M (Interaction Depth) moderates N/W/S → R relationships

**H5 (Latent Profiles):**
Distinct user profiles emerge from N/W/S combinations

---

### **3. Outcome Measures**

**Primary Outcome: R (User Outcome)**

| Outcome | Scale | Items | Range |
|---------|-------|-------|-------|
| 🟢 **Treasure** | Insight Experience Scale | 6 | 1-5 |
| 🟠 **Frustration** | Frustration Scale | 5 | 1-5 |
| 🔴 **Illusion** | Dependency & Illusion Scale | 7 | 1-5 |

**Predictor Variables:**

| Variable | Scale | Items | Range |
|----------|-------|-------|-------|
| **N** | AI Intentionality Scale | 12 | 1-5 |
| **W** | Structural Awareness Scale | 10 | 1-5 |
| **S** | Contemplative Patience Scale | 8 | 1-5 |
| **M** | Interaction logs (behavioral) | Multiple | z-score |

---

### **4. Sample Size Justification**

**Power Analysis:**
- Model: Multinomial logistic regression
- Effect size: OR = 2.0 (medium)
- Power: 0.80, Alpha: 0.05
- Required N ≈ 110
- **Recruited N = 120** (10% buffer)

---

### **5. Statistical Analysis Plan**

**Primary Analysis:**
```r
# Multinomial logistic regression
multinom(R_outcome ~ N + W + S + M + N:W + W:S + N:M + W:M + S:M)
```

**Secondary Analysis:**
- Latent Profile Analysis (N/W/S profiles)
- Qualitative thematic analysis
- Platform differences (exploratory)

---

### **6. Data Management**

**Missing Data:**
- Multiple imputation (5 imputations, mice package)
- ITT approach (all enrolled participants)

**Exclusion Criteria:**
- >20% missing on key variables
- Failed attention checks
- Non-genuine AI conversations (quality check)

---

## 🔒 Ethical Considerations

### **Privacy:**
- Anonymized conversation logs
- Encrypted data storage (REDCap/Qualtrics)
- No identifying information collected

### **Mental Health:**
- Screening excludes acute crises (GAD-7 ≥ 15)
- Resources provided to all participants
- Follow-up if distress reported

### **Informed Consent:**
- Full disclosure of study purpose
- Right to withdraw anytime
- Compensation: $15 for ~45 minutes

---

## 📚 Key References

**Measurement:**
- Brown, K. W., & Ryan, R. M. (2003). Mindfulness scale. *JPSP*.
- Long, D., & Magerko, B. (2020). AI literacy. *CHI*.

**Theory:**
- Sundar, S. S. (2020). Human-AI interaction. *JCMC*.
- Laukkonen, R. E., et al. (2022). Science of insight. *Psych Bulletin*.

---

## 📧 Contact

**Study Team:**  
Samir Baladi  
Email: riteofrenaissance@proton.me

**Pre-registration:**  
[OSF link to be added June 2026]

---

## 📝 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | May 2026 | Initial protocol |
| 1.1 | May 2026 | Updated timeline (July-Dec 2026) |

---

**Document Status:** Draft for pre-registration (June 2026)  
**Next Step:** OSF registration before data collection