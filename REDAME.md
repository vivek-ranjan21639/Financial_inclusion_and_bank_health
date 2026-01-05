# Financial Inclusion and Bank Health: A State-Level Analytical Study Using RBI Statistics  

**Author:** `Vivek Ranjan` `Gurjot Kaur`   

**Meet Vivek Ranjan**  
**Email Id:** vivekranjan21639@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/vivek-ranjan-jnu/

**Meet Gurjot Kaur**  
**Email Id:** gurjotk276@gmail.com  
**LinkedIn:** https://in.linkedin.com/in/gurjot-kaur-a16641281

## About the Project 
Financial inclusion has been a central pillar of India’s financial sector policy over the past decade, with sustained efforts aimed at expanding banking access, deepening credit penetration, and integrating underserved regions into the formal financial system. Alongside inclusion, the stability and soundness of the banking system remain core priorities for the Reserve Bank of India, particularly from a supervisory perspective.

While national-level indicators show significant progress in banking outreach, regional disparities across Indian states remain substantial. States differ widely in branch density, deposit mobilisation, credit penetration, and sectoral composition of lending. These differences have implications not only for inclusion outcomes but also for regional credit dynamics, balance-sheet behaviour, and potential supervisory concerns.

Understanding how financial inclusion interacts with basic indicators of bank health at the regional level is critical for:
- Identifying structurally under-banked regions,
- Interpreting persistently low or high credit–deposit (CD) ratios,
- Assessing whether inclusion is translating into balanced and sustainable credit growth.

This project seeks to address this gap by conducting a state-level analytical study using official RBI statistical publications, focusing on the intersection of financial inclusion and bank health proxies.

## Objectives

### Objectives 1: Measure and compare financial inclusion across Indian states.
#### Access (Infrastructure)
- SCB_Branches_per_Lakh = SCB_Offices / Total_Population × 100000
- RRB_Branches_per_Lakh_Rural = RRB_Branches / Rural_Population × 100000  
#### Usage (Depth)
- SCB_Deposit_per_Capita = SCB_Deposits / Total_Population
- SCB_Credit_per_Capita = SCB_Credit / Total_Population
- RRB_Credit_per_Capita = RRB_Credit / Rural_Population
#### Composite
- Inclusion_Index (average of z-scores of branch density, deposit per capita, credit per capita)

### Objectives 2: Examine state-level bank balance-sheet behaviour.
- CD_SCB_Utilisation
- CD_SCB_Sanction
- CD_RRB
- CD_Gap = CD_SCB_Sanction − CD_SCB_Utilisation  
#### CD classification bands:
- Low: < 60%
- Balanced: 60–90%
- High: > 90%

### Objectives 3: Analyse the relationship between inclusion and bank health proxie.
- Inclusion_Index
- SCB_Credit_per_Capita
- CD_SCB_Utilisation
- Controls:
    - PC_NSDP_Constant
    - Urbanisation
    - Literacy_Rate

### Objectives 4: Assess sectoral credit structure and concentration risk.
- Agri_Share = Agri_Credit / SCB_Credit
- Industry_Share = Industry_Credit / SCB_Credit
- Personal_Loan_Share = Personal_Loans / SCB_Credit
- Credit_Concentration = max(Agri, Industry, Personal)

### Objevtives 5: Distinguish development-driven gaps from structural banking gaps
- PC_NSDP_Constant
- Literacy_Rate
- Urbanisation
- Inclusion_Index


## Results and Interpretation

#### 1. Financial Inclusion across Indian States  
The analysis reveals substantial variation in financial inclusion across Indian states. States ranking higher on the composite inclusion index consistently exhibit higher branch density, deposit mobilisation, and credit penetration. Conversely, a group of states remains persistently low across all three dimensions, indicating structural inclusion deficits rather than temporary shortfalls.

Notably, branch density alone does not ensure financial deepening. Several states with relatively dense banking infrastructure continue to display low credit per capita, suggesting limited translation of access into effective usage.

#### 2. Bank Balance-Sheet Behaviour and CD Ratios  
State-wise credit–deposit ratios display pronounced dispersion. A number of states exhibit CD ratios below 60 per cent, reflecting under-utilisation of local deposits, while others show ratios exceeding 90 per cent, indicating relatively aggressive credit deployment.

Differences between CD ratios based on place of sanction and place of utilisation further reveal inter-state credit flows. Negative CD gaps in several states suggest that deposits mobilised locally are deployed elsewhere, whereas positive gaps indicate net inflow of credit.

#### 3. Financial Inclusion and Credit Deployment  
The relationship between financial inclusion and bank lending is non-linear. While higher inclusion is generally associated with greater credit penetration, several states demonstrate high inclusion accompanied by moderate or low CD ratios. This pattern points towards conservative lending behaviour or weak credit demand despite adequate banking outreach.

After accounting for income levels, inclusion continues to explain variation in credit outcomes, highlighting the independent role of banking infrastructure and engagement.

#### 4. Credit Structure and Sectoral Concentration  
Sectoral analysis shows that credit portfolios differ markedly across states. In several states, agriculture accounts for a dominant share of bank credit, while others are heavily skewed towards industrial or retail lending. States with high credit concentration indices are potentially more vulnerable to sector-specific shocks.

These structural differences underline the importance of contextualising CD ratios and credit growth with underlying credit composition.

#### 5. Development, Inclusion, and Structural Gaps  
The state typology based on income and inclusion reveals four distinct groups. While high-income–high-inclusion states represent mature banking ecosystems, the presence of high-income–low-inclusion states indicates structural banking gaps unrelated to economic capacity. Conversely, some low-income states have achieved relatively higher inclusion, reflecting successful outreach efforts.

#### 6. Supervisory and Policy Implications  
From a supervisory perspective, states characterised by persistently low CD ratios despite adequate branch presence may warrant closer examination of credit demand and lending practices. States with very high CD ratios combined with concentrated credit exposure may require careful monitoring to assess sustainability. The findings underscore the need for regionally differentiated supervisory and policy responses rather than uniform benchmarks.

 