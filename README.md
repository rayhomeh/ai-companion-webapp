# The Companion – AI Relationship Chat App

A bold, flirty AI companion chat experience built with **Next.js**, **OpenAI**, and optional **Stripe** or **LemonSqueezy** integration. Chat with fun, flirty characters powered by GPT-4.

---

## Features

- User Authentication (via Supabase or Clerk)
- Character-Based AI Chat
- OpenAI GPT-4 Integration
- Subscription Access (Stripe or LemonSqueezy)
- Character Avatars & Personality Prompts
- Deployable via Vercel

---

## Tech Stack

- **Frontend:** Next.js + Tailwind CSS
- **API & Chat:** OpenAI GPT-4
- **Authentication & Storage:** Supabase *(planned)*
- **Payments:** Stripe or LemonSqueezy *(optional)*
- **Hosting:** Vercel

---

## Project Structure

/pages
index.js → Home page
characters.js → Character grid
/chat/[id].js → Chat UI
/api/chat.js → OpenAI API handler
/data
characters.json → Personality profiles
/public/avatars → Character avatar images
.env.local → API key (not committed)


