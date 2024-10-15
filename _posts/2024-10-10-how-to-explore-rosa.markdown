
---
layout: posts
title:  " Explore your ROSA Environment"
date:   2024-10-10 03:48:27 -0500
tagline: "Hybrid cloud console"
author_profile: true
author: gerves Baniakina
categories: work
tags: [leadership]
highlight_home: false
header:
    overlay_image: https://images.unsplash.com/photo-1512928210967-3dced5ba507b
    teaser: https://images.unsplash.com/photo-1512928210967-3dced5ba507b
    caption: "Photo credit: [**Unsplash: Katya Ross**](https://unsplash.com/@katya)"
description: This article showcases the game Red hat Hybrid cloud.
---


# Background
 On Octiber 1st, 2024, I attended an in-person Red Hat summit entitled "Connect in Chicago". The summit consisted of visionary keynotes, hands-on labs and demos, breakout sessions, and networkings. Thus, one of favorite hands-on labs was exploring the Red Hat OpenShift service on AWS environment(ROSA Environment) that has been pre-deployed. This project was so inspiring that i decided to continue work on it after the summit to explore more feature of ROSA.

# Approach
In colaborations with hands-on lab leaders, I used Red Hat hybrid cloud console to configure node and cluster scaling policies, managed upgrades, single sign-on for the cluster using Amazon Cognito, and forward logs to Amazon CloudWatch.
In addition, I deployed an application that uses AWS IAM Roles for service Accounts and AWS STS to connect to an Amazon DynamoDB table. Besides, I made an application on OpenShift scalable and resisteant to node failures and upgrades. Finally, I deployed application using CI/CD tooling, including OpenShift GitOps and source-to-image, and use labels for deterministic app placement on nodes. Learned how to use Open Shift Service Mesh for application observability and tracing.
You can get the detailed approached used here [Hands-on-lab]({% post_url 2024-10-10-hands-on-lab-rosa-1 %}) directly.

# Result
The outcome of the project was splandid, but I was not  successful to use Open Shift Mesh to observe and trace application. You can find below the detailed outcome of  my work for this project:
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%206.24.31%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%207.09.56%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%207.10.30%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%2011.17.25%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%2011.18.18%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%2011.19.30%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%2011.20.12%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%2011.36.08%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%2011.47.31%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%2011.50.30%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-08%20at%2011.59.17%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%201.02.58%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%201.30.34%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%201.30.54%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%201.31.12%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%201.31.36%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%202.00.20%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%202.01.58%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%202.19.50%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%202.38.13%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%202.40.26%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%207.13.14%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%207.13.40%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%207.27.34%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%207.58.39%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%207.59.06%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%208.00.10%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%208.01.57%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%208.02.52%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%208.03.46%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%208.04.31%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%208.05.08%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%209.04.56%20AM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%209.05.12%20AM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%209.18.57%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%209.25.32%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.47.40%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.47.56%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.48.06%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.48.17%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.48.26%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.48.35%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.52.32%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.52.51%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.53.06%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.53.21%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.53.33%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.53.45%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.53.58%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.54.13%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.54.27%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.54.45%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.55.07%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.55.24%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.55.38%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.55.52%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.56.04%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.56.16%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.56.30%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.56.45%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.57.00%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.57.22%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.57.37%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.57.49%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.58.06%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2010.58.20%20PM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2011.05.48%20AM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2011.13.43%20AM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2011.49.27%20AM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2012.06.17%20AM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2012.19.11%20AM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2012.19.36%20AM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2012.19.59%20AM.png)
![My helpful screenshot 0 ](/assets/images/Screen%20Shot%202024-10-09%20at%2012.20.21%20AM.png)






## Next Steps
Ideally, I would have preferred to continue working on this project and further correct mistakes to repeat the experience. Unfortunately, due to the conclusion of the contract, I was unable to pursue these improvements.However, I would next like to work on "Enhance LLMs and streamline MLOps using instructLab
and KitOps".