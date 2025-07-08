<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAX Links Hub</title>
    <style>
        :root {
            --bg-color: #121212;
            --card-color: #1e1e1e;
            --text-color: #e0e0e0;
            --accent-color: #bb86fc;
            --secondary-color: #03dac6;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
        }
        
        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            padding: 20px;
            line-height: 1.6;
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid #333;
        }
        
        h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
            color: var(--accent-color);
            font-weight: 700;
        }
        
        .subtitle {
            font-size: 1rem;
            color: #aaa;
            margin-bottom: 15px;
        }
        
        .contact {
            font-size: 0.9rem;
            color: var(--secondary-color);
            margin-top: 10px;
        }
        
        .links-container {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            max-width: 600px;
            margin: 0 auto;
        }
        
        .link-card {
            background-color: var(--card-color);
            border-radius: 12px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .link-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .card-image {
            width: 100%;
            height: 160px;
            object-fit: cover;
            border-bottom: 1px solid #333;
        }
        
        .card-content {
            padding: 18px;
        }
        
        .card-title {
            font-size: 1.3rem;
            margin-bottom: 8px;
            color: var(--accent-color);
        }
        
        .card-description {
            font-size: 0.95rem;
            margin-bottom: 15px;
            color: #ccc;
        }
        
        .card-link {
            display: inline-block;
            padding: 8px 16px;
            background-color: var(--accent-color);
            color: #000;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 600;
            transition: background-color 0.3s ease;
        }
        
        .card-link:hover {
            background-color: var(--secondary-color);
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #333;
            font-size: 0.8rem;
            color: #777;
        }
        
        /* Анимации */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .link-card {
            animation: fadeIn 0.6s ease forwards;
            opacity: 0;
        }
        
        .link-card:nth-child(1) { animation-delay: 0.1s; }
        .link-card:nth-child(2) { animation-delay: 0.2s; }
        .link-card:nth-child(3) { animation-delay: 0.3s; }
        .link-card:nth-child(4) { animation-delay: 0.4s; }
        .link-card:nth-child(5) { animation-delay: 0.5s; }
        .link-card:nth-child(6) { animation-delay: 0.6s; }
    </style>
</head>
<body>
    <header>
        <h1>MAX Links Hub</h1>
        <div class="subtitle">Лучшие группы MAX одном месте</div>
        <div class="contact">Добавить группу: @Manish_Chandra2 (Telegram)</div>
    </header>
    
    <div class="links-container">
        <!-- КАРТОЧКА 1 -->
        <div class="link-card">
            <img src="https://rkn.gov.ru/images/news/image57154.jpg" alt="MAX Links Group" class="card-image">
            <div class="card-content">
                <h3 class="card-title"></h3>
                <p class="card-description">Разгаворный чат, критика в сторону РКН поддерживается.</p>
                <a href="https://max.ru/join/HZTUpdHuvlZeF4rUnc0PqP1sp-Kdp8VA3SATPwiRNog" class="card-link">Присоединиться</a>
            </div>
        </div>
    
    <footer>
        <p>© 2025 lk.</p>
        <p>Администратор: @Manish_Chandra2 (Telegram)</p>
    </footer>
    
    <script>
        // Небольшой скрипт для плавной загрузки
        document.addEventListener('DOMContentLoaded', function() {
            // Можно добавить больше интерактивности при необходимости
            console.log('Page loaded!');
        });
    </script>
</body>
</html>
