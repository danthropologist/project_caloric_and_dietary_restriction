# @ Rebecca S. A. Brittain
# 29 October 2021
# RStudio version: 1.4.1106 Tiger Daylily

** this README explains the context for data file "nutrition_urine_biomarkers_by_follow_RSAB_29oct2021.csv" to be used for the GF PNAS manuscript

## filtering notes
```
This file only contains follows that were NN. Infants were excluded from this analysis, leaving only individuals who have been weaned (weaned immature, adolescent, adult). Dates range from 2003-07-07 to 2018-03-13. All nutritional calculations involving protein use available protein. All nutritional calculations using NDF assume low fermentation. 
```

## variables
```
This file contains 45 variables
```

## variable names and levels
```
 [1] "follow_number"                                
 [2] "date" - note this was formatted as POSIXct in YYYY-mm-dd but may not read in that way. PLEASE SPOT CHECK THIS COLUMN and that it matches the year, month, day columns        
 [3] "year"                                         
 [4] "month"                                        
 [5] "day"                                          
 [6] "name_focal" - these IDs have been updated to reflect Maria vN's most recent genetic IDs                                   
 [7] "class_focal" - category with combined age and sex classes, with distinctions between flanged/unflanged males, and adult females with and without dependents (without dependent is just "adult female")                                  
 [8] "sex_focal" - male, female                                    
 [9] "age_category" - adult, adolescent, weaned immature, infant. Infants have been excluded from this file.                                  
[10] "follow_type" - only NN follows were included in this file                                 
[11] "length_active_period_min" - length from first observation to last observation in minutes                     
[12] "ap_kcal" - kcal of available protein consumed per day. Various availalbe protein coefficients were used based on item type                                    
[13] "prev_day_ap_kcal" - kcal of available protein consumed by the same individual the previous day, when applicable                              
[14] "lipid_kcal" - kcal of lipids consumed per day                                   
[15] "prev_day_lipid_kcal" - kcal of lipids consumed by the same individual the previous day, when applicable                       
[16] "tnc_kcal" - kcal of total nonstructural carbohydrates consumed per day                                    
[17] "prev_day_tnc_kcal" - kcal of nonstructural carbohyrdates consumed by the same individual the previous day, when applicable                              
[18] "ndf_kcal_low" - kcal of neutral detergent fiber consumed (assuming low fermentation)                                
[19] "prev_day_ndf_kcal_low" - kcal of neutral detergent fiber consumed (assuming low fermentation) by the same individual the previous day, when applicable                          
[20] "total_kcal_using_ap_low_fermentation" - total kcal consumed per follow using available protein (as opposed to protein) and assuming low fermentation of NDF         
[21] "prev_day_total_kcal_using_ap_low_fermentation" - previous day value for total_kcal_using_ap_low_fermentation
[22] "total_kcal_npe_low_fermentation" - total kcal consumed from lipids, TNC, and NDF              
[23] "prev_day_total_kcal_npe_low_fermentation" - previous day value for total_kcal_npe_low_fermentation     
[24] "npe_to_ap" - ratio non-protein energy to available protein (kcals)                                
[25] "lipid_to_ap" - ratio of lipid to available protein (kcals)                                  
[26] "lipid_to_tnc" - ratio of lipid to total nonstructural carbohydrates (kcals)                                 
[27] "lipid_to_ndf_low" - ratio of lipid to neutral detergent fiber (kcals) assuming low fermentation
[28] "tnc_to_ap" - ratio of total nonstructural carbohydrates to available protein (kcals)                                     
[29] "tnc_to_ndf_low" - ratio of total nonstructural carbohdydrates to neutral detergent fiber (kcals) assuming low fermentation                              
[30] "ap_to_ndf_low" - ratio of available protein to neutral detergent fiber (kcals) assuming low fermentation                               
[31] "percent_ap" - percentage of total kcal consumed that are from available protein                                   
[32] "percent_lipid" - percentage of total kcal consumed that are from lipids                                
[33] "percent_ndf_low" - percentage of total kcal consumed that are from neutral detergent fiber (assuming low fermentation)                              
[34] "percent_tnc" - percentage of total kcal consumed that are from nonstructural carbohydrates                                  
[35] "fai" - fruit abundance index                                          
[36] "hi_low_quartile" - fruit abundance category (high or low) based on Erin's 2021 recalculations (former values may have changed slightly)                               
[37] "fruit_category_quartiles" - fruit abundance category (high, medium, low) based on Erin's 2021 recalculations (former values may have changed slightly)                        
[38] "ketones_combo" - Chemstrip ketone values. Field values were used over lab values. Lab values were used if field values were not recorded.                                 
[39] "pos_neg_dn" - Daniel Naumenko's positive/negative ketone analysis- 0 is negative and 1 is positive                                   
[40] "urea_sgcor" - urea value corrected by specific gravity                                   
[41] "urea_time_collected" - urine collection time of day for associated urea value                          
[42] "ucp_sgcor" - urinary c-peptide value corrected by specific gravity                                    
[43] "ucp_time_collected" - urine collection time of day for associated ucp value                           
[44] "dn15_result" - dn15 isotope result                                  
[45] "isotope_time_collected" - urine collection time of day for associated dn15 isotope value     
```

## observations
```
This file contains 5,133 observations (follows)
```
