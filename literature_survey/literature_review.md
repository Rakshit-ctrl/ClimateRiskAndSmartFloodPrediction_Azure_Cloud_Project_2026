3.1 Paper 1
Schumann, G., Giustarini, L., Tarpanelli, A., Jarihani, B., Martinis, S., et al. (2023). Flood Modeling and Prediction Using Earth Observation Data. Surveys in Geophysics, 44, 1553–1578. https://doi.org/10.1007/s10712-022-09751-y
Summary
This paper provides an overview of the ways in which Earth Observation (EO) technology helps in modeling and predicting floods. The role of satellite images, such as those from Sentinel-1, Sentinel-2, Landsat, MODIS, and other EO satellites, in monitoring flooding has been examined in the paper. This paper highlights the differences between optical imagery and SAR and suggests that SAR imagery is especially important since SAR instruments can be used to obtain information about flooding under any conditions. The study also considers the ways in which EO data can be integrated with hydrological models, data assimilation methods, and machine learning algorithms to increase the quality of predictions. The authors state that the combination of multiple sources of EO data improves flood modeling and prediction but also face some practical problems in the process.
Research Gap Analysis
Method	Earth Observation (EO), Remote Sensing, Hydrological Modelling, Machine Learning
Dataset	Sentinel-1, Sentinel-2, Landsat, MODIS, meteorological and hydrological datasets
Advantages	Wide geographical coverage, improved prediction accuracy, supports near real-time monitoring, integrates multiple data sources.
Limitations	High computational cost, heterogeneous data integration challenges, and limited real-time deployment.
Research Gap	Most studies focus on flood mapping or forecasting separately. Few provide an integrated cloud-based system that combines satellite imagery, weather data, AI models, and decision support for real-time flood prediction.
Possible Improvement	Develop a scalable cloud platform that automatically processes multi-source EO data and weather information using AI to generate real-time flood predictions and alerts.

3.2 Paper 2
Ghosh, B., Garg, S., Motagh, M., & Martinis, S. (2024). Automatic Flood Detection from Sentinel-1 Data Using a Nested UNet Model and a NASA Benchmark Dataset. PFG – Journal of Photogrammetry, Remote Sensing and Geoinformation Science, 92, 1–18. https://doi.org/10.1007/s41064-024-00275-1
Summary
This paper proposes an Automated Flood Detection System Based On Sentinel-1 SAR Images Using a Nested UNet Network And EfficientNet-B7 Architecture. This research article describes a framework for automated flood detection based on Sentinel-1 SAR imagery using the Nested UNet deep learning network with EfficientNet-B7 architecture. The algorithm has been trained using the publicly available NASA-IEEE GRSS flood dataset, which includes floods in Nebraska, North Alabama, Bangladesh, and Florence, and evaluated on further floods in Spain, India, and Vietnam in order to verify the capability of the network to generalize to other geographic areas. The authors compare the presented system with several UNet-based convolutional neural networks and study the influence of various SAR polarization combinations (VV, VH, and polarization ratios) by using Shapley analysis.
Research Gap Analysis
Method	Nested UNet (UNet++) with EfficientNet-B7 backbone, Deep Learning, SAR Image Segmentation
Dataset	NASA–IEEE GRSS Sentinel-1 flood dataset with additional Sentinel-1 flood events from Spain, India, and Vietnam
Advantages	High segmentation accuracy, robust performance across multiple geographical regions, effective utilisation of Sentinel-1 SAR imagery, improved feature extraction using EfficientNet.
Limitations	Requires large labelled datasets and high computational resources for training. Performance is influenced by SAR polarisation combinations and varying land-cover characteristics.
Research Gap	The proposed model focuses primarily on flood image segmentation after satellite data acquisition. It does not integrate live meteorological information, cloud-based processing pipelines, or end-user decision support for continuous flood monitoring and early warning.
Possible Improvement	Integrate the deep learning model into a cloud platform that combines real-time Sentinel-1 imagery, weather forecasts, automated processing, interactive dashboards, and alert generation for operational flood management.

3.3 Paper 3
Feng, D., et al. (2024). Rapid Inundation Mapping Using the US National Water Model, Satellite Observations, and a Convolutional Neural Network. Geophysical Research Letters, 51(10). https://doi.org/10.1029/2024GL109424
Summary
In this research paper, an efficient flood inundation mapping technique is introduced through the combination of the output from the United States National Water Model (NWM), satellite data and Convolutional Neural Networks (CNN). This framework seeks to enhance flood mapping in terms of accuracy and speed in extreme weather conditions. CNN uses the learned relationship between hydrological simulation and satellite-based flood observation data to produce high-resolution flood maps. This research was conducted on various flood events within the United States, and it was shown that there is a higher prediction accuracy than with the use of hydrological models alone.
Research Gap Analysis
Method	Convolutional Neural Network (CNN) integrated with the US National Water Model and satellite observations.
Dataset	US National Water Model outputs, satellite flood observations, and historical flood event data.
Advantages	Produces high-resolution flood maps, improves prediction accuracy, combines physical modelling with deep learning, and supports rapid emergency response.
Limitations	Primarily evaluated for flood events in the United States, requires substantial computational resources, and depends on the availability of accurate hydrological simulations.
Research Gap	The framework mainly focuses on rapid flood mapping after hydrological modelling and does not incorporate global satellite datasets, real-time weather forecasting, or cloud-native deployment for continuous monitoring.
Possible Improvement	Develop a scalable cloud platform that integrates global satellite imagery, weather forecasts, and AI models to provide continuous flood prediction, visualisation, and automated alerts for different geographical regions.

