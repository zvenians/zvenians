# Kevin Simatupang

Full-stack developer focused on building resilient web systems, cloud API integrations, and practical workflow platforms.

Based in Balikpapan, Indonesia | Working with **PT. Wulandari Bangun Laksana**

---

## What I Build

I design and build production-grade web applications with a focus on data boundary isolation, serverless API design, and clean user experience. My core work spans modern Next.js and TypeScript ecosystems, Google Cloud platform integrations, and custom workflow automation.

* **Full-Stack Web Systems:** Modern, high-performance applications built with Next.js, React, and TypeScript.
* **Cloud & Storage Architectures:** Integration with Google Cloud APIs (Drive API v3 OAuth2), Firebase (Firestore, Authentication), and serverless proxy layers.
* **Workflow Automation & Tooling:** Custom administrative platforms, role-based access control (RBAC), and Google Apps Script automation via Clasp.
* **Editorial & Progressive Web Apps:** High-contrast, responsive user interfaces with offline service worker caching and WCAG-compliant design.

---

## Featured Production Projects

### 1. [GMAHK Galilea Digital Archive](https://github.com/zvenians/gmahk-galilea-digital-archive)
A cloud media repository and document discovery engine designed to permanently organize and preserve weekly worship bulletins, liturgy documents, and church media records.

* **Stack:** Next.js 16 (App Router), TypeScript, React 19, Tailwind CSS 4, Google Drive API v3 (OAuth2), Firebase Firestore & Auth
* **Architecture:** Implements strict data boundary enforcement (scoping Drive operations strictly within managed folder hierarchies), a client-side multi-file upload queue with byte-level progress reporting, and serverless in-memory caching to optimize API quotas.
* **Links:** [Repository](https://github.com/zvenians/gmahk-galilea-digital-archive) | [Live Application](https://drive-galilea.vercel.app)

### 2. [GMAHK Galilea Web Portal](https://github.com/zvenians/gmahk-galilea)
Production church web portal providing an editorial, cinematic interface for congregation worship, liturgy resources, and community news.

* **Stack:** JavaScript (ES6+), Vercel Serverless Functions, Google Apps Script, PWA (Service Worker), CSS3
* **Architecture:** Features full-screen narrative chapters, custom Bible and Hymnal readers with presenter modes, and an isolated Vercel serverless proxy bridging client requests to an upstream Google Apps Script backend with zero-trust allowlisting.
* **Links:** [Repository](https://github.com/zvenians/gmahk-galilea) | [Live Application](https://gmahk-galilea.vercel.app)

### 3. [Majelis Galilea](https://github.com/zvenians/majelis-galilea)
Church governance and board administration system handling meeting minutes, resolutions, and official document automation.

* **Stack:** Google Apps Script, Clasp, Vercel Serverless Proxy, Google Sheets DB, Single-Page Architecture
* **Architecture:** Multi-tiered role-based access control (ADMIN, KEUANGAN, PENGURUS, MAJELIS), automated PDF letterhead generation, and pre-deployment validation scripts enforcing backend integrity.
* **Links:** [Repository](https://github.com/zvenians/majelis-galilea) | [Live Application](https://majelis-galilea.vercel.app)

---

## Historical & Exploration Work

* **[galilea](https://github.com/zvenians/galilea)** - *Historical Prototype (2023):* Initial repository exploring church website architecture; superseded by the production `gmahk-galilea` portal.
* **[roulanx.github.io](https://github.com/zvenians/roulanx.github.io)** - *Legacy Student Project (2020):* Early static responsive web development assignment built with Bootstrap 4. ([Live Preview](https://zvenians.github.io/roulanx.github.io/))

---

## Technical Stack

| Area | Technologies & Tools |
| :--- | :--- |
| **Frontend** | Next.js (App Router), React, TypeScript, JavaScript (ES6+), Tailwind CSS, HTML5, CSS3 |
| **Backend & Cloud** | Node.js, Vercel Serverless Functions, Firebase (Firestore, Auth), Google Cloud APIs (Drive API v3, OAuth 2.0) |
| **Automation & Tooling** | Google Apps Script, Clasp, Git, GitHub CLI, Progressive Web Apps (PWA) |
| **Testing & Quality** | Node.js Test Runner (`node:test`), ESLint, WCAG Contrast Compliance |

---

## Engineering Practices

* **Data Isolation:** All third-party storage integrations (e.g., Google Drive) enforce strict parent-folder boundaries, preventing unauthorized traversals.
* **Serverless Proxy Design:** Upstream API keys and internal deployment IDs are kept strictly server-side behind Vercel serverless functions with explicit method allowlists.
* **Quota-Conscious Caching:** In-memory TTL caches protect external cloud API quotas while ensuring responsive load times for end users.
* **Accessibility First:** Visual themes adhere to WCAG contrast standards (minimum 4.5:1 for standard text) across dark and light modes.

---

## Contact & Profiles

* **GitHub:** [@zvenians](https://github.com/zvenians)
* **Location:** Balikpapan, East Kalimantan, Indonesia
* **Organization:** PT. Wulandari Bangun Laksana