# 🗂️ StoreMate - Storage Management Web Application

A professional, production-ready storage management platform that helps you upload, organize, and share your files with ease. Built with Next.js 15 and powered by Appwrite.

![TypeScript](https://img.shields.io/badge/TypeScript-90%25+-blue.svg)
![Next.js](https://img.shields.io/badge/Next.js-15+-black.svg)
![Appwrite](https://img.shields.io/badge/Appwrite-Cloud-pink.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 🌐 Live Demo

**[Try StoreMate Now!](https://your-deployment-url.vercel.app/)** 🚀

Experience the app live without any installation required.

## ✨ Features

- **🔐 Secure Authentication**: Sign up and sign in with OTP-based email verification
- **📤 File Uploads**: Upload documents, images, videos, and more with ease
- **🗂️ File Management**: Rename, share, and delete files from one place
- **🔍 Global Search & Filter**: Instantly find any file across all categories
- **📊 Dashboard Overview**: Visualize your storage usage and recent activity
- **📱 Responsive Design**: Works seamlessly on desktop and mobile devices
- **🔃 Sorting**: Sort files by name, date, size, and type
- **⚡ Fast & Efficient**: Optimized file routing and cached data for instant results

## 🚀 Demo

The application features:
- A clean, modern layout with sidebar and mobile navigation
- File uploads with real-time progress
- Dynamic file type routes for organized browsing
- Elegant file cards with actions dropdown (rename, share, delete)
- Global search with instant results across all file types

## 🛠️ Technology Stack

- **Frontend**: Next.js 15 with Tailwind CSS
- **Backend**: Appwrite (Authentication, Storage, Database)
- **Language**: TypeScript
- **Styling**: Tailwind CSS with custom theming
- **Code Quality**: ESLint & Prettier
- **Components**: shadcn/ui

## 📋 Prerequisites

Before running this application, make sure you have:

- Node.js 18 or higher installed
- npm or yarn (package manager)
- An [Appwrite](https://appwrite.io/) account
- Internet connection

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/devensm/Storemate
   cd Storemate
   ```

2. **Install required packages**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env.local` file in the root directory:
   ```env
   NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
   NEXT_PUBLIC_APPWRITE_PROJECT=your_project_id
   NEXT_PUBLIC_APPWRITE_DATABASE=your_database_id
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=your_users_collection_id
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=your_files_collection_id
   NEXT_PUBLIC_APPWRITE_BUCKET=your_bucket_id
   NEXT_APPWRITE_KEY=your_secret_api_key
   ```

## 🎮 Usage

1. **Run the development server**
   ```bash
   npm run dev
   ```

2. **Open your browser**
   - The application will be available at `http://localhost:3000`

3. **Start managing files**
   - Sign up or log in with OTP verification
   - Upload files using the upload button
   - Browse, search, and manage your files from the dashboard

## 📊 How It Works

### Storage & File Management System

1. **Authentication**: Users sign up with their email and verify identity via a one-time password (OTP) modal

2. **File Uploads**:
   - Files are uploaded directly to Appwrite Storage
   - Metadata (name, type, size, owner) is stored in the Appwrite Database
   - Supports documents, images, videos, and other file types

3. **Dynamic File Routes**:
   - Files are organized and accessible via dynamic Next.js routes by type
   - Real-time updates reflect changes instantly

4. **Search & Filter**:
   - Global search queries file metadata across all categories
   - Filters allow narrowing results by file type

5. **Actions**:
   - Rename, share (with other users), and delete files via the actions dropdown
   - File details modal shows size, upload date, and owner info

## 📁 Project Structure

```
Storemate/
│
├── app/                     # Next.js app router (pages & layouts)
├── components/              # Reusable UI components
├── constants/               # App-wide constants
├── hooks/                   # Custom React hooks
├── lib/                     # Appwrite config & utility functions
├── public/                  # Static assets
├── types/                   # TypeScript type definitions
├── .eslintrc.json           # ESLint configuration
├── .gitignore               # Git ignore rules
├── components.json          # shadcn/ui component config
├── next.config.ts           # Next.js configuration
├── tailwind.config.ts       # Tailwind CSS configuration
├── tsconfig.json            # TypeScript configuration
└── README.md                # Project documentation
```

## 🎨 UI Features

- **Custom Design System**: Clean light theme with custom color tokens and theming
- **Typography**: Modern sans-serif fonts for a professional look
- **Animations**: Smooth hover effects and transitions on file cards
- **Card Layout**: Responsive grid layout for file browsing
- **Sidebar & Mobile Nav**: Persistent sidebar on desktop, slide-out nav on mobile

## 📦 Dependencies

```
next >= 15.0.0           # React full-stack framework
react >= 18.0.0          # UI library
appwrite >= 14.0.0       # Backend-as-a-Service SDK
tailwindcss >= 3.4.0     # Utility-first CSS framework
typescript >= 5.0.0      # Static typing for 90%+ of the codebase
eslint >= 8.0.0          # Code linting
```

## 🔮 Future Enhancements

- [ ] Add file preview for images, PDFs, and videos
- [ ] Implement folder creation and nested organization
- [ ] Add storage usage progress bar per file type
- [ ] Enable public file sharing via shareable links
- [ ] Add collaborative access with role-based permissions
- [ ] Integrate notifications for shared file activity
- [ ] Dark mode support
- [ ] Multi-language support

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**devensm*
- GitHub: [@devensm](https://github.com/devensm)

## 🙏 Acknowledgments

- [Appwrite](https://appwrite.io/) for the powerful BaaS platform
- [Next.js](https://nextjs.org/) for the full-stack React framework
- [Tailwind CSS](https://tailwindcss.com/) for beautiful utility-first styling

## 📧 Contact

For questions, suggestions, or feedback, please open an issue on GitHub.

---

<div align="center">
  <strong>⭐ If you like this project, please give it a star! ⭐</strong>
</div>
