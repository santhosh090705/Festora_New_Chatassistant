# 🤖 Festora Assistant — AI-Powered Event Booking Chat

> A standalone AI chat assistant for the Festora event booking platform. Powered by Google Gemini AI with live Firebase data integration.

## 🌐 Live URL
👉 **[https://main.d13lqnm5gu6l55.amplifyapp.com](https://main.d13lqnm5gu6l55.amplifyapp.com)**

🔗 **Main Website:** [https://main.d39qu7n6qbh7g3.amplifyapp.com](https://main.d39qu7n6qbh7g3.amplifyapp.com)

---

## 💬 What Can It Do?

| Feature | Description |
|---------|-------------|
| 🎟 Browse Events | Fetches live events from Firestore with interactive cards |
| 🔍 Filter by Category | Music, Comedy, Sports, Festival, Tech |
| 🛒 Book Tickets in Chat | Full 3-step booking form — right inside the chat! |
| 📋 View My Bookings | Loads real booking history from Firebase |
| 🔐 Google Sign-In | Mandatory authentication before booking |
| 💡 FAQ Answering | Payment methods, VIP benefits, e-pass info |
| ⚡ Quick Commands | 14 pre-built sidebar buttons for instant queries |

---

## 🗂 Project Structure

```
Festora New Chatassistant/
└── index.html    # Single-file chat assistant (all CSS + JS included)
```

---

## 🔧 Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, JavaScript (Vanilla) |
| AI Engine | Google Gemini 2.0 Flash API |
| Authentication | Firebase Google Auth |
| Database | Firebase Firestore |
| Hosting | AWS Amplify |
| Fonts | Google Fonts (Bebas Neue, DM Sans, DM Serif Display) |

---

## 🤖 AI Configuration

- **Model:** `gemini-2.0-flash`
- **API:** Google Generative Language API v1beta
- **System Prompt:** Knows all Festora events, prices, venues, seats in real-time
- **Context:** Live event data injected into every prompt from Firestore

---

## 🛒 Booking Flow (Inside Chat)

```
User types "Book Arijit Singh Live"
→ AI responds with event details
→ Booking card appears in chat
→ Step 1: Select ticket type (radio buttons) + quantity
→ Step 2: Enter name & email (auto-filled if signed in)  [REQUIRES SIGN-IN]
→ Step 3: Review order summary
→ Confirm → Saved to Firestore → Booking ID generated
→ View E-Pass button → redirects to main website ticket page
```

---

## 🔥 Firebase Integration

- **Project ID:** `festora-6bac8` (shared with main website)
- **Auth:** Google Sign-In (same users as main site)
- **Firestore:** Reads `events` collection, writes to `bookings` collection
- **Authorized Domain:** `main.d13lqnm5gu6l55.amplifyapp.com`

---

## ⚡ Quick Commands Available

**Events:** All Events, Music, Comedy, Sports, Festival, Tech  
**Bookings:** My Bookings, View Tickets  
**Help:** How to Book, Payment Methods, VIP Benefits, Get E-Pass, Available Seats, Best Price

---

## 🚀 Deployment

Connected to GitHub via **AWS Amplify** — auto-deploys on every push.

```bash
git add .
git commit -m "Your message"
git push
```

---

## 🔗 Related Repositories

- **Main Website:** [github.com/santhosh090705/Festora_New](https://github.com/santhosh090705/Festora_New)
- **Chat Assistant:** [github.com/santhosh090705/Festora_New_Chatassistant](https://github.com/santhosh090705/Festora_New_Chatassistant)

---

## 👨‍💻 Developer

**Santhosh** — [@santhosh090705](https://github.com/santhosh090705)

---

## 📄 License

This project is for educational and portfolio purposes.
