<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>日越共生Lab — ベトナム大卒、JICA日本語教師。7年間で見つけた、日越共生のヒント。</title>
<meta name="description" content="日本に住むベトナム人と日本人が共に豊かに生きる社会へ。ベトナム専門家・小中悠一郎によるベトナム人雇用サポート、日本語指導、ビジネスコンサル、講演・情報発信。">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Shippori+Mincho:wght@500;600;700;800&family=Zen+Kaku+Gothic+New:wght@400;500;700&display=swap" rel="stylesheet">
<style>
*, *::before, *::after { box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {
  margin: 0;
  background: #fbf9f8;
  color: #000d33;
  font-family: "Zen Kaku Gothic New", sans-serif;
  -webkit-font-smoothing: antialiased;
  line-height: 1;
}

::selection { background: #bb0014; color: #fff; }

a { color: inherit; text-decoration: none; }

input, textarea, select, button { font-family: inherit; }

/* Fade-in animation */
@keyframes jvFade {
  from { opacity: 0; transform: translateY(14px); }
  to   { opacity: 1; transform: none; }
}

.anim-hero-left  { animation: jvFade 0.7s ease both; }
.anim-hero-right { animation: jvFade 0.9s ease both; }

/* ─── NAV ─────────────────────────────────────────── */
#site-nav {
  position: sticky;
  top: 0;
  z-index: 50;
  background: rgba(251,249,248,0.82);
  backdrop-filter: blur(14px);
  -webkit-backdrop-filter: blur(14px);
  border-bottom: 1px solid rgba(0,13,51,0.1);
}

.nav-inner {
  max-width: 1180px;
  margin: 0 auto;
  padding: 0 32px;
  height: 72px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.nav-logo {
  display: flex;
  align-items: center;
  gap: 9px;
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 21px;
  letter-spacing: 0.02em;
}

.nav-logo-dot {
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: #bb0014;
  display: inline-block;
  flex-shrink: 0;
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 34px;
  font-size: 14px;
  font-weight: 500;
}

.nav-links a:not(.nav-cta) { opacity: 0.78; transition: opacity 0.2s; }
.nav-links a:not(.nav-cta):hover { opacity: 1; }

.nav-cta {
  padding: 9px 20px;
  background: #000d33;
  color: #fbf9f8;
  border-radius: 2px;
  font-weight: 700;
  transition: background 0.2s;
}
.nav-cta:hover { background: #bb0014; }

/* ─── SECTIONS ─────────────────────────────────────── */
section { scroll-margin-top: 72px; }

.container {
  max-width: 1180px;
  margin: 0 auto;
  padding: 0 32px;
}

/* ─── HERO ─────────────────────────────────────────── */
#top {
  max-width: 1180px;
  margin: 0 auto;
  padding: 72px 32px 90px;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.08fr 0.92fr;
  gap: 56px;
  align-items: center;
}

.hero-tagline {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 30px;
}

.hero-tagline-line {
  height: 1px;
  width: 34px;
  background: #bb0014;
  flex-shrink: 0;
}

.hero-tagline-text {
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 0.24em;
  color: #bb0014;
}

.hero-h1 {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 52px;
  line-height: 1.34;
  letter-spacing: 0.01em;
  margin: 0 0 28px;
  text-wrap: balance;
}

.hero-lead {
  font-size: 16px;
  line-height: 2;
  color: rgba(0,13,51,0.66);
  max-width: 480px;
  margin: 0 0 38px;
}

.hero-ctas {
  display: flex;
  gap: 14px;
  margin-bottom: 40px;
  flex-wrap: wrap;
}

.btn-primary {
  padding: 15px 30px;
  background: #000d33;
  color: #fbf9f8;
  border-radius: 2px;
  font-weight: 700;
  font-size: 15px;
  display: inline-block;
  transition: background 0.2s;
}
.btn-primary:hover { background: #bb0014; }

.btn-secondary {
  padding: 15px 30px;
  border: 1px solid rgba(0,13,51,0.28);
  border-radius: 2px;
  font-weight: 700;
  font-size: 15px;
  display: inline-block;
  transition: border-color 0.2s, background 0.2s;
}
.btn-secondary:hover { border-color: rgba(0,13,51,0.6); background: rgba(0,13,51,0.04); }

.hero-stats {
  display: flex;
  gap: 40px;
  padding-top: 30px;
  border-top: 1px solid rgba(0,13,51,0.1);
  flex-wrap: wrap;
}

.hero-stat-value {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 30px;
  line-height: 1;
}

.hero-stat-value sub {
  font-size: 16px;
  vertical-align: baseline;
}

.hero-stat-label {
  font-size: 12px;
  color: rgba(0,13,51,0.55);
  margin-top: 7px;
  letter-spacing: 0.04em;
}

/* Hero portrait */
.hero-portrait-wrap {
  position: relative;
}

.hero-deco-circle-red {
  position: absolute;
  right: -14px;
  top: -22px;
  width: 150px;
  height: 150px;
  border-radius: 50%;
  background: #bb0014;
  z-index: 0;
  pointer-events: none;
}

.hero-deco-circle-outline {
  position: absolute;
  left: -20px;
  bottom: 38px;
  width: 74px;
  height: 74px;
  border: 1px solid rgba(0,13,51,0.25);
  border-radius: 50%;
  z-index: 0;
  pointer-events: none;
}

.hero-portrait {
  position: relative;
  z-index: 1;
  width: 100%;
  aspect-ratio: 4/5;
  display: block;
  border-radius: 3px;
  overflow: hidden;
  background: rgba(0,13,51,0.08);
}

.image-placeholder {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 10px;
  cursor: pointer;
  transition: background 0.2s;
}

.image-placeholder:hover { background: rgba(0,13,51,0.12); }

.image-placeholder svg { opacity: 0.3; }

.image-placeholder span {
  font-size: 12px;
  color: rgba(0,13,51,0.4);
  letter-spacing: 0.05em;
  text-align: center;
  padding: 0 20px;
}

.image-placeholder img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.hero-nameplate {
  position: absolute;
  left: -20px;
  bottom: -20px;
  z-index: 2;
  background: #000d33;
  color: #fbf9f8;
  padding: 16px 22px;
  border-radius: 2px;
  max-width: 230px;
}

.hero-nameplate-name {
  font-family: 'Shippori Mincho', serif;
  font-weight: 600;
  font-size: 17px;
}

.hero-nameplate-title {
  font-size: 12px;
  opacity: 0.7;
  margin-top: 4px;
  line-height: 1.6;
}

/* ─── ABOUT / PROFILE ──────────────────────────────── */
#about {
  background: #000d33;
  color: #fbf9f8;
}

.about-inner {
  max-width: 1180px;
  margin: 0 auto;
  padding: 96px 32px;
}

.section-label {
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 0.24em;
  color: #bb0014;
  margin-bottom: 16px;
}

.section-label-light { color: #ff5161; }

.about-h2 {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 38px;
  line-height: 1.4;
  margin: 0 0 12px;
}

.about-lead {
  font-size: 15px;
  line-height: 2;
  color: rgba(251,249,248,0.62);
  max-width: 560px;
  margin: 0 0 64px;
}

.about-grid {
  display: grid;
  grid-template-columns: 1.4fr 1fr;
  gap: 64px;
}

/* Timeline */
.timeline {
  position: relative;
  padding-left: 30px;
}

.timeline-line {
  position: absolute;
  left: 5px;
  top: 6px;
  bottom: 6px;
  width: 1px;
  background: rgba(251,249,248,0.18);
}

.timeline-item {
  position: relative;
  margin-bottom: 34px;
}

.timeline-item:last-child { margin-bottom: 0; }

.timeline-dot {
  position: absolute;
  left: -30px;
  top: 5px;
  width: 11px;
  height: 11px;
  border-radius: 50%;
  background: #fbf9f8;
}

.timeline-dot-highlight {
  left: -32px;
  top: 3px;
  width: 15px;
  height: 15px;
  background: #bb0014;
  border: 2px solid #000d33;
  box-shadow: 0 0 0 1px #bb0014;
}

.timeline-label {
  font-size: 12px;
  letter-spacing: 0.1em;
  color: rgba(251,249,248,0.5);
  font-weight: 700;
  margin-bottom: 5px;
}

.timeline-label-active { color: #ff5161; }

.timeline-title {
  font-family: 'Shippori Mincho', serif;
  font-size: 18px;
  font-weight: 600;
}

.timeline-desc {
  font-size: 13px;
  color: rgba(251,249,248,0.55);
  margin-top: 6px;
  line-height: 1.7;
}

/* Skill cards */
.skills-cards {
  display: flex;
  flex-direction: column;
  gap: 18px;
}

.skill-card {
  background: rgba(251,249,248,0.05);
  border: 1px solid rgba(251,249,248,0.14);
  border-radius: 3px;
  padding: 28px;
}

.skill-card-label {
  font-size: 12px;
  letter-spacing: 0.18em;
  color: #ff5161;
  font-weight: 700;
  margin-bottom: 18px;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 9px;
}

.skill-tag {
  border: 1px solid rgba(251,249,248,0.22);
  border-radius: 2px;
  padding: 7px 13px;
  font-size: 13px;
}

.qual-list {
  margin: 0;
  padding: 0;
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 13px;
  font-size: 14px;
  line-height: 1.6;
}

.qual-list li {
  display: flex;
  gap: 11px;
}

.qual-list li::before {
  content: '／';
  color: #ff5161;
  flex-shrink: 0;
}

/* ─── SERVICES ─────────────────────────────────────── */
#services {
  max-width: 1180px;
  margin: 0 auto;
  padding: 96px 32px;
}

.services-header { margin-bottom: 50px; }

.services-h2 {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 38px;
  line-height: 1.4;
  margin: 0;
}

.services-lead {
  font-size: 15px;
  line-height: 2;
  color: rgba(0,13,51,0.6);
  max-width: 540px;
  margin: 16px 0 0;
}

.services-bento {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 18px;
}

.service-card {
  background: #fff;
  border: 1px solid rgba(0,13,51,0.1);
  border-radius: 3px;
  padding: 38px;
  min-height: 240px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  transition: border-color 0.25s ease, box-shadow 0.25s ease;
}

.service-card:hover {
  border-color: rgba(187,0,20,0.5);
  box-shadow: 0 18px 40px -22px rgba(0,13,51,0.3);
}

.service-card-dark {
  background: #000d33;
  color: #fbf9f8;
  border: none;
}

.service-card-dark:hover {
  border-color: transparent;
  box-shadow: 0 18px 40px -22px rgba(0,13,51,0.5);
}

.col-7 { grid-column: span 7; }
.col-5 { grid-column: span 5; }

.service-card-top {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
}

.service-num {
  font-family: 'Shippori Mincho', serif;
  font-size: 15px;
  color: #bb0014;
  font-weight: 700;
}

.service-num-light { color: #ff5161; }

.service-cat {
  font-size: 11px;
  letter-spacing: 0.18em;
  color: rgba(0,13,51,0.4);
  font-weight: 700;
}

.service-cat-dark { color: rgba(251,249,248,0.45); }

.service-h3 {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 26px;
  margin: 0 0 14px;
}

.service-desc {
  font-size: 14px;
  line-height: 1.9;
  color: rgba(0,13,51,0.62);
  margin: 0 0 16px;
  max-width: 440px;
}

.service-desc-dark { color: rgba(251,249,248,0.66); }

.service-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.service-tag {
  background: #fbf9f8;
  border: 1px solid rgba(0,13,51,0.12);
  border-radius: 2px;
  padding: 5px 11px;
  font-size: 12px;
}

.service-tag-dark {
  background: transparent;
  border: 1px solid rgba(251,249,248,0.22);
  color: #fbf9f8;
}

/* ─── WORKS / MEDIA ────────────────────────────────── */
#works { background: #f3efec; }

.works-inner {
  max-width: 1180px;
  margin: 0 auto;
  padding: 96px 32px;
}

.works-header { margin-bottom: 50px; }

.works-h2 {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 38px;
  line-height: 1.4;
  margin: 0;
}

.works-bento {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 18px;
}

/* Companies card */
.companies-card {
  grid-column: span 7;
  background: #fff;
  border: 1px solid rgba(0,13,51,0.1);
  border-radius: 3px;
  padding: 36px;
}

.card-section-label {
  font-size: 12px;
  letter-spacing: 0.18em;
  color: #bb0014;
  font-weight: 700;
  margin-bottom: 24px;
}

.company-list { display: flex; flex-direction: column; }

.company-item {
  display: flex;
  gap: 18px;
  padding: 18px 0;
  border-bottom: 1px solid rgba(0,13,51,0.1);
}

.company-item:last-child { border-bottom: none; }

.company-num {
  font-family: 'Shippori Mincho', serif;
  color: #bb0014;
  font-weight: 700;
  font-size: 15px;
  min-width: 24px;
  flex-shrink: 0;
}

.company-name {
  font-family: 'Shippori Mincho', serif;
  font-weight: 600;
  font-size: 18px;
}

.company-role {
  font-size: 13px;
  color: rgba(0,13,51,0.6);
  margin-top: 4px;
}

/* Kindle card */
.kindle-card {
  grid-column: span 5;
  background: #000d33;
  color: #fbf9f8;
  border-radius: 3px;
  padding: 36px;
  display: flex;
  flex-direction: column;
}

.card-section-label-light {
  font-size: 12px;
  letter-spacing: 0.18em;
  color: #ff5161;
  font-weight: 700;
  margin-bottom: 24px;
}

.kindle-content {
  display: flex;
  gap: 20px;
  align-items: flex-start;
}

.book-cover {
  width: 118px;
  height: 170px;
  flex-shrink: 0;
  border-radius: 2px;
  overflow: hidden;
  background: rgba(251,249,248,0.08);
  box-shadow: 0 14px 30px -10px rgba(0,0,0,0.6);
}

.book-cover .image-placeholder { background: rgba(251,249,248,0.05); }
.book-cover .image-placeholder:hover { background: rgba(251,249,248,0.1); }
.book-cover .image-placeholder svg { opacity: 0.2; }
.book-cover .image-placeholder span { color: rgba(251,249,248,0.35); }

.book-title {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 19px;
  line-height: 1.5;
}

.book-desc {
  font-size: 12px;
  color: rgba(251,249,248,0.6);
  margin-top: 14px;
  line-height: 1.7;
}

/* Media card */
.media-card {
  grid-column: span 12;
  background: #fff;
  border: 1px solid rgba(0,13,51,0.1);
  border-radius: 3px;
  padding: 36px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 36px;
  align-items: center;
}

.media-desc {
  font-size: 14px;
  line-height: 1.9;
  color: rgba(0,13,51,0.62);
  margin: 0 0 22px;
  max-width: 420px;
}

.media-papers {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

.paper-badge {
  border: 1px solid rgba(0,13,51,0.14);
  border-radius: 2px;
  padding: 13px 20px;
}

.paper-name {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 17px;
}

.paper-label {
  font-size: 11px;
  color: rgba(0,13,51,0.5);
  margin-top: 3px;
  letter-spacing: 0.05em;
}

.media-image {
  width: 100%;
  aspect-ratio: 16/9;
  border-radius: 3px;
  overflow: hidden;
  background: rgba(0,13,51,0.06);
}

/* ─── CONTACT ──────────────────────────────────────── */
#contact {
  max-width: 1180px;
  margin: 0 auto;
  padding: 96px 32px;
}

.contact-grid {
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  gap: 64px;
  align-items: start;
}

.contact-h2 {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 38px;
  line-height: 1.4;
  margin: 0 0 20px;
}

.contact-lead {
  font-size: 15px;
  line-height: 2;
  color: rgba(0,13,51,0.62);
  margin: 0 0 34px;
}

.contact-meta {
  display: flex;
  flex-direction: column;
  gap: 18px;
  border-top: 1px solid rgba(0,13,51,0.12);
  padding-top: 30px;
}

.contact-meta-label {
  font-size: 11px;
  letter-spacing: 0.16em;
  color: rgba(0,13,51,0.5);
  font-weight: 700;
  margin-bottom: 5px;
}

.contact-meta-value {
  font-size: 14px;
  line-height: 1.8;
}

/* Form */
.form-card {
  background: #fff;
  border: 1px solid rgba(0,13,51,0.1);
  border-radius: 3px;
  padding: 40px;
}

.form-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
}

.form-field {
  display: flex;
  flex-direction: column;
  gap: 8px;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 0.08em;
  color: rgba(0,13,51,0.7);
}

.form-field .required { color: #bb0014; }

.form-input {
  border: none;
  border-bottom: 1px solid rgba(0,13,51,0.25);
  background: transparent;
  padding: 9px 2px;
  font-size: 15px;
  color: #000d33;
  outline: none;
  transition: border-bottom-color 0.2s;
  width: 100%;
}

.form-input:focus { border-bottom-color: #bb0014; }

.form-select {
  border: none;
  border-bottom: 1px solid rgba(0,13,51,0.25);
  background: transparent;
  padding: 9px 2px;
  font-size: 15px;
  color: #000d33;
  outline: none;
  transition: border-bottom-color 0.2s;
  width: 100%;
  cursor: pointer;
  appearance: none;
  -webkit-appearance: none;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='8' viewBox='0 0 12 8'%3E%3Cpath d='M1 1l5 5 5-5' stroke='rgba(0,13,51,0.4)' stroke-width='1.5' fill='none' stroke-linecap='round'/%3E%3C/svg%3E");
  background-repeat: no-repeat;
  background-position: right 4px center;
}

.form-select:focus { border-bottom-color: #bb0014; }

.form-textarea {
  border: 1px solid rgba(0,13,51,0.18);
  border-radius: 3px;
  background: #fbf9f8;
  padding: 12px;
  font-size: 15px;
  color: #000d33;
  outline: none;
  resize: vertical;
  transition: border-color 0.2s;
  width: 100%;
}

.form-textarea:focus { border-color: #bb0014; }

.contact-form {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.btn-submit {
  margin-top: 8px;
  padding: 16px;
  background: #000d33;
  color: #fbf9f8;
  border: none;
  border-radius: 2px;
  font-weight: 700;
  font-size: 15px;
  cursor: pointer;
  transition: background 0.2s;
  width: 100%;
}

.btn-submit:hover { background: #bb0014; }

/* Success state */
.form-success {
  display: none;
  text-align: center;
  padding: 50px 20px;
}

.form-success.visible { display: block; }
.contact-form.hidden { display: none; }

.success-icon {
  width: 54px;
  height: 54px;
  border-radius: 50%;
  background: #bb0014;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 22px;
  font-size: 26px;
}

.success-title {
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 24px;
  margin: 0 0 12px;
}

.success-desc {
  font-size: 14px;
  line-height: 1.9;
  color: rgba(0,13,51,0.6);
  margin: 0;
}

/* ─── FOOTER ────────────────────────────────────────── */
#site-footer {
  background: #000d33;
  color: #fbf9f8;
}

.footer-main {
  max-width: 1180px;
  margin: 0 auto;
  padding: 56px 32px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 24px;
}

.footer-logo {
  display: flex;
  align-items: center;
  gap: 9px;
  font-family: 'Shippori Mincho', serif;
  font-weight: 700;
  font-size: 21px;
}

.footer-tagline {
  font-size: 12px;
  color: rgba(251,249,248,0.55);
  margin-top: 10px;
  letter-spacing: 0.04em;
}

.footer-links {
  display: flex;
  gap: 28px;
  font-size: 13px;
}

.footer-links a {
  opacity: 0.75;
  transition: opacity 0.2s;
}
.footer-links a:hover { opacity: 1; }

.footer-bottom {
  border-top: 1px solid rgba(251,249,248,0.12);
}

.footer-copy {
  max-width: 1180px;
  margin: 0 auto;
  padding: 18px 32px;
  font-size: 12px;
  color: rgba(251,249,248,0.45);
}

/* ─── RESPONSIVE ────────────────────────────────────── */
@media (max-width: 900px) {
  .hero-grid {
    grid-template-columns: 1fr;
    gap: 64px;
  }

  .hero-portrait-wrap {
    max-width: 420px;
    margin: 0 auto;
  }

  .about-grid {
    grid-template-columns: 1fr;
    gap: 48px;
  }

  .services-bento,
  .works-bento {
    grid-template-columns: 1fr;
  }

  .col-7, .col-5,
  .companies-card, .kindle-card, .media-card {
    grid-column: span 1;
  }

  .media-card {
    grid-template-columns: 1fr;
  }

  .contact-grid {
    grid-template-columns: 1fr;
    gap: 40px;
  }

  .form-row {
    grid-template-columns: 1fr;
  }

  .hero-h1 { font-size: 40px; }
  .about-h2, .services-h2, .works-h2, .contact-h2 { font-size: 30px; }
}

@media (max-width: 640px) {
  .nav-inner { padding: 0 20px; }
  .nav-links { gap: 18px; }
  .nav-links a:not(.nav-cta) { display: none; }

  #top { padding: 48px 20px 72px; }
  .about-inner, .works-inner { padding: 72px 20px; }
  #services, #contact { padding: 72px 20px; }

  .hero-h1 { font-size: 34px; }
  .hero-stats { gap: 24px; }
  .footer-main { padding: 40px 20px; }
  .footer-copy { padding: 16px 20px; }
}

/* ─── IMAGE SLOT DROP ZONE ───────────────────────────── */
.image-slot { position: relative; width: 100%; height: 100%; }

.image-slot.drag-over .image-placeholder {
  background: rgba(187,0,20,0.06);
  border: 2px dashed #bb0014;
}
</style>
</head>
<body>

<!-- NAV -->
<header id="site-nav">
  <nav class="nav-inner">
    <a href="#top" class="nav-logo">
      <span class="nav-logo-dot"></span>
      日越共生<span style="color:#bb0014;">Lab</span>
    </a>
    <div class="nav-links">
      <a href="#about">プロフィール</a>
      <a href="#services">サービス</a>
      <a href="#works">実績・メディア</a>
      <a href="#contact" class="nav-cta">お問い合わせ</a>
    </div>
  </nav>
</header>

<!-- HERO -->
<section id="top">
  <div class="hero-grid">

    <!-- Left: copy -->
    <div class="anim-hero-left">
      <div class="hero-tagline">
        <span class="hero-tagline-line"></span>
        <span class="hero-tagline-text">JAPAN &times; VIETNAM &mdash; 共生</span>
      </div>
      <h1 class="hero-h1">
        ベトナム大卒、<br>JICA日本語教師。<br>
        <span style="color:#bb0014;">7年間</span>で見つけた、<br>日越共生のヒント。
      </h1>
      <p class="hero-lead">
        日本に住むベトナム人と日本人が、共に豊かに生きる社会へ。ベトナム専門家として、企業の採用から個人の学びまで、両国の架け橋となる確かな実践知をお届けします。
      </p>
      <div class="hero-ctas">
        <a href="#services" class="btn-primary">サービスを見る</a>
        <a href="#contact" class="btn-secondary">お問い合わせ</a>
      </div>
      <div class="hero-stats">
        <div>
          <div class="hero-stat-value">約7<sub>年</sub></div>
          <div class="hero-stat-label">ベトナム滞在（北部・南部）</div>
        </div>
        <div>
          <div class="hero-stat-value">JICA</div>
          <div class="hero-stat-label">海外協力隊 日本語教師</div>
        </div>
        <div>
          <div class="hero-stat-value">正規卒</div>
          <div class="hero-stat-label">国立大ベトナム学部</div>
        </div>
      </div>
    </div>

    <!-- Right: portrait -->
    <div class="hero-portrait-wrap anim-hero-right">
      <span class="hero-deco-circle-red"></span>
      <span class="hero-deco-circle-outline"></span>
      <div class="hero-portrait">
        <div class="image-slot" id="slot-portrait" data-label="ポートレート写真をドロップ">
          <div class="image-placeholder" onclick="document.getElementById('file-portrait').click()">
            <svg width="32" height="32" viewBox="0 0 32 32" fill="none">
              <rect x="2" y="6" width="28" height="20" rx="2" stroke="#000d33" stroke-width="1.5"/>
              <circle cx="16" cy="16" r="5" stroke="#000d33" stroke-width="1.5"/>
              <path d="M10 7l1.5-3h9L22 7" stroke="#000d33" stroke-width="1.5" stroke-linecap="round"/>
            </svg>
            <span>ポートレート写真をドロップ<br>またはクリックして選択</span>
          </div>
          <input type="file" id="file-portrait" accept="image/*" style="display:none" onchange="loadImage(this,'slot-portrait')">
        </div>
      </div>
      <div class="hero-nameplate">
        <div class="hero-nameplate-name">小中 悠一郎</div>
        <div class="hero-nameplate-title">日越共生Lab 主宰 / ベトナム専門家</div>
      </div>
    </div>

  </div>
</section>

<!-- ABOUT / PROFILE -->
<section id="about">
  <div class="about-inner">
    <div class="section-label section-label-light">01 &mdash; PROFILE</div>
    <h2 class="about-h2">慶應を中退し、<br>ベトナムの大学生になった。</h2>
    <p class="about-lead">広島に生まれ福岡で育つ。日本の常識を一度手放し、ベトナムの社会に身ひとつで飛び込んだ7年間。その歩みが、両国をつなぐ実践知の土台になっています。</p>

    <div class="about-grid">
      <!-- Timeline -->
      <div class="timeline">
        <span class="timeline-line"></span>

        <div class="timeline-item">
          <span class="timeline-dot"></span>
          <div class="timeline-label timeline-label-active">出身</div>
          <div class="timeline-title">広島生まれ・福岡育ち</div>
        </div>

        <div class="timeline-item">
          <span class="timeline-dot"></span>
          <div class="timeline-label">大学</div>
          <div class="timeline-title">慶應義塾大学 商学部 入学 → 退学</div>
          <div class="timeline-desc">人生の問いを追い、進路を大きく転換。</div>
        </div>

        <div class="timeline-item">
          <span class="timeline-dot timeline-dot-highlight"></span>
          <div class="timeline-label timeline-label-active">転機 / 正規卒業</div>
          <div class="timeline-title">ホーチミン市人文社会科学大学<br>ベトナム学部 正規卒業</div>
          <div class="timeline-desc">ベトナム語・歴史・社会を現地の学生と共に学び、学位を取得。</div>
        </div>

        <div class="timeline-item">
          <span class="timeline-dot"></span>
          <div class="timeline-label">資格</div>
          <div class="timeline-title">日本語教育能力検定試験 取得</div>
        </div>

        <div class="timeline-item">
          <span class="timeline-dot"></span>
          <div class="timeline-label">JICA海外協力隊</div>
          <div class="timeline-title">ハロン大学 日本語教師（北部）</div>
          <div class="timeline-desc">北部・南部の両方で生活し、地域による文化の違いを肌で理解。</div>
        </div>

        <div class="timeline-item">
          <span class="timeline-dot"></span>
          <div class="timeline-label">2027年4月</div>
          <div class="timeline-title">日本へ帰国予定</div>
        </div>
      </div>

      <!-- Skills -->
      <div class="skills-cards">
        <div class="skill-card">
          <div class="skill-card-label">SKILLS</div>
          <div class="skill-tags">
            <span class="skill-tag">ベトナム語</span>
            <span class="skill-tag">日本語教育</span>
            <span class="skill-tag">通訳・翻訳</span>
            <span class="skill-tag">ビジネスコンサル</span>
            <span class="skill-tag">異文化マネジメント</span>
          </div>
        </div>
        <div class="skill-card">
          <div class="skill-card-label">QUALIFICATION</div>
          <ul class="qual-list">
            <li>日本語教育能力検定試験 合格</li>
            <li>ベトナム国立大 ベトナム学部 卒業</li>
            <li>JICA海外協力隊 修了</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <div class="services-header">
    <div class="section-label">02 &mdash; SERVICES</div>
    <h2 class="services-h2">4つの専門サービス</h2>
    <p class="services-lead">企業の採用・定着から、個人の学び、ビジネス進出まで。現地での実体験に裏打ちされた支援を提供します。</p>
  </div>

  <div class="services-bento">
    <!-- 01 -->
    <div class="service-card col-7">
      <div class="service-card-top">
        <span class="service-num">01</span>
        <span class="service-cat">FOR COMPANIES</span>
      </div>
      <div>
        <h3 class="service-h3">ベトナム人雇用サポート</h3>
        <p class="service-desc">採用前の選考支援から特定技能の手続き、通訳、入社後の定着まで一気通貫で伴走。文化の壁を越えた職場づくりを支えます。</p>
        <div class="service-tags">
          <span class="service-tag">採用・選考</span>
          <span class="service-tag">特定技能サポート</span>
          <span class="service-tag">通訳・定着支援</span>
        </div>
      </div>
    </div>

    <!-- 02 -->
    <div class="service-card col-5">
      <div class="service-card-top">
        <span class="service-num">02</span>
        <span class="service-cat">EDUCATION</span>
      </div>
      <div>
        <h3 class="service-h3">日本語指導</h3>
        <p class="service-desc">検定対策からビジネス日本語まで。学習者の母語と文化を理解した教師による、続く学びを設計します。</p>
        <div class="service-tags">
          <span class="service-tag">検定対策</span>
          <span class="service-tag">ビジネス日本語</span>
        </div>
      </div>
    </div>

    <!-- 03 -->
    <div class="service-card col-5">
      <div class="service-card-top">
        <span class="service-num">03</span>
        <span class="service-cat">CONSULTING</span>
      </div>
      <div>
        <h3 class="service-h3">ベトナムビジネスコンサル</h3>
        <p class="service-desc">市場調査・進出支援・現地ネットワーク構築。北部・南部双方の商習慣を踏まえた実践的アドバイス。</p>
        <div class="service-tags">
          <span class="service-tag">進出支援</span>
          <span class="service-tag">市場調査</span>
        </div>
      </div>
    </div>

    <!-- 04 -->
    <div class="service-card service-card-dark col-7">
      <div class="service-card-top">
        <span class="service-num service-num-light">04</span>
        <span class="service-cat service-cat-dark">MEDIA</span>
      </div>
      <div>
        <h3 class="service-h3">講演・情報発信</h3>
        <p class="service-desc service-desc-dark">講演・執筆・メディア出演を通じて、日越共生のリアルを発信。ベトナム全国紙への掲載やKindle出版の実績があります。</p>
        <div class="service-tags">
          <span class="service-tag service-tag-dark">講演・登壇</span>
          <span class="service-tag service-tag-dark">執筆・出版</span>
          <span class="service-tag service-tag-dark">メディア出演</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- WORKS / MEDIA -->
<section id="works">
  <div class="works-inner">
    <div class="works-header">
      <div class="section-label">03 &mdash; WORKS &amp; MEDIA</div>
      <h2 class="works-h2">実績・メディア掲載</h2>
    </div>

    <div class="works-bento">
      <!-- Companies -->
      <div class="companies-card">
        <div class="card-section-label">企業・団体 実績</div>
        <div class="company-list">
          <div class="company-item">
            <span class="company-num">01</span>
            <div>
              <div class="company-name">丸一（特定技能登録支援機関）</div>
              <div class="company-role">通訳サポート</div>
            </div>
          </div>
          <div class="company-item">
            <span class="company-num">02</span>
            <div>
              <div class="company-name">新居浜自動車教習所</div>
              <div class="company-role">ベトナムビジネスアドバイザー</div>
            </div>
          </div>
          <div class="company-item">
            <span class="company-num">03</span>
            <div>
              <div class="company-name">日中国際交流協会</div>
              <div class="company-role">医療ツーリズムアドバイザー</div>
            </div>
          </div>
        </div>
      </div>

      <!-- Kindle -->
      <div class="kindle-card">
        <div class="card-section-label-light">出版物 / KINDLE</div>
        <div class="kindle-content">
          <div class="book-cover">
            <div class="image-slot" id="slot-book" data-label="書影">
              <div class="image-placeholder" onclick="document.getElementById('file-book').click()">
                <svg width="24" height="24" viewBox="0 0 32 32" fill="none">
                  <rect x="2" y="6" width="28" height="20" rx="2" stroke="#fbf9f8" stroke-width="1.5"/>
                  <circle cx="16" cy="16" r="5" stroke="#fbf9f8" stroke-width="1.5"/>
                </svg>
                <span>書影</span>
              </div>
              <input type="file" id="file-book" accept="image/*" style="display:none" onchange="loadImage(this,'slot-book')">
            </div>
          </div>
          <div>
            <div class="book-title">僕が慶應中退して<br>ベトナムの大学生に<br>なった理由</div>
            <div class="book-desc">Amazon Kindle にて出版。<br>常識を手放した先の物語。</div>
          </div>
        </div>
      </div>

      <!-- Media -->
      <div class="media-card">
        <div>
          <div class="card-section-label">ベトナム メディア掲載</div>
          <p class="media-desc">「ベトナムの大学を正規卒業した日本人」として、ベトナムの全国紙に取り上げられました。</p>
          <div class="media-papers">
            <div class="paper-badge">
              <div class="paper-name">Thanh Niên</div>
              <div class="paper-label">ベトナム全国紙</div>
            </div>
            <div class="paper-badge">
              <div class="paper-name">Sài Gòn Giải Phóng</div>
              <div class="paper-label">ベトナム全国紙</div>
            </div>
          </div>
        </div>
        <div class="media-image">
          <div class="image-slot" id="slot-media" data-label="掲載記事の画像をドロップ">
            <div class="image-placeholder" onclick="document.getElementById('file-media').click()">
              <svg width="32" height="32" viewBox="0 0 32 32" fill="none">
                <rect x="2" y="6" width="28" height="20" rx="2" stroke="#000d33" stroke-width="1.5"/>
                <circle cx="16" cy="16" r="5" stroke="#000d33" stroke-width="1.5"/>
                <path d="M10 7l1.5-3h9L22 7" stroke="#000d33" stroke-width="1.5" stroke-linecap="round"/>
              </svg>
              <span>掲載記事の画像をドロップ<br>またはクリックして選択</span>
            </div>
            <input type="file" id="file-media" accept="image/*" style="display:none" onchange="loadImage(this,'slot-media')">
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="contact-grid">
    <div>
      <div class="section-label">04 &mdash; CONTACT</div>
      <h2 class="contact-h2">お問い合わせ</h2>
      <p class="contact-lead">ベトナム人材の採用、日本語指導、ビジネス進出のご相談など、お気軽にご連絡ください。2〜3営業日以内にご返信します。</p>
      <div class="contact-meta">
        <div>
          <div class="contact-meta-label">対象</div>
          <div class="contact-meta-value">ベトナム人を雇いたい日本企業 / ベトナムに興味のある個人</div>
        </div>
        <div>
          <div class="contact-meta-label">運営</div>
          <div class="contact-meta-value">日越共生Lab ・ 小中 悠一郎</div>
        </div>
      </div>
    </div>

    <div class="form-card">
      <form class="contact-form" id="contact-form" onsubmit="handleSubmit(event)">
        <div class="form-row">
          <label class="form-field">
            お名前 <span class="required">*</span>
            <input class="form-input" required name="name" type="text" autocomplete="name">
          </label>
          <label class="form-field">
            会社名・団体名
            <input class="form-input" name="company" type="text" autocomplete="organization">
          </label>
        </div>
        <label class="form-field">
          メールアドレス <span class="required">*</span>
          <input class="form-input" required name="email" type="email" autocomplete="email">
        </label>
        <label class="form-field">
          ご相談内容
          <select class="form-select" name="topic">
            <option>ベトナム人雇用サポート</option>
            <option>日本語指導</option>
            <option>ベトナムビジネスコンサル</option>
            <option>講演・情報発信</option>
            <option>その他</option>
          </select>
        </label>
        <label class="form-field">
          メッセージ
          <textarea class="form-textarea" name="message" rows="4"></textarea>
        </label>
        <button type="submit" class="btn-submit">送信する</button>
      </form>

      <div class="form-success" id="form-success">
        <div class="success-icon">✓</div>
        <h3 class="success-title">送信しました</h3>
        <p class="success-desc">お問い合わせありがとうございます。<br>2〜3営業日以内にご返信いたします。</p>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer id="site-footer">
  <div class="footer-main">
    <div>
      <div class="footer-logo">
        <span class="nav-logo-dot"></span>
        日越共生<span style="color:#ff5161;">Lab</span>
      </div>
      <div class="footer-tagline">JAPAN &times; VIETNAM &mdash; 共生のヒントを、ここから。</div>
    </div>
    <div class="footer-links">
      <a href="#about">プロフィール</a>
      <a href="#services">サービス</a>
      <a href="#works">実績</a>
      <a href="#contact">お問い合わせ</a>
    </div>
  </div>
  <div class="footer-bottom">
    <div class="footer-copy">&copy; 2025 日越共生Lab / 小中悠一郎. All rights reserved.</div>
  </div>
</footer>

<script>
/* Form submission */
function handleSubmit(e) {
  e.preventDefault();
  document.getElementById('contact-form').classList.add('hidden');
  document.getElementById('form-success').classList.add('visible');
}

/* Image slots — drag & drop + file picker + localStorage persistence */
function loadImage(input, slotId) {
  const file = input.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = function(e) {
    setSlotImage(slotId, e.target.result);
    try { localStorage.setItem('img-' + slotId, e.target.result); } catch(err) {}
  };
  reader.readAsDataURL(file);
}

function setSlotImage(slotId, src) {
  const slot = document.getElementById('slot-' + slotId.replace('slot-', ''));
  if (!slot) return;
  const placeholder = slot.querySelector('.image-placeholder');
  if (!placeholder) return;

  /* Replace placeholder content with the image */
  placeholder.innerHTML = '<img src="' + src + '" alt="アップロード画像">';
  placeholder.style.padding = '0';
  placeholder.onclick = null;
}

/* Drag & drop on each slot container */
document.querySelectorAll('.image-slot').forEach(function(slot) {
  slot.addEventListener('dragover', function(e) {
    e.preventDefault();
    slot.classList.add('drag-over');
  });
  slot.addEventListener('dragleave', function() {
    slot.classList.remove('drag-over');
  });
  slot.addEventListener('drop', function(e) {
    e.preventDefault();
    slot.classList.remove('drag-over');
    const file = e.dataTransfer.files[0];
    if (!file || !file.type.startsWith('image/')) return;
    const reader = new FileReader();
    reader.onload = function(ev) {
      const id = slot.id;
      const placeholder = slot.querySelector('.image-placeholder');
      if (placeholder) {
        placeholder.innerHTML = '<img src="' + ev.target.result + '" alt="アップロード画像">';
        placeholder.style.padding = '0';
        placeholder.onclick = null;
      }
      try { localStorage.setItem('img-' + id, ev.target.result); } catch(err) {}
    };
    reader.readAsDataURL(file);
  });
});

/* Restore persisted images */
['slot-portrait', 'slot-book', 'slot-media'].forEach(function(id) {
  try {
    const saved = localStorage.getItem('img-' + id);
    if (saved) {
      const slot = document.getElementById(id);
      if (slot) {
        const placeholder = slot.querySelector('.image-placeholder');
        if (placeholder) {
          placeholder.innerHTML = '<img src="' + saved + '" alt="アップロード画像">';
          placeholder.style.padding = '0';
          placeholder.onclick = null;
        }
      }
    }
  } catch(err) {}
});
</script>

</body>
</html>
