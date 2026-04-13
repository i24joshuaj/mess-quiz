<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Scheme Eligibility Portal – Surveyor Tool</title>
<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@400;600;700;800&family=Noto+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --saffron: #FF6B00;
    --saffron-light: #FF8C35;
    --saffron-glow: rgba(255,107,0,0.15);
    --navy: #0D2445;
    --navy-mid: #163364;
    --navy-light: #1E4080;
    --green: #138808;
    --green-light: #1AAD0A;
    --cream: #FFF8F0;
    --white: #FFFFFF;
    --text-dark: #1A1A2E;
    --text-mid: #3D4A6B;
    --text-light: #7A8AAD;
    --border: rgba(13,36,69,0.12);
    --card-bg: #FFFFFF;
    --tag-pension: #7B4EA6;
    --tag-insurance: #1565C0;
    --tag-health: #00796B;
    --tag-finance: #E65100;
    --tag-women: #AD1457;
    --tag-agriculture: #2E7D32;
    --tag-skill: #6A1B9A;
    --tag-housing: #4E342E;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Noto Sans', sans-serif;
    background: var(--cream);
    color: var(--text-dark);
    min-height: 100vh;
    position: relative;
    overflow-x: hidden;
  }

  /* Tricolor accent bar */
  .tricolor-bar {
    height: 5px;
    background: linear-gradient(to right, var(--saffron) 33.3%, white 33.3% 66.6%, var(--green) 66.6%);
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    box-shadow: 0 1px 8px rgba(0,0,0,0.18);
  }

  header {
    background: var(--navy);
    padding: 18px 40px;
    display: flex;
    align-items: center;
    gap: 20px;
    position: sticky;
    top: 5px;
    z-index: 90;
    box-shadow: 0 4px 20px rgba(0,0,0,0.3);
  }

  .emblem {
    width: 52px; height: 52px;
    background: radial-gradient(circle, var(--saffron-light), var(--saffron));
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-size: 26px;
    box-shadow: 0 0 0 3px rgba(255,255,255,0.3);
    flex-shrink: 0;
  }

  .header-text h1 {
    font-family: 'Baloo 2', cursive;
    font-size: 1.5rem;
    font-weight: 800;
    color: var(--white);
    letter-spacing: 0.02em;
    line-height: 1.1;
  }

  .header-text p {
    font-size: 0.78rem;
    color: rgba(255,255,255,0.6);
    letter-spacing: 0.08em;
    text-transform: uppercase;
    margin-top: 2px;
  }

  .header-badge {
    margin-left: auto;
    background: rgba(255,107,0,0.2);
    border: 1px solid var(--saffron);
    color: var(--saffron-light);
    padding: 4px 14px;
    border-radius: 20px;
    font-size: 0.72rem;
    font-weight: 600;
    letter-spacing: 0.06em;
    text-transform: uppercase;
  }

  .main-layout {
    display: grid;
    grid-template-columns: 380px 1fr;
    gap: 0;
    min-height: calc(100vh - 85px);
    margin-top: 0;
  }

  /* LEFT PANEL */
  .left-panel {
    background: var(--white);
    border-right: 1px solid var(--border);
    padding: 28px 24px;
    overflow-y: auto;
    max-height: calc(100vh - 85px);
    position: sticky;
    top: 85px;
  }

  .panel-title {
    font-family: 'Baloo 2', cursive;
    font-size: 1rem;
    font-weight: 700;
    color: var(--navy);
    letter-spacing: 0.04em;
    text-transform: uppercase;
    margin-bottom: 20px;
    padding-bottom: 10px;
    border-bottom: 2px solid var(--saffron);
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .form-section {
    margin-bottom: 22px;
  }

  .form-section-label {
    font-size: 0.7rem;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--text-light);
    margin-bottom: 8px;
  }

  .form-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
  }

  .field-group {
    display: flex;
    flex-direction: column;
    gap: 5px;
  }

  .field-group label {
    font-size: 0.78rem;
    font-weight: 500;
    color: var(--text-mid);
  }

  .field-group input,
  .field-group select {
    padding: 9px 12px;
    border: 1.5px solid var(--border);
    border-radius: 8px;
    font-size: 0.85rem;
    font-family: 'Noto Sans', sans-serif;
    color: var(--text-dark);
    background: var(--cream);
    transition: border-color 0.2s, box-shadow 0.2s;
    width: 100%;
  }

  .field-group input:focus,
  .field-group select:focus {
    outline: none;
    border-color: var(--saffron);
    box-shadow: 0 0 0 3px var(--saffron-glow);
  }

  .toggle-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 8px;
  }

  .toggle-btn {
    padding: 8px 10px;
    border: 1.5px solid var(--border);
    border-radius: 8px;
    background: var(--cream);
    font-size: 0.78rem;
    font-family: 'Noto Sans', sans-serif;
    color: var(--text-mid);
    cursor: pointer;
    transition: all 0.15s;
    display: flex;
    align-items: center;
    gap: 6px;
    font-weight: 500;
  }

  .toggle-btn.active {
    background: var(--saffron-glow);
    border-color: var(--saffron);
    color: var(--saffron);
    font-weight: 600;
  }

  .toggle-btn:hover:not(.active) {
    border-color: var(--navy-light);
    color: var(--navy);
    background: rgba(13,36,69,0.04);
  }

  .check-grid {
    display: flex;
    flex-direction: column;
    gap: 8px;
  }

  .check-item {
    display: flex;
    align-items: center;
    gap: 10px;
    cursor: pointer;
    padding: 8px 10px;
    border-radius: 8px;
    border: 1.5px solid var(--border);
    background: var(--cream);
    transition: all 0.15s;
    user-select: none;
  }

  .check-item.active {
    border-color: var(--saffron);
    background: var(--saffron-glow);
  }

  .check-item input[type="checkbox"] {
    accent-color: var(--saffron);
    width: 16px;
    height: 16px;
    cursor: pointer;
    flex-shrink: 0;
    pointer-events: none;
  }

  .check-item span {
    font-size: 0.82rem;
    font-weight: 500;
    color: var(--text-mid);
  }

  .check-item.active span {
    color: var(--saffron);
    font-weight: 600;
  }

  .find-btn {
    width: 100%;
    padding: 14px;
    background: linear-gradient(135deg, var(--saffron), var(--saffron-light));
    color: white;
    border: none;
    border-radius: 10px;
    font-family: 'Baloo 2', cursive;
    font-size: 1rem;
    font-weight: 700;
    cursor: pointer;
    letter-spacing: 0.04em;
    transition: all 0.2s;
    box-shadow: 0 4px 16px rgba(255,107,0,0.35);
    margin-top: 4px;
  }

  .find-btn:hover {
    transform: translateY(-1px);
    box-shadow: 0 6px 22px rgba(255,107,0,0.45);
  }

  .find-btn:active { transform: translateY(0); }

  .reset-btn {
    width: 100%;
    padding: 10px;
    background: transparent;
    color: var(--text-light);
    border: 1.5px solid var(--border);
    border-radius: 10px;
    font-family: 'Noto Sans', sans-serif;
    font-size: 0.82rem;
    cursor: pointer;
    margin-top: 8px;
    transition: all 0.15s;
  }

  .reset-btn:hover {
    border-color: var(--text-mid);
    color: var(--text-mid);
  }

  /* RIGHT PANEL */
  .right-panel {
    padding: 28px 32px;
    overflow-y: auto;
  }

  .results-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 22px;
    flex-wrap: wrap;
    gap: 12px;
  }

  .results-count {
    font-family: 'Baloo 2', cursive;
    font-size: 1.3rem;
    font-weight: 800;
    color: var(--navy);
  }

  .results-count span {
    color: var(--saffron);
  }

  .filter-tags {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }

  .filter-tag {
    padding: 4px 12px;
    border-radius: 20px;
    font-size: 0.72rem;
    font-weight: 600;
    letter-spacing: 0.04em;
    cursor: pointer;
    transition: all 0.15s;
    border: 1.5px solid transparent;
  }

  .filter-tag.all {
    background: var(--navy);
    color: white;
  }

  .filter-tag[data-cat="Insurance"] { background: rgba(21,101,192,0.1); color: #1565C0; border-color: #1565C0; }
  .filter-tag[data-cat="Pension"] { background: rgba(123,78,166,0.1); color: #7B4EA6; border-color: #7B4EA6; }
  .filter-tag[data-cat="Health"] { background: rgba(0,121,107,0.1); color: #00796B; border-color: #00796B; }
  .filter-tag[data-cat="Finance"] { background: rgba(230,81,0,0.1); color: #E65100; border-color: #E65100; }
  .filter-tag[data-cat="Women"] { background: rgba(173,20,87,0.1); color: #AD1457; border-color: #AD1457; }
  .filter-tag[data-cat="Agriculture"] { background: rgba(46,125,50,0.1); color: #2E7D32; border-color: #2E7D32; }
  .filter-tag[data-cat="Skill"] { background: rgba(106,27,154,0.1); color: #6A1B9A; border-color: #6A1B9A; }
  .filter-tag[data-cat="Housing"] { background: rgba(78,52,46,0.1); color: #4E342E; border-color: #4E342E; }

  .schemes-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
    gap: 18px;
  }

  .scheme-card {
    background: var(--card-bg);
    border-radius: 14px;
    border: 1.5px solid var(--border);
    overflow: hidden;
    transition: all 0.2s;
    display: flex;
    flex-direction: column;
    position: relative;
  }

  .scheme-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 32px rgba(13,36,69,0.12);
    border-color: rgba(255,107,0,0.3);
  }

  .card-stripe {
    height: 4px;
    width: 100%;
  }

  .scheme-card[data-cat="Insurance"] .card-stripe { background: #1565C0; }
  .scheme-card[data-cat="Pension"] .card-stripe { background: #7B4EA6; }
  .scheme-card[data-cat="Health"] .card-stripe { background: #00796B; }
  .scheme-card[data-cat="Finance"] .card-stripe { background: #E65100; }
  .scheme-card[data-cat="Women"] .card-stripe { background: #AD1457; }
  .scheme-card[data-cat="Agriculture"] .card-stripe { background: #2E7D32; }
  .scheme-card[data-cat="Skill"] .card-stripe { background: #6A1B9A; }
  .scheme-card[data-cat="Housing"] .card-stripe { background: #4E342E; }

  .card-body {
    padding: 18px;
    flex: 1;
  }

  .card-header {
    display: flex;
    align-items: flex-start;
    gap: 12px;
    margin-bottom: 12px;
  }

  .card-icon {
    font-size: 26px;
    flex-shrink: 0;
    line-height: 1;
    margin-top: 2px;
  }

  .card-title {
    font-family: 'Baloo 2', cursive;
    font-size: 0.95rem;
    font-weight: 700;
    color: var(--navy);
    line-height: 1.3;
  }

  .card-subtitle {
    font-size: 0.72rem;
    color: var(--text-light);
    margin-top: 2px;
    font-weight: 500;
  }

  .card-benefit {
    background: linear-gradient(135deg, rgba(255,107,0,0.08), rgba(255,107,0,0.04));
    border: 1px solid rgba(255,107,0,0.2);
    border-radius: 8px;
    padding: 8px 12px;
    margin-bottom: 12px;
  }

  .card-benefit-label {
    font-size: 0.65rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--saffron);
    margin-bottom: 2px;
  }

  .card-benefit-value {
    font-size: 0.9rem;
    font-weight: 600;
    color: var(--text-dark);
    line-height: 1.4;
  }

  .eligibility-list {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 5px;
    margin-bottom: 12px;
  }

  .eligibility-list li {
    display: flex;
    align-items: flex-start;
    gap: 6px;
    font-size: 0.78rem;
    color: var(--text-mid);
    line-height: 1.4;
  }

  .eligibility-list li::before {
    content: '✓';
    color: var(--green);
    font-weight: 700;
    font-size: 0.75rem;
    flex-shrink: 0;
    margin-top: 1px;
  }

  .doc-chips {
    display: flex;
    flex-wrap: wrap;
    gap: 5px;
    margin-top: 10px;
  }

  .doc-chip {
    padding: 3px 9px;
    background: rgba(13,36,69,0.06);
    border-radius: 20px;
    font-size: 0.68rem;
    color: var(--text-mid);
    font-weight: 500;
  }

  .card-cat-badge {
    position: absolute;
    top: 14px;
    right: 14px;
    padding: 3px 10px;
    border-radius: 20px;
    font-size: 0.65rem;
    font-weight: 700;
    letter-spacing: 0.05em;
    text-transform: uppercase;
  }

  .scheme-card[data-cat="Insurance"] .card-cat-badge { background: rgba(21,101,192,0.1); color: #1565C0; }
  .scheme-card[data-cat="Pension"] .card-cat-badge { background: rgba(123,78,166,0.1); color: #7B4EA6; }
  .scheme-card[data-cat="Health"] .card-cat-badge { background: rgba(0,121,107,0.1); color: #00796B; }
  .scheme-card[data-cat="Finance"] .card-cat-badge { background: rgba(230,81,0,0.1); color: #E65100; }
  .scheme-card[data-cat="Women"] .card-cat-badge { background: rgba(173,20,87,0.1); color: #AD1457; }
  .scheme-card[data-cat="Agriculture"] .card-cat-badge { background: rgba(46,125,50,0.1); color: #2E7D32; }
  .scheme-card[data-cat="Skill"] .card-cat-badge { background: rgba(106,27,154,0.1); color: #6A1B9A; }
  .scheme-card[data-cat="Housing"] .card-cat-badge { background: rgba(78,52,46,0.1); color: #4E342E; }

  .card-footer {
    padding: 12px 18px;
    background: rgba(13,36,69,0.03);
    border-top: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .premium-info {
    font-size: 0.72rem;
    color: var(--text-light);
    font-style: italic;
  }

  .more-btn {
    font-size: 0.72rem;
    font-weight: 600;
    color: var(--navy-light);
    background: none;
    border: none;
    cursor: pointer;
    text-decoration: underline;
    text-underline-offset: 2px;
    padding: 0;
  }

  /* Empty State */
  .empty-state {
    grid-column: 1 / -1;
    text-align: center;
    padding: 60px 20px;
    color: var(--text-light);
  }

  .empty-state .big-icon { font-size: 52px; margin-bottom: 14px; }
  .empty-state h3 { font-family: 'Baloo 2', cursive; font-size: 1.2rem; color: var(--text-mid); margin-bottom: 6px; }
  .empty-state p { font-size: 0.85rem; }

  /* Initial state */
  .initial-state {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 400px;
    text-align: center;
    padding: 40px;
  }

  .initial-state .big-icon { font-size: 64px; margin-bottom: 20px; opacity: 0.8; }
  .initial-state h2 { font-family: 'Baloo 2', cursive; font-size: 1.5rem; color: var(--navy); margin-bottom: 10px; }
  .initial-state p { font-size: 0.9rem; color: var(--text-light); max-width: 360px; line-height: 1.6; }

  .stat-row {
    display: flex;
    gap: 20px;
    margin-top: 24px;
    justify-content: center;
  }

  .stat-box {
    background: var(--white);
    border: 1.5px solid var(--border);
    border-radius: 10px;
    padding: 14px 20px;
    text-align: center;
  }

  .stat-box .num {
    font-family: 'Baloo 2', cursive;
    font-size: 1.6rem;
    font-weight: 800;
    color: var(--saffron);
    line-height: 1;
  }

  .stat-box .lbl {
    font-size: 0.7rem;
    color: var(--text-light);
    font-weight: 500;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    margin-top: 3px;
  }

  .separator {
    height: 1px;
    background: var(--border);
    margin: 14px 0;
  }

  /* Modal */
  .modal-overlay {
    display: none;
    position: fixed; inset: 0;
    background: rgba(13,36,69,0.6);
    z-index: 200;
    align-items: center;
    justify-content: center;
    padding: 20px;
    backdrop-filter: blur(3px);
  }

  .modal-overlay.open { display: flex; }

  .modal {
    background: var(--white);
    border-radius: 18px;
    max-width: 560px;
    width: 100%;
    max-height: 80vh;
    overflow-y: auto;
    position: relative;
    box-shadow: 0 20px 60px rgba(0,0,0,0.25);
  }

  .modal-header {
    padding: 20px 24px;
    border-bottom: 1px solid var(--border);
    position: sticky;
    top: 0;
    background: var(--white);
    z-index: 5;
  }

  .modal-close {
    position: absolute;
    top: 16px; right: 16px;
    background: rgba(13,36,69,0.08);
    border: none;
    border-radius: 50%;
    width: 30px; height: 30px;
    cursor: pointer;
    font-size: 16px;
    display: flex; align-items: center; justify-content: center;
    transition: background 0.15s;
  }

  .modal-close:hover { background: rgba(255,107,0,0.15); }

  .modal-body { padding: 20px 24px 28px; }

  .modal-section { margin-bottom: 18px; }
  .modal-section-title {
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--saffron);
    margin-bottom: 8px;
  }

  .modal-section p, .modal-section li {
    font-size: 0.85rem;
    color: var(--text-mid);
    line-height: 1.6;
  }

  .modal-section ul { list-style: none; display: flex; flex-direction: column; gap: 4px; }
  .modal-section ul li::before { content: '• '; color: var(--saffron); font-weight: 700; }

  @media (max-width: 860px) {
    .main-layout { grid-template-columns: 1fr; }
    .left-panel { max-height: none; position: static; }
    .right-panel { padding: 20px; }
    header { padding: 14px 20px; }
    .schemes-grid { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<div class="tricolor-bar"></div>

<header>
  <div class="emblem">🏛️</div>
  <div class="header-text">
    <h1>Scheme Eligibility Portal</h1>
    <p>Surveyor Assessment Tool &nbsp;·&nbsp; Government of India</p>
  </div>
  <div class="header-badge">Surveyor Use Only</div>
</header>

<div class="main-layout">

  <!-- LEFT: FORM -->
  <div class="left-panel">
    <div class="panel-title">📋 Beneficiary Profile</div>

    <!-- Basic Info -->
    <div class="form-section">
      <div class="form-section-label">Basic Information</div>
      <div class="form-row">
        <div class="field-group">
          <label>Age (Years)</label>
          <input type="number" id="age" min="0" max="120" placeholder="e.g. 35">
        </div>
        <div class="field-group">
          <label>Gender</label>
          <select id="gender">
            <option value="">Select</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
          </select>
        </div>
      </div>
    </div>

    <div class="separator"></div>

    <!-- Income -->
    <div class="form-section">
      <div class="form-section-label">Income & Financial Status</div>
      <div class="field-group">
        <label>Annual Family Income (₹)</label>
        <input type="number" id="income" placeholder="e.g. 120000">
      </div>
      <div style="margin-top:10px;">
        <div class="field-group">
          <label>BPL Card Holder?</label>
          <select id="bpl">
            <option value="">Select</option>
            <option value="yes">Yes</option>
            <option value="no">No</option>
          </select>
        </div>
      </div>
    </div>

    <div class="separator"></div>

    <!-- Occupation -->
    <div class="form-section">
      <div class="form-section-label">Occupation</div>
      <div class="field-group">
        <label>Sector / Occupation Type</label>
        <select id="occupation">
          <option value="">Select occupation</option>
          <option value="farmer">Farmer / Agriculture</option>
          <option value="unorganized">Unorganized Sector Worker</option>
          <option value="construction">Construction Worker</option>
          <option value="street_vendor">Street Vendor</option>
          <option value="artisan">Artisan / Craftsperson</option>
          <option value="fisherman">Fisherman</option>
          <option value="unemployed">Unemployed</option>
          <option value="student">Student</option>
          <option value="small_business">Small Business / MSME</option>
          <option value="salaried">Salaried / Government Employee</option>
          <option value="other">Other</option>
        </select>
      </div>
    </div>

    <div class="separator"></div>

    <!-- Family Situation -->
    <div class="form-section">
      <div class="form-section-label">Family Situation</div>
      <div class="check-grid">
        <label class="check-item" for="has_girl_child">
          <input type="checkbox" id="has_girl_child" onchange="syncCheckStyle(this)"> <span>👧 Has Girl Child (&lt;10 yrs)</span>
        </label>
        <label class="check-item" for="single_parent">
          <input type="checkbox" id="single_parent" onchange="syncCheckStyle(this)"> <span>🤱 Single Parent</span>
        </label>
        <label class="check-item" for="widow">
          <input type="checkbox" id="widow" onchange="syncCheckStyle(this)"> <span>🕊️ Widow / Widower</span>
        </label>
        <label class="check-item" for="disabled">
          <input type="checkbox" id="disabled" onchange="syncCheckStyle(this)"> <span>♿ Differently Abled</span>
        </label>
        <label class="check-item" for="has_bank_account">
          <input type="checkbox" id="has_bank_account" onchange="syncCheckStyle(this)"> <span>🏦 Has Bank Account</span>
        </label>
        <label class="check-item" for="no_house">
          <input type="checkbox" id="no_house" onchange="syncCheckStyle(this)"> <span>🏠 No Pucca House</span>
        </label>
        <label class="check-item" for="rural">
          <input type="checkbox" id="rural" onchange="syncCheckStyle(this)"> <span>🌾 Rural Area</span>
        </label>
        <label class="check-item" for="has_school_children">
          <input type="checkbox" id="has_school_children" onchange="syncCheckStyle(this)"> <span>🎒 School Children (5–10th)</span>
        </label>
      </div>
    </div>

    <div class="separator"></div>

    <!-- State -->
    <div class="form-section">
      <div class="form-section-label">State / Region</div>
      <div class="field-group">
        <label>State</label>
        <select id="state">
          <option value="all">All India (Central Schemes)</option>
          <option value="maharashtra">Maharashtra</option>
          <option value="karnataka">Karnataka</option>
          <option value="tamilnadu">Tamil Nadu</option>
          <option value="telangana">Telangana</option>
        </select>
      </div>
    </div>

    <button class="find-btn" onclick="findSchemes()">🔍 Find Eligible Schemes</button>
    <button class="reset-btn" onclick="resetForm()">↺ Reset Form</button>
  </div>

  <!-- RIGHT: RESULTS -->
  <div class="right-panel" id="right-panel">
    <div class="initial-state" id="initial-state">
      <div class="big-icon">🇮🇳</div>
      <h2>Social Security Scheme Finder</h2>
      <p>Fill in the beneficiary's profile on the left and click <strong>Find Eligible Schemes</strong> to see all applicable government programmes.</p>
      <div class="stat-row">
        <div class="stat-box"><div class="num">25+</div><div class="lbl">Schemes</div></div>
        <div class="stat-box"><div class="num">8</div><div class="lbl">Categories</div></div>
        <div class="stat-box"><div class="num">5</div><div class="lbl">States</div></div>
      </div>
    </div>
    <div id="results-area" style="display:none;"></div>
  </div>
</div>

<!-- MODAL -->
<div class="modal-overlay" id="modal-overlay" onclick="closeModal(event)">
  <div class="modal" id="modal-box">
    <div class="modal-header">
      <div id="modal-title" style="font-family:'Baloo 2',cursive;font-size:1.1rem;font-weight:800;color:var(--navy);padding-right:40px;"></div>
      <button class="modal-close" onclick="closeModalDirect()">✕</button>
    </div>
    <div class="modal-body" id="modal-body"></div>
  </div>
</div>

<script>
// ===================== SCHEME DATABASE =====================
const SCHEMES = [
  {
    id: 1,
    name: "Ayushman Bharat (PM-JAY)",
    shortName: "AB-PMJAY",
    icon: "🏥",
    category: "Health",
    benefit: "Health insurance up to ₹5 lakh/family/year – free treatment at empanelled hospitals",
    objective: "Flagship health insurance for economically disadvantaged families. Covers secondary and tertiary hospitalization including surgery, consultation, pre & post-hospitalization.",
    eligibility: [
      "Economically disadvantaged / BPL families",
      "SECC 2011 listed families",
      "No strict age limit"
    ],
    documents: ["Aadhaar", "Ration Card", "Income Certificate", "Bank Account"],
    premium: "Free – no premium",
    check: (f) => f.bpl === 'yes' || f.income < 200000,
    state: "all"
  },
  {
    id: 2,
    name: "e-Shram Card",
    shortName: "e-Shram",
    icon: "🪪",
    category: "Insurance",
    benefit: "Accidental insurance ₹2 lakh (death/total disability), ₹1 lakh partial disability + access to welfare schemes",
    objective: "Unique identity for unorganized sector workers giving access to all social security schemes under Ministry of Labour.",
    eligibility: [
      "Age 16–59 years",
      "Unorganized sector worker",
      "Not member of EPFO/ESIC"
    ],
    documents: ["Aadhaar (mobile linked)", "Bank Account", "Photograph", "Occupation Details"],
    premium: "Free registration",
    check: (f) => f.age >= 16 && f.age <= 59 && ['unorganized','construction','street_vendor','artisan','fisherman','farmer','other'].includes(f.occupation),
    state: "all"
  },
  {
    id: 3,
    name: "PM Suraksha Bima Yojana",
    shortName: "PMSBY",
    icon: "🛡️",
    category: "Insurance",
    benefit: "Accidental death ₹2 lakh, total disability ₹2 lakh, partial disability ₹1 lakh",
    objective: "Accidental death and disability insurance for the underprivileged at just ₹20/year.",
    eligibility: [
      "Age 18–70 years",
      "Must have savings bank account"
    ],
    documents: ["Aadhaar", "Bank Account", "Nominee Details"],
    premium: "₹20 per annum",
    check: (f) => f.age >= 18 && f.age <= 70 && f.has_bank_account,
    state: "all"
  },
  {
    id: 4,
    name: "PM Jeevan Jyoti Bima Yojana",
    shortName: "PMJJBY",
    icon: "💛",
    category: "Insurance",
    benefit: "Life insurance cover of ₹2 lakh on death due to any cause",
    objective: "Life insurance for unorganized sector and economically weaker sections.",
    eligibility: [
      "Age 18–50 years",
      "Bank account linked with Aadhaar"
    ],
    documents: ["Aadhaar", "Bank Account", "Nominee Details"],
    premium: "₹430 per annum",
    check: (f) => f.age >= 18 && f.age <= 50 && f.has_bank_account,
    state: "all"
  },
  {
    id: 5,
    name: "Atal Pension Yojana",
    shortName: "APY",
    icon: "🏧",
    category: "Pension",
    benefit: "Monthly pension ₹1,000–₹5,000 after age 60. Govt co-contributes 50% for income < ₹15,000/month",
    objective: "Pension for unorganized sector workers with government co-contribution.",
    eligibility: [
      "Age 18–40 years",
      "Indian citizen with savings account",
      "No income ceiling"
    ],
    documents: ["Aadhaar", "Bank Account", "Income Proof (optional)"],
    premium: "₹55–₹250/month depending on entry age",
    check: (f) => f.age >= 18 && f.age <= 40 && f.has_bank_account,
    state: "all"
  },
  {
    id: 6,
    name: "PM Shram Yogi Maan-Dhan",
    shortName: "PM-SYM",
    icon: "👷",
    category: "Pension",
    benefit: "Monthly pension of ₹3,000 after age 60 + government matching contribution",
    objective: "Pension for unorganized sector workers with monthly income ≤ ₹15,000.",
    eligibility: [
      "Age 18–40 years",
      "Monthly income ≤ ₹15,000",
      "Not member of EPFO/NPS"
    ],
    documents: ["Aadhaar", "Bank Account", "Income Certificate", "Age Proof"],
    premium: "₹55–₹250/month",
    check: (f) => f.age >= 18 && f.age <= 40 && f.income <= 180000 && ['unorganized','construction','street_vendor','artisan','fisherman','farmer'].includes(f.occupation),
    state: "all"
  },
  {
    id: 7,
    name: "PM Kisan Samman Nidhi",
    shortName: "PM-KISAN",
    icon: "🌾",
    category: "Agriculture",
    benefit: "₹6,000/year in 3 installments directly to farmer's bank account",
    objective: "Direct income support to small and marginal farmers with land up to 2 hectares.",
    eligibility: [
      "Small/marginal farmer with land ≤ 2 hectares",
      "Must be landowner",
      "Indian citizen"
    ],
    documents: ["Aadhaar", "Bank Account (Aadhaar linked)", "Land Ownership Proof"],
    premium: "Free – no charges",
    check: (f) => f.occupation === 'farmer',
    state: "all"
  },
  {
    id: 8,
    name: "MGNREGA",
    shortName: "MGNREGA",
    icon: "⛏️",
    category: "Finance",
    benefit: "Guaranteed 100–125 days of wage employment/year at ₹200–₹400/day",
    objective: "Livelihood security for rural households through guaranteed public works employment.",
    eligibility: [
      "Any adult (18+) member of a rural household",
      "Household must be registered",
      "Residing in rural area"
    ],
    documents: ["Aadhaar", "Bank Account", "Household Details"],
    premium: "Free – government employment",
    check: (f) => f.age >= 18 && f.rural,
    state: "all"
  },
  {
    id: 9,
    name: "PM Jan Dhan Yojana",
    shortName: "PMJDY",
    icon: "🏦",
    category: "Finance",
    benefit: "Zero-balance savings account + RuPay card with free accidental insurance + overdraft facility",
    objective: "Universal banking access ensuring financial inclusion for all Indian households.",
    eligibility: [
      "Indian citizen aged 18+",
      "No minimum balance required",
      "No bank account required currently"
    ],
    documents: ["Aadhaar or any ID Proof", "Address Proof", "Photographs"],
    premium: "Free – no charges",
    check: (f) => f.age >= 18 && !f.has_bank_account,
    state: "all"
  },
  {
    id: 10,
    name: "NSAP – Old Age Pension",
    shortName: "IGNOAPS",
    icon: "👴",
    category: "Pension",
    benefit: "₹200–₹500/month for elderly citizens aged 60+",
    objective: "Social assistance to elderly, widows, and disabled below the poverty line.",
    eligibility: [
      "Age 60 years or above",
      "Below Poverty Line (BPL)",
      "No other pension income"
    ],
    documents: ["Aadhaar", "Age Proof", "Income Certificate", "BPL Certificate"],
    premium: "Free – government benefit",
    check: (f) => f.age >= 60 && f.bpl === 'yes',
    state: "all"
  },
  {
    id: 11,
    name: "Sukanya Samriddhi Yojana",
    shortName: "SSY",
    icon: "👧",
    category: "Finance",
    benefit: "High interest savings for girl child + tax benefit under 80C. Full withdrawal after 21 years.",
    objective: "Secure the future of a girl child under Beti Bachao Beti Padhao initiative.",
    eligibility: [
      "Girl child under 10 years old",
      "Account opened by parent/guardian",
      "Indian citizen guardian"
    ],
    documents: ["Girl's Birth Certificate", "Guardian's Aadhaar", "Bank Account"],
    premium: "Min ₹250/year, max ₹1.5 lakh/year",
    check: (f) => f.has_girl_child,
    state: "all"
  },
  {
    id: 12,
    name: "PM Awas Yojana",
    shortName: "PMAY",
    icon: "🏠",
    category: "Housing",
    benefit: "Financial assistance for home + interest subsidy up to ₹2.67 lakh on home loan",
    objective: "Housing for EWS, LIG, and MIG families with priority to women and differently-abled.",
    eligibility: [
      "EWS / LIG / MIG families",
      "Must not own a pucca house anywhere in India",
      "Priority to women beneficiaries"
    ],
    documents: ["Aadhaar", "Identity Proof", "Address Proof", "Income Proof", "Bank Account"],
    premium: "No upfront fee – subsidy applied to loan",
    check: (f) => f.no_house && (f.bpl === 'yes' || f.income < 600000),
    state: "all"
  },
  {
    id: 13,
    name: "PM Ujjwala Yojana",
    shortName: "PMUY",
    icon: "🔥",
    category: "Finance",
    benefit: "Free LPG connection + subsidized LPG cylinders for BPL women households",
    objective: "Clean cooking fuel for BPL women, reducing indoor air pollution.",
    eligibility: [
      "BPL card holder",
      "Women head of household",
      "Priority: SC/ST, OBC, EWS"
    ],
    documents: ["Aadhaar", "Bank Account", "BPL Certificate"],
    premium: "Free connection (refundable security deposit may apply)",
    check: (f) => f.bpl === 'yes' && f.gender === 'female',
    state: "all"
  },
  {
    id: 14,
    name: "PM Vishwakarma Yojana",
    shortName: "Vishwakarma",
    icon: "🔨",
    category: "Skill",
    benefit: "Free skill training + ₹500/day stipend + ₹15,000 toolkit + collateral-free loan up to ₹3 lakh @ 5%",
    objective: "Support traditional artisans and craftspeople (carpenters, potters, goldsmiths, cobblers, tailors etc.)",
    eligibility: [
      "Age 18+ in traditional trades",
      "One member per family only",
      "Actively practicing the craft",
      "Not an income tax payer"
    ],
    documents: ["Aadhaar (mobile linked)", "Bank Account", "Proof of Occupation"],
    premium: "Free – government funded",
    check: (f) => f.age >= 18 && f.occupation === 'artisan',
    state: "all"
  },
  {
    id: 15,
    name: "PM Svanidhi Scheme",
    shortName: "SVANidhi",
    icon: "🛒",
    category: "Finance",
    benefit: "Collateral-free loans ₹10k→₹20k→₹50k + 7% interest subsidy + ₹1,200/yr cashback on digital payments",
    objective: "Working capital loans for urban street vendors for business restart and growth.",
    eligibility: [
      "Street vendor in urban/peri-urban area",
      "Must have Certificate of Vending or ULB recommendation",
      "Age 18+"
    ],
    documents: ["Certificate of Vending / Vendor ID", "Aadhaar", "KYC Document", "Bank Account"],
    premium: "Free – loans at subsidized rates",
    check: (f) => f.age >= 18 && f.occupation === 'street_vendor',
    state: "all"
  },
  {
    id: 16,
    name: "Skill India – PMKVY",
    shortName: "PMKVY",
    icon: "📚",
    category: "Skill",
    benefit: "Free skill development training + certification + financial incentives on completion",
    objective: "Enhance employability of youth through certified sector-specific skill training.",
    eligibility: [
      "Indian citizen aged 14–35 years",
      "Seeking skill training for employment"
    ],
    documents: ["Aadhaar", "Educational Proof", "Bank Account", "Photograph"],
    premium: "Free training and certification",
    check: (f) => f.age >= 14 && f.age <= 35,
    state: "all"
  },
  {
    id: 17,
    name: "MUDRA Yojana",
    shortName: "PMMY",
    icon: "💼",
    category: "Finance",
    benefit: "Collateral-free business loans: Shishu ₹50k / Kishore ₹5L / Tarun ₹10L",
    objective: "Financial support to micro & small entrepreneurs for income-generating activities.",
    eligibility: [
      "Micro / small business owner",
      "Manufacturing, trading or service sector",
      "Non-corporate small businesses"
    ],
    documents: ["Aadhaar", "PAN", "Business Address Proof", "Bank Account", "Business Plan"],
    premium: "No collateral required",
    check: (f) => ['small_business','artisan','street_vendor','unorganized'].includes(f.occupation),
    state: "all"
  },
  {
    id: 18,
    name: "Rashtriya Swasthya Bima Yojana",
    shortName: "RSBY",
    icon: "🩺",
    category: "Health",
    benefit: "Health insurance up to ₹30,000/family/year – cashless hospitalization",
    objective: "Health coverage for BPL families including maternity and surgical procedures.",
    eligibility: [
      "Below Poverty Line (BPL) families",
      "Includes differently-abled and migrant workers"
    ],
    documents: ["BPL Card", "Aadhaar", "Family Details"],
    premium: "Subsidized – government funded",
    check: (f) => f.bpl === 'yes',
    state: "all"
  },
  {
    id: 19,
    name: "Child Care Scheme",
    shortName: "Child Care",
    icon: "👶",
    category: "Finance",
    benefit: "₹2,250/month for education of children from single-parent families",
    objective: "Financial assistance for children's education from single-parent households.",
    eligibility: [
      "Children below 18 years",
      "From single-parent families"
    ],
    documents: ["Aadhaar (Child & Parent)", "Income Certificate", "Death Certificate (if applicable)", "Bank Passbook"],
    premium: "Free benefit",
    check: (f) => f.single_parent,
    state: "all"
  },
  {
    id: 20,
    name: "Pre-Matric Scholarship",
    shortName: "Pre-Matric",
    icon: "🎓",
    category: "Finance",
    benefit: "₹3,500/year directly credited to student's bank account",
    objective: "Support students from economically weaker communities for school education (5th–10th standard).",
    eligibility: [
      "Students in 5th to 10th standard",
      "Eligible income and community category",
      "As per government norms"
    ],
    documents: ["Aadhaar", "Income Certificate", "Community Certificate", "Bank Account"],
    premium: "Free scholarship",
    check: (f) => f.has_school_children,
    state: "all"
  },
  {
    id: 21,
    name: "Senior Citizen Card",
    shortName: "Senior Card",
    icon: "🪪",
    category: "Finance",
    benefit: "Rail/bus concessions + higher interest rates + priority in banks & hospitals + pension access",
    objective: "Identity recognition and welfare access for senior citizens 60 years and above.",
    eligibility: [
      "Age 60 years or above"
    ],
    documents: ["Aadhaar", "Age Proof", "Address Proof", "2 Photographs"],
    premium: "Free",
    check: (f) => f.age >= 60,
    state: "all"
  },
  {
    id: 22,
    name: "Udyam Registration (MSME)",
    shortName: "Udyam",
    icon: "🏭",
    category: "Finance",
    benefit: "Access to priority credit, subsidies, government tenders, MSME Act protection against delayed payments",
    objective: "Formal recognition of MSMEs for government benefits and financial support.",
    eligibility: [
      "Micro, Small or Medium Enterprise",
      "Any sector – manufacturing, services, trading"
    ],
    documents: ["Aadhaar of Proprietor", "PAN", "Business Address", "Bank Account", "GSTIN (if applicable)"],
    premium: "Free online registration",
    check: (f) => f.occupation === 'small_business',
    state: "all"
  },
  // Maharashtra Schemes
  {
    id: 23,
    name: "Ladki Bahin Scheme",
    shortName: "Ladki Bahin",
    icon: "👩",
    category: "Women",
    benefit: "₹1,500/month financial assistance to economically weaker women",
    objective: "Financial assistance and social security to women with family income under ₹2.5 lakh.",
    eligibility: [
      "Women with annual family income < ₹2.5 lakh",
      "Resident of Maharashtra"
    ],
    documents: ["Aadhaar", "Income Proof", "Bank Passbook", "Photograph"],
    premium: "Free – government benefit",
    check: (f) => f.gender === 'female' && f.income < 250000,
    state: "maharashtra"
  },
  {
    id: 24,
    name: "Single & Destitute Women Scheme",
    shortName: "Destitute Women",
    icon: "🤝",
    category: "Women",
    benefit: "₹1,500/month to single, destitute, widow, and disabled women",
    objective: "Monthly financial support for single/destitute/widow/disabled women for livelihood and social security.",
    eligibility: [
      "Single / Destitute / Widow / Disabled women",
      "Maharashtra resident"
    ],
    documents: ["Aadhaar", "Income Certificate", "Death Certificate (if widow)", "Bank Passbook"],
    premium: "Free – government benefit",
    check: (f) => f.gender === 'female' && (f.widow || f.disabled || f.single_parent),
    state: "maharashtra"
  },
  {
    id: 25,
    name: "Elderly Niradhar Yojana",
    shortName: "Niradhar",
    icon: "🧓",
    category: "Pension",
    benefit: "₹1,500/month for destitute senior citizens aged 65+",
    objective: "Monthly financial assistance for destitute elderly persons.",
    eligibility: [
      "Destitute person aged 65 years and above",
      "Maharashtra resident"
    ],
    documents: ["Aadhaar", "Income Proof", "Bank Passbook", "Proof of Destitution", "Ration Card"],
    premium: "Free",
    check: (f) => f.age >= 65 && f.bpl === 'yes',
    state: "maharashtra"
  },
  {
    id: 26,
    name: "Free Sewing Machine Scheme",
    shortName: "Sewing Machine",
    icon: "🧵",
    category: "Women",
    benefit: "Free sewing machine for self-employment",
    objective: "Encourage women entrepreneurs who have completed sewing training to start self-employment.",
    eligibility: [
      "Women who completed sewing training",
      "Age 18–45 years",
      "Preference to SHG members"
    ],
    documents: ["Aadhaar", "Income Proof", "Bank Passbook", "SHG Membership Proof"],
    premium: "Free",
    check: (f) => f.gender === 'female' && f.age >= 18 && f.age <= 45,
    state: "maharashtra"
  },
  // Karnataka
  {
    id: 27,
    name: "Yuva Nidhi Scheme",
    shortName: "Yuva Nidhi",
    icon: "🎓",
    category: "Finance",
    benefit: "₹3,000/month (graduates) or ₹1,500/month (diploma) for up to 2 years till employment",
    objective: "Unemployment financial assistance for educated youth of Karnataka.",
    eligibility: [
      "Karnataka resident",
      "Graduated or Diploma (2022-23 or later)",
      "Currently unemployed",
      "Not self-employed"
    ],
    documents: ["Aadhaar", "Degree/Diploma Certificate", "Residence Certificate", "Bank Account"],
    premium: "Free – DBT benefit",
    check: (f) => f.occupation === 'unemployed' && f.age >= 18 && f.age <= 35,
    state: "karnataka"
  },
  // Tamil Nadu
  {
    id: 28,
    name: "Magalir Urimai Thogai",
    shortName: "Magalir Urimai",
    icon: "💐",
    category: "Women",
    benefit: "₹1,000/month financial assistance for eligible women",
    objective: "Monthly financial assistance to eligible women for economic empowerment in Tamil Nadu.",
    eligibility: [
      "Women aged 21+ and permanent TN resident",
      "Annual household income < ₹2.5 lakh",
      "Land ≤ 5 acres wet/10 acres dry",
      "Electricity < 3,600 units/year",
      "One woman per family only"
    ],
    documents: ["Aadhaar", "Ration Card", "Income Certificate", "Bank Account", "Electricity Bill"],
    premium: "Free",
    check: (f) => f.gender === 'female' && f.age >= 21 && f.income < 250000,
    state: "tamilnadu"
  },
  {
    id: 29,
    name: "Nalavariyam Card",
    shortName: "Nalavariyam",
    icon: "🏗️",
    category: "Insurance",
    benefit: "Educational/marriage/maternity/death/accident assistance + pension + medical support",
    objective: "Social security for unorganized sector workers in Tamil Nadu through welfare board registration.",
    eligibility: [
      "Unorganized sector worker in Tamil Nadu",
      "Age 18–60 years",
      "Engaged in eligible occupations"
    ],
    documents: ["Aadhaar", "Ration Card", "Bank Passbook", "Proof of Occupation"],
    premium: "Nominal registration fee",
    check: (f) => f.age >= 18 && f.age <= 60 && ['unorganized','construction','artisan','fisherman','farmer'].includes(f.occupation),
    state: "tamilnadu"
  },
  {
    id: 30,
    name: "TN Fishermen Welfare Board",
    shortName: "TNFWB",
    icon: "🐟",
    category: "Insurance",
    benefit: "Accident death ₹5 lakh + savings-cum-relief + educational/marriage/maternity/pension benefits",
    objective: "Comprehensive social security and welfare for registered fishermen in Tamil Nadu.",
    eligibility: [
      "Registered fisherman in Tamil Nadu",
      "Age 18–60 years",
      "Registered with Fisheries Dept"
    ],
    documents: ["Aadhaar", "Ration Card", "Fisherman ID Card", "Bank Passbook", "Boat Registration (if applicable)"],
    premium: "Nominal registration",
    check: (f) => f.occupation === 'fisherman',
    state: "tamilnadu"
  },
  // Telangana
  {
    id: 31,
    name: "Telangana Labour Card",
    shortName: "TS Labour Card",
    icon: "🪖",
    category: "Insurance",
    benefit: "Maternity ₹30,000 (2 girl children) + Accident death ₹6 lakh + Medical ₹1.5 lakh",
    objective: "Social security for registered construction and unorganized workers in Telangana.",
    eligibility: [
      "Age 18–60 years",
      "Worked ≥ 90 days in construction/related activities in previous year"
    ],
    documents: ["Ration Card", "Photographs", "Bank Passbook", "Aadhaar", "Voter ID"],
    premium: "Nominal registration",
    check: (f) => f.age >= 18 && f.age <= 60 && ['construction','unorganized'].includes(f.occupation),
    state: "telangana"
  }
];

// ===================== STATE & LOGIC =====================
let currentFilter = 'all';

function syncCheckStyle(cb) {
  cb.closest('.check-item').classList.toggle('active', cb.checked);
}

function getFormData() {
  return {
    age: parseInt(document.getElementById('age').value) || 0,
    gender: document.getElementById('gender').value,
    income: parseInt(document.getElementById('income').value) || 999999,
    bpl: document.getElementById('bpl').value,
    occupation: document.getElementById('occupation').value,
    state: document.getElementById('state').value,
    has_girl_child: document.getElementById('has_girl_child').checked,
    single_parent: document.getElementById('single_parent').checked,
    widow: document.getElementById('widow').checked,
    disabled: document.getElementById('disabled').checked,
    has_bank_account: document.getElementById('has_bank_account').checked,
    no_house: document.getElementById('no_house').checked,
    rural: document.getElementById('rural').checked,
    has_school_children: document.getElementById('has_school_children').checked
  };
}

function findSchemes() {
  const f = getFormData();
  const selectedState = f.state;

  const eligible = SCHEMES.filter(s => {
    const stateMatch = s.state === 'all' || s.state === selectedState;
    return stateMatch && s.check(f);
  });

  document.getElementById('initial-state').style.display = 'none';
  document.getElementById('results-area').style.display = 'block';

  renderResults(eligible, f);
}

function renderResults(schemes, f) {
  const area = document.getElementById('results-area');
  currentFilter = 'all';

  const cats = [...new Set(schemes.map(s => s.category))];

  const catColors = {
    Insurance: '#1565C0', Pension: '#7B4EA6', Health: '#00796B',
    Finance: '#E65100', Women: '#AD1457', Agriculture: '#2E7D32',
    Skill: '#6A1B9A', Housing: '#4E342E'
  };

  let filterHTML = `<span class="filter-tag all" onclick="filterCards('all', this)">All (${schemes.length})</span>`;
  cats.forEach(c => {
    const cnt = schemes.filter(s => s.category === c).length;
    filterHTML += `<span class="filter-tag" data-cat="${c}" onclick="filterCards('${c}', this)">${c} (${cnt})</span>`;
  });

  let cardsHTML = '';
  if (schemes.length === 0) {
    cardsHTML = `<div class="empty-state">
      <div class="big-icon">🔎</div>
      <h3>No matching schemes found</h3>
      <p>Try adjusting the beneficiary profile — check age, income, or occupation fields.</p>
    </div>`;
  } else {
    schemes.forEach(s => {
      const eligPoints = s.eligibility.map(e => `<li>${e}</li>`).join('');
      const docs = s.documents.slice(0,3).map(d => `<span class="doc-chip">${d}</span>`).join('') + (s.documents.length > 3 ? `<span class="doc-chip">+${s.documents.length-3} more</span>` : '');
      cardsHTML += `
        <div class="scheme-card" data-cat="${s.category}" data-id="${s.id}">
          <div class="card-stripe"></div>
          <div class="card-cat-badge">${s.category}</div>
          <div class="card-body">
            <div class="card-header">
              <div class="card-icon">${s.icon}</div>
              <div>
                <div class="card-title">${s.name}</div>
                <div class="card-subtitle">${s.shortName}</div>
              </div>
            </div>
            <div class="card-benefit">
              <div class="card-benefit-label">Key Benefit</div>
              <div class="card-benefit-value">${s.benefit.length > 100 ? s.benefit.substring(0,100)+'…' : s.benefit}</div>
            </div>
            <ul class="eligibility-list">${eligPoints}</ul>
            <div class="doc-chips">${docs}</div>
          </div>
          <div class="card-footer">
            <span class="premium-info">${s.premium}</span>
            <button class="more-btn" onclick="showModal(${s.id})">View Details →</button>
          </div>
        </div>`;
    });
  }

  area.innerHTML = `
    <div class="results-header">
      <div class="results-count">Found <span>${schemes.length}</span> eligible scheme${schemes.length !== 1 ? 's' : ''}</div>
      <div class="filter-tags">${filterHTML}</div>
    </div>
    <div class="schemes-grid" id="schemes-grid">${cardsHTML}</div>`;

  window._currentSchemes = schemes;
}

function filterCards(cat, el) {
  currentFilter = cat;
  document.querySelectorAll('.filter-tag').forEach(t => t.style.fontWeight = '');
  el.style.fontWeight = '700';

  const cards = document.querySelectorAll('.scheme-card');
  cards.forEach(card => {
    if (cat === 'all' || card.dataset.cat === cat) {
      card.style.display = 'flex';
    } else {
      card.style.display = 'none';
    }
  });
}

function showModal(id) {
  const s = SCHEMES.find(x => x.id === id);
  if (!s) return;

  document.getElementById('modal-title').innerHTML = `${s.icon} ${s.name}`;

  const eligHTML = s.eligibility.map(e => `<li>${e}</li>`).join('');
  const docHTML = s.documents.map(d => `<li>${d}</li>`).join('');

  document.getElementById('modal-body').innerHTML = `
    <div class="modal-section">
      <div class="modal-section-title">Objective</div>
      <p>${s.objective}</p>
    </div>
    <div class="modal-section">
      <div class="modal-section-title">Key Benefits</div>
      <p>${s.benefit}</p>
    </div>
    <div class="modal-section">
      <div class="modal-section-title">Eligibility Criteria</div>
      <ul>${eligHTML}</ul>
    </div>
    <div class="modal-section">
      <div class="modal-section-title">Documents Required</div>
      <ul>${docHTML}</ul>
    </div>
    <div class="modal-section">
      <div class="modal-section-title">Premium / Amount</div>
      <p>${s.premium}</p>
    </div>
    <div class="modal-section">
      <div class="modal-section-title">Category</div>
      <p>${s.category} Scheme${s.state !== 'all' ? ` – ${s.state.charAt(0).toUpperCase()+s.state.slice(1)} State` : ' – Central Government'}</p>
    </div>`;

  document.getElementById('modal-overlay').classList.add('open');
}

function closeModal(e) {
  if (e.target === document.getElementById('modal-overlay')) {
    document.getElementById('modal-overlay').classList.remove('open');
  }
}

function closeModalDirect() {
  document.getElementById('modal-overlay').classList.remove('open');
}

function resetForm() {
  document.getElementById('age').value = '';
  document.getElementById('gender').value = '';
  document.getElementById('income').value = '';
  document.getElementById('bpl').value = '';
  document.getElementById('occupation').value = '';
  document.getElementById('state').value = 'all';

  document.querySelectorAll('.check-item input[type="checkbox"]').forEach(cb => {
    cb.checked = false;
    cb.closest('.check-item').classList.remove('active');
  });

  document.getElementById('initial-state').style.display = 'flex';
  document.getElementById('results-area').style.display = 'none';
}

document.addEventListener('keydown', (e) => {
  if (e.key === 'Escape') closeModalDirect();
});
</script>
</body>
</html>
