
<h1 align="center">🧠💼 PathFinder AI</h1>

<p align="center">
  <strong>Your AI-Powered Career Coach & Resume Builder</strong>
</p>

<p align="center">
  Build professional resumes, generate tailored cover letters, prepare for interviews, and accelerate your career using AI-powered workflows.
</p>

<p align="center">
  <a href="https://pathfinder-ai.vercel.app">
    <img src="https://img.shields.io/badge/🌐_Live_Demo-Visit_Now-000000?style=for-the-badge" />
  </a>

  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
  </a>

  <img src="https://img.shields.io/badge/Open_Source-GSSoC'26-blueviolet?style=for-the-badge" />

  <img src="https://img.shields.io/badge/PRs-Welcome-orange?style=for-the-badge" />

  <img src="https://img.shields.io/badge/Maintained-Yes-success?style=for-the-badge" />
</p>

---

# 📸 Project Preview

<h1 align="center">PathFinder AI 🧠💼</h1>






<p align="center">
  <img src="https://raw.githubusercontent.com/harshdwivediiiii/pathfinder-ai/main/public/pathfinder-ai.gif" alt="PathFinder AI Preview" width="100%" />
</p>


---

# 🌟 About PathFinder AI

PathFinder AI is an intelligent AI-powered career platform designed to help students, developers, and professionals create ATS-friendly resumes, generate personalized cover letters, and prepare for interviews with adaptive AI assistance.

Whether you're applying for internships, jobs, or career transitions, PathFinder AI acts as your personalized AI career companion.

---

# 🌐 Live Demo

<p align="center">
  <a href="https://pathfinder-ai.vercel.app">
    <img src="https://img.shields.io/badge/🚀_Launch_PathFinder_AI-black?style=for-the-badge" />
  </a>
</p>

---

# ✨ Core Features

- 📄 **AI Resume Builder** – Create personalized, ATS-friendly resumes.
- ✉️ **Cover Letter Generator** – Generate tone-matched, role-specific letters.
- 🎯 **Interview Preparation** – Practice with adaptive, role-based AI questions.
- 📊 **Industry Insights** – Get real-time trends, salary data, and in-demand skills.
- 🔐 **Secure Authentication** – Authenticated via Clerk with complete session management.
- ⚡ **Modern UI/UX** – Responsive, elegant, and production-ready interface.
- ☁️ **Cloud Deployment** – Optimized deployment with Vercel.

---

# 🧩 Application Workflow

```text
User Input
   ↓
AI Processing (Gemini API)
   ↓
Resume / Cover Letter / Interview Generation
   ↓
Database Storage (PostgreSQL + Prisma)
   ↓
Dashboard Rendering
   ↓
Personalized Career Experience
```

---

# 🛠️ Tech Stack

| Category | Technology |
|----------|-------------|
| Framework | Next.js 14 (App Router) |
| Authentication | Clerk.dev |
| AI Engine | Gemini API (Google AI) |
| Database | PostgreSQL + Prisma ORM |
| Styling | TailwindCSS + ShadCN UI |
| Deployment | Vercel |

---

# 🚀 Tech Badges

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=nextdotjs" />
  <img src="https://img.shields.io/badge/Gemini%20API-Google%20AI-red?style=for-the-badge&logo=google" />
  <img src="https://img.shields.io/badge/TailwindCSS-3.x-38bdf8?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-ORM-3982CE?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge&logo=postgresql" />
  <img src="https://img.shields.io/badge/Vercel-Deployment-black?style=for-the-badge&logo=vercel" />
</p>

---

# 📂 Project Structure

```bash
pathfinder-ai/
│── app/
│── components/
│── lib/
│── prisma/
│── public/
│── styles/
│── utils/
│── hooks/
│── constants/
│── package.json
│── README.md
```

---

