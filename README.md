
# 📊 Cancer Incidence and Survival Dashboard — Project Notes

Inspired by *Cancer Facts & Figures 2025* from the American Cancer Society, I developed an interactive dashboard to make complex cancer statistics more accessible. While the report presents detailed tables, my goal was to create a tool that enables users to explore cancer incidence, mortality, and survival outcomes across states, cancer types, and sexes.

---

### **Key Questions and Findings**

**1. Are there geographical patterns in cancer incidence and death rates?**

* **Female:** Incidence rates are generally lower in western and southwestern states (California, Nevada, Utah, Arizona, New Mexico) and higher in northeastern states. Death rates appear more dispersed but are particularly high in east–inland states such as Mississippi, Kentucky, West Virginia, and Oklahoma.
* **Male:** Patterns are clearer: incidence rates are lower in western states from Oregon through New Mexico and Colorado, while death rates are concentrated in east–inland states like Mississippi, Kentucky, and Oklahoma.

**2. Do states with high cancer incidence also experience higher death rates?**
Yes. A correlation test shows a very strong relationship (Pearson correlation = **0.963**, p < 0.001). States with higher incidence tend to also have higher death rates.

**3. Does the Mortality-to-Incidence Ratio (MIR) differ significantly across states?**
MIR was calculated as a proxy for survival.

* **Range:** \~28–42% for males, \~25–35% for females (males have consistently higher MIR).
* **Statistical test:** Comparing the top 10 and bottom 10 states, both sexes showed highly significant differences (Female: *t* = 14.916, Male: *t* = 15.022, both p < 0.001).

**4. Does MIR reflect healthcare quality?**
Using the *2025 Scorecard on State Health System Performance* (Commonwealth Fund), I tested the correlation between MIR and healthcare rankings.

* **Females:** Spearman ρ = **0.706**, p < 0.001 → strong positive correlation.
* **Males:** Spearman ρ = **0.550**, p < 0.001 → moderate-to-strong correlation.
* **Interpretation:** In states with poorer healthcare system performance (higher ranking score), MIR is higher. The association is stronger for females, suggesting female outcomes may be more sensitive to healthcare quality.

  <img width="523" height="408" alt="image" src="https://github.com/user-attachments/assets/067efe16-b689-447b-a040-3ee9d8f23907" />


**5. Have 5-year survival rates improved consistently across cancer types?**
Overall survival has improved substantially: a **41% relative increase** over recent decades. However, gains vary by cancer type.

**6. Which cancers have seen the greatest and least improvements?**

* **Greatest gains:** Lung & bronchus cancer, despite still having the lowest survival rates, has shown the largest relative improvement.
* **Least gains:** Breast cancer survival remains high (91%) but has seen the smallest relative improvement. Prostate cancer has the highest survival (97%).

---

### **Future Considerations**

* Integrate socioeconomic and healthcare access variables (e.g., insurance coverage, rural vs. urban) to better explain disparities.
* Expand sex-specific analyses to highlight public health priorities.
* Track survival trends longitudinally to capture progress over time.
* Add prevention and screening data for a fuller picture of outcomes.

---

### **Takeaway**

This project shows how public health data can be transformed into interactive insights. By connecting incidence, mortality, MIR, healthcare quality, and survival trends, the dashboard highlights both progress and disparities. These findings can support researchers, policymakers, and the public in targeting efforts to reduce cancer burden and improve outcomes.

