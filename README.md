# <span style="font-size: 30px; color: #000000; ; font-weight: bold;">Exploratory Data Analysis on the Australian Black Summer Bush Fires using NASA satellite data</span>

#### <span style="font-size: 18px; color: #000000; font-weight: bold;">Context</span>
<p style="font-size: 15px; color: #333333;">
    The following EDA focuses on the 2019/2020 Australian Black Summer bushfires, utilizing data captured by NASA’s MODIS satellite instrument. The dataset spans the entire period of the fires, offering a comprehensive view of their extent, intensity, and progression. I have attempted to answer a set of critical questions that uncover the patterns and impact of this disaster. 
</p>

#### <span style="font-size: 18px; color: #000000; font-weight: bold;">Dataset</span>
<p style="font-size: 15px; color: #333333;">
    The NASA dataset represents fire data in Australia captured by NASA's MODIS satellite instrument. The dataset contains key attributes such as latitude, longitude, fire pixel temperature, acquisition date(UTC format), confidence, type and daynight. The ABS state and territories file was also utilized during this analysis.
<li>
  <a href="https://firms.modaps.eosdis.nasa.gov/data/country/modis/2019/modis_2019_Australia.csv" target="_blank" style="color: #0066cc; text-decoration: none;">2019 fire data</a>
</li>
<li>
  <a href="https://firms.modaps.eosdis.nasa.gov/data/country/modis/2020/modis_2020_Australia.csv" target="_blank" style="color: #0066cc; text-decoration: none;">2020 fire data</a>
</li>
<li>
  <a href="https://www.abs.gov.au/statistics/standards/australian-statistical-geography-standard-asgs-edition-3/jul2021-jun2026/access-and-downloads/digital-boundary-files/STE_2021_AUST_SHP_GDA2020.zip" target="_blank" style="color: #0066cc; text-decoration: none;">ABS states and territories file</a>
</li>
</p>

#### <span style="font-size: 18px; color: #000000; font-weight: bold;">Process</span>
<p style="font-size: 15px; color: #333333;">
    In this analysis, I begin by cleaning and merging the dataset to ensure data quality and consistency. To enhance the existing dataset, I incorporated the Australian Bureau of Statistics (ABS) shapefile for Australian states and territories. By leveraging the latitude and longitude data from the NASA dataset, I mapped each fire to its respective state or territory. Using all of this data I have answered the following questions and visualized the impact of this disaster.
</p>
<ol style="font-size: 15px; color: #333333;">
    <li>Which state recorded the most bushfire incidents during the Black Summer?</li>
    <li>During which months were bushfires most active?</li>
    <li>What is the average radiative power and fire pixel temperature for each month?</li>
    <li>What is the relationship between fire pixel temperature and radiative power?</li>
    <li>What is the difference in the average confidence of fire detections between daytime and night time observations?</li>
    <li>Are bushfires more likely to be detected during the day or night?</li>
    <li>Which state had the fires with the highest average radiative power?</li>
    <li>Which satellite detected the most fires?</li>
    <li>Create a heat map with a time slider showing all bush fires.</li>
    <li>Create a comprehensive map showing all bush fires.</li>
</ol>

Note: The maps have been commented out in the notebook to ensure it can be uploaded to GitHub without issues.

#### <span style="font-size: 18px; color: #000000; font-weight: bold;">Acknowledgements</span>
<p style="font-size: 16px; color: #333333;">
    The datasets used in this analysis is sourced from <a href="https://firms.modaps.eosdis.nasa.gov" target="_blank" style="color: #0066cc; text-decoration: none;">NASA FIRMS </a> and the <a href="https://www.abs.gov.au" target="_blank" style="color: #0066cc; text-decoration: none;">Australian Bureau of Statistics</a>.
</p>

#### <span style="font-size: 18px; color: #000000; font-weight: bold;">Demo</span>

<img width="674" height="510" alt="heatmap" src="https://github.com/user-attachments/assets/c6d04e63-63f8-4609-9804-6daf24e29771" />
<img width="1045" height="650" alt="heatmap_time" src="https://github.com/user-attachments/assets/7ab2d87b-e348-41cb-9ac5-fcc1e0dd0e7a" />


