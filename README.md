# Google_Landmark_Recognition_2021
This is a training notebook from used in Google Landmark Recognition 2021.
training step:
  1. Reload imagenet21kf1k weight.
  2. Train model in 384 x 384 with 25 steps.
  3. Reload weight from previous step and train in 640 x 640

To be tested:
  1. change embedding dims from 768 to 512. 768 seems unnecessary, and the inference speed was bad.
  2. If possible, change efficientnetv2_s to some larger model, like efficientnetb5 or efficientnetv2_m
