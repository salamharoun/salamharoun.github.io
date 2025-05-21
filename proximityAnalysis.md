
# Crime-Free Rental Ordinances in Cook County Suburbs

## Introduction

This study investigates the racial and economic demographic variables that influence the passage of Crime-Free Rental Ordinances (CFROs) in Cook County, Illinois suburbs. The purpose of CFRO is to keep tenants with a history of crime out of a given municipality. When passed, landlords may be required to evict tenants who are or have been involved with the criminal justice system. Landlords may be fined or lose their rental property license for noncompliance. The definition of ‘involvement in the criminal justice system’ remains vague and varies widely between ordinances and often includes alleged criminal activities. These ordinances have been criticized for several adverse effects including discriminatory enforcement and neighborhood segregation.

## Methods

Cook County is a favorable test subject with over 120 municipalities of varying sizes (from under 1,000 to over 60,000 residents) and demographics (from near-zero to over 90% Black residents). This study addresses a gap in research on suburban politics. Suburbs are often overshadowed by studies focused on urban centers despite housing a large portion of the American population.

We examined four hypotheses aimed at explaining the adoption of these nuisance laws:

- **Racial Threat Hypothesis**
- **Place Stratification Hypothesis**
- **Proximity to City Boundaries Hypothesis**
- **Policy Diffusion Hypothesis**

The data collected to test these hypotheses were taken from the American Community Survey (ACS) from the US Census Bureau, the Cook County Health Atlas, the Shriver Center on Poverty Law, and the Illinois Housing Development Authority (IHDA).




## Hypotheses 

### Racial Threat Hypothesis

Studies (Moy 2023; Griswold et al. 2024; Kroeger and La Mattina 2020) suggest CFROs disproportionately impact Black and Hispanic renters. Certified rental units are typically located in lower-income areas with higher proportions of these populations. Reports from Northeast Ohio (Mead et al., 2017) indicate that race and class stereotypes often influence nuisance ordinance discussions.

According to Moy, the racial threat hypothesis states that when a minority group approaches approximately 50% of a population, it begins to exert majority influence, leading to a decline in the passage of laws that do not serve its interests. However, this pattern was not observed in Cook County. 

The figure below groups cities in Cook County into bins based on the percentage of Black residents. For each group, the proportion of cities with CFROs was calculated and plotted. The graph displays these proportions as bubbles, where the height represents the fraction of cities with CFROs, and the size reflects the number of cities in each bin. A red dashed line indicates the overall average CFRO adoption rate across all municipalities. The results show that as the percentage of Black residents increases, the likelihood of CFRO adoption also tends to rise, with no clear decline around the 50% mark.


<img src="images/blackpop.png?raw=true"/>

When the same analysis was applied to the percentage of residents relying on housing vouchers, the results showed a more pronounced pattern: CFRO adoption peaked and then declined as voucher reliance approached 30%. This indicates that perceived economic instability, rather than racial composition, may be a more direct trigger for these policies.

<img src="images/voucherpop.png?raw=true"/>


Overall, the graphs suggest that having a demographic majority does not necessarily translate into political power, as cities with large Black populations still adopt CFROs at high rates. Additionally, the clustering of CFROs across municipalities (discussed in a later hypothesis) points to policy diffusion, which is where cities adopt similar laws based on what nearby municipalities are doing rather than on their own local conditions. This may help explain how these ordinances continue to spread and persist.

### Place Stratification Hypothesis

Dominant groups manipulate spatial arrangements to maintain separation from groups they perceive as undesirable (Pais, South, & Crowder, 2012; Charles, 2003). Policies deputize landlords as enforcers of crime control (Greif, 2018). RAND (2023) shows CFHPs require property owners to attend police-led training and enforce lease terms permitting eviction based on allegations.

The maps below reveal a strong geographic correlation between cities with high non-white populations, high housing voucher usage, and the adoption of CFROs. This pattern supports the place stratification hypothesis, which argues that dominant groups shape spatial arrangements to maintain social and physical separation from groups they perceive as undesirable (Pais, South, & Crowder, 2012; Charles, 2003). In this context, CFROs serve as tools of exclusion, enabling municipalities to regulate tenant populations under the guise of public safety. As shown by Greif (2018), such policies deputize landlords as agents of crime control, while RAND (2023) notes that property owners are often required to attend law enforcement-led trainings and enforce lease clauses that permit eviction based on mere allegations. These spatial trends suggest that CFROs are not just reactive public safety measures but are actively used to reinforce racial and economic boundaries within the suburban landscape.