# ⚡ Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/harshdwivediiiii/pathfinder-ai.git
cd pathfinder-ai
```

## 2️⃣ Install Dependencies

```bash
npm install
```

## 🔑 Environment Variables

Create a `.env.local` file in the root directory and add:

```env
DATABASE_URL=your_postgresql_connection_string

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=your_gemini_api_key
```

## 🧪 Developer Notes (Clerk Keyless Mode)

When developing locally, Clerk can run in **keyless mode** (without API keys).
In this state:
- Authentication routes will redirect safely
- Protected dashboards won't crash
- Ideal for rapid frontend development

## 🗄️ Prisma Setup

```bash
npx prisma generate
npx prisma migrate dev
```

## ▶️ Start Development Server

```bash
npm run dev
```

---

# 🤖 AI Capabilities

PathFinder AI leverages the **Gemini API** to power:
- Resume bullet generation
- AI cover letter writing
- Interview preparation questions
- Career guidance workflows
- Personalized AI responses

---

# 📱 Responsive Design

PathFinder AI is fully optimized for Desktop, Mobile, and Tablets.

---

# 🌟 Open Source & GSSoC 2026

We warmly welcome contributors from all backgrounds ❤️

PathFinder AI is actively preparing for **GirlScript Summer of Code 2026 (GSSoC'26)**.

We encourage contributions in:
- AI integrations
- Resume intelligence systems
- Performance optimization
- UI/UX enhancements
- Accessibility improvements
- Open-source documentation

---

# 🤝 Contributing

## 1️⃣ Fork the Repository
Click the **Fork** button at the top-right corner.

## 2️⃣ Create a Feature Branch
```bash
git checkout -b feature/your-feature-name
```

## 3️⃣ Make Your Changes
Follow the existing coding style and project structure.

## 4️⃣ Commit Your Changes
```bash
git commit -m "feat: add amazing feature"
```

## 5️⃣ Push to GitHub
```bash
git push origin feature/your-feature-name
```

## 6️⃣ Create a Pull Request
Open a PR with a clear description and screenshots if UI changes were made.

---

# 📌 Contribution Guidelines

Before contributing, ensure:
- ✅ Code is production-ready
- ✅ UI is responsive
- ✅ Existing conventions are followed
- ✅ Documentation is updated if needed
- ✅ Changes are tested locally

---

# 🏷️ Label System

We use a comprehensive labeling system to organize our workflow. Our labeling is **automated** via GitHub Actions.

### 📊 Quick Reference

| Category | Key Labels |
| :--- | :--- |
| **Difficulty** | `level:beginner`, `level:intermediate`, `level:advanced`, `level:critical` |
| **Type** | `type:bug`, `type:feature`, `type:docs`, `type:design`, `type:security` |
| **Domain** | `frontend`, `backend`, `database`, `ai`, `ui/ux` |
| **Programs** | `Gssoc`, `good first issue` |

For a full list of labels and how the automation works, see our [**Label Management Guide**](docs/LABELS.md).

---

# ✅ How to Get Assigned an Issue

1. Comment on the issue.
2. Explain your planned approach.
3. Wait for maintainer approval.
4. Start working after assignment.

### Example
```text
Hi maintainers 👋

I would like to work on this issue under GSSoC'26.

Planned approach:
- Improve validation flow
- Optimize API handling
- Update related documentation

Could you please assign it to me?
```

---

# 🔥 Pull Request Guidelines

Before submitting a PR:
- Sync with latest `main`
- Resolve merge conflicts
- Add screenshots for UI changes
- Reference related issues

### PR Naming Convention
```text
feat: add resume analytics dashboard
fix: resolve onboarding bug
docs: improve setup guide
```

---

# 🧪 Development Standards

- **Frontend**: Use reusable components, Tailwind conventions, and maintain accessibility.
- **Backend**: Validate inputs, follow RESTful principles, and handle edge cases.
- **AI Features**: Optimize prompt engineering and handle fallback cases.

---

# 📖 Beginner-Friendly Ideas

- Documentation improvements
- UI polishing / Loading skeletons
- Mobile responsiveness
- Accessibility fixes
- Unit testing

---

# 🏆 Contributor Recognition

All contributors are recognized publicly.
- ✅ Contributors automatically appear in the README
- 🌟 Major contributors may receive special mentions
- 🚀 Long-term contributors can become collaborators

---

# ❤️ Our Contributors

<p align="center">
  <a href="https://github.com/harshdwivediiiii/pathfinder-ai/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=harshdwivediiiii/pathfinder-ai&max=500" alt="PathFinder AI Contributors" />
  </a>
</p>

---

# 🤝 Code of Conduct

Please be respectful and collaborative. We aim to maintain a welcoming environment for everyone.

---

# 📄 License

This project is licensed under the [MIT License](LICENSE).

---

# ✉️ Contact

📧 **harshvardhandwivedi18@gmail.com**

---

# 🌐 Deployment

Deploy instantly using **Vercel**.
[Next.js Deployment Documentation](https://nextjs.org/docs/app/building-your-application/deploying)

---

# 🌍 Support the Project

If you like PathFinder AI:
- ⭐ Star the repository
- 🍴 Fork the project
- 🚀 Join during GSSoC'26
- 📢 Share with developers

---

<p align="center">
  <strong>PathFinder AI</strong> – <em>Smart Careers Start Here.</em>
</p>
