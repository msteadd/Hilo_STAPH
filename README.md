# Hilo_STAPH
Raw data, analysis, and predictive models for the manuscript titled "Detection and modeling of _Staphylococcus aureus_ and fecal bacteria in Hawaiian coastal waters and sands" submitted to the journal, Water Environment Research. 

Amongst these files including the raw data and R Markdown data analyses in R, includes a file with predictive models of _S. aureus_, Methicillin-Resistant _S. aureus_ (MRSA), _Enterococcus_ spp., and _C. perfringens_ in concentrations seawater and sand based on data from this study. 

These models were initially developed in R, and include negative binomial generalized linear models (GLM) and generalized linear mixed models (GLMM) for predictions of concentrations. 

These models can assist in predictions of these bacteria if all required data is included. These required data include physicochemical and environmental parameters, specifically salinity (in practical salinity units or ppt), water temperature (°C), dissolved oxygen (mg/L), water turbidity (NTU), 24-hour cumulative rainfall (cm), linear beach distance to the closest discharging stream (meters), denisty of on-site sewage disposal systems within 1-km of the beach (quantity), and tidal height (also known as water level, meters). Once these data are included, the excel sheet will automatically produce predicted concentrations of _S. aureus_, MRSA, and FIB in seawater and sand. Please see the full manuscript (once published) for more details.

These models are the first of their kind for making predictions of _S. aureus_ and MRSA concentrations in seawater and sand. We hope to continue expanding and developing predictive models for _S. aureus_ with data from different regions and including more physicochemical and environmental parameters.
