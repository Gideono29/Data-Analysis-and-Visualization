# Data-Analysis-and-Visualization of Obsessive-Compulsive Disorder (OCD) dataset. 

## Dataset 

The OCD Patient Dataset: Demographics & Clinical Data contains detailed records of 1,500 individuals diagnosed with Obsessive-Compulsive Disorder (OCD), offering a comprehensive view of the demographic and clinical characteristics of this population.
The dataset captures demographic variables such as age, gender, ethnicity, marital status, and education level, enabling an understanding of the social and personal contexts of individuals with OCD. These variables help identify patterns and disparities across different population groups.

It also includes clinical information such as the date of diagnosis, duration of symptoms, and previous psychiatric history, which provides insights into disease progression and comorbidity. Of particular importance are the Yale-Brown Obsessive-Compulsive Scale (Y-BOCS) scores, which measure the severity of obsessions and compulsions separately. This distinction allows for a nuanced understanding of the disorder’s symptom profile.

Beyond symptom assessment, the dataset highlights co-occurring conditions like depression and anxiety, which are common among individuals with OCD. It also documents treatment approaches, including the types of medications prescribed, and whether patients have a family history of OCD, offering potential clues about genetic or environmental influences.

Overall, this dataset provides a multidimensional perspective on OCD, combining demographic, diagnostic, and therapeutic information. Its breadth allows researchers and clinicians to explore hidden trends and associations, such as demographic factors linked to symptom severity or treatment outcomes.

<img width="1785" height="969" alt="Screenshot 2025-10-18 000327" src="https://github.com/user-attachments/assets/19966693-afb2-4e54-8608-cda918b45029" />

## OCD Dataset – Key Findings and Insights

1. Temporal Trend
The line chart shows patient counts from 2013 to 2023. There’s a steady number of diagnosed cases with mild fluctuations, peaking slightly around 2016–2018 before stabilizing. This may suggest growing awareness and diagnosis rates over time.

2. Gender Distribution
OCD affects both genders almost equally — Male: 49.8%, Female: 50.2% — showing no significant gender bias in prevalence.

3. Ethnicity Distribution
Caucasian and Hispanic populations represent the largest patient groups (~370–380 each), followed by Asian (~350) and African (~300). This suggests a relatively diverse dataset, though possible underrepresentation of some ethnic groups may exist.

4. Compulsion Types
The most common compulsions are Washing, Counting, and Checking, indicating dominant anxiety-control behaviors. Praying and Ordering are less frequent, suggesting possible cultural or personal differences in coping mechanisms.

5. Obsession Types and Severity
The “Obsession Count vs. Average Obsession Score” graph shows that Harm-related and Contamination obsessions score highest on the Y-BOCS, implying these are the most severe and distressing forms. Hoarding also appears as a notable but less intense subtype.



---

## Other key findings

1. **Severity distribution (Y-BOCS total)**

   * `YBOCS_Total = Y-BOCS (Obsessions) + Y-BOCS (Compulsions)`.
   * **Mean ≈ 39.7**, median = 40, standard deviation ≈ 16.95; range 1–79. The distribution is broadly spread with a central concentration around 30–50 (plot saved). This indicates many patients in moderate–to–high severity ranges.

2. **No strong relation between severity and demographics or duration**

   * Correlation between `YBOCS_Total` and **Age** ≈ **0.008** (negligible).
   * Correlation between `YBOCS_Total` and **Duration of symptoms (months)** ≈ **0.033** (negligible).
   * Conclusion: age and symptom duration do **not** predict severity in this dataset.

3. **Comorbidity (Depression / Anxiety) and medication status did not show higher severity**

   * Comparing Y-BOCS totals in patients with vs without depression or anxiety gave **non-significant** t-tests (p ≫ 0.05).
   * Comparing patients on any medication vs none also showed no significant difference.
   * Conclusion: in this cross-sectional sample, comorbid depression/anxiety and whether a patient was on medication do **not** explain higher Y-BOCS scores.

4. **Obsessions and compulsions sub-scores are similar in magnitude but weakly correlated**

   * Mean obsessions ≈ 20.05, mean compulsions ≈ 19.63.
   * Correlation between the two subscales ≈ **0.03** (surprisingly low). That suggests some patients present relatively higher on one subscale than the other — i.e., some heterogeneity in symptom profile.

