## 📊 Cancer Incidence and Survival Dashboard — Project Notes

Reading *Cancer Facts & Figures 2025* from the American Cancer Society inspired me to visualize the data in a more accessible way. While the report contains extensive tables, I wanted to create an interactive dashboard that allows users to explore cancer incidence, death rates, and survival outcomes across states, cancer types, and sexes.

---

### **Key Questions**

1. **State-level patterns:**
   * Is there a geographical pattern of cancer incidence or death rate?
     for female, Incidence rates seem to have relatively better outcomes in west coast and westsouthern states such as California, Nevada, Utah, Arizona, and New Mexico, and worst outocmes among north east states. On the other hand, it seems that death rates are dispersed with east inland states having worst death rates from cancer such as Mississippi, Kentucky, West Virginia, Oklahoma.
     for male, The patterns are more distinct: incidence rates are better in west coast from Oregon to New Mexico and colorado. Death rates are worst narrowly focused on east inland states like Mississippi, Kentucky, Oklahoma. 
   ** Do states with high cancer incidence also experience higher cancer death rates?
     For better comparison, I created Mortality-to-Incidence ratio with two data tables as a proxy for survival/healthcare access quality. 
     Mortality-to-Incidence ratio shows that states have around 16~22% death out of incidence. Whether the top and bottom states different significantly, we need to test, which requires knowing SEs or CIs to run formal hypothesis tests. With just the Cancer Facts & Figures tables (which are summary rates), you can’t run significance tests.  it remains for further analysis. 
   * If not, could differences in healthcare access and treatment quality explain the gap?
     Top 5 states with the highest death rates overlap with the 5 worst health system except Kentucky(bottom #13)

2. **Sex-based differences:**

   * Since incidence and death rates (Tables 3 & 4) are recorded separately by sex, how do male and female rates compare?
   * Are there cancers where disparities between sexes are especially pronounced?

3. **Survival progress:**

   * Have survival rates improved consistently across all cancer types?
   * Which cancers have seen the greatest gains, and which have lagged behind?

4. **Geographic risk factors:**

   * Is skin cancer more prevalent in sunny states?
   * How do new melanoma case rates compare across different regions when adjusted for population?

---

### **Data & Method**

* **Source:** *Cancer Facts & Figures 2025*, American Cancer Society (Tables 3, 4, and 5 for incidence and death rates; survival data by cancer type).
* **Tools:** Tableau for visualization; Excel for data preparation.
* **Approach:** Combined incidence, death, survival, and sex-specific datasets into an interactive map and charts, enabling comparisons by state, sex, and cancer type.

---

### **Insights**

* **Incidence ≠ Death:** Not all cancers with high incidence correspond to high death rates. For example, prostate cancer is common but has a relatively low mortality rate compared to lung cancer, highlighting differences in early detection and treatment.
* **Sex disparities:** Male incidence and death rates are generally higher than female rates for several cancers, but not all. This suggests biological, behavioral, and healthcare access factors may play a role.
* **Survival improvements:** Since the 1970s, survival has improved for nearly all cancers, with some cancers showing dramatic progress (e.g., breast cancer, leukemia), while others like pancreatic cancer have seen slower gains.
* **Geographic disparities:** Preliminary patterns suggest that melanoma rates are indeed higher in sunnier states, consistent with known risk factors like UV exposure.

---

### **Future Considerations**

* Integrate socioeconomic and healthcare access data (e.g., insurance coverage, rural vs. urban) to better understand disparities.
* Expand sex-based analysis to highlight public health priorities where one sex is disproportionately affected.
* Track survival rate improvements over time with longitudinal visualizations.
* Add prevention and screening statistics to provide a fuller picture of progress.

---

### **Takeaway**

This project demonstrates how public health data can be translated into interactive visual insights. By connecting incidence, mortality, sex differences, and survival trends, the dashboard can help researchers, policymakers, and the public better understand progress in cancer outcomes and identify where efforts should be focused next.


