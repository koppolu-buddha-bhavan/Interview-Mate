# Interview-Mate

**Interview-Mate** is an AI-powered platform for practicing job interviews and receiving instant, structured feedback. It simulates real interview scenarios using voice and text, leveraging advanced AI models to generate questions and analyze candidate responses.

## Features

- 🤖 **AI-Generated Interview Questions:** Practice with questions tailored to your chosen role, experience level, and tech stack.
- 🗣️ **Voice & Text Interview Simulation:** Interact with an AI interviewer in real-time, mimicking real interview conditions.
- ⭐ **Instant Feedback:** Receive detailed, category-based feedback on your performance, including communication, technical knowledge, problem-solving, and more.
- 🔒 **User Authentication:** Secure sign-up and sign-in with Firebase.
- 💻 **Modern UI:** Responsive, accessible design using Next.js, Tailwind CSS, and Radix UI components.

## Tech Stack

- **Frontend:** Next.js 15, React 19, Tailwind CSS
- **Backend/Serverless:** Next.js API routes
- **AI/ML:** Google Gemini, OpenAI GPT-4 (via Vapi and ai-sdk)
- **Authentication & Database:** Firebase (client and admin SDKs)
- **Voice/Transcription:** Vapi, Deepgram, 11labs
- **Form Handling:** React Hook Form, Zod validation
- **UI Components:** Radix UI, Lucide Icons, shadcn/ui

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/interview-mate.git
cd interview-mate
```

### 2. Install dependencies

```bash
npm install
# or
yarn install
```

### 3. Set up environment variables

Create a `.env.local` file in the root directory and add your Firebase, Vapi, and AI provider credentials:

```
NEXT_PUBLIC_FIREBASE_API_KEY=...
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=...
NEXT_PUBLIC_FIREBASE_PROJECT_ID=...
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=...
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=...
NEXT_PUBLIC_FIREBASE_APP_ID=...
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=...
FIREBASE_PROJECT_ID=...
FIREBASE_CLIENT_EMAIL=...
FIREBASE_PRIVATE_KEY=...
NEXT_PUBLIC_VAPI_WEB_TOKEN=...
NEXT_PUBLIC_VAPI_WORKFLOW_ID=...
# Add any other required API keys
```

### 4. Run the development server

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

## Project Structure

- `app/` – Next.js app directory (routes, layouts, API)
- `components/` – Reusable React components
- `firebase/` – Firebase client and admin setup
- `lib/` – Utility functions and server actions
- `constants/` – Static mappings and configuration
- `public/` – Static assets (images, icons)
- `types/` – TypeScript type definitions

## Scripts

- `npm run dev` – Start the development server
- `npm run build` – Build for production
- `npm start` – Start the production server
- `npm run lint` – Lint the codebase

## Contributing

Pull requests and issues are welcome! Please open an issue to discuss your ideas or report bugs.

## License

[MIT](LICENSE) (add a LICENSE file if you haven’t already)
