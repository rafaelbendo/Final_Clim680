# Ice Concentration and the Arctic Oscillation Index

# By Rafael Bendo

## Introduction

Arctic sea ice concentration plays a pivotal role in Earth's climate system by controlling energy exchange between the ocean and atmosphere. The seasonal growth and retreat of sea ice regulate ocean salinity, heat flux, and weather systems beyond the Arctic. Over recent decades, dramatic declines in ice concentration have raised concerns about feedback mechanisms such as the ice-albedo effect, which amplifies warming by increasing solar energy absorption. These processes not only exacerbate Arctic warming but also disrupt atmospheric and oceanic circulation patterns, linking the Arctic to global climate variability.

The Arctic Oscillation (AO) serves as a crucial mediator of these changes, driving shifts in pressure systems that influence wind patterns, temperature, and ice dynamics. In its positive phase, the AO strengthens the polar vortex, stabilizing ice by confining cold air over the Arctic. During negative phases, however, disrupted circulation patterns allow heat intrusions, triggering ice melt. These oscillatory patterns underscore the interconnectedness of Arctic sea ice and broader climate phenomena, highlighting the importance of monitoring AO phases to understand global climate impacts better.

## Arctic Oscillation (AO)

The Arctic Oscillation (AO) is a climate index that describes the variability in atmospheric pressure patterns between the Arctic and the mid-latitudes. It represents the state of the polar vortex and the strength of westerly winds encircling the Arctic at approximately 55°N. The AO has two primary phases:

Positive Phase: Characterized by lower-than-average atmospheric pressure over the Arctic and higher-than-average pressure over the mid-latitudes. This phase strengthens the polar vortex, confines cold air masses to the Arctic, and results in relatively stable Arctic sea ice conditions. It is often associated with milder winters in the mid-latitudes and less frequent cold air outbreaks.

Negative Phase: Marked by higher-than-average atmospheric pressure over the Arctic and lower-than-average pressure over the mid-latitudes. This phase weakens the polar vortex, allowing cold Arctic air to spill into the mid-latitudes, often leading to harsher winters and increased ice melt due to the intrusion of warm air into the Arctic region.

