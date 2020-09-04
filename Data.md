Dataset Used:

The detailed dataset of all road collisions (since 2004 to present) can be found [here](https://s3.us.cloud-object-storage.appdomain.cloud/cf-courses-data/CognitiveClass/DP0701EN/version-2/Data-Collisions.csv). This data was provided by the Seattle Police Department and recorded by Traffic Records Department.
The dataset consists of 37 independent fields and 194673 records, which includes both numerical and categorical data. The dependent field or label for the data set is SEVERITYCODE, which describes the fatality of an accident. The values under this label are categorised into fatality (3), serious injury (2b), inury (2), prop damage (1) and unknown (0).

Other attributes that have been taken into consideration for the analysis are 

1. LOCATION - Description of the general location of the collision, 
2. ADDRTYPE - Collision address types are 'Alley', 'Block' or 'Intersection'
2. ROADCOND - The condition of the road during the collision (for example, 'Wet', 'Dry', 'Snow/Slush', 'Ice', 'Sand/Mud/Dirt', 'Standing Water', 'Oil',etc.),
3. WEATHER - A description of the weather conditions during the time of the collision, (for example, 'Overcast', 'Raining', 'Clear', 'Snowing', 'Fog/Smog/Smoke', etc.),
4. JUNCTIONTYPE - Category of junction at which collision took place (for example, 'At Intersection (intersection related)', 'Mid-Block (not related to intersection)',etc.),
5. PERSONCOUNT - The total number of people involved in the collision (reflected as an integer),
6. VEHCOUNT - The number of vehicles involved in the collision (reflected as an integer),
7. LIGHTCOND - The light conditions during the collision (for example, 'Daylight', 'Dark - Street Lights On', 'Dark - No Street Lights', 'Dusk', 'Dawn', etc.)
8. SPEEDING - Whether or not speeding was a factor in the collision.
