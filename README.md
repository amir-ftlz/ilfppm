# A Survey and Future Outlook on Indoor Location Fingerprinting Privacy Preservation

A curated list of papers on privacy-preserving indoor fingerprinting localization.

Papers are sorted by the proposed privacy-preserving mechanism. 
These include Cryptographic Models, Anonymization, Differential Privacy, and Federated Learning.

This repository serves as a complement to the survey below.

[**A survey and future outlook on indoor location fingerprinting privacy preservation**](https://www.sciencedirect.com/science/article/abs/pii/S1389128625001677?via%3Dihub)

````bibtex
@article{FATHALIZADEH2025111199,
title = {A survey and future outlook on indoor location fingerprinting privacy preservation},
journal = {Computer Networks},
pages = {111199},
year = {2025},
issn = {1389-1286},
doi = {https://doi.org/10.1016/j.comnet.2025.111199},
url = {https://www.sciencedirect.com/science/article/pii/S1389128625001677},
author = {Amir Fathalizadeh and Vahideh Moghtadaiee and Mina Alishahi},
keywords = {Indoor localization, Location privacy, Privacy-preserving, Location fingerprinting}
}
````

If you feel this repository is helpful, please cite the survey above.

## Quick Links
**Papers sorted by privacy-preserving mechanism:** | [Cryptographic Models](#cryptographic-models-back-to-top) | [Anonymization](#anonymization-back-to-top) | [Differential Privacy](#differential-privacy-back-to-top) | [Federated Learning](#federated-learning-back-to-top) | 

## Indoor Location Fingerprinting Privacy Preserving Mechanism (ILFPPM)

### Cryptographic Models [[Back to Top](#a-survey-and-future-outlook-on-indoor-location-fingerprinting-privacy-preservation)] 

<p align="center">
<img src="images/crypt.png" alt="Image 1" width="800"/>
</p>


| Year | Paper | Privacy Method | Localization | Dataset | Paper Link |
|------|-------|---------------|--------------|---------|---------|
| 2014 | **Achieving privacy preservation in WiFi fingerprint-based localization** | Paillier | kNN | Simulated, Private | [Link](https://ieeexplore.ieee.org/document/6848178), [pdf](https://nsec.sjtu.edu.cn/publications/2014/Achieving%20Privacy%20Preservation%20in%20WiFi%20Fingerprint-Based%20Localization.pdf)|
| 2015 | **A Privacy-Preserving Fuzzy Localization Scheme with CSI Fingerprint** | Paillier | Fuzzy Logic | CRAWDAD | [Link](https://ieeexplore.ieee.org/document/7417168), [pdf](https://cse.usf.edu/~yliu21/webresources/?n=pdf/FuzzyGC15.pdf) |
| 2016 | **Privacy-Preserving Wi-Fi Fingerprinting Indoor Localization** | Paillier | SVM | Private | [Link](https://link.springer.com/chapter/10.1007/978-3-319-44524-3_13)|
| 2018 | **The Death and Rebirth of Privacy-Preserving WiFi Fingerprint Localization with Paillier Encryption** | Paillier, Garbled Circuit | - | - | [Link](https://ieeexplore.ieee.org/document/8486221)|
| 2018 | **Modeling Privacy in WiFi Fingerprinting Indoor Localization** | Paillier, Garbled Circuit | - | Simulated | [Link](https://link.springer.com/chapter/10.1007/978-3-030-01446-9_19), [pdf](https://helda.helsinki.fi/server/api/core/bitstreams/e8276b94-9cb4-4fb9-9362-7245bc4fd938/content)|
| 2018 | **Received Signal Strength Quantization for Secure Indoor Positioning via Fingerprinting** | Paillier, Garbled Circuit | kNN | Private, JUIndoorLoc, Tampere Uni | [Link](https://ieeexplore.ieee.org/document/8440910), [pdf](https://encrypto.de/papers/RYTLJSL18.pdf)|
| 2019 | **Server-Side Fingerprint-Based Indoor Localization Using Encrypted Sorting** | Paillier, DGK Algorithm | kNN | Colombia Uni | [Link](https://ieeexplore.ieee.org/abstract/document/9059316), [pdf](https://arxiv.org/pdf/2008.11612)|
| 2019 | **On Location Privacy in Fingerprinting-Based Indoor Positioning System: An Encryption Approach** | ABY Framework, Arithmetic Sharing, Boolean Sharing, Yao's Sharing | kNN | Simulated, Private | [Link](https://dl.acm.org/doi/10.1145/3347146.3359081)|
| 2019 | **PILOT: Practical Privacy-Preserving Indoor Localization Using OuTsourcing** | Trusted Third Party | kNN | Simulated | [Link](https://ieeexplore.ieee.org/document/8806758), [pdf](https://encrypto.de/papers/JLLRSTY19.pdf)|
| 2019 | **A Privacy-Preserving Protocol for Indoor Wi-Fi Localization** | Paillier, Spatial Bloom | kNN | - | [Link](https://dl.acm.org/doi/10.1145/3310273.3323400), [pdf](https://cora.ucc.ie/server/api/core/bitstreams/cb653511-77df-4b5d-b4a0-7c4180eae688/content)|
| 2020 | **Lightweight Privacy-Preserving Scheme in Wi-Fi Fingerprint-Based Indoor Localization** | Paillier | kNN | Private | [Link](https://ieeexplore.ieee.org/document/9040904)| 
| 2020 | **Practical Privacy Protection Scheme In WiFi Fingerprint-based Localization** | Expectation-maximization, Bayes Network | kNN | UJIIndoorLoc | [Link](https://ieeexplore.ieee.org/document/9260101)|
| 2021 | **Practical Privacy-Preserving Indoor Localization Based on Secure Two-Party Computation** | Paillier, One Time Pad, Garbled Circuits | kNN | Simulated, Uni of Helsinki | [Link](https://ieeexplore.ieee.org/document/9079655), [pdf](https://helda.helsinki.fi/server/api/core/bitstreams/4cc14b4b-6f3f-4350-b368-99df5cfe8e57/content)|
| 2022 | **FAPRIL: Towards Faster Privacy-Preserving Fingerprint-Based Localization** | Arithmetic Sharing, Delta Sharing, Yao's Sharing | kNN | Simulated | [Link](https://www.scitepress.org/PublishedPapers/2022/112635/), [pdf](https://www.scitepress.org/PublishedPapers/2022/112635/112635.pdf)|
| 2022 | **PriHorus: Privacy-Preserving RSS-Based Indoor Positioning** | Paillier | MLE | Private | [Link](https://ieeexplore.ieee.org/document/9839103)|
| 2024 | **Privacy-preserving indoor localization based on inner product encryption in a cloud environment** | Inner Product Encryption | kNN | Simulated, JUIndoorLoc | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0950705121011126)|



### Anonymization [[Back to Top](#a-survey-and-future-outlook-on-indoor-location-fingerprinting-privacy-preservation)] 

<p align="center">
  <img src="images/anon.png" alt="Image 1" width="400"/>
  <img src="images/anon2.png" alt="Image 2" width="379"/>
</p>

| Year | Paper | Privacy Method | Localization | Dataset | Paper Link |
|------|-------|---------------|--------------|---------|---------|
| 2012 | **$K$-Anonymity in Indoor Spaces through Hierarchical Graphs** | $k$-anonymity, Hierarchical graph | - | Simulated | [Link](https://dl.acm.org/doi/10.1145/2442616.2442622)|
| 2014 | **Location Privacy in Buildings: A 3-Dimensional $K$-Anonymity Model** | $k$-anonymity, Cloaking, Obfuscation | kNN, SVM | Simulated | [Link](https://ieeexplore.ieee.org/document/7051770)|
| 2015 | **Privacy-Preserving Indoor Localization on Smartphones** | $k$-anonymity, Bloom Filter | - | Simulated, CSUCY, KIOSUCY, Crawdad | [Link](https://ieeexplore.ieee.org/document/7118199)|
| 2016 | **Location $K$-Anonymity in Indoor Spaces** | $k$-anonymity, $\ell$-diversity, Hierarchical graph | kNN | Simulated | [Link](https://link.springer.com/article/10.1007/s10707-015-0241-y)|
| 2018 | **A Privacy Preserving Method for Crowdsourcing in Indoor Fingerprinting Localization** | Hilbert Curve, $k$-anonymity | NN | Simulated | [Link](https://ieeexplore.ieee.org/document/8566402)|
| 2020 | **A Low-complexity trajectory privacy preservation approach for indoor fingerprinting positioning systems** | $k$-anonymity, Randomization, Permutation | kNN | Simulated, CRI | [Link](https://www.sciencedirect.com/science/article/abs/pii/S2214212619304338), [pdf](https://www.researchgate.net/publication/341394589_A_Low-complexity_trajectory_privacy_preservation_approach_for_indoor_fingerprinting_positioning_systems)|
| 2020 | **Preserving Privacy in WiFi Localization With Plausible Dummy Locations** | $k$-anonymity | kNN | Simulated | [Link](https://ieeexplore.ieee.org/document/9130897)|
| 2021 | **Privacy preserving in indoor fingerprint localization and radio map expansion** | $k$-anonymity, Hilbert Curve, Bloom Filter | kNN | Simulated, CRI, CSUCY, KIOSUCY, PosData | [Link](https://link.springer.com/article/10.1007/s12083-020-00950-1), [pdf](https://repository.uel.ac.uk/download/cae3581a1c556150ac25bb0e46752385696c210abc1bf7d674133cfab88eedf6/3084038/Main_Manuscript-1.pdf)|
| 2022 | **On the privacy protection of indoor location dataset using anonymization** | $k$-anonymity, $\ell$-diversity, $t$-closeness, ($\alpha,k$)-anonymity, $\delta$-presence | - | Simulated, CRI, UJIIndoorLoc | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0167404822000645), [pdf](https://www.researchgate.net/publication/358792446_On_the_Privacy_Protection_of_Indoor_Location_Dataset_using_Anonymization)|


### Differential Privacy [[Back to Top](#a-survey-and-future-outlook-on-indoor-location-fingerprinting-privacy-preservation)] 

<p align="center">
<img src="images/dp.png" alt="Image 1" width="800"/>
</p>

| Year | Paper | Privacy Method | Localization | Dataset | Paper Link |
|------|-------|---------------|--------------|---------|---------|
| 2016 | **Privacy-preserving crowdsourced site survey in WiFi fingerprint-based localization** | CDP, Paillier | kNN | Private | [Link](https://jwcn-eurasipjournals.springeropen.com/articles/10.1186/s13638-016-0624-2), [pdf](https://d-nb.info/1099610346/34)|
| 2017 | **CollabLoc: Privacy-Preserving Multi-Modal Localization via Collaborative Information Fusion** | LDP, Two-step classifier | - | Multi Building, Rutgers Uni | [Link](https://ieeexplore.ieee.org/document/8038390), [pdf](https://www.researchgate.net/publication/319886948_CollabLoc_Privacy-Preserving_Multi-Modal_Localization_via_Collaborative_Information_Fusion)|
| 2017 | **WiFi fingerprint releasing for indoor localization based on differential privacy** | LDP, Delaunay triangulation, Range generalization | - | Simulated | [Link](https://ieeexplore.ieee.org/document/8292470)|
| 2018 | **Application of Local Differential Privacy to Collection of Indoor Positioning Data** | LDP, Randomized Response | - | Simulated, Sangmyung Uni | [Link](https://ieeexplore.ieee.org/document/8253434), [pdf](https://www.researchgate.net/publication/322376484_Application_of_Local_Differential_Privacy_to_Collection_of_Indoor_Positioning_Data)|
| 2018 | **DP3: A Differential Privacy-Based Privacy-Preserving Indoor Localization Mechanism** | CDP, AP fuzzification, Finger Clustering, Finger Permutation | - | PosData | [Link](https://ieeexplore.ieee.org/document/8493532)|
| 2018 | **P3-LOC: A Privacy-Preserving Paradigm-Driven Framework for Indoor Localization** | LDP, Segmenting Data, $k$-anonymity | - | Private | [Link](https://ieeexplore.ieee.org/document/8542955), [pdf](https://www.cse.cuhk.edu.hk/~cslui/PUBLICATION/TON_LOC_2018.pdf)|
| 2019 | **Workload-Aware Indoor Positioning Data Collection via Local Differential Privacy** | LDP, Randomized Encoding | - | Simulated, Beijing Taxi, Trajectory | [Link](https://ieeexplore.ieee.org/document/8736750)|
| 2022 | **Hide me Behind the Noise: Local Differential Privacy for Indoor Location Privacy** | LDP, Local Hashing, Unary Encoding, Histogram Encoding, Random response, RAPPOR | - | JUIndoorLoc, CRI | [Link](https://ieeexplore.ieee.org/document/9799430), [pdf](https://www.researchgate.net/publication/361729310_Hide_me_Behind_the_Noise_Local_Differential_Privacy_for_Indoor_Location_Privacy)|
| 2022 | **A Differentially Private Indoor Localization Scheme with Fusion of WiFi and Bluetooth Fingerprints in Edge Computing** | LDP, Edge–cloud collaboration | FSELM | Private | [Link](https://link.springer.com/article/10.1007/s00521-021-06815-9)|
| 2022 | **3D Geo-Indistinguishability for Indoor Location-Based Services** | GeoInd, Laplace Mechanism | - | Simulated | [Link](https://ieeexplore.ieee.org/document/9646489)|
| 2023 | **Indoor Geo-Indistinguishability: Adopting Differential Privacy for Indoor Location Data Protection** | GeoInd, Laplace Mechanism, Distance calculation, RSS Generation | - | Simulated, JUIndoorLoc, CRI | [Link](https://ieeexplore.ieee.org/document/10041019)|
| 2023 | **Indoor Semantic Location Privacy Protection With Safe Reinforcement Learning** | GeoInd, Reinforcement learning | - | Simulated | [Link](https://ieeexplore.ieee.org/document/10171230)|
| 2024 | **Preserving location privacy against inference attacks in indoor positioning system** | LDP, GeoInd | - | Geolife, Gowalla | [Link](https://link.springer.com/article/10.1007/s12083-023-01609-3)|



### Federated Learning [[Back to Top](#a-survey-and-future-outlook-on-indoor-location-fingerprinting-privacy-preservation)] 

<p align="center">
<img src="images/fl.png" alt="Image 1" width="800"/>
</p>

| Year | Paper | Privacy Method | Localization | Dataset | Paper Link |
|------|-------|---------------|--------------|---------|---------|
| 2019 | **FLoc: Fingerprint-Based Indoor Localization System under a Federated Learning Updating Framework** | AutoEncoder | DNN | Private | [Link](https://ieeexplore.ieee.org/document/9066152)|
| 2020 | **Pseudo Label-Driven Federated Learning-Based Decentralized Indoor Localization via Mobile Crowdsourcing** | FedAvg | SAEC | UJIIndoorLoc | [Link](https://ieeexplore.ieee.org/document/9103044)|
| 2020 | **Federated Learning for RSS Fingerprint-based Localization: A Privacy-Preserving Crowdsourcing Method** | FedAvg | MLP | UJIIndoorLoc | [Link](https://ieeexplore.ieee.org/document/9148111)|
| 2021 | **Personalized Federated Learning over non-IID Data for Indoor Localization** | FedAvg, FedAmp, FedAmp-fusion | MLP | UJIIndoorLoc | [Link](https://ieeexplore.ieee.org/document/9593115), [pdf](https://www.researchgate.net/publication/353171063_Personalized_Federated_Learning_over_non-IID_Data_for_Indoor_Localization)|
| 2021 | **A Privacy-Preserved Online Personalized Federated Learning Framework for Indoor Localization** | FedAvg, DP | MLP | UJIIndoorLoc, Guangzhou Xinguang, Shopping Mall | [Link](https://ieeexplore.ieee.org/document/9658722)|
| 2022 | **Zone-Based Federated Learning in Indoor Positioning** | FedAvg | kNN, MLP, Random Forest | UJIIndoorLoc, CRI | [Link](https://ieeexplore.ieee.org/document/9960135), [pdf](https://www.researchgate.net/publication/365869024_Zone-Based_Federated_Learning_in_Indoor_Positioning)|
| 2022 | **Federated Learning-Based Localization With Heterogeneous Fingerprint Database** | FedAvg | MLP | UJIIndoorLoc | [Link](https://ieeexplore.ieee.org/document/9761235), [pdf](https://arxiv.org/pdf/2203.15388)|
| 2022 | **Prediction Based Semi-Supervised Online Personalized Federated Learning for Indoor Localization** | FedAvg, Knowledge distillation, Mixture of Experts | MLP | UJIIndoorLoc, Guangzhou Xinguang, Shopping Mall | [Link](https://ieeexplore.ieee.org/document/9749277)|
| 2022 | **Federated Learning for WiFi Fingerprinting** | FedProx | CNN, LSTM | Private | [Link](https://ieeexplore.ieee.org/document/9838945)|
| 2022 | **Federated Learning for Indoor Localization via Model Reliability With Dropout** | Monte Carlo Dropout | NN | UJIIndoorLoc | [Link](https://ieeexplore.ieee.org/document/9764747), [pdf](https://www.researchgate.net/publication/363051449_Federated_Learning_for_Indoor_Localization_via_Model_Reliability_With_Dropout)|
| 2022 | **Multi-Level Federated Graph Learning and Self-Attention Based Personalized Wi-Fi Indoor Fingerprint Localization** | Federated Graph Learning | GNN | Guangzhou Xinguang, Shopping Mall | [Link](https://ieeexplore.ieee.org/document/9734052)|
| 2023 | **A Federated Learning Framework for Fingerprinting-Based Indoor Localization in Multibuilding and Multifloor Environments** | AutoEncoder | CNN, DNN | UJIIndoorLoc | [Link](https://ieeexplore.ieee.org/document/9917443)|
| 2023 | **Confidentiality Preserved Federated Learning for Indoor Localization Using Wi-Fi Fingerprinting** | - | CNN, LSTM | Private | [Link](https://www.mdpi.com/2075-5309/13/8/2048)|
| 2023 | **FedHIL: Heterogeneity Resilient Federated Learning for Robust Indoor Localization with Mobile Devices** | AutoEncoder, FedHIL | MLP | Private | [Link](https://dl.acm.org/doi/10.1145/3607919), [pdf](https://arxiv.org/pdf/2307.01780)|
| 2023 | **FedPos: A Federated Transfer Learning Framework for CSI-Based Wi-Fi Indoor Positioning** | Cloud Feature Extractor, Homomorphic Encryption | CNN | Simulated | [Link](https://ieeexplore.ieee.org/document/10005038), [pdf](https://www.researchgate.net/publication/366815452_FedPos_A_Federated_Transfer_Learning_Framework_for_CSI-Based_Wi-Fi_Indoor_Positioning)|
| 2023 | **Federated KNN-based Privacy-Preserving Position Recommendation for Indoor Consumer Applications** | Discrete Coordinate Encryption, Federated KNN | kNN | Private | [Link](https://ieeexplore.ieee.org/document/10304302)|
| 2024 | **A Three-level Federated Learning Framework for CSI Fingerprint based Indoor Localization in Multiple Servers Environment** | Inner Production | CNN | Private | [Link](https://ieeexplore.ieee.org/document/10412104)|
| 2024 | **Federated Distillation based Indoor Localization for IoT Networks** | Knowledge distillation, Federated distillation | DNN | Simulated, UJIIndoorLoc | [Link](https://ieeexplore.ieee.org/document/10416167), [pdf](https://arxiv.org/pdf/2205.11440)|
| 2024 | **Feature fusion federated learning for privacy-aware indoor localization** | FedAvg, FedSGD | MLP, LSTM | SPAWC | [Link](https://link.springer.com/article/10.1007/s12083-024-01736-5), [pdf](https://www.researchgate.net/publication/381125287_Feature_fusion_federated_learning_for_privacy-aware_indoor_localization)|
| 2024 | **FeMLoc: Federated Meta-learning for Adaptive Wireless Indoor Localization Tasks in IoT Networks** | Transfer Learning, Meta-learning | kNN, SVM | UJIIndoorLoc, Tampere Uni, Uni of Minho | [Link](https://ieeexplore.ieee.org/document/10628047), [pdf](https://arxiv.org/pdf/2405.11079)|

