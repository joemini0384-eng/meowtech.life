<!DOCTYPE html>
<html lang="zh-HK">
<head>
    <meta charset="UTF-8">
    <title>Joe & Cat | Tech Life</title>
    <style>
        body { font-family: 'Helvetica', sans-serif; background-color: #f5f5f7; margin: 0; padding: 20px; color: #333; }
        .container { max-width: 960px; margin: 0 auto; background: white; padding: 40px; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
        header { text-align: center; margin-bottom: 40px; border-bottom: 2px solid #f39c12; padding-bottom: 20px; }
        h1 { font-size: 3em; color: #2c3e50; margin: 0; }
        .subtitle { color: #f39c12; font-weight: bold; letter-spacing: 2px; }
        
        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; }
        .card { padding: 30px; border-radius: 8px; transition: 0.3s; }
        .card:hover { transform: translateY(-5px); }
        
        /* Tech Section */
        .tech { background-color: #eef2f3; border-left: 6px solid #3498db; }
        /* Meow Section */
        .meow { background-color: #fef9f0; border-left: 6px solid #e67e22; }
        
        h2 { font-size: 1.8em; margin-top: 0; }
        p { line-height: 1.6; }
        .placeholder-img { width: 100%; height: 250px; background-color: #ddd; display: flex; align-items: center; justify-content: center; color: #777; margin-top: 15px; border-radius: 6px; border: 2px dashed #bbb; }
        
        footer { text-align: center; margin-top: 60px; color: #999; font-size: 0.9em; }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Joe & Cat 🐱</h1>
            <span class="subtitle">TECH LIFE | DIGITAL DIARY</span>
        </header>

        <div class="grid">
            <!-- 左邊：技術 -->
            <div class="card tech">
                <h2>Tech & Projects</h2>
                <p>AI Experimentation, Code Reviews & Digital Innovation.</p>
                <p>Here goes the latest Tech Analysis & Deep Dive papers.</p>
            </div>

            <!-- 右邊：貓咪 -->
            <div class="card meow">
                <h2>Meow Diary 🐾</h2>
                <p>Cat videos, funny moments, and food reviews.</p>
                <div class="placeholder-img">Cat Photo Here (Upload later)</div>
            </div>
        </div>

        <footer>
            © 2026 Joe & Tech. Powered by meowtech.life
        </footer>
    </div>

</body>
</html>