3.4 Paper 4
Sarker, M. M., et al. (2024). Vision Transformer for Flood Detection Using Satellite Images from Sentinel-1 and Sentinel-2. Water, 16(12), 1670. https://doi.org/10.3390/w16121670
Summary
In this paper, we explore the potential of using Vision Transformers for flood detection from Sentinel-1 SAR and Sentinel-2 optical satellite imagery. In contrast to typical CNN-based methods, Vision Transformers detect long-distance spatial dependencies in satellite imagery which help in detecting complicated flood patterns. The proposed vision transformer network is analyzed on multi-temporal Sentinel imagery from various flood events and compared against other deep learning techniques. The experiments conducted reveal that the proposed Vision Transformer outperforms others in terms of classification accuracy and generalization especially in heterogeneous terrains where conventional CNN based models fail.
Research Gap Analysis
Method	Vision Transformer (ViT) using Sentinel-1 SAR and Sentinel-2 optical imagery.
Dataset	Multi-temporal Sentinel-1 and Sentinel-2 satellite images collected from various flood events.
Advantages	Captures long-range spatial dependencies, improves flood classification accuracy, performs well across diverse landscapes, and effectively combines SAR and optical imagery.
Limitations	Requires large training datasets, high computational power, and longer training time compared to CNN-based models. Performance may decrease when sufficient labelled data is unavailable.
Research Gap	Although Vision Transformers improve flood detection accuracy, the study focuses mainly on image classification. It does not integrate meteorological data, cloud-based deployment, real-time inference, or automated disaster response mechanisms.
Possible Improvement	Combine Vision Transformer models with cloud computing, weather forecasting APIs, and real-time satellite data processing to develop an intelligent flood prediction and early warning platform capable of continuous monitoring.

3.5 Paper 5
Cian, F., Marconcini, M., Ceccato, P., & Giustarini, L. (2023). Mapping Floods from Remote Sensing Data and Quantifying the Effects of Surface Obstruction by Clouds and Vegetation. Remote Sensing of Environment, 292, 113588. https://doi.org/10.1016/j.rse.2023.113588
Summary
This paper examines the difficulties associated with creating flood maps through remote sensing, with special attention to the interference caused by cloud cover and vegetations that affect accurate identification of floods. The authors compare satellite images from Optical and Synthetic Aperture Radar (SAR) to examine the effect of various environmental conditions on the accuracy of flood mapping. They compare the effectiveness of optical and radar images and find that even though SAR works better in cloudy conditions, dense vegetation interferes with the detection of floods. Various methods of preprocessing and analyzing the images have been compared to mitigate these challenges. The findings show that a combination of various remote sensing data sources enhances flood detection accuracy.
Research Gap Analysis
Method	Remote sensing analysis using optical and SAR satellite imagery for flood mapping.
Dataset	Sentinel-1 SAR, Sentinel-2 optical imagery, and other Earth Observation datasets.
Advantages	Improves flood mapping accuracy, performs well under different environmental conditions, and highlights the benefits of combining multiple satellite sensors.
Limitations	Dense vegetation still affects SAR-based flood detection, optical imagery remains vulnerable to cloud cover, and additional preprocessing is required for accurate mapping.
Research Gap	The study mainly focuses on improving flood mapping accuracy using remote sensing techniques but does not incorporate AI-based prediction models, cloud-based processing, or automated decision-support systems for real-time flood forecasting.
Possible Improvement	Integrate multi-source satellite imagery with artificial intelligence and cloud computing to automate flood prediction, improve processing speed, and provide real-time alerts through an interactive platform.

