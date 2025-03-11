![Screenshot 2025-03-11 100415](https://github.com/user-attachments/assets/99b142a3-d684-43c2-a901-7dc1183dea30)
![Screenshot 2025-03-11 100608](https://github.com/user-attachments/assets/553c8ec3-7070-47a6-b775-e3e88b855115)
![Screenshot 2025-03-11 100640](https://github.com/user-attachments/assets/9838bd3c-5fca-45cb-bfe8-e6580fd0ee39)



APP DEMO HERE " https://storage-management-solution-orpin.vercel.app/ "


🤖 Introduction
A storage management and file sharing platform that lets users effortlessly upload, organize, and share files. Built with the latest Next.js 15 and the Appwrite Node SDK, utilizing advanced features for seamless file management.


⚙️ Tech Stack
React 19
Next.js 15
Appwrite
TailwindCSS
ShadCN
TypeScript


🔋 Features
👉 User Authentication with Appwrite: Implement signup, login, and logout functionality using Appwrite's authentication system.

👉 FIle Uploads: Effortlessly upload a variety of file types, including documents, images, videos, and audio, ensuring all your important data.

👉 View and Manage Files: Users can browse through their uploaded files stored in Appwrite storage, view on a new tab, rename file or delete.

👉 Download Files: Users can download their uploaded files giving them instant access to essential documents.

👉 File Sharing: Users can easily share their uploaded files with others, enabling collaboration and easy access to important content.

👉 Dashboard: Gain insights at a glance with a dynamic dashboard that showcases total and consumed storage, recent uploads, and a summary of files grouped by type.

👉 Global Search: Users can quickly find files and shared content across the platform with a robust global search feature.

👉 Sorting Options: Organize files efficiently by sorting them by date, name, or size, making file management a breeze.

👉 Modern Responsive Design: A fresh and minimalist UI that emphasizes usability, ensuring a clean aesthetic across all devices.

and many more, including the latest React 19, Next.js 15 and Appwrite features alongside code architecture and reusability


🤸 Quick Start
Follow these steps to set up the project locally on your machine.

   Prerequisites

Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository

git clone https://github.com/wilfriedtech97/storage_management_solution.git
cd storage_management_solution
Installation

Install the project dependencies using npm:

npm install
Set Up Environment Variables

Create a new file named .env.local in the root of your project and add the following content:

"
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""
"


Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up & creating a new project on the Appwrite website.

Running the Project

npm run dev
Open http://localhost:3000 in your browser to view the project.

🕸️ Snippets

tailwind.config.ts
globals.css
constants/index.ts
lib/utils.ts
index.d.ts
