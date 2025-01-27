<H1 align="center">
Pedestrian Tracking with DeepSORT (ID + Trails) </H1>

<a target="_blank" href="https://colab.research.google.com/github/wendycao411/Pedestrian_Tracking/blob/main/Pedestrian_Tracking.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## To Do
1. ~~Detect shade using this algorithm: https://github.com/wendycao411/MetabolicWalking_Original.git~~
2. ~~Count people in shade~~
3. ~~Save outputs in csv file (count, velocity, centroid, etc.)~~
4. Analyze data using matplotlib

   a. ~~Basic graphs - heat map, plot paths across frames, scatter plot?, analyze shade preference~~

   b. Get coordinates + area of shade polygon and track how it changes

   c. Separate people into categories: start + end in shade, start + end out of shade, start + end different -- track ratio of categories across different days

   d. Area of street??

   e. Track weather information across several days
   
6. Apply homography transformation
7. ~~Be able to analyze full videos~~
8. ~~Improve video quality without crashing~~

## References
- https://github.com/ultralytics/ultralytics
- https://github.com/MuhammadMoinFaisal/YOLOv8_Segmentation_DeepSORT_Object_Tracking
- https://github.com/Emmmmmmaa/MetabolicWalking
