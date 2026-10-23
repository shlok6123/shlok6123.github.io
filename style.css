/* ==========================================================================
   THEME VARIABLES (DARK FIRST, LIGHT TOGGLE)
   ========================================================================== */
:root {
  --bg-primary: #0a0e17;
  --bg-secondary: #111827;
  --bg-card: #151e31;
  --bg-terminal: #0d1322;
  --text-primary: #f3f4f6;
  --text-secondary: #9ca3af;
  --accent: #10b981;
  --accent-hover: #059669;
  --accent-subtle: rgba(16, 185, 129, 0.12);
  --border-color: #1e293b;
  --font-sans: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
  --font-mono: 'JetBrains Mono', monospace;
  --transition: 0.22s ease;
  --max-width: 1060px;
}

[data-theme="light"] {
  --bg-primary: #f8fafc;
  --bg-secondary: #f1f5f9;
  --bg-card: #ffffff;
  --bg-terminal: #0f172a;
  --text-primary: #0f172a;
  --text-secondary: #475569;
  --accent: #059669;
  --accent-hover: #047857;
  --accent-subtle: rgba(5, 150, 105, 0.1);
  --border-color: #e2e8f0;
}

/* ==========================================================================
   BASE & RESET
   ========================================================================== */
*, *::before, *::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 78px;
}

body {
  font-family: var(--font-sans);
  background-color: var(--bg-primary);
  color: var(--text-primary);
  line-height: 1.65;
  transition: background-color var(--transition), color var(--transition);
  -webkit-font-smoothing: antialiased;
}

.container {
  width: 90%;
  max-width: var(--max-width);
  margin: 0 auto;
}

.inline-link {
  color: var(--accent);
  text-decoration: underline;
  text-underline-offset: 3px;
}

.skip-link {
  position: absolute;
  top: -100px;
  left: 1rem;
  background: var(--accent);
  color: #fff;
  padding: 0.5rem 1rem;
  z-index: 1000;
  border-radius: 4px;
  text-decoration: none;
}
.skip-link:focus { top: 1rem; }

/* ==========================================================================
   NAVBAR
   ========================================================================== */
.site-header {
  position: sticky;
  top: 0;
  z-index: 100;
  background-color: rgba(10, 14, 23, 0.88);
  border-bottom: 1px solid var(--border-color);
  backdrop-filter: blur(10px);
}

[data-theme="light"] .site-header {
  background-color: rgba(248, 250, 252, 0.9);
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 70px;
}

.logo {
  font-family: var(--font-mono);
  font-size: 1.35rem;
  font-weight: 700;
  color: var(--text-primary);
  text-decoration: none;
}

.logo-bracket, .accent-dot {
  color: var(--accent);
}

.nav-controls {
  display: flex;
  align-items: center;
  gap: 0.65rem;
  order: 2;
}

.nav-links {
  display: none;
  list-style: none;
  flex-direction: column;
  position: absolute;
  top: 70px;
  left: 0;
  width: 100%;
  background-color: var(--bg-secondary);
  border-bottom: 1px solid var(--border-color);
  padding: 1rem 0;
}

.nav-links.open {
  display: flex;
}

.nav-link {
  display: block;
  padding: 0.7rem 1.5rem;
  color: var(--text-secondary);
  text-decoration: none;
  font-weight: 500;
  font-size: 0.94rem;
  transition: color var(--transition);
}

.nav-link:hover, .nav-link.active {
  color: var(--accent);
}

.icon-btn {
  background: var(--bg-card);
  border: 1px solid var(--border-color);
  color: var(--text-primary);
  padding: 0.45rem 0.65rem;
  border-radius: 6px;
  cursor: pointer;
  font-size: 0.95rem;
}

.hamburger {
  display: block;
  width: 18px;
  height: 2px;
  background: var(--text-primary);
  position: relative;
}
.hamburger::before, .hamburger::after {
  content: '';
  position: absolute;
  width: 18px;
  height: 2px;
  background: var(--text-primary);
  left: 0;
}
.hamburger::before { top: -6px; }
.hamburger::after { top: 6px; }

