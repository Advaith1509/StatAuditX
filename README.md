# _StatAuditX_
> **"A Statistical Approach with RCBD & Factorial Design"**  
> – _The project applies statistical experimental designs to analyze how **AI adoption** and **employee workload** impact **audit effectiveness** in Big 4 consulting firms._

---

## _🎯 Objective of the Study_

To statistically assess:
- The impact of **AI usage** in auditing across different firms.
- The **interaction between AI and employee workload** on audit effectiveness.

Using:
- ✅ _**RCBD**_ to control for firm-level differences.
- ✅ _**Factorial Design**_ to study main effects and interactions.

---

## _🔬 Experimental Designs Used_

### 🔷 Randomized Complete Block Design (RCBD)
- **Factor (Treatment):** AI Usage (Yes / No)  
- **Blocking Factor:** Firm Name (EY, PwC, Deloitte, KPMG)  
- **Response Variable:** Audit Effectiveness Score  
- 🎯 *Purpose:* To isolate the effect of AI while accounting for firm-specific variations.

### _🔶 Full Factorial Design (2×3)_
- **Factors:**
  - AI Usage (Yes / No)
  - Workload Level (Low / Medium / High)
- **Response Variable:** Audit Effectiveness Score  
- 🎯 *Purpose:* To analyze **main effects** and **interaction effect** between AI and workload.

---

## _Why We Didn't Use Other Designs_

### 🔸 Latin Square Design
- Requires **two orthogonal blocking factors** (e.g., row and column).
- Our dataset has only **one meaningful block** (Firm Name).
- ➡️ **Not suitable** for our layout.

### 🔸 Balanced Incomplete Block Design (BIBD)
- Intended for **incomplete treatment-block combinations**.
- Our data is **fully observed** for all treatment levels and firms.
- ➡️ **Not applicable** due to completeness.

---

## _📊 Visualizations_

- 📈 _Boxplots:_ AI vs Audit Score, Firm vs Audit Score
- 🔥 _Heatmap:_ Audit Score by AI × Firm
- 📉 _Interaction Plot:_ AI × Workload vs Audit Score
- 🧪 RCBD and Factorial ANOVA Tables with:
  - Sum of Squares (SS)
  - Degrees of Freedom (DF)
  - Mean Squares (MS)
  - F-Values and Hypothesis Testing

---

## _🧠 Hypothesis Testing_

### RCBD
- **H₀:** AI usage has no significant impact on audit effectiveness.
- **H₁:** AI usage significantly affects audit effectiveness.

### Factorial Design
- **Main Effect (AI):** H₀ — No effect of AI usage  
- **Main Effect (Workload):** H₀ — No effect of workload  
- **Interaction Effect:** H₀ — No interaction between AI and workload  

✅ *All hypotheses are tested using manually calculated ANOVA tables and compared against F-critical values.*

---



