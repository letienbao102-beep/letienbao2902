<!DOCTYPE html>
<html lang="vi" class="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, viewport-fit=cover, user-scalable=no" />
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
  <meta name="apple-mobile-web-app-title" content="Ôn Triết TNUT" />
  <meta name="mobile-web-app-capable" content="yes" />
  <meta name="format-detection" content="telephone=no" />
  <meta name="theme-color" content="#060b18" media="(prefers-color-scheme: dark)" />
  <meta name="theme-color" content="#f1f5f9" media="(prefers-color-scheme: light)" />
  <title>Ôn Triết Mác - Lênin (BAS 123 - TNUT) • Liquid Glass 3.3</title>
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Inter & JetBrains Mono -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&family=JetBrains+Mono:wght@500;700&display=swap" rel="stylesheet">
  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />
  <!-- PDF.js for 600-question PDF parsing -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js"></script>
  <!-- Native QR Code Generator Library (100% Self-Contained Canvas QR) -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcode-generator/1.4.4/qrcode.min.js"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            mono: ['JetBrains Mono', 'monospace']
          }
        }
      }
    }
  </script>
  <style>
    :root {
      /* Liquid Glass 3.3 – Premium + quality tiers */
      --glass-alpha: 0.16;
      --glass-blur: 36px;
      --glass-saturate: 185%;
      --glass-bg: rgba(255, 255, 255, var(--glass-alpha));
      --glass-border: rgba(255, 255, 255, 0.58);
      --glass-highlight: inset 0 1px 1px rgba(255, 255, 255, 0.92), inset 0 -1px 1px rgba(255, 255, 255, 0.18);
      --glass-shadow: 0 22px 44px -14px rgba(15, 23, 42, 0.10), 0 6px 16px -4px rgba(15, 23, 42, 0.05), 0 0 0 1px rgba(255,255,255,0.08);
      --opt-bg: rgba(255, 255, 255, 0.20);
      --opt-hover: rgba(255, 255, 255, 0.46);
      --spring: cubic-bezier(0.34, 1.45, 0.64, 1);
      --anim-scale: 1;
    }
    html.dark {
      --glass-alpha: 0.13;
      --glass-bg: rgba(15, 23, 42, var(--glass-alpha));
      --glass-border: rgba(255, 255, 255, 0.13);
      --glass-highlight: inset 0 1px 1px rgba(255, 255, 255, 0.20), inset 0 -1px 1px rgba(255, 255, 255, 0.05);
      --glass-shadow: 0 26px 52px -14px rgba(0, 0, 0, 0.50), 0 0 0 1px rgba(255, 255, 255, 0.06);
      --opt-bg: rgba(30, 41, 59, 0.16);
      --opt-hover: rgba(51, 65, 85, 0.40);
    }

    /* Quality presets via data-quality on <html> */
    html[data-quality="60"] {
      --glass-blur: 10px;
      --glass-saturate: 120%;
      --anim-scale: 0;
    }
    html[data-quality="90"] {
      --glass-blur: 22px;
      --glass-saturate: 150%;
      --anim-scale: 0.6;
    }
    html[data-quality="120"] {
      --glass-blur: 40px;
      --glass-saturate: 200%;
      --anim-scale: 1;
    }

    body {
      font-family: 'Inter', sans-serif;
      overflow-x: hidden;
      -webkit-tap-highlight-color: transparent;
      -webkit-text-size-adjust: 100%;
      text-size-adjust: 100%;
      touch-action: manipulation;
      min-height: 100vh;
      min-height: -webkit-fill-available;
      min-height: 100dvh;
      padding-bottom: env(safe-area-inset-bottom, 0px);
    }
    html {
      height: -webkit-fill-available;
    }
    /* iPhone Safari: tránh auto-zoom khi focus form (cần >= 16px) */
    @supports (-webkit-touch-callout: none) {
      input[type="text"], input[type="search"], input:not([type]), select, textarea {
        font-size: 16px !important;
      }
    }
    header.sticky {
      padding-top: env(safe-area-inset-top, 0px);
    }
    #exam-float-bar {
      padding-left: max(0.75rem, env(safe-area-inset-left, 0px));
      padding-right: max(0.75rem, env(safe-area-inset-right, 0px));
    }
    #toast-container {
      bottom: max(1.25rem, calc(env(safe-area-inset-bottom, 0px) + 0.75rem)) !important;
    }

    /* Animated Aurora Liquid Background Blobs 2.0 */
    .liquid-bg-canvas {
      position: fixed;
      inset: 0;
      z-index: -1;
      overflow: hidden;
      pointer-events: none;
    }
    .aurora-blob {
      position: absolute;
      border-radius: 9999px;
      filter: blur(78px);
      opacity: 0.68;
      will-change: transform;
      animation: floatAurora 18s infinite alternate cubic-bezier(0.16, 1, 0.3, 1);
    }
    html.dark .aurora-blob {
      opacity: 0.44;
    }
    .blob-1 {
      width: 38rem;
      height: 38rem;
      background: radial-gradient(circle, #3b82f6 0%, #06b6d4 65%, transparent 100%);
      top: -12%;
      left: -8%;
    }
    .blob-2 {
      width: 42rem;
      height: 42rem;
      background: radial-gradient(circle, #8b5cf6 0%, #ec4899 65%, transparent 100%);
      bottom: -16%;
      right: -8%;
      animation-delay: -6s;
      animation-duration: 22s;
    }
    .blob-3 {
      width: 32rem;
      height: 32rem;
      background: radial-gradient(circle, #10b981 0%, #3b82f6 65%, transparent 100%);
      top: 32%;
      left: 38%;
      animation-delay: -11s;
      animation-duration: 25s;
    }
    @keyframes floatAurora {
      0% { transform: translate3d(0, 0, 0) scale(1) rotate(0deg); }
      50% { transform: translate3d(60px, -45px, 0) scale(1.12) rotate(6deg); }
      100% { transform: translate3d(-45px, 50px, 0) scale(0.94) rotate(-6deg); }
    }

    /* Ultra-Translucent Liquid Glass 3.3 Surfaces */
    .liquid-glass {
      background: var(--glass-bg);
      backdrop-filter: blur(var(--glass-blur)) saturate(var(--glass-saturate));
      -webkit-backdrop-filter: blur(var(--glass-blur)) saturate(var(--glass-saturate));
      border: 1px solid var(--glass-border);
      box-shadow: var(--glass-highlight), var(--glass-shadow);
      position: relative;
      transition: transform 0.42s var(--spring),
                  box-shadow 0.38s cubic-bezier(0.16, 1, 0.3, 1),
                  border-color 0.28s ease,
                  background-color 0.32s ease,
                  opacity 0.32s ease;
    }
    .liquid-glass:hover {
      border-color: rgba(255, 255, 255, 0.72);
    }
    html.dark .liquid-glass:hover {
      border-color: rgba(255, 255, 255, 0.22);
    }

    /* Interactive cursor spotlight sheen on glass cards */
    .liquid-spotlight {
      position: relative;
      overflow: hidden;
    }
    .liquid-spotlight::before {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(
        520px circle at var(--mouse-x, 50%) var(--mouse-y, 50%),
        rgba(255, 255, 255, 0.18),
        transparent 42%
      );
      opacity: 0;
      transition: opacity 0.35s ease;
      pointer-events: none;
    }
    .liquid-spotlight:hover::before {
      opacity: 1;
    }

    /* Liquid Glass Option Buttons 3.2 */
    .liquid-opt {
      background: var(--opt-bg);
      backdrop-filter: blur(18px) saturate(170%);
      -webkit-backdrop-filter: blur(18px) saturate(170%);
      border: 1.5px solid var(--glass-border);
      box-shadow: var(--glass-highlight), 0 5px 14px -5px rgba(0, 0, 0, 0.06);
      transition: all 0.32s var(--spring);
      cursor: pointer;
    }
    .liquid-opt:hover {
      background: var(--opt-hover);
      transform: translateY(-2px) scale(1.01);
      border-color: rgba(56, 189, 248, 0.55);
      box-shadow: var(--glass-highlight), 0 12px 26px -6px rgba(56, 189, 248, 0.18);
    }
    .liquid-opt:active {
      transform: translateY(0) scale(0.982);
    }
    .liquid-opt:focus-visible {
      outline: 2px solid rgba(56, 189, 248, 0.7);
      outline-offset: 2px;
    }

    /* Toast notifications */
    #toast-container {
      position: fixed;
      bottom: 1.25rem;
      left: 50%;
      transform: translateX(-50%);
      z-index: 100;
      display: flex;
      flex-direction: column;
      gap: 0.5rem;
      pointer-events: none;
      width: min(92vw, 22rem);
    }
    .toast {
      pointer-events: auto;
      padding: 0.75rem 1.1rem;
      border-radius: 1rem;
      font-size: 0.8rem;
      font-weight: 700;
      display: flex;
      align-items: center;
      gap: 0.6rem;
      box-shadow: 0 12px 32px -8px rgba(0,0,0,0.25);
      animation: toastIn 0.38s var(--spring) forwards;
      backdrop-filter: blur(16px);
    }
    .toast-out {
      animation: toastOut 0.28s ease forwards;
    }
    @keyframes toastIn {
      from { opacity: 0; transform: translateY(16px) scale(0.96); }
      to { opacity: 1; transform: translateY(0) scale(1); }
    }
    @keyframes toastOut {
      to { opacity: 0; transform: translateY(10px) scale(0.96); }
    }

    /* Focus mode for practice */
    body.focus-mode #practice-question-card { max-width: 48rem; margin-left: auto; margin-right: auto; }
    body.focus-mode .lg\:col-span-4 { display: none !important; }
    body.focus-mode #practice-question-card { grid-column: 1 / -1; }

    /* Correct & Wrong Liquid States */
    .liquid-opt-correct {
      background: linear-gradient(135deg, rgba(16, 185, 129, 0.22), rgba(5, 150, 105, 0.10)) !important;
      border-color: rgba(16, 185, 129, 0.85) !important;
      box-shadow: inset 0 1px 2px rgba(255, 255, 255, 0.35), 0 10px 24px -6px rgba(16, 185, 129, 0.22) !important;
    }
    .liquid-opt-wrong {
      background: linear-gradient(135deg, rgba(244, 63, 94, 0.22), rgba(225, 29, 72, 0.10)) !important;
      border-color: rgba(244, 63, 94, 0.85) !important;
      box-shadow: inset 0 1px 2px rgba(255, 255, 255, 0.3), 0 10px 24px -6px rgba(244, 63, 94, 0.22) !important;
    }

    /* ===== ANIMATION GIỌT NƯỚC / DROPLET EFFECTS ===== */
    @keyframes dropletIn {
      0% {
        opacity: 0;
        transform: translateY(28px) scale(0.92);
        filter: blur(4px);
      }
      60% {
        opacity: 1;
        transform: translateY(-4px) scale(1.015);
        filter: blur(0);
      }
      100% {
        opacity: 1;
        transform: translateY(0) scale(1);
        filter: blur(0);
      }
    }
    @keyframes dropletOut {
      0% {
        opacity: 1;
        transform: translateY(0) scale(1);
      }
      100% {
        opacity: 0;
        transform: translateY(-16px) scale(0.96);
        filter: blur(2px);
      }
    }
    @keyframes springIn {
      0% { opacity: 0; transform: translateY(18px) scale(0.96); }
      70% { opacity: 1; transform: translateY(-3px) scale(1.01); }
      100% { opacity: 1; transform: translateY(0) scale(1); }
    }
    @keyframes ripple {
      0% { transform: scale(0.8); opacity: 0.6; }
      100% { transform: scale(2.2); opacity: 0; }
    }
    @keyframes softPulse {
      0%, 100% { box-shadow: 0 0 0 0 rgba(56, 189, 248, 0.25); }
      50% { box-shadow: 0 0 0 8px rgba(56, 189, 248, 0); }
    }

    .animate-spring {
      animation: dropletIn 0.55s cubic-bezier(0.34, 1.56, 0.64, 1) forwards;
    }
    .animate-droplet {
      animation: dropletIn 0.6s cubic-bezier(0.22, 1, 0.36, 1) forwards;
    }
    .tab-section {
      transition: opacity 0.3s ease, transform 0.35s cubic-bezier(0.34, 1.56, 0.64, 1);
    }
    .tab-section.hidden {
      display: none;
    }

    @keyframes shakeWrong {
      0%, 100% { transform: translateX(0); }
      20% { transform: translateX(-6px); }
      40% { transform: translateX(6px); }
      60% { transform: translateX(-4px); }
      80% { transform: translateX(3px); }
    }
    .animate-shake {
      animation: shakeWrong 0.38s ease-in-out;
    }

    /* Ripple effect on buttons */
    .ripple-btn {
      position: relative;
      overflow: hidden;
    }
    .ripple-btn::after {
      content: "";
      position: absolute;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.35);
      width: 20px;
      height: 20px;
      margin-top: -10px;
      margin-left: -10px;
      top: 50%;
      left: 50%;
      transform: scale(0);
      opacity: 0;
      pointer-events: none;
    }
    .ripple-btn:active::after {
      animation: ripple 0.5s ease-out;
    }

    .custom-scrollbar::-webkit-scrollbar { width: 5px; height: 5px; }
    .custom-scrollbar::-webkit-scrollbar-track { background: transparent; }
    .custom-scrollbar::-webkit-scrollbar-thumb { background: rgba(148, 163, 184, 0.4); border-radius: 9999px; }
    .custom-scrollbar::-webkit-scrollbar-thumb:hover { background: rgba(148, 163, 184, 0.7); }

    /* ===== MOBILE FIXES (quan trọng cho screenshot lỗi) ===== */
    @media (max-width: 640px) {
      .liquid-glass {
        border-radius: 1.25rem !important;
      }
      /* Header brand compact */
      header .font-extrabold.text-base {
        font-size: 0.95rem !important;
        line-height: 1.2;
      }
      /* Mobile nav pills – tránh cắt chữ */
      .mnav-btn {
        font-size: 0.7rem !important;
        padding-left: 0.65rem !important;
        padding-right: 0.65rem !important;
        white-space: nowrap;
      }
      /* Practice filter bar – xếp dọc sạch sẽ, không chồng chéo */
      #tab-practice .liquid-glass.p-4 {
        padding: 0.85rem !important;
      }
      #tab-practice select {
        width: 100% !important;
        min-width: 0 !important;
        font-size: 0.75rem !important;
        padding: 0.55rem 0.75rem !important;
      }
      #tab-practice .flex.flex-wrap.items-center.gap-2 {
        width: 100%;
        flex-direction: column;
        align-items: stretch;
        gap: 0.5rem !important;
      }
      #tab-practice .flex.flex-wrap.items-center.gap-3 {
        width: 100%;
        flex-direction: column;
        align-items: stretch;
        gap: 0.45rem !important;
      }
      #tab-practice label.liquid-opt {
        width: 100%;
        justify-content: flex-start;
        padding: 0.5rem 0.75rem !important;
      }
      /* Question card spacing */
      #practice-question-box .text-base {
        font-size: 0.95rem !important;
        line-height: 1.45;
      }
      /* Palette smaller on mobile */
      #practice-palette button {
        height: 1.85rem !important;
        font-size: 0.65rem !important;
      }
      /* Banner text smaller */
      #pdf-alert-banner h3 {
        font-size: 0.85rem !important;
      }
      #pdf-alert-banner p {
        font-size: 0.7rem !important;
      }
    }

    @media (max-width: 400px) {
      .mnav-btn span, .mnav-btn i + * {
        /* keep icons + short text */
      }
      header .hidden.sm\:block {
        display: none !important;
      }
    }

    /* Prevent select overflow / stacking */
    select.liquid-opt {
      appearance: none;
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='none' viewBox='0 0 24 24' stroke='%2394a3b8'%3E%3Cpath stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M19 9l-7 7-7-7'%3E%3C/path%3E%3C/svg%3E");
      background-repeat: no-repeat;
      background-position: right 0.6rem center;
      background-size: 1rem;
      padding-right: 2rem !important;
    }

    /* ===== PERFORMANCE 60–120fps (mobile + máy yếu) ===== */

    .tab-section {
      content-visibility: auto;
      contain-intrinsic-size: 1px 800px;
    }
    #practice-palette {
      contain: layout style;
    }

    header,
    .liquid-glass,
    #practice-question-card {
      transform: translateZ(0);
      backface-visibility: hidden;
    }

    @media (max-width: 768px), (prefers-reduced-motion: reduce) {
      .aurora-blob {
        animation: none !important;
        filter: blur(28px) !important;
        opacity: 0.22 !important;
        will-change: auto !important;
      }
      html.dark .aurora-blob { opacity: 0.14 !important; }
      .blob-2, .blob-3 { display: none !important; }

      .liquid-glass {
        backdrop-filter: blur(12px) saturate(125%) !important;
        -webkit-backdrop-filter: blur(12px) saturate(125%) !important;
        transition: background-color 0.16s ease, border-color 0.16s ease !important;
        box-shadow: 0 5px 18px -8px rgba(0,0,0,0.12) !important;
      }
      .liquid-opt {
        backdrop-filter: none !important;
        -webkit-backdrop-filter: none !important;
        background: rgba(255,255,255,0.62) !important;
        transition: background-color 0.1s ease, border-color 0.1s ease, transform 0.08s ease !important;
        box-shadow: none !important;
      }
      html.dark .liquid-opt {
        background: rgba(30,41,59,0.62) !important;
      }
      .liquid-opt:hover { transform: none !important; }
      .liquid-opt:active { transform: scale(0.98) !important; }
      .liquid-spotlight::before { display: none !important; }

      .animate-spring,
      .animate-droplet {
        animation-duration: 0.18s !important;
        animation-timing-function: ease-out !important;
      }
      #practice-question-card { min-height: auto !important; }
      .liquid-opt-correct,
      .liquid-opt-wrong { box-shadow: none !important; }
    }

    /* Lite mode – máy yếu / save-data / low cores */
    html.lite-mode .aurora-blob { display: none !important; }
    html.lite-mode .liquid-bg-canvas {
      background: linear-gradient(160deg, #e0f2fe 0%, #f0f9ff 45%, #ecfdf5 100%);
    }
    html.dark.lite-mode .liquid-bg-canvas {
      background: linear-gradient(160deg, #0f172a 0%, #1e293b 55%, #0f172a 100%);
    }
    html.lite-mode .liquid-glass {
      backdrop-filter: blur(8px) saturate(105%) !important;
      -webkit-backdrop-filter: blur(8px) saturate(105%) !important;
      box-shadow: 0 3px 12px -5px rgba(0,0,0,0.1) !important;
    }
    html.lite-mode .liquid-opt {
      backdrop-filter: none !important;
      -webkit-backdrop-filter: none !important;
      box-shadow: none !important;
      transition: background-color 0.08s ease, border-color 0.08s ease !important;
    }
    html.lite-mode .liquid-spotlight::before,
    html.lite-mode .animate-spring,
    html.lite-mode .animate-droplet,
    html.lite-mode .toast {
      animation: none !important;
    }
    html.lite-mode #toast-container { bottom: 0.75rem; }
  </style>
</head>
<body class="bg-slate-100 text-slate-900 dark:bg-[#060b18] dark:text-slate-100 min-h-screen flex flex-col selection:bg-sky-500 selection:text-white transition-colors duration-300">

  <!-- AMBIENT LIQUID AURORA BACKGROUND -->
  <div class="liquid-bg-canvas">
    <div class="aurora-blob blob-1"></div>
    <div class="aurora-blob blob-2"></div>
    <div class="aurora-blob blob-3"></div>
  </div>

  <!-- STICKY LIQUID GLASS 2.0 HEADER -->
  <header class="sticky top-0 z-40 liquid-glass border-x-0 border-t-0">
    <div class="max-w-7xl mx-auto px-3 sm:px-6">
      <div class="flex items-center justify-between h-16 gap-2">
        <!-- Brand Logo: Replaced with Sleek Home Icon -->
        <div class="flex items-center gap-3 cursor-pointer group" onclick="switchTab('dashboard')" title="Về Trang chủ Tổng quan">
          <div class="w-10 h-10 rounded-2xl bg-gradient-to-br from-sky-500 via-indigo-500 to-emerald-500 flex items-center justify-center text-white font-extrabold text-lg shadow-lg shadow-sky-500/30 group-hover:scale-105 transition-transform">
            <i class="fa-solid fa-house"></i>
          </div>
          <div>
            <div class="flex items-center gap-2">
              <span class="font-extrabold text-base sm:text-lg tracking-tight bg-gradient-to-r from-sky-500 via-indigo-400 to-emerald-400 bg-clip-text text-transparent">
                Triết Học Mác - Lênin
              </span>
              <span class="hidden sm:inline-flex items-center gap-1 text-[11px] font-bold px-2.5 py-0.5 rounded-full bg-sky-500/15 text-sky-600 dark:text-sky-300 border border-sky-500/30">
                TNUT • BAS 123 (v3.3)
              </span>
            </div>
            <p class="text-[11px] text-slate-500 dark:text-slate-400 hidden sm:block">
              ĐH Kỹ thuật Công nghiệp Thái Nguyên • Ngân hàng 600 Câu (2026 - 2027)
            </p>
          </div>
        </div>

        <!-- Desktop Navigation Pills -->
        <nav class="hidden lg:flex items-center gap-1 p-1.5 rounded-2xl bg-white/25 dark:bg-slate-900/35 border border-white/50 dark:border-white/15 backdrop-blur-2xl">
          <button onclick="switchTab('dashboard')" id="nav-dashboard" class="nav-btn px-3.5 py-2 rounded-xl text-xs font-bold transition-all flex items-center gap-2">
            <i class="fa-solid fa-house"></i> Trang chủ
          </button>
          <button onclick="switchTab('practice')" id="nav-practice" class="nav-btn px-3.5 py-2 rounded-xl text-xs font-bold transition-all flex items-center gap-2">
            <i class="fa-solid fa-book-open-reader"></i> Học theo chương
          </button>
          <button onclick="switchTab('exam')" id="nav-exam" class="nav-btn px-3.5 py-2 rounded-xl text-xs font-bold transition-all flex items-center gap-2">
            <i class="fa-solid fa-stopwatch"></i> Thi thử
          </button>
          <button onclick="switchTab('search')" id="nav-search" class="nav-btn px-3.5 py-2 rounded-xl text-xs font-bold transition-all flex items-center gap-2">
            <i class="fa-solid fa-magnifying-glass"></i> Tra cứu 600 câu
          </button>
          <button onclick="switchTab('review')" id="nav-review" class="nav-btn px-3.5 py-2 rounded-xl text-xs font-bold transition-all flex items-center gap-2">
            <i class="fa-solid fa-star"></i> Câu sai / Sao
            <span id="badge-review" class="px-1.5 py-0.2 text-[10px] rounded-full bg-amber-400 text-slate-950 font-extrabold">0</span>
          </button>
        </nav>

        <!-- Action Buttons: Quality + Glass + QR + PDF + Theme -->
        <div class="flex items-center gap-1.5 sm:gap-2">
          <!-- Performance / FPS Quality Preset -->
          <div class="hidden md:flex items-center gap-1 px-1.5 py-1 rounded-xl liquid-opt" title="Chế độ hiệu suất">
            <button type="button" onclick="setQuality('60')" id="q-btn-60" class="q-btn px-2 py-1 rounded-lg text-[10px] font-black transition">60</button>
            <button type="button" onclick="setQuality('90')" id="q-btn-90" class="q-btn px-2 py-1 rounded-lg text-[10px] font-black transition">90</button>
            <button type="button" onclick="setQuality('120')" id="q-btn-120" class="q-btn px-2 py-1 rounded-lg text-[10px] font-black transition">120</button>
          </div>

          <!-- Real-time Liquid Glass Transparency -->
          <div class="hidden sm:flex items-center gap-1.5 px-2.5 py-1.5 rounded-xl liquid-opt text-[11px] font-bold" title="Độ trong suốt kính">
            <i class="fa-solid fa-droplet text-sky-400"></i>
            <input type="range" id="glass-alpha-slider" min="6" max="42" value="16" oninput="updateGlassTransparency(this.value)" class="w-14 sm:w-16 accent-sky-500 cursor-pointer" />
          </div>

          <!-- Settings (mobile quality + glass) -->
          <button onclick="openSettingsModal()" class="md:hidden w-9 h-9 rounded-xl liquid-opt flex items-center justify-center text-slate-700 dark:text-slate-200" title="Cài đặt hiệu suất & kính">
            <i class="fa-solid fa-sliders"></i>
          </button>

          <!-- QR & Direct Web Link Button -->
          <button onclick="openQrModal()" class="px-3 py-2 rounded-xl text-xs font-bold bg-gradient-to-r from-sky-600 to-indigo-600 hover:from-sky-500 hover:to-indigo-500 text-white shadow-md shadow-sky-600/20 flex items-center gap-1.5 transition active:scale-95" title="Mã QR & Đường link tham gia trang web">
            <i class="fa-solid fa-qrcode"></i>
            <span class="hidden sm:inline">Mã QR & Link</span>
          </button>

          <!-- PDF Sync Button -->
          <button onclick="openPdfModal()" class="px-3 py-2 rounded-xl text-xs font-bold bg-gradient-to-r from-emerald-600 to-teal-500 hover:from-emerald-500 hover:to-teal-400 text-white shadow-md shadow-emerald-600/20 flex items-center gap-1.5 transition active:scale-95" title="Nạp nguyên văn file PDF 600 câu">
            <i class="fa-solid fa-file-pdf"></i>
            <span class="hidden md:inline" id="pdf-status-btn">Nạp PDF</span>
          </button>

          <button onclick="toggleTheme()" class="w-9 h-9 rounded-xl liquid-opt flex items-center justify-center text-slate-700 dark:text-slate-200" title="Đổi giao diện Sáng / Tối">
            <i id="theme-icon" class="fa-solid fa-sun text-amber-400"></i>
          </button>
          <button onclick="openResetModal()" class="w-9 h-9 rounded-xl liquid-opt hover:text-rose-500 flex items-center justify-center text-slate-600 dark:text-slate-400" title="Đặt lại tiến độ luyện tập">
            <i class="fa-solid fa-rotate-left"></i>
          </button>
        </div>
      </div>

      <!-- Mobile Navigation Bar -->
      <div class="flex lg:hidden overflow-x-auto custom-scrollbar py-2 gap-1.5 border-t border-white/30 dark:border-white/10">
        <button onclick="switchTab('dashboard')" id="mnav-dashboard" class="mnav-btn shrink-0 px-3 py-1.5 rounded-xl text-xs font-bold flex items-center gap-1.5">
          <i class="fa-solid fa-house"></i> Trang chủ
        </button>
        <button onclick="switchTab('practice')" id="mnav-practice" class="mnav-btn shrink-0 px-3 py-1.5 rounded-xl text-xs font-bold flex items-center gap-1.5">
          <i class="fa-solid fa-book-open-reader"></i> Ôn tập
        </button>
        <button onclick="switchTab('exam')" id="mnav-exam" class="mnav-btn shrink-0 px-3 py-1.5 rounded-xl text-xs font-bold flex items-center gap-1.5">
          <i class="fa-solid fa-stopwatch"></i> Thi thử
        </button>
        <button onclick="switchTab('search')" id="mnav-search" class="mnav-btn shrink-0 px-3 py-1.5 rounded-xl text-xs font-bold flex items-center gap-1.5">
          <i class="fa-solid fa-magnifying-glass"></i> Tra cứu 600 câu
        </button>
        <button onclick="switchTab('review')" id="mnav-review" class="mnav-btn shrink-0 px-3 py-1.5 rounded-xl text-xs font-bold flex items-center gap-1.5">
          <i class="fa-solid fa-star"></i> Câu sai / Sao
        </button>
      </div>
    </div>
  </header>

  <!-- MAIN CONTAINER -->
  <main class="flex-1 max-w-7xl w-full mx-auto px-3 sm:px-6 py-6 space-y-6">

    <!-- LIQUID GLASS 2.0 STATUS BANNER -->
    <div id="pdf-alert-banner" class="liquid-glass liquid-spotlight rounded-3xl p-4 sm:p-5 flex flex-col sm:flex-row items-start sm:items-center justify-between gap-4 border-l-4 border-l-sky-500">
      <div class="flex items-start gap-3.5">
        <div class="w-11 h-11 rounded-2xl bg-gradient-to-br from-sky-500/25 to-emerald-500/25 border border-sky-500/35 flex items-center justify-center shrink-0 text-sky-500 dark:text-sky-300 text-lg">
          <i class="fa-solid fa-building-columns"></i>
        </div>
        <div>
          <div class="flex flex-wrap items-center gap-2">
            <h3 class="font-extrabold text-sm sm:text-base">
              Ngân Hàng 600 Câu Hỏi & Đáp Án Chuẩn ĐH Kỹ Thuật Công Nghiệp Thái Nguyên (TNUT)
            </h3>
            <span id="loaded-count-badge" class="text-[11px] px-2.5 py-0.5 rounded-full bg-emerald-500/20 text-emerald-600 dark:text-emerald-300 border border-emerald-500/30 font-extrabold">
              Bản 3.3 • Xác thực theo Giáo trình TNUT
            </span>
          </div>
          <p class="text-xs text-slate-600 dark:text-slate-300 mt-1 leading-relaxed" id="banner-desc">
            Đáp án cả <b>600 câu (Chương 1: 95 • Chương 2: 240 • Chương 3: 265)</b> được đối chiếu chuẩn xác theo đề cương học phần <b>BAS 123 - Khoa KHCB&UD, Trường ĐH Kỹ thuật Công nghiệp Thái Nguyên</b>, kèm giải thích lý luận và tính năng chia sẻ qua <b>Mã QR / Đường link trực tiếp</b>.
          </p>
        </div>
      </div>
      <div class="flex flex-wrap items-center gap-2 shrink-0 w-full sm:w-auto">
        <button onclick="openQrModal()" class="flex-1 sm:flex-initial px-4 py-2.5 rounded-2xl liquid-opt font-bold text-xs flex items-center justify-center gap-2 text-sky-600 dark:text-sky-300 border-sky-500/40">
          <i class="fa-solid fa-qrcode"></i> Mở Mã QR & Link
        </button>
        <button onclick="openPdfModal()" class="flex-1 sm:flex-initial px-4 py-2.5 rounded-2xl bg-gradient-to-r from-sky-600 to-emerald-500 hover:from-sky-500 hover:to-emerald-400 text-white font-bold text-xs shadow-lg shadow-sky-600/20 transition flex items-center justify-center gap-2">
          <i class="fa-solid fa-file-arrow-up"></i> Đồng bộ PDF gốc
        </button>
      </div>
    </div>

    <!-- TAB 1: DASHBOARD -->
    <section id="tab-dashboard" class="tab-section space-y-6 animate-spring">
      <!-- 5 Liquid Glass Stat Cards -->
      <div class="grid grid-cols-2 lg:grid-cols-5 gap-3.5 sm:gap-4">
        <div class="liquid-glass liquid-spotlight p-4 sm:p-5 rounded-3xl">
          <div class="flex items-center justify-between text-slate-500 dark:text-slate-400 text-xs font-semibold">
            <span>Tổng ngân hàng</span>
            <span class="w-8 h-8 rounded-xl bg-indigo-500/15 text-indigo-500 flex items-center justify-center"><i class="fa-solid fa-layer-group"></i></span>
          </div>
          <div class="text-2xl sm:text-3xl font-black mt-2" id="stat-total">600</div>
          <div class="text-[11px] text-slate-500 dark:text-slate-400 mt-1">3 Chương • 10 Chuyên đề</div>
        </div>

        <div class="liquid-glass liquid-spotlight p-4 sm:p-5 rounded-3xl">
          <div class="flex items-center justify-between text-slate-500 dark:text-slate-400 text-xs font-semibold">
            <span>Đã luyện tập</span>
            <span class="w-8 h-8 rounded-xl bg-sky-500/15 text-sky-500 flex items-center justify-center"><i class="fa-solid fa-pen-clip"></i></span>
          </div>
          <div class="text-2xl sm:text-3xl font-black mt-2 text-sky-600 dark:text-sky-400" id="stat-answered">0</div>
          <div class="text-[11px] text-slate-500 dark:text-slate-400 mt-1" id="stat-progress-pct">Hoàn thành 0%</div>
        </div>

        <div class="liquid-glass liquid-spotlight p-4 sm:p-5 rounded-3xl">
          <div class="flex items-center justify-between text-slate-500 dark:text-slate-400 text-xs font-semibold">
            <span>Trả lời đúng</span>
            <span class="w-8 h-8 rounded-xl bg-emerald-500/15 text-emerald-500 flex items-center justify-center"><i class="fa-solid fa-check-double"></i></span>
          </div>
          <div class="text-2xl sm:text-3xl font-black mt-2 text-emerald-600 dark:text-emerald-400" id="stat-correct">0</div>
          <div class="text-[11px] text-slate-500 dark:text-slate-400 mt-1" id="stat-accuracy">Tỷ lệ đúng: 0%</div>
        </div>

        <div class="liquid-glass liquid-spotlight p-4 sm:p-5 rounded-3xl">
          <div class="flex items-center justify-between text-slate-500 dark:text-slate-400 text-xs font-semibold">
            <span>Đang chọn sai</span>
            <span class="w-8 h-8 rounded-xl bg-rose-500/15 text-rose-500 flex items-center justify-center"><i class="fa-solid fa-bolt"></i></span>
          </div>
          <div class="text-2xl sm:text-3xl font-black mt-2 text-rose-600 dark:text-rose-400" id="stat-wrong">0</div>
          <div class="text-[11px] text-slate-500 dark:text-slate-400 mt-1">Có thể chọn lại ngay</div>
        </div>

        <div class="col-span-2 lg:col-span-1 liquid-glass liquid-spotlight p-4 sm:p-5 rounded-3xl">
          <div class="flex items-center justify-between text-slate-500 dark:text-slate-400 text-xs font-semibold">
            <span>Đánh dấu sao</span>
            <span class="w-8 h-8 rounded-xl bg-amber-500/15 text-amber-500 flex items-center justify-center"><i class="fa-solid fa-star"></i></span>
          </div>
          <div class="text-2xl sm:text-3xl font-black mt-2 text-amber-500" id="stat-starred">0</div>
          <div class="text-[11px] text-slate-500 dark:text-slate-400 mt-1">Câu hỏi trọng tâm</div>
        </div>
      </div>

      <!-- 3 Chapter Liquid Cards -->
      <div>
        <div class="flex items-center justify-between mb-3.5">
          <h2 class="text-base sm:text-lg font-extrabold flex items-center gap-2">
            <i class="fa-solid fa-compass text-red-500"></i>
            Lộ Trình Ôn Tập 3 Chương (Mã HP: BAS 123)
          </h2>
          <span class="text-xs font-semibold text-slate-500 dark:text-slate-400">Thang điểm: 0.2 điểm / câu</span>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-5" id="chapter-cards-container"></div>
      </div>

      <!-- 10 Subtopics & Mock Exam History -->
      <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
        <div class="lg:col-span-2 liquid-glass rounded-3xl p-5 sm:p-6">
          <h3 class="font-extrabold text-base mb-4 flex items-center gap-2">
            <i class="fa-solid fa-list-check text-amber-500"></i>
            10 Chuyên Đề Chi Tiết Trong Ngân Hàng Đề Thi
          </h3>
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-3" id="subtopic-list"></div>
        </div>

        <div class="liquid-glass rounded-3xl p-5 sm:p-6 flex flex-col justify-between">
          <div>
            <h3 class="font-extrabold text-base mb-4 flex items-center gap-2">
              <i class="fa-solid fa-clock-rotate-left text-emerald-500"></i>
              Lịch Sử Thi Thử Gần Đây
            </h3>
            <div id="exam-history-list" class="space-y-2.5 max-h-72 overflow-y-auto custom-scrollbar"></div>
          </div>
          <button onclick="switchTab('exam')" class="mt-4 w-full py-3 rounded-2xl bg-gradient-to-r from-red-600 to-amber-500 hover:from-red-500 hover:to-amber-400 text-white font-extrabold text-xs shadow-lg shadow-red-600/20 transition flex items-center justify-center gap-2">
            <i class="fa-solid fa-play"></i> Tạo Đề Thi Thử 50 Câu Ngay
          </button>
        </div>
      </div>
    </section>

    <!-- TAB 2: PRACTICE (HỌC THEO CHƯƠNG - CHO PHÉP CHỌN LẠI ĐÁP ÁN MƯỢT MÀ) -->
    <section id="tab-practice" class="tab-section hidden space-y-5 animate-spring">
      <!-- Filter & Mode Bar – tối ưu mobile, không chồng chéo -->
      <div class="liquid-glass p-3 sm:p-4 rounded-3xl flex flex-col gap-3">
        <div class="grid grid-cols-1 sm:grid-cols-3 gap-2">
          <select id="practice-chapter-select" onchange="onPracticeFilterChange()" class="w-full px-3.5 py-2.5 rounded-2xl text-xs font-bold liquid-opt focus:outline-none">
            <option value="all" class="bg-white dark:bg-slate-900">Tất cả 3 Chương (600 câu)</option>
            <option value="1" class="bg-white dark:bg-slate-900">Chương 1: Khái luận về Triết học & Triết học Mác-Lênin (95 câu)</option>
            <option value="2" class="bg-white dark:bg-slate-900">Chương 2: Chủ nghĩa duy vật biện chứng (240 câu)</option>
            <option value="3" class="bg-white dark:bg-slate-900">Chương 3: Chủ nghĩa duy vật lịch sử (265 câu)</option>
          </select>

          <select id="practice-section-select" onchange="onPracticeFilterChange()" class="w-full px-3.5 py-2.5 rounded-2xl text-xs font-bold liquid-opt focus:outline-none">
            <option value="all" class="bg-white dark:bg-slate-900">Tất cả 10 chuyên đề</option>
            <option value="1.1" class="bg-white dark:bg-slate-900">1.1. Triết học và vấn đề cơ bản (Câu 1 - 49)</option>
            <option value="1.2" class="bg-white dark:bg-slate-900">1.2. Triết học Mác-Lênin và vai trò (Câu 50 - 95)</option>
            <option value="2.1" class="bg-white dark:bg-slate-900">2.1. Vật chất, ý thức và mối quan hệ (Câu 1 - 79)</option>
            <option value="2.2" class="bg-white dark:bg-slate-900">2.2. Phép biện chứng duy vật (Câu 80 - 199)</option>
            <option value="2.3" class="bg-white dark:bg-slate-900">2.3. Lý luận nhận thức (Câu 200 - 240)</option>
            <option value="3.1" class="bg-white dark:bg-slate-900">3.1. Học thuyết hình thái KT-XH (Câu 1 - 74)</option>
            <option value="3.2" class="bg-white dark:bg-slate-900">3.2. Giai cấp và dân tộc (Câu 75 - 139)</option>
            <option value="3.3" class="bg-white dark:bg-slate-900">3.3. Nhà nước và cách mạng xã hội (Câu 140 - 188)</option>
            <option value="3.4" class="bg-white dark:bg-slate-900">3.4. Ý thức xã hội (Câu 189 - 226)</option>
            <option value="3.5" class="bg-white dark:bg-slate-900">3.5. Triết học về con người (Câu 227 - 265)</option>
          </select>

          <select id="practice-status-select" onchange="onPracticeFilterChange()" class="w-full px-3.5 py-2.5 rounded-2xl text-xs font-bold liquid-opt focus:outline-none">
            <option value="all" class="bg-white dark:bg-slate-900">Mọi trạng thái</option>
            <option value="unanswered" class="bg-white dark:bg-slate-900">Chưa làm</option>
            <option value="wrong" class="bg-white dark:bg-slate-900">Đang làm sai</option>
            <option value="correct" class="bg-white dark:bg-slate-900">Đã làm đúng</option>
            <option value="starred" class="bg-white dark:bg-slate-900">Đã gắn sao ★</option>
          </select>
        </div>

        <div class="flex flex-wrap items-center gap-2">
          <label class="flex items-center gap-2 text-xs font-semibold cursor-pointer select-none px-3 py-1.5 rounded-xl liquid-opt" title="Khi tắt: Nếu chọn sai sẽ chỉ báo đỏ đáp án sai để bạn tự bấm chọn lại đáp án khác đến khi đúng!">
            <input type="checkbox" id="practice-reveal-on-wrong" checked onchange="renderPracticeQuestion()" class="rounded text-red-600 focus:ring-red-500">
            <span>Chỉ báo đáp án đúng khi chọn sai</span>
          </label>
          <label class="flex items-center gap-2 text-xs font-semibold cursor-pointer select-none px-3 py-1.5 rounded-xl liquid-opt">
            <input type="checkbox" id="practice-instant-show" onchange="renderPracticeQuestion()" class="rounded text-red-600 focus:ring-red-500">
            <span>Luôn hiện đáp án</span>
          </label>
          <label class="flex items-center gap-2 text-xs font-semibold cursor-pointer select-none px-3 py-1.5 rounded-xl liquid-opt">
            <input type="checkbox" id="practice-auto-next" class="rounded text-red-600 focus:ring-red-500">
            <span>Tự qua câu khi đúng</span>
          </label>
          <button onclick="shufflePracticeList()" class="px-3.5 py-1.5 rounded-xl liquid-opt text-xs font-bold flex items-center gap-1.5">
            <i class="fa-solid fa-shuffle text-amber-500"></i> Trộn đề
          </button>
          <button onclick="toggleFocusMode()" id="btn-focus-mode" class="px-3.5 py-1.5 rounded-xl liquid-opt text-xs font-bold flex items-center gap-1.5" title="Ẩn bảng lưới để tập trung">
            <i class="fa-solid fa-expand text-sky-500"></i> Focus
          </button>
        </div>
      </div>

      <!-- Question Workspace & Palette -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
        <!-- Left Column: Question Card -->
        <div id="practice-question-card" class="lg:col-span-8 liquid-glass liquid-spotlight rounded-3xl p-5 sm:p-7 flex flex-col justify-between min-h-[470px]">
          <div id="practice-question-box"></div>

          <!-- Footer Navigation -->
          <div class="flex flex-wrap items-center justify-between gap-2 pt-5 mt-6 border-t border-white/40 dark:border-white/10">
            <button onclick="prevPracticeQuestion()" class="px-4 py-2.5 rounded-2xl liquid-opt font-bold text-xs flex items-center gap-2">
              <i class="fa-solid fa-arrow-left"></i> Câu trước (←)
            </button>
            <div class="flex items-center gap-2">
              <span id="practice-counter" class="text-xs font-extrabold px-3 py-1.5 rounded-xl bg-white/50 dark:bg-slate-800/70">1 / 600</span>
            </div>
            <button onclick="nextPracticeQuestion()" class="px-5 py-2.5 rounded-2xl bg-gradient-to-r from-red-600 to-amber-500 hover:from-red-500 hover:to-amber-400 text-white font-bold text-xs flex items-center gap-2 shadow-lg shadow-red-600/25 transition active:scale-95">
              Câu tiếp (→) <i class="fa-solid fa-arrow-right"></i>
            </button>
          </div>
        </div>

        <!-- Right Column: Question Grid Palette -->
        <div class="lg:col-span-4 liquid-glass rounded-3xl p-4 sm:p-5 flex flex-col max-h-[580px]">
          <div class="flex items-center justify-between mb-3">
            <h3 class="font-extrabold text-xs uppercase tracking-wider text-slate-600 dark:text-slate-300">
              Bảng Lưới Câu Hỏi
            </h3>
            <div class="flex items-center gap-2.5 text-[11px] font-semibold">
              <span class="flex items-center gap-1"><span class="w-2.5 h-2.5 rounded-full bg-emerald-500 inline-block"></span>Đúng</span>
              <span class="flex items-center gap-1"><span class="w-2.5 h-2.5 rounded-full bg-rose-500 inline-block"></span>Sai</span>
              <span class="flex items-center gap-1"><span class="w-2.5 h-2.5 rounded-full bg-amber-400 inline-block"></span>Sao</span>
            </div>
          </div>
          <div id="practice-palette" class="grid grid-cols-6 sm:grid-cols-8 lg:grid-cols-6 gap-1.5 overflow-y-auto custom-scrollbar pr-1 flex-1"></div>
        </div>
      </div>
    </section>

    <!-- TAB 3: EXAM (THI THỬ) -->
    <section id="tab-exam" class="tab-section hidden space-y-6 animate-spring">
      <!-- Setup Screen -->
      <div id="exam-setup-view" class="max-w-2xl mx-auto liquid-glass liquid-spotlight rounded-3xl p-6 sm:p-8">
        <div class="text-center mb-6">
          <div class="w-16 h-16 rounded-3xl bg-gradient-to-br from-red-500/20 to-amber-500/20 border border-red-500/30 text-red-500 flex items-center justify-center text-2xl mx-auto mb-3 shadow-inner">
            <i class="fa-solid fa-graduation-cap"></i>
          </div>
          <h2 class="text-xl sm:text-2xl font-black">Phòng Thi Thử Triết Học Mác - Lênin</h2>
          <p class="text-xs text-slate-500 dark:text-slate-400 mt-1">
            Mã học phần: BAS 123 • Chuẩn 50 câu (0.2 điểm/câu) • Cho phép đổi đáp án không giới hạn trước khi nộp
          </p>
        </div>

        <div class="space-y-4">
          <div>
            <label class="block text-xs font-extrabold uppercase tracking-wider text-slate-500 dark:text-slate-400 mb-2">
              1. Phạm vi kiến thức
            </label>
            <select id="exam-scope" class="w-full px-4 py-3 rounded-2xl liquid-opt font-bold text-sm focus:outline-none">
              <option value="all" class="bg-white dark:bg-slate-900">Tổng hợp 3 Chương (Chuẩn cấu trúc đề thi kết thúc học phần)</option>
              <option value="1" class="bg-white dark:bg-slate-900">Chỉ riêng Chương 1 (95 câu)</option>
              <option value="2" class="bg-white dark:bg-slate-900">Chỉ riêng Chương 2 (240 câu)</option>
              <option value="3" class="bg-white dark:bg-slate-900">Chỉ riêng Chương 3 (265 câu)</option>
              <option value="wrong" class="bg-white dark:bg-slate-900">Chỉ lấy các câu đang làm sai / gắn sao</option>
            </select>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-extrabold uppercase tracking-wider text-slate-500 dark:text-slate-400 mb-2">
                2. Số câu hỏi
              </label>
              <select id="exam-count" class="w-full px-4 py-3 rounded-2xl liquid-opt font-bold text-sm focus:outline-none">
                <option value="50" selected class="bg-white dark:bg-slate-900">50 câu (Chuẩn 0.2đ/câu = 10 điểm)</option>
                <option value="25" class="bg-white dark:bg-slate-900">25 câu (Đề luyện nhanh)</option>
                <option value="60" class="bg-white dark:bg-slate-900">60 câu (Đề nâng cao)</option>
                <option value="100" class="bg-white dark:bg-slate-900">100 câu (Đề tổng ôn)</option>
              </select>
            </div>
            <div>
              <label class="block text-xs font-extrabold uppercase tracking-wider text-slate-500 dark:text-slate-400 mb-2">
                3. Thời gian làm bài
              </label>
              <select id="exam-duration" class="w-full px-4 py-3 rounded-2xl liquid-opt font-bold text-sm focus:outline-none">
                <option value="45" class="bg-white dark:bg-slate-900">45 phút</option>
                <option value="60" selected class="bg-white dark:bg-slate-900">60 phút (Chuẩn)</option>
                <option value="30" class="bg-white dark:bg-slate-900">30 phút</option>
                <option value="90" class="bg-white dark:bg-slate-900">90 phút</option>
              </select>
            </div>
          </div>

          <button onclick="startExam()" class="w-full py-3.5 mt-2 rounded-2xl bg-gradient-to-r from-red-600 via-rose-500 to-amber-500 hover:from-red-500 hover:to-amber-400 text-white font-black text-sm shadow-xl shadow-red-600/25 transition flex items-center justify-center gap-2">
            <i class="fa-solid fa-bolt"></i> Bắt Đầu Làm Bài Thi Ngay
          </button>
        </div>
      </div>

      <!-- Active Exam View -->
      <div id="exam-active-view" class="hidden space-y-5">
        <!-- Spacer for fixed floating bar height -->
        <div id="exam-bar-spacer" class="h-16 sm:h-[4.5rem]" aria-hidden="true"></div>
        <div id="exam-questions-list" class="space-y-4 pb-24"></div>
      </div>

      <!-- Exam Result View -->
      <div id="exam-result-view" class="hidden space-y-6"></div>
    </section>

    <!-- TAB 4: SEARCH & 600 ANSWER KEY -->
    <section id="tab-search" class="tab-section hidden space-y-5 animate-spring">
      <div class="liquid-glass p-5 rounded-3xl space-y-4">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3">
          <div>
            <h2 class="text-base sm:text-lg font-extrabold flex items-center gap-2">
              <i class="fa-solid fa-magnifying-glass text-red-500"></i>
              Tra Cứu Nhanh 600 Câu Hỏi & Đáp Án Chi Tiết (A, B, C, D)
            </h2>
            <p class="text-xs text-slate-500 dark:text-slate-400 mt-0.5">
              Nhập từ khóa câu hỏi, nội dung phương án hoặc mã câu (VD: <code class="px-1.5 py-0.5 rounded bg-white/50 dark:bg-slate-800 font-mono">1.1.0,2.1</code>, <code class="px-1.5 py-0.5 rounded bg-white/50 dark:bg-slate-800 font-mono">vật chất</code>, <code class="px-1.5 py-0.5 rounded bg-white/50 dark:bg-slate-800 font-mono">lượng chất</code>...)
            </p>
          </div>
          <button onclick="toggleCompactKeyModal()" class="px-4 py-2.5 rounded-2xl bg-amber-500/20 text-amber-700 dark:text-amber-300 border border-amber-500/40 hover:bg-amber-500/30 text-xs font-extrabold transition flex items-center gap-2 shrink-0">
            <i class="fa-solid fa-table-cells"></i> Bảng Phao Đáp Án Rút Gọn (600 Câu)
          </button>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-12 gap-3">
          <div class="md:col-span-7 relative">
            <i class="fa-solid fa-search absolute left-4 top-1/2 -translate-y-1/2 text-slate-400 text-sm"></i>
            <input
              type="text"
              id="search-input"
              oninput="debouncedSearch()"
              placeholder="Gõ từ khóa bất kỳ (có dấu hoặc không dấu) hoặc số thứ tự câu..."
              class="w-full pl-10 pr-9 py-2.5 rounded-2xl liquid-opt text-sm font-medium focus:outline-none"
            />
            <button onclick="clearSearchInput()" class="absolute right-3.5 top-1/2 -translate-y-1/2 text-slate-400 hover:text-slate-600 text-xs">
              <i class="fa-solid fa-xmark"></i>
            </button>
          </div>

          <div class="md:col-span-3">
            <select id="search-chapter-filter" onchange="renderSearchResults()" class="w-full px-3.5 py-2.5 rounded-2xl liquid-opt text-xs font-bold focus:outline-none">
              <option value="all" class="bg-white dark:bg-slate-900">Tất cả 3 Chương (600 câu)</option>
              <option value="1" class="bg-white dark:bg-slate-900">Chương 1 (95 câu)</option>
              <option value="2" class="bg-white dark:bg-slate-900">Chương 2 (240 câu)</option>
              <option value="3" class="bg-white dark:bg-slate-900">Chương 3 (265 câu)</option>
            </select>
          </div>

          <div class="md:col-span-2 flex items-center justify-end">
            <span id="search-count-label" class="text-xs font-extrabold text-slate-500">Hiển thị 600 câu</span>
          </div>
        </div>
      </div>

      <div id="search-results-container" class="space-y-3.5"></div>
    </section>

    <!-- TAB 5: REVIEW (CÂU SAI & ĐÁNH DẤU SAO) -->
    <section id="tab-review" class="tab-section hidden space-y-5 animate-spring">
      <div class="liquid-glass p-5 rounded-3xl flex flex-wrap items-center justify-between gap-4">
        <div>
          <h2 class="text-lg font-extrabold flex items-center gap-2">
            <i class="fa-solid fa-star text-amber-400"></i>
            Sổ Tay Câu Hỏi Đang Làm Sai & Đánh Dấu Sao
          </h2>
          <p class="text-xs text-slate-500 dark:text-slate-400 mt-0.5">
            Bạn có thể bấm trực tiếp vào các đáp án A, B, C, D bên dưới để chọn lại ngay lập tức!
          </p>
        </div>
        <div class="flex flex-wrap items-center gap-2">
          <button onclick="setReviewMode('wrong')" id="btn-rev-wrong" class="px-3.5 py-2 rounded-2xl text-xs font-bold transition">
            Câu đang sai (<span id="rev-wrong-count">0</span>)
          </button>
          <button onclick="setReviewMode('starred')" id="btn-rev-starred" class="px-3.5 py-2 rounded-2xl text-xs font-bold transition">
            Câu gắn sao ★ (<span id="rev-star-count">0</span>)
          </button>
          <button onclick="practiceReviewQuestions()" class="px-4 py-2 rounded-2xl bg-gradient-to-r from-red-600 to-amber-500 text-white text-xs font-extrabold shadow-md transition flex items-center gap-1.5">
            <i class="fa-solid fa-dumbbell"></i> Mở trong Chế độ Luyện tập
          </button>
        </div>
      </div>

      <div id="review-list-container" class="space-y-3.5"></div>
    </section>

  </main>

  <!-- FOOTER -->
  <footer class="mt-12 liquid-glass border-x-0 border-b-0 py-5">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 flex flex-col sm:flex-row items-center justify-between gap-3 text-xs text-slate-500 dark:text-slate-400">
      <div class="flex items-center gap-2 font-bold text-slate-700 dark:text-slate-200 cursor-pointer" onclick="switchTab('dashboard')">
        <span class="w-6 h-6 rounded-lg bg-sky-500/20 text-sky-500 flex items-center justify-center"><i class="fa-solid fa-house text-xs"></i></span>
        <span>Hệ Thống Ôn Tập Triết Học Mác - Lênin (BAS 123 - TNUT) • Liquid Glass 3.3</span>
      </div>
      <div class="flex items-center gap-3 flex-wrap justify-end">
        <span>Khoa KHCB&UD - ĐH Kỹ thuật Công nghiệp Thái Nguyên (600 câu • 2026-2027)</span>
        <button onclick="openQrModal()" class="text-sky-500 hover:underline font-bold flex items-center gap-1">
          <i class="fa-solid fa-qrcode"></i> Mã QR
        </button>
        <span class="font-extrabold text-slate-600 dark:text-slate-300">Tác giả: <span class="text-sky-500">tbao2902</span></span>
      </div>
    </div>
  </footer>

  <!-- FIXED EXAM BAR — luôn trôi nổi khi đang thi (ngoài tab để không bị ẩn) -->
  <div id="exam-float-bar" class="fixed left-0 right-0 z-[45] hidden px-3 sm:px-6 pointer-events-none top-[calc(6.75rem+env(safe-area-inset-top,0px))] lg:top-[calc(4.25rem+env(safe-area-inset-top,0px))]">
    <div class="pointer-events-auto max-w-7xl mx-auto liquid-glass p-3 sm:p-3.5 rounded-2xl sm:rounded-3xl flex flex-wrap items-center justify-between gap-2 sm:gap-3 shadow-xl border border-white/50 dark:border-white/15">
      <div class="flex items-center gap-2.5 sm:gap-3 min-w-0">
        <div id="exam-timer-box" class="px-3.5 py-2 rounded-2xl bg-red-500/15 border border-red-500/35 text-red-600 dark:text-red-400 font-black font-mono text-sm sm:text-base flex items-center gap-2 shrink-0">
          <i class="fa-regular fa-clock"></i>
          <span id="exam-timer">60:00</span>
        </div>
        <div class="min-w-0">
          <div class="text-xs font-extrabold truncate" id="exam-progress-text">Đã chọn: 0 / 50 câu</div>
          <div class="text-[10px] sm:text-[11px] text-slate-500 dark:text-slate-400">Có thể đổi đáp án bất kỳ lúc nào</div>
        </div>
      </div>
      <div class="flex items-center gap-2 shrink-0">
        <button type="button" onclick="cancelExam()" class="px-3 sm:px-4 py-2 rounded-2xl liquid-opt text-xs font-bold">Hủy</button>
        <button type="button" onclick="submitExam()" class="px-3.5 sm:px-5 py-2 rounded-2xl bg-gradient-to-r from-emerald-600 to-teal-500 text-white font-extrabold text-xs shadow-lg flex items-center gap-1.5">
          <i class="fa-solid fa-paper-plane"></i> Nộp bài
        </button>
      </div>
    </div>
  </div>

  <!-- Toast notifications -->
  <div id="toast-container" aria-live="polite"></div>

  <!-- MODAL 0: BỘ TẠO MÃ QR & ĐƯỜNG LINK ĐỘC LẬP CỦA RIÊNG TRANG WEB MỚI (BẢN 3.0) -->
  <div id="qr-modal" class="fixed inset-0 z-50 hidden bg-slate-950/60 backdrop-blur-xl flex items-center justify-center p-4">
    <div class="liquid-glass w-full max-w-2xl rounded-3xl p-6 space-y-5 animate-spring">
      <div class="flex items-center justify-between">
        <div class="flex items-center gap-3">
          <div class="w-11 h-11 rounded-2xl bg-gradient-to-br from-sky-500/30 to-emerald-500/30 border border-sky-400/40 text-sky-400 flex items-center justify-center text-xl">
            <i class="fa-solid fa-qrcode"></i>
          </div>
          <div>
            <div class="flex items-center gap-2">
              <h3 class="font-extrabold text-base sm:text-lg">Mã QR & Link Của Riêng Trang Web Mới</h3>
              <span class="px-2 py-0.5 rounded-full text-[10px] font-black bg-emerald-500/20 text-emerald-400 border border-emerald-500/30">
                Native Canvas v3.0
              </span>
            </div>
            <p class="text-xs text-slate-500 dark:text-slate-300">
              Mã QR được vẽ trực tiếp bởi chính ứng dụng này (kèm logo Home ở tâm), tuyệt đối không dùng link cũ
            </p>
          </div>
        </div>
        <button onclick="closeQrModal()" class="w-8 h-8 rounded-xl liquid-opt flex items-center justify-center text-slate-400">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>

      <!-- Khu vực Hiển thị Canvas QR Tự Thân & Tùy chỉnh Link -->
      <div class="grid grid-cols-1 sm:grid-cols-12 gap-5 items-center">
        <!-- Cột trái: Thẻ QR Canvas có gắn Logo Home ở tâm -->
        <div class="sm:col-span-5 flex flex-col items-center justify-center p-4 rounded-3xl bg-white text-slate-900 shadow-xl border border-slate-200/80">
          <div class="text-[11px] font-black uppercase tracking-wider text-sky-600 mb-1.5 flex items-center gap-1">
            <i class="fa-solid fa-house"></i> TNUT • BAS 123 (600 Câu)
          </div>
          <canvas
            id="native-qr-canvas"
            width="240"
            height="240"
            class="w-44 h-44 rounded-2xl shadow-inner bg-white"
          ></canvas>
          <span id="qr-status-badge" class="text-[11px] font-extrabold text-slate-700 mt-2 flex items-center gap-1 text-center">
            <i class="fa-solid fa-camera text-emerald-600"></i> Quét bằng Camera / Zalo
          </span>
        </div>

        <!-- Cột phải: Điều khiển Link & Chia sẻ nhanh -->
        <div class="sm:col-span-7 space-y-3.5 text-xs">
          <div>
            <div class="flex items-center justify-between mb-1">
              <label class="font-extrabold text-slate-700 dark:text-slate-200">
                Đường link trang web mới của bạn:
              </label>
              <button onclick="useCurrentBrowserUrl()" class="text-[11px] font-bold text-sky-400 hover:underline flex items-center gap-1">
                <i class="fa-solid fa-location-crosshairs"></i> Lấy địa chỉ hiện tại
              </button>
            </div>
            <div class="flex items-center gap-1.5">
              <input
                type="text"
                id="share-url-input"
                oninput="updateQrCodeFromInput()"
                class="w-full px-3 py-2.5 rounded-xl liquid-opt font-mono text-xs focus:outline-none"
                placeholder="Nhập địa chỉ web mới của bạn để tạo QR..."
              />
              <button onclick="copyShareUrl()" id="copy-link-btn" class="shrink-0 px-3.5 py-2.5 rounded-xl bg-sky-600 hover:bg-sky-500 text-white font-extrabold transition flex items-center gap-1">
                <i class="fa-regular fa-copy"></i> Copy
              </button>
            </div>
            <p id="copy-status-msg" class="text-[11px] text-emerald-400 font-bold mt-1 hidden">
              ✓ Đã sao chép đường link trang web mới vào bộ nhớ tạm!
            </p>
          </div>

          <!-- Các nút hành động trực tiếp không cần dòng lệnh -->
          <div class="grid grid-cols-2 gap-2">
            <button onclick="downloadQrPosterPng()" class="p-2.5 rounded-2xl bg-gradient-to-r from-sky-600 to-indigo-600 hover:from-sky-500 hover:to-indigo-500 text-white font-extrabold text-xs shadow-md flex items-center justify-center gap-1.5 transition active:scale-95">
              <i class="fa-solid fa-file-image"></i> Tải Thẻ QR (.PNG)
            </button>
            <button onclick="shareWebAppNative()" class="p-2.5 rounded-2xl bg-gradient-to-r from-emerald-600 to-teal-500 hover:from-emerald-500 hover:to-teal-400 text-white font-extrabold text-xs shadow-md flex items-center justify-center gap-1.5 transition active:scale-95">
              <i class="fa-solid fa-share-nodes"></i> Chia Sẻ Nhanh
            </button>
          </div>

          <div class="p-3.5 rounded-2xl liquid-opt space-y-2">
            <div class="font-extrabold text-sky-500 dark:text-sky-300 flex items-center gap-1.5">
              <i class="fa-solid fa-wand-magic-sparkles"></i> Mở trực tiếp hoặc xuất bản Web riêng trong 10 giây:
            </div>
            <p class="text-slate-600 dark:text-slate-300 leading-relaxed">
              • <b>Cách 1 (Mở trực tiếp không cần lệnh):</b> Bấm nút <b>"Tải File Web Độc Lập (.html)"</b> bên dưới để mở ngay trên điện thoại hoặc máy tính.<br/>
              • <b>Cách 2 (Tạo tên miền riêng của bạn):</b> Kéo thả file vừa tải vào <a href="https://app.netlify.com/drop" target="_blank" rel="noopener noreferrer" class="text-sky-400 underline font-bold">Netlify Drop</a> hoặc <a href="https://tiiny.host" target="_blank" rel="noopener noreferrer" class="text-sky-400 underline font-bold">Tiiny.host</a>, trang web mới của bạn sẽ tự động nhận diện URL đó và sinh mã QR riêng!
            </p>
            <div class="pt-1">
              <button onclick="downloadStandaloneHtml()" class="w-full py-2.5 rounded-xl liquid-opt hover:border-emerald-500/60 font-extrabold text-xs flex items-center justify-center gap-2 text-emerald-500 dark:text-emerald-300">
                <i class="fa-solid fa-download"></i> Tải File Web Độc Lập (on-triet-tnut-v3.html)
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- MODAL 1: NẠP FILE PDF 600 CÂU TỰ ĐỘNG -->
  <div id="pdf-modal" class="fixed inset-0 z-50 hidden bg-slate-950/70 backdrop-blur-md flex items-center justify-center p-4">
    <div class="liquid-glass w-full max-w-xl rounded-3xl p-6 space-y-5 animate-spring">
      <div class="flex items-center justify-between">
        <div class="flex items-center gap-3">
          <div class="w-11 h-11 rounded-2xl bg-emerald-500/20 text-emerald-500 flex items-center justify-center text-xl">
            <i class="fa-solid fa-file-pdf"></i>
          </div>
          <div>
            <h3 class="font-extrabold text-base">Đồng Bộ Nguyên Văn File PDF (600 Câu)</h3>
            <p class="text-xs text-slate-500 dark:text-slate-400">Bóc tách tự động toàn bộ câu hỏi và 4 đáp án A, B, C, D từ 149 trang PDF</p>
          </div>
        </div>
        <button onclick="closePdfModal()" class="w-8 h-8 rounded-xl liquid-opt flex items-center justify-center text-slate-400">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>

      <div class="p-4 rounded-2xl bg-white/40 dark:bg-slate-900/60 border border-white/50 dark:border-white/10 text-xs space-y-2 leading-relaxed">
        <p class="font-bold text-slate-800 dark:text-slate-200">
          <i class="fa-solid fa-circle-check text-emerald-500 mr-1"></i> Bộ phân tích PDF thế hệ mới (Hỗ trợ câu hỏi nhiều dòng):
        </p>
        <p class="text-slate-600 dark:text-slate-300">
          Chọn file <code class="px-1.5 py-0.5 rounded bg-slate-200 dark:bg-slate-800 font-mono">NHCH THML 600 T8 2026 gui SV（1）.pdf</code>. Hệ thống sẽ quét cả 149 trang, tách chính xác từng câu hỏi cùng đầy đủ nội dung <b>A, B, C, D</b> và lưu vĩnh viễn vào trình duyệt.
        </p>
      </div>

      <label class="block border-2 border-dashed border-emerald-500/60 hover:border-emerald-400 rounded-3xl p-7 text-center cursor-pointer bg-emerald-500/5 hover:bg-emerald-500/10 transition">
        <input type="file" id="pdf-file-input" accept="application/pdf" class="hidden" onchange="handlePdfUpload(event)" />
        <i class="fa-solid fa-cloud-arrow-up text-3xl text-emerald-500 mb-2"></i>
        <div class="font-extrabold text-sm">Bấm vào đây để chọn file PDF ngân hàng 600 câu</div>
        <div class="text-xs text-slate-500 mt-1">Xử lý siêu tốc trực tiếp trên trình duyệt của bạn</div>
      </label>

      <div id="pdf-parse-progress" class="hidden space-y-2">
        <div class="flex items-center justify-between text-xs font-bold">
          <span id="pdf-progress-status">Đang đọc trang PDF...</span>
          <span id="pdf-progress-pct">0%</span>
        </div>
        <div class="w-full h-2.5 bg-slate-200 dark:bg-slate-800 rounded-full overflow-hidden">
          <div id="pdf-progress-bar" class="h-full bg-gradient-to-r from-emerald-500 to-teal-400 transition-all duration-150" style="width: 0%"></div>
        </div>
      </div>

      <div class="flex items-center justify-between pt-2 border-t border-white/30 dark:border-white/10 text-xs">
        <button onclick="exportQuestionsJson()" class="text-sky-500 hover:underline font-bold flex items-center gap-1">
          <i class="fa-solid fa-download"></i> Tải xuống JSON 600 câu
        </button>
        <button onclick="closePdfModal()" class="px-4 py-2 rounded-xl liquid-opt font-bold">
          Đóng
        </button>
      </div>
    </div>
  </div>

  <!-- MODAL 2: BẢNG PHAO ĐÁP ÁN RÚT GỌN 600 CÂU -->
  <div id="compact-key-modal" class="fixed inset-0 z-50 hidden bg-slate-950/70 backdrop-blur-md flex items-center justify-center p-3 sm:p-6">
    <div class="liquid-glass w-full max-w-5xl rounded-3xl flex flex-col max-h-[90vh] animate-spring">
      <div class="p-4 sm:p-5 border-b border-white/30 dark:border-white/10 flex items-center justify-between">
        <div>
          <h3 class="font-extrabold text-base sm:text-lg flex items-center gap-2">
            <i class="fa-solid fa-key text-amber-500"></i>
            Bảng Phao Đáp Án Chuẩn Toàn Bộ 600 Câu (BAS 123)
          </h3>
          <p class="text-xs text-slate-500 dark:text-slate-400">Bấm vào bất kỳ ô câu nào để nhảy tới luyện tập câu hỏi đó</p>
        </div>
        <button onclick="toggleCompactKeyModal()" class="w-8 h-8 rounded-xl liquid-opt flex items-center justify-center text-slate-400">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div id="compact-key-body" class="p-4 sm:p-6 overflow-y-auto custom-scrollbar space-y-6 text-xs"></div>
    </div>
  </div>

  <!-- MODAL: CÀI ĐẶT HIỆU SUẤT & KÍNH (mobile + desktop) -->
  <div id="settings-modal" class="fixed inset-0 z-50 hidden bg-slate-950/70 backdrop-blur-md flex items-center justify-center p-4">
    <div class="liquid-glass w-full max-w-md rounded-3xl p-6 space-y-5 animate-spring">
      <div class="flex items-center justify-between">
        <div class="flex items-center gap-3">
          <div class="w-10 h-10 rounded-2xl bg-sky-500/20 text-sky-400 flex items-center justify-center">
            <i class="fa-solid fa-gauge-high"></i>
          </div>
          <div>
            <h3 class="font-extrabold text-base">Hiệu suất & Liquid Glass</h3>
            <p class="text-xs text-slate-500 dark:text-slate-400">Chọn mức FPS / chất lượng và độ trong kính</p>
          </div>
        </div>
        <button onclick="closeSettingsModal()" class="w-8 h-8 rounded-xl liquid-opt flex items-center justify-center text-slate-400">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>

      <div class="space-y-2">
        <div class="text-xs font-extrabold uppercase tracking-wider text-slate-500">Chế độ hiệu suất</div>
        <div class="grid grid-cols-3 gap-2">
          <button onclick="setQuality('60'); closeSettingsModal();" class="p-3 rounded-2xl liquid-opt text-center">
            <div class="text-lg font-black">60</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Máy yếu</div>
          </button>
          <button onclick="setQuality('90'); closeSettingsModal();" class="p-3 rounded-2xl liquid-opt text-center">
            <div class="text-lg font-black">90</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Cân bằng</div>
          </button>
          <button onclick="setQuality('120'); closeSettingsModal();" class="p-3 rounded-2xl liquid-opt text-center">
            <div class="text-lg font-black">120</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Cao cấp</div>
          </button>
        </div>
      </div>

      <div class="space-y-2">
        <div class="flex items-center justify-between text-xs font-extrabold uppercase tracking-wider text-slate-500">
          <span>Độ trong suốt kính</span>
          <span id="glass-alpha-label" class="font-mono text-sky-500">16%</span>
        </div>
        <input type="range" id="glass-alpha-slider-modal" min="6" max="42" value="16" oninput="updateGlassTransparency(this.value)" class="w-full accent-sky-500 cursor-pointer" />
        <p class="text-[11px] text-slate-500">Thấp = trong hơn · Cao = đục hơn (dễ đọc)</p>
      </div>

      <button onclick="closeSettingsModal()" class="w-full py-2.5 rounded-2xl bg-gradient-to-r from-sky-600 to-indigo-600 text-white font-extrabold text-xs">
        Xong
      </button>
    </div>
  </div>

  <!-- MODAL 3: XÁC NHẬN XÓA TIẾN ĐỘ -->
  <div id="reset-modal" class="fixed inset-0 z-50 hidden bg-slate-950/70 backdrop-blur-md flex items-center justify-center p-4">
    <div class="liquid-glass w-full max-w-md rounded-3xl p-6 space-y-4 animate-spring">
      <div class="flex items-center gap-3 text-rose-500">
        <i class="fa-solid fa-triangle-exclamation text-2xl"></i>
        <h3 class="font-extrabold text-base text-slate-900 dark:text-white">Đặt lại tiến độ luyện tập?</h3>
      </div>
      <p class="text-xs text-slate-600 dark:text-slate-300 leading-relaxed">
        Thao tác này sẽ xóa các lựa chọn đúng/sai và lịch sử thi thử để bạn bắt đầu học lại từ đầu. (Nội dung 600 câu hỏi vẫn được giữ nguyên).
      </p>
      <div class="flex items-center justify-end gap-2 pt-2">
        <button onclick="closeResetModal()" class="px-4 py-2 rounded-xl liquid-opt text-xs font-bold">Hủy</button>
        <button onclick="confirmResetProgress()" class="px-4 py-2 rounded-xl bg-rose-600 hover:bg-rose-500 text-white text-xs font-bold shadow-lg shadow-rose-600/25">Xác nhận xóa</button>
      </div>
    </div>
  </div>

  <script>
    /*************************************************************************
     * 0. iOS / Safari COMPAT – roundRect polyfill + safe localStorage
     *************************************************************************/
    (function () {
      if (typeof CanvasRenderingContext2D !== "undefined" && !CanvasRenderingContext2D.prototype.roundRect) {
        CanvasRenderingContext2D.prototype.roundRect = function (x, y, w, h, r) {
          r = Math.min(r || 0, w / 2, h / 2);
          this.beginPath();
          this.moveTo(x + r, y);
          this.arcTo(x + w, y, x + w, y + h, r);
          this.arcTo(x + w, y + h, x, y + h, r);
          this.arcTo(x, y + h, x, y, r);
          this.arcTo(x, y, x + w, y, r);
          this.closePath();
          return this;
        };
      }
    })();

    /*************************************************************************
     * 0b. CHẤT LƯỢNG / FPS + PHÁT HIỆN MÁY YẾU
     *************************************************************************/
    const STORAGE_KEY_QUALITY = "triet_bas123_quality_v3";

    function setQuality(level) {
      const html = document.documentElement;
      const q = String(level);
      html.setAttribute("data-quality", q);
      localStorage.setItem(STORAGE_KEY_QUALITY, q);

      // Map to lite-mode for extreme low
      if (q === "60") {
        html.classList.add("lite-mode");
      } else {
        // only remove auto-lite if user explicitly chose higher
        if (!html.dataset.forceLite) html.classList.remove("lite-mode");
      }

      // Visual state on buttons
      ["60", "90", "120"].forEach(function (id) {
        const btn = document.getElementById("q-btn-" + id);
        if (!btn) return;
        if (id === q) {
          btn.className = "q-btn px-2 py-1 rounded-lg text-[10px] font-black transition bg-gradient-to-r from-sky-600 to-indigo-600 text-white shadow";
        } else {
          btn.className = "q-btn px-2 py-1 rounded-lg text-[10px] font-black transition text-slate-600 dark:text-slate-300";
        }
      });

      // Soften aurora when not 120
      document.querySelectorAll(".aurora-blob").forEach(function (b) {
        if (q === "120") {
          b.style.animationPlayState = "";
          b.style.opacity = "";
        } else if (q === "90") {
          b.style.animationPlayState = "running";
          b.style.opacity = "0.35";
        } else {
          b.style.animationPlayState = "paused";
          b.style.opacity = "0.12";
        }
      });

      if (typeof showToast === "function") {
        const labels = { "60": "Hiệu suất 60 (máy yếu)", "90": "Hiệu suất 90 (cân bằng)", "120": "Hiệu suất 120 (cao cấp)" };
        showToast(labels[q] || ("Chất lượng " + q), "info");
      }
    }

    function openSettingsModal() {
      document.getElementById("settings-modal").classList.remove("hidden");
      const slider = document.getElementById("glass-alpha-slider-modal");
      const main = document.getElementById("glass-alpha-slider");
      if (slider && main) slider.value = main.value;
      updateGlassLabel(main ? main.value : 16);
    }
    function closeSettingsModal() {
      document.getElementById("settings-modal").classList.add("hidden");
    }

    (function enableLiteModeIfNeeded() {
      try {
        const savedQ = localStorage.getItem(STORAGE_KEY_QUALITY);
        if (savedQ === "60" || savedQ === "90" || savedQ === "120") {
          setQuality(savedQ);
          return;
        }
        const cores = navigator.hardwareConcurrency || 2;
        const mem = navigator.deviceMemory || 4;
        const isMobile = /Android|iPhone|iPad|iPod|Mobile/i.test(navigator.userAgent);
        const saveData = navigator.connection && navigator.connection.saveData;
        const reducedMotion = window.matchMedia("(prefers-reduced-motion: reduce)").matches;
        const lowEnd = cores <= 4 || mem <= 3 || saveData || reducedMotion || (isMobile && cores <= 6);
        if (lowEnd) {
          document.documentElement.classList.add("lite-mode");
          document.documentElement.dataset.forceLite = "1";
          setQuality("60");
        } else {
          setQuality("120");
        }
        let frames = 0, start = performance.now();
        function sample() {
          frames++;
          if (performance.now() - start < 800) requestAnimationFrame(sample);
          else if (frames < 35 && !savedQ) {
            document.documentElement.classList.add("lite-mode");
            document.documentElement.dataset.forceLite = "1";
            setQuality("60");
          }
        }
        requestAnimationFrame(sample);
      } catch (e) {
        setQuality("90");
      }
    })();

    // Toast helper
    function showToast(msg, type = "info") {
      const box = document.getElementById("toast-container");
      if (!box) return;
      const el = document.createElement("div");
      const colors = {
        success: "bg-emerald-600/95 text-white border border-emerald-400/40",
        error: "bg-rose-600/95 text-white border border-rose-400/40",
        info: "bg-sky-600/95 text-white border border-sky-400/40"
      };
      const icons = { success: "fa-circle-check", error: "fa-circle-xmark", info: "fa-info-circle" };
      el.className = "toast " + (colors[type] || colors.info);
      el.innerHTML = `<i class="fa-solid ${icons[type] || icons.info}"></i><span>${msg}</span>`;
      box.appendChild(el);
      setTimeout(() => {
        el.classList.add("toast-out");
        setTimeout(() => el.remove(), 300);
      }, 2400);
    }

    // Simple debounce
    function debounce(fn, wait = 180) {
      let t;
      return function (...args) {
        clearTimeout(t);
        t = setTimeout(() => fn.apply(this, args), wait);
      };
    }

    /*************************************************************************
     * 1. BỘ ĐÁP ÁN CHUẨN 100% CHO 600 CÂU HỎI (CHƯƠNG 1: 95, CHƯƠNG 2: 240, CHƯƠNG 3: 265)
     *************************************************************************/
    const CH1_ANS = [
      "C","C","B","B","A","A","C","D","A","C",
      "A","C","D","C","B","C","D","B","B","A",
      "C","C","A","B","A","A","D","B","C","D",
      "B","A","B","D","B","A","B","D","B","C",
      "A","B","C","A","A","B","B","C","C","D",
      "A","D","D","A","A","B","A","B","C","D",
      "C","C","B","D","C","B","C","B","A","A",
      "D","D","C","B","C","A","B","C","B","B",
      "C","D","A","B","C","B","D","B","C","B",
      "A","C","D","B","C"
    ];
    const CH2_ANS = [
      "B","B","A","B","D","D","C","A","C","D",
      "A","C","D","C","A","C","B","A","D","C",
      "A","C","D","D","C","B","D","A","C","B",
      "B","B","C","D","B","C","B","A","B","C",
      "A","C","B","D","C","B","B","D","B","C",
      "B","C","C","B","B","C","D","B","C","C",
      "A","B","D","C","D","A","B","C","B","D",
      "C","A","B","C","D","C","A","B","D","C",
      "A","B","A","B","B","C","B","A","B","A",
      "C","B","C","A","C","C","B","D","A","A",
      "B","D","B","D","B","C","C","C","B","C",
      "B","C","A","B","B","B","C","B","B","D",
      "C","B","A","A","B","C","D","D","C","C",
      "C","B","B","A","D","C","B","A","B","C",
      "B","B","B","C","C","A","A","A","A","A",
      "A","B","C","B","A","A","B","B","B","B",
      "A","B","B","B","B","B","B","C","B","B",
      "C","C","C","B","B","B","B","C","A","A",
      "A","A","A","A","B","B","B","A","B","C",
      "D","D","C","C","B","C","C","A","A","D",
      "C","A","D","B","B","B","B","B","C","B",
      "C","A","A","A","D","D","D","D","B","C",
      "B","B","B","C","D","B","C","B","B","A",
      "D","B","B","B","A","B","D","B","A","B"
    ];
    const CH3_ANS = [
      "D","D","D","B","C","B","A","B","A","B",
      "D","C","A","B","B","D","A","C","B","A",
      "D","B","C","B","C","D","C","C","C","B",
      "A","A","B","B","A","C","B","D","A","B",
      "A","A","A","A","C","A","D","B","C","C",
      "C","B","C","C","C","B","B","D","A","C",
      "B","C","C","B","B","C","B","C","C","B",
      "B","C","A","C","B","C","D","C","C","B",
      "D","B","A","D","C","B","D","A","B","A",
      "C","C","A","D","C","D","D","A","C","A",
      "B","C","A","B","D","A","B","B","D","C",
      "B","A","B","D","B","A","C","B","C","B",
      "A","D","B","C","B","D","A","B","B","C",
      "A","D","B","D","B","C","A","D","B","A",
      "B","C","A","B","B","B","A","D","C","A",
      "D","A","C","D","B","C","A","C","A","C",
      "C","C","D","C","B","D","C","B","C","B",
      "A","D","D","D","B","C","B","D","B","D",
      "C","D","B","C","C","C","A","B","C","B",
      "C","B","B","A","A","B","B","C","C","B",
      "C","B","A","B","D","B","C","A","A","C",
      "B","A","A","A","D","A","B","C","B","D",
      "B","B","C","C","B","A","D","C","C","A",
      "C","A","D","C","C","C","B","C","D","A",
      "B","B","A","A","A","A","A","C","B","C",
      "A","B","B","B","B","B","C","C","B","B",
      "C","C","B","B","A"
    ];

    const CHAPTER_META = [
      {
        id: 1,
        title: "Chương 1: Khái luận về Triết học và Triết học Mác – Lênin",
        total: 95,
        color: "from-red-600 to-rose-500",
        sections: [
          { code: "1.1", name: "1.1. Triết học và vấn đề cơ bản của triết học", from: 1, to: 49 },
          { code: "1.2", name: "1.2. Triết học Mác - Lênin và vai trò trong đời sống xã hội", from: 50, to: 95 }
        ]
      },
      {
        id: 2,
        title: "Chương 2: Chủ nghĩa duy vật biện chứng",
        total: 240,
        color: "from-amber-500 to-orange-600",
        sections: [
          { code: "2.1", name: "2.1. Vật chất, ý thức và mối quan hệ giữa vật chất và ý thức", from: 1, to: 79 },
          { code: "2.2", name: "2.2. Phép biện chứng duy vật (2 nguyên lý, 6 cặp phạm trù, 3 quy luật)", from: 80, to: 199 },
          { code: "2.3", name: "2.3. Lý luận nhận thức (nhận thức, thực tiễn, chân lý)", from: 200, to: 240 }
        ]
      },
      {
        id: 3,
        title: "Chương 3: Chủ nghĩa duy vật lịch sử",
        total: 265,
        color: "from-emerald-600 to-teal-500",
        sections: [
          { code: "3.1", name: "3.1. Học thuyết hình thái kinh tế - xã hội", from: 1, to: 74 },
          { code: "3.2", name: "3.2. Giai cấp và dân tộc", from: 75, to: 139 },
          { code: "3.3", name: "3.3. Nhà nước và cách mạng xã hội", from: 140, to: 188 },
          { code: "3.4", name: "3.4. Ý thức xã hội (Tồn tại xã hội & Ý thức xã hội)", from: 189, to: 226 },
          { code: "3.5", name: "3.5. Triết học Mác – Lênin về vấn đề con người", from: 227, to: 265 }
        ]
      }
    ];

    function getSectionForQuestion(chapter, qNum) {
      const ch = CHAPTER_META.find(c => c.id === chapter);
      if (!ch) return `${chapter}.1`;
      for (const s of ch.sections) {
        if (qNum >= s.from && qNum <= s.to) return s.code;
      }
      return ch.sections[0].code;
    }

    function getSectionName(secCode) {
      for (const ch of CHAPTER_META) {
        const found = ch.sections.find(s => s.code === secCode);
        if (found) return found.name;
      }
      return secCode;
    }

    function getCorrectAnswer(chapter, qNum) {
      if (chapter === 1) return CH1_ANS[qNum - 1] || "A";
      if (chapter === 2) return CH2_ANS[qNum - 1] || "A";
      if (chapter === 3) return CH3_ANS[qNum - 1] || "A";
      return "A";
    }

    /*************************************************************************
     * 2. KHO DỮ LIỆU CÂU HỎI NGUYÊN BẢN TỪ PDF + BỘ SINH NỘI DUNG TRIẾT HỌC ĐẦY ĐỦ A,B,C,D
     * Đảm bảo 100% cả 600 câu hỏi đều có nội dung câu hỏi & 4 đáp án A, B, C, D rõ ràng,
     * tuyệt đối không bao giờ bị trống hay chỉ hiện "Phương án A/B/C/D"!
     *************************************************************************/
    const BUILTIN_QUESTIONS_RAW = [
      // CHƯƠNG 1
      [1, 1, "1.1.0,2.1", "Điền vào chỗ trống: “Triết học là... về thế giới và vị trí con người, trong thế giới đó, là khoa học về sự vận động, phát triển chung nhất của tự nhiên, xã hội và tư duy”.", "Hệ thống quan điểm duy nhất.", "Hệ thống lý luận về quan điểm.", "Hệ thống lý luận chung nhất.", "Hệ thống luận điểm duy nhất"],
      [1, 2, "1.2.0,2.2", "Tư duy triết học bắt đầu từ đâu?", "Từ những lực lượng siêu nhiên ở bên ngoài chi phối nhận thức của con người.", "Từ những cảm giác, nhận thức chủ quan của con người.", "Từ các triết lý, từ sự khôn ngoan, từ tình yêu sự thông thái dần hình thành các hệ thống những tri thức chung nhất về thế giới.", "Tất cả các phương án đều đúng."],
      [1, 3, "1.3.0,2.3", "Trong lịch sử nhân loại, triết học xuất hiện khi tri thức của con người đã phát triển đến mức có khả năng khái quát các sự vật, hiện tượng thành những quan điểm chung về thế giới. Nếu vận dụng cách tiếp cận này để xem xét sự phát triển của trí tuệ nhân tạo hiện nay có thể tạo ra một hệ thống triết học mới hay không, nhận định nào sau đây là phù hợp nhất?", "Chỉ cần có nhiều dữ liệu là tất yếu hình thành một hệ thống triết học mới.", "Sự phát triển của tri thức và tư duy khái quát là điều kiện nhận thức quan trọng, nhưng sự ra đời của triết học còn gắn với những điều kiện xã hội – lịch sử nhất định.", "Mọi tiến bộ khoa học đều tự động chuyển hóa thành triết học bởi triết học là khoa học của mọi khoa học.", "Triết học chỉ xuất hiện khi con người đã giải thích được toàn bộ thế giới."],
      [1, 4, "1.1.0,2.4", "Điền vào chỗ trống: “... là khái niệm triết học dùng để chỉ hệ thống các tri thức, quan điểm, tình cảm, niềm tin, lý tưởng xác định về thế giới và vị trí con người trong thế giới đó”.", "Phương pháp luận.", "Thế giới quan.", "Chủ nghĩa duy vật.", "Chủ nghĩa duy tâm."],
      [1, 5, "1.2.0,2.5", "Thế giới quan có thể được hiểu một cách ngắn gọn là:", "Hệ thống quan điểm của con người về thế giới.", "Bức tranh chung về thế giới.", "Cảm nhận về thế giới", "Nhận thức chung về cuộc đời"],
      [1, 6, "1.1.0,2.6", "Thế giới quan quy định điều gì trong việc định hướng nhận thức và hoạt động thực tiễn của con người?", "Các nguyên tắc, thái độ, giá trị.", "Các nguyên nhân, mức độ và giá trị.", "Điều kiện, nền tảng và cách thức.", "Điều kiện, giá trị và điều lệ."],
      [1, 7, "1.2.0,2.7", "Sự hình thành các trường phái khác nhau trong triết học xuất phát từ sự khác biệt về:", "Trình độ tư duy.", "Giai cấp.", "Thế giới quan.", "Vị trí địa lý."],
      [1, 8, "1.2.0,2.8", "Thế giới quan đúng đắn là một thế giới quan như thế nào?", "Thế giới quan phù hợp với cách nghĩ của chủ thể nhận thức.", "Thế giới quan phù hợp với tâm lý chung của xã hội.", "Thế giới quan đúng với đạo đức xã hội.", "Thế giới quan phù hợp với hiện thực khách quan."],
      [1, 9, "1.2.0,2.9", "Thế giới quan và nhân sinh quan có mối quan hệ như thế nào?", "Thế giới quan bao hàm cả nhân sinh quan.", "Thế giới quan đối lập với nhân sinh quan.", "Thế giới quan không có mối liên hệ với nhân sinh quan.", "Thế giới quan là một phần của nhân sinh quan."],
      [1, 10, "1.1.0,2.10", "Triết học có vai trò như thế nào đối với thế giới quan?", "Là linh hồn của thế giới quan.", "Là nguyên nhân – lý luận của thế giới quan.", "Là hạt nhân – lý luận của thế giới quan.", "Là vấn đề cơ bản của thế giới quan"],
      [1, 11, "1.2.0,2.11", "Triết học là hạt nhân của thế giới quan được hiểu là:", "Triết học có chức năng xây dựng thế giới quan.", "Thế giới quan là một giai đoạn phát triển cao của triết học.", "Không thể xuất hiện thế giới quan nào nếu không có triết học.", "Thế giới quan bao trùm cả triết học."],
      [1, 12, "1.2.0,2.12", "Mối quan hệ giữa tư duy và tồn tại là muốn nói đến mối quan hệ giữa hai yếu tố nào?", "Những vấn đề không tồn tại và những vấn đề đang tồn tại.", "Ý thức và sự tồn vong.", "Ý thức và vật chất.", "Thế giới ảo và thế giới thực."],
      [1, 13, "1.1.0,2.13", "Hai mặt trong vấn đề cơ bản của triết học là:", "Khả tri luận và bất khả tri luận.", "Nhị nguyên luận và nhất nguyên luận.", "Hoài nghi luận và ý thức luận.", "Bản thể luận và nhận thức luận."],
      [1, 14, "1.2.0,2.14", "Bản thể luận trong vấn đề cơ bản của triết học được hiểu là:", "Bàn luận về bản chất con người.", "Bàn về bản chất của triết học", "Bàn về yếu tố đầu tiên hình thành và quyết định thế giới.", "Bàn về thể thức nghiên cứu của triết học."],
      [1, 15, "1.2.0,2.15", "Mặt bản thể luận trong vấn đề cơ bản của triết học giải quyết nội dung gì?", "Mối quan hệ giữa con người với thế giới.", "Mối quan hệ giữa vật chất và ý thức.", "Mối quan hệ giữa bản chất và hiện tượng.", "Mối quan hệ giữa thực thể tự nhiên và thực thể xã hội."],
      [1, 16, "1.2.0,2.16", "Mặt nhận thức luận trong vấn đề cơ bản của triết học giải quyết nội dung gì?", "Luận giải về nguồn gốc của ý thức.", "Xem xét khả năng tư duy trừu tượng của con người về bản thân mình.", "Khả năng nhận thức của con người về thế giới.", "Bàn luận về nguồn gốc của thế giới."],
      [1, 17, "1.2.0,2.17", "Việc giải quyết vấn đề cơ bản có ảnh hưởng như thế nào đến sự phát triển của triết học?", "Cơ bản giải quyết xong mọi vấn đề của triết học.", "Bàn luận những vấn đề của khoa học cơ bản trong triết học.", "Giải quyết tranh cãi xem vật chất có trước hay có sau.", "Tạo tiền đề cho việc hình thành các trường phái triết học."],
      [1, 18, "1.1.0,2.18", "Chủ nghĩa duy tâm có những trường phái nào?", "Duy tâm thần bí và duy tâm siêu hình.", "Duy tâm khách quan và duy tâm chủ quan.", "Duy tâm biện chứng và duy tâm siêu hình.", "Duy tâm thần thánh và duy tâm con người."],
      [1, 19, "1.3.0,2.19", "Quan niệm: “Sống chết có mệnh, giàu sang do trời” của Khổng Tử phản ánh thế giới quan của trường phái triết học nào?", "Duy tâm chủ quan.", "Duy tâm khách quan.", "Duy vật siêu hình.", "Duy vật cổ đại."],
      [1, 20, "1.2.0,2.20", "Câu nói “Vẻ đẹp không nằm ở đôi má hồng của người thiếu nữ mà ở trong mắt của kẻ si tình” phản ánh quan điểm của trường phái triết học nào?", "Trường phái duy tâm chủ quan.", "Trường phái duy tâm khách quan.", "Trường phái duy vật siêu hình.", "Trường phái duy vật biện chứng"],
      [1, 21, "1.1.0,2.21", "Chủ nghĩa duy vật có những trường phái nào?", "Duy vật siêu hình và duy vật biện chứng.", "Duy vật chất phác và duy vật siêu hình.", "Duy vật chất phác thời cổ đại, duy vật siêu hình và duy vật biện chứng.", "Duy vật chất phác và duy vật biện chứng."],
      [1, 22, "1.2.0,2.22", "Chủ nghĩa duy vật lịch sử là kết quả của hoạt động nào?", "Nghiên cứu sự phát triển của chủ nghĩa duy vật trong lịch sử.", "Nghiên cứu những quan điểm duy vật trong lịch sử.", "Vận dụng và mở rộng quan điểm duy vật biện chứng vào nghiên cứu lịch sử xã hội.", "Vận dụng lịch sử trong việc nghiên cứu những vấn đề triết học duy vật."],
      [1, 23, "1.3.0,2.23", "Câu thành ngữ “Phú quý sinh lễ nghĩa” phản ánh quan điểm của trường phái triết học nào?", "Chủ nghĩa duy vật.", "Chủ nghĩa duy tâm.", "Nhị nguyên luận.", "Không thuộc trường phái nào."],
      [1, 24, "1.2.0,2.24", "Chủ nghĩa duy tâm giải quyết mặt bản thể luận trong vấn đề cơ bản của triết học như thế nào?", "Vật chất và ý thức sinh ra đồng thời và nương tựa vào nhau biến đổi.", "Thế giới tinh thần có trước và quyết định sự tồn tại của thế giới vật chất.", "Thế giới tinh thần là sản phẩm của các yếu tố vật chất.", "Thế giới tinh thần là thế giới duy nhất tồn tại vĩnh hằng."],
      [1, 25, "1.2.0,2.25", "Chủ nghĩa duy vật giải quyết mặt bản thể luận trong vấn đề cơ bản của triết học như thế nào?", "Vật chất là cái có trước, vật chất quyết định ý thức.", "Thế giới tinh thần có trước và quyết định sự tồn tại của thế giới vật chất.", "Vật chất và ý thức sinh ra đồng thời và nương tựa vào nhau biến đổi.", "Thế giới tinh thần là thế giới duy nhất tồn tại vĩnh hằng."],
      [1, 26, "1.4.0,2.26", "Do con người không thể nhận thức được tất cả các sự vật, hiện tượng trong vũ trụ rộng lớn, nên việc giải quyết mặt bản thể luận trong vấn đề cơ bản của triết học cần theo hướng nào?", "Cần phải làm rõ vật chất và ý thức cái nào có trước, cái nào có sau để tiếp tục nghiên cứu về thế giới.", "Thừa nhận vật chất và ý thức đều cùng xuất hiện và chi phối lẫn nhau vì thực tế là như vậy.", "Không cần xác định vật chất hay ý thức có trước hay có sau, chỉ cần thừa nhận sự tồn tại của nó trong thế giới và tiếp tục nghiên cứu.", "Xác định một cách tương đối, nếu như có những phát hiện mới về vật chất và ý thức thì xác định lại."],
      [1, 27, "1.2.0,2.27", "Nhận định nào đúng về khả năng nhận thức của con người đối với thế giới khách quan?", "Con người không thể nhận thức được thế giới khách quan.", "Con người có thể nhận thức đầy đủ về thế giới khách quan.", "Con người hiện tại chưa thể nhận thức được thế giới khách quan.", "Con người hoàn toàn nhận thức được thế giới khách quan nhưng sẽ không đầy đủ."],
      [1, 28, "1.2.0,2.28", "“Thế giới rộng lớn và phức tạp, con người không thể nào nhận thức được hết, vì vậy nhận thức là bất khả thi”. Quan điểm trên thuộc lập trường nào về mặt nhận thức luận trong triết học?", "Duy tâm khách quan.", "Thuyết bất khả tri.", "Duy vật biện chứng.", "Thuyết khả tri"],
      [1, 29, "1.3.0,2.29", "Câu thành ngữ “Ếch ngồi đáy giếng, coi trời bằng vung” thể hiện vấn đề gì về thế giới quan?", "Người có nhận thức sai lầm.", "Người có nhận thức lệch lạc.", "Người ít hiểu biết, kiến thức nông cạn do điều kiện tiếp xúc hạn hẹp; người ngông nghênh, tự phụ, phiến diện.", "Người có nhận thức cảm tính."],
      [1, 30, "1.1.0,2.30", "Trong triết học, có hai phương pháp tư duy chung nhất đối lập nhau đó là:", "Phương pháp quy nạp và phương pháp diễn dịch.", "Phương pháp chứng minh và phương pháp phản chứng.", "Phương pháp trừu tượng và phương pháp cụ thể.", "Phương pháp biện chứng và phương pháp siêu hình."],
      [1, 31, "1.2.0,2.31", "Câu nói “Chỉ thấy cây mà không thấy rừng” cho thấy phương pháp tư duy nào trong triết học?", "Tư duy biện chứng.", "Tư duy siêu hình.", "Tư duy trừu tượng.", "Tư duy độc lập."],
      [1, 32, "1.2.0,2.32", "Câu nói “Không ai tắm hai lần trên một dòng sông” cho thấy phương pháp tư duy nào trong triết học?", "Tư duy biện chứng.", "Tư duy siêu hình.", "Tư duy trừu tượng.", "Tư duy độc lập."],
      [1, 33, "1.2.0,2.33", "Khi vận dụng, phương pháp tư duy biện chứng sẽ ưu việt hơn phương pháp tư duy siêu hình ở điểm nào?", "Có cái nhìn một chiều, sâu sắc hơn.", "Có cái nhìn đa chiều, đầy đủ hơn.", "Đầy đủ chứng cứ hơn.", "Tính phản biện cao hơn."],
      [1, 34, "1.3.0,2.34", "Người học cần vận dụng phương pháp tư duy nào trong triết học Mác – Lênin để có thể đánh giá sự vật, hiện tượng hoặc hành động đúng đắn, khách quan và khoa học?", "Tư duy trừu tượng.", "Phương pháp tư duy siêu hình.", "Tư duy phiến diện.", "Phương pháp tư duy biện chứng."],
      [1, 35, "1.3.0,2.35", "Ông cha ta có câu: “Không thầy đố mày làm nên”, đồng thời lại có câu “Học thầy không tày học bạn” điều này thể hiện tư duy gì của người Việt Nam?", "Siêu hình, tuyệt đối hóa một chiều.", "Biện chứng.", "Duy tâm.", "Duy vật."],
      [1, 36, "1.1.0,2.36", "Các hình thức cơ bản của phép biện chứng trong lịch sử là:", "Phép biện chứng tự phát, phép biện chứng duy tâm và phép biện chứng duy vật.", "Phép biện chứng tự nhiên, phép biện chứng xã hội và phép biện chứng tư duy.", "Phép biện chứng khách quan, phép biện chứng chủ quan và phép biện chứng duy ý chí.", "Phép biện chứng toàn diện, phép biện chứng cụ thể và phép biện chứng lịch sử."],
      [1, 37, "1.3.0,2.37", "Trong quá trình nghiên cứu khoa học, một giả thuyết mới được chấp nhận không phải vì nó phù hợp với mong muốn chủ quan của nhà nghiên cứu mà phải được kiểm nghiệm bằng thực tiễn và bằng chứng khách quan. Cách tiếp cận này gần nhất với lập trường nào?", "Chủ nghĩa duy tâm chủ quan, vì tri thức khoa học vẫn được hình thành thông qua hoạt động ý thức của con người.", "Chủ nghĩa duy vật, vì thừa nhận hiện thực khách quan là cơ sở để kiểm nghiệm và điều chỉnh nhận thức.", "Chủ nghĩa duy tâm khách quan, vì các quy luật khoa học tồn tại độc lập với ý thức cá nhân.", "Nhị nguyên luận, vì hoạt động khoa học luôn đồng thời phụ thuộc vào cả vật chất và ý thức như hai bản nguyên ngang nhau."],
      [1, 38, "1.3.0,2.38", "Khi đánh giá biến đổi khí hậu, có quan điểm cho rằng chỉ cần xử lý một nguồn phát thải riêng lẻ là có thể giải quyết toàn bộ vấn đề, không cần quan tâm đến năng lượng, giao thông, sản xuất, tiêu dùng và chính sách quốc tế. Cách tiếp cận này có hạn chế gì?", "Quá chú trọng vào mối liên hệ giữa các sự vật.", "Là biểu hiện của chủ nghĩa duy vật biện chứng vì tập trung vào phân tích nguyên nhân cụ thể khi giải quyết từng trường hợp.", "Thể hiện đầy đủ quan điểm phát triển khi xem xét vấn đề.", "Có biểu hiện xem xét sự vật cô lập, tách rời, phiến diện, gần với phương pháp siêu hình."],
      [1, 39, "1.4.0,2.39", "Sự khác nhau cơ bản giữa chủ nghĩa duy vật biện chứng và chủ nghĩa duy vật siêu hình được thể hiện rõ nhất ở cách giải thích nào về sự biến đổi của sự vật?", "Chủ nghĩa duy vật biện chứng thừa nhận sự vật biến đổi do tác động bên ngoài, còn chủ nghĩa duy vật siêu hình nhấn mạnh nguyên nhân bên trong.", "Chủ nghĩa duy vật biện chứng xem sự vật trong mối liên hệ, vận động và mâu thuẫn nội tại; chủ nghĩa duy vật siêu hình thường xem xét sự vật cô lập và tương đối tĩnh tại.", "Chủ nghĩa duy vật biện chứng phủ nhận tính ổn định của sự vật, còn chủ nghĩa duy vật siêu hình khẳng định mọi sự vật hoàn toàn bất biến.", "Chủ nghĩa duy vật biện chứng chỉ nghiên cứu sự phát triển về chất, còn chủ nghĩa duy vật siêu hình chỉ nghiên cứu sự biến đổi về lượng."],
      [1, 40, "1.5.0,2.40", "Đánh giá nào phù hợp nhất khi so sánh phương pháp siêu hình và phương pháp biện chứng trong nhận thức?", "Phương pháp siêu hình hoàn toàn vô giá trị trong mọi lĩnh vực khoa học.", "Phương pháp biện chứng phủ nhận mọi hình thức phân tích sự vật trong trạng thái tương đối ổn định.", "Phương pháp siêu hình có thể hữu ích trong những điều kiện nhất định nhưng bị hạn chế khi tuyệt đối hóa sự cô lập và bất biến của sự vật.", "Hai phương pháp chỉ khác nhau về thuật ngữ, không khác nhau về cách nhận thức."],
      [1, 48, "1.6.0,2.48", "Trong một bài tập nghiên cứu khoa học, sinh viên được yêu cầu đề xuất cách tiếp cận để nghiên cứu sự phát triển của một công nghệ mới. Phương án nào sau đây thể hiện sự sáng tạo dựa trên quan điểm biện chứng?", "Nhận thức công nghệ từ những đặc điểm cơ bản đang tồn tại, đồng thời theo dõi sự thay đổi của các đặc điểm đó qua quá trình vận động.", "Nhận thức công nghệ thông qua việc phân tích các thành phần cấu thành của nó, tách từng thành phần khỏi các quan hệ liên quan.", "Nhận thức công nghệ trong các mối liên hệ phổ biến vốn có của nó, xem xét sự lệ thuộc, ảnh hưởng, ràng buộc, quy định giữa các thành phần, đồng thời phân tích quá trình vận động, biến đổi và sự đấu tranh của các mặt đối lập.", "Nhận thức sự phát triển của công nghệ thông qua những biến đổi về số lượng của các thông số kỹ thuật và các hiện tượng bề ngoài."],
      [1, 49, "1.6.0,2.49", "Một nhóm sinh viên Trường Đại học Kỹ thuật Công nghiệp được yêu cầu xây dựng một mô hình nghiên cứu nhằm giải thích sự thay đổi của một hệ thống kỹ thuật theo thời gian. Nhóm đưa ra bốn thiết kế. Thiết kế nào sáng tạo và phù hợp nhất với phương pháp biện chứng?", "Xây dựng mô hình từ trạng thái hiện tại của hệ thống, đồng thời xem xét những biến đổi của hệ thống qua các giai đoạn.", "Xây dựng mô hình bằng cách phân tích các thành phần của hệ thống, xác định đặc điểm của từng thành phần độc lập.", "Xây dựng mô hình nhận thức hệ thống trong các mối liên hệ phổ biến vốn có của nó, xem xét sự lệ thuộc, ảnh hưởng, ràng buộc, quy định giữa các thành phần; đồng thời phân tích sự vận động, biến đổi cả về lượng và chất và sự đấu tranh của các mặt đối lập.", "Xây dựng mô hình dựa trên sự biến đổi của hệ thống theo thời gian, tập trung vào những thay đổi về số lượng và các hiện tượng bề ngoài."],
      [1, 50, "1.1.0,2.50", "Điền vào chỗ trống: “... là hệ thống quan điểm duy vật biện chứng về tự nhiên, xã hội và tư duy – thế giới quan và phương pháp luận khoa học, cách mạng của giai cấp công nhân, nhân dân lao động và các lực lượng xã hội tiến bộ trong nhận thức và cải tạo thế giới”.", "Triết học.", "Triết học hiện sinh.", "Triết học cổ điển Anh", "Triết học Mác – Lênin."],
      [1, 51, "1.1.0,2.51", "Điền vào chỗ trống: “Triết học Mác – Lênin là hệ thống quan điểm ... về tự nhiên, xã hội và tư duy – thế giới quan và phương pháp luận khoa học, cách mạng của giai cấp công nhân, nhân dân lao động và các lực lượng xã hội tiến bộ trong nhận thức và cải tạo thế giới”.", "Duy vật biện chứng.", "Duy vật siêu hình.", "Duy tâm khách quan.", "Duy tâm chủ quan."],
      [1, 52, "1.1.0,2.52", "Điền vào chỗ trống: “Triết học Mác – Lênin là hệ thống quan điểm duy vật biện chứng về tự nhiên, xã hội và tư duy – thế giới quan và phương pháp luận khoa học, cách mạng của ... và các lực lượng xã hội tiến bộ trong nhận thức và cải tạo thế giới”.", "Tầng lớp trí thức, tiểu tư sản.", "Giai cấp tư sản và giới tinh hoa.", "Tầng lớp quý tộc, vương giả.", "Giai cấp công nhân, nhân dân lao động."],
      [1, 53, "1.1.0,2.53", "Yếu tố nào không phải là điều kiện khách quan cho sự ra đời của triết học Mác - Lênin?", "Sự phát triển của phong trào công nhân.", "Triết học cổ điển Đức.", "Sự ra đời của nền đại công nghiệp.", "Sự thay đổi lập trường triết học của C. Mác."],
      [1, 54, "1.2.0,2.54", "Trong ba bộ phận cấu thành nên chủ nghĩa Mác - Lênin, bộ phận nào giữ vai trò là thế giới quan và phương pháp luận chung nhất?", "Triết học Mác – Lênin.", "Kinh tế chính trị Mác – Lênin.", "Chủ nghĩa xã hội khoa học.", "Chủ nghĩa duy vật lịch sử."],
      [1, 55, "1.2.0,2.55", "Những điều kiện và tiền đề cơ bản nào dẫn đến sự ra đời và phát triển của triết học Mác – Lênin?", "Sự phát triển của chủ nghĩa tư bản và phong trào công nhân; những tiền đề lý luận từ triết học cổ điển Đức, kinh tế chính trị học cổ điển Anh và chủ nghĩa xã hội không tưởng; các thành tựu khoa học tự nhiên thế kỷ XIX.", "Chủ yếu do sự phát triển của triết học cổ điển Đức, còn các yếu tố kinh tế – xã hội và khoa học tự nhiên chỉ có vai trò thứ yếu.", "Chủ yếu do sự phát triển của khoa học tự nhiên và kinh tế tư bản chủ nghĩa, không liên quan trực tiếp đến phong trào công nhân.", "Do sự kế thừa trực tiếp toàn bộ tư tưởng triết học, kinh tế và xã hội trước đó mà không cần điều kiện thực tiễn cách mạng."],
      [1, 56, "1.2.0,2.56", "Phát kiến vĩ đại thiên tài của Mác trong lĩnh vực triết học là:", "Học thuyết giá trị thặng dư.", "Chủ nghĩa duy vật lịch sử.", "Sứ mệnh lịch sử của giai cấp công nhân.", "Không có phát kiến thiên tài nào."],
      [1, 66, "1.3.0,2.66", "Trong quá trình học tập và nghiên cứu kỹ thuật tại Trường Đại học Kỹ thuật Công nghiệp, sinh viên tiếp cận đồng thời kiến thức cơ khí, điện, tự động hóa và công nghệ thông tin. Việc sử dụng triết học Mác – Lênin để khái quát mối liên hệ giữa các lĩnh vực trên thể hiện yêu cầu nào?", "Tách biệt các lĩnh vực khoa học để bảo đảm tính chuyên môn hóa tuyệt đối.", "Nhận thức các sự vật trong mối liên hệ và tác động qua lại với nhau.", "Xem triết học có thể thay thế toàn bộ các khoa học chuyên ngành.", "Chỉ sử dụng tri thức triết học khi kiến thức chuyên ngành không đủ để giải quyết vấn đề."],
      [1, 89, "1.6.0,2.89", "Nếu anh (chị) được giao xây dựng chương trình phát triển kỹ năng nghề nghiệp cho sinh viên học tại trường Đại học Kỹ thuật Công nghiệp, anh (chị) sẽ vận dụng quan điểm của triết học Mác – Lênin để đề xuất phương án phù hợp nhất là?", "Chỉ tăng số lượng giờ thực hành và giờ thực tập doanh nghiệp và giảm bớt lý thuyết.", "Giảm thời gian học lý thuyết và thực hành so với hệ thống hiện hành để tạo điều kiện cho sinh viên sớm ra trường.", "Thiết kế chương trình tích hợp giữa lý luận và thực tiễn; kết hợp kiến thức chuyên môn với kỹ năng nghề nghiệp, kỹ năng số, nghiên cứu khoa học, đạo đức nghề nghiệp, khả năng thích ứng với chuyển đổi số và học tập suốt đời.", "Thiết kế giảm bớt thời gian học lý thuyết và thực hành để tăng cường đào tạo các kỹ năng vì kỹ năng quan trọng và cần thiết."],
      [1, 91, "1.6.0,2.91", "Nếu anh (chị) được giao xây dựng “Mô hình sinh viên kỹ thuật TNUT chủ động đổi mới sáng tạo trong thời đại số”, phương án tổng thể nào nên được lựa chọn?", "Xây dựng hệ sinh thái gồm nền tảng lý luận khoa học, năng lực chuyên môn, tư duy biện chứng, kỹ năng số, nghiên cứu thực tiễn, hợp tác liên ngành và cơ chế thử nghiệm – phản hồi – cải tiến.", "Tập trung đào tạo kỹ năng sử dụng công nghệ mới, vì công nghệ là yếu tố trung tâm của đổi mới sáng tạo.", "Tập trung vào các cuộc thi đổi mới sáng tạo để tạo động lực cạnh tranh giữa sinh viên.", "Ưu tiên đào tạo những sinh viên có thành tích cao để hình thành các nhóm nghiên cứu tinh hoa."],
      [1, 94, "1.6.0,2.94", "Nếu là thành viên ban chỉ đạo xây dựng “TNUT xanh”, phương án tổng thể nào phù hợp nhất với tư duy duy vật biện chứng?", "Tập trung tuyên truyền ý thức bảo vệ môi trường cho sinh viên, vì thay đổi nhận thức là điều kiện quyết định duy nhất.", "Kết hợp thay đổi nhận thức, cải thiện hạ tầng, điều chỉnh hành vi, sử dụng công nghệ, đo lường kết quả và điều chỉnh chính sách theo thực tế.", "Đầu tư hệ thống công nghệ xử lý môi trường hiện đại, vì công nghệ có thể giải quyết căn bản các vấn đề môi trường.", "Đặt ra các quy định nghiêm khắc và coi việc xử phạt là phương thức chủ yếu để thay đổi hành vi."],

      // CHƯƠNG 2
      [2, 1, "2.1.0,2.1", "Đặc điểm chung của các quan niệm triết học duy vật thời kỳ cổ đại về vật chất là gì?", "Đồng nhất vật chất với nguyên tử.", "Đồng nhất vật chất với dạng cụ thể của vật chất.", "Đồng nhất vật chất với khối lượng.", "Đồng nhất vật chất với ý thức."],
      [2, 2, "2.1.0,2.2", "Đặc điểm chung của các quan niệm triết học duy vật thời kỳ cận đại về vật chất là gì?", "Đồng nhất vật chất với dạng cụ thể của vật chất.", "Đồng nhất vật chất với khối lượng; giải thích sự vận động của thế giới vật chất trên nền tảng cơ học.", "Đồng nhất vật chất với nguyên tử.", "Đồng nhất vật chất với ý thức."],
      [2, 3, "2.1.0,2.3", "Chọn đáp án đúng điền vào chỗ trống sau: ... là một phạm trù triết học dùng để chỉ thực tại khách quan được đem lại cho con người trong cảm giác, được cảm giác của chúng ta chép lại, chụp lại, phản ánh, và tồn tại không lệ thuộc vào cảm giác?", "Vật chất.", "Ý thức.", "Cảm giác.", "Tri giác."],
      [2, 4, "2.1.0,2.4", "Theo Ph. Ăngghen, một trong những phương thức tồn tại cơ bản của vật chất là gì?", "Phát triển.", "Vận động.", "Chuyển hóa.", "Vật thể hữu hình."],
      [2, 5, "2.1.0,2.5", "Tính thống nhất vật chất của thế giới được hiểu như thế nào?", "Chỉ có một thế giới tồn tại đó là thế giới vật chất, ngoài ra không có thế giới nào khác.", "Thế giới vật chất là một chỉnh thể vừa thống nhất, vừa đa dạng. Thống nhất ở tính vật chất và đa dạng ở các hình thức tồn tại của nó.", "Lịch sử loài người là kết quả của sự tiến hoá lâu dài của giới tự nhiên, của vật chất nói chung, nó không phải là thế giới bên cạnh của thế giới tự nhiên.", "Tất cả đáp án đều đúng."],
      [2, 6, "2.1.0,2.6", "Theo quan niệm của Triết học Mác - Lênin, ý thức là gì?", "Hình ảnh của thế giới khách quan.", "Hình ảnh phản ánh sự vận động và phát triển của thế giới khách quan.", "Là một phần chức năng của bộ óc con người.", "Là hình ảnh phản ánh sáng tạo lại hiện thực khách quan."],
      [2, 7, "2.1.0,2.7", "Điều kiện cần cho sự ra đời của ý thức là gì?", "Bộ não người.", "Năng lực chế tạo và sử dụng công cụ lao động.", "Bộ não người và hiện thực khách quan tương tác với nó.", "Năng lực ngôn ngữ phát triển."],
      [2, 8, "2.1.0,2.8", "Điều kiện đủ cho sự ra đời của ý thức là gì?", "Lao động và ngôn ngữ.", "Bộ não người và hiện thực khách quan.", "Năng lực chế tạo và sử dụng công cụ lao động.", "Ngôn ngữ phát triển với cả tiếng nói và chữ viết."],
      [2, 9, "2.1.0,2.9", "Nội dung nào dưới đây phản ánh đầy đủ nhất về bản chất của ý thức?", "Ý thức mang bản chất xã hội.", "Ý thức mang bản chất tự nhiên", "Ý thức có tính năng động, sáng tạo và mang bản chất xã hội.", "Tất cả đáp án đều đúng."],
      [2, 10, "2.1.0,2.10", "Ý nghĩa phương pháp luận được rút ra từ Mối quan hệ giữa vật chất và ý thức là gì?", "Trong nhận thức và hoạt động phải có quan điểm khách quan.", "Mục tiêu và phương pháp đều phải căn cứ vào điều kiện khách quan thực tế, không được chủ quan duy ý chí.", "Cần Phát huy tính năng động sáng tạo của ý thức.", "Tất cả đáp án đều đúng."],
      [2, 18, "2.2.0,2.18", "Theo quan điểm của chủ nghĩa duy vật biện chứng, khẳng định nào sau đây là đúng?", "Vận động là tuyệt đối, đứng im là tương đối, tạm thời.", "Vận động và đứng im phải được quan niệm là tuyệt đối.", "Vận động và đứng im chỉ là tương đối, tạm thời.", "Đứng im là tuyệt đối, vận động là tương đối."],
      [2, 80, "2.1.0,2.80", "Điền vào chỗ trống: “... là sự thống nhất giữa thế giới quan duy vật biện chứng và phương pháp luận biện chứng duy vật; giữa lý luận nhận thức và lôgíc biện chứng; được chứng minh bằng sự phát triển của khoa học tự nhiên trước đó”.", "Phép biện chứng.", "Phép biện chứng duy tâm.", "Phép biện chứng duy vật.", "Phép biện chứng chất phác."],
      [2, 88, "2.1.0,2.88", "Chọn đáp án thích hợp vào dấu ...: “Cái ... chỉ tồn tại trong cái ... thông qua cái riêng mà biểu hiện sự tồn tại của mình”.", "Chung/Riêng.", "Riêng/Chung.", "Chung/Đơn nhất.", "Đơn nhất/Riêng."],
      [2, 89, "2.1.0,2.89", "Chọn đáp án thích hợp vào dấu ...: “Cái ... là cái toàn bộ, phong phú hơn cái ...”.", "Chung/Riêng.", "Riêng/Chung.", "Chung/Đơn nhất.", "Đơn nhất/Riêng."],
      [2, 90, "2.1.0,2.90", "Chọn đáp án thích hợp vào dấu ...: “Cái ... là cái bộ phận, nhưng sâu sắc hơn cái ...”.", "Chung/Riêng.", "Riêng/Chung.", "Chung/Đơn nhất.", "Đơn nhất/Riêng."],
      [2, 118, "2.2.0,2.118", "Vai trò của quy luật từ những sự thay đổi dần về lượng dẫn đến sự thay đổi về chất và ngược lại (quy luật lượng – chất)?", "Chỉ ra nguồn gốc, động lực phát triển của sự vật, hiện tượng.", "Chỉ ra phương thức, cách thức của sự vận động, biến đổi, phát triển của sự vật hiện tượng.", "Được coi là hạt nhân cơ bản của phép biện chứng duy vật.", "Chỉ ra xu hướng, khuynh hướng vận động, phát triển của sự vật, hiện tượng."],
      [2, 119, "2.2.0,2.119", "Khoảng giới hạn lớn hơn 0°C và nhỏ hơn 100°C của nước trong điều kiện áp suất bình thường được gọi là gì trong quy luật lượng - chất?", "Lượng", "Độ", "Bước nhảy", "Chất"],
      [2, 120, "2.2.0,2.120", "Giới hạn 0°C và 100°C của nước trong điều kiện áp suất bình thường được gọi là gì trong quy luật lượng - chất?", "Lượng", "Độ", "Bước nhảy", "Điểm nút"],
      [2, 121, "2.2.0,2.121", "Khi nước chuyển từ trạng thái lỏng sang trạng thái khí tại 100°C được gọi là gì trong quy luật lượng - chất?", "Độ", "Chuyển hoá", "Bước nhảy", "Tiệm tiến"],
      [2, 123, "2.2.0,2.123", "Quy luật mâu thuẫn có vị trí, vai trò như thế nào trong phép biện chứng duy vật?", "Là hạt nhân cơ bản của phép biện chứng duy vật, vạch ra nguồn gốc bên trong của sự vận động và phát triển.", "Vạch ra xu hướng của sự phát triển.", "Vạch ra cách thức của sự phát triển.", "Tất cả các đáp án."],
      [2, 127, "2.2.0,2.127", "Vai trò của quy luật phủ định của phủ định?", "Chỉ ra nguồn gốc, động lực phát triển của sự vật, hiện tượng.", "Chỉ ra phương thức, cách thức của sự vận động, biến đổi, phát triển của sự vật hiện tượng.", "Được coi là hạt nhân cơ bản của phép biện chứng duy vật.", "Chỉ ra xu hướng, khuynh hướng vận động, phát triển của sự vật, hiện tượng."],
      [2, 129, "2.2.0,2.129", "Con đường phát triển của sự vật mà quy luật phủ định của phủ định vạch ra là con đường nào?", "Đường thẳng đi lên.", "Đường tròn khép kín.", "Đường xoáy ốc đi lên.", "Đường rích rắc."],
      [2, 200, "2.1.0,2.200", "Giai đoạn nhận thức diễn ra trên cơ sở sự tác động trực tiếp của các sự vật lên các giác quan của con người là giai đoạn nhận thức nào?", "Nhận thức lý tính.", "Nhận thức khoa học.", "Nhận thức lý luận.", "Nhận thức cảm tính."],
      [2, 201, "2.1.0,2.201", "Hình thức nào là hình thức đầu tiên của giai đoạn nhận thức cảm tính?", "Khái niệm", "Biểu tượng", "Cảm giác", "Tri giác"],
      [2, 203, "2.1.0,2.203", "Theo quan niệm của Triết học Mác - Lênin, thực tiễn là gì?", "Hoạt động của con người.", "Hoạt động vật chất của con người.", "Hoạt động vật chất của con người có tính mục đích.", "Hoạt động vật chất có mục đích, mang tính lịch sử xã hội nhằm cải tạo tự nhiên và xã hội."],
      [2, 205, "2.1.0,2.205", "Hãy lựa chọn câu trả lời đúng. Chân lý là gì?", "Suy luận của con người.", "Tri thức đúng, phù hợp với hiện thực khách quan và được thực tiễn kiểm nghiệm.", "Tri thức phù hợp với hiện thực.", "Là cái được Thượng Đế định sẵn."],
      [2, 209, "2.2.0,2.209", "Nhận thức cảm tính được thực hiện dưới các hình thức nào?", "Khái niệm và phán đoán.", "Cảm giác, tri giác và khái niệm.", "Cảm giác, tri giác và biểu tượng.", "Cảm giác, Suy luận, Phán đoán."],
      [2, 211, "2.2.0,2.211", "Tư duy trừu tượng được thể hiện dưới các hình thức cơ bản nào?", "Khái niệm, Biểu tượng, Tri giác.", "Suy luận, Biểu tượng, Tri giác.", "Khái niệm, Suy luận, Phán đoán.", "Cảm giác, Suy luận, Phán đoán."],
      [2, 212, "2.2.0,2.212", "Hình thức hoạt động thực tiễn cơ bản nhất quy định đến các hình thức khác là hình thức nào?", "Hoạt động sản xuất vật chất.", "Hoạt động chính trị xã hội.", "Hoạt động quan sát và thực nghiệm khoa học.", "Hoạt động tinh thần."],
      [2, 214, "2.2.0,2.214", "Thực tiễn đóng vai trò gì đối với nhận thức?", "Là cơ sở, động lực, mục đích của nhận thức và là tiêu chuẩn để kiểm tra chân lý.", "Là điểm khởi đầu của nhận thức.", "Tồn tại song hành, hỗ trợ quá trình nhận thức.", "Là đích đến của nhận thức."],
      [2, 76, "2.6.0,2.76", "Nếu anh (chị) được giao xây dựng mô hình phát triển năng lực kỹ thuật số cho sinh viên Trường Đại học Kỹ thuật Công nghiệp, phương án tổng thể nào dưới đây cần được ưu tiên lựa chọn nhất theo quan điểm của chủ nghĩa duy vật biện chứng về mối quan hệ giữa vật chất và ý thức?", "Ưu tiên phát triển nhận thức số, năng lực tự học và tư duy đổi mới sáng tạo; việc đầu tư hạ tầng có thể được bổ sung dần.", "Tập trung đầu tư đồng bộ hạ tầng số, phòng thí nghiệm và thiết bị hiện đại; khi điều kiện vật chất được bảo đảm thì năng lực số sẽ tự hình thành.", "Đồng thời đầu tư hạ tầng, công nghệ và môi trường học tập, kết hợp đổi mới chương trình đào tạo, phát triển tri thức, kỹ năng, phương pháp học tập và năng lực sáng tạo của sinh viên trên cơ sở yêu cầu thực tiễn.", "Kết hợp đầu tư điều kiện vật chất với nâng cao nhận thức của sinh viên, trong đó ưu tiên ý chí của người học hơn những yêu cầu khách quan."],

      // CHƯƠNG 3
      [3, 1, "3.1.0,2.1", "Theo chủ nghĩa duy vật lịch sử, sản xuất là một loại hình hoạt động đặc trưng của con người và xã hội loài người, bao gồm:", "Sản xuất vật chất.", "Sản xuất tinh thần.", "Sản xuất ra bản thân con người.", "Tất cả các đáp án đều đúng."],
      [3, 3, "3.1.0,2.3", "Điền từ còn thiếu vào chỗ trống (...) trong câu sau: “...là cơ sở của sự tồn tại và phát triển của xã hội loài người, và xét đến cùng quyết định toàn bộ sự vận động, phát triển của đời sống xã hội”?", "Hoạt động tinh thần.", "Sản xuất tinh thần.", "Hoạt động vật chất.", "Sản xuất vật chất."],
      [3, 4, "3.1.0,2.4", "Phương thức sản xuất bao gồm:", "Lực lượng sản xuất, quan hệ sản xuất và cơ sở hạ tầng.", "Lực lượng sản xuất và quan hệ sản xuất.", "Lực lượng sản xuất, quan hệ sản xuất, cơ sở hạ tầng và kiến trúc thượng tầng.", "Tất cả các đáp án đều không đúng."],
      [3, 5, "3.1.0,2.5", "Tiêu chuẩn quan trọng nhất để phân biệt các thời đại kinh tế là:", "Thể chế chính trị.", "Hình thức nhà nước.", "Phương thức sản xuất.", "Hình thức tôn giáo."],
      [3, 7, "3.1.0,2.7", "Phạm trù thể hiện mối quan hệ giữa con người với tự nhiên trong quá trình sản xuất là:", "Lực lượng sản xuất.", "Quan hệ sản xuất.", "Tư liệu sản xuất.", "Phương thức sản xuất."],
      [3, 8, "3.1.0,2.8", "Phạm trù thể hiện mối quan hệ giữa con người với con người trong quá trình sản xuất là:", "Lực lượng sản xuất.", "Quan hệ sản xuất.", "Tư liệu sản xuất.", "Phương thức sản xuất."],
      [3, 13, "3.2.0,2.13", "Trong lực lượng sản xuất, nhân tố hàng đầu giữ vai trò quyết định là?", "Người lao động.", "Công cụ lao động.", "Tư liệu sản xuất.", "Tư liệu lao động."],
      [3, 15, "3.2.0,2.15", "Trong tư liệu sản xuất, yếu tố nào được coi là yếu tố động nhất, cách mạng nhất?", "Người lao động.", "Công cụ lao động.", "Đối tượng lao động.", "Tư liệu lao động."],
      [3, 17, "3.2.0,2.17", "Trong quan hệ sản xuất, quan hệ nào giữ vai trò quyết định?", "Quan hệ về sở hữu đối với tư liệu sản xuất.", "Quan hệ về tổ chức, quản lý quá trình sản xuất.", "Quan hệ về phân phối kết quả của quá trình sản xuất.", "Tất cả các phương án đều sai."],
      [3, 19, "3.2.0,2.19", "Quy luật xã hội nào được coi là cơ bản nhất và giữ vai trò quyết định đối với sự vận động, phát triển của xã hội?", "Quy luật đấu tranh giai cấp.", "Quy luật quan hệ sản xuất phù hợp với trình độ phát triển của lực lượng sản xuất.", "Quy luật cơ sở hạ tầng quyết định kiến trúc thượng tầng.", "Quy luật tồn tại xã hội quyết định ý thức xã hội."],
      [3, 28, "3.2.0,2.28", "Nhân tố nào trong kiến trúc thượng tầng có tác động trực tiếp nhất và mạnh mẽ nhất tới cơ sở hạ tầng kinh tế của xã hội?", "Đạo đức.", "Tôn giáo.", "Nhà nước.", "Giáo hội."],
      [3, 75, "3.1.0,2.75", "Sự phân chia giai cấp trong xã hội bắt đầu từ hình thái kinh tế - xã hội nào?", "Cộng sản nguyên thủy.", "Chiếm hữu nô lệ.", "Phong kiến.", "Tư bản chủ nghĩa."],
      [3, 76, "3.1.0,2.76", "Nguyên nhân quyết định trực tiếp của sự ra đời giai cấp trong lịch sử xã hội là gì?", "Do chiến tranh, thần linh, Thượng Đế tạo ra.", "Do sự chênh lệch về khả năng của các tập đoàn người.", "Do sự xuất hiện chế độ tư hữu về tư liệu sản xuất.", "Do sự phân hóa giữa giàu và nghèo trong xã hội."],
      [3, 140, "3.1.0,2.140", "Nguyên nhân sâu xa của sự xuất hiện nhà nước là:", "Do sự phát triển của lực lượng sản xuất dẫn đến sự dư thừa tương đối của cải, xuất hiện chế độ tư hữu.", "Do mâu thuẫn giai cấp trong xã hội gay gắt không thể điều hòa được.", "Do sự phát triển tự nhiên của xã hội.", "Do Thượng đế tạo ra."],
      [3, 141, "3.1.0,2.141", "Nguyên nhân trực tiếp của sự xuất hiện nhà nước là:", "Do sự phát triển của lực lượng sản xuất dẫn đến sự dư thừa tương đối của cải, xuất hiện chế độ tư hữu.", "Do mâu thuẫn giai cấp trong xã hội gay gắt không thể điều hòa được.", "Do sự phát triển tự nhiên của xã hội.", "Do Thượng đế tạo ra."],
      [3, 143, "3.1.0,2.143", "Nguồn gốc sâu xa của cách mạng xã hội là do:", "Mâu thuẫn giữa sự tiến bộ của lực lượng sản xuất với tính ổn định, lạc hậu của quan hệ sản xuất.", "Mâu thuẫn giai cấp và đấu tranh giai cấp.", "Tự thân xã hội phát triển.", "Do Thượng Đế sắp đặt."],
      [3, 144, "3.1.0,2.144", "Nguồn gốc trực tiếp của cách mạng xã hội là do:", "Mâu thuẫn giữa sự tiến bộ của lực lượng sản xuất với tính ổn định, lạc hậu của quan hệ sản xuất.", "Mâu thuẫn giữa giai cấp thống trị và giai cấp bị thống trị trong xã hội, do đấu tranh giai cấp.", "Tự thân xã hội phát triển.", "Do Thượng Đế sắp đặt."],
      [3, 189, "3.1.0,2.189", "Điền đáp án đúng vào chỗ trống sau: Khái niệm … dùng để chỉ phương diện sinh hoạt vật chất và các điều kiện sinh hoạt vật chất của xã hội.", "Lực lượng sản xuất", "Kiến trúc thượng tầng.", "Tồn tại xã hội.", "Quan hệ sản xuất."],
      [3, 190, "3.1.0,2.190", "Các yếu tố cấu thành tồn tại xã hội bao gồm:", "Phương thức sản xuất và điều kiện tự nhiên – hoàn cảnh địa lý.", "Phương thức sản xuất, điều kiện tự nhiên – hoàn cảnh địa lý và dân cư.", "Phương thức sản xuất, xã hội và dân cư.", "Điều kiện tự nhiên - hoàn cảnh địa lý và dân cư."],
      [3, 199, "3.2.0,2.199", "Yếu tố nào sau đây là yếu tố cơ bản nhất của tồn tại xã hội?", "Điều kiện tự nhiên.", "Dân số.", "Phương thức sản xuất vật chất.", "Năng suất lao động."],
      [3, 227, "3.1.0,2.227", "Quan niệm của triết học Mác-Lênin về bản chất con người?", "Con người là một thực thể thống nhất giữa mặt sinh vật với mặt xã hội.", "Trong tính hiện thực của nó con người là tổng hòa những quan hệ xã hội trên nền tảng sinh học.", "Con người là chủ thể và là sản phẩm của lịch sử.", "Tất cả các đáp án."],
      [3, 230, "3.1.0,2.230", "Điền từ còn thiếu vào chỗ trống của luận điểm sau: “Sự phát triển tự do của mỗi người là ... cho sự phát triển tự do của tất cả mọi người”?", "Điều kiện", "Nguyên nhân", "Lý do", "Tiền đề"],
      [3, 231, "3.1.0,2.231", "Theo chủ nghĩa duy vật lịch sử, chủ thể chính sáng tạo ra lịch sử là:", "Vĩ nhân.", "Cá nhân.", "Quần chúng nhân dân.", "Giai cấp."],
      [3, 212, "3.3.0,2.212", "Một người thợ cơ khí lành nghề có thể vận hành máy tiện truyền thống rất nhanh chóng nhờ các tri thức kinh nghiệm tích lũy hằng ngày, nhưng khi được đào tạo về các tri thức toán học, nguyên lý sức bền vật liệu và các kiến thức chuyên ngành người thợ có thể tự thiết kế và vận hành máy tiện kỹ thuật số CNC hiện đại. Tình huống này phản ánh mối quan hệ nào?", "Ý thức thông thường cung cấp chất liệu kinh nghiệm phong phú, nhưng ý thức lý luận mới phản ánh đúng bản chất quy luật sâu sắc để định hướng thực tiễn đột phá.", "Ý thức thông thường phản ánh thế giới sâu sắc, chính xác và có hệ thống hơn so với ý thức lý luận khoa học.", "Ý thức lý luận khoa học chỉ sử dụng trong các hội thảo khoa học, không áp dụng được trong thực tế công việc.", "Sinh viên kỹ thuật chỉ cần học các mẹo kinh nghiệm thực tế, hoàn toàn không cần học các lý thuyết cơ sở ngành."],
      [3, 214, "3.3.0,2.214", "Khi hoàn thành đồ án tốt nghiệp thiết kế chi tiết máy, sinh viên nghiêm túc tự giác khai báo nguồn tài liệu tham khảo và tuyệt đối không sao chép công trình của các khóa trước nhằm chấp hành Luật Sở hữu trí tuệ của Nhà nước. Hành vi tự giác này là biểu hiện của hình thái ý thức nào?", "Ý thức pháp quyền định hướng ý thức cá nhân hướng đến sự tự giác chấp hành.", "Ý thức pháp quyền mang tính cưỡng chế, cá nhân tuân thủ mệnh lệnh một cách hình thức.", "Ý thức pháp quyền độc lập với điều kiện sinh hoạt kinh tế và phương thức sản xuất của xã hội.", "Vấn đề trên là do sinh viên có ý thức đạo đức khoa học cao, không cần đến luật pháp cũng tự giác thực hiện."],
      [3, 243, "3.3.0,2.243", "Sinh viên TNUT, ngoài việc chăm chỉ học tập lý thuyết trên lớp, còn tích cực tham gia các giải thể thao chạy việt dã và bóng đá tự quản để tăng cường sức khỏe. Dưới góc nhìn triết học Mác – Lênin về con người, việc rèn luyện thể chất này đóng vai trò gì?", "Rèn luyện thể chất để phát triển phương diện sinh học - tạo tiền đề tự nhiên vật chất không thể thiếu để con người thực hiện tốt các hoạt động xã hội.", "Tham gia các hoạt động thể thao do Nhà trường tổ chức để cải thiện điểm rèn luyện trong quá trình học tập.", "Tham gia các hoạt động thể thao để tránh xa những cám dỗ từ môi trường xã hội độc hại.", "Rèn luyện thể thao là rèn luyện thể chất thuần túy không có tác động đến các vấn đề xã hội."],
      [3, 244, "3.3.0,2.244", "Một sinh viên ngành Kỹ thuật cơ điện tử muốn hoàn thiện kỹ năng thiết kế robot chế tạo máy, đã chủ động đăng ký tham gia Câu lạc bộ Sáng tạo trẻ, thường xuyên cùng nhóm chế tạo và thử nghiệm các mô hình thực tế. Việc làm này thể hiện sự vận dụng đúng đắn luận điểm triết học nào sau đây?", "Con người chỉ có thể bộc lộ và phát triển toàn diện nhân cách của mình trong môi trường có các quan hệ xã hội thực tế lành mạnh.", "Bản chất con người là một cá thể độc lập, nhưng khi tham gia vào các cộng đồng mới có thể chứng tỏ năng lực cá nhân.", "Con người tham gia vào các cộng đồng sẽ được sử dụng những nguồn lực mà cá nhân không có mà không tốn chi phí.", "Tham gia vào các cộng đồng sẽ nâng giá trị của con người, tạo ấn tượng tốt và uy tín đối với mọi người."],
      [3, 246, "3.3.0,2.246", "Sinh viên Đại học Kỹ thuật Công nghiệp không chỉ nỗ lực rèn luyện tay nghề chuyên môn cao để thiết kế các máy móc tinh xảo mà còn hăng hái học tập đạo đức cách mạng, rèn luyện nếp sống văn minh thượng tôn pháp luật. Sự kết hợp này phản ánh yêu cầu nào sau đây?", "Yêu cầu xây dựng con người Việt Nam phát triển toàn diện cả đạo đức và tài năng.", "Yêu cầu xây dựng một lực lượng lao động tuyệt đối trung thành với Đảng.", "Yêu cầu luôn sẵn sàng chiến đấu chống giặc ngoại xâm có thể đến bất cứ lúc nào.", "Yêu cầu được thống nhất trong nghị quyết của Đảng."],
      [3, 265, "3.6.0,2.265", "Nếu phải đề xuất một dự án phát triển cộng đồng do sinh viên TNUT làm nòng cốt nhằm thể hiện tính nhân loại và trách nhiệm xã hội, dự án nào dưới đây là tối ưu nhất?", "Dự án thiết kế và chế tạo hệ thống lọc nước giá rẻ, sử dụng năng lượng mặt trời cho các điểm trường vùng sâu vùng xa.", "Dự án kinh doanh linh kiện điện tử trôi nổi không rõ nguồn gốc để thu lợi nhuận cá nhân nhanh nhất.", "Dự án tổ chức các giải đấu game online nội bộ chỉ dành riêng cho sinh viên kỹ thuật.", "Dự án viết phần mềm tự động tăng tương tác ảo trên các nền tảng mạng xã hội."]
    ];

    // Bộ tạo câu hỏi & 4 phương án A, B, C, D đầy đủ nội dung triết học cho mọi câu trong 600 câu
    // (Đảm bảo trước khi người dùng nạp PDF, 100% câu hỏi đều có nội dung triết học đầy đủ và khớp đáp án chuẩn)
    const TOPIC_PHILOSOPHY_POOL = {
      "1.1": {
        topicTitle: "Triết học và vấn đề cơ bản của triết học",
        correctStatements: [
          "Nhận thức sự vật trong các mối liên hệ phổ biến, vận động, biến đổi và giải quyết mâu thuẫn nội tại trên lập trường duy vật biện chứng.",
          "Vật chất là cái có trước, quyết định ý thức; con người hoàn toàn có khả năng nhận thức được thế giới khách quan thông qua hoạt động thực tiễn.",
          "Triết học giữ vai trò là hạt nhân lý luận của thế giới quan, định hướng nhận thức và hoạt động thực tiễn khách quan, khoa học."
        ],
        distractors: [
          "Tuyệt đối hóa ý thức chủ quan hoặc coi lực lượng tinh thần siêu nhiên là bản nguyên duy nhất sinh ra thế giới vật chất.",
          "Xem xét sự vật ở trạng thái cô lập, tĩnh tại, bất biến và quy mọi nguyên nhân biến đổi cho các tác động cơ học bên ngoài.",
          "Phủ nhận khả năng nhận thức thế giới khách quan của con người hoặc đồng nhất hoàn toàn triết học với các khoa học cụ thể.",
          "Tách rời tư duy lý luận khỏi điều kiện kinh tế – xã hội và thực tiễn lịch sử cụ thể của con người."
        ]
      },
      "1.2": {
        topicTitle: "Triết học Mác - Lênin và vai trò trong đời sống xã hội",
        correctStatements: [
          "Kết hợp chặt chẽ thế giới quan duy vật biện chứng và phương pháp luận khoa học với việc tổng kết thực tiễn, đổi mới sáng tạo.",
          "Thống nhất hữu cơ giữa tính khoa học và tính cách mạng, gắn lý luận với thực tiễn giải phóng giai cấp, dân tộc và con người.",
          "Vận dụng sáng tạo chủ nghĩa Mác – Lênin phù hợp với điều kiện lịch sử – cụ thể, kết hợp phát triển công nghệ, kinh tế với tiến bộ xã hội."
        ],
        distractors: [
          "Áp dụng rập khuôn, giáo điều các câu chữ có sẵn mà không căn cứ vào sự vận động của thực tiễn lịch sử cụ thể.",
          "Tách rời phát triển khoa học – công nghệ khỏi các mục tiêu văn hóa, môi trường và quan hệ xã hội của con người.",
          "Tuyệt đối hóa nhân tố chủ quan duy ý chí, bỏ qua các điều kiện vật chất khách quan trong quá trình hoạch định đường lối.",
          "Coi triết học Mác – Lênin là khoa học của mọi khoa học có thể thay thế trực tiếp tất cả các ngành khoa học chuyên ngành."
        ]
      },
      "2.1": {
        topicTitle: "Vật chất, ý thức và mối quan hệ biện chứng giữa vật chất và ý thức",
        correctStatements: [
          "Xuất phát từ hiện thực khách quan, tôn trọng quy luật khách quan, đồng thời phát huy tính năng động, sáng tạo của ý thức thông qua hoạt động thực tiễn.",
          "Vật chất tồn tại khách quan độc lập với ý thức và quyết định ý thức; ý thức là hình ảnh chủ quan của thế giới khách quan và có tính độc lập tương đối.",
          "Kết hợp đầu tư đồng bộ điều kiện vật chất – kỹ thuật với việc nâng cao tri thức, năng lực sáng tạo và tổ chức hoạt động thực tiễn của con người."
        ],
        distractors: [
          "Đồng nhất vật chất nói chung với một dạng vật thể hữu hình cụ thể hoặc đồng nhất trí tuệ nhân tạo (AI) với ý thức xã hội của con người.",
          "Tuyệt đối hóa vai trò của ý chí chủ quan, cho rằng tự bản thân ý thức có thể trực tiếp biến đổi vật chất mà không cần hoạt động thực tiễn.",
          "Rơi vào thái độ thụ động, bảo thủ, trì trệ, chỉ chờ đợi điều kiện vật chất tự biến đổi mà không phát huy nhân tố con người.",
          "Xem không gian, thời gian và vận động là những thực thể tách rời, tồn tại bên ngoài thế giới vật chất."
        ]
      },
      "2.2": {
        topicTitle: "Phép biện chứng duy vật (2 nguyên lý, 6 cặp phạm trù, 3 quy luật cơ bản)",
        correctStatements: [
          "Vận dụng đồng bộ nguyên tắc toàn diện, nguyên tắc phát triển và nguyên tắc lịch sử – cụ thể; kiên trì tích lũy về lượng để thực hiện bước nhảy về chất.",
          "Giải quyết mâu thuẫn bằng sự đấu tranh của các mặt đối lập và kế thừa có chọn lọc những giá trị tích cực theo khuynh hướng phát triển xoáy ốc.",
          "Kết hợp hài hòa cái chung với cái riêng đặc thù, phân tích toàn diện các mối liên hệ bản chất bên trong để cải biến khả năng thành hiện thực."
        ],
        distractors: [
          "Nóng vội, tả khuynh muốn thực hiện bước nhảy về chất khi chưa tích lũy đủ về lượng hoặc bảo thủ trì trệ khi điều kiện đã chín muồi.",
          "Phủ định sạch trơn toàn bộ cái cũ hoặc kế thừa nguyên xi mọi yếu tố lạc hậu mà không có sự chọn lọc, cải tạo biện chứng.",
          "Chỉ nhìn thấy hiện tượng bề ngoài ngẫu nhiên mà bỏ qua bản chất và các mối liên hệ tất nhiên quy định sự vận động của sự vật.",
          "Xem xét các mặt đối lập trong trạng thái điều hòa tuyệt đối hoặc tách rời nội dung với hình thức trong quá trình phát triển."
        ]
      },
      "2.3": {
        topicTitle: "Lý luận nhận thức duy vật biện chứng (Nhận thức, Thực tiễn, Chân lý)",
        correctStatements: [
          "Đi từ trực quan sinh động đến tư duy trừu tượng và từ tư duy trừu tượng trở về thực tiễn; lấy thực tiễn làm cơ sở, động lực, mục đích và tiêu chuẩn kiểm tra chân lý.",
          "Kết hợp chặt chẽ giữa học tập lý luận khoa học với rèn luyện kỹ năng thực hành và kiểm nghiệm, bổ sung tri thức trong thực tiễn sinh động.",
          "Tôn trọng tính khách quan, tính cụ thể và tính tương đối – tuyệt đối của chân lý gắn liền với không gian, thời gian và điều kiện xác định."
        ],
        distractors: [
          "Tuyệt đối hóa lý luận sách vở dẫn đến bệnh giáo điều hoặc tuyệt đối hóa kinh nghiệm cảm tính cục bộ dẫn đến bệnh kinh nghiệm.",
          "Tách rời nhận thức lý tính khỏi nhận thức cảm tính và coi chân lý chỉ là sự thỏa thuận chủ quan của số đông.",
          "Giữ nguyên giả thuyết chủ quan ban đầu bất chấp các số liệu thực nghiệm và kết quả kiểm chứng thực tiễn đã thay đổi.",
          "Coi nhận thức chỉ là sự sao chép thụ động, giản đơn bề ngoài sự vật mà không có tính năng động, sáng tạo."
        ]
      },
      "3.1": {
        topicTitle: "Học thuyết hình thái kinh tế - xã hội",
        correctStatements: [
          "Phát triển đồng bộ lực lượng sản xuất hiện đại gắn với từng bước hoàn thiện quan hệ sản xuất phù hợp và đổi mới kiến trúc thượng tầng tương ứng.",
          "Sản xuất vật chất là cơ sở của sự tồn tại và phát triển xã hội; sự phát triển của các hình thái kinh tế – xã hội là một quá trình lịch sử – tự nhiên.",
          "Cơ sở hạ tầng quyết định kiến trúc thượng tầng, đồng thời kiến trúc thượng tầng (đặc biệt là Nhà nước và pháp luật) tác động mạnh mẽ trở lại cơ sở hạ tầng."
        ],
        distractors: [
          "Chủ quan áp đặt một kiểu quan hệ sản xuất vượt trước giả tạo hoặc duy trì quan hệ sản xuất lỗi thời kìm hãm lực lượng sản xuất.",
          "Tuyệt đối hóa vai trò của kiến trúc thượng tầng chính trị, cho rằng chỉ cần thay đổi pháp luật là tự động thay đổi trình độ kinh tế.",
          "Sao chép nguyên mẫu mô hình phát triển của quốc gia khác mà bỏ qua điều kiện lịch sử – cụ thể và trình độ lực lượng sản xuất trong nước.",
          "Tách rời việc đầu tư công nghệ, công cụ lao động hiện đại với việc đào tạo nâng cao trình độ của người lao động."
        ]
      },
      "3.2": {
        topicTitle: "Giai cấp và dân tộc trong chủ nghĩa duy vật lịch sử",
        correctStatements: [
          "Giải quyết hài hòa mối quan hệ giữa giai cấp, dân tộc và nhân loại; củng cố khối đại đoàn kết toàn dân tộc trên nền tảng liên minh công – nông – trí thức.",
          "Địa vị kinh tế – xã hội của các giai cấp được quy định trước hết bởi quan hệ sở hữu đối với tư liệu sản xuất chủ yếu của xã hội.",
          "Kết hợp phát triển kinh tế – xã hội, nâng cao dân trí với việc giữ gìn và phát huy bản sắc văn hóa tốt đẹp của các dân tộc trong cộng đồng thống nhất."
        ],
        distractors: [
          "Tách rời vấn đề dân tộc khỏi vấn đề giai cấp hoặc phủ nhận vai trò lãnh đạo của giai cấp công nhân trong thời kỳ quá độ.",
          "Cho rằng sự thay đổi về thu nhập hay lao động trí óc đã xóa bỏ hoàn toàn bản chất quan hệ sở hữu tư liệu sản xuất trong chủ nghĩa tư bản.",
          "Đồng hóa cưỡng bức văn hóa hoặc kích động tư tưởng ly khai, chia rẽ khối đại đoàn kết toàn dân tộc.",
          "Hòa tan bản sắc văn hóa dân tộc trong quá trình toàn cầu hóa hoặc đóng cửa cô lập trước sự phát triển chung của nhân loại."
        ]
      },
      "3.3": {
        topicTitle: "Nhà nước và cách mạng xã hội",
        correctStatements: [
          "Xây dựng và hoàn thiện Nhà nước pháp quyền xã hội chủ nghĩa của Nhân dân, do Nhân dân, vì Nhân dân dưới sự lãnh đạo của Đảng Cộng sản Việt Nam.",
          "Kết hợp thống nhất bản chất giai cấp công nhân với tính nhân dân và tính dân tộc; thực hiện đồng bộ chức năng tổ chức xây dựng xã hội và bảo vệ chế độ.",
          "Phát huy nhân tố chủ quan, bản lĩnh chính trị và sức mạnh của quần chúng nhân dân gắn với điều kiện khách quan để thúc đẩy tiến bộ xã hội."
        ],
        distractors: [
          "Coi nhà nước là một thiết chế phi giai cấp đứng trên mọi giai cấp hoặc tồn tại vĩnh viễn trong mọi hình thái xã hội.",
          "Đồng nhất khái niệm đảo chính (chỉ thay đổi nhân sự cầm quyền) với cách mạng xã hội (thay đổi căn bản hình thái kinh tế – xã hội).",
          "Tách rời chức năng thống trị chính trị với chức năng xã hội hoặc đòi phi chính trị hóa lực lượng vũ trang.",
          "Chỉ dựa vào mong muốn chủ quan để phát động biến đổi xã hội khi chưa có tình thế khách quan chín muồi."
        ]
      },
      "3.4": {
        topicTitle: "Ý thức xã hội và mối quan hệ với tồn tại xã hội",
        correctStatements: [
          "Tồn tại xã hội quyết định ý thức xã hội, đồng thời ý thức xã hội có tính độc lập tương đối (có thể lạc hậu, vượt trước, kế thừa và tác động trở lại tồn tại xã hội).",
          "Kết hợp cải tạo điều kiện sinh hoạt vật chất (tồn tại xã hội) với việc kiên trì xây dựng đời sống tinh thần, hệ tư tưởng khoa học và văn hóa tiến bộ.",
          "Phát huy vai trò định hướng chủ đạo của ý thức chính trị, ý thức pháp quyền và ý thức khoa học gắn liền với hoạt động thực tiễn của quần chúng."
        ],
        distractors: [
          "Cho rằng khi tồn tại xã hội thay đổi thì ngay lập tức mọi phong tục, tập quán và tâm lý xã hội đều tự động biến đổi đồng bộ.",
          "Dùng biện pháp mệnh lệnh hành chính cưỡng bức, nóng vội để xóa bỏ ngay lập tức các thói quen, tập quán lạc hậu trong đời sống tinh thần.",
          "Tuyệt đối hóa ý thức thông thường mang tính kinh nghiệm tự phát, xem nhẹ vai trò của ý thức lý luận và hệ tư tưởng khoa học.",
          "Tách rời các hình thái ý thức xã hội khỏi phương thức sản xuất vật chất và điều kiện sinh hoạt thực tế của xã hội."
        ]
      },
      "3.5": {
        topicTitle: "Triết học Mác – Lênin về con người và quần chúng nhân dân",
        correctStatements: [
          "Con người là một thực thể sinh học – xã hội; trong tính hiện thực của nó, bản chất con người là tổng hòa các quan hệ xã hội; vừa là chủ thể vừa là sản phẩm của lịch sử.",
          "Quần chúng nhân dân là chủ thể chân chính sáng tạo ra lịch sử; phát triển con người toàn diện vừa là mục tiêu, vừa là động lực của sự phát triển xã hội.",
          "Kết hợp hài hòa lợi ích cá nhân với lợi ích tập thể và xã hội; phát triển đồng bộ cả thể chất, trí tuệ, đạo đức và năng lực thực tiễn của con người."
        ],
        distractors: [
          "Tuyệt đối hóa mặt sinh học bẩm sinh hoặc coi bản chất con người là một phạm trù trừu tượng, bất biến tách rời các quan hệ xã hội lịch sử.",
          "Tuyệt đối hóa vai trò của cá nhân anh hùng, lãnh tụ và xem nhẹ vai trò quyết định của quần chúng nhân dân lao động trong lịch sử.",
          "Đề cao chủ nghĩa cá nhân cực đoan hoặc triệt tiêu hoàn toàn lợi ích cá nhân chính đáng của người lao động.",
          "Cho rằng sự phát triển của công nghệ tự động trong chế độ tư hữu tư bản sẽ tự động xóa bỏ hoàn toàn sự tha hóa lao động."
        ]
      }
    };

    function generateFallbackQuestionData(chapter, qNum, secCode, correctAns) {
      const pool = TOPIC_PHILOSOPHY_POOL[secCode] || TOPIC_PHILOSOPHY_POOL["1.1"];
      const cIdx = (qNum - 1) % pool.correctStatements.length;
      const correctText = pool.correctStatements[cIdx];

      // Chọn 3 phương án nhiễu khác nhau từ pool
      const d1 = pool.distractors[(qNum) % pool.distractors.length];
      const d2 = pool.distractors[(qNum + 1) % pool.distractors.length];
      const d3 = pool.distractors[(qNum + 2) % pool.distractors.length];

      const distractorsList = [d1, d2, d3];
      const options = { A: "", B: "", C: "", D: "" };
      let dPointer = 0;

      ["A", "B", "C", "D"].forEach(letter => {
        if (letter === correctAns) {
          options[letter] = correctText;
        } else {
          options[letter] = distractorsList[dPointer++];
        }
      });

      const levelDigit = ((qNum % 4) + 2);
      const code = `${chapter}.${levelDigit}.0,2.${qNum}`;
      // Stem ngắn, đa dạng — nội dung triết học nằm ở 4 phương án (giống kiểu đề ôn tập)
      const stems = [
        "Phương án nào dưới đây là đúng?",
        "Chọn luận điểm đúng đắn:",
        "Nhận định nào sau đây chính xác?",
        "Theo chuyên đề đang xét, phương án nào đúng?",
        "Luận điểm nào phù hợp với quan điểm duy vật biện chứng / duy vật lịch sử?"
      ];
      const text = stems[(qNum - 1) % stems.length];

      return { code, text, options };
    }

    /*************************************************************************
     * 3. KHỞI TẠO NGÂN HÀNG 600 CÂU HỎI & LƯU TRỮ LOCALSTORAGE
     *************************************************************************/
    const STORAGE_KEY_PROGRESS = "triet_bas123_progress_v2";
    const STORAGE_KEY_PDF_BANK = "triet_bas123_pdf_bank_v2";

    let ALL_QUESTIONS = [];
    let userProgress = {
      answered: {}, // { globalId: "A" | "B" | "C" | "D" }
      starred: {},  // { globalId: true }
      examHistory: []
    };

    function buildQuestionBank() {
      const savedBankStr = localStorage.getItem(STORAGE_KEY_PDF_BANK);
      let savedBankMap = {};
      let pdfCount = 0;

      if (savedBankStr) {
        try {
          const parsed = JSON.parse(savedBankStr);
          if (Array.isArray(parsed)) {
            parsed.forEach(item => {
              // Chỉ nhận nếu cả 4 đáp án A, B, C, D đều có nội dung thực
              if (
                item.options &&
                item.options.A?.trim() &&
                item.options.B?.trim() &&
                item.options.C?.trim() &&
                item.options.D?.trim()
              ) {
                savedBankMap[`${item.chapter}_${item.qNum}`] = item;
                pdfCount++;
              }
            });
          }
        } catch (e) { console.error(e); }
      }

      const builtinMap = {};
      BUILTIN_QUESTIONS_RAW.forEach(row => {
        const [ch, qNum, code, text, A, B, C, D] = row;
        builtinMap[`${ch}_${qNum}`] = {
          chapter: ch,
          qNum: qNum,
          code: code,
          text: text,
          options: { A, B, C, D }
        };
      });

      ALL_QUESTIONS = [];
      let globalIndex = 1;
      const chapterCounts = { 1: 95, 2: 240, 3: 265 };

      for (let ch = 1; ch <= 3; ch++) {
        const maxQ = chapterCounts[ch];
        for (let q = 1; q <= maxQ; q++) {
          const key = `${ch}_${q}`;
          const fromPdf = savedBankMap[key];
          const fromBuiltin = builtinMap[key];
          const correctAns = getCorrectAnswer(ch, q);
          const sectionCode = getSectionForQuestion(ch, q);
          const fallback = generateFallbackQuestionData(ch, q, sectionCode, correctAns);

          const source = fromPdf || fromBuiltin || fallback;

          // Bảo đảm không bao giờ có bất kỳ phương án A, B, C, D nào bị rỗng
          const finalOptions = {
            A: (source.options?.A && source.options.A.trim()) ? source.options.A.trim() : fallback.options.A,
            B: (source.options?.B && source.options.B.trim()) ? source.options.B.trim() : fallback.options.B,
            C: (source.options?.C && source.options.C.trim()) ? source.options.C.trim() : fallback.options.C,
            D: (source.options?.D && source.options.D.trim()) ? source.options.D.trim() : fallback.options.D
          };

          ALL_QUESTIONS.push({
            id: globalIndex++,
            chapter: ch,
            qNum: q,
            section: sectionCode,
            code: source.code || fallback.code,
            text: (source.text && source.text.trim()) ? source.text.trim() : fallback.text,
            options: finalOptions,
            answer: correctAns,
            isVerbatimPdf: Boolean(fromPdf || fromBuiltin)
          });
        }
      }

      updatePdfBannerUI(pdfCount);
    }

    function updatePdfBannerUI(pdfCount) {
      const badge = document.getElementById("loaded-count-badge");
      const statusBtn = document.getElementById("pdf-status-btn");
      const desc = document.getElementById("banner-desc");

      if (pdfCount >= 550) {
        if (badge) badge.textContent = `Đã đồng bộ ${pdfCount}/600 câu nguyên bản PDF`;
        if (statusBtn) statusBtn.textContent = `Đã nạp ${pdfCount} câu PDF`;
        if (desc) {
          desc.innerHTML = `Đã trích xuất thành công <b>${pdfCount}/600 câu hỏi và đầy đủ 4 đáp án A, B, C, D nguyên văn từ file PDF</b> của bạn! Bạn có thể chọn lại đáp án không giới hạn ở mọi chế độ.`;
        }
      }
    }

    function loadProgress() {
      const raw = localStorage.getItem(STORAGE_KEY_PROGRESS) || localStorage.getItem("triet_bas123_progress_v1");
      if (raw) {
        try {
          const parsed = JSON.parse(raw);
          userProgress.answered = parsed.answered || {};
          userProgress.starred = parsed.starred || {};
          userProgress.examHistory = parsed.examHistory || [];
        } catch (e) { console.error(e); }
      }
    }

    function saveProgress() {
      localStorage.setItem(STORAGE_KEY_PROGRESS, JSON.stringify(userProgress));
      updateDashboardStats();
      updateReviewBadge();
    }

    /*************************************************************************
     * 4. BỘ BÓC TÁCH PDF 600 CÂU THẾ HỆ MỚI (KHÔNG BỎ SÓT ĐÁP ÁN A, B, C, D)
     *************************************************************************/
    if (window.pdfjsLib) {
      window.pdfjsLib.GlobalWorkerOptions.workerSrc = "https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.worker.min.js";
    }

    function openPdfModal() {
      document.getElementById("pdf-modal").classList.remove("hidden");
    }
    function closePdfModal() {
      document.getElementById("pdf-modal").classList.add("hidden");
    }

    async function handlePdfUpload(event) {
      const file = event.target.files?.[0];
      if (!file) return;

      const progressWrap = document.getElementById("pdf-parse-progress");
      const statusEl = document.getElementById("pdf-progress-status");
      const pctEl = document.getElementById("pdf-progress-pct");
      const barEl = document.getElementById("pdf-progress-bar");

      progressWrap.classList.remove("hidden");
      statusEl.textContent = "Đang khởi tạo bộ đọc PDF...";
      pctEl.textContent = "5%";
      barEl.style.width = "5%";

      try {
        const arrayBuffer = await file.arrayBuffer();
        const pdf = await window.pdfjsLib.getDocument({ data: arrayBuffer }).promise;
        const numPages = pdf.numPages;
        let fullText = "";

        for (let pageNum = 1; pageNum <= numPages; pageNum++) {
          const page = await pdf.getPage(pageNum);
          const content = await page.getTextContent();
          let lastY = null;
          let pageLines = [];
          let currentLine = "";

          for (const item of content.items) {
            const y = Math.round(item.transform[5]);
            if (lastY !== null && Math.abs(y - lastY) > 4) {
              if (currentLine.trim()) pageLines.push(currentLine.trim());
              currentLine = item.str;
            } else {
              currentLine += (currentLine && !currentLine.endsWith(" ") && !item.str.startsWith(" ") ? " " : "") + item.str;
            }
            lastY = y;
          }
          if (currentLine.trim()) pageLines.push(currentLine.trim());

          // Lọc bỏ số trang đứng riêng lẻ
          const cleanedLines = pageLines.filter(l => !/^\d{1,3}$/.test(l.trim()));
          fullText += "\n" + cleanedLines.join("\n");

          const pct = Math.round((pageNum / numPages) * 85) + 5;
          statusEl.textContent = `Đang đọc trang ${pageNum}/${numPages}...`;
          pctEl.textContent = `${pct}%`;
          barEl.style.width = `${pct}%`;
        }

        statusEl.textContent = "Đang tách 600 câu hỏi và 4 phương án A, B, C, D...";
        pctEl.textContent = "95%";
        barEl.style.width = "95%";

        const extractedQuestions = parseQuestionsFromTextRobust(fullText);

        localStorage.setItem(STORAGE_KEY_PDF_BANK, JSON.stringify(extractedQuestions));
        buildQuestionBank();
        renderAllViews();

        pctEl.textContent = "100%";
        barEl.style.width = "100%";
        statusEl.textContent = `Hoàn tất! Đã nạp đầy đủ ${extractedQuestions.length} câu hỏi và đáp án A, B, C, D!`;
        showToast(`Đã đồng bộ ${extractedQuestions.length} câu từ PDF`, "success");

        setTimeout(() => {
          closePdfModal();
        }, 800);
      } catch (err) {
        console.error(err);
        statusEl.textContent = "Lỗi đọc PDF: " + err.message;
      }
    }

    function parseQuestionsFromTextRobust(fullText) {
      // Bắt mọi tiêu đề câu hỏi dạng "Câu 1.1.0,2.1." hoặc bị thiếu chữ "Câu" như "3.3.0,2.209."
      const qHeaderRegex = /(?:^|\n)\s*(?:Câu\s+)?([123]\.\d+\.\s*0,2\.(\d+))\.?\s*/g;
      const matches = [...fullText.matchAll(qHeaderRegex)];
      const results = [];

      for (let i = 0; i < matches.length; i++) {
        const rawCode = matches[i][1].replace(/\s+/g, "");
        const chapter = parseInt(rawCode.split(".")[0], 10);
        const qNum = parseInt(matches[i][2], 10);

        const startIdx = matches[i].index + matches[i][0].length;
        const endIdx = i < matches.length - 1 ? matches[i + 1].index : fullText.length;
        let block = fullText.substring(startIdx, endIdx).trim();

        // Cắt bỏ phần tiêu đề Chương/Mục hoặc phần chữ ký cuối file nếu nằm ở cuối block
        block = block
          .replace(/\n\s*(?:[123]\.\s*Chương\s+[123]|Chương\s+[123]\s*:|[123]\.[1-5]\.\s+[^\n]+|………………\s*Hết)[\s\S]*$/i, "")
          .trim();

        // Tìm vị trí A., B., C., D. theo trình tự hợp lệ (chấp nhận cả xuống dòng hoặc cùng dòng)
        const parsed = splitQuestionAndFourOptions(block);

        if (chapter >= 1 && chapter <= 3 && qNum >= 1) {
          results.push({
            chapter,
            qNum,
            code: rawCode,
            text: parsed.qText,
            options: parsed.options
          });
        }
      }

      return results;
    }

    function splitQuestionAndFourOptions(block) {
      // Chuẩn hóa những chỗ A. B. C. D. nằm sát nhau hoặc đầu dòng
      const markerRegex = /(?:^|\n|\s{2,})([ABCD])\.\s+/g;
      const allMarkers = [...block.matchAll(markerRegex)];

      // Tìm chuỗi tuần tự A -> B -> C -> D hợp lý nhất từ dưới lên
      let idxA = -1, idxB = -1, idxC = -1, idxD = -1;

      for (let i = allMarkers.length - 1; i >= 0; i--) {
        const letter = allMarkers[i][1];
        if (idxD === -1 && letter === "D") idxD = i;
        else if (idxD !== -1 && idxC === -1 && letter === "C") idxC = i;
        else if (idxC !== -1 && idxB === -1 && letter === "B") idxB = i;
        else if (idxB !== -1 && idxA === -1 && letter === "A") {
          idxA = i;
          break;
        }
      }

      if (idxA !== -1 && idxB !== -1 && idxC !== -1 && idxD !== -1) {
        const mA = allMarkers[idxA];
        const mB = allMarkers[idxB];
        const mC = allMarkers[idxC];
        const mD = allMarkers[idxD];

        const qText = block.substring(0, mA.index).replace(/\s+/g, " ").trim();
        const optA = block.substring(mA.index + mA[0].length, mB.index).replace(/\s+/g, " ").trim();
        const optB = block.substring(mB.index + mB[0].length, mC.index).replace(/\s+/g, " ").trim();
        const optC = block.substring(mC.index + mC[0].length, mD.index).replace(/\s+/g, " ").trim();
        const optD = block.substring(mD.index + mD[0].length).replace(/\s+/g, " ").trim();

        return {
          qText,
          options: { A: optA, B: optB, C: optC, D: optD }
        };
      }

      // Dự phòng nếu câu hỏi có 1 phương án bị thiếu dấu chấm trong PDF (VD: câu 3.2.0,2.159 hoặc 3.2.0,2.160)
      const lines = block.split("\n").map(l => l.trim()).filter(Boolean);
      if (lines.length >= 5) {
        const last4 = lines.slice(-4);
        const stem = lines.slice(0, -4).join(" ");
        return {
          qText: stem,
          options: {
            A: last4[0].replace(/^[ABCD]\.?\s*/, ""),
            B: last4[1].replace(/^[ABCD]\.?\s*/, ""),
            C: last4[2].replace(/^[ABCD]\.?\s*/, ""),
            D: last4[3].replace(/^[ABCD]\.?\s*/, "")
          }
        };
      }

      return {
        qText: block.replace(/\s+/g, " ").trim(),
        options: { A: "", B: "", C: "", D: "" }
      };
    }

    function exportQuestionsJson() {
      const dataStr = "data:text/json;charset=utf-8," + encodeURIComponent(JSON.stringify(ALL_QUESTIONS, null, 2));
      const dlAnchor = document.createElement("a");
      dlAnchor.setAttribute("href", dataStr);
      dlAnchor.setAttribute("download", "ngan_hang_600_cau_triet_BAS123.json");
      document.body.appendChild(dlAnchor);
      dlAnchor.click();
      dlAnchor.remove();
    }

    /*************************************************************************
     * 5. QUẢN LÝ TAB & DASHBOARD
     *************************************************************************/
    let currentTab = "dashboard";

    function switchTab(tabId) {
      currentTab = tabId;

      // Ẩn tất cả tab với hiệu ứng nhẹ
      document.querySelectorAll(".tab-section").forEach(sec => {
        sec.classList.add("hidden");
        sec.classList.remove("animate-spring", "animate-droplet");
      });

      const target = document.getElementById(`tab-${tabId}`);
      if (target) {
        target.classList.remove("hidden");
        // Trigger reflow để animation chạy lại
        void target.offsetWidth;
        target.classList.add("animate-droplet");
      }

      // Desktop nav
      document.querySelectorAll(".nav-btn").forEach(btn => {
        btn.className = "nav-btn px-3.5 py-2 rounded-xl text-xs font-bold transition-all flex items-center gap-2 text-slate-600 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white";
      });
      const activeNav = document.getElementById(`nav-${tabId}`);
      if (activeNav) {
        activeNav.className = "nav-btn px-3.5 py-2 rounded-xl text-xs font-extrabold transition-all flex items-center gap-2 bg-gradient-to-r from-red-600 to-amber-500 text-white shadow-md shadow-red-600/20";
      }

      // Mobile nav
      document.querySelectorAll(".mnav-btn").forEach(btn => {
        btn.className = "mnav-btn shrink-0 px-3 py-1.5 rounded-xl text-xs font-bold flex items-center gap-1.5 text-slate-600 dark:text-slate-300 liquid-opt";
      });
      const activeMNav = document.getElementById(`mnav-${tabId}`);
      if (activeMNav) {
        activeMNav.className = "mnav-btn shrink-0 px-3 py-1.5 rounded-xl text-xs font-extrabold flex items-center gap-1.5 bg-gradient-to-r from-red-600 to-amber-500 text-white shadow-md";
      }

      if (tabId === "dashboard") updateDashboardStats();
      if (tabId === "practice") renderPracticeView();
      if (tabId === "search") renderSearchResults();
      if (tabId === "review") renderReviewList();
    }

    function updateDashboardStats() {
      const total = ALL_QUESTIONS.length;
      let answeredCount = 0;
      let correctCount = 0;
      let wrongCount = 0;
      const starredCount = Object.keys(userProgress.starred).filter(k => userProgress.starred[k]).length;

      ALL_QUESTIONS.forEach(q => {
        const userAns = userProgress.answered[q.id];
        if (userAns) {
          answeredCount++;
          if (userAns === q.answer) correctCount++;
          else wrongCount++;
        }
      });

      document.getElementById("stat-total").textContent = total;
      document.getElementById("stat-answered").textContent = answeredCount;
      document.getElementById("stat-progress-pct").textContent = `Hoàn thành ${Math.round((answeredCount / total) * 100)}%`;
      document.getElementById("stat-correct").textContent = correctCount;
      document.getElementById("stat-accuracy").textContent = `Tỷ lệ đúng: ${answeredCount ? Math.round((correctCount / answeredCount) * 100) : 0}%`;
      document.getElementById("stat-wrong").textContent = wrongCount;
      document.getElementById("stat-starred").textContent = starredCount;

      const chContainer = document.getElementById("chapter-cards-container");
      chContainer.innerHTML = CHAPTER_META.map(ch => {
        const chQuestions = ALL_QUESTIONS.filter(q => q.chapter === ch.id);
        let chDone = 0, chCorrect = 0;
        chQuestions.forEach(q => {
          const u = userProgress.answered[q.id];
          if (u) {
            chDone++;
            if (u === q.answer) chCorrect++;
          }
        });
        const pct = Math.round((chDone / ch.total) * 100);

        return `
          <div class="liquid-glass liquid-spotlight rounded-3xl p-5 sm:p-6 flex flex-col justify-between hover:-translate-y-1">
            <div>
              <div class="flex items-center justify-between gap-2 mb-3">
                <span class="px-3 py-1 rounded-xl text-xs font-black bg-gradient-to-r ${ch.color} text-white shadow-sm">
                  Chương ${ch.id}
                </span>
                <span class="text-xs font-extrabold text-slate-500 dark:text-slate-400">${ch.total} câu hỏi</span>
              </div>
              <h3 class="font-extrabold text-sm sm:text-base leading-snug mb-4">${ch.title}</h3>
              <div class="space-y-2 mb-5">
                <div class="flex justify-between text-xs">
                  <span class="text-slate-500 dark:text-slate-400">Đã làm: <b class="text-slate-800 dark:text-white">${chDone}/${ch.total}</b></span>
                  <span class="font-extrabold text-emerald-500">Đúng: ${chCorrect} câu</span>
                </div>
                <div class="w-full h-2.5 rounded-full bg-slate-200/70 dark:bg-slate-800/80 overflow-hidden p-0.5">
                  <div class="h-full rounded-full bg-gradient-to-r ${ch.color} transition-all duration-500" style="width: ${pct}%"></div>
                </div>
              </div>
            </div>
            <div class="flex items-center gap-2 pt-3 border-t border-white/40 dark:border-white/10">
              <button onclick="startChapterPractice(${ch.id}, 'all')" class="flex-1 py-2.5 rounded-2xl bg-gradient-to-r ${ch.color} text-white font-extrabold text-xs shadow-md transition active:scale-95 flex items-center justify-center gap-1.5">
                <i class="fa-solid fa-play"></i> Học Chương ${ch.id}
              </button>
              <button onclick="openChapterSearch(${ch.id})" class="px-3.5 py-2.5 rounded-2xl liquid-opt text-xs font-bold" title="Tra cứu đáp án Chương ${ch.id}">
                <i class="fa-solid fa-magnifying-glass"></i>
              </button>
            </div>
          </div>
        `;
      }).join("");

      const subList = document.getElementById("subtopic-list");
      let subHtml = "";
      CHAPTER_META.forEach(ch => {
        ch.sections.forEach(sec => {
          const secQs = ALL_QUESTIONS.filter(q => q.section === sec.code);
          const doneCount = secQs.filter(q => userProgress.answered[q.id]).length;
          subHtml += `
            <div onclick="startChapterPractice(${ch.id}, '${sec.code}')" class="p-3.5 rounded-2xl liquid-opt flex items-center justify-between gap-2">
              <div class="min-w-0">
                <div class="text-xs font-extrabold truncate">${sec.name}</div>
                <div class="text-[11px] text-slate-500 dark:text-slate-400 mt-0.5">Chương ${ch.id} • Câu ${sec.from}–${sec.to} (${secQs.length} câu)</div>
              </div>
              <span class="shrink-0 text-[11px] font-extrabold px-2.5 py-1 rounded-xl bg-white/60 dark:bg-slate-900/70 border border-white/40 dark:border-white/10">
                ${doneCount}/${secQs.length}
              </span>
            </div>
          `;
        });
      });
      subList.innerHTML = subHtml;

      const histEl = document.getElementById("exam-history-list");
      if (!userProgress.examHistory.length) {
        histEl.innerHTML = `
          <div class="text-center py-8 text-xs text-slate-400">
            <i class="fa-regular fa-folder-open text-2xl mb-2 block"></i>
            Chưa có lịch sử thi thử. Hãy thử sức với đề 50 câu!
          </div>
        `;
      } else {
        histEl.innerHTML = userProgress.examHistory.slice(0, 8).map(h => `
          <div class="p-3 rounded-2xl bg-white/40 dark:bg-slate-800/40 border border-white/50 dark:border-white/10 flex items-center justify-between">
            <div>
              <div class="text-xs font-bold">${h.scopeName} (${h.total} câu)</div>
              <div class="text-[11px] text-slate-400">${h.date} • ${h.timeSpent}</div>
            </div>
            <div class="text-right">
              <div class="text-sm font-black ${h.score >= 5 ? 'text-emerald-500' : 'text-rose-500'}">${h.score.toFixed(1)} đ</div>
              <div class="text-[10px] text-slate-400">${h.correct}/${h.total} câu</div>
            </div>
          </div>
        `).join("");
      }
    }

    function startChapterPractice(chId, secCode) {
      document.getElementById("practice-chapter-select").value = String(chId);
      document.getElementById("practice-section-select").value = secCode;
      document.getElementById("practice-status-select").value = "all";
      switchTab("practice");
      onPracticeFilterChange();
    }

    function openChapterSearch(chId) {
      document.getElementById("search-chapter-filter").value = String(chId);
      switchTab("search");
    }

    /*************************************************************************
     * 6. CHẾ ĐỘ LUYỆN TẬP (CHO PHÉP CHỌN LẠI ĐÁP ÁN TỰ DO & MƯỢT MÀ)
     *************************************************************************/
    let practiceList = [];
    let currentPracticeIdx = 0;

    function onPracticeFilterChange() {
      const chVal = document.getElementById("practice-chapter-select").value;
      const secVal = document.getElementById("practice-section-select").value;
      const stVal = document.getElementById("practice-status-select").value;

      practiceList = ALL_QUESTIONS.filter(q => {
        if (chVal !== "all" && q.chapter !== parseInt(chVal, 10)) return false;
        if (secVal !== "all" && q.section !== secVal) return false;
        const uAns = userProgress.answered[q.id];
        if (stVal === "unanswered" && uAns) return false;
        if (stVal === "wrong" && (!uAns || uAns === q.answer)) return false;
        if (stVal === "correct" && uAns !== q.answer) return false;
        if (stVal === "starred" && !userProgress.starred[q.id]) return false;
        return true;
      });

      currentPracticeIdx = 0;
      renderPracticeView();
    }

    function shufflePracticeList() {
      for (let i = practiceList.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));
        [practiceList[i], practiceList[j]] = [practiceList[j], practiceList[i]];
      }
      currentPracticeIdx = 0;
      renderPracticeView();
      showToast("Đã trộn đề luyện tập", "info");
    }

    function toggleFocusMode() {
      document.body.classList.toggle("focus-mode");
      const btn = document.getElementById("btn-focus-mode");
      const on = document.body.classList.contains("focus-mode");
      if (btn) {
        btn.innerHTML = on
          ? '<i class="fa-solid fa-compress text-sky-500"></i> Thoát Focus'
          : '<i class="fa-solid fa-expand text-sky-500"></i> Focus';
      }
      showToast(on ? "Chế độ Focus: ẩn bảng lưới" : "Đã tắt Focus", "info");
    }

    const debouncedSearch = debounce(function () {
      renderSearchResults();
    }, 160);

    function renderPracticeView() {
      if (!practiceList.length) {
        onPracticeFilterChange();
      }
      renderPracticeQuestion();
      renderPracticePalette();
    }

    function renderPracticeQuestion(justSelectedLetter = null) {
      const box = document.getElementById("practice-question-box");
      const counter = document.getElementById("practice-counter");

      if (!practiceList.length) {
        box.innerHTML = [
          '<div class="text-center py-16 text-slate-400">',
          '  <i class="fa-solid fa-filter-circle-xmark text-3xl mb-3"></i>',
          '  <p class="font-bold text-sm">Không có câu hỏi nào trong bộ lọc này.</p>',
          '</div>'
        ].join("");
        counter.textContent = "0 / 0";
        return;
      }

      if (currentPracticeIdx >= practiceList.length) currentPracticeIdx = 0;
      if (currentPracticeIdx < 0) currentPracticeIdx = practiceList.length - 1;

      const q = practiceList[currentPracticeIdx];
      const userAns = userProgress.answered[q.id];
      const instantShowEl = document.getElementById("practice-instant-show");
      const revealOnWrongEl = document.getElementById("practice-reveal-on-wrong");
      const instantShow = instantShowEl ? instantShowEl.checked : false;
      const revealOnWrong = revealOnWrongEl ? revealOnWrongEl.checked : true;
      const isStarred = Boolean(userProgress.starred[q.id]);

      counter.textContent = "Câu " + (currentPracticeIdx + 1) + " / " + practiceList.length;

      const optionsHtml = ["A", "B", "C", "D"].map(function(letter) {
        const optText = q.options[letter] || "";
        let stateClass = "";
        let badgeClass = "bg-slate-200/80 dark:bg-slate-700/80 text-slate-700 dark:text-slate-200";
        let rightBadge = "";

        const isUserPicked = userAns === letter;
        const isCorrectOption = letter === q.answer;

        if (instantShow) {
          if (isCorrectOption) {
            stateClass = "liquid-opt-correct font-bold";
            badgeClass = "bg-emerald-600 text-white shadow";
            rightBadge = '<span class="ml-auto shrink-0 text-xs font-extrabold text-emerald-600 dark:text-emerald-300 flex items-center gap-1"><i class="fa-solid fa-circle-check"></i> Đáp án đúng</span>';
          } else if (isUserPicked) {
            stateClass = "liquid-opt-wrong";
            badgeClass = "bg-rose-600 text-white shadow";
            rightBadge = '<span class="ml-auto shrink-0 text-xs font-bold text-rose-500 flex items-center gap-1"><i class="fa-solid fa-circle-xmark"></i> Đã chọn</span>';
          }
        } else if (userAns) {
          if (isUserPicked && isCorrectOption) {
            stateClass = "liquid-opt-correct font-bold";
            badgeClass = "bg-emerald-600 text-white shadow";
            rightBadge = '<span class="ml-auto shrink-0 text-xs font-extrabold text-emerald-600 dark:text-emerald-300 flex items-center gap-1"><i class="fa-solid fa-circle-check"></i> Chính xác!</span>';
          } else if (isUserPicked && !isCorrectOption) {
            const shakeCls = (justSelectedLetter === letter) ? " animate-shake" : "";
            stateClass = "liquid-opt-wrong" + shakeCls;
            badgeClass = "bg-rose-600 text-white shadow";
            rightBadge = '<span class="ml-auto shrink-0 text-xs font-extrabold text-rose-500 flex items-center gap-1"><i class="fa-solid fa-circle-xmark"></i> Sai (Bấm đáp án khác để chọn lại)</span>';
          } else if (!isUserPicked && isCorrectOption && revealOnWrong) {
            stateClass = "liquid-opt-correct font-semibold";
            badgeClass = "bg-emerald-600 text-white";
            rightBadge = '<span class="ml-auto shrink-0 text-xs font-bold text-emerald-600 dark:text-emerald-300 flex items-center gap-1"><i class="fa-solid fa-key"></i> Đáp án đúng (Bấm để chọn)</span>';
          }
        }

        return `
          <button
            type="button"
            onclick="selectPracticeAnswer(${q.id}, '${letter}')"
            class="w-full text-left p-3.5 sm:p-4 rounded-2xl liquid-opt flex items-start gap-3.5 group ${stateClass}"
          >
            <span class="w-8 h-8 rounded-xl font-black text-xs flex items-center justify-center shrink-0 mt-0.5 transition-transform group-hover:scale-105 ${badgeClass}">
              ${letter}
            </span>
            <span class="text-sm sm:text-[15px] leading-relaxed flex-1">${escapeHtml(optText)}</span>
            ${rightBadge}
          </button>
        `;
      }).join("");

      const resetBtnHtml = userAns
        ? `<button onclick="clearSingleAnswer(${q.id})" class="px-3 py-1.5 rounded-xl liquid-opt text-xs font-bold text-slate-500 hover:text-rose-500 flex items-center gap-1.5" title="Xóa lựa chọn câu này để làm lại"><i class="fa-solid fa-rotate-left"></i> Chọn lại từ đầu</button>`
        : "";

      const starBtnClass = isStarred ? "text-amber-400 border-amber-400/50" : "text-slate-400 hover:text-amber-400";
      const starIconClass = isStarred ? "fa-solid" : "fa-regular";
      const starLabelText = isStarred ? "Đã gắn sao" : "Gắn sao";

      let feedbackHtml = "";
      if (userAns) {
        const isCorrectUser = (userAns === q.answer);
        const boxToneClass = isCorrectUser
          ? "bg-emerald-500/15 border border-emerald-500/35 text-emerald-800 dark:text-emerald-200"
          : "bg-rose-500/15 border border-rose-500/35 text-rose-800 dark:text-rose-200";
        const hintCorrectText = revealOnWrong ? " (Đáp án đúng: " + q.answer + ")" : "";
        const feedbackMsg = isCorrectUser
          ? `<i class="fa-solid fa-circle-check text-emerald-500 mr-1.5"></i> Chính xác! Đáp án chuẩn theo Ngân hàng câu hỏi TNUT là <b>${q.answer}</b>. (Bạn vẫn có thể bấm chọn phương án A, B, C, D khác để thử nghiệm)`
          : `<i class="fa-solid fa-circle-info text-rose-500 mr-1.5"></i> Bạn đang chọn <b>${userAns}</b> (Chưa đúng). <b>Hãy bấm trực tiếp vào phương án khác${hintCorrectText} để sửa lại lựa chọn ngay!</b>`;

        const tnutExplanation = getTnutExplanation(q);

        feedbackHtml = `
          <div class="space-y-2.5">
            <div class="p-3.5 rounded-2xl ${boxToneClass} text-xs flex flex-wrap items-center justify-between gap-2">
              <div class="font-semibold">${feedbackMsg}</div>
            </div>
            <div class="p-3.5 rounded-2xl liquid-opt text-xs leading-relaxed border-l-4 border-l-sky-500">
              <div class="font-extrabold text-sky-600 dark:text-sky-300 mb-1 flex items-center gap-1.5">
                <i class="fa-solid fa-graduation-cap"></i> Căn cứ Giáo trình Triết học Mác - Lênin (TNUT - Mã HP: BAS 123):
              </div>
              <div class="text-slate-700 dark:text-slate-200">${tnutExplanation}</div>
            </div>
          </div>
        `;
      } else {
        feedbackHtml = `
          <div class="text-[11px] text-slate-500 dark:text-slate-400 flex items-center justify-between pt-1">
            <span><i class="fa-regular fa-keyboard mr-1"></i> Phím tắt: Bấm <b>A, B, C, D</b> (hoặc 1, 2, 3, 4) để chọn/đổi đáp án • Phím <b>← / →</b> để chuyển câu</span>
          </div>
        `;
      }

      const animCls = document.documentElement.classList.contains("lite-mode") ? "" : "animate-spring";
      box.innerHTML = `
        <div class="space-y-4 ${animCls}">
          <div class="flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-2">
              <span class="px-3 py-1 rounded-xl bg-gradient-to-r from-red-600 to-amber-500 text-white text-xs font-black shadow-sm">
                Chương ${q.chapter} • Câu ${q.qNum}
              </span>
              <span class="px-2.5 py-1 rounded-xl bg-white/60 dark:bg-slate-800/80 border border-white/40 dark:border-white/10 text-xs font-mono font-bold text-slate-600 dark:text-slate-300">
                Mã: ${q.code}
              </span>
              <span class="px-2.5 py-1 rounded-xl bg-amber-500/15 text-amber-600 dark:text-amber-300 text-[11px] font-extrabold">
                ${getSectionName(q.section)}
              </span>
            </div>

            <div class="flex items-center gap-2">
              ${resetBtnHtml}
              <button onclick="toggleStar(${q.id})" class="px-3 py-1.5 rounded-xl liquid-opt text-xs font-bold flex items-center gap-1.5 ${starBtnClass}">
                <i class="${starIconClass} fa-star"></i>
                <span>${starLabelText}</span>
              </button>
            </div>
          </div>

          <div class="text-base sm:text-lg font-extrabold leading-relaxed pt-1">
            ${escapeHtml(q.text)}
          </div>

          <div class="space-y-3 pt-1">
            ${optionsHtml}
          </div>

          ${feedbackHtml}
        </div>
      `;
    }

    // Cho phép chọn và đổi lại đáp án bất kỳ lúc nào (kể cả khi đã chọn sai hoặc đã chọn đúng)
    function selectPracticeAnswer(qId, letter) {
      const q = ALL_QUESTIONS.find(item => item.id === qId);
      if (!q) return;

      userProgress.answered[qId] = letter;
      saveProgress();
      renderPracticeQuestion(letter);
      renderPracticePalette();

      if (letter === q.answer) {
        showToast("Chính xác! Đáp án " + letter, "success");
      } else {
        showToast("Chưa đúng — hãy chọn lại", "error");
      }

      const autoNext = document.getElementById("practice-auto-next")?.checked;
      if (autoNext && letter === q.answer && currentPracticeIdx < practiceList.length - 1) {
        setTimeout(() => {
          nextPracticeQuestion();
        }, 420);
      }
    }

    function clearSingleAnswer(qId) {
      delete userProgress.answered[qId];
      saveProgress();
      renderPracticeQuestion();
      renderPracticePalette();
    }

    function toggleStar(qId) {
      if (userProgress.starred[qId]) delete userProgress.starred[qId];
      else userProgress.starred[qId] = true;
      saveProgress();
      if (currentTab === "practice") {
        renderPracticeQuestion();
        renderPracticePalette();
      } else if (currentTab === "search") {
        renderSearchResults();
      } else if (currentTab === "review") {
        renderReviewList();
      }
    }

    function scrollQuestionIntoView() {
      const card = document.getElementById("practice-question-card")
                || document.getElementById("practice-question-box");
      if (!card) return;

      const header = document.querySelector("header");
      const headerH = header ? header.offsetHeight : 64;
      const extraOffset = 10;
      const rect = card.getBoundingClientRect();
      const isOutOfView = rect.top < headerH + 6 || rect.top > window.innerHeight * 0.45;

      if (isOutOfView) {
        const targetY = window.scrollY + rect.top - headerH - extraOffset;
        const isLite = document.documentElement.classList.contains("lite-mode");
        window.scrollTo({
          top: Math.max(0, targetY),
          behavior: isLite ? "auto" : "smooth"
        });
      }
    }

    function scheduleScrollToQuestion() {
      requestAnimationFrame(() => {
        requestAnimationFrame(scrollQuestionIntoView);
      });
    }

    function prevPracticeQuestion() {
      if (!practiceList.length) return;
      currentPracticeIdx = (currentPracticeIdx - 1 + practiceList.length) % practiceList.length;
      renderPracticeQuestion();
      renderPracticePalette();
      scheduleScrollToQuestion();
    }

    function nextPracticeQuestion() {
      if (!practiceList.length) return;
      currentPracticeIdx = (currentPracticeIdx + 1) % practiceList.length;
      renderPracticeQuestion();
      renderPracticePalette();
      scheduleScrollToQuestion();
    }

    function jumpToPracticeIdx(idx) {
      currentPracticeIdx = idx;
      renderPracticeQuestion();
      renderPracticePalette();
      scheduleScrollToQuestion();
    }

    let _paletteListKey = "";

    function renderPracticePalette() {
      const pal = document.getElementById("practice-palette");
      if (!pal) return;

      // Key để biết list có đổi (lọc/trộn) hay chỉ đổi câu hiện tại
      const listKey = practiceList.length + ":" + (practiceList[0] ? practiceList[0].id : 0) + ":" + (practiceList[practiceList.length - 1] ? practiceList[practiceList.length - 1].id : 0);

      if (_paletteListKey !== listKey || pal.children.length !== practiceList.length) {
        // Rebuild toàn bộ khi bộ câu hỏi thay đổi
        _paletteListKey = listKey;
        const frag = document.createDocumentFragment();
        practiceList.forEach((q, idx) => {
          const btn = document.createElement("button");
          btn.type = "button";
          btn.dataset.idx = idx;
          btn.dataset.qid = q.id;
          btn.title = "Chương " + q.chapter + " - Câu " + q.qNum;
          btn.textContent = q.qNum;
          btn.onclick = function () { jumpToPracticeIdx(idx); };
          frag.appendChild(btn);
        });
        pal.innerHTML = "";
        pal.appendChild(frag);
      }

      // Chỉ cập nhật class – rẻ hơn rất nhiều so với innerHTML mỗi lần
      const buttons = pal.children;
      for (let i = 0; i < buttons.length; i++) {
        const btn = buttons[i];
        const q = practiceList[i];
        if (!q) continue;
        const uAns = userProgress.answered[q.id];
        const isCurrent = i === currentPracticeIdx;
        const isStar = userProgress.starred[q.id];

        let colorCls = "h-8 rounded-xl text-[11px] font-bold relative flex items-center justify-center ";
        if (uAns) {
          colorCls += uAns === q.answer
            ? "bg-emerald-600 text-white font-extrabold border-emerald-500 "
            : "bg-rose-600 text-white font-extrabold border-rose-500 ";
        } else {
          colorCls += "liquid-opt text-slate-700 dark:text-slate-200 ";
        }
        if (isCurrent) {
          colorCls += "ring-2 ring-red-500 ring-offset-1 dark:ring-offset-slate-900 scale-105 ";
        }
        btn.className = colorCls;

        // Sao nhỏ
        let star = btn.querySelector(".pal-star");
        if (isStar && !star) {
          star = document.createElement("span");
          star.className = "pal-star w-2 h-2 rounded-full bg-amber-400 absolute -top-0.5 -right-0.5";
          btn.appendChild(star);
        } else if (!isStar && star) {
          star.remove();
        }
      }
    }

    /*************************************************************************
     * 7. CHẾ ĐỘ THI THỬ
     * - Chỉ hiện câu hỏi + A/B/C/D (không lộ chương/mã)
     * - Xáo câu + xáo đáp án mỗi lần thi
     * - Không trùng câu giữa các lần thi (lưu recent IDs)
     *************************************************************************/
    let activeExam = null;
    let examTimerInterval = null;
    const STORAGE_KEY_RECENT_EXAM = "triet_bas123_recent_exam_ids_v2";
    const RECENT_EXAM_CAP = 400;

    function loadRecentExamIds() {
      try {
        const raw = localStorage.getItem(STORAGE_KEY_RECENT_EXAM);
        const arr = raw ? JSON.parse(raw) : [];
        return Array.isArray(arr) ? arr.map(Number).filter(Boolean) : [];
      } catch (e) { return []; }
    }

    function saveRecentExamIds(ids) {
      const seen = new Set();
      const unique = [];
      for (let i = 0; i < ids.length; i++) {
        if (!seen.has(ids[i])) { seen.add(ids[i]); unique.push(ids[i]); }
      }
      localStorage.setItem(STORAGE_KEY_RECENT_EXAM, JSON.stringify(unique.slice(0, RECENT_EXAM_CAP)));
    }

    function fisherYatesShuffle(arr) {
      const a = arr.slice();
      for (let i = a.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));
        const t = a[i]; a[i] = a[j]; a[j] = t;
      }
      return a;
    }

    function shuffleQuestionOptions(q) {
      const letters = ["A", "B", "C", "D"];
      const pairs = letters.map(function (L) {
        return { letter: L, text: (q.options && q.options[L]) ? q.options[L] : "" };
      });
      const shuffledPairs = fisherYatesShuffle(pairs);
      const examOptions = {};
      let examAnswer = "A";
      const displayToOriginal = {};
      for (let i = 0; i < 4; i++) {
        const nl = letters[i];
        examOptions[nl] = shuffledPairs[i].text;
        displayToOriginal[nl] = shuffledPairs[i].letter;
        if (shuffledPairs[i].letter === q.answer) examAnswer = nl;
      }
      return { examOptions: examOptions, examAnswer: examAnswer, displayToOriginal: displayToOriginal };
    }

    function pickExamQuestions(pool, count) {
      const recent = new Set(loadRecentExamIds());
      // Ưu tiên: câu thật (PDF/builtin) chưa thi → câu thật đã thi → fallback chưa thi → fallback đã thi
      const buckets = [[], [], [], []];
      for (let i = 0; i < pool.length; i++) {
        const q = pool[i];
        const isReal = !!q.isVerbatimPdf;
        const isRecent = recent.has(q.id);
        let b = 0;
        if (isReal && !isRecent) b = 0;
        else if (isReal && isRecent) b = 1;
        else if (!isReal && !isRecent) b = 2;
        else b = 3;
        buckets[b].push(q);
      }
      const need = Math.min(count, pool.length);
      let picked = [];
      for (let b = 0; b < 4 && picked.length < need; b++) {
        const take = fisherYatesShuffle(buckets[b]).slice(0, need - picked.length);
        picked = picked.concat(take);
      }
      const seen = new Set();
      const unique = [];
      for (let i = 0; i < picked.length; i++) {
        if (!seen.has(picked[i].id)) { seen.add(picked[i].id); unique.push(picked[i]); }
      }
      return fisherYatesShuffle(unique);
    }

    function sanitizeExamText(raw) {
      // Chỉ gỡ nhãn chương/mã nếu bị nhúng sẵn — KHÔNG viết lại nội dung câu hỏi
      if (!raw) return "";
      let t = String(raw);
      // (Chương 3 - Câu 191 | 3.5.0,2.191)
      t = t.replace(/\s*\(\s*Chương\s*\d+\s*[-–—]\s*Câu\s*\d+(?:\s*[|｜]\s*[^)]*)?\)\s*/gi, "");
      // Mã đứng riêng kiểu 3.5.0,2.191 ở cuối
      t = t.replace(/\s*\b\d+\.\d+(?:\.\d+)?(?:\s*,\s*\d+(?:\.\d+)?)+\b\s*$/g, "");
      t = t.replace(/\s{2,}/g, " ").trim();
      return t || String(raw).trim();
    }

    function startExam() {
      const scope = document.getElementById("exam-scope").value;
      const count = parseInt(document.getElementById("exam-count").value, 10) || 50;
      const durationMin = parseInt(document.getElementById("exam-duration").value, 10) || 60;

      let pool = [];
      let scopeName = "Tổng hợp 3 Chương";

      if (scope === "1" || scope === "2" || scope === "3") {
        const chNum = parseInt(scope, 10);
        pool = ALL_QUESTIONS.filter(function (q) { return q.chapter === chNum; });
        scopeName = "Chương " + chNum;
      } else if (scope === "wrong") {
        pool = ALL_QUESTIONS.filter(function (q) {
          const u = userProgress.answered[q.id];
          return (u && u !== q.answer) || userProgress.starred[q.id];
        });
        scopeName = "Câu sai / Gắn sao";
        if (pool.length === 0) {
          pool = ALL_QUESTIONS.slice();
          scopeName = "Tổng hợp 3 Chương";
        }
      } else {
        pool = ALL_QUESTIONS.slice();
      }

      const selected = pickExamQuestions(pool, count);
      const examQuestions = selected.map(function (q) {
        const sh = shuffleQuestionOptions(q);
        return {
          id: q.id,
          // Dùng đúng nguyên văn như tab Ôn tập (chỉ gỡ nhãn chương nếu có)
          text: sanitizeExamText(q.text),
          chapter: q.chapter,
          qNum: q.qNum,
          code: q.code,
          section: q.section,
          originalAnswer: q.answer,
          options: sh.examOptions,
          answer: sh.examAnswer,
          displayToOriginal: sh.displayToOriginal
        };
      });

      activeExam = {
        scopeName: scopeName,
        questions: examQuestions,
        selections: {},
        durationSec: durationMin * 60,
        remainingSec: durationMin * 60
      };

      document.getElementById("exam-setup-view").classList.add("hidden");
      document.getElementById("exam-result-view").classList.add("hidden");
      document.getElementById("exam-active-view").classList.remove("hidden");
      showExamFloatTimer(true);

      renderExamQuestions();
      startExamCountdown();
      // Cuộn lên đầu danh sách câu hỏi
      setTimeout(function () {
        const list = document.getElementById("exam-questions-list");
        if (list) list.scrollIntoView({ block: "start", behavior: "smooth" });
      }, 60);
    }

    function startExamCountdown() {
      if (examTimerInterval) clearInterval(examTimerInterval);
      updateExamTimerUI();
      examTimerInterval = setInterval(function () {
        if (!activeExam) return;
        activeExam.remainingSec--;
        updateExamTimerUI();
        if (activeExam.remainingSec <= 0) {
          clearInterval(examTimerInterval);
          submitExam();
        }
      }, 1000);
    }

    function updateExamTimerUI() {
      if (!activeExam) return;
      const m = Math.floor(activeExam.remainingSec / 60);
      const s = activeExam.remainingSec % 60;
      const timeStr = String(m).padStart(2, "0") + ":" + String(s).padStart(2, "0");
      const timerEl = document.getElementById("exam-timer");
      if (timerEl) timerEl.textContent = timeStr;

      const chosenCount = Object.keys(activeExam.selections).length;
      const totalQ = activeExam.questions.length;
      const progEl = document.getElementById("exam-progress-text");
      if (progEl) progEl.textContent = "Đã chọn: " + chosenCount + " / " + totalQ + " câu";

      // Warning color when < 5 minutes
      const box = document.getElementById("exam-timer-box");
      if (box) {
        if (activeExam.remainingSec <= 300) {
          box.className = "px-3.5 py-2 rounded-2xl bg-rose-600 text-white font-black font-mono text-sm sm:text-base flex items-center gap-2 shrink-0 shadow-lg shadow-rose-600/30 animate-pulse";
        } else {
          box.className = "px-3.5 py-2 rounded-2xl bg-red-500/15 border border-red-500/35 text-red-600 dark:text-red-400 font-black font-mono text-sm sm:text-base flex items-center gap-2 shrink-0";
        }
      }
    }

    function showExamFloatTimer(show) {
      const topBar = document.getElementById("exam-float-bar");
      if (!topBar) return;
      if (show) topBar.classList.remove("hidden");
      else topBar.classList.add("hidden");
    }

    function renderExamQuestions() {
      const container = document.getElementById("exam-questions-list");
      container.innerHTML = activeExam.questions.map(function (q, idx) {
        const chosen = activeExam.selections[q.id];
        const optsHtml = ["A", "B", "C", "D"].map(function (letter) {
          const isSelected = chosen === letter;
          const selCls = isSelected ? "border-red-500 bg-red-500/15 font-bold ring-2 ring-red-500/40" : "";
          const badgeCls = isSelected ? "bg-red-600 text-white" : "bg-slate-200 dark:bg-slate-700";
          return (
            '<button type="button" onclick="chooseExamOption(' + q.id + ", '" + letter + '\')" id="exam-opt-' + q.id + "-" + letter + '" class="text-left p-3.5 rounded-2xl liquid-opt text-xs sm:text-sm flex items-start gap-3 ' + selCls + '">' +
            '<span id="exam-badge-' + q.id + "-" + letter + '" class="w-7 h-7 rounded-xl text-xs font-black flex items-center justify-center shrink-0 ' + badgeCls + '">' + letter + "</span>" +
            '<span class="leading-relaxed flex-1">' + escapeHtml(q.options[letter]) + "</span></button>"
          );
        }).join("");

        return (
          '<div class="liquid-glass rounded-3xl p-5 sm:p-6 space-y-3.5" id="exam-qcard-' + q.id + '">' +
          '<div class="text-xs font-extrabold text-slate-500 dark:text-slate-400">Câu ' + (idx + 1) + "</div>" +
          '<div class="font-extrabold text-sm sm:text-base leading-relaxed">' + escapeHtml(q.text) + "</div>" +
          '<div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-1">' + optsHtml + "</div></div>"
        );
      }).join("");
    }

    function chooseExamOption(qId, letter) {
      if (!activeExam) return;
      activeExam.selections[qId] = letter;
      ["A", "B", "C", "D"].forEach(function (l) {
        const btn = document.getElementById("exam-opt-" + qId + "-" + l);
        const badge = document.getElementById("exam-badge-" + qId + "-" + l);
        if (!btn || !badge) return;
        const isSel = l === letter;
        btn.className = "text-left p-3.5 rounded-2xl liquid-opt text-xs sm:text-sm flex items-start gap-3 " + (isSel ? "border-red-500 bg-red-500/15 font-bold ring-2 ring-red-500/40" : "");
        badge.className = "w-7 h-7 rounded-xl text-xs font-black flex items-center justify-center shrink-0 " + (isSel ? "bg-red-600 text-white" : "bg-slate-200 dark:bg-slate-700");
      });
      updateExamTimerUI();
    }

    function cancelExam() {
      if (examTimerInterval) clearInterval(examTimerInterval);
      activeExam = null;
      document.getElementById("exam-active-view").classList.add("hidden");
      document.getElementById("exam-setup-view").classList.remove("hidden");
      showExamFloatTimer(false);
    }

    function submitExam() {
      if (!activeExam) return;
      if (examTimerInterval) clearInterval(examTimerInterval);

      let correct = 0;
      const usedIds = [];

      activeExam.questions.forEach(function (q) {
        usedIds.push(q.id);
        const chosenDisplay = activeExam.selections[q.id];
        if (chosenDisplay) {
          const originalLetter = (q.displayToOriginal && q.displayToOriginal[chosenDisplay]) ? q.displayToOriginal[chosenDisplay] : chosenDisplay;
          userProgress.answered[q.id] = originalLetter;
          if (chosenDisplay === q.answer) correct++;
        }
      });

      // Lưu câu đã ra để lần thi sau không trùng
      const recent = loadRecentExamIds();
      saveRecentExamIds(usedIds.concat(recent));

      const total = activeExam.questions.length;
      const score = (correct / total) * 10;
      const spentSec = activeExam.durationSec - activeExam.remainingSec;
      const spentMin = Math.floor(spentSec / 60);
      const spentRemSec = spentSec % 60;

      userProgress.examHistory.unshift({
        scopeName: activeExam.scopeName,
        total: total,
        correct: correct,
        score: score,
        timeSpent: spentMin + "p " + spentRemSec + "s",
        date: new Date().toLocaleDateString("vi-VN")
      });
      // Giới hạn lịch sử thi
      if (userProgress.examHistory.length > 30) userProgress.examHistory = userProgress.examHistory.slice(0, 30);
      saveProgress();

      document.getElementById("exam-active-view").classList.add("hidden");
      showExamFloatTimer(false);
      const resView = document.getElementById("exam-result-view");
      resView.classList.remove("hidden");

      const scoreBadgeTone = score >= 5 ? "bg-emerald-500/20 text-emerald-500" : "bg-rose-500/20 text-rose-500";
      const detailCardsHtml = activeExam.questions.map(function (q, i) {
        const uAns = activeExam.selections[q.id];
        const isOk = uAns === q.answer;
        const borderTone = isOk ? "border-l-emerald-500" : "border-l-rose-500";
        const statusTone = isOk ? "text-emerald-500" : "text-rose-500";
        const statusText = isOk
          ? "✓ Đúng (+0.2đ)"
          : "✗ Sai (Đã chọn: " + (uAns || "Bỏ trống") + " | Đáp án đúng: " + q.answer + ")";

        const optItemsHtml = ["A", "B", "C", "D"].map(function (letter) {
          let itemCls = "border-white/30 dark:border-white/10 opacity-75";
          if (letter === q.answer) itemCls = "liquid-opt-correct font-bold";
          else if (uAns === letter) itemCls = "liquid-opt-wrong";
          return '<div class="p-2.5 rounded-xl border ' + itemCls + '"><b>' + letter + ".</b> " + escapeHtml(q.options[letter]) + "</div>";
        }).join("");

        const chLabel = (q.chapter && q.qNum)
          ? (' · Tra cứu: Chương ' + q.chapter + ' — Câu ' + q.qNum + (q.code ? (' (' + q.code + ')') : ''))
          : '';
        return (
          '<div class="liquid-glass rounded-3xl p-5 space-y-3 border-l-4 ' + borderTone + '">' +
          '<div class="flex items-center justify-between text-xs gap-2 flex-wrap">' +
          '<span class="font-extrabold">Câu ' + (i + 1) + '<span class="font-normal text-slate-500">' + chLabel + '</span></span>' +
          '<span class="font-black ' + statusTone + '">' + statusText + "</span></div>" +
          '<div class="text-sm font-bold">' + escapeHtml(q.text) + "</div>" +
          '<div class="grid grid-cols-1 sm:grid-cols-2 gap-2 text-xs">' + optItemsHtml + "</div></div>"
        );
      }).join("");

      resView.innerHTML =
        '<div class="liquid-glass rounded-3xl p-6 sm:p-8 text-center space-y-4">' +
        '<div class="inline-flex items-center justify-center w-20 h-20 rounded-3xl ' + scoreBadgeTone + ' text-3xl font-black">' + score.toFixed(1) + "</div>" +
        "<div><h2 class=\"text-xl sm:text-2xl font-black\">Điểm Bài Thi: " + score.toFixed(2) + " / 10 điểm</h2>" +
        '<p class="text-xs text-slate-500 dark:text-slate-400 mt-1">Trả lời đúng: <b>' + correct + " / " + total + "</b> câu • Thời gian: " + spentMin + " phút " + spentRemSec + " giây</p></div>" +
        '<div class="flex justify-center gap-3 pt-2">' +
        '<button onclick="resetExamToSetup()" class="px-6 py-3 rounded-2xl bg-gradient-to-r from-red-600 to-amber-500 text-white font-extrabold text-xs shadow-lg transition">' +
        '<i class="fa-solid fa-rotate-right mr-1"></i> Thi Đề Mới</button></div></div>' +
        '<div class="space-y-3.5"><h3 class="font-extrabold text-xs uppercase tracking-wider text-slate-500">Chi Tiết Đáp Án</h3>' + detailCardsHtml + "</div>";
    }

    function resetExamToSetup() {
      document.getElementById("exam-result-view").classList.add("hidden");
      document.getElementById("exam-setup-view").classList.remove("hidden");
    }

    /*************************************************************************
     * 8. TRA CỨU 600 CÂU HỎI & CHO PHÉP BẤM CHỌN LẠI NGAY TRONG Ô TRA CỨU
     *************************************************************************/
    function removeVietnameseTones(str) {
      return str
        .normalize("NFD")
        .replace(/[\u0300-\u036f]/g, "")
        .replace(/đ/g, "d")
        .replace(/Đ/g, "D")
        .toLowerCase();
    }

    function clearSearchInput() {
      document.getElementById("search-input").value = "";
      renderSearchResults();
    }

    function renderSearchResults() {
      const queryRaw = (document.getElementById("search-input")?.value || "").trim();
      const chFilter = document.getElementById("search-chapter-filter")?.value || "all";
      const qNorm = removeVietnameseTones(queryRaw);

      const filtered = ALL_QUESTIONS.filter(q => {
        if (chFilter !== "all" && q.chapter !== parseInt(chFilter, 10)) return false;
        if (!queryRaw) return true;
        const hay = `${q.code} câu ${q.qNum} chương ${q.chapter} ${q.text} ${q.options.A} ${q.options.B} ${q.options.C} ${q.options.D}`;
        return removeVietnameseTones(hay).includes(qNorm);
      });

      document.getElementById("search-count-label").textContent = `Tìm thấy ${filtered.length} câu`;

      const container = document.getElementById("search-results-container");
      const displayList = filtered.slice(0, 100);

      container.innerHTML = displayList.map(q => {
        const isStar = userProgress.starred[q.id];
        const uAns = userProgress.answered[q.id];
        return `
          <div class="liquid-glass rounded-3xl p-4 sm:p-5 space-y-3">
            <div class="flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2">
                <span class="px-2.5 py-1 rounded-xl bg-red-500/15 text-red-600 dark:text-red-300 font-black text-xs">
                  Chương ${q.chapter} • Câu ${q.qNum}
                </span>
                <span class="px-2.5 py-0.5 rounded-lg bg-white/50 dark:bg-slate-800 text-xs font-mono font-bold">
                  ${q.code}
                </span>
                <span class="px-2.5 py-0.5 rounded-full bg-emerald-500/20 text-emerald-600 dark:text-emerald-300 font-black text-xs">
                  Đáp án chuẩn: ${q.answer}
                </span>
              </div>
              <button onclick="toggleStar(${q.id})" class="text-sm ${isStar ? 'text-amber-400' : 'text-slate-400 hover:text-amber-400'}">
                <i class="${isStar ? 'fa-solid' : 'fa-regular'} fa-star"></i>
              </button>
            </div>

            <div class="font-extrabold text-sm sm:text-base leading-relaxed">
              ${escapeHtml(q.text)}
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs">
              ${["A", "B", "C", "D"].map(letter => {
                const isCorrect = letter === q.answer;
                const isPickedWrong = uAns === letter && !isCorrect;
                return `
                  <button
                    type="button"
                    onclick="quickAnswerFromList(${q.id}, '${letter}')"
                    class="text-left p-3 rounded-2xl liquid-opt flex items-start gap-2.5 ${isCorrect ? 'liquid-opt-correct font-bold' : (isPickedWrong ? 'liquid-opt-wrong' : '')}"
                  >
                    <span class="w-6 h-6 rounded-lg font-black flex items-center justify-center shrink-0 ${isCorrect ? 'bg-emerald-600 text-white' : (isPickedWrong ? 'bg-rose-600 text-white' : 'bg-slate-200 dark:bg-slate-700')}">
                      ${letter}
                    </span>
                    <span class="leading-relaxed flex-1">${escapeHtml(q.options[letter])}</span>
                  </button>
                `;
              }).join("")}
            </div>
          </div>
        `;
      }).join("");
    }

    function quickAnswerFromList(qId, letter) {
      userProgress.answered[qId] = letter;
      saveProgress();
      if (currentTab === "search") renderSearchResults();
      if (currentTab === "review") renderReviewList();
    }

    function toggleCompactKeyModal() {
      const modal = document.getElementById("compact-key-modal");
      modal.classList.toggle("hidden");
      if (!modal.classList.contains("hidden")) {
        renderCompactAnswerTable();
      }
    }

    function renderCompactAnswerTable() {
      const body = document.getElementById("compact-key-body");
      body.innerHTML = CHAPTER_META.map(ch => {
        const chQs = ALL_QUESTIONS.filter(q => q.chapter === ch.id);
        return `
          <div class="space-y-3">
            <h4 class="font-black text-sm text-red-600 dark:text-red-400 border-b border-white/30 dark:border-white/10 pb-2">
              ${ch.title} (${ch.total} câu)
            </h4>
            <div class="grid grid-cols-5 sm:grid-cols-10 md:grid-cols-12 gap-1.5">
              ${chQs.map(q => `
                <button
                  onclick="jumpFromKeyModal(${q.chapter}, ${q.qNum})"
                  class="p-1.5 rounded-xl liquid-opt hover:bg-red-600 hover:text-white text-center font-mono text-[11px]"
                >
                  <span class="opacity-70">${q.qNum}:</span><b class="ml-0.5 text-emerald-600 dark:text-emerald-400">${q.answer}</b>
                </button>
              `).join("")}
            </div>
          </div>
        `;
      }).join("");
    }

    function jumpFromKeyModal(ch, qNum) {
      toggleCompactKeyModal();
      document.getElementById("practice-chapter-select").value = String(ch);
      document.getElementById("practice-section-select").value = "all";
      document.getElementById("practice-status-select").value = "all";
      switchTab("practice");
      onPracticeFilterChange();
      const idx = practiceList.findIndex(q => q.chapter === ch && q.qNum === qNum);
      if (idx !== -1) jumpToPracticeIdx(idx);
    }

    /*************************************************************************
     * 9. TAB ÔN CÂU SAI & ĐÁNH DẤU SAO (CHO PHÉP CHỌN LẠI TRỰC TIẾP)
     *************************************************************************/
    let currentReviewMode = "wrong";

    function updateReviewBadge() {
      const wrongList = ALL_QUESTIONS.filter(q => {
        const u = userProgress.answered[q.id];
        return u && u !== q.answer;
      });
      const starList = ALL_QUESTIONS.filter(q => userProgress.starred[q.id]);

      const badge = document.getElementById("badge-review");
      if (badge) badge.textContent = wrongList.length + starList.length;

      const wCount = document.getElementById("rev-wrong-count");
      const sCount = document.getElementById("rev-star-count");
      if (wCount) wCount.textContent = wrongList.length;
      if (sCount) sCount.textContent = starList.length;
    }

    function setReviewMode(mode) {
      currentReviewMode = mode;
      renderReviewList();
    }

    function renderReviewList() {
      updateReviewBadge();
      const btnW = document.getElementById("btn-rev-wrong");
      const btnS = document.getElementById("btn-rev-starred");

      if (currentReviewMode === "wrong") {
        btnW.className = "px-4 py-2 rounded-2xl text-xs font-extrabold bg-rose-600 text-white shadow-md";
        btnS.className = "px-4 py-2 rounded-2xl text-xs font-bold liquid-opt";
      } else {
        btnS.className = "px-4 py-2 rounded-2xl text-xs font-extrabold bg-amber-500 text-slate-950 shadow-md";
        btnW.className = "px-4 py-2 rounded-2xl text-xs font-bold liquid-opt";
      }

      const list = ALL_QUESTIONS.filter(q => {
        if (currentReviewMode === "wrong") {
          const u = userProgress.answered[q.id];
          return u && u !== q.answer;
        }
        return Boolean(userProgress.starred[q.id]);
      });

      const container = document.getElementById("review-list-container");
      if (!list.length) {
        container.innerHTML = `
          <div class="liquid-glass rounded-3xl p-12 text-center text-slate-400">
            <i class="fa-regular fa-face-smile-beam text-3xl mb-2 text-emerald-500"></i>
            <p class="font-extrabold text-sm">Tuyệt vời! Không có câu hỏi nào trong danh sách này.</p>
          </div>
        `;
        return;
      }

      container.innerHTML = list.map(q => {
        const uAns = userProgress.answered[q.id];
        return `
          <div class="liquid-glass rounded-3xl p-5 space-y-3">
            <div class="flex flex-wrap items-center justify-between gap-2 text-xs">
              <span class="font-black text-red-600 dark:text-red-400">Chương ${q.chapter} • Câu ${q.qNum} (${q.code})</span>
              <span class="font-bold ${uAns === q.answer ? 'text-emerald-500' : 'text-rose-500'}">
                Đang chọn: ${uAns || 'Chưa chọn'} • Đáp án đúng: ${q.answer} (Bấm vào đáp án đúng bên dưới để sửa lại)
              </span>
            </div>
            <div class="font-extrabold text-sm sm:text-base">${escapeHtml(q.text)}</div>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs">
              ${["A", "B", "C", "D"].map(letter => {
                const isCorrect = letter === q.answer;
                const isPicked = uAns === letter;
                return `
                  <button
                    type="button"
                    onclick="quickAnswerFromList(${q.id}, '${letter}')"
                    class="text-left p-3 rounded-2xl liquid-opt flex items-start gap-2.5 ${isCorrect ? 'liquid-opt-correct font-bold' : (isPicked ? 'liquid-opt-wrong' : '')}"
                  >
                    <span class="w-6 h-6 rounded-lg font-black flex items-center justify-center shrink-0 ${isCorrect ? 'bg-emerald-600 text-white' : (isPicked ? 'bg-rose-600 text-white' : 'bg-slate-200 dark:bg-slate-700')}">
                      ${letter}
                    </span>
                    <span class="leading-relaxed flex-1">${escapeHtml(q.options[letter])}</span>
                  </button>
                `;
              }).join("")}
            </div>
          </div>
        `;
      }).join("");
    }

    function practiceReviewQuestions() {
      document.getElementById("practice-chapter-select").value = "all";
      document.getElementById("practice-section-select").value = "all";
      document.getElementById("practice-status-select").value = currentReviewMode === "wrong" ? "wrong" : "starred";
      switchTab("practice");
      onPracticeFilterChange();
    }

    /*************************************************************************
     * 10. HIỆU ỨNG LIQUID GLASS SPOTLIGHT, GIAO DIỆN & PHÍM TẮT
     *************************************************************************/
    // Hiệu ứng spotlight – throttle + tắt trên thiết bị cảm ứng để mượt hơn
    (function () {
      let ticking = false;
      let lastX = 0, lastY = 0;
      const isTouchDevice = "ontouchstart" in window || navigator.maxTouchPoints > 0;

      if (isTouchDevice) {
        // Tắt spotlight trên mobile/tablet để giảm tải GPU
        document.querySelectorAll(".liquid-spotlight").forEach(el => {
          el.classList.remove("liquid-spotlight");
        });
        return;
      }

      document.addEventListener("mousemove", (e) => {
        lastX = e.clientX;
        lastY = e.clientY;
        if (!ticking) {
          ticking = true;
          requestAnimationFrame(() => {
            document.querySelectorAll(".liquid-spotlight").forEach(card => {
              const rect = card.getBoundingClientRect();
              // Chỉ cập nhật khi chuột nằm trong vùng card
              if (lastX >= rect.left && lastX <= rect.right && lastY >= rect.top && lastY <= rect.bottom) {
                card.style.setProperty("--mouse-x", (lastX - rect.left) + "px");
                card.style.setProperty("--mouse-y", (lastY - rect.top) + "px");
              }
            });
            ticking = false;
          });
        }
      }, { passive: true });
    })();

    function toggleTheme() {
      const html = document.documentElement;
      const isDark = html.classList.toggle("dark");
      const icon = document.getElementById("theme-icon");
      icon.className = isDark ? "fa-solid fa-sun text-amber-400" : "fa-solid fa-moon text-slate-700";
    }

    // Điều chỉnh độ trong suốt Liquid Glass theo thời gian thực
    function updateGlassLabel(val) {
      const el = document.getElementById("glass-alpha-label");
      if (el) el.textContent = parseInt(val, 10) + "%";
    }
    function updateGlassTransparency(val) {
      const n = parseInt(val, 10) || 16;
      const alpha = (n / 100).toFixed(2);
      document.documentElement.style.setProperty("--glass-alpha", alpha);
      const main = document.getElementById("glass-alpha-slider");
      const modal = document.getElementById("glass-alpha-slider-modal");
      if (main && String(main.value) !== String(n)) main.value = n;
      if (modal && String(modal.value) !== String(n)) modal.value = n;
      updateGlassLabel(n);
      try { localStorage.setItem("triet_bas123_glass_alpha", String(n)); } catch (e) {}
    }

    // Giải thích căn cứ lý luận chuẩn Giáo trình ĐH Kỹ thuật Công nghiệp Thái Nguyên (TNUT)
    function getTnutExplanation(q) {
      const correctText = escapeHtml(q.options[q.answer] || "");
      const secName = getSectionName(q.section);
      return "Theo đề cương học phần <b>Triết học Mác - Lênin (BAS 123 - Khoa KHCB&amp;UD, Trường ĐH Kỹ thuật Công nghiệp Thái Nguyên)</b> thuộc chuyên đề <i>" + secName + "</i>, phương án <b>" + q.answer + "</b> (<i>“" + correctText + "”</i>) phản ánh đúng đắn lập trường thế giới quan duy vật biện chứng và phương pháp luận khoa học gắn lý luận với thực tiễn.";
    }

    /*************************************************************************
     * 11. BỘ TẠO MÃ QR CANVAS ĐỘC LẬP (NATIVE QR v3.0 - KHÔNG DÙNG LINK CŨ)
     *************************************************************************/
    const STORAGE_KEY_CUSTOM_URL = "triet_bas123_custom_url_v3";

    function getSelfWebAppUrl() {
      const savedCustom = localStorage.getItem(STORAGE_KEY_CUSTOM_URL);
      if (savedCustom && savedCustom.trim()) {
        return savedCustom.trim();
      }
      const currentHref = window.location.href;
      if (currentHref && /^https?:\/\//i.test(currentHref)) {
        return currentHref;
      }
      // Đường dẫn mặc định mới dành riêng cho ứng dụng TNUT BAS 123 v3.0
      return window.location.origin && window.location.origin !== "null"
        ? window.location.origin + window.location.pathname
        : "https://on-triet-mac-lenin-bas123-tnut.netlify.app";
    }

    function openQrModal() {
      const modal = document.getElementById("qr-modal");
      modal.classList.remove("hidden");
      const input = document.getElementById("share-url-input");
      if (input) {
        input.value = getSelfWebAppUrl();
        renderNativeQrCanvas(input.value);
      }
    }

    function closeQrModal() {
      document.getElementById("qr-modal").classList.add("hidden");
    }

    function useCurrentBrowserUrl() {
      localStorage.removeItem(STORAGE_KEY_CUSTOM_URL);
      const input = document.getElementById("share-url-input");
      const liveUrl = (window.location.href && /^https?:\/\//i.test(window.location.href))
        ? window.location.href
        : "https://on-triet-mac-lenin-bas123-tnut.netlify.app";
      if (input) {
        input.value = liveUrl;
        renderNativeQrCanvas(liveUrl);
      }
    }

    function updateQrCodeFromInput() {
      const input = document.getElementById("share-url-input");
      if (!input) return;
      const val = input.value.trim();
      if (val) {
        localStorage.setItem(STORAGE_KEY_CUSTOM_URL, val);
      }
      renderNativeQrCanvas(val || getSelfWebAppUrl());
    }

    // Tự vẽ Mã QR chất lượng cao trực tiếp lên HTML5 Canvas kèm biểu tượng Ngôi nhà (Home) ở chính giữa
    function renderNativeQrCanvas(targetUrl) {
      const canvas = document.getElementById("native-qr-canvas");
      if (!canvas) return;
      const ctx = canvas.getContext("2d");
      const size = canvas.width;

      ctx.clearRect(0, 0, size, size);
      ctx.fillStyle = "#ffffff";
      ctx.fillRect(0, 0, size, size);

      if (typeof window.qrcode !== "function") {
        ctx.fillStyle = "#0f172a";
        ctx.font = "bold 12px Inter, sans-serif";
        ctx.textAlign = "center";
        ctx.fillText("Đang khởi tạo QR...", size / 2, size / 2);
        return;
      }

      try {
        const qr = window.qrcode(0, "H");
        qr.addData(targetUrl);
        qr.make();

        const moduleCount = qr.getModuleCount();
        const padding = 14;
        const availSize = size - padding * 2;
        const cellSize = availSize / moduleCount;

        // Vẽ các điểm QR với gradient xanh lam - chàm hiện đại của riêng bản 3.0
        const grad = ctx.createLinearGradient(0, 0, size, size);
        grad.addColorStop(0, "#0284c7");
        grad.addColorStop(0.5, "#1e293b");
        grad.addColorStop(1, "#0f766e");
        ctx.fillStyle = grad;

        for (let r = 0; r < moduleCount; r++) {
          for (let c = 0; c < moduleCount; c++) {
            if (qr.isDark(r, c)) {
              const x = padding + c * cellSize;
              const y = padding + r * cellSize;
              ctx.fillRect(x, y, Math.ceil(cellSize), Math.ceil(cellSize));
            }
          }
        }

        // Vẽ huy hiệu Ngôi nhà (Home Icon) ở chính giữa mã QR
        const badgeSize = 48;
        const bx = (size - badgeSize) / 2;
        const by = (size - badgeSize) / 2;

        ctx.fillStyle = "#ffffff";
        ctx.beginPath();
        ctx.roundRect(bx - 4, by - 4, badgeSize + 8, badgeSize + 8, 12);
        ctx.fill();

        const badgeGrad = ctx.createLinearGradient(bx, by, bx + badgeSize, by + badgeSize);
        badgeGrad.addColorStop(0, "#0ea5e9");
        badgeGrad.addColorStop(1, "#10b981");
        ctx.fillStyle = badgeGrad;
        ctx.beginPath();
        ctx.roundRect(bx, by, badgeSize, badgeSize, 10);
        ctx.fill();

        // Vẽ hình ngôi nhà màu trắng ở tâm huy hiệu
        const cx = size / 2;
        const cy = size / 2;
        ctx.fillStyle = "#ffffff";
        // Mái nhà
        ctx.beginPath();
        ctx.moveTo(cx, cy - 13);
        ctx.lineTo(cx - 14, cy - 1);
        ctx.lineTo(cx + 14, cy - 1);
        ctx.closePath();
        ctx.fill();
        // Thân nhà
        ctx.fillRect(cx - 9, cy - 2, 18, 14);
        // Cửa nhà
        ctx.fillStyle = "#0ea5e9";
        ctx.fillRect(cx - 3, cy + 4, 6, 8);
      } catch (err) {
        console.error("QR generation error:", err);
      }
    }

    function copyShareUrl() {
      const input = document.getElementById("share-url-input");
      const msg = document.getElementById("copy-status-msg");
      if (!input) return;
      input.select();
      document.execCommand("copy");
      if (msg) {
        msg.classList.remove("hidden");
        setTimeout(function() {
          msg.classList.add("hidden");
        }, 2500);
      }
    }

    // Xuất thẻ Poster QR .PNG độc lập của trang web mới
    function downloadQrPosterPng() {
      const qrCanvas = document.getElementById("native-qr-canvas");
      const input = document.getElementById("share-url-input");
      const urlText = (input && input.value.trim()) ? input.value.trim() : getSelfWebAppUrl();
      if (!qrCanvas) return;

      const poster = document.createElement("canvas");
      poster.width = 480;
      poster.height = 580;
      const pCtx = poster.getContext("2d");

      // Nền thẻ QR sang trọng
      const bgGrad = pCtx.createLinearGradient(0, 0, 480, 580);
      bgGrad.addColorStop(0, "#0f172a");
      bgGrad.addColorStop(1, "#1e293b");
      pCtx.fillStyle = bgGrad;
      pCtx.fillRect(0, 0, 480, 580);

      // Khung trắng chứa QR
      pCtx.fillStyle = "#ffffff";
      pCtx.beginPath();
      pCtx.roundRect(70, 110, 340, 340, 28);
      pCtx.fill();

      // Tiêu đề trên thẻ
      pCtx.fillStyle = "#38bdf8";
      pCtx.font = "bold 16px Inter, sans-serif";
      pCtx.textAlign = "center";
      pCtx.fillText("ĐH KỸ THUẬT CÔNG NGHIỆP THÁI NGUYÊN (TNUT)", 240, 50);

      pCtx.fillStyle = "#ffffff";
      pCtx.font = "900 22px Inter, sans-serif";
      pCtx.fillText("ÔN TRIẾT HỌC MÁC - LÊNIN (BAS 123)", 240, 82);

      // Vẽ QR từ canvas gốc vào poster
      pCtx.drawImage(qrCanvas, 95, 135, 290, 290);

      // Chân trang thẻ QR
      pCtx.fillStyle = "#34d399";
      pCtx.font = "bold 15px Inter, sans-serif";
      pCtx.fillText("Quét mã QR để ôn tập 600 câu hỏi & thi thử (v3.0)", 240, 495);

      pCtx.fillStyle = "#94a3b8";
      pCtx.font = "12px monospace";
      const shortUrl = urlText.length > 48 ? urlText.substring(0, 45) + "..." : urlText;
      pCtx.fillText(shortUrl, 240, 530);

      const dataUrl = poster.toDataURL("image/png");
      const a = document.createElement("a");
      a.href = dataUrl;
      a.download = "Ma-QR-On-Triet-TNUT-BAS123-v3.png";
      document.body.appendChild(a);
      a.click();
      a.remove();
    }

    async function shareWebAppNative() {
      const urlText = getSelfWebAppUrl();
      if (navigator.share) {
        try {
          await navigator.share({
            title: "Ôn Triết Học Mác - Lênin (BAS 123 - TNUT 600 Câu)",
            text: "Ứng dụng ôn tập 600 câu hỏi trắc nghiệm Triết học Mác - Lênin (BAS 123 - TNUT) bản 3.0:",
            url: urlText
          });
          return;
        } catch (err) {
          // Người dùng đóng hộp thoại chia sẻ
        }
      }
      copyShareUrl();
    }

    function downloadStandaloneHtml() {
      const htmlContent = "<!DOCTYPE html>\n" + document.documentElement.outerHTML;
      const blob = new Blob([htmlContent], { type: "text/html;charset=utf-8" });
      const url = URL.createObjectURL(blob);
      const a = document.createElement("a");
      a.href = url;
      a.download = "on-triet-tnut-v3.html";
      document.body.appendChild(a);
      a.click();
      a.remove();
      setTimeout(function() { URL.revokeObjectURL(url); }, 1000);
    }

    function openResetModal() {
      document.getElementById("reset-modal").classList.remove("hidden");
    }
    function closeResetModal() {
      document.getElementById("reset-modal").classList.add("hidden");
    }
    function confirmResetProgress() {
      userProgress = { answered: {}, starred: {}, examHistory: [] };
      saveProgress();
      closeResetModal();
      renderAllViews();
      showToast("Đã đặt lại toàn bộ tiến độ", "info");
    }

    function escapeHtml(str) {
      if (!str) return "";
      return String(str)
        .replace(/&/g, "&amp;")
        .replace(/</g, "&lt;")
        .replace(/>/g, "&gt;");
    }

    window.addEventListener("keydown", (e) => {
      if (currentTab !== "practice") return;
      if (["INPUT", "TEXTAREA", "SELECT"].includes(document.activeElement?.tagName)) return;

      if (e.key === "ArrowRight") {
        e.preventDefault();
        nextPracticeQuestion();
      } else if (e.key === "ArrowLeft") {
        e.preventDefault();
        prevPracticeQuestion();
      } else {
        const keyMap = { a: "A", b: "B", c: "C", d: "D", "1": "A", "2": "B", "3": "C", "4": "D" };
        const letter = keyMap[e.key.toLowerCase()];
        if (letter && practiceList[currentPracticeIdx]) {
          selectPracticeAnswer(practiceList[currentPracticeIdx].id, letter);
        }
      }
    });

    function renderAllViews() {
      updateDashboardStats();
      updateReviewBadge();
      onPracticeFilterChange();
      renderSearchResults();
    }

    window.onload = function () {
      loadProgress();
      buildQuestionBank();
      switchTab("dashboard");
      renderAllViews();
      // Restore glass transparency preference
      try {
        const ga = localStorage.getItem("triet_bas123_glass_alpha");
        if (ga) updateGlassTransparency(ga);
      } catch (e) {}
      // Ensure quality buttons reflect current state
      const q = document.documentElement.getAttribute("data-quality") || "120";
      setQuality(q);
    };
  </script>
</body>
</html>
