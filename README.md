# ✍️ Amour Editorials

**Amour Editorials** is a professional platform that helps students and professionals craft compelling Statements of Purpose (SOPs), Letters of Recommendation (LORs), and other academic documents — turning their dreams into impactful stories.

---

## 📌 Table of Contents

- [About Us](#about-us)
- [Features](#features)
- [Preview](#preview)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Folder Structure](#folder-structure)
- [Requirement Document](#requirement-document)
- [Contributing](#contributing)
- [Connect with Us](#connect-with-us)

---

## 🧠 About Us

Amour Editorials was founded by Akshai Krishna A and Lathika D with the mission to help aspirants express their journeys with honesty and power through SOPs, LORs, and other impactful narratives. Backed by years of experience and acceptances to top global universities, the team ensures every story echoes across admission panels worldwide.

---

## 🌟 Features

- 🖥️ Fully responsive UI with 3D effects and animations
- 📄 Secure form submissions and email integrations
- 📅 Calendly booking support
- 🔐 File uploads through backend integration
- ⚙️ Modular and scalable Next.js frontend
- ✨ Advanced UI with Framer Motion and custom TSX components
- 🧪 TypeScript support and linting
- 🎯 SEO, performance, and accessibility focused
- 📎 Social sharing & legal pages (Privacy, Terms)

---

## 📷 Preview

| Page Name              | Description                                         |
|------------------------|-----------------------------------------------------|
| 🏠 Landing Page        | Engaging homepage with animation & brand overview  |
| 🧍 About Us            | Mission, vision, and team insights                  |
| 📑 Services            | SOP, LOR, Editing service details                   |
| 💬 Testimonials        | Client reviews and success stories                  |
| ❓ FAQs                | Process and timeline clarifications                 |
| 📚 Resources           | Samples and writing tips                            |
| 📝 Blog                | Informative articles on writing, branding, etc.     |
| 📅 Booking Page        | Calendly embed for consultation scheduling          |
| 📩 Contact Page        | Contact form connected to backend                   |
| 🔐 Privacy & Terms     | User protection documents                           |

---

## 🛠️ Tech Stack

### 🌐 Frontend – `amour-next-ts`

| Area               | Technology                      |
|-------------------|----------------------------------|
| Framework          | Next.js (App Router)             |
| Language           | TypeScript                      |
| Styling            | Tailwind CSS                    |
| Animations         | Framer Motion                   |
| Component Library  | Custom + ShadCN (UI primitives) |
| Icons              | Lucide                          |
| Build Tool         | Vite / Next.js build            |
| Linting            | ESLint                          |

### 🔧 Backend – `amour-Backend`

| Area               | Technology                      |
|-------------------|----------------------------------|
| Runtime            | Node.js                         |
| Framework          | Express.js                      |
| API Routes         | `/form` (formRoutes.js)         |
| Controllers        | `formController.js`             |
| Email Service      | Nodemailer (`emailService.js`)  |
| Security           | Helmet, CORS, HTTPS             |

### ☁️ Hosting & Deployment

| Component        | Platform                         |
|------------------|----------------------------------|
| Frontend Hosting | Vercel                           |
| Backend Hosting  | Render / Railway / AWS / Cyclic  |
| DB (Optional)    | Supabase / MongoDB Atlas         |
| CI/CD            | GitHub Actions (optional)        |

---

## 🚀 Installation

### Prerequisites:
- Node.js ≥ 18.x
- npm ≥ 9.x

### Clone the Repository

```bash
git clone https://github.com/sneha-94/Amour-Editorial-Website.git
cd Amour-Editorial-Website
```

### Frontend Setup

```bash
cd amour-next-ts
npm install
npm run dev
```

> Access frontend: `http://localhost:3000`

### Backend Setup

```bash
cd amour-Backend
npm install
node index.js
```

> Access backend: `http://localhost:5000` (or your configured port)

---

## 📁 Folder Structure

```
Amour-Editorial-Website/
├── amour-Backend/
│   ├── Controllers/
│   ├── routes/
│   ├── utilise/
│   ├── index.js
│   ├── package.json
│   └── ...
├── amour-next-ts/
│   ├── src/
│   │   ├── app/
│   │   ├── components/
│   │   └── lib/
│   ├── public/
│   └── ...
├── PROJECT-SETUP.md
├── Contributors.md
├── LICENSE
└── README.md
```

---

## 📄 Requirement Document

📎 [Click to view the complete project requirement document](https://drive.google.com/drive/folders/1UKhRycAPGKAMnXEQuGMF5JSSEaz0_awR?usp=sharing)

---

## 🤝 Contributing

We welcome contributions from developers, designers, writers, and testers! 💜

### How to Contribute

1. **Fork** the repository  
2. **Clone** to local  
3. **Create a new branch** for your feature/bug  
4. **Commit changes** with meaningful messages  
5. **Push** and create a Pull Request  

### Contribution Guidelines

- 🧹 Maintain code style & lint rules  
- 🚫 Don’t break existing features  
- 🧪 Write/modify tests (if applicable)  
- 💬 Be clear in PR descriptions  
- 🙌 Respect others and give constructive feedback  

---

## 📬 Connect with Us

- 🌐 [Official Website](https://amour-editorial-website.vercel.app/)
- 💼 [LinkedIn](https://www.linkedin.com/company/amour-editorial/)
- 📧 Email: contact@amour-editorial.com

---

_Your contributions will be reviewed and appreciated! Let’s build something impactful together._


---

## 📸 Project Screenshots

| Page / Feature      | Preview                                   |
|---------------------|-------------------------------------------|
| Landing Page        | ![Landing Page](images/landing-page.png) |
| Services Section    | ![Services](images/services.png)         |
| Booking Flow        | ![Booking](images/booking.png)           |
| Testimonials        | ![Testimonials](images/testimonials.png) |
| Responsive View     | ![Mobile View](images/mobile-view.png)   |
