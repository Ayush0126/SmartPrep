
---

#  SmartPrep — AI-Powered Interview Preparation

SmartPrep is a next-generation AI-driven mock interview platform designed to help candidates prepare for technical and behavioral interviews. Built using **Next.js** and powered by **Vapi.ai**, SmartPrep simulates realistic interviewer conversations using speech and NLP capabilities.

##  Features

*  **Real-time AI Voice Interviewing** using Vapi's speech-based AI
*  **Dynamic Question Flow** tailored to user responses
*  **Feedback & Analytics** to track performance
*  **Custom Interview Scripts** with easy workflow control
*  **Modern Frontend** built in Next.js with Tailwind CSS and shadcn/ui
*  **Responsive Design** – Use it on desktop or mobile

---

##  Tech Stack

| Tech         | Purpose                               |
| ------------ | ------------------------------------- |
| Next.js      | React Framework for UI & routing      |
| Vapi.ai      | AI voice interaction & workflow logic |
| Tailwind CSS | UI styling                            |
| Shadcn/ui    | Beautiful reusable components         |
| Netlify       | Deployment platform                  |

---

##  Architecture Overview

1. **Frontend**: Built with `Next.js` using React hooks and components.
2. **Voice Layer**: Vapi workflows manage the AI interview logic.
3. **Integration**:

   * Vapi SDK used for initializing and managing voice calls
   * Webhooks or client APIs handle flow transitions and answer capturing
4. **State Handling**: `useState`, `useEffect`, and context for app state
5. **Deployment**: Easily deployable on Vercel or any Node-based platform

---

##  Installation & Setup

```bash
# Clone the repository
git clone https://github.com/Ayush0126/smartprep.git
cd smartprep

# Install dependencies
npm install

# Set environment variables
touch .env.local
```

Add your Vapi API Key in `.env.local`:

```env
NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key
```

Then run the app:

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser.

---

##  How It Works

1. User clicks **Start Interview**
2. Vapi connects to a voice model through defined workflow
3. AI begins asking questions, listens to answers, and dynamically decides next question
4. After the interview, feedback and scoring are shown on screen

---

##  How to Customize Interview Questions

To customize the flow:

* Go to your [Vapi Dashboard](https://dashboard.vapi.ai/)
* Edit your **workflow**: add/capture questions, say blocks, logic branches
* Use `capture` blocks to process user responses
* Reference the `workflow_id` in your code to start the desired flow

---


##  Author

**Ayush Panwar**
3rd-year Computer Engineering, Thapar Institute
[LinkedIn](https://www.linkedin.com/in/ayush-panwar603957264) • [Portfolio](https://portfolioayush26.netlify.app/) • [GitHub](https://github.com/Ayush0126)

---
## Live At --> [Link](https://smartprep1.netlify.app/)
