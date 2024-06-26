# PPE Detection using Computer Vision


4,764 workers died on the job in 2020 (3.4 per 100,000 full-time equivalent workers). Workers in transportation and material moving occupations and construction and extraction occupations accounted for nearly half of all fatal occupational injuries (47.4 percent), representing 1,282 and 976 workplace deaths, respectively.

Occupational Safety and Health Administration (US Department of Labour)

The above statistics highlight the need for more stringent protocols regarding the use of PPE in industrial settings. In this project, we develop an object detection model based on computer vision that detects Personal Protective Equipment (PPE) on workers within an industrial environment. Our model is capable of real time detection of vital safety gear on workers, which include hardhats, masks and safety vests. It addresses the issues of workplace safety by detecting safety equipment and helps reduce the risk of accidents and injuries at the workplace.

Our model is fine-tuned and based on a pre-trained YOLO model used for single-shot object detection, which uses a single pass of an input image to make predictions about the presence and location of the safety gear in the image. Various versions of YOLO are tested, and the medium COCO detection model of YOLOv8 is chosen to be fine-tuned for our project. The final model demonstrates strong performance for detecting safety gear in both images and videos