/* ==========================================================================
   COMMON SECTIONS & BUTTONS
   ========================================================================== */
.section {
  padding: 4.5rem 0;
  border-bottom: 1px solid var(--border-color);
}

.section-title {
  font-size: 1.7rem;
  font-weight: 700;
  margin-bottom: 2.25rem;
  position: relative;
  display: inline-block;
}

.section-title::after {
  content: '';
  display: block;
  width: 45%;
  height: 3px;
  background-color: var(--accent);
  margin-top: 0.35rem;
  border-radius: 2px;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.68rem 1.3rem;
  border-radius: 6px;
  font-weight: 600;
  font-size: 0.92rem;
  font-family: var(--font-sans);
  text-decoration: none;
  transition: all var(--transition);
  cursor: pointer;
}

.btn-sm {
  padding: 0.48rem 0.95rem;
  font-size: 0.84rem;
}

.btn-primary {
  background-color: var(--accent);
  color: #ffffff;
  border: 1px solid var(--accent);
}
.btn-primary:hover {
  background-color: var(--accent-hover);
  border-color: var(--accent-hover);
}

.btn-secondary {
  background-color: var(--accent-subtle);
  color: var(--accent);
  border: 1px solid rgba(16, 185, 129, 0.35);
}
.btn-secondary:hover {
  background-color: var(--accent);
  color: #ffffff;
}

.btn-outline {
  background-color: transparent;
  color: var(--text-primary);
  border: 1px solid var(--border-color);
}
.btn-outline:hover {
  border-color: var(--accent);
  color: var(--accent);
}

/* ==========================================================================
   HERO SECTION & METRICS BAR
   ========================================================================== */
.hero-section {
  padding: 5rem 0 4.5rem;
  border-bottom: 1px solid var(--border-color);
}

.availability-badge {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  font-family: var(--font-mono);
  font-size: 0.8rem;
  color: var(--accent);
  background: var(--accent-subtle);
  border: 1px solid rgba(16, 185, 129, 0.3);
  padding: 0.3rem 0.8rem;
  border-radius: 999px;
  margin-bottom: 1.25rem;
}

.pulse-dot {
  width: 8px;
  height: 8px;
  background-color: var(--accent);
  border-radius: 50%;
  display: inline-block;
}

.hero-name {
  font-size: clamp(2.4rem, 5vw, 3.8rem);
  font-weight: 700;
  line-height: 1.12;
  margin-bottom: 0.5rem;
}

.hero-headline {
  font-size: clamp(1.2rem, 2.8vw, 1.75rem);
  color: var(--text-secondary);
  font-weight: 600;
  margin-bottom: 1.25rem;
}

.hero-pitch {
  max-width: 680px;
  color: var(--text-secondary);
  font-size: 1.05rem;
  margin-bottom: 2rem;
}

.hero-cta {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-bottom: 3rem;
}

.metrics-bar {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;
  padding-top: 2rem;
  border-top: 1px solid var(--border-color);
}

.metric-item {
  background: var(--bg-card);
  border: 1px solid var(--border-color);
  padding: 0.9rem 1.1rem;
  border-radius: 8px;
}

.metric-val {
  display: block;
  font-family: var(--font-mono);
  font-size: 1.05rem;
  font-weight: 700;
  color: var(--accent);
}

.metric-label {
  font-size: 0.82rem;
  color: var(--text-secondary);
}

/* ==========================================================================
   ABOUT & CODE TERMINAL CARD
   ========================================================================== */
.about-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
  align-items: center;
}

.about-content p {
  color: var(--text-secondary);
  margin-bottom: 1rem;
  font-size: 1rem;
}

.about-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-top: 1.25rem;
  padding-top: 1rem;
  border-top: 1px dashed var(--border-color);
  font-size: 0.9rem;
}

.terminal-card {
  background-color: var(--bg-terminal);
  border: 1px solid var(--border-color);
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.25);
}

