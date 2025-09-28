# Social Calling App

A clean, minimal **React Native** social calling app built with **Supabase** (OTP auth & user profile) and **WebRTC** for real-time audio/video calls.

> **Specially made by Kartik Chilkoti**

---

## 🚀 Quick summary

* OTP-based phone authentication (Supabase)
* Collects gender & date-of-birth during registration
* Shows a list of registered users with **Audio Call** and **Video Call** buttons
* Real-time calls via **WebRTC** with noise suppression and echo cancellation
* Gender filter (Male / Female / All)
* Clean React Native UI

---

## 🧩 Tech stack

* React Native
* Supabase (Auth, Realtime, Postgres)
* WebRTC (`react-native-webrtc` or equivalent)

---

## 🔧 Quick setup

1. Clone repo:

```bash
git clone https://github.com/chilkotiKartik/social-calling.git
cd social-calling
```

2. Install:

```bash
yarn install
# or
npm install
```

3. Create a Supabase project, enable Phone (SMS) auth, and create the `profiles` table (see long README for SQL).
4. Copy `.env.example` → `.env` and fill `SUPABASE_URL` and `SUPABASE_ANON_KEY`.
5. Run the app:

```bash
npx react-native run-android
# or
npx react-native run-ios
```

---

## ⚠️ Notes & tips

* Configure an SMS provider (Twilio) to ensure OTP delivery.
* Use a TURN server for reliable media connectivity on mobile networks.
* Add microphone & camera permissions for iOS/Android.

---

## 📜 License

MIT

---

## ❤️ Credits

**Specially made by Kartik Chilkoti** — feel free to open issues or PRs.

---

_For full setup details, architecture notes, and troubleshooting, see the complete `README_full.md` in the repo (or ask me to paste the full README here)."
