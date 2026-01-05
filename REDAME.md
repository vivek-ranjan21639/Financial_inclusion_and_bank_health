# About the Project

## `Title:` Financial Inclusion and Bank Health: A State-Level Analytical Study Using RBI Statistics

## Background and Motivation
Financial inclusion has been a central pillar of India’s financial sector policy over the past decade, with sustained efforts aimed at expanding banking access, deepening credit penetration, and integrating underserved regions into the formal financial system. Alongside inclusion, the stability and soundness of the banking system remain core priorities for the Reserve Bank of India, particularly from a supervisory perspective.

While national-level indicators show significant progress in banking outreach, regional disparities across Indian states remain substantial. States differ widely in branch density, deposit mobilisation, credit penetration, and sectoral composition of lending. These differences have implications not only for inclusion outcomes but also for regional credit dynamics, balance-sheet behaviour, and potential supervisory concerns.

From a Department of Supervision (DoS) standpoint, understanding how financial inclusion interacts with basic indicators of bank health at the regional level is critical for:
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


## Outcome

## Conclusion
 