.terminal-header {
  background: #1e293b;
  padding: 0.6rem 1rem;
  display: flex;
  align-items: center;
  gap: 0.45rem;
}

.dot {
  width: 10px;
  height: 10px;
  border-radius: 50%;
}
.dot.red { background: #ef4444; }
.dot.yellow { background: #f59e0b; }
.dot.green { background: #10b981; }

.terminal-title {
  font-family: var(--font-mono);
  font-size: 0.78rem;
  color: #cbd5e1;
  margin-left: 0.5rem;
}

.terminal-body {
  padding: 1.25rem;
  font-family: var(--font-mono);
  font-size: 0.82rem;
  line-height: 1.6;
  color: #e2e8f0;
  overflow-x: auto;
}

.code-kw { color: #f472b6; }
.code-cls { color: #38bdf8; }
.code-str { color: #34d399; }
.code-num { color: #fbbf24; }
.code-cm { color: #64748b; }

/* ==========================================================================
   SKILLS SECTION
   ========================================================================== */
.skills-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.25rem;
}

.skill-category {
  background-color: var(--bg-card);
  border: 1px solid var(--border-color);
  padding: 1.4rem;
  border-radius: 8px;
}

.skill-group-title {
  font-size: 1rem;
  margin-bottom: 0.9rem;
  color: var(--text-primary);
}

.chip-container {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
}

.chip {
  font-family: var(--font-mono);
  font-size: 0.8rem;
  background-color: var(--accent-subtle);
  color: var(--accent);
  padding: 0.32rem 0.7rem;
  border-radius: 999px;
  border: 1px solid rgba(16, 185, 129, 0.25);
}

/* ==========================================================================
   PROJECTS & INTERACTIVE ARCHITECTURE DRAWER
   ========================================================================== */
.projects-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.5rem;
}

.project-card {
  background-color: var(--bg-card);
  border: 1px solid var(--border-color);
  border-radius: 8px;
  padding: 1.6rem;
  display: flex;
  flex-direction: column;
  transition: transform var(--transition), border-color var(--transition);
}

.project-card:hover {
  transform: translateY(-3px);
  border-color: var(--accent);
}

.project-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 0.75rem;
  margin-bottom: 0.65rem;
}

.project-eyebrow {
  font-family: var(--font-mono);
  font-size: 0.75rem;
  color: var(--accent);
  display: block;
  margin-bottom: 0.15rem;
}

.project-title {
  font-size: 1.2rem;
  font-weight: 600;
}

.status-badge {
  font-family: var(--font-mono);
  font-size: 0.72rem;
  background-color: var(--bg-secondary);
  color: var(--text-secondary);
  padding: 0.22rem 0.55rem;
  border-radius: 4px;
  border: 1px solid var(--border-color);
  white-space: nowrap;
}

.status-badge.live {
  background-color: var(--accent-subtle);
  color: var(--accent);
  border-color: rgba(16, 185, 129, 0.3);
}

.project-desc {
  color: var(--text-secondary);
  font-size: 0.94rem;
  margin-bottom: 1rem;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-bottom: 1.15rem;
}

.project-tags span {
  font-family: var(--font-mono);
  font-size: 0.74rem;
  background-color: var(--bg-secondary);
  color: var(--text-secondary);
  padding: 0.22rem 0.5rem;
  border-radius: 4px;
  border: 1px solid var(--border-color);
}

.project-bullets {
  padding-left: 1.15rem;
  margin-bottom: 1.15rem;
  color: var(--text-secondary);
  font-size: 0.9rem;
  flex-grow: 1;
}

.project-bullets li {
  margin-bottom: 0.45rem;
}

.arch-drawer {
  margin-bottom: 1.2rem;
  border: 1px solid var(--border-color);
  border-radius: 6px;
  background-color: var(--bg-secondary);
}

.arch-toggle {
  width: 100%;
  background: none;
  border: none;
  color: var(--text-primary);
  font-family: var(--font-mono);
  font-size: 0.78rem;
  padding: 0.6rem 0.85rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  cursor: pointer;
}

.arch-content {
  padding: 0.75rem 0.85rem;
  border-top: 1px solid var(--border-color);
  font-size: 0.82rem;
}

.arch-line {
  margin-bottom: 0.45rem;
  color: var(--text-secondary);
}

.endpoint-pill {
  display: inline-block;
  font-family: var(--font-mono);
  font-size: 0.74rem;
  background: var(--bg-card);
  color: var(--accent);
  padding: 0.2rem 0.45rem;
  border-radius: 4px;
  margin: 0.2rem 0.25rem 0.2rem 0;
  border: 1px solid var(--border-color);
}

.arch-note {
  margin-top: 0.5rem;
  font-size: 0.76rem;
  color: var(--text-secondary);
  font-style: italic;
}

.project-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.65rem;
  margin-top: auto;
}

/* ==========================================================================
   TIMELINE (EXPERIENCE & EDUCATION)
   ========================================================================== */
.timeline {
  position: relative;
  border-left: 2px solid var(--border-color);
  margin-left: 0.6rem;
  padding-left: 1.6rem;
}

.timeline-item {
  position: relative;
  margin-bottom: 2.2rem;
}
.timeline-item:last-child { margin-bottom: 0; }

.timeline-marker {
  position: absolute;
  left: -2rem;
  top: 0.35rem;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background-color: var(--accent);
  border: 2px solid var(--bg-primary);
}

.timeline-date {
  font-family: var(--font-mono);
  font-size: 0.8rem;
  color: var(--accent);
  display: block;
  margin-bottom: 0.2rem;
}

.timeline-title {
  font-size: 1.12rem;
  font-weight: 600;
  margin-bottom: 0.15rem;
}

.timeline-org {
  color: var(--text-secondary);
  font-size: 0.94rem;
  margin-bottom: 0.45rem;
}

.timeline-grade {
  font-size: 0.9rem;
  color: var(--text-secondary);
}

.timeline-bullets {
  padding-left: 1.15rem;
  color: var(--text-secondary);
  font-size: 0.9rem;
}
.timeline-bullets li { margin-bottom: 0.35rem; }

/* ==========================================================================
   CONTACT & FOOTER
   ========================================================================== */
.contact-box {
  background-color: var(--bg-card);
  border: 1px solid var(--border-color);
  border-radius: 8px;
  padding: 2.4rem 1.5rem;
  text-align: center;
}

.contact-text {
  max-width: 580px;
  margin: 0 auto 1.5rem;
  color: var(--text-secondary);
}

.contact-actions {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0.75rem;
  margin-bottom: 1.5rem;
}

.contact-links {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  gap: 0.75rem;
  font-size: 0.92rem;
}

.contact-link {
  color: var(--text-primary);
  text-decoration: none;
  font-weight: 500;
}
.contact-link:hover { color: var(--accent); }

.divider { color: var(--text-secondary); }

.site-footer {
  padding: 2rem 0;
  text-align: center;
  color: var(--text-secondary);
  font-size: 0.85rem;
}

/* ==========================================================================
   SCROLL REVEAL & RESPONSIVE BREAKPOINTS
   ========================================================================== */
.reveal {
  opacity: 0;
  transform: translateY(16px);
  transition: opacity 0.45s ease-out, transform 0.45s ease-out;
}
.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}

@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
  .reveal { opacity: 1; transform: none; transition: none; }
}

@media (min-width: 768px) {
  .mobile-menu-btn { display: none; }

  .nav-links {
    display: flex;
    flex-direction: row;
    position: static;
    width: auto;
    background: transparent;
    border: none;
    padding: 0;
    gap: 1.4rem;
  }

  .nav-link { padding: 0; }

  .metrics-bar {
    grid-template-columns: repeat(4, 1fr);
  }

  .about-grid {
    grid-template-columns: 1.35fr 1fr;
  }

  .skills-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .projects-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}