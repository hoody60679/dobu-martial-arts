/* ===== CSS VARIABLES ===== */
:root {
  --accent: #D4CFC8;
  --accent-dark: #B8B2AA;
  --black: #0C0C0C;
  --charcoal: #141414;
  --dark-grey: #1C1C1C;
  --mid-grey: #555;
  --light-grey: #F0EDE8;
  --white: #E8E4DD;
  --muted: #777;
  --font-display: 'Bebas Neue', sans-serif;
  --font-body: 'Open Sans', sans-serif;
  --nav-height: 70px;
  --transition: 0.3s ease;
}

/* ===== RESET ===== */
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
html { scroll-behavior: smooth; }
body {
  font-family: var(--font-body);
  background: var(--black);
  color: var(--white);
  font-size: 16px;
  line-height: 1.7;
  overflow-x: hidden;
}
img { max-width: 100%; display: block; }
a { text-decoration: none; color: inherit; }
ul { list-style: none; }

/* ===== NAVIGATION ===== */
nav {
  position: fixed;
  top: 0; left: 0; right: 0;
  height: var(--nav-height);
  background: rgba(12,12,12,0.97);
  border-bottom: 1px solid #1E1E1E;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 5%;
  z-index: 1000;
  backdrop-filter: blur(8px);
}
.nav-logo {
  font-family: var(--font-display);
  font-size: 2rem;
  color: var(--white);
  letter-spacing: 3px;
}
.nav-logo span { color: rgba(255,255,255,0.4); }
.nav-links {
  display: flex;
  gap: 2rem;
  align-items: center;
}
.nav-links a {
  font-size: 0.75rem;
  font-weight: 600;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #888;
  transition: color var(--transition);
  padding: 4px 0;
  border-bottom: 1px solid transparent;
}
.nav-links a:hover, .nav-links a.active {
  color: var(--white);
  border-bottom-color: rgba(255,255,255,0.3);
}
.nav-cta {
  color: var(--white) !important;
  padding: 8px 20px !important;
  border: 1px solid rgba(255,255,255,0.2) !important;
  border-bottom: 1px solid rgba(255,255,255,0.2) !important;
  transition: all var(--transition) !important;
}
.nav-cta:hover {
  border-color: rgba(255,255,255,0.5) !important;
  background: rgba(255,255,255,0.05) !important;
}
.hamburger {
  display: none;
  flex-direction: column;
  gap: 5px;
  cursor: pointer;
  padding: 5px;
  background: none;
  border: none;
}
.hamburger span {
  display: block;
  width: 26px;
  height: 2px;
  background: var(--white);
  transition: var(--transition);
}

/* ===== PAGES ===== */
.page { display: none; padding-top: var(--nav-height); min-height: 100vh; }
.page.active { display: block; }

