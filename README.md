<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>wiznkingpro · github profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #0d1117;
            font-family: 'SF Mono', 'Fira Code', 'JetBrains Mono', monospace;
            display: flex;
            justify-content: center;
            padding: 2rem 1rem;
            line-height: 1.5;
        }

        .profile {
            max-width: 880px;
            width: 100%;
        }

        /* блоки как на GitHub – но чище */
        .card {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 20px;
            padding: 1.8rem;
            margin-bottom: 1.8rem;
            transition: border 0.1s ease;
        }

        .card:hover {
            border-color: #6e7681;
        }

        /* хедер с аватаркой */
        .header {
            display: flex;
            align-items: center;
            gap: 1.5rem;
            flex-wrap: wrap;
        }
        .avatar {
            width: 88px;
            height: 88px;
            border-radius: 50%;
            object-fit: cover;
            border: 1px solid #30363d;
        }
        .title h1 {
            font-size: 1.8rem;
            font-weight: 500;
            color: #f0f6fc;
            letter-spacing: -0.3px;
        }
        .title p {
            color: #8b949e;
            margin-top: 0.3rem;
            font-size: 0.95rem;
        }

        /* секция с текстом */
        .bio {
            color: #c9d1d9;
            font-size: 0.95rem;
            border-left: 3px solid #3fb950;
            padding-left: 1.2rem;
            margin: 1rem 0 0.2rem 0;
        }

        /* ссылки — без подчёркиваний, аккуратно */
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }

        /* ряд с виджетами */
        .stats-row {
            display: flex;
            flex-wrap: wrap;
            gap: 1.2rem;
            justify-content: center;
            margin: 1.2rem 0;
        }
        .stats-row img {
            border-radius: 12px;
            max-width: 100%;
            height: auto;
            background: #0d1117;
        }

        /* трофеи и кастомные блоки */
        .trophy-place img {
            max-width: 100%;
        }

        .badge-list {
            display: flex;
            flex-wrap: wrap;
            gap: 0.8rem;
            margin-top: 0.75rem;
        }
        .badge {
            background: #21262d;
            padding: 0.2rem 0.75rem;
            border-radius: 30px;
            font-size: 0.75rem;
            color: #c9d1d9;
            font-family: monospace;
        }

        hr {
            border: 0;
            height: 0;
            border-top: 1px solid #30363d;
            margin: 1rem 0;
        }

        .quote-text {
            font-style: normal;
            color: #8b949e;
            font-size: 0.9rem;
            padding: 0.5rem 0 0 0;
        }

        .footer-note {
            font-size: 0.7rem;
            text-align: center;
            color: #6e7681;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
<div class="profile">

    <!-- ШАПКА: ник, описание -->
    <div class="card">
        <div class="header">
            <img class="avatar" src="https://github.com/wiznkingpro.png" alt="avatar">
            <div class="title">
                <h1>wiznkingpro</h1>
                <p>user /arch + hyprland/ &nbsp;·&nbsp; /g/ reader</p>
            </div>
        </div>
        <div class="bio">
            ⚡ конфиги вместо резюме ·  I use arch, btw
        </div>
    </div>

    <!-- СТАТИСТИКА (основные виджеты из статьи) -->
    <div class="card">
        <h3 style="color:#f0f6fc; font-weight: 500; margin-bottom: 1rem;">📊 github metrics</h3>
        <div class="stats-row">
            <img src="https://github-readme-stats.vercel.app/api?username=wiznkingpro&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&icon_color=58a6ff&title_color=f0f6fc" alt="stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=wiznkingpro&layout=compact&theme=dark&hide_border=true&bg_color=0d1117" alt="top langs">
        </div>
        <div class="stats-row">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=wiznkingpro&theme=dark&hide_border=true&background=0d1117&stroke=30363d&ring=3fb950&fire=3fb950&currStreakLabel=f0f6fc" alt="streak stats">
        </div>
    </div>

    <!-- ТРОФЕИ (на минимализме выглядят как теги) -->
    <div class="card">
        <h3 style="color:#f0f6fc; font-weight: 500; margin-bottom: 0.6rem;">🏆 achievements</h3>
        <div class="trophy-place">
            <img src="https://github-profile-trophy.vercel.app/?username=wiznkingpro&theme=darkhub&no-frame=true&row=1&column=5" alt="trophy" style="max-width:100%;">
        </div>
    </div>

    <!-- МИНИМАЛЬНЫЕ БАДЖИ (набор стеков) -->
    <div class="card">
        <h3 style="color:#f0f6fc; font-weight: 500;">⚙️ stack / tools</h3>
        <div class="badge-list">
            <span class="badge">hyprland / waybar</span>
            <span class="badge">arch linux</span>
            <span class="badge">kitty / fish</span>
            <span class="badge">rofi / wofi</span>
            <span class="badge">git / github cli</span>
            <span class="badge">micro / neovim</span>
        </div>
    </div>

    <!-- ЦИТАТА (из статьи — random quote плагин) -->
    <div class="card">
        <h3 style="color:#f0f6fc; font-weight: 500; margin-bottom: 0.4rem;">📖 terminal wisdom</h3>
        <div class="quote-text">
            <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="random quote" style="max-width:100%; border-radius: 12px;">
        </div>
        <div class="bio" style="margin-top: 0.8rem; border-left-color: #58a6ff;">
            — from habr.com guide
        </div>
    </div>

    <!-- ССЫЛКИ И СЧЁТЧИК (view counter – тоже из статьи) -->
    <div class="card">
        <div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
            <span style="color:#8b949e;">🔄 repos / dots</span>
            <span style="font-size: 0.75rem; color:#6e7681;">
                <img src="https://komarev.com/ghpvc/?username=wiznkingpro&color=3fb950&style=flat-square" alt="visitors">
            </span>
        </div>
        <div style="margin-top: 1rem;">
            <a href="https://github.com/wiznkingpro/Hyprland-config" target="_blank">› hyprland-config</a><br>
            <a href="https://github.com/wiznkingpro" target="_blank">› github / wiznkingpro</a>
        </div>
        <hr>
        <div style="font-size: 0.7rem; color: #5c6778;">
            $ cat ~/.profile<br>
            # минимализм + честная статистика<br>
            # оформлено под влиянием хабра-статьи "Как информативно оформить профиль на GitHub"
        </div>
    </div>

    <div class="footer-note">
        wiznkingpro · arch + hyprland · grep is love
    </div>
</div>
</body>
</html>
