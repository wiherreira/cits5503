# CITS5503 Cloud Computing

This unit introduces cloud computing as the provision of computing resources. Students are exposed to modern systems architectures and software development kits that, together, provide cloud computing frameworks. Students will learn about different aspects of the design, development, provisioning and management of cloud-based applications.

Students will gain a sound understanding of cloud-based computing and the opportunities that it provides for a diverse range of computing applications. Special attention will be made to security of cloud based applications and the different strategies that are available in these deployments.

An overarching goal of the unit is to provide students with an opportunity to undertake problem identification, analysis and solution and to apply these skills to the field of Cloud Computing.

## Note on the use of AWS and Alibaba Cloud

The course is based on the cloud services of Amazon Web Services and Alibaba Cloud and a range of open source and other products. It is not possible in a couse such as this to cover all of the products that these cloud services provide. The theme has been to concentrate on the most common use cases of [a] using AWS and Alibaba Cloud to deploy web applications utilising data sources such as databases and [b] data analytics and machine learning.

## Learning Outcomes

Students are able to

1.  Understand cloud services, there motivation, design and implementation
2.  Understand the basics of virtualisation of hardware, networks and security
3.  Understand application architectures and how they meet specific requirements and needs
4.  Understand how to achieve scalability and security in a cloud-based architecture
5.  Use DevOps to deploy and manage the creation and updating of software environments
6.  Use cloud services to carry out specific use cases such as data analytics, machine learning and other artificial intelligence tasks
7.  Write code in Python using a variety of SDKs to achieve the above where appropriate

The course consists of 12 weeks of lectures and 10 weeks of practical lab classes. Assessment is through marking of lab assignments, a mid-term exam and a final exam.

## Lectures

