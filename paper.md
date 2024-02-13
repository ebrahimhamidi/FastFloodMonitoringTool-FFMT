---
title: 'Multi-Source and Multi-Temporal Google Earth Engine App for Emergency Flood Mapping'
tags:
  - Java Script
  - flood mapping
  - remote sensing
  - Synthetic Aperture Radar (SAR)
  - Optical Data
  - Hurricanes
  - Multidisciplinary Information
authors:
  - name: Ebrahim Hamidi
    orcid: 0000-0003-3160-6999 
    corresponding: true
    affiliation: "1, 2"
  - name: Brad G. Peter
  - orcid: 0000-0002-5724-4482
    equal-contrib: true
    affiliation: 3
  - name: Hamed Moftakhari
  - orcid: 0000-0003-3170-8653
    equal-contrib: true
    affiliation: "1, 2"
  - name: Hamid Moradkhani
  - orcid: 0000-0002-2889-999X
  - equal-contrib: true
    affiliation: "1, 2"
affiliations:
 - name: Department of Civil, Construction and Environmental Engineering, The University of Alabama, Tuscaloosa, AL, USA
   index: 1
 - name: The Center for Complex Hydrosystems Research, The University of Alabama, Tuscaloosa, AL, USA
   index: 2
 - name: Department of Geosciences, University of Arkansas, Fayetteville, AR, USA
   index: 3
date: 13 February 2024
bibliography: paper.bib

---

# Summary

Recent studies suggest that global warming will lead to a greater chance of 
extreme flooding in the coming decades, doubling every five years in the near future. 
Coastal regions, being densely populated areas, are highly vulnerable to flooding due 
to various drivers such as extreme rainfall and tropical cyclones. Therefore, identifying 
efficient and accurate models for mapping floods is key in flood risk assessment. While 
remotely sensed observations have provided researchers with decades of continuous and 
reliable data for extracting flood information, it is important to note that relying solely 
on single-source remote sensing data may not provide a comprehensive solution for urgent 
flood monitoring. Satellite revisit cycles, spatial resolution, weather conditions, and 
solar reflectance dependency, as well as sensor defects, are a number of remote sensing 
limitations that can hinder flood mapping progress.
Multi-source methods can address part of the limitations inherent in single-source methods. 
These methods can cope with the drawbacks of satellite data while leveraging their advantages. 
For example, using multi-source optical/SAR imagery can provide abundant spectral information 
and highly accurate water extraction from the optical imagery, thereby benefiting the SAR images 
all-weather and day-night operation capabilities for flood mapping. In this study, we build on our 
previous research and introduce an App that leverages state-of-the-art remote sensing resources 
and the capability of the Google Earth Engine (GEE) platform to produce a rapid estimation of 
floods using an advanced multi-source remote sensing approach that is geographically generalizable. 
Then, this GEE App extracts multidisciplinary information from the final flood map for responsible 
responders to adopt flexible measures based on the types of land-use and land-cover affected.
This tool will be among the first user-friendly GEE Apps that produce flood extent maps at a scale 
that will help emergency responders as well as the scientific community with rapid and reliable flood 
inundation information and improves the current methods of flood mapping.

# Statement of need

Floods, common natural disasters worldwide, resulted in approximately $40 billion in losses between 2011 
and 2015, as reported by the Financial Management of Flood Risk [@OECD:2016].
Science and technology advancements provide alternatives for managing natural disasters such as floods. 
Satellite-based flood inundation mapping is crucial for emergency responders, aiding crisis managers in 
monitoring and managing floods. It enhances situational awareness, identifying areas requiring immediate 
action across large geographical areas, expediting relief response activities.
Remote sensing is widely employed not only for flood inundation mapping but also for assessing flood impact, 
offering a comprehensive review to address diverse stakeholder needs [@Sadiq:2023]. These stakeholders have specific 
requirements aligned with particular objectives, serving various purposes.
• Flood monitoring
• Strategies for preventing and mitigating flood risks
• Emergency response planning
• Prioritizing preventive actions through classifying flooded areas
• Estimating the population at risk
• Land-use planning and management
• Public awareness campaigns
• Providing information for the insurance sector
Due to the unpredictable nature of flooding and the slow retrieval rate of satellite images, local implementation 
faces limitations. Relying solely on remotely sensed images poses challenges in fully capturing the scope of flood 
monitoring. This has prompted research into integrating multiple sources for improved flood mapping [@Hamidi:2023].
This research study introduces an App that uses multi-source and multi-temporal remote sensing data for fast flood 
monitoring. This App provides tools to facilitate flood monitoring tasks by defining a flood period and drawing a 
boundary to observe the flood extent conditions in their area of interest. Through this App, our aim is to empower 
decision-makers, first responders, scientists, and other stakeholders with clear, useful information, enabling them 
to better understand, prepare for, and respond to treacherous flooding hazards. This information is crucial, 
considering the populations, infrastructure facilities, urban area, and cropland at risk.

# Citations

- `@author:2016`  ->  "OECD (2016)"
- `[@Sadiq:2023]` -> "(Sadiq et al., 2023)"
- `[@Hamidi:2023]` -> "(Hamidi et al., 2023)"

# Acknowledgements

App created by Ebrahim Hamidi (University of Alabama) and reviewed by Brad G. Peter (University of Arkansas), 
funded by the National Science Foundation INFEWS Program and the U.S. Army Corps of Engineers. Also, partial 
support for development of this App is awarded through CUAHSI’s 2023 Hydroinformatics Innovation Fellowship (HIF).

# References
- OECD, Financial Management of Flood Risk. OECD, 2016. doi: 10.1787/9789264257689-en.
- R. Sadiq, M. Imran, and F. Ofli, “Remote Sensing for Flood Mapping and Monitoring,” in International Handbook of Disaster Research, A. Singh, Ed., Singapore: Springer Nature Singapore, 2023, pp. 679–697. doi: 10.1007/978-981-19-8388-7_178.
- E. Hamidi, B. G. Peter, D. F. Munoz, H. Moftakhari, and H. Moradkhani, “Fast Flood Extent Monitoring with SAR Change Detection Using Google Earth Engine,” IEEE Trans. Geosci. Remote Sensing, pp. 1–1, 2023, doi: 10.1109/TGRS.2023.3240097.
