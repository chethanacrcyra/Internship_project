# Internship_project

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LumiScan AI - Broken Street Light Detection & Landmark Synthesis</title>
  <meta name="description" content="AI-Powered Broken Street Light Detection, Building Color & Signboard Landmark Synthesis">
  
  <!-- CSS & CDN Bindings -->
  <link rel="stylesheet" href="styles.css">
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" crossorigin="" />
</head>
<body>
  <!-- Top Navigation Bar -->
  <header class="navbar">
    <a href="#" class="brand">
      <div class="brand-icon">⚡</div>
      <div class="brand-title">LumiScan <span>AI</span></div>
    </a>
    
    <nav class="nav-links">
      <button id="navBtnReporter" class="nav-btn active">
        <span>📸</span> Citizen Reporter & AI Scan
      </button>
      <button id="navBtnDashboard" class="nav-btn">
        <span>🗺️</span> Municipal Admin Map
      </button>
    </nav>
    
    <div class="nav-controls">
      <button id="themeToggleBtn" class="theme-toggle-btn">
        ☀️ Light Mode
      </button>
    </div>
  </header>
