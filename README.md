
#  Store It

**Store It** is a modern, full-featured Google Drive clone built as part of a learning exercise inspired by the [JS Mastery](https://www.jsmastery.pro/) series. It offers a sleek, responsive interface for uploading, managing, and sharing files — all powered by cutting-edge tools in the modern web ecosystem.

**Live Demo:** 👉 [https://storeit-gules.vercel.app/](https://storeit-gules.vercel.app/)

##  Tech Stack

- **React 19** – Declarative UI with the latest updates
- **Next.js 15** – App router, server actions, and RSC support
- **Appwrite** – Backend-as-a-service for storage and authentication
- **TailwindCSS** – Utility-first styling
- **ShadCN UI** – Clean, accessible components built with Radix
- **TypeScript** – Static typing for scalability and safety

## Features

- ** User Authentication** 
  Secure login, signup, and logout flows via Appwrite’s built-in auth system.

- ** File Uploads** 
  Seamlessly upload documents, images, videos, and audio files with real-time feedback.

- ** File Management** 
  View all your uploaded files in one place. Rename, delete, or open them in a new tab.

- ** Download Support** 
  Download any uploaded file instantly for offline access.

- ** File Sharing** 
  Share files with others by granting access via email, enabling smooth collaboration.

- ** Interactive Dashboard** 
  See total and used storage, recent uploads, and a breakdown of file types in a visual dashboard.

- ** Global Search** 
  Search for any file by name or type across your personal and shared files.

- ** Smart Sorting** 
  Sort files by date, name, or size to keep your workspace organized.

- ** Responsive Design** 
  Optimized UI for all screen sizes with a minimal, elegant layout built using Tailwind and ShadCN.

- ** Modern Stack & Architecture** 
  Built using the latest React 19 and Next.js 15 features with a clean, scalable codebase.

##  Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/store-it.git
cd store-it
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure environment variables

Create a `.env.local` file and add your Appwrite credentials:

```env
NEXT_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_BUCKET_ID=your_bucket_id
NEXT_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION_ID=your_collection_id
```

### 4. Run the development server
```bash
npm run dev
```


##  License

This project is open-source and available under the [MIT License](LICENSE).

---

## Acknowledgements

- Inspired by the **JS Mastery** course and Appwrite tutorials.
- Built for educational purposes and hands-on practice with full-stack technologies.
