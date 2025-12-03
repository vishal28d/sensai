# SensAI : AI Job Preparation Platform

A simple AI-powered platform to help students prepare for jobs. It includes:

* Resume & Cover Letter Generator
* Mock MCQs for practice
* Performance Analytics

This is a **resume project**, built to showcase full-stack development skills.

<img width="940" height="448" alt="image" src="https://github.com/user-attachments/assets/d6912919-07ae-4751-8f66-75e6e84c12ad" />


---

## 🚀 Features

* Generate AI-based resumes and cover letters
* Attempt mock MCQs
* View accuracy, weak topics & improvement stats
* Clean UI using Next.js + Shadcn
* Fast backend with Node.js, Postgres & Prisma

---

## 🛠 Tech Stack

* **Frontend:** Next.js, React, Shadcn UI, Tailwind CSS
* **Backend:** Node.js, Express/Nest, Postgres, Prisma
* **AI:** OpenAI API (or compatible LLM)
* **Auth:** JWT / NextAuth

---

## 📦 Setup Instructions

### 1️⃣ Clone the repo

```bash
git clone https://github.com/vishal28d/sensai.git
cd ai-jobprep
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
cp .env.example .env
# update DATABASE_URL and OPENAI_API_KEY
npm run prisma:migrate
npm run dev
```

Backend runs on: **[http://localhost:4000](http://localhost:4000)**

### 3️⃣ Frontend Setup

```bash
cd ../frontend
npm install
cp .env.example .env.local
# set NEXT_PUBLIC_API_URL=http://localhost:4000
npm run dev
```

Frontend runs on: **[http://localhost:3000](http://localhost:3000)**

---

## 📊 How It Works

1. User logs in
2. Generates resume/cover letter OR starts MCQ test
3. AI processes request and returns results
4. Data is saved in Postgres for analysis

---

## 📁 Project Structure

```
root
├── backend    # Node.js + Postgres + Prisma
└── frontend   # Next.js + Shadcn UI
```

---

## 📝 Future Improvements

* Add coding interview questions
* Add job tracking dashboard
* Add AI mock interview

---

## 📧 Contact

Made by **Vishal Maurya** (Student Developer)
Feel free to connect for project details or improvements!

