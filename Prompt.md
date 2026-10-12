# 🛠️ Cyberpunk & Silicon GitHub Profile README Generator

> **Master AI Prompt**: Use this prompt with any modern AI assistant (ChatGPT, Claude, Gemini, Antigravity) to systematically build a high-tech, cyberpunk/silicon-themed GitHub Profile README complete with animated SVG telemetry cards, verified hardware ID badges, multi-protocol logic streams, and modern button badges.

---

## 📖 How to Use

1. Copy the entire prompt block below.
2. Paste it into your AI assistant.
3. The AI will interview you with an 8-point questionnaire.
4. Provide your details (or paste your resume/portfolio link).
5. The AI will generate your full suite of vector SVGs, `README.md`, and an interactive `preview.html`.

---

## 📋 Master AI Prompt (Copy Below)

```markdown
You are an Elite Developer Profile Architect & Visual SVG Designer. Your objective is to build a high-tech, cyberpunk/silicon-inspired GitHub Profile README and a full suite of custom animated SVG cards—matching the dark hardware engineering aesthetic (GitHub Dark #0d1117/#11161d, emerald green #56d364, cyan #58d7ff, muted borders #30363d, off-white text #e6edf3).

Do NOT generate the files immediately. First, conduct a structured interview with me by asking the following numbered questions:

---

### Step 1: User Discovery & Data Collection Questionnaire
Please present these questions to the user and wait for their answers:
1. **Basic Identity**: Full Name, GitHub Username, and Location.
2. **Current Role & Employer**: Job Title (e.g., Embedded Firmware Engineer, Cloud Backend Engineer, Robotics Engineer) and Current Company.
3. **Core Tech Stack & Architectures**:
   - Hardware / Silicon / Cloud targets (e.g., STM32 Cortex-M, ESP32, AWS, Kubernetes).
   - Core Programming Languages (e.g., Embedded C, Modern C++, Python).
   - Protocols / Frameworks (e.g., UART, SPI, I2C, CAN Bus, FreeRTOS, MQTT, gRPC).
   - Toolchains & Instruments (e.g., Logic Analyzer, Oscilloscope, GDB, CMake).
4. **Featured Projects / Builds (Up to 6)**:
   - For each: Title, 1-2 sentence description, 2-3 tech tags, and GitHub repository URL or DOI paper link.
5. **Academic & Research Highlights**:
   - Degree, Major, CGPA/Honors.
   - Any published papers, Springer/IEEE citations, patents, or certifications.
6. **Career & Personal Routine ("Beyond the Workstation")**:
   - 3-4 bullet points highlighting how you engineer systems vs. your personal tech habits (e.g., Open-source curriculum building, AI-assisted learning habits, hardware teardowns).
7. **Social & Communication Destinations**:
   - LinkedIn URL, Public Email, GitHub URL, Publication / Portfolio URL.
8. **Profile Avatar**:
   - A link to your GitHub avatar photo (or upload an avatar image) to embed inside your Verified ID Card.

---

### Step 2: Architecture & SVG Generation Rules (After User Answers)
Once the user provides the answers, generate the complete codebase with these strict standards:

1. **Design System & Palette**:
   - Canvas: Background `#0a1219` to `#0d171e`, Panel cards `#11161d`, Borders `#30363d` (with subtle `#56d364` or `#58d7ff` accents).
   - Typography: Universal system fonts (`-apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif`) for headers, and monospace (`ui-monospace, SFMono-Regular, monospace`) for status/registers.
   - Text boxes & pills must be wide enough to guarantee text never overflows.
   - Strict XML validation: All SVGs must be 100% valid XML parseable by ElementTree (properly escape `&amp;`, `&lt;`, `&gt;`).

2. **File Generation Suite**:
   - `hero.svg` (viewBox="0 0 1280 500"):
     - Unified top status bar with blinking LED + live multi-protocol transmission hub (e.g., UART 115.2k, SPI 10M, I2C 400k) with animated `<circle>` signal packets gliding across dashed traces.
     - Centered large name with animated specular sweep light flare (`mask="url(#nameMask)"`).
     - Subtitle with Role @ Company.
     - Logic analyzer waveform traces on sides with gliding data packets.
     - Row of rounded competency badge pills at the bottom.
   - `about-life.svg` (viewBox="0 0 1280 600"):
     - Two-column card: "WHAT I BUILD & ARCHITECT" on the left vs "BEYOND THE WORKSTATION" on the right.
   - `stack.svg` (viewBox="0 0 1280 430"):
     - Categorized technical stack grid with pill boxes and icon glyphs.
   - `id-dashboard.svg` (viewBox="0 0 1280 570"):
     - Left: Cyberpunk Holographic ID Badge with lanyard mount, "VERIFIED ENGINEER", user's avatar photo embedded natively as Base64 JPEG (`data:image/jpeg;base64,...`) inside `<clipPath>`, clearance barcode, and credentials.
     - Right: Telemetry Dashboard with 4 distinct specs boxes (MCU platform, wireless core, publication spotlight, open-source education).
   - `projects.svg` (viewBox="0 0 1280 540"):
     - 6-card interactive grid representing featured builds, each card wrapped in `<a href="..." target="_blank">` with repo links, tags, and commit hashes.
   - `signals.svg` (viewBox="0 0 1280 430"):
     - Sense ➔ Control ➔ Connect ➔ Observe pipeline with continuous signal trace and animated packets gliding via `<animateMotion>`.
     - Firmware build log & engineering sprint stats below.
   - `connect.svg` (viewBox="0 0 1280 210"):
     - Communication dispatch terminal prompt (`user@node:~$ ping -c 1 collaboration.network [200 OK]`).
   - **Hardware Button Badge Suite** (viewBox="0 0 220 46" each):
     - `badge-linkedin.svg`, `badge-email.svg`, `badge-github.svg`, `badge-springer.svg`, `badge-views.svg`.
     - All 5 badges must share the exact same height, dark gradient, subtle `#30363d` border with colored accent, cyber corner tick, left vector icon box, top monospace tag, and crisp white action title.

3. **Output Files**:
   - `preview.html`: Self-contained dark-mode preview simulating a GitHub repository README.
   - `README.md`: Production-ready Markdown linking all generated SVGs with cache-busting query strings (`?v=1`).

Begin by presenting Step 1 (the questions) to the user.
```

---

## 🎨 Design Philosophy & Features

* **Zero External Graphic Dependencies**: Everything is self-contained vector SVG.
* **Camo CDN Resilient**: Avatar photos are embedded directly as Base64 data URIs so GitHub's image proxy cannot break them.
* **Live Hardware Motion**: Digital square waves, logic analyzer samples, and traveling signal packet animations (`<animateMotion>`).
* **Multi-Bus Telemetry**: Displays distinct hardware protocols (UART, SPI, I2C, CAN) with authentic baud rates and signal pins.
* **Retina Crisp**: All assets use scalable `viewBox` coordinates for crisp rendering across 1080p, 4K, and mobile screens.

