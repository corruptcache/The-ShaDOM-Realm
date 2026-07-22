# The ShaDOM Realm 👁️

Curated by Corruptcache

Welcome to The ShaDOM Realm, an interactive, gamified learning environment focused strictly on client-side web vulnerabilities. Loosely themed around the Yu-Gi-Oh! trading card game, this Capture The Flag (CTF) platform challenges players to manipulate browser state, inspect front-end architecture, and intercept client-network interactions to uncover hidden flags.

## ⭐ Enjoying the realm? Star this repository to get updates when new challenge cards are released! ⭐

## 👁️ The Inspiration

The name is a play on the browser's "Shadow DOM" and the infamous "Shadow Realm" from the Yu-Gi-Oh! anime series.

In the show, the Shadow Realm is a mystical, hidden dimension where the true, dangerous mechanics of a duel unfold. Similarly, a modern web application's client-side state acts as a hidden layer where the underlying logic reside. To conquer these challenges, you cannot simply trust the user interface; you must look beneath the surface and master the mechanics hidden in the developer tools.

## 🖥️ Recommended Setup

This environment is heavily stylized and requires specific UI interactions. It is highly recommended to play on a Desktop or Laptop computer. Mobile devices and smaller screens may find the interface difficult to navigate or lack the necessary Developer Tools required to solve the challenges.

## 🚀 How to Play

You do not need to download or install anything to play. The entire realm is hosted live!

[Enter The ShaDOM Realm Here](https://corruptcache.github.io/The-ShaDOM-Realm/)

(Optional) If you wish to review the source code locally, this project is built using entirely Vanilla HTML, CSS, and JavaScript. There is no complex build step or backend required.
```
git clone https://github.com/corruptcache/The-ShaDOM-Realm.git
```
Open index.html in any modern web browser.

## 🃏 Current Challenges

1. Heart of the Cache (Magic Card) - Available

Vulnerability: Unsafe Client-Side State Management

Objective: Traverse levels to assemble a True Name and bypass a session-based failure lock.

Techniques: Browser Forensics, Client-Side State Analysis.

2. The Millennium Token (Trap Card) - Coming Soon

Vulnerability: Insecure JWT / Token Forgery

Objective: Decode the payload, shatter the signature seal, and forge a new destiny as an Administrator.

3. The Shadow Router (Field Card) - Coming Soon

Vulnerability: Client-Side Access Control & Hidden Routes

Objective: Dissect the underlying front-end routing architecture to discover unlinked, restricted pathways.

4. Source Map Secrets (Effect Card) - Coming Soon

Vulnerability: Information Disclosure via Source Maps

Objective: Reconstruct minified JavaScript source code using browser DevTools to unearth hardcoded credentials.

5. The Front-End Filter (Link Card) - Coming Soon

Vulnerability: Client-Side Data Filtering

Objective: Intercept raw JSON API payloads to find administrative rows that the UI is explicitly hiding.

## 💡 Why Client-Side?

Many modern web applications push business logic, routing, and state management directly to the client. The ShaDOM Realm exists to demonstrate that the client can never be trusted. If it happens in the browser, the user controls it.

## 📝 Write-Ups and Spoilers

Write-ups are highly encouraged! Teaching others how you solved a challenge is one of the best ways to solidify your own knowledge. However, please try to avoid posting outright spoilers or raw flags (flag{...}) in public forums without warning tags, so new players can still enjoy the "Aha!" moments.

## 🤝 Contributing & Bug Reports

As this is a curated personal portfolio project, I am not currently accepting Pull Requests for new challenges or features to keep the scope defined.

However, if you find a bug, a broken UI element, or a typo, please open an Issue! I appreciate the help keeping the realm polished.

## 🔗 Links

Creator: [Corruptcache](https://corruptcache.me)

LinkedIn: [Andrew Knowles](https://www.linkedin.com/in/johnaknowles/)

## 📜 License

This project is licensed under the MIT License.
