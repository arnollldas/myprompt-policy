# Privacy Policy for the "MYPROMPT" Extension

> 🇩🇪 Deutschsprachig? Zur [Datenschutzerklärung auf Deutsch](./DATENSCHUTZ.md).

**Last Updated:** July 24, 2026

This Privacy Policy explains how "MYPROMPT" (hereinafter "the Extension") collects, uses, and protects personal data.

## 1. Developer

arnollldas  
Email: studio.tablet657@slmail.me

## 2. What Data Is Collected?

When you sign in with your Google account, the Extension collects the following data from Google to provide its functionality:

*   **Your Google ID:** A unique identifier to associate your prompts with your account.
*   **Your Email Address:** Displayed in your profile within the Extension.
*   **Your Name:** Displayed in your profile within the Extension.
*   **Your Profile Picture:** Displayed in your profile within the Extension.

Additionally, the prompts you create (title, content, icon, tags) are stored in the cloud and linked to your Google ID.

**No passwords are stored.** Authentication is handled exclusively through Google's secure OAuth 2.0 service.

## 3. How Is the Data Used?

Your data is used solely for the following purposes:

*   To verify your identity after login.
*   To securely store your prompts in the cloud and link them to your account.
*   To enable synchronization of your prompts across devices.
*   To display your profile (name, picture) within the Extension.

Your data is **not** shared with, sold to, or used by any third parties for advertising purposes.

## 4. AI Features (Prompt Enhancement & Synthesis)

The Extension offers optional AI-powered features (Improve Prompt, Generate Prompt, Arena Synthesis). When you use these features, the text you enter is forwarded to a serverless function (hosted on Vercel), which securely transmits it to the AI service Groq (groq.com) for processing.

*   No user inputs are permanently stored.
*   Using the AI features is optional and requires a Google sign-in (to protect AI access from abuse).
*   Groq processes requests according to its own privacy policy: [https://groq.com/privacy-policy/](https://groq.com/privacy-policy/)

**International Data Transfer:** Groq, Inc. is a US-based company (Mountain View, CA, USA). The transfer of your input data to the United States is based on Standard Contractual Clauses (SCCs) pursuant to Art. 46(2)(c) GDPR. The legal basis for processing is Art. 6(1)(f) GDPR (legitimate interests in providing AI functionality).

## 5. Data Storage

*   **Prompts and profile data** are stored in Google Firebase Firestore (cloud database), linked to your Google ID. All data is stored exclusively within the EU (Region: `eur3`, EU Multi-Region — European data centers). A Data Processing Agreement (DPA) pursuant to Art. 28 GDPR is in place with Google.
*   **Session data** (login status / sign-in token) is stored locally in your browser (`chrome.storage.local`). The extension accesses Google Firestore directly to store/load your prompts.
*   **Authentication and the AI proxy** run as serverless functions on Vercel in the EU region Frankfurt (they issue the sign-in token and relay AI requests so the AI key stays server-side).

## 6. Your Rights

You have the right at any time to:

*   **Request access** to your stored data.
*   **Request deletion** of your data — all associated prompts and profile data will be permanently removed.
*   **File a complaint** with the relevant data protection authority.

For data requests, contact: studio.tablet657@slmail.me

## 7. Changes to This Policy

This Privacy Policy may be updated from time to time. The current version is always available at this URL.

---
