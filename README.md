# tech-for-wildlife-conservation
This is code for classifying human vs elephants in UAV thermal IR videos using spatio-temporal data and KNN model with Dyanamic Time Warping Similarity metric.

**References:**
1. Anika Puri, “A Novel Wildlife Poaching Detection Solution using Spatio-temporal Data with Dynamic Time Warping”, IEEE MIT Undergraduate Research Technology  
   Conference, Selected for publication and oral presentation, October 8-10, 2021 

      Conference: https://urtc.mit.edu/
      
      Presentation from 1:12:42 - 1:21:50): https://www.youtube.com/watch?v=WXOQNRAxM0g&list=PL2yP2hgZp_0pUavqp8Fr26fZc_3qWzR5y&index=18
      
      Paper: https://github.com/AnikaPuri/tech-for-wildlife-conservation/blob/main/IEEE_MIT_URTC%20FINAL.pdf


2. Anika Puri, Elizabeth Bondi, “Space, Time and Counts: Improved Human vs. Animal Detection inThermal Infrared Drone Videos for Prevention of Wildlife Poaching”,      ACM Knowledge Discovery and Data Mining (KDD) Conference Fifth Annual FRAGILE EARTH Workshop, Selected for publication and oral presentation, August 14-18, 2021.

      Conference: https://ai4good.org/fragile-earth-2021/
      
      Presentation: https://www.youtube.com/watch?v=OBCwVU7C2hw&list=PLQ9F64Tjt01lc0nwyxPoNCfPEqQ-BX9MZ&index=13
      
      Paper: https://github.com/AnikaPuri/tech-for-wildlife-conservation/blob/main/ACM_KDD_FRAGILE_EARTH%202021.pdf

**Description:**

Wildlife poaching of endangered species such as elephants and rhinoceroses in Africa and Asia for illegal trading has become a biodiversity crisis (UN sustainable Development Goal SDG15). Recently, unoccupied aerial vehicles (UAVs) equipped with heat-sensing infrared cameras (and coupled with computer vision software) have been deployed to help park rangers monitor protected areas at night when illegal wildlife poaching typically occurs. To maximize the area covered within a fixed flight time and battery constraints, the UAVs usually fly at an altitude of approx. 400 ft. This results in small animal/human sizes in the captured thermal images and consequently leads to poor detection accuracy of as low as 20% for humans. In this research, I studied the Spatio-temporal nature of the video data, i.e., the difference in the movement pattern of animals and humans over time, such as their turning radius, speed, herd nature etc. to determine whether these features have promise in improving classification. When tested using a thermal infrared video dataset collected from four national parks in Africa, this method was able to use movement patterns to detect humans with 90.9% accuracy - a 4X improvement over the existing state-of-the-art methods. 
These  spatio-temporal  series then classified (as  human  or  animal ) without doing any feature extration  by leveraging  dynamic  timewarping  metrics  similarity metric directly within K-Nearest  Neighbor  Clustering (KNN-DTW).  When tested on the BIRDSAI dataset, KNN-DTW method was able to detect human activity  with  94%  sensitivity enabling  real-time  inferencing. 
