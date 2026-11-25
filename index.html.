<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мир технологий</title>
    <style>
        :root {
            --bg-color: #f4f7fb;
            --card-bg: #ffffff;
            --text-color: #1e293b;
            --text-muted: #475569;
            --accent: #2563eb;
            --accent-hover: #1d4ed8;
            --shadow: 0 10px 25px rgba(0, 0, 0, 0.06);
        }

        body.dark-theme {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-color: #f8fafc;
            --text-muted: #94a3b8;
            --accent: #3b82f6;
            --accent-hover: #60a5fa;
            --shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            transition: background-color 0.3s, color 0.3s;
        }

        header {
            background-color: var(--card-bg);
            box-shadow: var(--shadow);
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-size: 1.4rem;
            font-weight: bold;
            color: var(--accent);
        }

        .theme-btn {
            background: transparent;
            border: 2px solid var(--accent);
            color: var(--text-color);
            padding: 6px 14px;
            border-radius: 20px;
            cursor: pointer;
            font-size: 0.9rem;
            transition: 0.3s;
        }

        .theme-btn:hover {
            background: var(--accent);
            color: #fff;
        }

        .container {
            max-width: 960px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .hero {
            background-color: var(--card-bg);
            padding: 40px;
            border-radius: 16px;
            box-shadow: var(--shadow);
            margin-bottom: 30px;
        }

        .hero h1 {
            font-size: 2.2rem;
            margin-bottom: 20px;
            color: var(--accent);
        }

        .hero p {
            margin-bottom: 16px;
            font-size: 1.05rem;
            color: var(--text-muted);
        }

        .main-btn {
            background-color: var(--accent);
            color: #ffffff;
            border: none;
            padding: 12px 26px;
            font-size: 1rem;
            font-weight: 600;
            border-radius: 8px;
            cursor: pointer;
            margin-top: 10px;
            transition: background-color 0.3s, transform 0.2s;
        }

        .main-btn:hover {
            background-color: var(--accent-hover);
            transform: translateY(-2px);
        }

        #moreText {
            display: none;
            margin-top: 25px;
            padding-top: 20px;
            border-top: 1px solid rgba(148, 163, 184, 0.3);
            animation: fadeIn 0.4s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-5px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: var(--card-bg);
            padding: 25px;
            border-radius: 14px;
            box-shadow: var(--shadow);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            margin-bottom: 10px;
            color: var(--accent);
        }

        .card p {
            font-size: 0.95rem;
            color: var(--text-muted);
        }

        footer {
            text-align: center;
            padding: 30px 20px;
            color: var(--text-muted);
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">TechFuture</div>
        <button class="theme-btn" id="themeToggle" onclick="toggleTheme()">🌙 Тёмная тема</button>
    </header>

    <main class="container">
        <section class="hero">
            <h1>Современные технологии в нашей жизни</h1>
            <p>Цифровые технологии стремительно меняют мир вокруг нас. Смартфоны, высокоскоростной интернет и облачные сервисы позволяют учиться, работать и общаться с людьми из любой точки планеты за считанные секунды.</p>
            <p>Особое место сегодня занимает искусственный интеллект и робототехника. Умные алгоритмы помогают врачам ставить точные диагнозы, управляют беспилотным транспортом и берут на себя сложные рутинные задачи.</p>
            
            <button class="main-btn" id="moreBtn" onclick="toggleMore()">Узнать больше</button>

            <div id="moreText">
                <h3>Технологии будущего</h3>
                <p>В ближайшем будущем нас ждёт развитие квантовых компьютеров, «умных» городов и виртуальной реальности. Освоение цифровых навыков уже сейчас открывает доступ к самым востребованным профессиям завтрашнего дня.</p>
            </div>
        </section>

        <section class="cards">
            <div class="card">
                <h3>🤖 Искусственный интеллект</h3>
                <p>Нейросети анализируют огромные объёмы данных, создают изображения, пишут код и помогают учёным открывать новые лекарства.</p>
            </div>
            <div class="card">
                <h3>🦾 Робототехника</h3>
                <p>Автоматизированные системы работают на заводах, доставляют посылки и помогают исследовать глубины океана и космос.</p>
            </div>
            <div class="card">
                <h3>🌐 Интернет вещей</h3>
                <p>Умные часы, бытовая техника и датчики в домах объединяются в единую сеть для комфорта и экономии энергии.</p>
            </div>
        </section>
    </main>

    <footer>
        © 2026 Учебный проект по информатике • Веб-разработка
    </footer>

    <script>
        function toggleMore() {
            const block = document.getElementById("moreText");
            const btn = document.getElementById("moreBtn");

            if (block.style.display === "block") {
                block.style.display = "none";
                btn.textContent = "Узнать больше";
            } else {
                block.style.display = "block";
                btn.textContent = "Скрыть";
            }
        }

        function toggleTheme() {
            const body = document.body;
            const themeBtn = document.getElementById("themeToggle");
            body.classList.toggle("dark-theme");

            if (body.classList.contains("dark-theme")) {
                themeBtn.textContent = "☀️ Светлая тема";
            } else {
                themeBtn.textContent = "🌙 Тёмная тема";
            }
        }
    </script>

</body>
</html>
