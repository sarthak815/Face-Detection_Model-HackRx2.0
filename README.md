# PS8_XORBIANS

![Team-Preview](/github_ready/home.PNG)

# Introduction:

Our team, Xorbians, hopes to achieve a scalable, deployable, and maintainable Face Detection and Validation product for HackRx. Keeping in mind the above three factors, we surveyed and enlisted state-of-the-art modules supported and backed by Open Source and well-maintained products such as Tensorflow, FastAPI, and OpenCV. Please refer to the [competition website](https://hackrx.in/) for refined details regarding the problem statement and check out our [acknowledgment](#Ackowledgement) for further details on this repository.

# Tackling our Problem Statements:

![Order of Detection](/github_ready/order_of_detection.PNG)

![Detection](/github_ready/detection.PNG)

![Obstruction Blur Number](/github_ready/obstruction_blur_number.PNG)

![Cartoon](/github_ready/cartoonification.PNG)

![Professional](/github_ready/professional.PNG)

![Live Face](/github_ready/live_face.PNG)

![thumbnail](/github_ready/small_regions.PNG)

# Datasets Used:
1)Face Obstruction Detection - https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset<br />
2)Face Spoofing Detection - https://github.com/fernandovinicius/densenet-face-anti-spoofing/tree/c3dfd9c916d3c9b55220252571b3392004c5710b<br />

# Tech Stacks Used:
1)FastApi<br />
2)SteamLit<br />
3)MongoDB<br />

# Scalability, Deployability, and Maintainability

## Scalability and Deployment:

Our goal for this project revolves around memory-efficient high performing models. Each of our models is State-of-the-Art for both speeds as well as memory. We have displayed these in our [Problem Statement slides](#tackling-our-problem-statements), where we mention our preferred choice of models (best IoU, speed, memory). Even so, the models are expected to be multi-threaded to prevent bottlenecking and allow support for increased resource usage. 

## Maintenance:

We approach the problem statement from the Memory + Performance optimization standpoint, where we are looking to find the optimal solutions for both of them. Our selected models are low memory high performance backed by scientific research in the field of machine learning. 

Even so, these models are pre-implemented with a community of more than 1.2 million new users of Tensorfow just in the past decade; we can see a large amount of backing and community it has built. From a maintenance point of view, Tensorflow is one of the two base machine learning libraries in Python, the most used language for AI/ML. This makes product maintenance extremely easy, as multiple people with sufficient knowledge can collaborate on it. Another positive point is the numerous resources and courses available for Tensorflow, which would allow easy training for maintainers.

OpenCV, another technology integrated into the framework, is an image processing tool for Python. Considered the best library, it has an easy learning curve and an abundance of well-documented articles for support.

Finally, our implementation of FastAPI, one of the fastest, best, and popular API frameworks, would also allow easy access and integration in the future.

All three of these base frameworks are open-sourced, backed by a large supporting community, and popular!

# Ackowledgement:

This repository was created on a later date as a record of our performance during the HackRx2.0 hackathon., which led us to simply upload our zipped winning submission. We would like to thank the organizing team and Bajaj Finserv for organizing such a wonderful event. The internal details of the project have been made open-source to allow others to augment/improve upon our code. We would be glad to hear feedback if any!

If you wish to check out the repository at the time of the competition, please checkout the [Official-GitHub-Repository](https://github.com/HackRx2-0/ps8_xorbians) by HackRx. We will also continue to improve upon our API.