/* ===== HERO ===== */
.hero {
  position: relative;
  min-height: calc(100vh - var(--nav-height));
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  overflow: hidden;
  background: var(--black);
}
.hero-bg {
  position: absolute;
  inset: 0;
  background:
    linear-gradient(135deg, rgba(255,255,255,0.02) 0%, transparent 50%),
    radial-gradient(ellipse at 80% 50%, rgba(255,255,255,0.01) 0%, transparent 60%);
}
.hero-grid {
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(255,255,255,0.025) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.025) 1px, transparent 1px);
  background-size: 60px 60px;
}
.hero-diagonal {
  position: absolute;
  right: -5%;
  top: 0;
  bottom: 0;
  width: 55%;
  background: #181818;
  clip-path: polygon(15% 0, 100% 0, 100% 100%, 0% 100%);
  opacity: 0.5;
}
.hero-content {
  position: relative;
  z-index: 2;
  max-width: 900px;
  padding: 0 5%;
  animation: fadeUp 0.9s ease forwards;
}
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}
.hero-tag {
  display: inline-block;
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #666;
  margin-bottom: 1.2rem;
  padding: 4px 14px;
  border: 1px solid #2A2A2A;
}
.hero h1 {
  font-family: var(--font-display);
  font-size: clamp(4rem, 10vw, 9rem);
  line-height: 0.9;
  letter-spacing: 4px;
  color: var(--white);
  text-transform: uppercase;
}
.hero h1 em {
  font-style: normal;
  color: rgba(255,255,255,0.3);
  display: block;
}
.hero-sub {
  font-size: 1rem;
  color: #666;
  max-width: 540px;
  margin: 1.5rem auto 2.5rem;
  font-weight: 300;
}
.hero-btns { display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap; }
.hero-stats {
  display: flex;
  justify-content: center;
  gap: 4rem;
  margin-top: 4rem;
  padding-top: 3rem;
  border-top: 1px solid rgba(255,255,255,0.07);
}
.stat-num {
  font-family: var(--font-display);
  font-size: 2.8rem;
  color: rgba(255,255,255,0.55);
  line-height: 1;
}
.stat-label { font-size: 0.65rem; letter-spacing: 2px; text-transform: uppercase; color: #444; margin-top: 4px; }

/* ===== BUTTONS ===== */
.btn-primary {
  background: transparent;
  color: var(--white);
  padding: 14px 36px;
  font-size: 0.75rem;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  border: 1px solid rgba(255,255,255,0.25);
  cursor: pointer;
  transition: all var(--transition);
  font-family: var(--font-body);
}
.btn-primary:hover { background: rgba(255,255,255,0.05); border-color: rgba(255,255,255,0.5); }
.btn-outline {
  background: transparent;
  color: var(--white);
  padding: 14px 36px;
  font-size: 0.75rem;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  border: 1px solid rgba(255,255,255,0.2);
  cursor: pointer;
  transition: all var(--transition);
  font-family: var(--font-body);
}
.btn-outline:hover { border-color: rgba(255,255,255,0.5); background: rgba(255,255,255,0.04); }

/* ===== SECTION STYLES ===== */
section { padding: 90px 5%; }
.section-label {
  font-size: 0.65rem;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #666;
  margin-bottom: 0.8rem;
  display: block;
}
.section-title {
  font-family: var(--font-display);
  font-size: clamp(2.2rem, 5vw, 3.5rem);
  letter-spacing: 2px;
  line-height: 1.05;
  color: var(--white);
}
.section-title span { color: rgba(255,255,255,0.4); }
.section-intro {
  color: #666;
  max-width: 580px;
  margin-top: 1rem;
  font-weight: 300;
  font-size: 0.95rem;
}
.section-header { margin-bottom: 3.5rem; }
.dark-section { background: var(--charcoal); }
.text-center { text-align: center; }
.text-center .section-intro { margin-left: auto; margin-right: auto; }
.text-center .divider { margin-left: auto; margin-right: auto; }

/* ===== DISCIPLINES ===== */
.disciplines-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.5px;
}
.discipline-card {
  background: var(--dark-grey);
  padding: 2.5rem 2rem;
  border-top: 1px solid #2A2A2A;
  transition: transform var(--transition), background var(--transition);
  cursor: pointer;
}
.discipline-card:hover { background: #222; transform: translateY(-4px); }
.discipline-icon { font-size: 2rem; margin-bottom: 1rem; }
.discipline-card h3 {
  font-family: var(--font-display);
  font-size: 1.5rem;
  letter-spacing: 2px;
  margin-bottom: 0.5rem;
}
.discipline-card p { font-size: 0.85rem; color: #666; line-height: 1.6; }

/* ===== CTA STRIP ===== */
.cta-strip {
  background: #161616;
  padding: 60px 5%;
  text-align: center;
  border-top: 1px solid #1E1E1E;
  border-bottom: 1px solid #1E1E1E;
}
.cta-strip h2 {
  font-family: var(--font-display);
  font-size: clamp(1.8rem, 4vw, 3rem);
  letter-spacing: 3px;
  margin-bottom: 1rem;
}
.cta-strip p { color: rgba(255,255,255,0.45); margin-bottom: 2rem; font-size: 0.95rem; }

/* ===== TIMETABLE ===== */
.timetable-wrapper { overflow-x: auto; }
table { width: 100%; border-collapse: collapse; font-size: 0.85rem; min-width: 700px; }
thead tr { background: #1A1A1A; border-bottom: 1px solid #2A2A2A; }
th {
  padding: 14px 16px;
  text-align: left;
  font-size: 0.65rem;
  letter-spacing: 2px;
  text-transform: uppercase;
  font-weight: 700;
  color: #888;
}
td { padding: 13px 16px; border-bottom: 1px solid rgba(255,255,255,0.04); color: #999; }
tr:nth-child(even) td { background: rgba(255,255,255,0.01); }
tr:hover td { background: rgba(255,255,255,0.03); color: var(--white); }
.badge {
  display: inline-block;
  padding: 3px 10px;
  font-size: 0.6rem;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.badge-beginner, .badge-intermediate, .badge-advanced, .badge-all {
  background: rgba(255,255,255,0.05);
  color: #777;
}

/* ===== MEMBERSHIP ===== */
.membership-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
  align-items: stretch;
}
.mem-card {
  background: var(--dark-grey);
  padding: 2.5rem 2rem;
  border: 1px solid rgba(255,255,255,0.06);
  display: flex;
  flex-direction: column;
  position: relative;
  transition: border-color var(--transition), transform var(--transition);
}
.mem-card:hover { border-color: rgba(255,255,255,0.14); transform: translateY(-4px); }
.mem-card.featured { background: #222; border-color: rgba(255,255,255,0.15); }
.featured-badge {
  position: absolute;
  top: -12px;
  left: 50%;
  transform: translateX(-50%);
  background: #2A2A2A;
  color: #888;
  font-size: 0.6rem;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  padding: 4px 14px;
  white-space: nowrap;
}
.mem-tier {
  font-family: var(--font-display);
  font-size: 1.6rem;
  letter-spacing: 3px;
  margin-bottom: 0.3rem;
  color: var(--white);
}
.mem-price {
  margin: 1.5rem 0;
  border-top: 1px solid rgba(255,255,255,0.07);
  border-bottom: 1px solid rgba(255,255,255,0.07);
  padding: 1.2rem 0;
}
.mem-price-num {
  font-family: var(--font-display);
  font-size: 3rem;
  color: var(--white);
  line-height: 1;
}
.mem-price-num sup { font-size: 1.4rem; vertical-align: super; }
.mem-price-period { font-size: 0.75rem; color: #555; margin-top: 4px; }
.mem-features { flex: 1; }
.mem-features li {
  font-size: 0.85rem;
  color: #777;
  padding: 6px 0;
  border-bottom: 1px solid rgba(255,255,255,0.04);
  display: flex;
  align-items: center;
  gap: 8px;
}
.mem-features li::before {
  content: '';
  width: 4px; height: 4px;
  background: #444;
  display: inline-block;
  flex-shrink: 0;
}
.mem-btn {
  display: block;
  text-align: center;
  margin-top: 1.8rem;
  padding: 12px;
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  cursor: pointer;
  transition: all var(--transition);
  border: 1px solid rgba(255,255,255,0.18);
  color: var(--white);
  background: transparent;
  font-family: var(--font-body);
}
.mem-btn:hover { border-color: rgba(255,255,255,0.5); background: rgba(255,255,255,0.04); }

/* ===== INSTRUCTORS ===== */
.instructors-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
}
.instructor-card {
  background: var(--dark-grey);
  overflow: hidden;
  border-bottom: 1px solid transparent;
  transition: border-color var(--transition), transform var(--transition);
}
.instructor-card:hover { border-bottom-color: #333; transform: translateY(-4px); }
.instructor-photo {
  height: 220px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 4rem;
  background: #181818;
  position: relative;
  overflow: hidden;
}
.instructor-info { padding: 1.8rem; }
.instructor-name {
  font-family: var(--font-display);
  font-size: 1.4rem;
  letter-spacing: 2px;
  margin-bottom: 0.2rem;
}
.instructor-title { font-size: 0.65rem; letter-spacing: 2px; text-transform: uppercase; color: #666; margin-bottom: 0.8rem; }
.instructor-bio { font-size: 0.85rem; color: #666; line-height: 1.6; margin-bottom: 1rem; }
.instructor-belts { display: flex; gap: 8px; }
.belt { display: inline-block; width: 32px; height: 8px; }

/* ===== PAGE HERO ===== */
.page-hero {
  background: var(--charcoal);
  padding: 60px 5% 50px;
  border-bottom: 1px solid #1E1E1E;
  position: relative;
  overflow: hidden;
}
.page-hero::before {
  content: '';
  position: absolute;
  right: -5%;
  top: -20%;
  width: 300px;
  height: 300px;
  background: radial-gradient(circle, rgba(255,255,255,0.02) 0%, transparent 70%);
}
.page-hero-label {
  font-size: 0.65rem;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #666;
  display: block;
  margin-bottom: 0.6rem;
}
.page-hero h1 {
  font-family: var(--font-display);
  font-size: clamp(2.5rem, 6vw, 4.5rem);
  letter-spacing: 3px;
  line-height: 1;
}
.page-hero p { color: #666; font-size: 0.95rem; margin-top: 0.8rem; max-width: 600px; }
.breadcrumb { font-size: 0.7rem; color: #444; letter-spacing: 1px; margin-bottom: 1rem; }
.breadcrumb span { color: #777; }

/* ===== ABOUT ===== */
.about-intro { display: grid; grid-template-columns: 1.2fr 1fr; gap: 5rem; align-items: center; }
.about-text h2 {
  font-family: var(--font-display);
  font-size: clamp(2rem, 4vw, 3rem);
  letter-spacing: 2px;
  margin-bottom: 1.5rem;
  line-height: 1.1;
}
.about-text p { color: #777; margin-bottom: 1rem; font-size: 0.95rem; }
.about-visual {
  background: var(--dark-grey);
  aspect-ratio: 4/5;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 8rem;
  border-left: 1px solid #2A2A2A;
  position: relative;
  overflow: hidden;
}
.about-visual::after {
  content: 'SINCE 2009';
  position: absolute;
  bottom: 20px;
  right: 20px;
  font-family: var(--font-display);
  font-size: 1rem;
  letter-spacing: 3px;
  color: #333;
}
.values-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1.5rem; }
.value-card { background: var(--dark-grey); padding: 2rem; border-left: 1px solid #2A2A2A; }
.value-num {
  font-family: var(--font-display);
  font-size: 3rem;
  color: rgba(255,255,255,0.05);
  line-height: 1;
  margin-bottom: 0.5rem;
}
.value-card h3 { font-size: 0.75rem; letter-spacing: 2px; text-transform: uppercase; margin-bottom: 0.5rem; }
.value-card p { font-size: 0.8rem; color: #555; }

/* ===== CONTACT ===== */
.contact-layout { display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; align-items: start; }
.contact-info-block { display: flex; flex-direction: column; gap: 2rem; }
.contact-detail { display: flex; gap: 1.2rem; align-items: flex-start; }
.contact-icon {
  width: 42px; height: 42px;
  background: #1C1C1C;
  border: 1px solid #2A2A2A;
  display: flex; align-items: center; justify-content: center;
  font-size: 1rem;
  flex-shrink: 0;
}
.contact-text h4 { font-size: 0.65rem; letter-spacing: 2px; text-transform: uppercase; color: #666; margin-bottom: 4px; }
.contact-text p { font-size: 0.9rem; color: #888; }
.contact-form { display: flex; flex-direction: column; gap: 1.2rem; }
.form-group { display: flex; flex-direction: column; gap: 6px; }
.form-group label { font-size: 0.65rem; letter-spacing: 2px; text-transform: uppercase; color: #666; }
.form-group input,
.form-group select,
.form-group textarea {
  background: var(--dark-grey);
  border: 1px solid rgba(255,255,255,0.08);
  color: var(--white);
  padding: 12px 14px;
  font-family: var(--font-body);
  font-size: 0.9rem;
  outline: none;
  transition: border-color var(--transition);
  width: 100%;
}
.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus { border-color: #444; }
.form-group select option { background: var(--dark-grey); }
.form-group textarea { resize: vertical; min-height: 120px; }
.form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
.form-error { display: none; font-size: 0.75rem; color: #888; margin-top: 2px; }
.form-success {
  display: none;
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(255,255,255,0.1);
  padding: 1rem;
  color: #aaa;
  font-size: 0.9rem;
  text-align: center;
}

/* ===== FOOTER ===== */
footer {
  background: #080808;
  padding: 60px 5% 30px;
  border-top: 1px solid #1E1E1E;
}
.footer-grid {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr 1fr;
  gap: 3rem;
  margin-bottom: 3rem;
}
.footer-logo {
  font-family: var(--font-display);
  font-size: 2rem;
  letter-spacing: 3px;
  margin-bottom: 1rem;
}
.footer-logo span { color: rgba(255,255,255,0.3); }
.footer-brand p { font-size: 0.85rem; color: #444; line-height: 1.7; }
.footer-social { display: flex; gap: 10px; margin-top: 1.2rem; }
.social-btn {
  width: 36px; height: 36px;
  border: 1px solid rgba(255,255,255,0.1);
  display: flex; align-items: center; justify-content: center;
  font-size: 0.75rem;
  color: #555;
  cursor: pointer;
  transition: all var(--transition);
  text-decoration: none;
}
.social-btn:hover { border-color: #555; color: #ccc; }
.footer-col h4 { font-size: 0.65rem; letter-spacing: 3px; text-transform: uppercase; color: var(--white); margin-bottom: 1.2rem; }
.footer-col ul li { margin-bottom: 0.6rem; }
.footer-col ul li a { font-size: 0.85rem; color: #444; transition: color var(--transition); cursor: pointer; }
.footer-col ul li a:hover { color: #999; }
.footer-bottom {
  border-top: 1px solid rgba(255,255,255,0.05);
  padding-top: 1.5rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 0.75rem;
  color: #333;
}

/* ===== UTILITY ===== */
.divider { width: 40px; height: 1px; background: #2A2A2A; margin: 1rem 0 2rem; }
.red { color: rgba(255,255,255,0.4); }
.mt-2 { margin-top: 2rem; }
.highlight-box {
  background: rgba(255,255,255,0.02);
  border-left: 1px solid #2A2A2A;
  padding: 1.2rem 1.5rem;
  margin: 1.5rem 0;
  font-size: 0.9rem;
  color: #777;
}

/* ===== RESPONSIVE ===== */
@media (max-width: 900px) {
  .nav-links { display: none; }
  .hamburger { display: flex; }
  .nav-links.open {
    display: flex;
    flex-direction: column;
    position: fixed;
    top: var(--nav-height);
    left: 0; right: 0;
    background: rgba(12,12,12,0.98);
    padding: 2rem;
    gap: 1.5rem;
    border-bottom: 1px solid #1E1E1E;
  }
  .contact-layout { grid-template-columns: 1fr; }
  .about-intro { grid-template-columns: 1fr; }
  .footer-grid { grid-template-columns: 1fr 1fr; }
  .hero-stats { gap: 2rem; }
  .hero-diagonal { display: none; }
  .form-row { grid-template-columns: 1fr; }
}
@media (max-width: 600px) {
  section { padding: 60px 5%; }
  .footer-grid { grid-template-columns: 1fr; }
  .hero-stats { flex-wrap: wrap; }
  .membership-grid { grid-template-columns: 1fr; }
}
