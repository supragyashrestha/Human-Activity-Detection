# Human-Activity-Detection

Project Statement

To generate text results for human activities from videos.


Project Overview

In today's world, security is a big concern for everyone. The overgrowing use of CCTV has given rise to various problems, such as human surveillance personnel and storage space shortages. This problem is going to be a big problem for the future, and Machine Learning and especially Deep Learning can be used to solve this problem. Machine Learning models can be used to impersonate surveillance personnel, answer the first problem, and solve the storage space issue. Machine Learning models can be used to generate text detections for human activity detection, which I am trying to achieve here.
Most Activity Detection Machine Learning models present in today's world are typically more or less video classification models that take small videos with prelabelled human activity. They predict whether the video has a particular event or not. Also, the corresponding dataset for these models ranges in size of TBs, which is not possible for me to use with the hardware available with me. So I had to look for another approach to this problem. I finally came up with the idea of using the real-time object detection model Yolo which is typically used to detect objects in an image. However, it can also be used to identify actions if a dataset for human actions in the image format is available. I was able to find such a dataset, and so I have used this approach throughout my project.

Further Reading - https://github.com/supragyashrestha/Human-Activity-Detection/blob/main/Internship%20Project%20Report.pdf
