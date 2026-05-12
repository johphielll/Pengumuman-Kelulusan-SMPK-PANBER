<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pengumuman Kelulusan – SMP Kristen Pancaran Berkat 2025/2026</title>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,400;0,500;0,600;0,700;0,800;1,400&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">
<style>
/* ===== RESET & BASE ===== */
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
:root {
  --blue-900: #0d2f5e;
  --blue-800: #0f4c81;
  --blue-700: #1565c0;
  --blue-600: #1976d2;
  --gold: #FFD54F;
  --gold-dark: #F9A825;
  --green-700: #2e7d32;
  --green-500: #43a047;
  --red-500: #e53935;
  --slate-900: #0f172a;
  --slate-800: #1e293b;
  --slate-700: #334155;
  --slate-600: #475569;
  --slate-400: #94a3b8;
  --slate-200: #e2e8f0;
  --slate-100: #f1f5f9;
  --slate-50:  #f8fafc;
  --white: #ffffff;
  --radius: 14px;
  --radius-lg: 22px;
  --shadow-lg: 0 24px 64px rgba(0,0,0,.22);
  --shadow-md: 0 8px 32px rgba(0,0,0,.12);
}
body { font-family: 'Plus Jakarta Sans', sans-serif; min-height: 100vh; }

/* ===== SHARED UTILS ===== */
.hidden { display: none !important; }
.mono { font-family: 'JetBrains Mono', monospace; }

/* ============================================================
   PUBLIC VIEW
   ============================================================ */
#public-view {
  background: linear-gradient(160deg, var(--blue-900) 0%, var(--blue-700) 55%, var(--blue-800) 100%);
  min-height: 100vh;
  padding: 40px 16px 60px;
  color: #fff;
}
.pub-container { max-width: 640px; margin: 0 auto; }

/* Header */
.pub-header { text-align: center; margin-bottom: 32px; animation: fadeDown .7s ease both; }
@keyframes fadeDown { from{opacity:0;transform:translateY(-20px)} to{opacity:1;transform:translateY(0)} }
@keyframes fadeUp   { from{opacity:0;transform:translateY(20px)}  to{opacity:1;transform:translateY(0)} }

