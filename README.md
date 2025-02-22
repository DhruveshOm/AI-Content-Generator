This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.




# AI Content Generator App

## 🚀 Overview
The **AI Content Generator App** is a powerful web application that utilizes AI to generate high-quality content, including blog posts, essays, code snippets, and more. It provides users with an intuitive interface to input their requirements and receive AI-generated content instantly.

## 🏗 Tech Stack
- **Frontend:** Next.js, React, Tailwind CSS, TypeScript
- **Backend:** Node.js, Express.js (if applicable)
- **Database:** MongoDB (if applicable)
- **Authentication:** Clerk
- **AI Model:** Gemini API
- **Hosting:** Vercel / Firebase / Render

## 🎯 Features
✅ **AI-Powered Content Generation**
✅ **Multiple Templates (Blog, Essay, Code, etc.)**
✅ **Custom Forms for Each Template**
✅ **User Authentication via Clerk**
✅ **Content Preview & Editing in Rich Text Editor**
✅ **Responsive & Modern UI**

## 🔄 Project Structure
```
📂 AI-Content-Generator-App
 ├── 📁 public/                # Static assets (icons, images, etc.)
 ├── 📁 src/
 │   ├── 📁 components/        # Reusable React components
 │   ├── 📁 pages/             # Next.js page components
 │   ├── 📁 styles/            # Tailwind CSS styling
 │   ├── 📁 utils/             # Utility functions
 │   ├── 📄 app.tsx            # Main entry file
 │   ├── 📄 index.tsx          # Landing page
 ├── 📄 package.json           # Dependencies & scripts
 ├── 📄 README.md              # Project documentation
 └── 📄 .gitignore             # Files to ignore in Git
```

## 🔧 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/ai-content-generator.git
cd ai-content-generator
```

### 2️⃣ Install Dependencies
```bash
npm install  # or yarn install
```

### 3️⃣ Set Up Environment Variables
Create a `.env.local` file and add the following variables:
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key
```

### 4️⃣ Run the Development Server
```bash
npm run dev  # or yarn dev
```
Access the app at `http://localhost:3000`

## 🚀 Usage Guide
1. **Sign Up / Log In** using Clerk authentication.
2. **Select a Template** (Blog Generator, Essay Writer, Code Generator, etc.).
3. **Enter Input Data** into the form fields.
4. **Generate Content** using the AI model.
5. **Edit & Copy the Output** as needed.

## 🛠 Troubleshooting & Debugging
### ❌ Clerk Authentication Issue
- Ensure that your Clerk API key is correctly set in `.env.local`.
- Convert the **Settings** route to a catch-all route (`[[...rest]]/page.tsx`).

### ❌ API Not Responding
- Verify your **Gemini API key** is correct.
- Check the network request in the browser's **Developer Tools** (`F12 → Network Tab`).

## 🔮 Future Enhancements
- 📌 **More AI Models (OpenAI, Claude, etc.)**
- 📌 **Improved Content Summarization & Formatting**
- 📌 **Save & Download AI-Generated Content**

## 🤝 Contributing
Feel free to fork this repository and submit pull requests. We welcome improvements and feature suggestions!


---

💡 **Made with ❤️ by [Dhruvesh Singh Om]**
