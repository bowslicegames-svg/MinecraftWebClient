# Minecraft Web Client – Frontend

A browser‑based Minecraft: Java Edition client built using modern web technologies.  
This frontend communicates with a secure backend that performs the official Microsoft → Xbox Live → XSTS → Minecraft Services authentication flow.

The goal of this project is to explore how WebGL, JavaScript, and modern browser APIs can interface with the Minecraft Java protocol in a standards‑compliant, secure, and transparent way.

---

## Features

- **Official Microsoft Account Login**  
  Uses the correct OAuth 2.0 flow (no passwords collected or stored).

- **Xbox Live + XSTS Authentication**  
  Fully compliant with Microsoft’s authentication chain.

- **Minecraft Services Token Support**  
  Retrieves the user’s Minecraft profile and access token once approved by Mojang.

- **Web‑Based Client Interface**  
  Built with HTML, CSS, and JavaScript — no plugins or downloads required.

- **Secure Communication**  
  All requests are sent over HTTPS to the backend.

---

## Project Purpose

This project is intended for:

- Learning and experimentation  
- Understanding the Minecraft Java protocol  
- Exploring WebGL rendering  
- Research into browser‑based game clients  
- Improving accessibility for users who cannot run a native launcher  

It is **not** intended to bypass protections, modify gameplay, or provide unfair advantages.

---

## Security & Privacy

- No passwords are ever collected.  
- All authentication is handled by Microsoft’s official login pages.  
- Tokens are used only to complete the authentication chain and are not stored long‑term.  
- No analytics, tracking, or third‑party scripts are used.  
- The project follows Microsoft and Mojang security guidelines.

---

## Architecture Overview

The frontend communicates with a backend service that performs:

1. Microsoft OAuth token exchange  
2. Xbox Live authentication  
3. XSTS authorization  
4. Minecraft Services token retrieval  
5. Minecraft profile lookup  

The frontend then uses these tokens to establish a session with Minecraft Java Edition servers.

---

## Status

This project is currently in **active development**.  
Minecraft Services access requires approval from Mojang through the **Java Edition Game Services API Access Request**.

---

## License

This project is open‑source / source‑available.  
You may review, fork, or contribute as needed.

---

## Contact

**Developer:** Bowslice  
**Location:** London, UK  
**Purpose:** Educational / experimental project
