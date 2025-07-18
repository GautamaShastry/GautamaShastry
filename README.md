

<!--
**GautamaShastry/GautamaShastry** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<h1 align="center">Hey there, I'm Satya 👋</h1>

<p align="center">
  MSCS @ George Mason University • Aspiring SDE 1 • Cloud ☁️ & AI/ML Enthusiast
</p>

<p align="center">
  <a href="mailto:gautamashastry@gmail.com"><img src="https://img.shields.io/badge/Email-gautamashastry@gmail.com-D14836?style=flat&logo=gmail&logoColor=white"/></a>
  <a href="https://linkedin.com/in/satya2603/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin"/></a>
  <a href="https://gautamportfolio.com"><img src="https://img.shields.io/badge/Portfolio-Visit-FF5722?style=flat&logo=firefox-browser&logoColor=white"/></a>
  <a href="https://github.com/GautamaShastry"><img src="https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github"/></a>
</p>

## 🗒️ About Me
I'm a Master's student in Computer Science (GPA 3.85) who loves turning ambiguous customer problems into scalable, low‑latency cloud services on AWS. With 200 + LeetCode problems under my belt, I bring strong algorithms chops alongside production experience building microservices in Java, Python, and C++. I thrive in fast Agile teams that measure success by working software and delighted users.

## 🌐 Website
Please check out my website: [gautamportfolio.com](https://gautamportfolio.com)

## 🛠️ Skills
- **Languages:** Java, Python, C++, SQL, JavaScript/TypeScript, HTML/CSS
- **Frameworks & Libraries:** Spring Boot, React.js, Node.js, Express, Redux
- **Databases:** PostgreSQL, MySQL, MongoDB, DynamoDB
- **Cloud & DevOps:** AWS (EC2, S3, CloudFront, Route 53, RDS, Lambda, SQS, SNS), Docker, Kubernetes, Jenkins, Rancher, Git/GitHub
- **ML/AI:** pandas, NumPy, spaCy, TensorFlow, Keras, RAG, LLM fine‑tuning
- **Practices:** Microservices, REST APIs, CI/CD, Agile/Scrum, TDD

## 📜 Certifications
- **AWS Certified Cloud Practitioner – CLF‑C02**

## 💼 Experience
**Software Engineer Intern – Backflipt | Jan 2023 – Jun 2023 (Hyderabad, India)**
- Shipped modular React + Redux interfaces that boosted user engagement **20 %** by improving scalability.
- Cut unnecessary re‑renders **40 %** and trimmed page‑load times **10 %** through component‑level profiling.
- Authored Confluence docs that reduced new‑hire ramp‑up **25 %**.
- Optimized state management, slashing API latency **15 %**.

## 🚀 Projects
<details>
<summary><b>Student Survey Application | SpringBoot, Docker, Kubernetes, Jenkins, AWS EC2, AWS RDS, Rancher</b> <br/> <i>March 2025 – May 2025</i></summary>

- Designed a Spring Boot REST API for a 13‑field Survey entity with five CRUD endpoints using Spring Data JPA and Bean Validation (@NotBlank, @Email, @NotNull); verified all routes in Postman and processed **60 +** live submissions with zero validation errors.
- Provisioned an Amazon RDS MySQL 8 database and tuned HikariCP (max pool size 20, min idle 5) for consistent throughput and low latency.
- Containerized the service into an OpenJDK 23‑slim image with an optimized single‑stage Dockerfile, pushed version‑tagged images to DockerHub from the CLI, and deployed a 3‑replica Kubernetes Deployment on 3 EC2 nodes managed by Rancher, exposed via a NodePort Service—maintained **99.9 %** uptime.
- Created a Git‑triggered Jenkins pipeline (Maven tests, build & push Docker image, and `kubectl rollout`) that rebuilds and redeploys in about **5 minutes**, maintaining zero‑downtime releases under Git/GitHub version control.

</details>

<details>
<summary><b>Taskify – Task Management Web App | Vite + React.js, Express.js, Node.js, MongoDB, Docker</b> <br/> <i>Jan 2025 – Feb 2025</i></summary>

- Developed a full‑stack task management application using React.js, Node.js, and MongoDB, allowing users to efficiently create, update, delete, and manage tasks; included comprehensive features such as profile updates and deletions.
- Integrated JWT‑based authentication with Express.js and user profile management with bcrypt password hashing, enhancing security and reducing login‑related incidents by **25 %**.
- Designed and developed **20 +** real‑time filtering, sorting, and search functionalities, enhancing data accessibility and reducing search response time by **15 %**.

</details>

<details>
<summary><b>Resume Analyzer | React.js, SpringBoot, Python, Flask, PostgreSQL, Render, Vercel, Docker</b> <br/> <i>Feb 2025 – May 2025</i></summary>

- Built a React application that lets recruiters upload resumes and job descriptions, then view AI‑generated fit scores; implemented protected routes and JWT handling with Axios, cutting manual screening clicks by **70 %** in user tests.
- Developed a Spring Boot REST API secured by Spring Security roles and JWT; exposed endpoints for resume upload, job description upload, and score retrieval, persisting all data in PostgreSQL via Spring Data JPA.
- Created a Python microservice that uses spaCy to extract entities and assign fit scores with **87 %** validation accuracy and sub‑1.5‑second inference latency.
- Orchestrated cross‑service communication: the Java API calls the AI microservice, stores scores and extracted skills in PostgreSQL, and returns aggregated results to the React UI; processed **50 +** candidate resumes during a two‑week pilot with zero API errors.
- Deployed the Spring Boot backend and Flask ML service on Render and the React frontend on Vercel, enabling auto‑scaling to zero, sustaining **99.95 %** uptime, and keeping hosting spend under **US $50/month**.

</details>

<details>
<summary><b>Portfolio | React.js, Tailwind CSS, AWS S3, AWS CloudFront, AWS Route 53, AWS ACM</b> <br/> <i>Jan 2025 – Jul 2025</i></summary>

- **Frontend Development & UI:** Engineered a mobile‑first SPA in React + Tailwind that scores > 90 on Lighthouse (Performance, Accessibility, Best Practices, SEO) for both mobile and desktop. Integrated Framer Motion micro‑interactions—animated cards, section reveals, hover effects—boosting user engagement by **15 %**.
- **Cloud DevOps:** Architected a latency‑optimized stack—Amazon S3 for static hosting, CloudFront CDN for content delivery, and Route 53 for DNS health‑check failover—that now serves <code>gautamportfolio.com</code> at an average TTFB of **193 ms** and earns an **89 %** SpeedVitals grade A. Locked down the origin with OAI, enforced SSL/TLS via ACM, enabled HSTS preload, and mandated HTTPS redirects, resulting in zero high‑severity findings across recurring AWS Security Hub scans.

</details>

## 🎓 Education
- **George Mason University**, Fairfax, VA — *M.S. Computer Science*, GPA 3.85/4.00 *(Jan 2024 – Dec 2025)*
- **Andhra University**, Visakhapatnam, India — *B.Tech. Computer Science*, 8.15/10 *(Aug 2019 – May 2023)*

---

> “Every once in a while a new technology, an old problem and a big idea turn into an innovation.” – Dean Kamen
