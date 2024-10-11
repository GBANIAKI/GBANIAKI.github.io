
---
layout: posts
title:  " Explore your ROSA Environment"
date:   2024-10-10 03:48:27 -0500
tags: [leadership]
author_profile: false
author: gerves Baniakina
categories: work
highlight_home: false
tagline: " hybrid cloud console"
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
The outcome of the project was splandid, but I was not  successful to use Open Shift Mesh to observe and trace application. You can find below the detailed outcome of the process





## Next Steps
Ideally, I would have preferred to continue monitoring metrics on this interface and further correct mistakes to repeat the experience. Unfortunately, due to the conclusion of the contract, I was unable to pursue these improvements.