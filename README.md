# InterviewGenie 🧞‍♂️

![InterviewGenie Logo](public/robot.png)

> Master your interviews with AI-powered practice sessions that provide real-time feedback, boosting your confidence and landing you that dream job.

## 📱 Screenshots

<!-- Add your screenshots here. Examples: -->
<!-- ![Home Page](screenshots/home.png) -->
<!-- ![Interview Session](screenshots/interview-session.png) --> 
<!-- ![Feedback Page](screenshots/feedback.png) -->

## ✨ Features

- 🤖 **AI-Powered Interviews**: Practice with realistic interview scenarios powered by advanced AI
- 💬 **Real-time Feedback**: Get instant analysis on your responses and performance
- 📊 **Progress Tracking**: Monitor your improvement over time with detailed metrics
- 📝 **Diverse Question Bank**: Practice with questions from various industries and job roles
- 📱 **Responsive Design**: Seamless experience across all devices

## 🛠️ Tech Stack

- **Frontend**: Next.js 15, React 19, TailwindCSS 4
- **Backend**: Firebase (Authentication, Firestore, Storage)
- **AI**: Google Generative AI, VAPI
- **Styling**: Tailwind CSS, Radix UI
- **State Management**: React Hook Form
- **Deployment**: Vercel

## 🚀 Getting Started

### Prerequisites

- Node.js 20.x or higher
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/interviewgenie.git
   cd interviewgenie
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables
   Create a `.env.local` file with the following variables:
   ```
   FIREBASE_PROJECT_ID=your-project-id
   FIREBASE_PRIVATE_KEY=your-private-key
   FIREBASE_CLIENT_EMAIL=your-client-email
   GOOGLE_GENERATIVE_AI_API_KEY=your-api-key
   NEXT_PUBLIC_VAPI_WEB_TOKEN=your-vapi-token
   NEXT_PUBLIC_FIREBASE_API_KEY=your-firebase-api-key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-auth-domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-storage-bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your-sender-id
   NEXT_PUBLIC_FIREBASE_APP_ID=your-app-id
   NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=your-measurement-id
   ```

4. Run the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the application

## 📂 Project Structure

```
interviewgenie/
├── app/                   # Next.js app directory
│   ├── (auth)/            # Authentication related pages
│   ├── (root)/            # Main application pages
│   ├── api/               # API routes
│   └── layout.tsx         # Root layout
├── components/            # Reusable components
├── firebase/              # Firebase configuration
├── lib/                   # Utility functions and actions
├── public/                # Static assets
└── types/                 # TypeScript type definitions
```

## 🔒 Authentication

InterviewGenie uses Firebase Authentication for secure user management. Users can sign up and log in using:
- Email and password
- Google authentication

## 🧠 AI Integration

The application leverages Google's Generative AI and VAPI for:
- Generating realistic interview questions
- Analyzing user responses
- Providing personalized feedback
- Creating custom interview scenarios

## 🎨 UI/UX

- Modern, clean interface with responsive design
- Accessible components using Radix UI
- Smooth animations and transitions
- Dark/light mode support

## 📈 Future Enhancements

- Industry-specific interview preparation
- Video interview practice with facial expression analysis
- Resume analysis and improvement suggestions
- Interview scheduling with real professionals
- Community features for peer feedback

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

- Your Name - [GitHub Profile](https://github.com/yourusername)

## 🙏 Acknowledgements

- [Next.js](https://nextjs.org/)
- [Firebase](https://firebase.google.com/)
- [Google Generative AI](https://ai.google.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Radix UI](https://www.radix-ui.com/)
