# Hi, I'm Alberto 👋

**Robotics Engineering student · Industrial automation × AI · iOS & web builder**

I'm currently interning in industrial automation, where I program PLCs and build the tools I wish the job already had. Outside the plant I ship my own apps for iPhone and the web, and I design websites for small businesses in my city.

The thread that ties it together: **make systems traceable and machine-checkable, so AI can help build them safely.**

---

### ⚙️ Industrial automation × AI

*PLC engineering is still mostly manual and hard to verify. I build tools that make it structured enough for software, and AI, to check.*

| Project | What it does | Stack |
|---|---|---|
| **PLC project toolkit** *(desktop)* | Offline companion for Rockwell PLC projects: GRAFCET editor, L5X parser and generator, project-wide cross-reference ("where is this signal used?"), double-coil detection, sequence simulator, and export back to Studio 5000. | Rust · WASM · Tauri 2 · React 19 · TypeScript |
| **Grafsets** | Browser-based GRAFCET (IEC 60848) editor with cross-sheet signal tracing, revisions, and PDF documentation. Fully local. | React · React Flow · PWA |
| **LLM agents that write PLC code** | Research on getting an industrial AI agent to produce *verifiable* PLC logic: a programming standard, rule sets, a scan simulator, a linter, and differential tests (equivalence checked over 192k scans). | Python · Ladder / ST / SFC · L5X |
| **L5X agent skill** | A Claude skill that turns GRAFCET specs into importable Studio 5000 SFC routines, validated 1:1 against real re-exports, with an eval harness. | Python · Claude Agent Skills |
| **IIoT telemetry architecture** | Design for secure, outbound-only telemetry from industrial gateways to a serverless cloud dashboard. | Ewon · MQTT/TLS · AWS IoT |

### 📱 Apps I build for myself

| Project | What it does | Stack | Status |
|---|---|---|---|
| **[Macitta](https://macitta.vercel.app)** | Offline-first study app for English vocabulary and TOEFL practice, driven by my own spaced-repetition engine. | Next.js 15 · Supabase · Turborepo · PWA | 🟢 Live · v1.4 |
| **Rosa** | Native iPhone music player, 100% local: FLAC, gapless playback, EQ, synced lyrics, home and lock-screen widgets. | Swift · SwiftUI · WidgetKit | 🟡 In development |
| **Puerkito** | Personal finance PWA. | React · Vite · Supabase (RLS) | 🟡 In development |
| **Sitka** | On-device AI voice inbox for iPhone: dictate a thought and it becomes a reminder or an Obsidian note. No cloud. | SwiftUI · Apple Foundation Models | 🔵 In design |
| **Lector** | Distraction-free EPUB reader for iPhone and Mac that syncs highlights into my second brain. | SwiftUI · Swift Packages | 🔵 In design |
| **SkyVision** | ESP32 multi-sensor weather station streaming to Supabase, with a real-time dashboard. | C++ (ESP32) · React · Recharts | ✅ School project |

### 🎨 Web design for local businesses

On the side I run a local-visibility practice for small businesses in Hidalgo, México: mobile-first websites, Google Maps, and WhatsApp working together. → **[albertoanaya.com.mx](https://www.albertoanaya.com.mx)**

- **Stack:** Astro + Tailwind on Cloudflare with near-zero JavaScript; Next.js + Framer Motion for the premium tier
- **Built in:** WhatsApp CTAs, local SEO (JSON-LD, sitemaps, Google Business Profile), menus and pricing, brand kits
- **Example:** [albertojardinero.com](https://albertojardinero.com)

### 🧠 How I work

- **Spec first.** Decision records, specs, and HTML prototypes before writing code.
- **AI-native, but verified.** I use Claude Code every day, write agent skills with evals, and run agent-driven QA with Playwright. I also measure where AI fails.
- **Offline-first and private by default.** Local storage and on-device processing whenever possible.

### 🛠 Toolbox

| | |
|---|---|
| **Automation** | Rockwell Studio 5000 · Ladder / ST / SFC · GRAFCET (IEC 60848) · L5X · Ewon / Talk2M · HMI design |
| **Languages** | TypeScript · Rust · Python · Swift · C++ (ESP32) |
| **Web & apps** | React · Next.js · Astro · Tailwind · SwiftUI · Tauri · Supabase · Cloudflare · Vercel |
| **AI** | Claude Code · Agent Skills · MCP · Apple Foundation Models |

### 🌱 Currently exploring

- Connecting electrical design → tags → GRAFCET → PLC program in a single pipeline (Studio 5000, TIA Portal, EPLAN)
- On-device AI on iPhone
- Productized websites for local businesses

---

> Most of my work lives in private repositories (client and industrial code). I'm happy to walk you through any of it.

📫 **contacto.angel.anaya@gmail.com**
