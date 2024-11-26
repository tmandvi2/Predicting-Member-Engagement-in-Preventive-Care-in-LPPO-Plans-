# Predicting-Member-Engagement-in-Preventive-Care-in-LPPO-Plans-
The projects presents a comprehensive analysis of preventive care utilization in Humana's Local Preferred Provider Organization (LPPO) plans


The project presents a comprehensive analysis of preventive care utilization in Humana's Local Preferred Provider Organization (LPPO) plans. It explores the challenges, proposes data-driven strategies to address care gaps, and outlines the potential business implications of these solutions.

---

### 1. **Executive Summary**
Humana’s LPPO plans face significant challenges in preventive care engagement, especially when compared to Health Maintenance Organization (HMO) plans. These gaps have implications for member health outcomes, CMS Star Ratings, and the competitiveness of LPPO plans in the growing Medicare Advantage market. The report leverages advanced machine learning techniques to develop actionable strategies.

---

### 2. **Key Insights**
1. **Factors Affecting Preventive Care Utilization**:
   - **Demographics**: Age, gender, and race impact engagement levels.
   - **Geography**: Regional disparities in healthcare access are significant.
   - **Health Status**: Chronic conditions and disabilities influence care behavior.
   - **Plan Characteristics**: Elements like attributed providers and plan benefits play a role.
   - **Engagement Patterns**: Active digital engagement correlates with better preventive care adherence.

2. **High-Risk Populations**:
   - Three distinct clusters were identified among high-risk members:
     - **Cluster 0**: Diverse group with moderate veteran representation and low healthcare costs.
     - **Cluster 1**: Non-veterans with high healthcare costs and limited provider continuity.
     - **Cluster 2**: Veterans with very low healthcare costs and infrequent care utilization.

3. **Digital Behavior**:
   Members engaging with Humana’s digital services are more likely to utilize preventive care.

4. **Veteran-Specific Challenges**:
   Veterans exhibit unique healthcare patterns that necessitate tailored interventions.

---

### 3. **Methodology**
The report applies machine learning models, specifically **CatBoost**, for predictive analytics. The SHAP (SHapley Additive exPlanations) framework was used to interpret the model and derive insights.

#### Data Processing:
- **Data Integration**: Merged 11 datasets covering demographics, health conditions, claims, and quality measures.
- **Feature Engineering**: Aggregated data to represent member-level characteristics.

#### Model Performance:
- The CatBoost model achieved an AUC of 0.778, with accuracy at 71%, making it a reliable tool for predicting care gaps.

#### Clustering:
- **K-Means** identified three meaningful subgroups within high-risk populations, informing targeted strategies.

---

### 4. **Business Recommendations**
#### 4.1 Targeted Interventions:
1. **Preventive Care Rebate Program (Cluster 1)**:
   - Target: High-cost, non-veteran members.
   - Mechanism: $50 rebates for preventive care visits.
   - Projected Impact:
     - Additional users: 5,070.
     - Total program cost: $713,130.
     - Healthcare savings: $2,535,000.
     - ROI: 255.47%.

2. **Veteran-Centric Care Coordination Program (Cluster 2)**:
   - Target: Low-cost veterans with infrequent care visits.
   - Mechanism: Peer-led outreach with trained veterans encouraging engagement.
   - Projected Impact:
     - Additional users: 856.
     - Total program cost: $84,700.
     - Healthcare savings: $428,000.
     - ROI: 405.3%.

---

#### 4.2 General Recommendations:
1. **Digital Engagement Strategy**:
   - Encourage members to interact with Humana’s online platforms.
   - Promote frequent statement checks to raise awareness of health services.

2. **Accessibility for Members with Disabilities**:
   - Provide at-home preventive care checks to address mobility challenges.

3. **Exploring Peer Influence**:
   - Analyze how social and familial networks impact health behaviors.
   - Incorporate relational data into models for personalized interventions.

---

### 5. **Implementation Considerations**
#### Legal and Ethical Safeguards:
- Compliance with HIPAA and other regulations.
- Informed consent for all participants.
- Transparency in program goals, processes, and data usage.
- Opt-out mechanisms for members.

#### Administrative Support:
- Train volunteers for peer-led programs.
- Use part-time coordinators for implementation oversight.

#### Financial Planning:
- Clear budget allocation for rebates, incentives, and administrative costs.
- Regular audits to ensure compliance and effectiveness.

---

### 6. **Expected Outcomes**
- **Enhanced Health Outcomes**:
  Increased engagement in preventive care leads to early detection of illnesses and better chronic disease management.

- **Improved CMS Star Ratings**:
  Higher ratings translate to better funding and plan competitiveness.

- **Cost Optimization**:
  Preventive care reduces long-term healthcare expenditures by avoiding costly emergency and advanced treatments.

- **Strengthened Market Position**:
  Proactive strategies differentiate Humana’s LPPO plans in the Medicare Advantage market.

---

### 7. **Conclusion**
The report concludes that targeted, data-driven strategies can significantly enhance preventive care engagement. By addressing gaps in care and tailoring solutions to specific populations, Humana can improve member health, operational efficiency, and market competitiveness. The combination of advanced analytics, digital innovation, and personalized outreach positions Humana as a leader in preventive care engagement within Medicare Advantage LPPO plans.
