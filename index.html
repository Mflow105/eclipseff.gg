<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FF HACK MENU DEMO</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; user-select: none; }
        body {
            background: #0a0a0f;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-image: radial-gradient(ellipse at 30% 40%, #1a1a3e 0%, #0a0a0f 70%);
        }
        
        .menu {
            background: rgba(20, 22, 40, 0.55);
            backdrop-filter: blur(40px) saturate(1.8);
            -webkit-backdrop-filter: blur(40px) saturate(1.8);
            width: 420px;
            padding: 20px 24px 28px;
            border-radius: 32px;
            border: 1px solid rgba(255, 255, 255, 0.08);
            box-shadow: 0 30px 80px rgba(0, 0, 0, 0.8), 0 0 60px rgba(0, 200, 255, 0.03), inset 0 1px 0 rgba(255, 255, 255, 0.05);
            position: relative;
            overflow: hidden;
        }
        
        .menu::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(ellipse at 30% 20%, rgba(255, 255, 255, 0.03) 0%, transparent 60%);
            pointer-events: none;
            z-index: 0;
        }
        
        .menu > * {
            position: relative;
            z-index: 1;
        }
        
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(255, 255, 255, 0.06);
            padding-bottom: 14px;
            margin-bottom: 18px;
        }
        
        .header h1 {
            font-size: 22px;
            font-weight: 700;
            letter-spacing: 0.5px;
            text-shadow: 0 0 30px rgba(0, 229, 255, 0.15);
            background: linear-gradient(135deg, #ffffff 30%, #80d4ff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .header .status {
            background: rgba(255, 255, 255, 0.06);
            border: 1px solid rgba(255, 255, 255, 0.08);
            color: rgba(255, 255, 255, 0.4);
            padding: 4px 14px;
            border-radius: 30px;
            font-size: 11px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            backdrop-filter: blur(10px);
            transition: 0.4s ease;
        }
        
        .header .status.offline {
            color: #ff6b6b;
            border-color: rgba(255, 107, 107, 0.3);
            background: rgba(255, 107, 107, 0.08);
        }
        
        .header .status.online {
            color: #6bcb77;
            border-color: rgba(107, 203, 119, 0.3);
            background: rgba(107, 203, 119, 0.08);
        }
        
        /* === KEY SYSTEM - CHỈ HIỆN KHI CHƯA NHẬP KEY === */
        .keysystem {
            background: rgba(255, 255, 255, 0.04);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border-radius: 14px;
            padding: 12px 16px;
            margin-bottom: 16px;
            border: 1px solid rgba(255, 255, 255, 0.04);
            display: flex;
            align-items: center;
            gap: 10px;
            transition: 0.4s ease;
        }
        
        .keysystem.hidden {
            display: none;
        }
        
        .keysystem .key-label {
            color: rgba(255, 255, 255, 0.3);
            font-size: 11px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            white-space: nowrap;
        }
        
        .keysystem input {
            flex: 1;
            background: rgba(255, 255, 255, 0.04);
            border: 1px solid rgba(255, 255, 255, 0.06);
            color: rgba(255, 255, 255, 0.8);
            padding: 8px 14px;
            border-radius: 10px;
            font-size: 14px;
            outline: none;
            transition: 0.2s;
            font-family: 'Courier New', monospace;
            letter-spacing: 1px;
        }
        
        .keysystem input:focus {
            border-color: rgba(0, 229, 255, 0.2);
        }
        
        .keysystem input::placeholder {
            color: rgba(255, 255, 255, 0.15);
            letter-spacing: 0px;
            font-family: -apple-system, 'Segoe UI', Arial, sans-serif;
        }
        
        .keysystem .enter-btn {
            background: rgba(0, 229, 255, 0.15);
            color: #80d4ff;
            border: 1px solid rgba(0, 229, 255, 0.1);
            padding: 8px 18px;
            border-radius: 10px;
            font-weight: 600;
            font-size: 13px;
            cursor: pointer;
            transition: 0.2s;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            white-space: nowrap;
        }
        
        .keysystem .enter-btn:hover {
            background: rgba(0, 229, 255, 0.25);
            border-color: rgba(0, 229, 255, 0.2);
        }
        
        .keysystem .key-status {
            font-size: 16px;
            width: 24px;
            text-align: center;
        }
        
        .keysystem .key-status.valid {
            color: #6bcb77;
        }
        
        .keysystem .key-status.invalid {
            color: #ff6b6b;
        }
        
        .keysystem .key-status.waiting {
            color: rgba(255, 255, 255, 0.15);
        }
        
        /* === INJECT STATUS === */
        .inject-status {
            background: rgba(255, 255, 255, 0.04);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border-radius: 14px;
            padding: 10px 16px;
            margin-bottom: 16px;
            border: 1px solid rgba(255, 255, 255, 0.04);
            min-height: 44px;
            display: flex;
            align-items: center;
            transition: 0.3s ease;
        }
        
        .inject-status .step {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 14px;
            font-weight: 500;
            opacity: 0;
            transition: 0.5s ease;
            width: 100%;
        }
        
        .inject-status .step.active {
            opacity: 1;
        }
        
        .inject-status .step .spinner {
            display: inline-block;
            width: 16px;
            height: 16px;
            border: 2px solid rgba(255, 255, 255, 0.1);
            border-top-color: #80d4ff;
            border-radius: 50%;
            animation: spin 0.8s linear infinite;
            flex-shrink: 0;
        }
        
        .inject-status .step .icon {
            font-size: 16px;
            flex-shrink: 0;
        }
        
        .inject-status .step .text.yellow {
            color: #ffd93d;
        }
        
        .inject-status .step .text.green {
            color: #6bcb77;
        }
        
        .inject-status .step .text.white {
            color: rgba(255, 255, 255, 0.6);
        }
        
        .inject-status .step .pid {
            color: #6bcb77;
            font-weight: 600;
            font-family: 'Courier New', monospace;
        }
        
        @keyframes spin {
            to { transform: rotate(360deg); }
        }
        
        /* === MAIN MENU - ẨN KHI CHƯA CÓ KEY === */
        .menu-content {
            display: none;
        }
        
        .menu-content.unlocked {
            display: block;
        }
        
        /* === MAIN MENU ITEMS === */
        .section {
            margin-bottom: 16px;
        }
        
        .section-title {
            color: rgba(255, 255, 255, 0.35);
            font-size: 11px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            margin-bottom: 10px;
            font-weight: 600;
        }
        
        .toggle-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(255, 255, 255, 0.04);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            padding: 10px 14px;
            border-radius: 14px;
            margin-bottom: 6px;
            border: 1px solid rgba(255, 255, 255, 0.04);
            transition: 0.25s ease;
        }
        
        .toggle-row:hover {
            border-color: rgba(255, 255, 255, 0.08);
            background: rgba(255, 255, 255, 0.06);
        }
        
        .toggle-row .label {
            color: rgba(255, 255, 255, 0.85);
            font-size: 14px;
            font-weight: 500;
        }
        
        .toggle-row .label .key {
            color: rgba(255, 255, 255, 0.2);
            font-size: 11px;
            margin-left: 10px;
            font-weight: 400;
        }
        
        .toggle {
            width: 44px;
            height: 26px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 30px;
            cursor: pointer;
            position: relative;
            transition: 0.35s ease;
            flex-shrink: 0;
            border: 1px solid rgba(255, 255, 255, 0.04);
        }
        
        .toggle.active {
            background: rgba(0, 229, 255, 0.4);
            border-color: rgba(0, 229, 255, 0.2);
            box-shadow: 0 0 30px rgba(0, 229, 255, 0.1);
        }
        
        .toggle .knob {
            width: 20px;
            height: 20px;
            background: #fff;
            border-radius: 50%;
            position: absolute;
            top: 2px;
            left: 2px;
            transition: 0.35s cubic-bezier(0.34, 1.56, 0.64, 1);
            box-shadow: 0 2px 12px rgba(0, 0, 0, 0.3);
        }
        
        .toggle.active .knob {
            left: 20px;
            background: #fff;
            box-shadow: 0 2px 20px rgba(0, 229, 255, 0.3);
        }
        
        .slider-row {
            background: rgba(255, 255, 255, 0.04);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            padding: 10px 14px;
            border-radius: 14px;
            border: 1px solid rgba(255, 255, 255, 0.04);
            margin-bottom: 6px;
        }
        
        .slider-row .label {
            color: rgba(255, 255, 255, 0.85);
            font-size: 14px;
            font-weight: 500;
            display: flex;
            justify-content: space-between;
        }
        
        .slider-row .label .value {
            color: rgba(0, 229, 255, 0.8);
            font-weight: 600;
        }
        
        input[type="range"] {
            width: 100%;
            margin-top: 8px;
            -webkit-appearance: none;
            background: rgba(255, 255, 255, 0.06);
            height: 4px;
            border-radius: 10px;
            outline: none;
        }
        
        input[type="range"]::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 18px;
            height: 18px;
            background: #fff;
            border-radius: 50%;
            cursor: pointer;
            box-shadow: 0 2px 16px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .dropdown-row {
            background: rgba(255, 255, 255, 0.04);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            padding: 10px 14px;
            border-radius: 14px;
            border: 1px solid rgba(255, 255, 255, 0.04);
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 6px;
        }
        
        .dropdown-row .label {
            color: rgba(255, 255, 255, 0.85);
            font-size: 14px;
            font-weight: 500;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .dropdown-row .label .warning {
            color: #ff6b6b;
            font-size: 16px;
            font-weight: 700;
            display: none;
            animation: blink 0.8s infinite;
        }
        
        .dropdown-row .label .warning.show {
            display: inline;
        }
        
        .dropdown-row .label .warning-text {
            color: #ff6b6b;
            font-size: 11px;
            font-weight: 600;
            display: none;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        
        .dropdown-row .label .warning-text.show {
            display: inline;
        }
        
        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.2; }
        }
        
        .dropdown-row select {
            background: rgba(255, 255, 255, 0.06);
            color: rgba(255, 255, 255, 0.85);
            border: 1px solid rgba(255, 255, 255, 0.06);
            padding: 6px 14px;
            border-radius: 10px;
            font-size: 13px;
            outline: none;
            cursor: pointer;
            min-width: 110px;
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
        }
        
        .dropdown-row select:focus {
            border-color: rgba(0, 229, 255, 0.2);
        }
        
        .dropdown-row select option[value="head"] { color: #ff6b6b; background: #1a0a0a; }
        .dropdown-row select option[value="neck"] { color: #ffa94d; background: #1a120a; }
        .dropdown-row select option[value="chest"] { color: #6bcb77; background: #0a1a0a; }
        .dropdown-row select option[value="safe"] { color: #74c0fc; background: #0a0a1a; }
        
        .footer {
            margin-top: 18px;
            border-top: 1px solid rgba(255, 255, 255, 0.04);
            padding-top: 14px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .footer .info {
            color: rgba(255, 255, 255, 0.2);
            font-size: 11px;
        }
        
        .footer .info span {
            color: rgba(255, 255, 255, 0.35);
        }
        
        .badge {
            display: inline-block;
            background: rgba(0, 229, 255, 0.08);
            color: rgba(0, 229, 255, 0.6);
            font-size: 10px;
            padding: 2px 12px;
            border-radius: 30px;
            border: 1px solid rgba(0, 229, 255, 0.06);
            backdrop-filter: blur(10px);
        }
        
        .toast {
            position: fixed;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(0, 229, 255, 0.08);
            backdrop-filter: blur(30px) saturate(1.8);
            -webkit-backdrop-filter: blur(30px) saturate(1.8);
            border: 1px solid rgba(0, 229, 255, 0.1);
            color: rgba(255, 255, 255, 0.9);
            padding: 12px 32px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 500;
            opacity: 0;
            transition: 0.4s ease;
            pointer-events: none;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
        }
        
        .toast.show { opacity: 1; }
    </style>
</head>
<body>

<div class="menu">
    <div class="header">
        <h1>⬡ ECLIPSE</h1>
        <span class="status offline" id="statusBadge">● OFFLINE</span>
    </div>
    
    <!-- KEY SYSTEM - CHỈ HIỆN KHI CHƯA NHẬP KEY -->
    <div class="keysystem" id="keySystem">
        <span class="key-label">🔑 KEY</span>
        <input type="text" id="keyInput" placeholder="Nhập key..." onkeydown="if(event.key==='Enter') checkKey()">
        <button class="enter-btn" id="enterBtn" onclick="checkKey()">ENTER</button>
        <span class="key-status waiting" id="keyStatus">⏳</span>
    </div>
    
    <!-- MAIN MENU - ẨN KHI CHƯA CÓ KEY -->
    <div class="menu-content" id="menuContent">
        <!-- INJECT STATUS -->
        <div class="inject-status" id="injectStatus">
            <div class="step active" id="stepDisplay">
                <span class="icon">⏳</span>
                <span class="text white">Đang khởi động <span class="spinner"></span></span>
            </div>
        </div>
        
        <!-- MAIN HACK MENU -->
        <div class="section">
            <div class="section-title">▸ Aimbot</div>
            <div class="toggle-row">
                <span class="label">Aimbot <span class="key">[F1]</span></span>
                <div class="toggle" onclick="toggleElement(this, 'Aimbot')">
                    <div class="knob"></div>
                </div>
            </div>
            <div class="slider-row">
                <div class="label">
                    <span>FOV</span>
                    <span class="value" id="fovValue">120</span>
                </div>
                <input type="range" min="30" max="360" value="120" oninput="updateSlider(this, 'fovValue')">
            </div>
            <div class="slider-row">
                <div class="label">
                    <span>Smooth</span>
                    <span class="value" id="smoothValue">0.50</span>
                </div>
                <input type="range" min="0" max="100" value="50" oninput="updateSliderFloat(this, 'smoothValue')">
            </div>
            <div class="dropdown-row">
                <span class="label">
                    Target
                    <span class="warning" id="warningIcon">⚠️</span>
                    <span class="warning-text" id="warningText">HIGH RISK</span>
                </span>
                <select id="targetSelect" onchange="updateTargetWarning(this)">
                    <option value="head" style="color:#ff6b6b;">⬡ Head</option>
                    <option value="neck" style="color:#ffa94d;">◈ Neck</option>
                    <option value="chest" selected style="color:#6bcb77;">▣ Chest</option>
                    <option value="safe" style="color:#74c0fc;">⊡ Safe Mode</option>
                </select>
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">▸ ESP</div>
            <div class="toggle-row">
                <span class="label">ESP <span class="key">[F2]</span></span>
                <div class="toggle active" onclick="toggleElement(this, 'ESP')">
                    <div class="knob"></div>
                </div>
            </div>
            <div class="toggle-row">
                <span class="label">Box ESP</span>
                <div class="toggle active" onclick="toggleElement(this, 'BoxESP')">
                    <div class="knob"></div>
                </div>
            </div>
            <div class="toggle-row">
                <span class="label">Skeleton</span>
                <div class="toggle" onclick="toggleElement(this, 'Skeleton')">
                    <div class="knob"></div>
                </div>
            </div>
            <div class="toggle-row">
                <span class="label">Distance</span>
                <div class="toggle active" onclick="toggleElement(this, 'Distance')">
                    <div class="knob"></div>
                </div>
            </div>
        </div>
        
        <div class="footer">
            <span class="info">⚡ <span id="fps">60</span> FPS</span>
            <span class="badge">DEMO v1.0</span>
            <span class="info">👤 <span id="players">0</span></span>
        </div>
    </div>
</div>

<div class="toast" id="toast">Đã kích hoạt!</div>

<script>
    const CORRECT_KEY = 'ECLIPSEONTOP';
    let isUnlocked = false;
    let injectRunning = false;
    let injectStep = 0;
    
    // === KEY SYSTEM ===
    function checkKey() {
        const input = document.getElementById('keyInput');
        const status = document.getElementById('keyStatus');
        const btn = document.getElementById('enterBtn');
        const key = input.value.trim();
        
        if (key === CORRECT_KEY) {
            isUnlocked = true;
            status.className = 'key-status valid';
            status.textContent = '✓';
            btn.disabled = true;
            input.disabled = true;
            input.style.borderColor = 'rgba(107, 203, 119, 0.3)';
            
            // Ẩn phần key system
            document.getElementById('keySystem').classList.add('hidden');
            
            // Hiện menu chính
            document.getElementById('menuContent').classList.add('unlocked');
            
            showToast('✅ KEY HỢP LỆ! MENU ĐÃ MỞ');
            startInjectSequence();
        } else {
            status.className = 'key-status invalid';
            status.textContent = '✗';
            showToast('❌ KEY KHÔNG HỢP LỆ!');
            setTimeout(() => {
                if (!isUnlocked) {
                    status.className = 'key-status waiting';
                    status.textContent = '⏳';
                }
            }, 1500);
        }
    }
    
    // === UPDATE STATUS BADGE ===
    function updateStatusBadge(stepIndex) {
        const badge = document.getElementById('statusBadge');
        if (stepIndex >= 3) {
            badge.className = 'status online';
            badge.textContent = '● ONLINE';
        } else {
            badge.className = 'status offline';
            badge.textContent = '● OFFLINE';
        }
    }
    
    // === INJECT SEQUENCE ===
    function startInjectSequence() {
        if (injectRunning) return;
        injectRunning = true;
        
        const steps = [
            { icon: '⏳', text: 'Đang khởi động', cls: 'white', spinner: true },
            { icon: '⏳', text: '[1] Đang tìm FreeFire...', cls: 'yellow', spinner: true },
            { icon: '⏳', text: '[2] Đang inject...', cls: 'yellow', spinner: true },
            { icon: '✓', text: '[3] Đã inject FF pid=<span class="pid">-----</span> ✓', cls: 'green', spinner: false },
            { icon: '✓', text: '[4] Hoàn tất! ✓', cls: 'green', spinner: false }
        ];
        
        const display = document.getElementById('stepDisplay');
        const pid = Math.floor(10000 + Math.random() * 90000);
        
        const delays = [0, 1800, 4200, 6000, 7200];
        
        steps.forEach((step, index) => {
            setTimeout(() => {
                injectStep = index;
                display.classList.remove('active');
                setTimeout(() => {
                    let spinnerHtml = step.spinner ? ' <span class="spinner"></span>' : '';
                    let textContent = step.text;
                    if (step.text.includes('pid=<span')) {
                        textContent = step.text.replace('-----', pid);
                    }
                    display.innerHTML = `
                        <span class="icon">${step.icon}</span>
                        <span class="text ${step.cls}">${textContent}${spinnerHtml}</span>
                    `;
                    display.classList.add('active');
                    
                    updateStatusBadge(index);
                    
                    if (index === steps.length - 1) {
                        injectRunning = false;
                        showToast('✅ INJECT THÀNH CÔNG!');
                    }
                }, 250);
            }, delays[index]);
        });
    }
    
    // === TOGGLE ===
    function toggleElement(el, name) {
        if (!isUnlocked) return;
        el.classList.toggle('active');
        const state = el.classList.contains('active') ? 'ON' : 'OFF';
        showToast(name + ' → ' + state);
    }
    
    // === SLIDER ===
    function updateSlider(el, targetId) {
        document.getElementById(targetId).textContent = el.value;
    }
    
    function updateSliderFloat(el, targetId) {
        const val = (el.value / 100).toFixed(2);
        document.getElementById(targetId).textContent = val;
    }
    
    // === TARGET WARNING ===
    function updateTargetWarning(select) {
        if (!isUnlocked) return;
        const isHead = select.value === 'head';
        const icon = document.getElementById('warningIcon');
        const text = document.getElementById('warningText');
        
        if (isHead) {
            icon.classList.add('show');
            text.classList.add('show');
            showToast('⚠️ HEAD selected - HIGH RISK!');
        } else {
            icon.classList.remove('show');
            text.classList.remove('show');
            showToast('Target → ' + select.options[select.selectedIndex].text);
        }
    }
    
    // === TOAST ===
    function showToast(msg) {
        const t = document.getElementById('toast');
        t.textContent = msg;
        t.classList.add('show');
        clearTimeout(t._hide);
        t._hide = setTimeout(() => t.classList.remove('show'), 2000);
    }
    
    // === FAKE FPS & PLAYERS ===
    setInterval(() => {
        const base = 55 + Math.floor(Math.random() * 10);
        document.getElementById('fps').textContent = base;
    }, 500);
    
    setInterval(() => {
        const count = 8 + Math.floor(Math.random() * 14);
        document.getElementById('players').textContent = count;
    }, 2000);
    
    // === KEYBOARD SHORTCUTS ===
    document.addEventListener('keydown', function(e) {
        if (!isUnlocked) return;
        const key = e.key;
        if (key === 'F1') {
            const toggles = document.querySelectorAll('.toggle');
            if (toggles.length > 0) toggleElement(toggles[0], 'Aimbot');
        } else if (key === 'F2') {
            const toggles = document.querySelectorAll('.toggle');
            if (toggles.length > 3) toggleElement(toggles[3], 'ESP');
        }
    });
</script>
</body>
</html>