![image](https://github.com/user-attachments/assets/df9deb4e-ebe1-453f-8912-1393cde2a3ce)

## DATA

* Arctic Oscillation (AO) Index by NOAA/CPC
  
The Arctic Oscillation (AO) Index is a key dataset provided by the National Oceanic and Atmospheric Administration’s Climate Prediction Center (NOAA/CPC). The AO Index quantifies the phase and intensity of the Arctic Oscillation, a large-scale atmospheric circulation pattern that governs weather and climate variability in the Arctic and mid-latitudes. It is derived from pressure anomalies at sea level between the Arctic (20°N to 90°N) and the mid-latitudes (30°N to 50°N).

The dataset is valuable for analyzing temporal and spatial variability in Arctic climate patterns, serving as a predictor for phenomena such as sea ice extent, temperature anomalies, and storm tracks.

![image](https://github.com/user-attachments/assets/39b7a94b-fadf-46f7-8f75-6fdcece62d06)

This plot represents the Arctic Oscillation (AO) Index over time, spanning from the 1950s to the 2020s. The AO Index exhibits frequent fluctuations between positive and negative phases. Periods of higher amplitude spikes are noticeable, particularly in the positive phase (e.g., the early 2010s show strong positive AO activity). The negative phase is also pronounced, with deep troughs visible, especially in the 1950s and 1960s.

The Arctic Oscillation Index reflects atmospheric pressure anomalies and their influence on Arctic and mid-latitude climates. This plot provides insights into how the AO has oscillated over several decades, revealing periods of climatic variability that likely correlate with temperature and sea ice changes in the Arctic.

* COBE-SST2 (Centennial Observation-Based Estimates of Sea Surface Temperature, Version 2)

COBE-SST2 is a globally gridded dataset of sea surface temperatures (SST), produced by the Japan Meteorological Agency (JMA). It provides long-term, high-resolution records of SST based on historical observations from ships, buoys, and satellites. This dataset is particularly useful for monitoring oceanic changes in the Arctic, where SST fluctuations directly affect sea ice formation and melting.

Sea ice concentration datasets provide a measure of the proportion of an ocean surface covered by ice, expressed as a percentage. These datasets are often derived from satellite observations, such as those from passive microwave sensors. They offer daily to monthly resolutions, enabling analysis of seasonal and interannual changes in ice coverage.

The integration of these datasets—AO Index, COBE-SST2, and sea ice concentration—provides a robust framework for investigating the Arctic's response to climatic drivers, facilitating detailed analysis of the interplay between atmospheric circulation, ocean temperatures, and cryospheric changes.

![image](https://github.com/user-attachments/assets/a751a110-3d3c-4966-950d-1554ad1a09e2)

This figure shows monthly mean Sea Ice Concentration (%) over time in a specific Arctic region. It consists of 12 panels, one for each month, illustrating seasonal variations in sea ice concentration.

Winter Months (January–March): High sea ice concentration, covering most of the mapped area. Spring and Early Summer (April–June): A gradual reduction in ice coverage is observed, with areas expanding near coastal regions. Summer Months (July–September): Minimum ice concentration is evident, with large areas of open water, particularly near coastal and southern regions. Autumn and Early Winter (October–December): Ice begins to reform, transitioning back to high concentrations by December.
Geographical Features:

The figure highlights the seasonal cycle of sea ice in the Arctic, where ice builds up during colder months and retreats during warmer months. This behavior is critical for understanding Arctic climate dynamics and the impacts of global warming on ice extent.


# Results and Analysis

Project Notebook via Github
Located within my Final_Clim680 repository is a series of jupyter notebooks containing all of the labeled and commented code that was used in my analysis. Link:

Each topic will be discussed separately, along with a link to each relevant notebook.

Conda Environment
The climate.yml file is shown to define the environment needed to run all code successfully.

Function creation
A function was created to calculate climatologies and anomalies in the file climo_anoms_function.py, labeled as climo and anoms in each jupyter notebook. This is in addition to the clim680 function generated in class to calculate xyticks.

Link to climo,anoms function

Figures
The figures from my project notebook are saved in a separate ‘figures’ subdirectory, as well as shown in the project notebook.

Link to figures



# LOWESS and regression line

![image](https://github.com/user-attachments/assets/f8081c53-7f20-4769-bde2-ca78716efcb8)


![LOWESS](https://github.com/user-attachments/assets/f74a304d-0641-4e0f-85c4-0050e94c0151)





![image](https://github.com/user-attachments/assets/eef50e3f-6087-4567-aa84-e758b131b2c6)

This figure shows the Sea Ice Concentration Anomaly (%) over time. The anomaly values represent deviations from the long-term average sea ice concentration.

There is a gradual decline in the sea ice concentration anomaly, particularly noticeable from the late 2000s onward. This reflects a long-term decrease in Arctic sea ice concentration, likely related to climate change and global warming.

Between 1950 and 1970, the anomalies appear more variable but centered around zero, indicating smaller deviations from the average.

Starting from the 1980s, negative anomalies become more frequent and pronounced. The anomalies reach their most negative values after 2000, indicating a significant reduction in sea ice concentration relative to the long-term mean.

The figure also shows considerable interannual variability throughout the time series, with peaks and troughs that might correspond to seasonal, regional, or atmospheric influences such as the Arctic Oscillation (AO) or El Niño-Southern Oscillation (ENSO). The declining trend is consistent with observed Arctic sea ice loss due to rising global temperatures. The variability suggests influences from natural climate oscillations or episodic weather events. This visualization highlights the need for further exploration of climate drivers contributing to these changes.

![image](https://github.com/user-attachments/assets/16ce43f7-92b4-48a9-b67c-f7fa56cc2216)

![image](https://github.com/user-attachments/assets/d92b8f38-4962-402a-9a2e-04928c59f134)

![image](https://github.com/user-attachments/assets/bae32308-43f2-43f5-b3c7-bcf124c0d3a4)

![animation_monthly_7](https://github.com/user-attachments/assets/d52e4fa1-6bb2-4f1f-a98c-f148f669aa34) 

![animation_monthly_8](https://github.com/user-attachments/assets/135b3079-401e-4127-aa0c-eaba6358b88f)

![animation_monthly_9](https://github.com/user-attachments/assets/d6d35493-e4dd-4e1d-b5d2-5ce97622ad84)



![image](https://github.com/user-attachments/assets/9a63eaca-0437-4fa0-8d03-e30c0994d172)



