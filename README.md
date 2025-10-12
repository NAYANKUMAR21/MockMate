# AI-Powered Mock Interview Platform

<div align="center">
  <p>An intelligent, full-stack web application that helps job seekers prepare for technical interviews using AI-powered mock interviews with real-time feedback and analysis.</p>
  
  [![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![ShadCN](https://img.shields.io/badge/Shadcn-20232A?style=for-the-badge&logo=shadcn&logoColor=61DAFB)](https://ui.shadcn.com/)
</div>

## 🚀 Features

- **AI-Powered Mock Interviews**: Practice with an intelligent AI interviewer that adapts to your responses
- **Real-time Feedback**: Get instant analysis on your answers, communication skills, and technical knowledge
- **Comprehensive Analytics**: Track your progress with detailed performance metrics
- **Multiple Interview Tracks**: Prepare for various technical roles including Frontend, Backend, Full Stack, and more
- **Session Recording**: Review your interview sessions with audio/video playback (Upcomming Feature)
- **Personalized Questions**: Dynamic question generation based on your experience level and role
- **Authentication**: Secure user authentication with email/password and social logins

## 🛠 Tech Stack

### Frontend

- **Next.js 15** - React framework for server-rendered applications
- **TypeScript** - Type-safe JavaScript for better developer experience
- **Tailwind CSS** - Utility-first CSS framework for responsive design
- **Framer Motion** - Animation library for smooth, interactive UIs
- **React Hook Form** - Form handling with validation
- **Zod** - TypeScript-first schema validation

### Backend

- **Next.js API Routes** - Serverless API endpoints
- **Firebase**
  - **Authentication** - User management and authentication
  - **Firestore** - NoSQL database for user data and interview history
  - **Storage** - Store interview recordings and media

### AI/ML

- **Vapi AI** - AI-powered voice interaction
- **Google AI SDK** - Advanced AI capabilities for interview analysis

### DevOps

- **Turbopack** - Fast, incremental bundler for development
- **ESLint** - Code quality and consistency
- **TypeScript** - Static type checking

## 📁 Project Structure

```
src/
├── app/                    # App router
│   ├── (auth)/             # Authentication routes
│   │   ├── sign-in/        # Sign in page
│   │   └── sign-up/        # Sign up page
│   ├── (root)/             # Protected routes
│   │   └── interview/      # Interview related pages
│   │       └── [id]/       # Dynamic interview sessions
│   │           └── feedback/ # Interview feedback
│   └── api/                # API routes
│       └── vapi/           # Vapi AI integration
├── components/             # Reusable UI components
├── constants/              # App constants
├── firebase/               # Firebase configuration
├── lib/                    # Utility functions
└── public/                 # Static assets
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0.0 or later
- npm or yarn
- Firebase project with Firestore, Authentication, and Storage enabled
- Vapi.ai API key
- Google AI API key

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/NAYANKUMAR21/MockMate.git
   cd MockMate
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Set up environment variables
   Create a `.env.local` file in the root directory and add the following:

   ```env
   NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id
   NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key
   GOOGLE_APPLICATION_CREDENTIALS=path_to_your_google_credentials.json
   ```

4. Run the development server

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🚀 Deployment

### Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

1. Build the application

   ```bash
   npm run build
   ```

2. If you have vercel CLI then run the below command.If not then please deploy through the vercel Website
   ```
   vercel .
   ```

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

Your Name - [@your_twitter](https://x.com/nayankumar___) - nayankumar\_\_\_

Project Link: [https://github.com/NAYANKUMAR21/MockMate](https://github.com/NAYANKUMAR21/MockMate)

---

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
