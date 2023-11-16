# Distribution-Characteristics-and-Influencing-Factors-of-Billboards

<p align="center">
<img width="263" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/44c763c9-cbc1-4832-a08d-ff3255140ca9">
</p>

--------
In order to explore the characteristics of billboard distribution in Wuhan, this study employs various spatial analysis methods. These methods include the Average Nearest Neighbor method and Kernel Density analysis to investigate whether billboards exhibit clustered distribution and the extent of clustering. Additionally, the Standard Deviation Ellipse analysis is used to examine the directional distribution characteristics of billboards. Hotspot and Coldspot analysis is used to identify areas with high and low concentrations of billboards. Furthermore, Geodetector analysis is employed to explore the factors influencing billboard distribution. First, basic data processing was carried out to gain a preliminary understanding of the spatial distribution of billboards in Wuhan. Subsequently, various methods such as the Average Nearest Neighbor were employed to provide a detailed description of the spatial distribution characteristics of billboards in Wuhan. The experimental results obtained will contribute to determining suitable weightings for factors influencing the optimization of billboard placement in Wuhan.

# Study Area and Data
<p align="center">
<img width="220" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/c0090f48-3f23-46e7-88e5-1b7cd6ed7cc9">
</p>
Research is primarily conducted in the city of Wuhan. Wuhan is located in the central part of China, on the northern bank of the Yangtze River. As the provincial capital of Hubei province, Wuhan holds significant political, economic, cultural, and historical importance for both the province and China. This article focuses on the entire city of Wuhan and analyzes the spatial distribution of billboards throughout the city. 
<p align="center">
<img width="366" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/ee7605b0-d4f7-4b83-b0c3-04eb3e89a694">
</p>
The data for the study area includes building dataset, road dataset, population dataset, public transportation route dataset, bike share service point dataset, charging station point dataset, and billboard point dataset. These data can be categorized into four main categories of influences, which are geographic influences, footfall influences, audience influences, and mobility influences. All these data have a positive effect on the location of billboards, and the comprehensive use of these data to select the location can improve the exposure rate of billboards so that the advertising effect can be as optimal as possible.

# Methods
In this study, the Geodetector model is used to quantify the individual and interactive effects of various influencing factors on the spatial distribution of billboards in Wuhan City. It aims to reveal the primary influencing factors of billboard spatial distribution in Wuhan and the ways in which these factors interact. 
<p align="center">
<img width="354" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/a4158e91-3b58-4ac0-81c8-791928675da1">
</p>
The q-value falls within the range of [0,1], indicating the magnitude of the impact of this influencing factor on the spatial distribution of billboards in Wuhan City.
A larger value indicates a greater impact.

# Results
Spatial Analysis：It is evident that billboard locations are notably concentrated within the central urban regions of Wuhan City. This concentration includes districts such as Jianghan District, Hanyang District, and Wuchang District. This observation aligns seamlessly with the primary areas of urban development within Wuhan City, specifically the convergence point of the Hanjiang and Yangtze Rivers. These regions are known for their robust economic development and consequently exhibit a higher demand for billboards.
<p align="center">
<img width="167" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/05b10643-b7ab-4377-93ca-ac55450ac386">
</p>
Standard Deviational Ellipse：After conversion, it is determined that an error ellipse, centered at approximately 30°34'40.74"N, 114°18'21.81"E, can effectively encompass around 98% of the billboard locations within Wuhan City. Moreover, it becomes apparent that the clustered regions of billboards predominantly follow a northwest to southeast distribution pattern, covering a substantial portion of the central urban development zone in Wuhan City. 
<p align="center">
<img width="204" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/4a5cb94f-1450-4ced-8206-2d7815f17fb9">
</p>
<p align="center">
<img width="204" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/9e35d351-0bec-4270-88f2-39c8d705d58a">
</p>
Average Nearest Neighbor：The spatial pattern among the points is determined by comparing the average distance of the nearest point pairs. In the analysis report, showing a p-value less than 0.05. This finding suggests that billboard locations are not randomly distributed, as also highlighted in the report. Notably, the Z-score in the report is a very small negative value, reinforcing the conclusion that the distribution of billboards in Wuhan City exhibits significant clustering and is not a result of random data generation.
<p align="center">
<img width="192" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/caa1741c-1277-4a48-8f9f-c7a2b73cdf94">
</p>
Hot Spot Analysis and Kernel Density Analysis：The hot spot analysis results show that the distribution of billboards in Wuhan presents an obvious hot spot aggregation pattern. In contrast, the cold spots are distributed in a ring pattern, mainly in the farther outer regions. The results of the kernel density analysis show a unique multi-modal pattern, indicating polarization.
<p align="center">
<img width="204" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/4bdcac9c-35ff-4b4d-ae23-7e7e45fd786f">
</p>
<p align="center">
<img width="205" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/d27aed0f-2f7f-41ca-a628-65fdc5e81ced">
</p>
Geodetector：Bus Route Density has the highest explanatory power, indicating that the spatial distribution of billboards in Wuhan City is most strongly influenced by the distribution of bus route density, meaning that there is a strong consistency between the bus route density and the spatial distribution of billboards in Wuhan City. Secondary factors are the Number of Shared Bicycle Returns and the Number of Shared Bicycle Rentals per Kilometer Grid, indicating that shared bicycles are also important factors affecting the spatial distribution of billboards in Wuhan City. The results of the Interaction Detector are shown in the figure, indicating that the spatial differentiation pattern of billboards in Wuhan City is not controlled by a single factor but is the result of the combined action of multiple factors. Among these interactions, the interactions between Bus Route Density and Charging Station Density, are relatively large. The interactions between Road Density and Population Density and are relatively small. 
<p align="center">
<img width="290" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/9bb8ddb9-1136-46ae-93de-20143f28a0e6">
</p>
<p align="center">
<img width="298" alt="image" src="https://github.com/HIGISX/Distribution-Characteristics-and-Influencing-Factors-of-Billboards/assets/115253111/bff30b58-7cfd-4aff-9dd7-22514a701dbf">
</p>

# Conclusion
1.By utilizing various spatial analysis methods, we explore the influence of different factors on the spatial distribution of billboards. 

2.From the aforementioned analysis, it is evident that the optimal placement of billboards should be closely associated with public transportation infrastructure and other relevant structures.

3.The methods and tools employed in this paper can serve as a reference for spatial distribution analysis in other cities. 

4.This study has certain limitations, such as the failure to consider the impact of competition between different types of billboards on their placement. In the future, we will continue to improve and expand spatial analysis methods, focusing on delving deeper into the spatial distribution patterns of billboards in Wuhan. 

5.This will provide more valuable insights for optimizing the placement of billboards.