[Intro for 2019](https://youtu.be/YUgurpCvTL8 "Video: Intro 2019")

Week 1: Motivation for cloud computing, introduction to cloud computing ([CloudComputingIntro](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938436_1/xid-20938436_1) (pptx), [Video](https://youtu.be/a5zzb_T29GQ "Cloud Computing Intro"), [WhatIsTheCloud](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938424_1/xid-20938424_1) (pptx), [Video 1](https://youtu.be/qOIVPURG6sI), [Video 2](https://youtu.be/Hw8yVPlE3WU "What is the cloud part 2"))

Week 2: Guest Lecture by Brett Looney AWS on Cloud Computing and AWS

Additional Material: Introduction to AWS platform and services, awscli command line and python boto programming interfaces ([AWSIntro](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938437_1/xid-20938437_1) <span style="caret-color: #24292e; color: #24292e; font-family: 'Source Sans Pro'; font-size: 16px; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; display: inline !important; float: none;"> (pptx) [Video](https://youtu.be/_UxpJeOB-bM)</span>, [Boto<span style="caret-color: #24292e; color: #24292e; font-family: 'Source Sans Pro'; font-size: 16px; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; display: inline !important; float: none;"> (pptx)</span>](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938432_1/xid-20938432_1))

Week 3: Computer virtualisation. Background and different approaches. Containers and Docker ([Virtualisation<span style="caret-color: #24292e; color: #24292e; font-family: 'Source Sans Pro'; font-size: 16px; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; display: inline !important; float: none;"> (pptx)</span>](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938426_1/xid-20938426_1), [Video](https://youtu.be/fyo9WmKVHTY))

Week 4: AWS storage EBS, S3, DynamoDB ([Storage<span style="caret-color: #24292e; color: #24292e; font-family: 'Source Sans Pro'; font-size: 16px; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; display: inline !important; float: none;"> (pptx)</span>](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938430_1/xid-20938430_1), [S3 Video](https://youtu.be/ob6x5ZotyWk), [DynamoDB Video](https://youtu.be/mhNU38b96Oc "Dynamo DB") )

Week 5: AWS security and identity management ([IAM<span style="caret-color: #24292e; color: #24292e; font-family: 'Source Sans Pro'; font-size: 16px; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; display: inline !important; float: none;"> (pptx)</span>](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938431_1/xid-20938431_1), [Video](https://youtu.be/3prrCQxlJoQ))

Week 6: Networking, IP addressing, subnets, routing virtual private clouds ([Networking<span style="caret-color: #24292e; color: #24292e; font-family: 'Source Sans Pro'; font-size: 16px; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; display: inline !important; float: none;"> (pptx)</span>](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938428_1/xid-20938428_1), [Networking Video](https://youtu.be/FeIzLjkRi28), [NAT](https://youtu.be/fpHifzYGosA), [ELB](https://youtu.be/h5rhWRbuI74))

## Week 7: Mid Term Exam

<span style="caret-color: #24292e; color: #24292e; font-family: 'Source Sans Pro'; font-size: 16px; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; display: inline !important; float: none;">Week 8: Web architectures using python<span class="Apple-converted-space"> </span></span>django<span style="caret-color: #24292e; color: #24292e; font-family: 'Source Sans Pro'; font-size: 16px; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; display: inline !important; float: none;"><span class="Apple-converted-space"> </span>as a model with RDBMS <span style="font-family: 'courier new', courier; font-size: medium;">(</span></span><span style="font-family: 'courier new', courier; font-size: medium;">[WebArchitecture<span style="caret-color: #24292e; color: #24292e; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; float: none; display: inline !important;"> (pptx)</span>](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938425_1/xid-20938425_1), [Web Architecture Video](https://youtu.be/hl9QZS-ovn4), [Django Demo](https://youtu.be/wQZYSURos-s), [SQS Video](https://youtu.be/jVF3JAUMaw0)<span style="caret-color: #24292e; color: #24292e; font-style: normal; font-variant-caps: normal; font-weight: normal; letter-spacing: normal; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: #ffffff; text-decoration: none; float: none; display: inline !important;">)</span></span>

Week 9: Software controlled deployment of services and software using Chef ([DevOps](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938435_1/xid-20938435_1) (pptx), [OpsWorks Chef Video](https://youtu.be/ZyTQc2xDRv4), [DevOps Intro Fabric](https://youtu.be/iuOBJr2Rdkg), [Code Build Video](https://youtu.be/doW1ZjnMNfQ)  )

Week 10: Machine learning using classification and categorisation services ([AI](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938438_1/xid-20938438_1) (pptx), [AI Video](https://youtu.be/tHyPwdB5ghI), [ML Demo Video](https://youtu.be/Q5YHt_FieeQ))

Week 11: More AI services including text analysis, image analysis, chatbots and data anaylsis using Jupyter and SageMaker ([MoreAI](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938429_1/xid-20938429_1) (pptx), [More AI Intro Video](https://youtu.be/Uz25dAUf-TU), [Chatbots Video](https://youtu.be/rb9knoeXIss), [SageMaker Video](https://youtu.be/JmlFz-rLBAc), [SageMaker Demo Video](https://youtu.be/jHHySmY2KUc))

Week 12: Mobile application integration and services and IoT integration using cloud services ([MobileIntegration](https://lms.uwa.edu.au/bbcswebdav/pid-1412149-dt-content-rid-20938434_1/xid-20938434_1) (pptx), [Mobile Video](https://youtu.be/NAqVZrkHD-s), [Mobile Demo, Video](https://youtu.be/fUP935lHwmc))

## Labs

Week 2:<span class="Apple-converted-space"> </span>[Lab1 Intro and setup of environment](https://github.com/dglance/cits5503/blob/master/Labs/Lab1IntroSetup.md)

Week 3:<span class="Apple-converted-space"> </span>[Lab2 EC2 and docker](https://github.com/dglance/cits5503/blob/master/Labs/Lab2EC2Docker.md)

Week 4:<span class="Apple-converted-space"> </span>[Lab3 S3 and DynamoDB Creating CloudStorage application](https://github.com/dglance/cits5503/blob/master/Labs/Lab3S3DynamoDB.md)

Week 5:<span class="Apple-converted-space"> </span>[Lab4 IAM, KMS and AES encryption](https://github.com/dglance/cits5503/blob/master/Labs/Lab4KMSEncryption.md)

Week 6:<span class="Apple-converted-space"> </span>[Lab 5 Networks and VPC](https://github.com/dglance/cits5503/blob/master/Labs/Lab5Networking.md)

Week 7:<span class="Apple-converted-space"> </span>[Lab 6 Web applications, Django and ELB](https://github.com/dglance/cits5503/blob/master/Labs/Lab6WebApplication.md)

Week 8:<span class="Apple-converted-space"> </span>[Lab 7 DevOps](https://github.com/dglance/cits5503/blob/master/Labs/Lab7DevOps.md)

Week 9:<span class="Apple-converted-space"> </span>[Lab 8 Machine learning using classification and categorisation services](https://github.com/dglance/cits5503/blob/master/Labs/Lab8AI.md)

Week 10:<span class="Apple-converted-space"> </span>[Lab 9 More AI: Text analysis, image analysis, chatbots](https://github.com/dglance/cits5503/blob/master/Labs/Lab9MoreAI.md)

## Assessment

40% Midterm Exam (Week 6) 60% Final Exam

<span style="font-family: helvetica; text-shadow: none !important; letter-spacing: normal !important; margin: 0px; padding: 0px; border: 0px; outline: 0px; font-weight: inherit; font-style: inherit; font-size: medium;"> </span>