While these patterns align with the place stratification hypothesis, it’s important to interpret this relationship with caution. The observed overlap does not prove that demographic or economic factors directly cause CFRO adoption. Other factors, such as municipal leadership, law enforcement influence, or broader policy trends, also play a role. Without direct evidence of intent or policy motivations, the relationship remains correlational. Further research, including qualitative interviews or policy process analysis, would be needed to determine whether and how place stratification directly shapes these outcomes. 

<div class="tableauPlaceholder" id="viz1736983407708" style="position: relative">
    <noscript>
        <a href="#"><img alt="clusters" src="https://public.tableau.com/static/images/Pr/ProximityAnalysis/clusters/1_rss.png" style="border: none" /></a>
    </noscript>
    <object class="tableauViz" style="display:none;">
        <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
        <param name="embed_code_version" value="3" />
        <param name="site_root" value="" />
        <param name="name" value="ProximityAnalysis/clusters" />
        <param name="tabs" value="no" />
        <param name="toolbar" value="yes" />
        <param name="static_image" value="https://public.tableau.com/static/images/Pr/ProximityAnalysis/clusters/1.png" />
        <param name="animate_transition" value="yes" />
        <param name="display_static_image" value="yes" />
        <param name="display_spinner" value="yes" />
        <param name="display_overlay" value="yes" />
        <param name="display_count" value="yes" />
        <param name="language" value="en-US" />
        <param name="filter" value="publish=yes" />
    </object>
</div>


### Proximity to City Boundaries Hypothesis

Kroeger and La Mattina (2020) argue that nuisance ordinances may serve to prevent migration from urban centers. Mead (2017) further supports this, showing that renters using housing vouchers are often targeted by such policies.

In the study, we found that jurisdictions farther from Chicago are **more likely** to adopt CFROs.

- **Correlation coefficient**: 0.29 (positive)
- **Method**: Point-biserial correlation
This suggests suburban municipalities may adopt these policies to preempt perceived threats from urban migration.

- **T-test statistic**: 3.3 (positive)
- **p-value**: 0.001

In addition, a t-test was also used to compare cities closer to Chicago with those farther away in terms of CFRO adoption. The results (t = 3.3, p = 0.001) show a statistically significant difference. Cities that passed CFROs are, on average, farther from the city boundary than those that didn’t. The low p-value indicates this difference is unlikely to be due to chance. This data suggests that distance from Chicago may be a factor in the likelihood of CFRO adoption, with more distant suburbs being more prone to passing these ordinances.

These findings support the argument made by Kroeger and La Mattina (2020), who suggest that nuisance ordinances may be used by suburbs to discourage migration from nearby urban centers. The statistically significant difference in distance from Chicago between cities with and without CFROs, along with the positive correaltion between distance from Chicago borde and CFRO status, indicates that more distant suburbs are more likely to adopt these ordinances. This pattern suggests an effort to maintain separation from the city and its residents, particularly lower-income renters. Mead (2017) adds to this by showing that renters using housing vouchers are often the specific targets of such policies. Together, the data and prior research point to CFROs functioning as a form of exclusionary zoning aimed at keeping out populations perceived as economically or socially undesirable.




<img src="images/voucherpop.png?raw=true"/>



### Policy Diffusion Hypothesis

Policy adoption often spreads through neighboring jurisdictions. Neto (2021) shows advocacy groups promote standardized policies. Kroeger and La Mattina (2020) also highlight that adoption in one municipality increases the likelihood of adoption in neighboring areas.



### 3. Proximity to City Boundaries Hypothesis

Jurisdictions farther from Chicago are **more likely** to adopt CFROs.

- **Correlation coefficient**: 0.29 (positive)
- **Method**: Point-biserial correlation
- Suggests suburban municipalities may adopt these policies to preempt perceived threats from urban migration.

### 4. Policy Diffusion Hypothesis

- **70%** of municipalities’ CFRO status matches that of their nearest neighbor.
- **Moran’s I**: 0.2547 (moderate positive spatial autocorrelation)
- **p-value**: 0.0030 (statistically significant)

These findings suggest clustering in policy adoption, likely influenced by geographic proximity rather than formal coordination.

## Key Findings and Implications

- Racial threat alone does not explain CFRO adoption patterns.
- **Socioeconomic indicators** (e.g., housing voucher usage) and **distance from Chicago** are stronger predictors.
- CFRO adoption increases with distance from the city, contradicting assumptions that border municipalities are more restrictive.
- Policy diffusion plays a role in suburban adoption patterns.
- The complexity of suburban policymaking goes beyond simple racial animus, involving economic anxieties and spatial positioning.

## Next Steps

- Further investigation into **Place Stratification Hypothesis** with targeted qualitative data.
- Explore **communication patterns** between municipalities regarding policy sharing.
- Assess long-term impacts of CFROs on housing stability and racial segregation.
- Use findings to inform advocacy strategies against discriminatory suburban housing policies.


