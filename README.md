# Reducing Sign Clutter in Champaign and Urbana

## Organization Name
Urbana Public Works
 
## Local Sponsor
John Collins, Operations Division Manager for Urbana Public Works

## Overview
The Urbana Public Works Department promotes growth in the City of Urbana by maintaining, constructing and improving the City's infrastructure.  We preserve the quality of life for the citizens, visitors, businesses and government agencies (both within the City and in the surrounding areas).  Our department strives to provide prompt and courteous service in a professional, efficient and cost-effective manner to safeguard the safety, health and welfare of those we serve.
 
## Problem Statement
Signs are an important part of communicating to drivers and pedestrians about the restrictions for parking, driving, and walking around the community.  However, having too many signs in a location can be confusing and cause issues such as illegal parking or traffic accidents.  This project aims to identify locales where there are too many signs in a single location that could cause issues.  Additionally, sign data can be correlated with traffic incident and parking violation data to further validate issues.
 
## Evaluation criteria
Comprehensiveness of data profiling for existing sign data to identify outliers for cluttered sign locations

## Data Details

### urbana_traffic_signs.csv

The Urbana traffic sign data includes fields related to the street address, condition, and relevant text for the sign.

### urbana_traffic_sign_photos_mapping.csv

The mapping files give information about the Urbana traffic sign photos.  The photos can be downloaded from this Dropbox link: https://www.dropbox.com/s/krq97vhtdusuz50/urbana_traffic_sign_photo_files.zip?dl=0.


### champaign_traffic_signs.csv

The traffic sign data for Champaign includes information about location (latitude/longitude) and the text that is on the sign.  Details on how to use this dataset leveraging Wolfram One is here: https://datarepository.wolframcloud.com/resources/City-of-Champaign-Street-Signs.


| Field Name | Description |
| ---------- | ----------- |
| X | latitude |
| Y | longitude |
| OBJECTID | Internal feature number |
| Sign_Type | Type of Sign, for example street name or stop. |
| Size_ | Dimensions of the sign |
| Supplement | name which signs are supplemental to the sign in question; for example an all way stop sign would never be used without a stop sign so that sign is a Supplemental sign to the Stop Sign |
| Sign_Post | Sign Post Construction | 
| Year_Insta | Year Installed | 
| Category | Sign Category | 
| Notes | General note or comment field | 
| MUCTD | The MUTCD number of the sign, has to do with standard layout | 
| Ownership | Who owns the sign | 
| FACILITYID | layer unique ID for use in Public Work's Cityworks software | 
| Location_Adjusted | shows if position was from aerials or from survey GPS. | 
| Replacement_Zone | regional zone signs are found in, for internal tracking of replacement cycle | 
| Sign_Text | notes about sign text | 
| Set_ID | Internal grouping ID to help show which sign dots match, i.e. sign is on same pole | 



