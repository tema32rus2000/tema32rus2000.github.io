<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
  <title>Teast · Social</title>
  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #0a1a0e;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Segoe UI', 'Roboto', 'Arial', sans-serif;
      /* почти без отступов – во весь экран */
      padding: 8px;
      animation: fadeIn 0.5s ease;
    }

    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    /* Основная карточка — теперь почти на весь экран */
    .fullscreen-card {
      width: 100%;
      max-width: 700px;  /* ограничим ширину на больших экранах, но без полей */
      background: #1a2e1f;
      border-radius: 24px;
      box-shadow: 0 20px 30px -5px rgba(0, 0, 0, 0.7), 0 0 0 1px #3b6e3b inset;
      overflow: hidden;
      transition: all 0.2s;
      animation: slideUp 0.5s cubic-bezier(0.2, 0.9, 0.4, 1);
      border: 1px solid #3a6e3a;
    }

    @keyframes slideUp {
      0% { opacity: 0; transform: translateY(30px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    /* Шапка с вкладками – зелёные тона */
    .tabs-header {
      display: flex;
      background: #0f1f12;
      border-bottom: 3px solid #2e7d5e;
      padding: 0 12px;
    }

    .tab-btn {
      flex: 0 1 auto;
      padding: 1rem 2rem;
      font-size: 1.6rem;
      font-weight: 700;
      letter-spacing: 0.5px;
      background: transparent;
      border: none;
      color: #b0d9b0;
      cursor: pointer;
      transition: all 0.15s;
      text-transform: uppercase;
      font-family: 'Arial Black', 'Impact', sans-serif;
      border-radius: 16px 16px 0 0;
      margin-right: 6px;
      position: relative;
    }

    .tab-btn i {
      margin-right: 10px;
      font-size: 1.4rem;
    }

    .tab-btn:hover {
      background: #2a4a2f;
      color: #e0ffe0;
    }

    .tab-btn.active {
      background: #1a2e1f;
      color: #b3f0b3;
      box-shadow: 0 -3px 0 #2e7d5e inset, 0 2px 8px rgba(0,0,0,0.3);
      border-bottom: 2px solid #1a2e1f;
    }

    /* Контент */
    .tab-content {
      padding: 2rem 1.8rem 2.2rem;
      background: #1a2e1f;
    }

    .tab-pane {
      display: none;
      animation: fadePane 0.25s ease;
    }

    .tab-pane.active {
      display: block;
    }

    @keyframes fadePane {
      0% { opacity: 0.3; transform: translateY(6px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    /* ===== Вкладка Me ===== */
    .profile-me {
      text-align: center;
    }

    .avatar-me {
      width: 130px;
      height: 130px;
      margin: 0 auto 1.2rem;
      border-radius: 24px;
      border: 4px solid #3a8a5e;
      box-shadow: 0 8px 0 #1b4a2a, 0 10px 20px rgba(0,0,0,0.5);
      overflow: hidden;
      background: #1e402e;
      transition: transform 0.2s;
    }

    .avatar-me img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    .avatar-me:hover {
      transform: scale(1.02);
    }

    h1 {
      font-size: 3.2rem;
      font-weight: 900;
      text-transform: uppercase;
      font-family: 'Arial Black', 'Impact', sans-serif;
      color: #b8f0c8;
      text-shadow: 4px 4px 0 #1e4a2e, 2px 2px 0 #00000040;
      letter-spacing: 1px;
      margin-bottom: 0.5rem;
    }

    /* Никаких Player бейджей – только описание */
    .bio {
      background: #1f3b26;
      padding: 1.2rem 1.5rem;
      border-radius: 20px;
      border-left: 10px solid #3a9e6a;
      font-size: 1.2rem;
      color: #daf0da;
      margin: 1.8rem 0 1rem;
      box-shadow: inset 0 2px 6px #0c1e0c, 0 5px 0 #142314;
      text-align: left;
    }

    .bio i {
      color: #7fcf9f;
      margin-right: 10px;
    }

    .me-footer {
      margin-top: 30px;
      font-size: 0.9rem;
      color: #8fc09f;
    }

    /* ===== Вкладка Socials ===== */
    .socials-list {
      display: flex;
      flex-direction: column;
      gap: 1.5rem;
    }

    .social-item {
      background: #233e29;
      border-radius: 18px;
      padding: 1rem 1.4rem;
      display: flex;
      align-items: center;
      box-shadow: 0 7px 0 #0f1f0f, 0 3px 10px black;
      border: 2px solid #3f7a4f;
      transition: all 0.1s ease;
    }

    .social-item:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 0 #0f1f0f, 0 8px 15px black;
      border-color: #5faf7f;
    }

    .social-icon {
      width: 60px;
      height: 60px;
      background: #1a3a24;
      border-radius: 16px;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-right: 1.2rem;
      font-size: 2.4rem;
      color: #9fdfaf;
      border: 2px solid #4f9e6f;
      box-shadow: inset 0 2px 4px #0e1e0e, 0 5px 0 #0e1e0e;
      transition: 0.1s;
    }

    .social-item:hover .social-icon {
      background: #2c5538;
      color: #c0f0c0;
      border-color: #6fbf8f;
    }

    .social-info {
      flex: 1;
    }

    .social-title {
      font-size: 1.6rem;
      font-weight: 800;
      color: #e6f7e6;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }

    .social-sub {
      font-size: 0.95rem;
      color: #b1dbb1;
      display: flex;
      align-items: center;
      gap: 8px;
      flex-wrap: wrap;
    }

    .social-action .btn-green {
      background: #2e6e3e;
      border: none;
      color: white;
      font-weight: bold;
      padding: 0.6rem 1.5rem;
      border-radius: 40px;
      font-size: 0.95rem;
      cursor: pointer;
      box-shadow: 0 5px 0 #1a3a1a;
      transition: 0.08s linear;
      text-decoration: none;
      display: inline-block;
      border: 1px solid #5fa86f;
      text-transform: uppercase;
    }

    .btn-green i {
      margin-right: 8px;
    }

    .btn-green:hover {
      background: #3f8f4f;
      transform: translateY(-2px);
      box-shadow: 0 7px 0 #1a3a1a;
    }

    .btn-green:active {
      transform: translateY(2px);
      box-shadow: 0 3px 0 #1a3a1a;
    }

    .btn-green.copy-btn {
      background: #1f4f2a;
      box-shadow: 0 5px 0 #0f2a14;
    }

    .btn-green.copy-btn:hover {
      background: #2f6f3a;
    }

    /* Футер */
    .footer-note {
      margin-top: 2rem;
      text-align: center;
      color: #7fa37f;
      font-size: 0.8rem;
      border-top: 1px dashed #3f7a4f;
      padding-top: 1.2rem;
    }

    /* Toast */
    .toast-msg {
      position: fixed;
      bottom: 30px;
      left: 50%;
      transform: translateX(-50%);
      background: #1a3a1a;
      color: #d0f0d0;
      padding: 0.8rem 2rem;
      border-radius: 50px;
      font-weight: bold;
      border: 2px solid #3faf6f;
      box-shadow: 0 8px 0 #0e1e0e;
      opacity: 0;
      transition: opacity 0.2s;
      pointer-events: none;
      z-index: 999;
      text-transform: uppercase;
      font-size: 1rem;
    }

    .toast-msg.show {
      opacity: 1;
    }

    /* Адаптивность */
    @media (max-width: 550px) {
      body { padding: 4px; }
      .tab-btn { padding: 0.8rem 1.2rem; font-size: 1.3rem; }
      .social-title { font-size: 1.3rem; }
      .social-icon { width: 52px; height: 52px; font-size: 2rem; }
      h1 { font-size: 2.6rem; }
      .bio { font-size: 1rem; padding: 1rem; }
    }

    @media (min-width: 1200px) {
      .fullscreen-card { max-width: 800px; }
    }
  </style>
</head>
<body>

<div class="fullscreen-card">
  <!-- Вкладки -->
  <div class="tabs-header">
    <button class="tab-btn active" data-tab="me">
      <i class="fas fa-user-astronaut"></i> Me
    </button>
    <button class="tab-btn" data-tab="socials">
      <i class="fas fa-share-alt"></i> Socials
    </button>
  </div>

  <!-- Контент -->
  <div class="tab-content">
    <!-- Вкладка Me -->
    <div id="tab-me" class="tab-pane active">
      <div class="profile-me">
        <div class="avatar-me">
          <img src="https://media.discordapp.net/attachments/1412412538532003882/1492146317261013042/image.png?ex=69dee24c&is=69dd90cc&hm=a1580177d86d99ea122a8a6d8caafa6b02635dc6f58098a72c66f2c263d6626e&=&format=webp&quality=lossless&width=1160&height=1058" alt="Teast">
        </div>
        <h1>Teast</h1>
        <div class="bio">
          <i class="fas fa-comment-dots"></i> Hello! I am Teast! Welcome to my site, there are some links to my socials.
        </div>
        <div class="me-footer">
          <i class="fas fa-leaf"></i> Ready for adventures · 2026
        </div>
      </div>
    </div>

    <!-- Вкладка Socials -->
    <div id="tab-socials" class="tab-pane">
      <div class="socials-list">
        <!-- Roblox профиль -->
        <div class="social-item">
          <div class="social-icon"><i class="fab fa-roblox"></i></div>
          <div class="social-info">
            <div class="social-title">Roblox</div>
            <div class="social-sub">@Teast · профиль</div>
          </div>
          <div class="social-action">
            <a href="https://www.roblox.com/users/1340721796/profile" target="_blank" rel="noopener" class="btn-green">
              <i class="fas fa-external-link-alt"></i> Открыть
            </a>
          </div>
        </div>
        <!-- Discord (теперь только здесь) -->
        <div class="social-item">
          <div class="social-icon"><i class="fab fa-discord"></i></div>
          <div class="social-info">
            <div class="social-title">Discord</div>
            <div class="social-sub">
              <span id="discordNickDisplay">luciendre</span> 
              <span style="opacity:0.8;">· ID: 1392202165606420744</span>
            </div>
          </div>
          <div class="social-action">
            <button class="btn-green copy-btn" onclick="copyDiscord()">
              <i class="far fa-copy"></i> Копировать
            </button>
          </div>
        </div>
        <!-- Roblox Group -->
        <div class="social-item">
          <div class="social-icon"><i class="fas fa-users"></i></div>
          <div class="social-info">
            <div class="social-title">Quantum Dynamics</div>
            <div class="social-sub">Roblox группа</div>
          </div>
          <div class="social-action">
            <a href="https://www.roblox.com/communities/424646908/Quantum-Dynamics#!/about" target="_blank" rel="noopener" class="btn-green">
              <i class="fas fa-users-between-lines"></i> Перейти
            </a>
          </div>
        </div>
      </div>
      <div class="footer-note">
        <i class="fas fa-crown" style="color:#7fbf7f;"></i> Teast · GitHub Pages
      </div>
    </div>
  </div>
</div>

<!-- Toast -->
<div id="liveToast" class="toast-msg">
  <i class="fas fa-check-circle"></i> Ник <span id="copiedNickSpan">luciendre</span> скопирован!
</div>

<script>
  (function() {
    // Переключение вкладок
    const tabs = document.querySelectorAll('.tab-btn');
    const panes = {
      me: document.getElementById('tab-me'),
      socials: document.getElementById('tab-socials')
    };

    function switchTab(tabId) {
      tabs.forEach(btn => {
        btn.classList.toggle('active', btn.dataset.tab === tabId);
      });
      for (let id in panes) {
        panes[id].classList.toggle('active', id === tabId);
      }
    }

    tabs.forEach(btn => {
      btn.addEventListener('click', (e) => {
        const tabId = btn.dataset.tab;
        if (tabId) switchTab(tabId);
      });
    });

    // Копирование Discord ника
    window.copyDiscord = function() {
      const nick = "luciendre";
      navigator.clipboard.writeText(nick).then(() => {
        showToast(nick);
      }).catch(() => {
        const ta = document.createElement('textarea');
        ta.value = nick;
        document.body.appendChild(ta);
        ta.select();
        document.execCommand('copy');
        document.body.removeChild(ta);
        showToast(nick);
      });
    };

    function showToast(nickname) {
      const toast = document.getElementById('liveToast');
      const span = document.getElementById('copiedNickSpan');
      if (span) span.textContent = nickname;
      toast.classList.add('show');
      setTimeout(() => toast.classList.remove('show'), 2000);
    }

    // Небольшая интерактивность аватарки
    const avatar = document.querySelector('.avatar-me');
    if(avatar) {
      avatar.addEventListener('click', () => {
        avatar.style.transform = 'scale(0.97)';
        setTimeout(() => avatar.style.transform = '', 120);
      });
    }
  })();
</script>
</body>
</html>
