# Project Name : Vehicle Damage Detection

This project is for detecting the damage on car during accident.
I have used YOLO v5 for model building and Streamlit for creating web app.
You can upload both videos and images and check.

# Dataset:
I have use pre annoted dataset from Roboflow for creating model.
The dataset consists of 10675 images with 17 classes like Front-Windscreen-Damage, Headlight-Damage, Major-Rear-Bumper-Dent, Rear-windscreen-Damage, 
RunningBoard-Dent, Sidemirror-Damage, Signlight-Damage, Taillight-Damage, bonnet-dent, doorouter-dent, fender-dent, 
front-bumper-dent, medium-Bodypanel-Dent, pillar-dent, quaterpanel-dent, rear-bumper-dent, roof-dent.

# Link for dataset:
https://universe.roboflow.com/cardamage/cardamage2-mrtqm/dataset/2


# Installation of necessary pacakges.
pip install -r requirements.txt

# Running streamlit 
streamlit run damage_detect.py

# Dockerhub :
This app availbale as Docker Image. Use following coomands for runnig the app.:

docker pull pranaysawant17/damage_detect_app

docker run -p 8501:8501 pranaysawant17/damage_detect_app

http://localhost:8501/ 


# Future Scope:
1) I have used YoloV5s model. So further complex models can be created with more data.

# Refernce:
https://github.com/xugaoxiang/yolov5-streamlit

https://github.com/ultralytics/yolov5
