<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Problem Help — решения для тиктокеров</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: #0a0e17;
            color: #e0e0e0;
            font-family: 'Segoe UI', Tahoma, sans-serif;
            padding: 20px;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .container {
            max-width: 900px;
            background: #141a26;
            padding: 40px 30px;
            border-radius: 24px;
            box-shadow: 0 0 40px rgba(0, 200, 255, 0.06);
            border: 1px solid #1f2a3a;
        }
        .header {
            display: flex;
            align-items: center;
            gap: 14px;
            margin-bottom: 25px;
            flex-wrap: wrap;
        }
        .header h1 {
            font-size: 2.4rem;
            background: linear-gradient(135deg, #66ccff, #aa88ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .header span {
            background: #1a2a3a;
            padding: 6px 16px;
            border-radius: 40px;
            font-size: 0.9rem;
            color: #88bbdd;
            border: 1px solid #2a4a5a;
        }
        .sub {
            color: #8899aa;
            font-size: 1.1rem;
            margin-bottom: 30px;
            border-left: 4px solid #66ccff;
            padding-left: 18px;
        }
        .card {
            background: #10161f;
            border-radius: 16px;
            padding: 18px 22px;
            margin-bottom: 18px;
            border: 1px solid #1f2a3a;
            transition: 0.25s;
        }
        .card:hover {
            border-color: #66ccff;
            box-shadow: 0 0 20px rgba(102, 204, 255, 0.05);
        }
        .card h3 {
            color: #66ccff;
            font-size: 1.2rem;
            margin-bottom: 8px;
        }
        .card p {
            color: #b0c0d0;
            font-size: 0.98rem;
            line-height: 1.5;
        }
        .card code {
            background: #0a101a;
            padding: 2px 10px;
            border-radius: 6px;
            font-size: 0.9rem;
            color: #dd99ff;
            border: 1px solid #1f2a3a;
            display: inline-block;
            margin-top: 8px;
        }
        .btn {
            display: inline-block;
            background: #1a2a3a;
            border: 1px solid #2a4a5a;
            padding: 10px 24px;
            border-radius: 40px;
            color: #c0d0e0;
            text-decoration: none;
            font-weight: 500;
            transition: 0.25s;
            margin-top: 12px;
            font-size: 0.95rem;
        }
        .btn:hover {
            background: #2a3a4a;
            border-color: #66ccff;
            color: #ffffff;
        }
        .footer {
            margin-top: 35px;
            border-top: 1px solid #1a2a3a;
            padding-top: 20px;
            color: #667788;
            font-size: 0.9rem;
            text-align: center;
        }
        .footer a {
            color: #88bbdd;
            text-decoration: none;
        }
        .footer a:hover {
            color: #66ccff;
        }
        .badge {
            background: #1a2a3a;
            padding: 4px 14px;
            border-radius: 30px;
            font-size: 0.75rem;
            color: #88aacc;
            border: 1px solid #2a4a5a;
            margin-right: 6px;
        }
        @media (max-width: 600px) {
            .container { padding: 25px 18px; }
            .header h1 { font-size: 1.8rem; }
        }
    </style>
</head>
<body>
<div class="container">

    <div class="header">
        <h1>🛠 Problem Help</h1>
        <span>тиктокерский набор</span>
    </div>

    <div class="sub">
        👋 Собрал решения для частых вопросов. Если не нашёл — пиши в Telegram, добавим.
    </div>

    <!-- ===== КАРТОЧКА 1 ===== -->
    <div class="card">
        <h3>🌐 GitHub Pages — сайт не открывается</h3>
        <p>
            Проверь:
            <br>1. Включил ли Pages в настройках репозитория (Settings → Pages → ветка main).
            <br>2. Есть ли файл <code>index.html</code> в корне.
            <br>3. Подожди 2–3 минуты после загрузки.
            <br>4. Ссылка: <code>https://[ник].github.io/[репозиторий]/</code>
        </p>
        <a href="#" class="btn">📄 Гайд с картинками</a>
    </div>

    <!-- ===== КАРТОЧКА 2 ===== -->
    <div class="card">
        <h3>📦 Как залить файлы на GitHub (с телефона)</h3>
        <p>
            1. Зайди в репозиторий → нажми <strong>«Add file»</strong> → <strong>«Upload files»</strong>.
            <br>2. Выбери файлы с телефона.
            <br>3. Напиши комментарий и нажми <strong>«Commit changes»</strong>.
            <br>4. Готово! Через минуту сайт обновится.
        </p>
        <a href="#" class="btn">📱 Видео-инструкция</a>
    </div>

    <!-- ===== КАРТОЧКА 3 ===== -->
    <div class="card">
        <h3>🧩 Как переименовать репозиторий</h3>
        <p>
            Зайди в <strong>Settings</strong> репозитория → в самом верху поле <strong>«Repository name»</strong> → измени → нажми <strong>«Rename»</strong>.
            <br>Старая ссылка будет работать ещё год (редирект).
        </p>
        <a href="#" class="btn">🔄 Подробнее</a>
    </div>

    <!-- ===== КАРТОЧКА 4 ===== -->
    <div class="card">
        <h3>🔴 Ошибка 404 на GitHub Pages</h3>
        <p>
            Чаще всего:
            <br>• файл называется не <code>index.html</code> (или лежит не в корне);
            <br>• не выбрана ветка в Pages (Settings → Pages → Branch: main);
            <br>• сайт ещё не успел задеплоиться (подожди 2 минуты).
        </p>
        <a href="#" class="btn">🧯 Чек-лист</a>
    </div>

    <!-- ===== КАРТОЧКА 5 ===== -->
    <div class="card">
        <h3>📝 Как обновить сайт после изменений</h3>
        <p>
            Обновляешь файл <code>index.html</code> через «Edit» на GitHub → Commit → ждёшь 1–2 минуты → обновляешь страницу (Ctrl+F5).
            <br>Сайт не обновился? Проверь, что закоммитил в ту же ветку.
        </p>
        <a href="#" class="btn">🔄 Гайд</a>
    </div>

    <!-- ===== КАРТОЧКА 6 ===== -->
    <div class="card">
        <h3>🎨 Как добавить красивый баннер / предупреждение</h3>
        <p>
            Вставь в HTML перед контентом:
            <br><code>&lt;div style="background:#1f0f0f; border:2px solid #ff4444; padding:18px; border-radius:14px; text-align:center; color:#ff8888;"&gt;⚠️ Твой текст&lt;/div&gt;</code>
        </p>
        <a href="#" class="btn">🎨 Примеры</a>
    </div>

    <!-- ПОДВАЛ -->
    <div class="footer">
        <p>🧡 Если помогло — поставь лайк в TikTok и отметь меня.  
        <br><a href="#">Telegram</a> · <a href="#">TikTok</a></p>
        <p style="margin-top: 12px; font-size: 0.8rem; color: #445566;">
            © 2026 — Problem Help / SRG
        </p>
    </div>

</div>
</body>
</html>
