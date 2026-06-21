# Hi, I'm Tom Huth

Computer Science student at the University of Glasgow, building across the full stack - from AI-powered tools and ML pipelines to clean APIs and polished frontends. Passionate about writing software that's both well-engineered and actually useful.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tom-huth)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:tomhuthbus@gmail.com)
[![tomhuth.dev](https://img.shields.io/badge/tomhuth.dev-2ea44f?style=flat-square&logo=safari&logoColor=white)](https://tomhuth.dev/)

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Tools & DevOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Featured Projects

### Counting Beyond the Training Range - Honours Dissertation (https://github.com/TomHuth9/Counting-Beyond-the-Training-Range-Evaluating-CNN-Generalisation-on-Visual-Object-Counting)
Investigates whether CNNs can extrapolate visual object counts beyond their training distribution. Built a synthetic dataset of 21,000 images with controlled interpolation and extrapolation splits, then compared four architectural paradigms - a density map U-Net, pretrained ResNet-18, subitizing CNN, and AI-generated GAP model - under identical conditions. Key finding: the counting formulation matters more than architectural capacity or pretrained features. The density map model (MAE 0.270, degradation slope +0.013) outperformed all others including the pretrained ResNet-18, while cross-entropy classification failed catastrophically at the training ceiling.

`Python` `PyTorch` `CNNs` `Computer Vision` `Deep Learning` `Research`

---

### ETradie - Marketplace for Tradespeople (https://github.com/TomHuth9/ETradie)
A full-stack marketplace connecting homeowners with local tradespeople for on-demand job bookings. Homeowners post jobs with a location, which are geocoded and broadcast in real time to available tradespeople within a 25 km radius. Tradespeople accept or decline jobs through a live dashboard, with ownership-checked job lifecycle management (pending → accepted → completed → closed). Features role-based access control (homeowner / tradesperson), JWT authentication with pinned HS256 algorithm, proximity matching via the Haversine formula, job-scoped messaging, and a post-completion ratings system. Security-hardened REST API with per-route rate limiting, recursive input sanitisation, HTML tag stripping, Zod schema validation on all endpoints, atomic race-condition-safe job acceptance, and explicit body size limits. Covered by unit and end-to-end integration tests using Jest and Supertest, with component tests via Vitest and React Testing Library.

`Node.js` `Express` `Socket.IO` `PostgreSQL` `Prisma` `React` `JWT`

---

### The Farm Gate - Farm-to-Door Delivery Marketplace (https://github.com/TomHuth9/TheFarmGate)
A full-stack farm-to-door delivery app connecting local farm producers directly with customers. Customers browse products by category or farm, add items to a basket, and place orders - with postcodes automatically matched to a local collection centre. Farm producers manage their full product catalogue through a dedicated dashboard. Features role-based access control (customer / farm / admin), httpOnly cookie authentication with post-reset token invalidation, password reset via email, server-side price verification on orders, and a security-hardened REST API with rate limiting, NoSQL injection prevention, and input sanitisation. Covered by integration tests using Jest and Supertest against an in-memory MongoDB instance.

`Node.js` `Express` `MongoDB` `Mongoose` `Angular` `JWT`

---

### AirTap - Gesture-Based Mobile Interaction (https://github.com/TomHuth9/Airtap)
A hand gesture prototype using MediaPipe Hands and computer vision to enable touchless finger-counting interaction on mobile devices. Built as part of a Mobile HCI research project exploring novel input modalities.

`Python` `MediaPipe` `Computer Vision` `Mobile HCI`

---

## Core Competencies

- **API Design** - RESTful architecture, authentication systems, clean interface contracts
- **Database Design** - Schema design, normalisation, query optimisation (PostgreSQL, MySQL)
- **Software Engineering** - OOP principles, algorithms & data structures, clean code practices
- **AI/ML** - Applied ML pipelines, computer vision, LLM integration
- **Full-Stack Development** - End-to-end product delivery from backend to polished UI

---

*Currently seeking graduate roles in Software Engineering, AI/ML, and Data Science - open to opportunities across the UK.*
