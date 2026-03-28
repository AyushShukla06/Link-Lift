# 👋 Welcome to LinkLift

Hey there! I built LinkLift to make it incredibly easy for developers and creators to spin up stunning, modern digital portfolios. Instead of settling for a boring static resume, LinkLift lets you build highly interactive, 3D-powered personal sites in just a few clicks.

### 🛠️ The Tech Stack
Here's a quick look under the hood at what's powering this app:
- **Framework:** Next.js (App Router)
- **Styling & Animation:** Tailwind CSS, Framer Motion, and GSAP
- **Database & Auth:** Supabase
- **3D Interactive Elements:** React Three Fiber / Drei
- **Payments:** Razorpay

### 🚀 Getting Started

If you want to run this locally on your own machine, it's pretty straightforward.

1. Install the dependencies:
   ```bash
   npm install
   ```

2. Fire up the development server:
   ```bash
   npm run dev
   ```

3. Head over to [http://localhost:3000](http://localhost:3000) to see it in action.

### 📂 Quick Tour
- Feel free to poke around the `app/` directory to see how the Next.js routing is set up.
- Check out the `components/templates/` folder if you want to look at the different 3D portfolio designs (like the CyberNeon or ZenMinimalist templates).

*(Note: If you're setting this up from scratch, you'll need to create a `.env.local` file and plug in your own Supabase credentials and Razorpay keys!)*
