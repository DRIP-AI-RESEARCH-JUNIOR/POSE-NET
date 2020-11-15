# POSENET



The algorithm that was put forword in the paper "Simple Baselines for Human Pose Estimation and Tracking or Open Pose", achieves state-of-the-art results on challenging benchmarks. But the problem is with time high time consumption. So is it suitable for Video?

We come up with a modified architecture that can solve the time consumption on the Video processing problems without degrading the performance.
For the technical details follow this link to docx-https://lnkd.in/eGSTg6h

We use here the Keypoints generated from our model and use it to compare similarity between 2 videos of poses.

# Instructions to use.
#### To compare a video from previous Keypoint.
##### Using Python Script
   - Use the below command to download the model weight file.
   
    $ gdown --id 17e98AeE1fKUi9_-dwbIxqD3ODTEySP6X 
    
   - Use the below command to run the python program.

    $ python <PATH OF THE 'E2E_pose.py' FILE> -v <PATH OF VIDEO TO BE TESTED> -s <PATH OF REFRENCE SOLO FILE> -d <PATH OF REFERENCE DUO FILE> -g <PATH OF REFERENCE GROUP FILE> -w <PATH OF THE MODEL WEIGHT FILE>

##### Using Notebook 
   - Upload the files mentioned in the notebook(PoseNet.ipnyb) and follow the steps mentioned in the notebook.


#### To compare a video from another Video.
##### Using Notebook 
   - Upload the files mentioned in the notebook(PoseNet.ipnyb) and follow the steps mentioned in the notebook.

#### To Generate Keypoint.
##### Using Notebook 
   - Upload only the video to generate checkpoints from  and follow the steps mentioned in the notebook(PoseNet.ipnyb), and run the "Keypoint Generation" cell.
# Results.
#### Keypoints.
![alt text](https://github.com/DRIP-AI-RESEARCH-JUNIOR/POSE-NET/blob/master/ck1.jpg?raw=true)
![alt text](https://github.com/DRIP-AI-RESEARCH-JUNIOR/POSE-NET/blob/master/ck2.jpg?raw=true)
#### Similarity comparision.
![alt text](https://github.com/DRIP-AI-RESEARCH-JUNIOR/POSE-NET/blob/master/cmp.jpg?raw=true)
# TO DO.
- Improving the similarity comparision algorithm.

