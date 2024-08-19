


# VITB-Insights

VITB-Insights is a comprehensive web platform tailored specifically for the academic and placement needs of VIT Bhopal students. Developed using the MERN stack, the platform provides students with study materials, previous exam papers, and a space for discussions on academics and placements. The placement corner offers valuable insights and industry trends, while the academic section fosters collaboration.

## Motivation
VITB-Insights was created to empower students with a centralized hub for academic resources and placement-related information. It aims to ease the process of navigating through academic challenges and career planning by providing a collaborative space for students.

## Problem Statement
Students at VIT Bhopal currently face difficulties in accessing reliable information, scattered across various channels. The lack of a dedicated platform for academic and placement queries hampers students' efficiency in academic and career pursuits. VITB-Insights addresses this gap by providing a unified space for sharing resources, seeking guidance, and engaging in academic discussions.

## Objective
VITB-Insights aims to be the go-to digital platform for VIT Bhopal students, providing a centralized place for placement guidance, academic materials, and collaborative forums. The platform fosters a vibrant online community for knowledge exchange and peer support.

## Features
- **Placement Corner:** Insights on interview experiences, trends, and guidance.
- **Academic Section:** Study materials, exam papers, and discussion forums.
- **Collaborative Community:** Engage in meaningful academic and career discussions.

## Directory Structure
The project is structured as follows:

```
VITB-Insights/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── utils/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── README.md
└── .gitignore

```

## Technology Stack
- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Other:** Vite.js, OpenAI API

---

## How to run the application locally: 
 
1. Clone the project.

1. Install dependencies in both **client** and **server** folder by using <br> command `npm install` or `npm i`

1.  Complete the .env file in **server** folder. 
    - Connect to MongoDB.
    - Enter remaining fields.

1.  To run the application, 
    - move to **server** folder using command `cd server` <br> Then use command `npm start` to start the server.
    - move to **client** folder using command `cd client` <br> Then use command `npm start` to start the application.

---