3.6 Paper 6
Rahman, M. M., Hasan, M. K., Islam, M. R., et al. (2023). The State of the Art in Deep Learning Applications, Challenges, and Future Prospects: A Comprehensive Review of Flood Forecasting and Management. Sustainability, 15(13), 10543. https://doi.org/10.3390/su151310543
Summary
This paper conducts an extensive review on the use of deep learning algorithms in flood forecasting and disaster management. The authors review a number of neural network structures that include CNNs, RNNs, LSTM neural networks and hybrid deep learning networks. The paper discusses a range of datasets used in flood predictions which include the use of satellite images, rainfall, river water levels, and meteorological data. The review analyzes the advantages and disadvantages of each of the deep learning algorithms and recent advances in artificial intelligence based flood prediction. The paper concludes that deep learning algorithms provide better results in comparison to traditional statistical techniques, but they need huge amounts of data and powerful computational power as well as proper data pre-processing.
Research Gap Analysis
Method	CNN, RNN, LSTM, GRU, and hybrid deep learning models for flood forecasting.
Dataset	Satellite imagery, rainfall records, river water level measurements, weather observations, and historical flood datasets.
Advantages	High prediction accuracy, ability to model complex patterns, supports multiple data sources, and improves forecasting performance over traditional methods.
Limitations	Requires extensive training data, high computational cost, limited interpretability, and performance depends on data quality and availability.
Research Gap	Most reviewed studies focus on developing accurate AI models but provide limited discussion on deploying these models in scalable cloud environments with continuous data collection, monitoring, and automated alert generation.
Possible Improvement	Develop a cloud-native flood prediction platform that integrates deep learning models with real-time satellite imagery, weather APIs, cloud storage, and automated early warning systems to improve operational disaster management.

3.7 Paper 7
Bhuiyan, M. A. E., Rahman, M. S., Islam, M. R., et al. (2023). Know to Predict, Forecast to Warn: A Review of Flood Risk Prediction Tools. Water, 15(3), 427. https://doi.org/10.3390/w15030427
Summary
This review article evaluates the current status of flood risk prediction methods being used for forecasting and warning purposes. The authors study traditional hydrological models, Geographic Information Systems (GIS), remote sensing methods, machine learning, and deep learning methods used in flood prediction. In the review, the authors compare different models of predictions by their accuracy, efficiency, input data requirements, and applicability. The authors reveal that the usage of multiple sources of input data like rainfall, river flow, topography, and remote sensing greatly improves flood prediction outcomes. Moreover, the authors pay attention to the necessity of using early warning systems in order to reduce disasters impact, and stress that recent development in artificial intelligence improves forecast capabilities. However, there are still many problems in application of such systems for real disaster management.
Research Gap Analysis
Method	Hydrological models, GIS, Remote Sensing, Machine Learning, and Deep Learning.
Dataset	Rainfall records, river discharge data, Digital Elevation Models (DEM), satellite imagery, and historical flood datasets.
Advantages	Comprehensive comparison of flood prediction techniques, highlights the importance of multi-source data integration, and identifies recent AI developments in flood forecasting.
Limitations	Most prediction tools operate independently, require extensive preprocessing, and have limited scalability for continuous real-time monitoring.
Research Gap	Existing flood prediction tools focus primarily on prediction accuracy while giving limited attention to cloud-native deployment, automated data integration, scalable processing, and user-friendly decision support systems.
Possible Improvement	Develop a cloud-based intelligent flood prediction platform that integrates satellite imagery, meteorological information, AI models, interactive dashboards, and automated alert mechanisms for continuous flood monitoring.

3.8 Paper 8
Schumann, G., Hostache, R., Matgen, P., et al. (2026). The Potential of Earth Observation Data for Enhanced Flood Monitoring and Forecasting: A Consortium Assessment. Surveys in Geophysics. https://doi.org/10.1007/s10712-026-09935-w
Summary
The current study conducts an assessment of the use of Earth Observation (EO) data for the purpose of increasing the accuracy of floods monitoring and forecast by a consortium. Recent achievements in satellite remote sensing, high-resolution Earth Observation systems, hydrological modeling, and artificial intelligence are examined with regard to their impact on increasing the effectiveness of flood prediction systems. The increasing availability of satellite observations made available in near real-time is considered and the integration of such data into numerical weather prediction and hydrological models is also analyzed. At the same time, the challenges related to data interoperability and big geospatial data processing are addressed.
Research Gap Analysis
Method	Earth Observation, satellite remote sensing, hydrological modelling, AI-based analytics, and numerical weather prediction.
Dataset	Multi-source satellite imagery, Earth Observation missions, weather forecasts, and hydrological datasets.
Advantages	Provides a comprehensive overview of modern Earth Observation technologies, supports large-scale flood monitoring, and highlights future directions for flood forecasting.
Limitations	Primarily focuses on technological assessment rather than implementation details. Real-time deployment, cloud integration, and operational decision-support frameworks are discussed only at a conceptual level.
Research Gap	Despite significant advances in Earth Observation technologies, there is limited implementation of integrated platforms that combine satellite imagery, weather forecasting, artificial intelligence, cloud computing, and automated emergency response within a single operational system.
Possible Improvement	Design an end-to-end cloud-based flood prediction platform that continuously collects Earth Observation and weather data, performs AI-driven analysis, visualises flood-risk regions, and delivers automated early warning notifications to relevant stakeholders.
