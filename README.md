# Zineddine Rebbouh

**AI/ML Engineer & Full-Stack Developer** — I build things that ship, then I go learn why the model was wrong at 2am.

Based in Touggourt, Algeria. Most of my time these days goes into data science and data engineering — ML pipelines, MLOps, getting models out of notebooks and into production. Before that, I spent years shipping full-stack web apps, and I still do when a project needs one.

Open to full-time roles, freelance work, and research collaboration — remote-first, anywhere in the world.

📫 [zinedinerabouh@gmail.com](mailto:zinedinerabouh@gmail.com) &nbsp;·&nbsp;
🌐 [Portfolio](https://zinedine-rebbouh-portfolio-website.vercel.app) &nbsp;·&nbsp;
📄 [Resume](https://github.com/user-attachments/files/27443817/Zineddine_Rebbouh_CV_Fullstack.docx) &nbsp;·&nbsp;
💼 [LinkedIn](https://linkedin.com/in/zineddine-rebbouh)

<p align="left">
  <a href="https://linkedin.com/in/zineddine-rebbouh" target="blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="28" width="35" />
  </a>
  <a href="https://fb.com/zineddine.rebbouh" target="blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" height="28" width="35" />
  </a>
  <a href="https://instagram.com/rebbouh_zineddine" target="blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="28" width="35" />
  </a>
  <a href="https://discord.gg/zineddine_rebbouh" target="blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="Discord" height="28" width="35" />
  </a>
</p>

---

## About Me

I finished my M.Sc. in AI and Data Science at the University of Constantine 2 (thesis graded 19/20), but the way I actually learned most of this was by building for real people: a food-waste platform for small grocers, an insurance pipeline that has to survive real deployment, a marketplace for vendors who'd otherwise have no online presence.

That's the pattern I keep repeating — pick a problem someone actually has, build the model or the app, then do the unglamorous part: deploy it, monitor it, fix it when it breaks. A model that's 95% accurate in a notebook and never sees production is worth nothing to a business. I'd rather ship something at 88% that people actually use.

---

## ⭐ Featured Projects

### 🍲 [Tawfir](https://tawfir-landing-page.vercel.app) — stopping food waste before it happens
My flagship project, built across my Master's. Small grocers and restaurants throw away food that's still sellable because there's no fast way to discount it and get it in front of buyers before it expires. Tawfir fixes that: a ResNet-50 model reads freshness from a photo, a hybrid recommendation engine matches surplus stock with nearby buyers, and a RAG-based support system handles customer questions on its own — 68% of tickets resolved with zero human involvement, at 89% recall on the underlying retrieval. I also built the monetization layer from scratch: subscriptions, commission, and a manual payment-confirmation flow, because most payment gateways don't support Algeria and that wasn't going to stop the product from launching.

`Django` `PostgreSQL` `ResNet-50` `RAG` `Vercel` `Render`

### 🚗 Insurance Cross-Sell Prediction — an MLOps pipeline, not a notebook
Most ML side projects stop at a good accuracy score in a notebook. This one goes further: experiment tracking for reproducible results, Docker so it behaves the same everywhere, and an actual deployment step at the end. The underlying question — which customers are likely to buy a second policy — is the kind of prediction that saves real marketing spend when the model is even a little bit right.

`MLflow` `Docker` `scikit-learn` `XGBoost`

### ⚽ Football Analytics System — computer vision without an Opta budget
Professional player-tracking data is expensive. This shows how far you can get with a camera and open models instead: YOLOv8 and ByteTrack track players and the ball, K-means clusters players into teams by kit color, and from there I compute per-player speed and sprint metrics. It's a tool a smaller club or a coach reviewing match footage could actually use.

`YOLOv8` `ByteTrack` `OpenCV` `K-means`

### 🛒 Multi-Vendor E-Commerce Platform — MERN
A marketplace where independent vendors sell under one roof instead of each building their own storefront and payment setup. Built during my degree, currently getting a full audit and redeploy to Vercel/Render — I go back and fix my old work instead of letting it rot once the grade is in.

`MongoDB` `Express` `React` `Node.js`

### 📧 AI Email Marketing Chatbot
Small businesses rarely have a marketing team to write and send campaigns. This automates that: an AI chatbot drafts and sends email campaigns, Stripe handles billing, and Pusher keeps the UI live so users aren't refreshing a page to check if a campaign went out.

`Next.js` `Stripe` `Pusher`

---

## What Else I've Built

**Web:** a hotel management app with full Playwright test coverage, and a Flutter travel app.

**Data & ML:** customer segmentation with K-Means + PCA · Walmart sales forecasting with LightGBM/XGBoost · traffic sign recognition with CNNs · a real-time Arabic sports-trend detection platform (WANLP) · Arabic Sign Language recognition (3D-CNN, 90.71% validation accuracy) · a segmentation benchmark across six architectures.

I also completed a remote ML internship at Elevvo Pathways, delivering six production ML pipelines in about two months, and I'm currently working through the LLM Zoomcamp — RAG, agentic AI, the current frontier.

---

## Tech Stack

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-FF1709?style=for-the-badge&logo=django&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Machine Learning & AI
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2980B9?style=for-the-badge&logo=lightgbm&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### Data Engineering
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

### Other
![REST API](https://img.shields.io/badge/REST%20API-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

---

## GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=Zineddine-Rebbouh&theme=dark&hide_border=false&include_all_commits=false&count_private=false)
![](https://nirzak-streak-stats.vercel.app/?user=Zineddine-Rebbouh&theme=dark&hide_border=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Zineddine-Rebbouh&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

## Trophies

![](https://github-profile-trophy.vercel.app/?username=Zineddine-Rebbouh&theme=radical&no-frame=false&no-bg=true&margin-w=4)

---

<div align="center">

*Currently learning: RAG and agentic AI systems. Always open to a conversation about a hard problem.*

![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

</div>
