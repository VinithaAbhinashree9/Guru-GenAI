# Guru-GenAI
Google solution challenge
Problem Statement: "Competitive exam students lack consistent, on-demand access to personalized mentorship and peer support, hindering their ability to effectively prepare and succeed."

Goal of the MVP: To validate the assumption that students will actively use a platform to connect with peers or mentors for on-demand study support, and that this connection provides tangible value.

MVP Concept: "Guru-GenAI"

A simple web platform facilitating immediate or short-term scheduled connections between students preparing for the same exam (initially NEET/PGCET) for specific study tasks.

Core Value Proposition: Find a study partner or get quick help right when you need it.

Key Features for the MVP (Keep it MINIMAL):

User Profiles (Ultra-Simple):

Signup/Login: Basic email/password or Google Auth.

Profile Info:

Name/Username

Exam Preparing For (Dropdown: NEET / PGCET)

Current Status (Radio buttons: "Looking to study NOW", "Looking to schedule soon", "Just browsing/helping")

Subject/Topic Focus (Text input or predefined tags: e.g., "Physics - Kinematics", "Biology - Genetics", "Chemistry - Organic Qs")

Brief Goal (Text input: e.g., "Solve 10 physics problems", "Discuss botany chapter 5", "Clear doubt on mechanism")

"Live Connect" Dashboard:

A simple list/feed showing users currently "Looking to study NOW".

Display: Username, Exam, Subject/Topic Focus, Goal.

Sort/Filter: Basic filtering by Exam (NEET/PGCET) is essential. Subject filtering is a bonus if feasible.

Connection Mechanism:

A "Connect" or "Chat Request" button next to users on the dashboard.

When clicked, it sends a notification (or initiates a very basic chat).

Crucially: To keep it MVP, the actual study session might happen OFF-platform initially. The MVP's job is just to make the connection. The platform could facilitate sharing a temporary link (e.g., Google Meet, Discord, simple text chat). Alternatively, if time permits, implement a very basic 1-on-1 text chat within the app.

(Optional but Recommended) Basic Scheduling:

Allow users with "Looking to schedule soon" status to post a request with a time/date and topic.

Other users can browse these requests and signal interest. Again, coordination might happen off-platform initially.

What NOT to Include in the MVP:

Complex mentor profiles or verification systems (Focus on peer-to-peer first).

Detailed progress tracking.

Integrated video/audio call features (use external tools).

Content libraries or notes sharing.

Ratings and review systems (can add later based on feedback).

Gamification or points.

Mobile app (start with web).

Technology Stack Suggestion (for a Hackathon):

Frontend: React, Vue, or Svelte (Choose what the team knows best). Use a UI library like Material UI, Chakra UI, or Tailwind CSS for speed.

Backend:

Firebase/Supabase: Excellent choices for rapid development. They handle authentication, real-time database (for the live dashboard), and potentially basic functions easily.

Node.js (Express) + a simple DB (like PostgreSQL/MongoDB hosted on Render/Railway): If the team prefers more traditional backend control.

Deployment: Vercel or Netlify for the frontend, Render/Fly.io/Railway/Firebase Hosting/Supabase Hosting for the backend.

How to Create the "MVP Link":

Build: Develop the features listed above using your chosen tech stack.

Deploy:

Deploy the frontend code to Vercel or Netlify. They will automatically give you a URL like your-project-name.vercel.app or your-project-name.netlify.app. This is your primary MVP link.

Deploy the backend code (if separate) to a service like Render, Railway, Fly.io, or use the backend capabilities of Firebase/Supabase which are accessible via API endpoints configured in your frontend.

Configure: Ensure your frontend code correctly points to your backend API endpoints or Firebase/Supabase project.

Test: Access the generated Vercel/Netlify URL and test all the MVP features thoroughly.

Share: This .vercel.app or .netlify.app link is what you share with testers, judges, and initial users.

Success Metrics for the MVP:

Number of user signups.

Number of users setting status to "Looking to study NOW".

Number of successful connection requests initiated.

Qualitative feedback: Are users finding relevant partners? Is the connection process easy? Does it solve their immediate need?