.school-name {
  font-size: clamp(16px,3.5vw,24px); font-weight: 800;
  color: var(--gold); letter-spacing: 2.5px; text-transform: uppercase;
  margin-bottom: 16px; line-height: 1.3;
}
.divider { display:flex; align-items:center; gap:10px; max-width:400px; margin:0 auto 18px; }
.div-line { flex:1; height:1px; background:rgba(255,255,255,.2); }
.div-dot  { width:5px; height:5px; background:rgba(255,255,255,.35); border-radius:50%; flex-shrink:0; }
h1 { font-size:clamp(30px,6.5vw,50px); font-weight:800; line-height:1.05; letter-spacing:-.5px; color:#fff; }
h1 em { color: var(--gold); font-style:normal; }
.year-pill {
  display:inline-block; margin-top:12px;
  background:rgba(255,255,255,.15); border:1px solid rgba(255,255,255,.3);
  border-radius:100px; padding:6px 20px;
  font-size:13px; font-weight:600; color:#fff; letter-spacing:.5px;
}

/* Countdown */
.cd-section { margin-bottom:22px; animation: fadeUp .7s .1s ease both; }
.cd-label {
  text-align:center; font-size:11px; font-weight:700;
  letter-spacing:2.5px; text-transform:uppercase;
  color:rgba(255,255,255,.5); margin-bottom:10px;
}
.cd-announce {
  text-align:center; font-size:14px; font-weight:600;
  color:rgba(255,255,255,.65); margin-bottom:14px; line-height:1.6;
}
.cd-announce strong { color: var(--gold); }
.cd-grid { display:grid; grid-template-columns:repeat(4,1fr); gap:10px; }
.cd-box {
  background:rgba(255,255,255,.1); border:1px solid rgba(255,255,255,.18);
  border-radius:16px; padding:16px 8px 12px; text-align:center;
}
.cd-num { font-size:clamp(28px,6vw,44px); font-weight:800; color:#fff; line-height:1; display:block; font-variant-numeric:tabular-nums; }
.cd-unit { font-size:10px; font-weight:700; letter-spacing:2px; text-transform:uppercase; color:rgba(255,255,255,.45); margin-top:6px; display:block; }

/* Session status banner */
.session-banner {
  border-radius: var(--radius); padding:14px 18px;
  text-align:center; margin-bottom:16px; font-size:13px;
  font-weight:600; line-height:1.6;
  animation: fadeUp .7s .15s ease both;
}
.session-banner.locked    { background:rgba(255,255,255,.08); border:1px solid rgba(255,255,255,.2); color:rgba(255,255,255,.7); }
.session-banner.active    { background:rgba(67,160,71,.25);   border:1px solid rgba(129,199,132,.5); color:#a5d6a7; }
.session-banner.waiting   { background:rgba(255,213,79,.12);  border:1px solid rgba(255,213,79,.35); color:var(--gold); }
.session-banner.closed    { background:rgba(229,57,53,.15);   border:1px solid rgba(239,154,154,.4); color:#ef9a9a; }
.session-banner strong    { display:block; font-size:15px; margin-bottom:3px; }

/* Lock message */
.lock-msg {
  background:rgba(255,255,255,.08); border:1px solid rgba(255,255,255,.2);
  border-radius:var(--radius); padding:14px 20px; text-align:center;
  margin-bottom:16px; font-size:13px; color:rgba(255,255,255,.7); line-height:1.7;
  animation: fadeUp .7s .2s ease both;
}
.lock-msg strong { color:var(--gold); font-size:14px; display:block; margin-bottom:3px; }

/* Search card */
.pub-card {
  background:#fff; border-radius:var(--radius-lg); padding:26px;
  margin-bottom:18px; box-shadow: var(--shadow-lg);
  animation: fadeUp .7s .25s ease both;
  transition: opacity .4s, filter .4s;
}
.pub-card.locked { opacity:.4; pointer-events:none; user-select:none; filter:blur(1.5px); }
.field-lbl { font-size:11px; font-weight:700; letter-spacing:2px; text-transform:uppercase; color:var(--blue-700); margin-bottom:10px; }
.inp-row { display:flex; gap:10px; flex-wrap:wrap; }
#nisn-input {
  flex:1; min-width:160px; height:52px; padding:0 16px;
  border:2px solid var(--slate-200); border-radius:12px;
  font-family:'Plus Jakarta Sans',sans-serif; font-size:18px; font-weight:600;
  letter-spacing:2px; color:var(--blue-900); outline:none;
  transition:border-color .2s;
}
#nisn-input:focus { border-color:var(--blue-700); }
#nisn-input::placeholder { color:#b0bec5; letter-spacing:1px; font-weight:400; font-size:15px; }
#cek-btn {
  height:52px; padding:0 26px; background:var(--blue-700); border:none;
  border-radius:12px; color:#fff; font-family:'Plus Jakarta Sans',sans-serif;
  font-size:15px; font-weight:700; cursor:pointer; white-space:nowrap;
  transition:background .15s, transform .1s;
}
#cek-btn:hover  { background:var(--blue-900); }
#cek-btn:active { transform:scale(.97); }

/* Result */
#result { animation: fadeUp .4s ease both; }
.card-lulus { border-radius:var(--radius-lg); overflow:hidden; box-shadow:var(--shadow-lg); margin:0 auto 16px; position:relative; max-width:480px; }
.card-watermark {
  position:absolute; top:53.5%; left:50%;
  transform:translate(-50%, -50%);
  width:180px; height:180px;
  object-fit:contain;
  opacity:0.18;
  pointer-events:none;
  z-index:10;
}
.lulus-top {
  background:linear-gradient(135deg, var(--green-700), var(--green-500));
  padding:28px 28px 44px; text-align:center; position:relative;
}
.lulus-top::after {
  content:''; position:absolute; bottom:-1px; left:0; right:0;
  height:22px; background:#fff; border-radius:22px 22px 0 0;
}
.student-name { font-size:22px; font-weight:800; color:#fff; line-height:1.25; }
.card-body { background:#fff; padding:20px 28px; position:relative; }
.info-row { display:flex; justify-content:space-between; align-items:center; padding:10px 0; border-bottom:1px solid var(--slate-100); gap:8px; }
.info-row:last-child { border-bottom:none; }
.info-label { font-size:10px; font-weight:700; letter-spacing:1px; text-transform:uppercase; color:var(--slate-400); flex-shrink:0; width:110px; }
.info-val   { font-size:14px; font-weight:600; color:#1a237e; text-align:right; line-height:1.4; }
.status-pill { display:inline-block; background:#e8f5e9; border:1.5px solid #a5d6a7; border-radius:100px; padding:5px 18px; font-size:13px; font-weight:700; color:var(--green-700); }
.card-foot { background:var(--slate-50); padding:14px 28px; border-top:1px solid var(--slate-100); text-align:center; font-size:12px; color:var(--slate-400); line-height:1.7; }

.card-nf { background:#fff; border-radius:var(--radius-lg); padding:44px 26px; text-align:center; box-shadow:var(--shadow-lg); }
.nf-icon  { font-size:48px; margin-bottom:12px; }
.nf-title { font-size:20px; font-weight:800; color:#37474f; margin-bottom:8px; }
.nf-sub   { font-size:13px; color:var(--slate-400); line-height:1.7; }
.nf-sub strong { color:var(--slate-600); }

.pub-footer { text-align:center; margin-top:32px; font-size:12px; color:rgba(255,255,255,.35); line-height:1.8; }
.admin-link-btn {
  display:inline-block; margin-top:18px; padding:8px 20px;
  background:rgba(255,255,255,.06); border:1px solid rgba(255,255,255,.12);
  border-radius:100px; font-size:11px; color:rgba(255,255,255,.35); cursor:pointer;
  text-decoration:none; letter-spacing:1px; transition:all .2s;
}
.admin-link-btn:hover { background:rgba(255,255,255,.12); color:rgba(255,255,255,.6); }

/* Recap Access Log */
.recap-toolbar { display:flex; gap:10px; flex-wrap:wrap; align-items:center; margin-bottom:16px; }
.btn-clear-log {
  height:40px; padding:0 18px; background:#fff3e0; border:1.5px solid #ffb74d;
  border-radius:10px; color:#e65100; font-family:'Plus Jakarta Sans',sans-serif;
  font-size:13px; font-weight:700; cursor:pointer; white-space:nowrap; transition:all .15s;
}
.btn-clear-log:hover { background:#ffe0b2; }
.btn-export-csv {
  height:40px; padding:0 18px; background:var(--green-700); border:none;
  border-radius:10px; color:#fff; font-family:'Plus Jakarta Sans',sans-serif;
  font-size:13px; font-weight:700; cursor:pointer; white-space:nowrap; transition:background .15s;
}
.btn-export-csv:hover { background:#1b5e20; }
.recap-stats { display:flex; gap:12px; flex-wrap:wrap; margin-bottom:18px; }
.recap-stat-pill {
  background:#fff; border-radius:10px; padding:12px 18px; box-shadow:var(--shadow-md);
  font-size:13px; font-weight:700; color:var(--slate-700);
  display:flex; align-items:center; gap:8px;
}
.recap-stat-pill .rsp-num { font-size:22px; font-weight:800; color:var(--blue-700); }
.log-empty { text-align:center; padding:60px 20px; color:var(--slate-400); font-size:14px; }
.log-empty .le-icon { font-size:40px; margin-bottom:10px; }
.td-time { font-family:'JetBrains Mono',monospace; font-size:12px; color:var(--slate-500); white-space:nowrap; }
.badge-sesi { font-size:11px; font-weight:700; border-radius:6px; padding:3px 8px; display:inline-block; }
.badge-sesi.s1 { background:#f3e5f5; color:#6a1b9a; }
.badge-sesi.s2 { background:#e3f2fd; color:#0d47a1; }
.badge-sesi.s3 { background:#e8f5e9; color:#1b5e20; }
.badge-sesi.s4 { background:#fff3e0; color:#e65100; }
.badge-sesi.open { background:#e8f5e9; color:#1b5e20; }

/* Confetti */
.confetti-wrap { position:fixed; top:0; left:0; width:100%; height:100%; pointer-events:none; z-index:999; overflow:hidden; }
.cp { position:absolute; width:9px; height:9px; opacity:0; animation:cf 2.5s ease forwards; }
@keyframes cf { 0%{transform:translateY(-20px) rotate(0);opacity:1} 100%{transform:translateY(100vh) rotate(720deg);opacity:0} }

/* ============================================================
   ADMIN VIEW
   ============================================================ */
#admin-view {
  background: var(--slate-100);
  min-height: 100vh;
  font-family: 'Plus Jakarta Sans', sans-serif;
}

/* Login Screen */
#admin-login {
  min-height: 100vh;
  display: flex; align-items: center; justify-content: center;
  background: linear-gradient(135deg, var(--slate-900) 0%, var(--slate-800) 100%);
  padding: 24px;
}
.login-card {
  background: var(--white); border-radius: 24px;
  padding: 44px 40px; width: 100%; max-width: 420px;
  box-shadow: 0 40px 80px rgba(0,0,0,.4);
}
.login-brand { text-align:center; margin-bottom:32px; }
.login-icon { font-size: 36px; margin-bottom: 12px; }
.login-title { font-size:22px; font-weight:800; color:var(--slate-900); }
.login-sub   { font-size:13px; color:var(--slate-400); margin-top:4px; }
.form-group { margin-bottom:18px; }
.form-label { display:block; font-size:11px; font-weight:700; letter-spacing:1.5px; text-transform:uppercase; color:var(--slate-600); margin-bottom:8px; }
.form-input {
  width:100%; height:48px; padding:0 16px;
  border:2px solid var(--slate-200); border-radius:12px;
  font-family:'Plus Jakarta Sans',sans-serif; font-size:15px; color:var(--slate-900);
  outline:none; transition:border-color .2s;
}
.form-input:focus { border-color:var(--blue-700); }
.btn-primary {
  width:100%; height:48px; background:var(--slate-900); border:none;
  border-radius:12px; color:#fff; font-family:'Plus Jakarta Sans',sans-serif;
  font-size:15px; font-weight:700; cursor:pointer; transition:background .15s;
}
.btn-primary:hover { background:var(--blue-700); }
.login-err { color:var(--red-500); font-size:13px; text-align:center; margin-top:10px; display:none; }

/* Admin Dashboard */
#admin-dashboard {
  display: flex; min-height: 100vh;
}

/* Sidebar */
.sidebar {
  width: 250px; flex-shrink: 0;
  background: var(--slate-900);
  padding: 0; display: flex; flex-direction: column;
  position: sticky; top: 0; height: 100vh; overflow-y: auto;
}
.sidebar-brand {
  padding: 24px 20px 20px;
  border-bottom: 1px solid rgba(255,255,255,.07);
}
.sidebar-school { font-size: 11px; font-weight: 700; letter-spacing: 2px; text-transform: uppercase; color: var(--slate-400); margin-bottom: 4px; }
.sidebar-title  { font-size: 16px; font-weight: 800; color: #fff; line-height: 1.3; }
.sidebar-year   { font-size: 12px; color: var(--slate-400); margin-top: 3px; }

.sidebar-nav { padding: 16px 12px; flex: 1; }
.nav-section-label { font-size: 10px; font-weight: 700; letter-spacing: 2px; text-transform: uppercase; color: var(--slate-600); padding: 8px 8px 6px; }
.nav-item {
  display: flex; align-items: center; gap: 10px;
  padding: 10px 12px; border-radius: 10px; cursor: pointer;
  font-size: 14px; font-weight: 600; color: var(--slate-400);
  transition: all .15s; margin-bottom: 2px; user-select: none;
}
.nav-item:hover    { background: rgba(255,255,255,.06); color: #fff; }
.nav-item.active   { background: var(--blue-700); color: #fff; }
.nav-item .nav-icon { font-size: 16px; width: 20px; text-align: center; }

.sidebar-footer {
  padding: 16px 12px;
  border-top: 1px solid rgba(255,255,255,.07);
}
.session-live-badge {
  background: rgba(67,160,71,.2); border: 1px solid rgba(129,199,132,.3);
  border-radius: 10px; padding: 10px 12px; margin-bottom: 10px;
  font-size: 12px; color: #a5d6a7; line-height: 1.5;
}
.session-live-badge strong { display:block; font-size:13px; color:#66bb6a; margin-bottom:2px; }
.btn-logout {
  width: 100%; height: 40px; background: rgba(255,255,255,.06);
  border: 1px solid rgba(255,255,255,.1); border-radius: 10px;
  color: var(--slate-400); font-family: 'Plus Jakarta Sans', sans-serif;
  font-size: 13px; font-weight: 600; cursor: pointer; transition: all .15s;
}
.btn-logout:hover { background: rgba(229,57,53,.2); color: #ef9a9a; border-color: rgba(239,154,154,.3); }

/* Main content */
.main-content { flex: 1; padding: 28px; overflow-x: auto; }
.page-header { margin-bottom: 24px; }
.page-title { font-size: 24px; font-weight: 800; color: var(--slate-900); }
.page-sub   { font-size: 13px; color: var(--slate-400); margin-top: 4px; }

/* Stats */
.stats-row { display: grid; grid-template-columns: repeat(auto-fit, minmax(140px,1fr)); gap: 14px; margin-bottom: 24px; }
.stat-card { background: #fff; border-radius: var(--radius); padding: 18px 20px; box-shadow: var(--shadow-md); }
.stat-num   { font-size: 28px; font-weight: 800; color: var(--slate-900); line-height: 1; }
.stat-label { font-size: 11px; font-weight: 700; letter-spacing: 1.5px; text-transform: uppercase; color: var(--slate-400); margin-top: 6px; }
.stat-card.s1 .stat-num { color: #7b1fa2; }
.stat-card.s2 .stat-num { color: #1565c0; }
.stat-card.s3 .stat-num { color: var(--green-700); }
.stat-card.s4 .stat-num { color: #e65100; }
.stat-card.un .stat-num { color: var(--red-500); }

/* Toolbar */
.toolbar { display:flex; gap:10px; flex-wrap:wrap; align-items:center; margin-bottom:16px; }
.search-input {
  flex:1; min-width:200px; height:42px; padding:0 14px;
  border:1.5px solid var(--slate-200); border-radius:10px;
  font-family:'Plus Jakarta Sans',sans-serif; font-size:14px; color:var(--slate-900);
  outline:none; transition:border-color .2s;
}
.search-input:focus { border-color:var(--blue-700); }
.filter-select {
  height:42px; padding:0 12px; border:1.5px solid var(--slate-200); border-radius:10px;
  font-family:'Plus Jakarta Sans',sans-serif; font-size:13px; color:var(--slate-700);
  background:#fff; cursor:pointer; outline:none;
}
.btn-save-all {
  height:42px; padding:0 22px; background:var(--blue-700); border:none;
  border-radius:10px; color:#fff; font-family:'Plus Jakarta Sans',sans-serif;
  font-size:14px; font-weight:700; cursor:pointer; white-space:nowrap;
  transition:background .15s;
}
.btn-save-all:hover { background:var(--blue-900); }
.btn-bulk {
  height:42px; padding:0 16px; background:var(--slate-200); border:none;
  border-radius:10px; color:var(--slate-700); font-family:'Plus Jakarta Sans',sans-serif;
  font-size:13px; font-weight:600; cursor:pointer; white-space:nowrap;
  transition:background .15s;
}
.btn-bulk:hover { background:var(--slate-300); }

/* Table */
.table-wrap { background:#fff; border-radius:var(--radius-lg); box-shadow:var(--shadow-md); overflow:hidden; }
.data-table { width:100%; border-collapse:collapse; }
.data-table th {
  text-align:left; padding:13px 16px;
  font-size:10px; font-weight:700; letter-spacing:1.5px; text-transform:uppercase;
  color:var(--slate-400); background:var(--slate-50);
  border-bottom:1px solid var(--slate-200);
}
.data-table td { padding:11px 16px; border-bottom:1px solid var(--slate-100); font-size:14px; vertical-align:middle; }
.data-table tr:last-child td { border-bottom:none; }
.data-table tr:hover td { background:var(--slate-50); }
.td-name  { font-weight:600; color:var(--slate-900); }
.td-nisn  { font-family:'JetBrains Mono',monospace; font-size:12px; color:var(--slate-500); letter-spacing:.5px; }
.td-class { font-size:12px; font-weight:700; color:var(--blue-700); background:#e3f2fd; border-radius:6px; padding:3px 8px; display:inline-block; }

.session-select {
  height:36px; padding:0 10px; border:1.5px solid var(--slate-200); border-radius:8px;
  font-family:'Plus Jakarta Sans',sans-serif; font-size:13px; font-weight:600;
  cursor:pointer; outline:none; transition:border-color .2s, background .2s;
  background:#fff; color:var(--slate-700);
  min-width: 140px;
}
.session-select:focus { border-color:var(--blue-700); }
.session-select.s1 { background:#f3e5f5; border-color:#ce93d8; color:#6a1b9a; }
.session-select.s2 { background:#e3f2fd; border-color:#90caf9; color:#0d47a1; }
.session-select.s3 { background:#e8f5e9; border-color:#a5d6a7; color:#1b5e20; }
.session-select.s4 { background:#fff3e0; border-color:#ffb74d; color:#e65100; }
.session-select.un { background:#fff3e0; border-color:#ffcc80; color:#e65100; }

/* Settings tab */
.settings-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(300px,1fr)); gap:18px; }
.settings-card { background:#fff; border-radius:var(--radius-lg); padding:26px; box-shadow:var(--shadow-md); }
.settings-card-title { font-size:15px; font-weight:800; color:var(--slate-900); margin-bottom:18px; display:flex; align-items:center; gap:8px; }
.settings-card-title span { font-size:18px; }
.setting-row { display:flex; flex-direction:column; gap:6px; margin-bottom:16px; }
.setting-row:last-child { margin-bottom:0; }
.setting-label { font-size:11px; font-weight:700; letter-spacing:1.5px; text-transform:uppercase; color:var(--slate-500); }
.setting-input {
  height:44px; padding:0 14px; border:1.5px solid var(--slate-200); border-radius:10px;
  font-family:'Plus Jakarta Sans',sans-serif; font-size:14px; color:var(--slate-900);
  outline:none; transition:border-color .2s;
}
.setting-input:focus { border-color:var(--blue-700); }
.setting-desc { font-size:12px; color:var(--slate-400); line-height:1.5; }
.btn-setting-save {
  height:44px; padding:0 22px; background:var(--slate-900); border:none;
  border-radius:10px; color:#fff; font-family:'Plus Jakarta Sans',sans-serif;
  font-size:14px; font-weight:700; cursor:pointer; transition:background .15s; margin-top:14px;
}
.btn-setting-save:hover { background:var(--blue-700); }
.save-ok { display:none; color:var(--green-500); font-size:13px; font-weight:600; margin-top:8px; }

/* Mode toggle */
.toggle-row { display:flex; align-items:center; justify-content:space-between; padding:14px 0; border-bottom:1px solid var(--slate-100); }
.toggle-row:last-child { border-bottom:none; padding-bottom:0; }
.toggle-info .toggle-name { font-size:14px; font-weight:600; color:var(--slate-900); }
.toggle-info .toggle-desc { font-size:12px; color:var(--slate-400); margin-top:2px; }
.toggle-switch {
  width:48px; height:26px; background:var(--slate-200); border-radius:100px;
  cursor:pointer; position:relative; transition:background .2s; flex-shrink:0;
  border:none; outline:none;
}
.toggle-switch::after {
  content:''; position:absolute; top:3px; left:3px;
  width:20px; height:20px; background:#fff; border-radius:50%;
  transition:transform .2s; box-shadow:0 1px 4px rgba(0,0,0,.2);
}
.toggle-switch.on { background:var(--blue-700); }
.toggle-switch.on::after { transform:translateX(22px); }

/* Toast */
.toast {
  position:fixed; bottom:28px; right:28px; z-index:9999;
  background:var(--slate-900); color:#fff;
  padding:14px 22px; border-radius:12px; font-size:14px; font-weight:600;
  box-shadow:0 8px 32px rgba(0,0,0,.3);
  transform:translateY(20px); opacity:0;
  transition:all .3s ease;
  pointer-events:none;
}
.toast.show { transform:translateY(0); opacity:1; }
.toast.green { background:var(--green-700); }

/* Responsive tweaks */
@media (max-width:900px) {
  #admin-dashboard { flex-direction:column; }
  .sidebar { width:100%; height:auto; position:static; }
  .main-content { padding:20px 16px; }
}
@media (max-width:480px) {
  h1 { font-size:28px; white-space:normal; }
  .school-name { font-size:15px; letter-spacing:1.5px; }
  .cd-num { font-size:28px; }
  #cek-btn { width:100%; }
  #nisn-input { width:100%; }
  .login-card { padding:32px 24px; }
}

/* ===== DARK MODE — GLOBAL (public + admin) ===== */
body.dark { color-scheme: dark; background: #0f172a; }

/* Public page dark */
body.dark #public-view {
  background: linear-gradient(160deg, #020c1b 0%, #0d1f3c 55%, #071020 100%);
}
body.dark .pub-card { background: #1e293b; }
body.dark .field-lbl { color: #93c5fd; }
body.dark #nisn-input { background: #243447; border-color: rgba(255,255,255,.15); color: #e2e8f0; }
body.dark #nisn-input::placeholder { color: #64748b; }
body.dark #cek-btn { background: #1565c0; }
body.dark .cd-box { background: rgba(0,0,0,.35); border-color: rgba(255,255,255,.1); }
body.dark .cd-num { color: #e2e8f0; }
body.dark .lock-msg { background: rgba(0,0,0,.3); border-color: rgba(255,255,255,.1); color: rgba(255,255,255,.7); }
body.dark .lock-msg strong { color: var(--gold); }
body.dark .session-banner.locked { background: rgba(0,0,0,.3); border-color: rgba(255,255,255,.1); color: rgba(255,255,255,.6); }
body.dark .session-banner.waiting { background: rgba(255,213,79,.1); }
body.dark .session-banner.active { background: rgba(67,160,71,.15); }
body.dark .session-banner.closed { background: rgba(229,57,53,.1); }
body.dark .card-nf { background: #1e293b; }
body.dark .nf-title { color: #e2e8f0; }
body.dark .nf-sub { color: #94a3b8; }
body.dark .nf-sub strong { color: #cbd5e1; }
body.dark .card-lulus .card-body { background: #1e293b; }
body.dark .info-val { color: #93c5fd; }
body.dark .info-label { color: #64748b; }
body.dark .info-row { border-color: rgba(255,255,255,.07); }
body.dark .card-foot { background: #243447; border-color: rgba(255,255,255,.07); color: #94a3b8; }
body.dark .pub-footer { color: rgba(255,255,255,.4); }
body.dark .admin-link-btn { background: rgba(255,255,255,.08); border-color: rgba(255,255,255,.15); color: rgba(255,255,255,.5); }
body.dark .admin-link-btn:hover { background: rgba(255,255,255,.14); color: rgba(255,255,255,.75); }
body.dark .pub-card.locked { filter: blur(1.5px) brightness(.7); }

/* Admin page dark */
body.dark #admin-dashboard { background: #0f172a; }
body.dark .main-content { background: #0f172a; }
body.dark .stat-card, body.dark .table-wrap, body.dark .settings-card, body.dark .recap-stat-pill, body.dark .import-card { background: #1e293b !important; }
body.dark .data-table th { background: #243447; color: #94a3b8; border-bottom-color: rgba(255,255,255,.07); }
body.dark .data-table td { border-bottom-color: rgba(255,255,255,.07); color: #e2e8f0; }
body.dark .data-table tr:hover td { background: #243447; }
body.dark .page-title, body.dark .td-name, body.dark .settings-card-title, body.dark .toggle-info .toggle-name, body.dark .import-card-title, body.dark .page-sub { color: #e2e8f0; }
body.dark .search-input, body.dark .filter-select, body.dark .setting-input, body.dark .manual-input { background: #243447; border-color: rgba(255,255,255,.1); color: #e2e8f0; }
body.dark .drop-zone { background: #1e293b; border-color: rgba(255,255,255,.12); }
body.dark .drop-zone:hover, body.dark .drop-zone.drag { border-color: #1976d2; background: #1e3a5f; }
body.dark .preview-wrap { border-color: rgba(255,255,255,.08); }
body.dark .preview-wrap th { background: #243447; border-color: rgba(255,255,255,.07); color: #94a3b8; }
body.dark .preview-wrap td { border-color: rgba(255,255,255,.07); color: #e2e8f0; }
body.dark .import-cnt { color: #94a3b8; }
body.dark .stat-card .stat-num { color: #e2e8f0; }
body.dark .stat-label { color: #94a3b8; }
body.dark .stat-card.s1 .stat-num { color: #ce93d8; }
body.dark .stat-card.s2 .stat-num { color: #90caf9; }
body.dark .stat-card.s3 .stat-num { color: #a5d6a7; }
body.dark .stat-card.s4 .stat-num { color: #ffb74d; }
body.dark .stat-card.un .stat-num { color: #ef9a9a; }
body.dark .setting-desc { color: #64748b; }
body.dark .setting-label { color: #94a3b8; }
body.dark .toggle-desc { color: #64748b; }
body.dark .toggle-row { border-color: rgba(255,255,255,.07); }
body.dark .td-nisn { color: #94a3b8; }
body.dark .td-class { background: #1e3a5f; color: #90caf9; }
body.dark .recap-stat-pill { color: #e2e8f0; }
body.dark .rsp-num { color: #90caf9 !important; }
body.dark .session-select { background: #243447; border-color: rgba(255,255,255,.1); color: #e2e8f0; }
body.dark .session-select.s1 { background: #3b1a5e; border-color: #9c64d4; color: #ce93d8; }
body.dark .session-select.s2 { background: #1e3a5f; border-color: #5b9ade; color: #90caf9; }
body.dark .session-select.s3 { background: #1a3d1f; border-color: #5d9e65; color: #a5d6a7; }
body.dark .session-select.s4 { background: #3d2a0a; border-color: #c4893a; color: #ffb74d; }
body.dark .session-select.un { background: #2c1a0a; border-color: #c47c3a; color: #ffb74d; }
body.dark .btn-save-all { background: #1565c0; }
body.dark .btn-bulk { background: #243447; color: #e2e8f0; border: none; }
body.dark .btn-bulk:hover { background: #334155; }
body.dark .btn-setting-save { background: #1e293b; border: 1px solid rgba(255,255,255,.1); color: #e2e8f0; }
body.dark .btn-setting-save:hover { background: #1565c0; }
body.dark .save-ok { color: #a5d6a7; }
body.dark .td-time { color: #94a3b8; }
body.dark .log-empty { color: #64748b; }
body.dark .badge-sesi.s1 { background: #3b1a5e; color: #ce93d8; }
body.dark .badge-sesi.s2 { background: #1e3a5f; color: #90caf9; }
body.dark .badge-sesi.s3 { background: #1a3d1f; color: #a5d6a7; }
body.dark .badge-sesi.s4 { background: #3d2a0a; color: #ffb74d; }
body.dark .badge-sesi.open { background: #1a3d1f; color: #a5d6a7; }
body.dark .btn-clear-log { background: rgba(229,57,53,.15); border-color: rgba(239,154,154,.3); color: #ef9a9a; }
body.dark .btn-clear-log:hover { background: rgba(229,57,53,.25); }
body.dark .btn-export-csv { background: #1a3d1f; }
body.dark #fb-status { color: #64748b; }
body.dark .dz-txt { color: #94a3b8; }
body.dark .dz-sub { color: #64748b; }
body.dark .manual-lbl { color: #64748b; }
body.dark .preview-label { color: #64748b; }
body.dark p[style*='color:var(--slate-500)'] { color: #64748b !important; }
body.dark .login-card { background: #1e293b; }
body.dark .login-title { color: #e2e8f0; }
body.dark .login-sub { color: #64748b; }
body.dark .form-label { color: #94a3b8; }
body.dark #admin-login { background: linear-gradient(135deg, #020c1b 0%, #0d1f3c 100%); }
body.dark .form-input { background: #243447; border-color: rgba(255,255,255,.12); color: #e2e8f0; }
body.dark .form-input::placeholder { color: #64748b; }
body.dark .btn-primary { background: #1565c0; }
body.dark .eye-btn { color: #64748b; }
body.dark .eye-btn:hover { color: #90caf9; }

/* ===== EYE TOGGLE ===== */
.pass-wrap { position: relative; display: flex; align-items: center; }
.pass-wrap .setting-input, .pass-wrap .form-input { padding-right: 44px; width: 100%; }
.eye-btn { position: absolute; right: 10px; top: 50%; transform: translateY(-50%); background: none; border: none; cursor: pointer; color: var(--slate-400); padding: 4px; display: flex; align-items: center; transition: color .15s; }
.eye-btn svg { width: 18px; height: 18px; stroke: currentColor; fill: none; stroke-width: 2; stroke-linecap: round; stroke-linejoin: round; }
.eye-btn:hover { color: var(--blue-700); }

/* ===== IMPORT TAB ===== */
.import-2col{display:grid;grid-template-columns:1fr 1fr;gap:18px;}
@media(max-width:860px){.import-2col{grid-template-columns:1fr;}}
.import-card{background:#fff;border-radius:var(--radius-lg);padding:24px;box-shadow:var(--shadow-md);margin-bottom:18px;}
.import-card-title{font-size:15px;font-weight:800;color:var(--slate-900);margin-bottom:16px;display:flex;align-items:center;gap:8px;}
.drop-zone{border:2px dashed var(--slate-200);border-radius:12px;padding:32px 20px;text-align:center;cursor:pointer;transition:all .2s;background:var(--slate-50);}
.drop-zone:hover,.drop-zone.drag{border-color:var(--blue-700);background:#eff6ff;}
.dz-icon{font-size:38px;margin-bottom:8px;}
.dz-txt{font-size:14px;font-weight:600;color:var(--slate-600);margin-bottom:3px;}
.dz-sub{font-size:12px;color:var(--slate-400);}
.btn-tmpl{height:38px;padding:0 16px;background:#e8f5e9;border:1.5px solid #a5d6a7;border-radius:10px;color:var(--green-700);font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;font-weight:700;cursor:pointer;display:inline-flex;align-items:center;gap:6px;transition:all .15s;}
.btn-tmpl:hover{background:#c8e6c9;}
.btn-do-import{height:40px;padding:0 20px;background:var(--blue-700);border:none;border-radius:10px;color:#fff;font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;font-weight:700;cursor:pointer;transition:background .15s;}
.btn-do-import:hover{background:var(--blue-900);}
.btn-do-import:disabled{opacity:.45;cursor:not-allowed;}
.preview-label{font-size:11px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--slate-400);margin-bottom:8px;}
.preview-wrap{max-height:240px;overflow-y:auto;border:1px solid var(--slate-200);border-radius:10px;}
.preview-wrap table{width:100%;border-collapse:collapse;}
.preview-wrap th{padding:9px 12px;text-align:left;font-size:10px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--slate-400);background:var(--slate-50);border-bottom:1px solid var(--slate-200);white-space:nowrap;}
.preview-wrap td{padding:8px 12px;border-bottom:1px solid var(--slate-100);font-size:13px;}
.preview-wrap tr:last-child td{border-bottom:none;}
.manual-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:14px;}
@media(max-width:600px){.manual-grid{grid-template-columns:1fr;}}
.manual-field{display:flex;flex-direction:column;gap:5px;}
.manual-input{height:42px;padding:0 12px;border:1.5px solid var(--slate-200);border-radius:10px;font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;color:var(--slate-900);outline:none;transition:border-color .2s;width:100%;}
.manual-input:focus{border-color:var(--blue-700);}
.manual-lbl{font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:var(--slate-500);}
.btn-add-sw{height:42px;padding:0 22px;background:var(--green-700);border:none;border-radius:10px;color:#fff;font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;font-weight:700;cursor:pointer;transition:background .15s;}
.btn-add-sw:hover{background:#1b5e20;}
.import-actions{display:flex;gap:10px;flex-wrap:wrap;align-items:center;margin-top:14px;}
.import-cnt{font-size:13px;font-weight:600;color:var(--slate-500);}

/* ===== DARK MODE BTN ===== */
.btn-dm{display:flex;align-items:center;gap:8px;width:100%;height:38px;padding:0 12px;background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.1);border-radius:10px;color:var(--slate-400);font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;font-weight:600;cursor:pointer;transition:all .15s;margin-bottom:8px;}
.btn-dm:hover{background:rgba(255,255,255,.12);color:#fff;}
</style>
<!-- Firebase SDK -->
<script src="https://www.gstatic.com/firebasejs/10.12.2/firebase-app-compat.js"></script>
<script src="https://www.gstatic.com/firebasejs/10.12.2/firebase-database-compat.js"></script>
<!-- SheetJS for Excel import -->
<script src="https://cdn.sheetjs.com/xlsx-0.20.3/package/dist/xlsx.full.min.js"></script>
</head>
<body>

<!-- ===== CONFETTI ===== -->
<div class="confetti-wrap" id="conf"></div>

<!-- ===== TOAST ===== -->
<div class="toast" id="toast"></div>

<!-- ================================================================
     PUBLIC VIEW
     ================================================================ -->
<div id="public-view">
  <div class="pub-container">

    <header class="pub-header">
      <p class="school-name">SMP Kristen Pancaran Berkat</p>
      <div class="divider"><div class="div-line"></div><div class="div-dot"></div><div class="div-line"></div></div>
      <h1>Pengumuman <em>Kelulusan</em></h1>
      <div class="year-pill">Tahun Ajaran 2025 / 2026</div>
    </header>

    <!-- Countdown -->
    <div class="cd-section" id="cd-section">
      <p class="cd-label" id="cd-label">Pengumuman Dibuka Dalam</p>
      <p class="cd-announce" id="cd-announce">Senin, <strong>2 Juni 2026 — Pukul 10.00 WIB</strong></p>
      <div class="cd-grid">
        <div class="cd-box"><span class="cd-num" id="cd-d">00</span><span class="cd-unit">Hari</span></div>
        <div class="cd-box"><span class="cd-num" id="cd-h">00</span><span class="cd-unit">Jam</span></div>
        <div class="cd-box"><span class="cd-num" id="cd-m">00</span><span class="cd-unit">Menit</span></div>
        <div class="cd-box"><span class="cd-num" id="cd-s">00</span><span class="cd-unit">Detik</span></div>
      </div>
    </div>

    <!-- Lock Msg -->
    <div class="lock-msg" id="lock-msg">
      <strong>Formulir Terkunci</strong>
      Pencarian NISN akan aktif otomatis saat pengumuman dibuka pada 2 Juni 2026 pukul 10.00 WIB.
    </div>

    <!-- Search -->
    <div class="pub-card locked" id="search-card">
      <p class="field-lbl">Nomor Induk Siswa Nasional (NISN)</p>
      <div class="inp-row">
        <input id="nisn-input" type="text" placeholder="Contoh: 0107568178" maxlength="12" inputmode="numeric" />
        <button id="cek-btn" onclick="cekKelulusan()">Cek Sekarang</button>
      </div>
    </div>

    <div id="result"></div>

    <p class="pub-footer">
      Dokumen resmi kelulusan dapat diambil di sekolah sesuai jadwal.<br>
      Untuk informasi lebih lanjut, hubungi pihak sekolah.<br>
      <a class="admin-link-btn" onclick="showAdmin()">⚙ Panel Admin</a>
    </p>
  </div>
</div>

<!-- ================================================================
     ADMIN VIEW
     ================================================================ -->
<div id="admin-view" class="hidden">

  <!-- LOGIN -->
  <div id="admin-login">
    <div class="login-card">
      <div class="login-brand">
        <div class="login-icon">🔐</div>
        <p class="login-title">Panel Admin</p>
        <p class="login-sub">SMP Kristen Pancaran Berkat</p>
      </div>
      <div class="form-group">
        <label class="form-label">Kata Sandi Admin</label>
        <div class="pass-wrap">
          <input class="form-input" id="admin-pass-input" type="password" placeholder="Masukkan kata sandi" />
          <button class="eye-btn" type="button" onclick="toggleEye('admin-pass-input', this)" title="Tampilkan sandi">
            <svg viewBox="0 0 24 24"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/></svg>
          </button>
        </div>
      </div>
      <button class="btn-primary" onclick="doLogin()">Masuk ke Dashboard</button>
      <p class="login-err" id="login-err">Kata sandi salah. Coba lagi.</p>
      <p style="text-align:center;margin-top:16px;font-size:12px;color:#94a3b8;">
        <a href="#" onclick="backToPublic()" style="color:#94a3b8;">← Kembali ke halaman publik</a>
      </p>
    </div>
  </div>

  <!-- DASHBOARD -->
  <div id="admin-dashboard" class="hidden">

    <!-- Sidebar -->
    <aside class="sidebar">
      <div class="sidebar-brand">
        <p class="sidebar-school">SMP Kristen PB</p>
        <p class="sidebar-title">Panel Admin</p>
        <p class="sidebar-year">TA 2025 / 2026</p>
      </div>
      <nav class="sidebar-nav">
        <p class="nav-section-label">Menu</p>
        <div class="nav-item active" id="nav-students" onclick="switchTab('students')">
          <span class="nav-icon">👥</span> Manajemen Siswa
        </div>
        <div class="nav-item" id="nav-import" onclick="switchTab('import')">
          <span class="nav-icon">📥</span> Import Data
        </div>
        <div class="nav-item" id="nav-settings" onclick="switchTab('settings')">
          <span class="nav-icon">⚙️</span> Pengaturan
        </div>
        <div class="nav-item" id="nav-recap" onclick="switchTab('recap')">
          <span class="nav-icon">📋</span> Rekap Akses Siswa
        </div>
        <p class="nav-section-label" style="margin-top:16px">Halaman</p>
        <div class="nav-item" onclick="backToPublic()">
          <span class="nav-icon">🌐</span> Lihat Halaman Publik
        </div>
      </nav>
      <div class="sidebar-footer">
        <button class="btn-dm" id="btn-dark-mode" onclick="toggleDarkMode()">🌙 <span id="dm-label">Dark Mode</span></button>
        <div class="session-live-badge" id="sidebar-session-info">
          <strong>Menghitung...</strong>
          <span id="sidebar-session-text">—</span>
        </div>
        <button class="btn-logout" onclick="doLogout()">Keluar</button>
      </div>
    </aside>

    <!-- Main -->
    <div class="main-content">

      <!-- === STUDENTS TAB === -->
      <div id="tab-students">
        <div class="page-header">
          <p class="page-title">Manajemen Sesi Siswa</p>
          <p class="page-sub">Tentukan sesi pengecekan untuk setiap siswa. Siswa hanya bisa cek pada waktu sesinya.</p>
        </div>

        <div class="stats-row" id="stats-row"></div>

        <div class="toolbar">
          <input class="search-input" id="search-siswa" type="text" placeholder="🔍  Cari nama atau NISN..." oninput="renderTable()" />
          <select class="filter-select" id="filter-kelas" onchange="renderTable()">
            <option value="">Semua Kelas</option>
            <option value="IX A">IX A</option>
            <option value="IX B">IX B</option>
          </select>
          <select class="filter-select" id="filter-sesi" onchange="renderTable()">
            <option value="">Semua Sesi</option>
            <option value="1">Sesi 1</option>
            <option value="2">Sesi 2</option>
            <option value="3">Sesi 3</option>
            <option value="4">Sesi 4</option>
            <option value="0">Belum Ditentukan</option>
          </select>
          <button class="btn-bulk" onclick="bulkAssign(1)">Set Sesi 1 ▾</button>
          <button class="btn-bulk" onclick="bulkAssign(2)">Set Sesi 2 ▾</button>
          <button class="btn-bulk" onclick="bulkAssign(3)">Set Sesi 3 ▾</button>
          <button class="btn-bulk" onclick="bulkAssign(4)">Set Sesi 4 ▾</button>
          <button class="btn-save-all" onclick="saveAllSessions()">💾 Simpan Semua</button>
        </div>

        <div class="table-wrap">
          <table class="data-table">
            <thead>
              <tr>
                <th>#</th>
                <th>Nama Siswa</th>
                <th>NISN</th>
                <th>NIS</th>
                <th>Kelas</th>
                <th>Sesi Pengecekan</th>
              </tr>
            </thead>
            <tbody id="table-body"></tbody>
          </table>
        </div>
        <p style="font-size:12px;color:var(--slate-400);margin-top:10px;text-align:right;" id="table-count"></p>
      </div>

      <!-- === SETTINGS TAB === -->
      <div id="tab-settings" class="hidden">
        <div class="page-header">
          <p class="page-title">Pengaturan</p>
          <p class="page-sub">Konfigurasi waktu pengumuman, sesi, dan mode akses.</p>
        </div>

        <div class="settings-grid">

          <!-- Mode akses -->
          <div class="settings-card">
            <p class="settings-card-title"><span>🔧</span> Mode Akses</p>
            <div class="toggle-row">
              <div class="toggle-info">
                <p class="toggle-name">Mode Sesi Aktif</p>
                <p class="toggle-desc">Siswa hanya bisa cek saat sesi mereka berlangsung</p>
              </div>
              <button class="toggle-switch on" id="toggle-session-mode" onclick="toggleSessionMode()"></button>
            </div>
            <div class="toggle-row">
              <div class="toggle-info">
                <p class="toggle-name">Mode Terbuka</p>
                <p class="toggle-desc">Semua siswa bisa cek kapan saja (abaikan sesi)</p>
              </div>
              <button class="toggle-switch" id="toggle-open-mode" onclick="toggleOpenMode()"></button>
            </div>
            <div class="toggle-row">
              <div class="toggle-info">
                <p class="toggle-name">Aktifkan Countdown & Kunci Waktu</p>
                <p class="toggle-desc">ON = form terkunci sampai tanggal. OFF = form langsung bisa diakses</p>
              </div>
              <button class="toggle-switch on" id="toggle-countdown" onclick="toggleCountdown()"></button>
            </div>
          </div>

          <!-- Waktu pengumuman -->
          <div class="settings-card">
            <p class="settings-card-title"><span>📅</span> Waktu Pengumuman</p>
            <div class="setting-row">
              <p class="setting-label">Tanggal Pengumuman</p>
              <input class="setting-input" type="date" id="set-ann-date" value="2026-06-02" />
            </div>
            <div class="setting-row">
              <p class="setting-label">Jam Pengumuman (WIB)</p>
              <input class="setting-input" type="time" id="set-ann-time" value="10:00" />
            </div>
            <button class="btn-setting-save" onclick="saveTimeSetting()">Simpan Waktu</button>
            <p class="save-ok" id="time-save-ok">✅ Tersimpan!</p>
          </div>

          <!-- Waktu sesi -->
          <div class="settings-card">
            <p class="settings-card-title"><span>⏰</span> Jadwal Sesi</p>
            <div class="setting-row">
              <p class="setting-label">Sesi 1 — Mulai</p>
              <input class="setting-input" type="time" id="set-s1" value="10:00" />
              <p class="setting-desc">Siswa sesi 1 bisa cek mulai jam ini</p>
            </div>
            <div class="setting-row">
              <p class="setting-label">Sesi 2 — Mulai</p>
              <input class="setting-input" type="time" id="set-s2" value="10:15" />
              <p class="setting-desc">Siswa sesi 2 bisa cek mulai jam ini</p>
            </div>
            <div class="setting-row">
              <p class="setting-label">Sesi 3 — Mulai</p>
              <input class="setting-input" type="time" id="set-s3" value="10:30" />
              <p class="setting-desc">Siswa sesi 3 bisa cek mulai jam ini</p>
            </div>
            <div class="setting-row">
              <p class="setting-label">Sesi 4 — Mulai</p>
              <input class="setting-input" type="time" id="set-s4" value="10:45" />
              <p class="setting-desc">Siswa sesi 4 bisa cek mulai jam ini</p>
            </div>
            <button class="btn-setting-save" onclick="saveSessionTimes()">Simpan Jadwal</button>
            <p class="save-ok" id="sess-save-ok">✅ Tersimpan!</p>
          </div>

          <!-- Ganti password -->
          <div class="settings-card">
            <p class="settings-card-title"><span>🔑</span> Kata Sandi Admin</p>
            <div class="setting-row">
              <p class="setting-label">Kata Sandi Baru</p>
              <div class="pass-wrap">
                <input class="setting-input" type="password" id="new-pass1" placeholder="Masukkan kata sandi baru" />
                <button class="eye-btn" type="button" onclick="toggleEye('new-pass1',this)" title="Tampilkan">
                  <svg viewBox="0 0 24 24"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/></svg>
                </button>
              </div>
            </div>
            <div class="setting-row">
              <p class="setting-label">Konfirmasi Kata Sandi</p>
              <div class="pass-wrap">
                <input class="setting-input" type="password" id="new-pass2" placeholder="Ulangi kata sandi" />
                <button class="eye-btn" type="button" onclick="toggleEye('new-pass2',this)" title="Tampilkan">
                  <svg viewBox="0 0 24 24"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/></svg>
                </button>
              </div>
            </div>
            <button class="btn-setting-save" onclick="changePassword()">Ganti Kata Sandi</button>
            <p class="save-ok" id="pass-save-ok">✅ Kata sandi berhasil diubah!</p>
            <p style="display:none;color:var(--red-500);font-size:13px;margin-top:8px;" id="pass-err"></p>
          </div>

          <!-- Identitas Sekolah -->
          <div class="settings-card">
            <p class="settings-card-title"><span>🏫</span> Identitas Sekolah</p>
            <div class="setting-row">
              <p class="setting-label">Nama Sekolah</p>
              <input class="setting-input" type="text" id="set-school-name" placeholder="SMP Kristen Pancaran Berkat" />
              <p class="setting-desc">Nama yang tampil di halaman publik dan panel admin.</p>
            </div>
            <div class="setting-row">
              <p class="setting-label">Tahun Ajaran</p>
              <input class="setting-input" type="text" id="set-school-year" placeholder="2025 / 2026" />
              <p class="setting-desc">Contoh: 2025 / 2026</p>
            </div>
            <button class="btn-setting-save" onclick="saveSchoolInfo()">Simpan Identitas</button>
            <p class="save-ok" id="school-save-ok">✅ Identitas berhasil disimpan!</p>
          </div>

          <!-- Firebase Sync -->
          <div class="settings-card" style="grid-column:1/-1;">
            <p class="settings-card-title"><span>🔥</span> Sinkronisasi Real-time (Firebase)</p>
            <p style="font-size:12px;color:var(--slate-500);line-height:1.7;margin-bottom:14px;">
              Hubungkan ke Firebase Realtime Database agar perubahan pengaturan admin langsung terlihat di semua perangkat secara <em>live</em> — tanpa perlu reload.<br>
              <strong>Cara setup:</strong> Buka <a href="https://console.firebase.google.com" target="_blank" style="color:var(--blue-700);">console.firebase.google.com</a> → buat project → Realtime Database → buat database → Rules: ubah <code>".read"</code> dan <code>".write"</code> menjadi <code>true</code> → salin Database URL dan API Key di Project Settings.
            </p>
            <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:14px;">
              <div>
                <p class="setting-label">Database URL</p>
                <input class="setting-input" id="set-fb-url" placeholder="https://project-default-rtdb.firebaseio.com" style="width:100%;" />
              </div>
              <div>
                <p class="setting-label">API Key</p>
                <input class="setting-input" id="set-fb-key" placeholder="AIzaSy..." style="width:100%;" />
              </div>
            </div>
            <div style="display:flex;align-items:center;gap:14px;flex-wrap:wrap;">
              <button class="btn-setting-save" onclick="saveFirebaseConfig()">🔥 Hubungkan</button>
              <p class="save-ok" id="fb-save-ok">✅ Konfigurasi disimpan!</p>
              <span id="fb-status" style="font-size:12px;font-weight:700;color:var(--slate-400);">● Tidak terhubung</span>
            </div>
          </div>

        </div>
      </div>

      <!-- === RECAP TAB === -->
      <div id="tab-recap" class="hidden">
        <div class="page-header">
          <p class="page-title">Rekap Akses Siswa</p>
          <p class="page-sub">Log siswa yang telah mengakses dan mengecek status kelulusan, lengkap dengan tanggal dan waktu.</p>
        </div>
        <div class="recap-stats" id="recap-stats-row"></div>
        <div class="recap-toolbar">
          <input class="search-input" id="search-recap" type="text" placeholder="🔍  Cari nama atau NISN..." oninput="renderRecap()" style="flex:1;min-width:200px;" />
          <select class="filter-select" id="filter-recap-kelas" onchange="renderRecap()">
            <option value="">Semua Kelas</option>
            <option value="IX A">IX A</option>
            <option value="IX B">IX B</option>
          </select>
          <button class="btn-export-csv" onclick="exportRecapCSV()">⬇ Export CSV</button>
          <button class="btn-clear-log" onclick="clearRecapLog()">🗑 Hapus Log</button>
        </div>
        <div class="table-wrap">
          <table class="data-table">
            <thead>
              <tr>
                <th>#</th>
                <th>Nama Siswa</th>
                <th>NISN</th>
                <th>Kelas</th>
                <th>Mode</th>
                <th>Tanggal & Waktu Akses</th>
              </tr>
            </thead>
            <tbody id="recap-body"></tbody>
          </table>
        </div>
        <p style="font-size:12px;color:var(--slate-400);margin-top:10px;text-align:right;" id="recap-count"></p>
      </div>

      <!-- === IMPORT TAB === -->
      <div id="tab-import" class="hidden">
        <div class="page-header">
          <p class="page-title">Import Data Siswa</p>
          <p class="page-sub">Upload file Excel atau tambahkan siswa secara manual. Data akan langsung tersedia di sistem.</p>
        </div>

        <div class="import-2col">

          <!-- EXCEL UPLOAD CARD -->
          <div class="import-card">
            <p class="import-card-title"><span>📊</span> Upload Excel</p>

            <div class="import-actions" style="margin-bottom:14px;margin-top:0;">
              <button class="btn-tmpl" onclick="downloadTemplate()">⬇️ Download Template Excel</button>
              <span class="import-cnt" id="import-file-name">Belum ada file dipilih</span>
            </div>

            <!-- Drop Zone -->
            <div class="drop-zone" id="drop-zone"
                 onclick="document.getElementById('excel-file-input').click()"
                 ondragover="event.preventDefault();this.classList.add('drag')"
                 ondragleave="this.classList.remove('drag')"
                 ondrop="handleFileDrop(event)">
              <div class="dz-icon">📂</div>
              <p class="dz-txt">Klik atau seret file Excel ke sini</p>
              <p class="dz-sub">Format: .xlsx, .xls — Kolom: NISN, NIS, Nama, Kelas, TTL</p>
            </div>
            <input type="file" id="excel-file-input" accept=".xlsx,.xls" style="display:none" onchange="handleFileSelect(this)">

            <!-- Preview -->
            <div id="import-preview-section" style="display:none;margin-top:16px;">
              <p class="preview-label">Preview Data (<span id="preview-count">0</span> baris)</p>
              <div class="preview-wrap">
                <table>
                  <thead><tr>
                    <th>#</th><th>NISN</th><th>NIS</th><th>Nama</th><th>Kelas</th><th>TTL</th>
                  </tr></thead>
                  <tbody id="import-preview-body"></tbody>
                </table>
              </div>
              <div class="import-actions">
                <button class="btn-do-import" id="btn-do-import" onclick="doImportExcel(false)">➕ Gabungkan dengan Data Ada</button>
                <button class="btn-do-import" style="background:var(--red-500);" onclick="doImportExcel(true)">🔄 Ganti Semua Data</button>
                <span class="import-cnt" id="import-status"></span>
              </div>
            </div>
          </div>

          <!-- MANUAL INPUT CARD -->
          <div class="import-card">
            <p class="import-card-title"><span>✏️</span> Tambah Siswa Manual</p>
            <div class="manual-grid">
              <div class="manual-field">
                <label class="manual-lbl" for="m-nisn">NISN</label>
                <input class="manual-input" type="text" id="m-nisn" placeholder="0107568178" maxlength="12" inputmode="numeric">
              </div>
              <div class="manual-field">
                <label class="manual-lbl" for="m-nis">NIS</label>
                <input class="manual-input" type="text" id="m-nis" placeholder="2525" maxlength="10">
              </div>
              <div class="manual-field" style="grid-column:1/-1;">
                <label class="manual-lbl" for="m-nama">Nama Lengkap</label>
                <input class="manual-input" type="text" id="m-nama" placeholder="Abraham Alvino Edward Bale">
              </div>
              <div class="manual-field">
                <label class="manual-lbl" for="m-kelas">Kelas</label>
                <select class="manual-input" id="m-kelas" style="cursor:pointer;">
                  <option value="IX A">IX A</option>
                  <option value="IX B">IX B</option>
                  <option value="IX C">IX C</option>
                  <option value="IX D">IX D</option>
                </select>
              </div>
              <div class="manual-field">
                <label class="manual-lbl" for="m-ttl">Tempat, Tgl Lahir</label>
                <input class="manual-input" type="text" id="m-ttl" placeholder="Jakarta, 15 September 2010">
              </div>
            </div>
            <button class="btn-add-sw" onclick="addStudentManual()">➕ Tambah Siswa</button>
            <p style="font-size:12px;color:var(--slate-400);margin-top:10px;line-height:1.6;">
              Siswa yang ditambahkan akan langsung muncul di tabel Manajemen Siswa.
            </p>
          </div>

        </div>

        <!-- Current Student List (in Import tab) -->
        <div class="import-card">
          <div style="display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:10px;margin-bottom:16px;">
            <p class="import-card-title" style="margin-bottom:0;"><span>👥</span> Daftar Siswa Saat Ini (<span id="import-total-count">0</span>)</p>
            <div style="display:flex;gap:8px;flex-wrap:wrap;">
              <input class="search-input" type="text" id="import-search" placeholder="🔍 Cari nama / NISN..." oninput="renderImportList()" style="height:36px;font-size:13px;min-width:160px;">
              <button class="btn-clear-log" onclick="confirmClearStudents()" style="height:36px;">🗑 Hapus Semua</button>
            </div>
          </div>
          <div class="table-wrap" style="box-shadow:none;border:1px solid var(--slate-200);">
            <table class="data-table">
              <thead><tr><th>#</th><th>Nama Siswa</th><th>NISN</th><th>NIS</th><th>Kelas</th><th>TTL</th><th>Aksi</th></tr></thead>
              <tbody id="import-list-body"></tbody>
            </table>
          </div>
          <p style="font-size:12px;color:var(--slate-400);margin-top:8px;text-align:right;" id="import-list-count"></p>
        </div>

      </div>

    </div>
  </div>
</div>

<!-- ================================================================
     SCRIPT
     ================================================================ -->
<script>
// ======================================================
// DATA SISWA (50 siswa)
// ======================================================
const LOGO_WATERMARK = "data:image/png;base64,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";
let SISWA = [
  {nisn:"0107568178",nis:"2525",nama:"Abraham Alvino Edward Bale",kelas:"IX A",ttl:"Jakarta, 15 September 2010"},
  {nisn:"0116201697",nis:"2527",nama:"Chilla Pricillia",kelas:"IX A",ttl:"Jakarta, 17 April 2011"},
  {nisn:"0113949122",nis:"2528",nama:"Fendy Junior",kelas:"IX A",ttl:"Jakarta, 3 Juni 2011"},
  {nisn:"0118078873",nis:"2700",nama:"Florencia Lim",kelas:"IX A",ttl:"Sampit, 24 Februari 2012"},
  {nisn:"0111148520",nis:"2529",nama:"Holly Christiyani Condro",kelas:"IX A",ttl:"Jakarta, 26 September 2011"},
  {nisn:"0112064188",nis:"2530",nama:"Irene Susanti",kelas:"IX A",ttl:"Jakarta, 15 Oktober 2011"},
  {nisn:"0106141940",nis:"2531",nama:"Juliani",kelas:"IX A",ttl:"Jakarta, 5 Juli 2010"},
  {nisn:"0119673063",nis:"2533",nama:"Justin Oktavianus",kelas:"IX A",ttl:"Jakarta, 6 Oktober 2011"},
  {nisn:"0128306781",nis:"2534",nama:"Justine Benedict Dherline",kelas:"IX A",ttl:"Jakarta, 22 Juli 2011"},
  {nisn:"0115343415",nis:"2535",nama:"Jvellyn Ervina",kelas:"IX A",ttl:"Jakarta, 23 Juni 2011"},
  {nisn:"0117062221",nis:"2536",nama:"Kelvin Smart",kelas:"IX A",ttl:"Jakarta, 26 Maret 2011"},
  {nisn:"0119655951",nis:"2538",nama:"Lionel Ethan",kelas:"IX A",ttl:"Pontianak, 16 Juli 2011"},
  {nisn:"0111642032",nis:"2539",nama:"Louisa Priscil Komala",kelas:"IX A",ttl:"Jakarta, 26 Oktober 2011"},
  {nisn:"0113706795",nis:"2540",nama:"Mikha Aurelly Kusuma",kelas:"IX A",ttl:"Jakarta, 15 Juni 2011"},
  {nisn:"0106635842",nis:"2541",nama:"Nicholas Wisata",kelas:"IX A",ttl:"Jakarta, 5 Agustus 2010"},
  {nisn:"0104483046",nis:"2542",nama:"Peter Alfredo",kelas:"IX A",ttl:"Jakarta, 11 Desember 2010"},
  {nisn:"0114104051",nis:"2543",nama:"Raynardy Divian Wijaya",kelas:"IX A",ttl:"Jakarta, 14 Juli 2011"},
  {nisn:"0118126148",nis:"2544",nama:"Shellyna Novalia G",kelas:"IX A",ttl:"Jakarta, 30 November 2011"},
  {nisn:"0104563975",nis:"2545",nama:"Tristan Hermawan",kelas:"IX A",ttl:"Jakarta, 20 November 2010"},
  {nisn:"0116136505",nis:"2701",nama:"Vanessa",kelas:"IX A",ttl:"Jakarta, 20 Februari 2011"},
  {nisn:"0094419530",nis:"2546",nama:"Vicko Putra Boy Sxander",kelas:"IX A",ttl:"Jakarta, 31 Juli 2009"},
  {nisn:"0116972256",nis:"2547",nama:"Victoria Ivana Xiao",kelas:"IX A",ttl:"Jakarta, 14 Maret 2011"},
  {nisn:"0117642712",nis:"2548",nama:"Vinny Ztevia",kelas:"IX A",ttl:"Jakarta, 19 November 2011"},
  {nisn:"0093821097",nis:"2549",nama:"Violla Hillary Honey",kelas:"IX A",ttl:"Jakarta, 6 September 2009"},
  {nisn:"0113132310",nis:"2550",nama:"Wycliff Jose Adriano",kelas:"IX A",ttl:"Jakarta, 1 November 2011"},
  {nisn:"0103477238",nis:"2551",nama:"Andreas Adianto",kelas:"IX B",ttl:"Batam, 22 Juli 2010"},
  {nisn:"0117417719",nis:"2552",nama:"Aurelia Oktavina Rusli",kelas:"IX B",ttl:"Jakarta, 17 Oktober 2011"},
  {nisn:"0114504143",nis:"2553",nama:"Candy Agustyn",kelas:"IX B",ttl:"Jakarta, 9 Agustus 2011"},
  {nisn:"0123857634",nis:"2555",nama:"Christovel Gregory S",kelas:"IX B",ttl:"Jakarta, 20 Juni 2012"},
  {nisn:"0111295554",nis:"2642",nama:"Debora Elizia",kelas:"IX B",ttl:"Jakarta, 15 September 2011"},
  {nisn:"0108006343",nis:"2558",nama:"Enzo Lie",kelas:"IX B",ttl:"Jakarta, 22 November 2010"},
  {nisn:"0114148088",nis:"2559",nama:"Gisel Lay Aprillya",kelas:"IX B",ttl:"Jakarta, 28 April 2011"},
  {nisn:"0101514148",nis:"2560",nama:"Ivana Verlyn",kelas:"IX B",ttl:"Jakarta, 19 November 2010"},
  {nisn:"0118583241",nis:"2561",nama:"Ivander Lyv",kelas:"IX B",ttl:"Jakarta, 14 Juli 2011"},
  {nisn:"0118640865",nis:"2562",nama:"Jacquine Valencia Chuck",kelas:"IX B",ttl:"Jakarta, 30 November 2011"},
  {nisn:"0117837639",nis:"2563",nama:"Jennifer Anabella Q",kelas:"IX B",ttl:"Jakarta, 21 Januari 2011"},
  {nisn:"0101150626",nis:"2564",nama:"Jerry Yan Saputra",kelas:"IX B",ttl:"Jakarta, 12 April 2010"},
  {nisn:"0111911589",nis:"2565",nama:"Jesen",kelas:"IX B",ttl:"Pemangkat, 3 April 2011"},
  {nisn:"0118213369",nis:"2566",nama:"Jessica Anabella Gracia S",kelas:"IX B",ttl:"Jakarta, 8 Juli 2011"},
  {nisn:"0106495118",nis:"2567",nama:"Lionel Nieville",kelas:"IX B",ttl:"Jakarta, 20 September 2010"},
  {nisn:"0115689317",nis:"2568",nama:"Muhammad Jeffren",kelas:"IX B",ttl:"Jakarta, 25 Juni 2011"},
  {nisn:"0102805734",nis:"2569",nama:"Marnike Gunawan",kelas:"IX B",ttl:"Jakarta, 2 Maret 2010"},
  {nisn:"0116894609",nis:"2640",nama:"Matthew Gianes Netthanel",kelas:"IX B",ttl:"Jakarta, 14 Juli 2011"},
  {nisn:"0116185864",nis:"2570",nama:"Michael",kelas:"IX B",ttl:"Jakarta, 2 April 2011"},
  {nisn:"0124532326",nis:"2571",nama:"Moreno Orlando Mackenzo",kelas:"IX B",ttl:"Jakarta, 8 Oktober 2012"},
  {nisn:"0115454117",nis:"2572",nama:"Nathasya Halim",kelas:"IX B",ttl:"Jakarta, 12 Maret 2011"},
  {nisn:"0123322647",nis:"2573",nama:"Rava Herianza",kelas:"IX B",ttl:"Bogor, 5 November 2011"},
  {nisn:"0115989391",nis:"2702",nama:"Steven Whie",kelas:"IX B",ttl:"Jakarta, 20 Agustus 2011"},
  {nisn:"0114814322",nis:"2575",nama:"Summer Valencia Yong",kelas:"IX B",ttl:"Jakarta, 2 Februari 2011"},
  {nisn:"0114733967",nis:"2576",nama:"Tju Jun Sen",kelas:"IX B",ttl:"Jakarta, 15 Maret 2011"},
];

// Frozen base copy for merge/reset reference
const SISWA_BASE = SISWA.map(s => Object.assign({}, s));

// Build lookup
const DB = {};
SISWA.forEach(s => DB[s.nisn] = s);

// ======================================================
// STORAGE HELPERS (localStorage — runs in real browser)
// ======================================================
const LS = {
  get: (k, def) => { try { const v = localStorage.getItem(k); return v !== null ? JSON.parse(v) : def; } catch(e){ return def; } },
  set: (k, v)  => { try { localStorage.setItem(k, JSON.stringify(v)); } catch(e){} },
  raw: (k, v)  => { try { localStorage.setItem(k, JSON.stringify(v)); } catch(e){} } // tanpa Firebase sync
};

// ======================================================
// FIREBASE REALTIME SYNC
// ======================================================
const FB_SYNC_KEYS = ['pk_settings', 'pk_sessions', 'pk_access_log'];
let fbDB = null;

function getFBConfig() {
  // Konfigurasi Firebase hardcoded — tidak perlu input manual di admin
  return {
    apiKey: "AIzaSyA2zmQljCGbEK3l5rbBxOwGgvnHcPHsZR8",
    databaseURL: "https://pro-1-f00a8-default-rtdb.asia-southeast1.firebasedatabase.app"
  };
}

function _doInitFirebase(cfg) {
  try {
    firebase.initializeApp(cfg);
    fbDB = firebase.database();

    // indikator koneksi
    fbDB.ref('.info/connected').on('value', snap => {
      updateFBStatus(!!snap.val(), snap.val() ? 'Terhubung 🟢' : 'Menghubungkan...');
    });

    // ── Listener: settings ──────────────────────────────
    fbDB.ref('pk_settings').on('value', snap => {
      if (!snap.exists()) return;
      const val = snap.val();
      const old = getSettings();
      LS.raw('pk_settings', val); // simpan lokal tanpa trigger FB write lagi
      updateCountdown();
      // Jika countdown baru dinyalakan → bersihkan hasil yang tampil
      if (val.showCountdown && old.showCountdown === false) {
        document.getElementById('result').innerHTML = '';
        document.getElementById('nisn-input').value = '';
      }
      // Refresh admin dashboard jika sedang terbuka
      const dash = document.getElementById('admin-dashboard');
      if (dash && !dash.classList.contains('hidden')) { loadSettings(); renderStats(); }
    });

    // ── Listener: sessions ──────────────────────────────
    fbDB.ref('pk_sessions').on('value', snap => {
      const val = snap.val() || {};
      LS.raw('pk_sessions', val);
      const dash = document.getElementById('admin-dashboard');
      if (dash && !dash.classList.contains('hidden')) {
        editSessions = Object.assign({}, val);
        renderStats(); renderTable();
      }
    });

    // ── Listener: access log ────────────────────────────
    // BUG FIX: Firebase RTDB mengubah array menjadi object {0:{...},1:{...}}
    // sehingga harus dikonversi balik ke array dengan Object.values()
    fbDB.ref('pk_access_log').on('value', snap => {
      const raw = snap.val();
      let val = [];
      if (raw) {
        if (Array.isArray(raw)) val = raw;
        else val = Object.values(raw); // konversi object Firebase → array
      }
      LS.raw('pk_access_log', val);
      if (currentTab === 'recap') renderRecap();
    });

    // ── Push data lokal ke Firebase jika Firebase kosong ─
    fbDB.ref('pk_settings').once('value', snap => {
      if (!snap.exists()) fbDB.ref('pk_settings').set(getSettings());
    });
    fbDB.ref('pk_sessions').once('value', snap => {
      if (!snap.exists()) fbDB.ref('pk_sessions').set(getSessions());
    });

  } catch(err) {
    updateFBStatus(false, 'Error: ' + err.message);
    console.error('Firebase init error:', err);
  }
}

function initFirebase() {
  const cfg = getFBConfig();
  if (!cfg || !cfg.databaseURL || !cfg.apiKey) { updateFBStatus(false, 'Tidak terhubung'); return; }
  // Hapus semua app lama dulu (delete() adalah async, harus di-await agar tidak bentrok)
  if (firebase.apps.length > 0) {
    Promise.all(firebase.apps.map(app => app.delete()))
      .then(() => _doInitFirebase(cfg))
      .catch(() => _doInitFirebase(cfg));
  } else {
    _doInitFirebase(cfg);
  }
}

// Override LS.set → juga tulis ke Firebase untuk key yang disync
const _origLSset = LS.set.bind(LS);
LS.set = function(key, value) {
  _origLSset(key, value);
  if (fbDB && FB_SYNC_KEYS.includes(key)) {
    fbDB.ref(key).set(value).catch(e => console.warn('Firebase write:', e));
  }
};

function updateFBStatus(ok, msg) {
  const el = document.getElementById('fb-status');
  if (!el) return;
  el.style.color = ok ? 'var(--green-700)' : 'var(--slate-400)';
  el.textContent = '● ' + msg;
}

function saveFirebaseConfig() {
  const url = document.getElementById('set-fb-url').value.trim();
  const key = document.getElementById('set-fb-key').value.trim();
  if (!url || !key) { showToast('⚠️ Isi Database URL dan API Key terlebih dahulu'); return; }
  // Validasi format URL Firebase
  if (!url.includes('firebaseio.com') && !url.includes('firebasedatabase.app')) {
    showToast('⚠️ Database URL tidak valid. Harus mengandung firebaseio.com atau firebasedatabase.app');
    return;
  }
  if (!key.startsWith('AIza')) {
    showToast('⚠️ API Key tidak valid. Harus diawali dengan "AIza..."');
    return;
  }
  const cfg = { apiKey: key, databaseURL: url };
  LS.raw('pk_fb_config', cfg); // simpan tanpa sync ke FB
  showOk('fb-save-ok');
  updateFBStatus(false, 'Menghubungkan...');
  initFirebase(); // langsung hubungkan
  showToast('🔥 Mencoba menghubungkan ke Firebase...', true);
}

function loadFirebaseSettings() {
  const cfg = getFBConfig();
  const urlEl = document.getElementById('set-fb-url');
  const keyEl = document.getElementById('set-fb-key');
  if (urlEl && cfg) { urlEl.value = cfg.databaseURL || ''; keyEl.value = cfg.apiKey || ''; }
  if (fbDB) {
    fbDB.ref('.info/connected').once('value', snap => updateFBStatus(!!snap.val(), snap.val() ? 'Terhubung 🟢' : 'Tidak terhubung'));
  }
}

function getSessions()  { return LS.get('pk_sessions', {}); }
function getSettings()  {
  return LS.get('pk_settings', {
    annDate: '2026-06-02', annTime: '10:00',
    s1: '10:00', s2: '10:15', s3: '10:30', s4: '10:45',
    sessionMode: true,  // true = session-based, false = open
    openMode: false,
    showCountdown: true
  });
}
function getAdminPass() { return LS.get('pk_admin_pass', 'admin2026'); }

// ======================================================
// TIME HELPERS
// ======================================================
function pad(n) { return String(n).padStart(2,'0'); }

function getTargetDate() {
  const s = getSettings();
  return new Date(s.annDate + 'T' + s.annTime + ':00');
}

function getActiveSession() {
  const s = getSettings();
  const now = new Date();
  const target = getTargetDate();
  if (now < target) return null; // Not opened yet

  const today = now;
  const [s1h,s1m] = s.s1.split(':').map(Number);
  const [s2h,s2m] = s.s2.split(':').map(Number);
  const [s3h,s3m] = s.s3.split(':').map(Number);
  const [s4h,s4m] = (s.s4||'10:45').split(':').map(Number);

  const base = [today.getFullYear(), today.getMonth(), today.getDate()];
  const sess1 = new Date(...base, s1h, s1m, 0);
  const sess2 = new Date(...base, s2h, s2m, 0);
  const sess3 = new Date(...base, s3h, s3m, 0);
  const sess4 = new Date(...base, s4h, s4m, 0);

  if (now >= sess4) return 4;
  if (now >= sess3) return 3;
  if (now >= sess2) return 2;
  if (now >= sess1) return 1;
  return 0; // Announced but before any session
}

// ======================================================
// PUBLIC PAGE LOGIC
// ======================================================
function updateCountdown() {
  const settings = getSettings();
  const target  = getTargetDate();
  const now     = new Date();
  const diff    = target - now;
  const card    = document.getElementById('search-card');
  const lockMsg = document.getElementById('lock-msg');
  const cdSection = document.getElementById('cd-section');

  // === COUNTDOWN DIMATIKAN: langsung buka akses, sembunyikan countdown & pesan kunci ===
  if (settings.showCountdown === false) {
    cdSection.style.display = 'none';
    lockMsg.style.display   = 'none';
    card.classList.remove('locked');
    return;
  }

  // === COUNTDOWN AKTIF: tampilkan dan kunci berdasar tanggal ===
  cdSection.style.display = '';

  // Selalu update teks lock-msg dari pengaturan terkini
  const annDate = new Date(settings.annDate + 'T' + settings.annTime + ':00');
  const tglOpts = { weekday:'long', year:'numeric', month:'long', day:'numeric' };
  const tglStr  = annDate.toLocaleDateString('id-ID', tglOpts);
  lockMsg.querySelector('strong').textContent = 'Formulir Terkunci';
  lockMsg.lastChild.textContent = ` Pencarian NISN akan aktif otomatis saat pengumuman dibuka pada ${tglStr} pukul ${settings.annTime} WIB.`;

  if (diff <= 0) {
    ['cd-d','cd-h','cd-m','cd-s'].forEach(id => document.getElementById(id).textContent = '00');
    document.getElementById('cd-label').textContent  = 'Pengumuman Telah Dibuka';
    document.getElementById('cd-announce').innerHTML = 'Masukkan NISN Anda untuk melihat status kelulusan.';
    lockMsg.style.display = 'none';
    card.classList.remove('locked');
    return;
  }

  // Masih countdown: kunci formulir
  document.getElementById('cd-label').textContent  = 'Pengumuman Dibuka Dalam';
  document.getElementById('cd-announce').innerHTML = `${tglStr}, <strong>Pukul ${settings.annTime} WIB</strong>`;
  lockMsg.style.display = '';
  card.classList.add('locked');

  const d = Math.floor(diff / 86400000);
  const h = Math.floor((diff % 86400000) / 3600000);
  const m = Math.floor((diff % 3600000)  / 60000);
  const s = Math.floor((diff % 60000)    / 1000);

  document.getElementById('cd-d').textContent = pad(d);
  document.getElementById('cd-h').textContent = pad(h);
  document.getElementById('cd-m').textContent = pad(m);
  document.getElementById('cd-s').textContent = pad(s);
}

function cekKelulusan() {
  const now      = new Date();
  const target   = getTargetDate();
  const settings = getSettings();
  const cdOff    = (settings.showCountdown === false); // mode bebas

  // Jika countdown aktif, cek apakah tanggal sudah tiba
  if (!cdOff && now < target) { showToast('Pengumuman belum dibuka.'); return; }

  const input = document.getElementById('nisn-input').value.trim().replace(/\s+/g,'');
  const el    = document.getElementById('result');

  if (!input) {
    el.innerHTML = nfCard('✏️','NISN Belum Diisi','Masukkan NISN Anda terlebih dahulu untuk mengecek status kelulusan.','');
    return;
  }

  const siswa = DB[input];
  if (!siswa) {
    el.innerHTML = nfCard('🔍','NISN Tidak Ditemukan',`NISN <strong>${input}</strong> tidak terdaftar dalam sistem.<br>Periksa kembali NISN Anda atau hubungi pihak sekolah.`,'');
    return;
  }

  // Cek sesi — dilewati jika countdown OFF atau openMode aktif
  if (!cdOff && !settings.openMode) {
    const sessions = getSessions();
    const studentSession = sessions[input] || 0; // 0 = unassigned
    const active = getActiveSession();

    if (studentSession === 0 || active === null || active === 0 || studentSession > active) {
      const quotes = [
        { teks: "Karena Aku ini mengetahui rancangan-rancangan apa yang ada pada-Ku mengenai kamu, demikianlah firman TUHAN, yaitu rancangan damai sejahtera dan bukan rancangan kecelakaan, untuk memberikan kepadamu hari depan yang penuh harapan.", ref: "Yeremia 29:11" },
        { teks: "Segala perkara dapat kutanggung di dalam Dia yang memberi kekuatan kepadaku.", ref: "Filipi 4:13" },
        { teks: "TUHAN adalah gembalaku, takkan kekurangan aku.", ref: "Mazmur 23:1" },
        { teks: "Janganlah takut, sebab Aku menyertai engkau, janganlah bimbang, sebab Aku ini Allahmu; Aku akan meneguhkan, bahkan akan menolong engkau.", ref: "Yesaya 41:10" },
        { teks: "Percayalah kepada TUHAN dengan segenap hatimu dan janganlah bersandar kepada pengertianmu sendiri.", ref: "Amsal 3:5" },
        { teks: "Mintalah, maka akan diberikan kepadamu; carilah, maka kamu akan mendapat; ketoklah, maka pintu akan dibukakan bagimu.", ref: "Matius 7:7" },
        { teks: "Sebab Allah memberikan kepada kita bukan roh ketakutan, melainkan roh yang membangkitkan kekuatan, kasih dan ketertiban.", ref: "2 Timotius 1:7" },
        { teks: "Kuatkanlah hatimu dan teguhkanlah hatimu, janganlah takut dan jangan gemetar karena mereka, sebab TUHAN, Allahmu, Dialah yang berjalan menyertai engkau.", ref: "Ulangan 31:6" },
        { teks: "Adalah baik menantikan dengan diam pertolongan TUHAN.", ref: "Ratapan 3:26" },
        { teks: "Orang yang menanti-nantikan TUHAN mendapat kekuatan baru: mereka seumpama rajawali yang naik terbang dengan kekuatan sayapnya.", ref: "Yesaya 40:31" },
      ];
      const q = quotes[Math.floor(Math.random() * quotes.length)];
      el.innerHTML = nfCard('⏳','Mohon Menunggu',`<em style="display:block;margin-top:10px;color:#78909c;font-size:13px;line-height:1.7;">"${q.teks}"</em><span style="display:block;margin-top:6px;font-size:11px;font-weight:700;letter-spacing:1px;color:#90a4ae;">— ${q.ref}</span>`,'');
      return;
    }
  }

  // Lulus! — catat log akses
  const now2 = new Date();
  const logEntry = {
    nisn: siswa.nisn,
    nama: siswa.nama,
    kelas: siswa.kelas,
    mode: cdOff ? 'Bebas' : (settings.openMode ? 'Terbuka' : 'Sesi'),
    ts: now2.toISOString()
  };
  // BUG FIX: data dari Firebase bisa berupa object, bukan array — normalisasi dulu
  const rawLog = LS.get('pk_access_log', []);
  const accessLog = Array.isArray(rawLog) ? rawLog : Object.values(rawLog);
  accessLog.unshift(logEntry);
  LS.set('pk_access_log', accessLog.slice(0, 500)); // simpan maks 500 entri

  buatKonfeti();

  el.innerHTML = `
    <div class="card-lulus">
      <img class="card-watermark" src="${LOGO_WATERMARK}" alt="watermark" />
      <div class="lulus-top">
        <p class="student-name">${siswa.nama}</p>
      </div>
      <div class="card-body">
        <div class="info-row"><span class="info-label">NISN</span><span class="info-val mono">${siswa.nisn}</span></div>
        <div class="info-row"><span class="info-label">NIS</span><span class="info-val">${siswa.nis}</span></div>
        <div class="info-row"><span class="info-label">Kelas</span><span class="info-val">${siswa.kelas}</span></div>
        <div class="info-row"><span class="info-label">Tempat, Tgl Lahir</span><span class="info-val">${siswa.ttl}</span></div>
        <div class="info-row"><span class="info-label">Status</span><span class="info-val"><span class="status-pill">✓ LULUS</span></span></div>
      </div>
      <div class="card-foot">
        Selamat atas kelulusan Anda! Tuhan memberkati masa depan Anda.
      </div>
    </div>`;
}

function nfCard(icon, title, sub, extra) {
  return `<div class="card-nf">
    <div class="nf-icon">${icon}</div>
    <p class="nf-title">${title}</p>
    <p class="nf-sub">${sub}</p>${extra}
  </div>`;
}

document.getElementById('nisn-input').addEventListener('keydown', e => {
  if (e.key === 'Enter') cekKelulusan();
});

// ======================================================
// CONFETTI
// ======================================================
function buatKonfeti() {
  const c = document.getElementById('conf');
  c.innerHTML = '';
  const colors = ['#FFD54F','#42A5F5','#EF5350','#66BB6A','#AB47BC','#fff','#FF8A65'];
  for (let i = 0; i < 90; i++) {
    const p = document.createElement('div');
    p.className = 'cp';
    p.style.left = Math.random()*100+'%';
    p.style.background = colors[Math.floor(Math.random()*colors.length)];
    p.style.borderRadius = Math.random()>.5?'50%':'3px';
    p.style.animationDelay = Math.random()*1.5+'s';
    p.style.animationDuration = (2+Math.random())+'s';
    c.appendChild(p);
  }
  setTimeout(() => c.innerHTML='', 4500);
}

// ======================================================
// TOAST
// ======================================================
function showToast(msg, green=false) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.className = 'toast show' + (green?' green':'');
  setTimeout(() => t.className='toast', 3000);
}

// ======================================================
// ADMIN NAVIGATION
// ======================================================
function showAdmin() {
  document.getElementById('public-view').classList.add('hidden');
  document.getElementById('admin-view').classList.remove('hidden');
  document.getElementById('admin-login').classList.remove('hidden');
  document.getElementById('admin-dashboard').classList.add('hidden');
}

function backToPublic() {
  document.getElementById('admin-view').classList.add('hidden');
  document.getElementById('public-view').classList.remove('hidden');
}

function doLogin() {
  const pass = document.getElementById('admin-pass-input').value;
  const err  = document.getElementById('login-err');
  if (pass === getAdminPass()) {
    err.style.display = 'none';
    document.getElementById('admin-login').classList.add('hidden');
    document.getElementById('admin-dashboard').classList.remove('hidden');
    initDashboard();
  } else {
    err.style.display = 'block';
    document.getElementById('admin-pass-input').value = '';
    document.getElementById('admin-pass-input').focus();
  }
}

function doLogout() {
  document.getElementById('admin-dashboard').classList.add('hidden');
  document.getElementById('admin-login').classList.remove('hidden');
  document.getElementById('admin-pass-input').value = '';
}

document.getElementById('admin-pass-input').addEventListener('keydown', e => {
  if (e.key === 'Enter') doLogin();
});

// ======================================================
// ADMIN DASHBOARD
// ======================================================
let currentTab = 'students';
let editSessions = {}; // local edits (not yet saved)

function switchTab(tab) {
  currentTab = tab;
  ['students','import','settings','recap'].forEach(t => {
    document.getElementById('tab-'+t).classList.toggle('hidden', t !== tab);
    document.getElementById('nav-'+t).classList.toggle('active', t === tab);
  });
  if (tab === 'students') renderTable();
  if (tab === 'settings') loadSettings();
  if (tab === 'recap') renderRecap();
  if (tab === 'import') { renderImportList(); }
}

function initDashboard() {
  editSessions = Object.assign({}, getSessions());
  updateSidebarSession();
  renderStats();
  renderTable();
  loadSettings();
  setInterval(updateSidebarSession, 5000);
}

function updateSidebarSession() {
  const active = getActiveSession();
  const target = getTargetDate();
  const now    = new Date();
  const el1    = document.getElementById('sidebar-session-info');
  const el2    = document.getElementById('sidebar-session-text');
  const labels = ['Belum ada sesi aktif','Sesi 1 Aktif','Sesi 2 Aktif','Sesi 3 Aktif','Sesi 4 Aktif'];
  if (!el1) return;

  if (now < target) {
    el1.innerHTML = '<strong>⏳ Belum Dibuka</strong><span>Pengumuman belum dimulai</span>';
  } else if (active === null || active === 0) {
    el1.innerHTML = '<strong>⏰ Menunggu Sesi</strong><span>Belum ada sesi aktif</span>';
  } else {
    el1.innerHTML = `<strong>🟢 ${labels[active]}</strong><span>Siswa sesi ${active} bisa cek</span>`;
  }
}

function renderStats() {
  const sessions = editSessions;
  const counts = {1:0, 2:0, 3:0, 4:0, 0:0};
  SISWA.forEach(s => {
    const sess = sessions[s.nisn] || 0;
    counts[sess] = (counts[sess]||0)+1;
  });
  document.getElementById('stats-row').innerHTML = `
    <div class="stat-card"><p class="stat-num">${SISWA.length}</p><p class="stat-label">Total Siswa</p></div>
    <div class="stat-card s1"><p class="stat-num">${counts[1]}</p><p class="stat-label">Sesi 1</p></div>
    <div class="stat-card s2"><p class="stat-num">${counts[2]}</p><p class="stat-label">Sesi 2</p></div>
    <div class="stat-card s3"><p class="stat-num">${counts[3]}</p><p class="stat-label">Sesi 3</p></div>
    <div class="stat-card s4"><p class="stat-num">${counts[4]}</p><p class="stat-label">Sesi 4</p></div>
    <div class="stat-card un"><p class="stat-num">${counts[0]}</p><p class="stat-label">Belum Ditentukan</p></div>
  `;
}

function renderTable() {
  const q      = document.getElementById('search-siswa').value.toLowerCase();
  const kelas  = document.getElementById('filter-kelas').value;
  const sesiF  = document.getElementById('filter-sesi').value;
  const tbody  = document.getElementById('table-body');

  const filtered = SISWA.filter(s => {
    const matchQ = !q || s.nama.toLowerCase().includes(q) || s.nisn.includes(q);
    const matchK = !kelas || s.kelas === kelas;
    const sess   = editSessions[s.nisn] || 0;
    const matchS = sesiF === '' || String(sess) === sesiF;
    return matchQ && matchK && matchS;
  });

  document.getElementById('table-count').textContent = `Menampilkan ${filtered.length} dari ${SISWA.length} siswa`;

  const sessColors = ['un','s1','s2','s3','s4'];
  tbody.innerHTML = filtered.map((s, i) => {
    const curr = editSessions[s.nisn] || 0;
    return `<tr>
      <td style="color:var(--slate-400);font-size:12px;">${i+1}</td>
      <td class="td-name">${s.nama}</td>
      <td class="td-nisn">${s.nisn}</td>
      <td style="font-size:13px;color:var(--slate-600);">${s.nis}</td>
      <td><span class="td-class">${s.kelas}</span></td>
      <td>
        <select class="session-select ${sessColors[curr]}" 
                onchange="onSessionChange('${s.nisn}', this)"
                data-nisn="${s.nisn}">
          <option value="0" ${curr===0?'selected':''}>— Belum Ditentukan</option>
          <option value="1" ${curr===1?'selected':''}>Sesi 1 (${getSettings().s1} WIB)</option>
          <option value="2" ${curr===2?'selected':''}>Sesi 2 (${getSettings().s2} WIB)</option>
          <option value="3" ${curr===3?'selected':''}>Sesi 3 (${getSettings().s3} WIB)</option>
          <option value="4" ${curr===4?'selected':''}>Sesi 4 (${getSettings().s4||'10:45'} WIB)</option>
        </select>
      </td>
    </tr>`;
  }).join('');
}

function onSessionChange(nisn, sel) {
  const val = parseInt(sel.value);
  editSessions[nisn] = val;
  const colors = ['un','s1','s2','s3','s4'];
  sel.className = 'session-select ' + colors[val];
  renderStats();
}

function saveAllSessions() {
  LS.set('pk_sessions', editSessions);
  showToast('✅ Sesi berhasil disimpan!', true);
  renderStats();
}

function bulkAssign(sess) {
  const kelas = document.getElementById('filter-kelas').value;
  const q     = document.getElementById('search-siswa').value.toLowerCase();
  let count   = 0;
  SISWA.forEach(s => {
    const matchK = !kelas || s.kelas === kelas;
    const matchQ = !q || s.nama.toLowerCase().includes(q) || s.nisn.includes(q);
    if (matchK && matchQ) {
      editSessions[s.nisn] = sess;
      count++;
    }
  });
  renderTable();
  renderStats();
  showToast(`✅ ${count} siswa diset ke Sesi ${sess}`, true);
}

// ======================================================
// SETTINGS
// ======================================================
function loadSettings() {
  const s = getSettings();
  document.getElementById('set-ann-date').value = s.annDate;
  document.getElementById('set-ann-time').value = s.annTime;
  document.getElementById('set-s1').value = s.s1;
  document.getElementById('set-s2').value = s.s2;
  document.getElementById('set-s3').value = s.s3;
  document.getElementById('set-s4').value = s.s4||'10:45';
  const sm = document.getElementById('toggle-session-mode');
  const om = document.getElementById('toggle-open-mode');
  const cd = document.getElementById('toggle-countdown');
  sm.className = 'toggle-switch' + (s.sessionMode ? ' on' : '');
  om.className = 'toggle-switch' + (s.openMode    ? ' on' : '');
  cd.className = 'toggle-switch' + (s.showCountdown !== false ? ' on' : '');
  loadFirebaseSettings();
}

function saveTimeSetting() {
  const s = getSettings();
  s.annDate = document.getElementById('set-ann-date').value;
  s.annTime = document.getElementById('set-ann-time').value;
  LS.set('pk_settings', s);
  showOk('time-save-ok');
  showToast('✅ Waktu pengumuman disimpan!', true);
}

function saveSessionTimes() {
  const s  = getSettings();
  const s1 = document.getElementById('set-s1').value;
  const s2 = document.getElementById('set-s2').value;
  const s3 = document.getElementById('set-s3').value;
  const s4 = document.getElementById('set-s4').value;
  if (s1 >= s2 || s2 >= s3 || s3 >= s4) { showToast('⚠️ Urutan waktu sesi tidak valid!'); return; }
  s.s1 = s1; s.s2 = s2; s.s3 = s3; s.s4 = s4;
  LS.set('pk_settings', s);
  showOk('sess-save-ok');
  renderTable();
  showToast('✅ Jadwal sesi disimpan!', true);
}

function toggleSessionMode() {
  const s = getSettings();
  s.sessionMode = !s.sessionMode;
  if (s.sessionMode) s.openMode = false;
  LS.set('pk_settings', s);
  loadSettings();
}

function toggleOpenMode() {
  const s = getSettings();
  s.openMode = !s.openMode;
  if (s.openMode) s.sessionMode = false;
  LS.set('pk_settings', s);
  loadSettings();
}

function changePassword() {
  const p1 = document.getElementById('new-pass1').value;
  const p2 = document.getElementById('new-pass2').value;
  const err = document.getElementById('pass-err');
  err.style.display = 'none';
  if (!p1) { err.textContent='Kata sandi tidak boleh kosong.'; err.style.display='block'; return; }
  if (p1 !== p2) { err.textContent='Konfirmasi kata sandi tidak cocok.'; err.style.display='block'; return; }
  LS.set('pk_admin_pass', p1);
  document.getElementById('new-pass1').value='';
  document.getElementById('new-pass2').value='';
  showOk('pass-save-ok');
  showToast('✅ Kata sandi berhasil diubah!', true);
}

function showOk(id) {
  const el = document.getElementById(id);
  el.style.display='block';
  setTimeout(()=>el.style.display='none',3000);
}

function toggleCountdown() {
  const s = getSettings();
  s.showCountdown = (s.showCountdown === false) ? true : false;
  LS.set('pk_settings', s);
  loadSettings();
  updateCountdown();
  // Saat countdown dinyalakan, bersihkan hasil yang sudah tampil
  if (s.showCountdown) {
    document.getElementById('result').innerHTML = '';
    document.getElementById('nisn-input').value = '';
  }
  showToast(s.showCountdown ? '🔒 Countdown aktif — form terkunci berdasar tanggal' : '🔓 Countdown dimatikan — form langsung bisa diakses', true);
}

// ======================================================
// RECAP ACCESS LOG
// ======================================================
function renderRecap() {
  const log    = LS.get('pk_access_log', []);
  const q      = document.getElementById('search-recap').value.toLowerCase();
  const kelas  = document.getElementById('filter-recap-kelas').value;
  const tbody  = document.getElementById('recap-body');

  const filtered = log.filter(e => {
    const matchQ = !q || e.nama.toLowerCase().includes(q) || e.nisn.includes(q);
    const matchK = !kelas || e.kelas === kelas;
    return matchQ && matchK;
  });

  document.getElementById('recap-count').textContent = `Menampilkan ${filtered.length} dari ${log.length} entri`;

  // Stats
  const unique = [...new Set(log.map(e => e.nisn))].length;
  document.getElementById('recap-stats-row').innerHTML = `
    <div class="recap-stat-pill"><span class="rsp-num">${log.length}</span> Total Pengecekan</div>
    <div class="recap-stat-pill"><span class="rsp-num">${unique}</span> Siswa Unik</div>
    <div class="recap-stat-pill"><span class="rsp-num">${log.filter(e=>e.mode==='Terbuka').length}</span> Mode Terbuka</div>
    <div class="recap-stat-pill"><span class="rsp-num">${log.filter(e=>e.mode==='Sesi').length}</span> Mode Sesi</div>
  `;

  if (filtered.length === 0) {
    tbody.innerHTML = `<tr><td colspan="6"><div class="log-empty"><div class="le-icon">📭</div>Belum ada data akses siswa.</div></td></tr>`;
    return;
  }

  tbody.innerHTML = filtered.map((e, i) => {
    const dt   = new Date(e.ts);
    const tgl  = dt.toLocaleDateString('id-ID', {weekday:'short', day:'2-digit', month:'short', year:'numeric'});
    const jam  = dt.toLocaleTimeString('id-ID', {hour:'2-digit', minute:'2-digit', second:'2-digit'});
    const modeClass = e.mode === 'Terbuka' ? 'open' : 's1';
    return `<tr>
      <td style="color:var(--slate-400);font-size:12px;">${i+1}</td>
      <td class="td-name">${e.nama}</td>
      <td class="td-nisn">${e.nisn}</td>
      <td><span class="td-class">${e.kelas}</span></td>
      <td><span class="badge-sesi ${modeClass}">${e.mode}</span></td>
      <td class="td-time">${tgl} — ${jam}</td>
    </tr>`;
  }).join('');
}

function clearRecapLog() {
  const existing = document.getElementById('confirm-clear-bar');
  if (existing) { existing.remove(); return; }

  const bar = document.createElement('div');
  bar.id = 'confirm-clear-bar';
  bar.style.cssText = 'background:#fee2e2;border:1.5px solid #fca5a5;border-radius:10px;padding:12px 16px;display:flex;align-items:center;gap:12px;flex-wrap:wrap;margin-bottom:14px;animation:fadeUp .3s ease both;';
  bar.innerHTML = `
    <span style="font-size:13px;font-weight:600;color:#b91c1c;flex:1;">Yakin hapus semua log akses? Tidak bisa dibatalkan.</span>
    <button onclick="confirmClearLog()" style="height:36px;padding:0 16px;background:#dc2626;border:none;border-radius:8px;color:#fff;font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;font-weight:700;cursor:pointer;">Ya, Hapus</button>
    <button onclick="document.getElementById('confirm-clear-bar').remove()" style="height:36px;padding:0 16px;background:#fff;border:1.5px solid #fca5a5;border-radius:8px;color:#b91c1c;font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;font-weight:700;cursor:pointer;">Batal</button>
  `;
  const toolbar = document.querySelector('.recap-toolbar');
  toolbar.parentNode.insertBefore(bar, toolbar);
}

function confirmClearLog() {
  LS.set('pk_access_log', []);
  const bar = document.getElementById('confirm-clear-bar');
  if (bar) bar.remove();
  renderRecap();
  showToast('🗑 Log akses berhasil dihapus.', false);
}

function exportRecapCSV() {
  const log = LS.get('pk_access_log', []);
  if (log.length === 0) { showToast('Tidak ada data untuk diekspor.'); return; }
  const rows = [['No','Nama','NISN','Kelas','Mode','Tanggal','Jam']];
  log.forEach((e, i) => {
    const dt = new Date(e.ts);
    rows.push([
      i+1, e.nama, e.nisn, e.kelas, e.mode,
      dt.toLocaleDateString('id-ID'),
      dt.toLocaleTimeString('id-ID')
    ]);
  });
  const csv  = rows.map(r => r.map(c => `"${c}"`).join(',')).join('\n');
  const blob = new Blob(['\uFEFF'+csv], {type:'text/csv;charset=utf-8;'});
  const url  = URL.createObjectURL(blob);
  const a    = document.createElement('a');
  a.href = url; a.download = 'rekap-akses-siswa.csv'; a.click();
  URL.revokeObjectURL(url);
  showToast('✅ CSV berhasil diekspor!', true);
}

// ======================================================
// INIT
// ======================================================
// Init dengan error handling agar halaman tetap tampil meski Firebase gagal
try { initFirebase(); } catch(e) { console.error('Firebase gagal:', e); }
try { updateCountdown(); } catch(e) { console.error('Countdown error:', e); }
setInterval(() => { try { updateCountdown(); } catch(e) {} }, 1000);

// ======================================================
// DARK MODE
// ======================================================
const EYE_OPEN = `<svg viewBox="0 0 24 24"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/></svg>`;
const EYE_SHUT = `<svg viewBox="0 0 24 24"><path d="M17.94 17.94A10.07 10.07 0 0 1 12 20c-7 0-11-8-11-8a18.45 18.45 0 0 1 5.06-5.94M9.9 4.24A9.12 9.12 0 0 1 12 4c7 0 11 8 11 8a18.5 18.5 0 0 1-2.16 3.19m-6.72-1.07a3 3 0 1 1-4.24-4.24"/><line x1="1" y1="1" x2="23" y2="23"/></svg>`;

function toggleDarkMode() {
  const isDark = document.body.classList.toggle('dark');
  localStorage.setItem('pk_dark_mode', isDark ? '1' : '0');
  const btn = document.getElementById('btn-dark-mode');
  if (btn) btn.innerHTML = isDark
    ? '\u2600\ufe0f <span id="dm-label">Light Mode</span>'
    : '\ud83c\udf19 <span id="dm-label">Dark Mode</span>';
}
function loadDarkMode() {
  if (localStorage.getItem('pk_dark_mode') === '1') {
    document.body.classList.add('dark');
    const btn = document.getElementById('btn-dark-mode');
    if (btn) btn.innerHTML = '\u2600\ufe0f <span id="dm-label">Light Mode</span>';
  }
}
loadDarkMode();

// ======================================================
// EYE TOGGLE
// ======================================================
function toggleEye(inputId, btn) {
  const inp = document.getElementById(inputId);
  if (!inp) return;
  const show = inp.type === 'password';
  inp.type = show ? 'text' : 'password';
  btn.innerHTML = show ? EYE_SHUT : EYE_OPEN;
}

// ======================================================
// SCHOOL IDENTITY
// ======================================================
function getSchoolInfo() {
  return LS.get('pk_school_info', { name: 'SMP Kristen Pancaran Berkat', year: '2025 / 2026' });
}
function applySchoolInfo() {
  const info = getSchoolInfo();
  // Public page elements
  document.querySelectorAll('.school-name').forEach(el => el.textContent = info.name);
  document.querySelectorAll('.year-pill').forEach(el => el.textContent = 'Tahun Ajaran ' + info.year);
  // Sidebar elements
  const sSchool = document.querySelector('.sidebar-school');
  if (sSchool) sSchool.textContent = info.name.substring(0, 18);
  const sYear = document.querySelector('.sidebar-year');
  if (sYear) sYear.textContent = 'TA ' + info.year;
  // Page title
  document.title = 'Pengumuman Kelulusan \u2013 ' + info.name + ' ' + info.year;
}
function saveSchoolInfo() {
  const name = document.getElementById('set-school-name').value.trim();
  const year = document.getElementById('set-school-year').value.trim();
  if (!name || !year) { showToast('\u26a0\ufe0f Nama sekolah dan tahun ajaran wajib diisi!'); return; }
  LS.set('pk_school_info', { name, year });
  applySchoolInfo();
  showOk('school-save-ok');
  showToast('\u2705 Identitas sekolah berhasil disimpan!', true);
}
function loadSchoolInfo() {
  const info = getSchoolInfo();
  const nameEl = document.getElementById('set-school-name');
  const yearEl = document.getElementById('set-school-year');
  if (nameEl) nameEl.value = info.name;
  if (yearEl) yearEl.value = info.year;
}
// Apply on page load
applySchoolInfo();

// ======================================================
// IMPORT DATA — EXCEL
// ======================================================
let importPreviewData = [];

function handleFileDrop(e) {
  e.preventDefault();
  document.getElementById('drop-zone').classList.remove('drag');
  const file = e.dataTransfer.files[0];
  if (file) processExcelFile(file);
}
function handleFileSelect(inp) {
  const file = inp.files[0];
  if (file) processExcelFile(file);
}
function processExcelFile(file) {
  document.getElementById('import-file-name').textContent = file.name;
  const reader = new FileReader();
  reader.onload = function(e) {
    try {
      const wb  = XLSX.read(e.target.result, {type:'binary'});
      const ws  = wb.Sheets[wb.SheetNames[0]];
      const raw = XLSX.utils.sheet_to_json(ws, {defval:''});
      importPreviewData = raw.map(r => ({
        nisn : String(r['NISN'] || r['nisn'] || '').trim(),
        nis  : String(r['NIS']  || r['nis']  || '').trim(),
        nama : String(r['Nama'] || r['nama'] || r['NAMA'] || '').trim(),
        kelas: String(r['Kelas']|| r['kelas']|| r['KELAS']|| '').trim(),
        ttl  : String(r['TTL']  || r['ttl']  || r['Tempat, Tgl Lahir'] || '').trim()
      })).filter(r => r.nisn && r.nama);
      showImportPreview();
    } catch(err) { showToast('❌ Gagal membaca file: ' + err.message); }
  };
  reader.readAsBinaryString(file);
}
function showImportPreview() {
  const sec = document.getElementById('import-preview-section');
  const tbody = document.getElementById('import-preview-body');
  document.getElementById('preview-count').textContent = importPreviewData.length;
  tbody.innerHTML = importPreviewData.slice(0,50).map((r,i) =>
    `<tr><td style="color:var(--slate-400);font-size:12px">${i+1}</td><td class="td-nisn">${r.nisn}</td><td style="font-size:13px">${r.nis}</td><td style="font-size:13px;font-weight:600">${r.nama}</td><td><span class="td-class">${r.kelas}</span></td><td style="font-size:12px">${r.ttl}</td></tr>`
  ).join('');
  sec.style.display = '';
  document.getElementById('import-status').textContent = '';
}
function doImportExcel(replace) {
  if (!importPreviewData.length) { showToast('⚠️ Tidak ada data untuk diimport'); return; }
  if (replace && !confirm('Yakin ingin MENGGANTI SEMUA data siswa? Tindakan ini tidak bisa dibatalkan.')) return;
  const extras = LS.get('pk_extra_students', []);
  let base = replace ? [] : [...SISWA_BASE];
  const existing = new Set(base.map(s => s.nisn));
  let added = 0;
  importPreviewData.forEach(r => {
    if (!existing.has(r.nisn)) { base.push(r); existing.add(r.nisn); added++; }
  });
  LS.set('pk_extra_students', base.filter(s => !SISWA_BASE.find(b => b.nisn === s.nisn)));
  if (replace) { LS.set('pk_extra_students', importPreviewData); base = importPreviewData; }
  rebuildSISWA();
  document.getElementById('import-status').textContent = `✅ ${added} siswa berhasil diimport!`;
  renderImportList(); renderTable(); renderStats();
  showToast('✅ Import selesai!', true);
}

// ======================================================
// IMPORT DATA — MANUAL ADD
// ======================================================
function addStudentManual() {
  const nisn  = document.getElementById('m-nisn').value.trim();
  const nis   = document.getElementById('m-nis').value.trim();
  const nama  = document.getElementById('m-nama').value.trim();
  const kelas = document.getElementById('m-kelas').value;
  const ttl   = document.getElementById('m-ttl').value.trim();
  if (!nisn || !nama) { showToast('⚠️ NISN dan Nama wajib diisi!'); return; }
  const allSiswa = [...SISWA_BASE, ...LS.get('pk_extra_students', [])];
  if (allSiswa.find(s => s.nisn === nisn)) { showToast('⚠️ NISN sudah terdaftar!'); return; }
  const extras = LS.get('pk_extra_students', []);
  extras.push({nisn, nis, nama, kelas, ttl});
  LS.set('pk_extra_students', extras);
  rebuildSISWA();
  ['m-nisn','m-nis','m-nama','m-ttl'].forEach(id => document.getElementById(id).value = '');
  renderImportList(); renderTable(); renderStats();
  showToast('✅ Siswa berhasil ditambahkan!', true);
}
function deleteStudent(nisn) {
  const extras = LS.get('pk_extra_students', []).filter(s => s.nisn !== nisn);
  LS.set('pk_extra_students', extras);
  rebuildSISWA();
  renderImportList(); renderTable(); renderStats();
  showToast('🗑 Siswa dihapus.');
}
function confirmClearStudents() {
  if (!confirm('Hapus SEMUA siswa tambahan (bukan data bawaan)?')) return;
  LS.set('pk_extra_students', []);
  rebuildSISWA();
  renderImportList(); renderTable(); renderStats();
  showToast('🗑 Semua siswa tambahan dihapus.');
}
function renderImportList() {
  const q = (document.getElementById('import-search')?.value || '').toLowerCase();
  const tbody = document.getElementById('import-list-body');
  if (!tbody) return;
  const filtered = SISWA.filter(s => !q || s.nama.toLowerCase().includes(q) || s.nisn.includes(q));
  document.getElementById('import-total-count').textContent = SISWA.length;
  document.getElementById('import-list-count').textContent = `Menampilkan ${filtered.length} dari ${SISWA.length} siswa`;
  const isExtra = nisn => !SISWA_BASE.find(b => b.nisn === nisn);
  tbody.innerHTML = filtered.map((s, i) => `<tr>
    <td style="color:var(--slate-400);font-size:12px">${i+1}</td>
    <td class="td-name">${s.nama}${isExtra(s.nisn)? ' <span style="font-size:10px;font-weight:700;background:#e0f2fe;color:#0369a1;border-radius:4px;padding:1px 6px">BARU</span>':''}</td>
    <td class="td-nisn">${s.nisn}</td>
    <td style="font-size:13px;color:var(--slate-600)">${s.nis}</td>
    <td><span class="td-class">${s.kelas}</span></td>
    <td style="font-size:12px;color:var(--slate-500)">${s.ttl}</td>
    <td>${isExtra(s.nisn)?`<button onclick="deleteStudent('${s.nisn}')" style="height:30px;padding:0 12px;background:#fee2e2;border:1px solid #fca5a5;border-radius:7px;color:#dc2626;font-size:12px;font-weight:700;cursor:pointer;">Hapus</button>`:'-'}</td>
  </tr>`).join('');
}

// ======================================================
// DOWNLOAD TEMPLATE EXCEL
// ======================================================
function downloadTemplate() {
  if (typeof XLSX === 'undefined') { showToast('⚠️ SheetJS belum dimuat, coba refresh.'); return; }
  const ws_data = [
    ['NISN','NIS','Nama','Kelas','TTL'],
    ['0107568178','2525','Abraham Alvino Edward Bale','IX A','Jakarta, 15 September 2010'],
    ['0116201697','2527','Chilla Pricillia','IX A','Jakarta, 17 April 2011'],
    ['','','','','']
  ];
  const wb = XLSX.utils.book_new();
  const ws = XLSX.utils.aoa_to_sheet(ws_data);
  ws['!cols'] = [{wch:14},{wch:8},{wch:34},{wch:8},{wch:30}];
  // Style header row
  ['A1','B1','C1','D1','E1'].forEach(cell => {
    if (!ws[cell]) return;
    ws[cell].s = {font:{bold:true},fill:{fgColor:{rgb:'1565C0'}},alignment:{horizontal:'center'}};
  });
  XLSX.utils.book_append_sheet(wb, ws, 'Template Siswa');
  XLSX.writeFile(wb, 'template-import-siswa.xlsx');
  showToast('✅ Template Excel berhasil diunduh!', true);
}

// Rebuild SISWA array from base + extras
function rebuildSISWA() {
  const extras = LS.get('pk_extra_students', []);
  // Merge: base first, extras without duplicates
  const seen = new Set(SISWA_BASE.map(s => s.nisn));
  const merged = [...SISWA_BASE];
  extras.forEach(s => { if (!seen.has(s.nisn)) { merged.push(s); seen.add(s.nisn); } });
  SISWA.length = 0;
  merged.forEach(s => SISWA.push(s));
  // Rebuild DB lookup
  Object.keys(DB).forEach(k => delete DB[k]);
  SISWA.forEach(s => DB[s.nisn] = s);
}
// Load extras on init
rebuildSISWA();
</script>
</body>
</html>
