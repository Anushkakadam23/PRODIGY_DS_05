# Traffic Accident Data Analysis Repository

Welcome to the repository for my analysis of traffic accident data, which I completed during my internship in data science at Prodigy Infotech. This project focuses on data preprocessing, exploratory data analysis (EDA), visualization, and extracting meaningful insights from a dataset that documents traffic accidents.

## Project Summary
The aim of this project is to examine traffic accident data to identify patterns and trends, pinpoint accident-prone areas, and deliver actionable insights that could contribute to improving road safety measures.

## Dataset Details
This is a countrywide car accident dataset that covers 49 states of the USA. The accident data were collected from February 2016 to March 2023, using multiple APIs that provide streaming traffic incident (or event) data. These APIs broadcast traffic data captured by various entities, including the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road networks. The dataset currently contains approximately 7.7 million accident records.
The [dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) used for this analysis comprises the following features:

| Feature            | Description                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------------------|
| ID                 | A unique identifier assigned to each accident record.                                              |
| Severity           | A numeric value ranging from 1 to 4 that indicates the severity of the accident, with 1 being the least severe and 4 the most severe. |
| Start_Time         | The local time when the accident commenced.                                                         |
| End_Time           | The local time when the accident concluded.                                                         |
| Start_Lat          | Latitude coordinate of the accident's starting location.                                            |
| Start_Lng          | Longitude coordinate of the accident's starting location.                                           |
| End_Lat            | Latitude coordinate of the accident's ending location.                                              |
| End_Lng            | Longitude coordinate of the accident's ending location.                                             |
| Distance(mi)       | The length of the road segment impacted by the accident, measured in miles.                         |
| Description        | A natural language summary of the accident.                                                         |
| Number             | The street number indicated in the accident's address.                                             |
| Street             | The name of the street where the accident occurred.                                                 |
| Side               | Indicates which side of the street (Left/Right) the accident took place on.                        |
| City               | The city in which the accident occurred.                                                            |
| County             | The county in which the accident occurred.                                                          |
| State              | The state in which the accident occurred.                                                           |
| Zipcode            | The postal code for the accident's location.                                                        |
| Country            | The country where the accident occurred.                                                             |
| Timezone           | The timezone associated with the accident location (e.g., Eastern, Central).                        |
| Airport_Code       | The code for the nearest airport-based weather station to the accident site.                        |
| Weather_Timestamp  | The timestamp for the weather observation at the time of the accident (in local time).              |
| Temperature(F)     | The temperature recorded at the time of the accident (in Fahrenheit).                              |
| Wind_Chill(F)      | The wind chill factor at the time of the accident (in Fahrenheit).                                  |
| Humidity(%)        | The percentage of humidity during the accident.                                                    |
| Pressure(in)       | The atmospheric pressure at the accident site (in inches).                                         |
| Visibility(mi)     | The visibility distance at the time of the accident (in miles).                                    |
| Wind_Direction     | The direction from which the wind was blowing during the accident.                                  |
| Wind_Speed(mph)    | The speed of the wind at the time of the accident (in miles per hour).                             |
| Precipitation(in)  | The amount of precipitation at the time of the accident (in inches), if applicable.                |
| Weather_Condition  | The weather conditions present during the accident (e.g., rain, snow, fog).                        |
| Amenity            | An indicator of nearby amenities at the accident location.                                          |
| Bump               | An indicator of the presence of speed bumps near the accident location.                             |
| Crossing           | An indicator of the presence of pedestrian crossings near the accident location.                    |
| Give_Way           | An indicator of the presence of give way signs near the accident location.                          |
| Junction           | An indicator of junctions near the accident location.                                               |
| No_Exit            | An indicator of no exit signs near the accident location.                                          |
| Railway            | An indicator of railway tracks in proximity to the accident location.                               |
| Roundabout         | An indicator of roundabouts near the accident location.                                             |
| Station            | An indicator of stations nearby the accident location.                                              |
| Stop               | An indicator of stop signs near the accident location.                                             |
| Traffic_Calming    | An indicator of traffic calming measures in the vicinity of the accident location.                  |
| Traffic_Signal     | An indicator of traffic signals nearby the accident location.                                       |
| Turning_Loop       | An indicator of turning loops in the vicinity of the accident location.                             |
| Sunrise_Sunset     | Indicates whether the accident occurred during day or night based on sunrise and sunset times.     |
| Civil_Twilight     | Indicates whether the accident occurred during day or night based on civil twilight.               |
| Nautical_Twilight  | Indicates whether the accident occurred during day or night based on nautical twilight.            |
| Astronomical_Twilight| Indicates whether the accident occurred during day or night based on astronomical twilight.      |

## Methodology
1. **Data Cleaning**: Addressed missing values, converted data types, and ensured uniformity across the dataset.
2. **Exploratory Data Analysis (EDA)**: Explored the distribution and correlations of key variables to reveal insights and patterns.
3. **Visualization**: Developed various graphs and charts to represent the data and findings visually.

## Key Insights
- **City-wise Accident Analysis**: Miami recorded the highest number of accidents, while Star Junction and Stromsburg had the fewest.
- **State-wise Accident Analysis**: California reported the highest accident figures, while South Dakota had the least.
- **Yearly Trends**: The year 2021 marked the highest incidence of accidents.
- **Severity Levels**: A significant number of accidents fell under severity level 2.
- **Weather Conditions**: Most accidents occurred under favorable weather conditions.
- **Timing of Accidents**: A large proportion of accidents took place during the morning hours.

## Conclusion
This analysis uncovers essential trends in traffic accident data, particularly highlighting high accident rates in densely populated regions like Miami and California. Additionally, many accidents transpired under clear weather conditions during the morning. These findings can inform safety initiatives and support policy decisions aimed at mitigating accidents and enhancing public safety.

## Contact Information
For any questions or feedback related to this project, please feel free to reach out to me:

**Anushka Kadam**  
Email: anushkapkadam@gmail.com
