<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MeawMeawChan | AI 动物艺术空间</title>
    <style>
        :root {
            --bg-color: #0f0f0f;
            --card-bg: #1e1e1e;
            --accent-color: #3ea6ff;
            --text-color: #ffffff;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            text-align: center;
            margin-bottom: 40px;
        }

        h1 { color: var(--accent-color); margin-bottom: 5px; }
        p { opacity: 0.7; }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            width: 100%;
            max-width: 1200px;
        }

        .card {
            background: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            transition: transform 0.3s;
            border: 1px solid #333;
        }

        .card:hover { transform: translateY(-5px); }

        .card-img {
            width: 100%;
            height: 200px;
            background: #333; /* 这里将来放你的 AI 原图 */
            display: flex;
            align-items: center;
            justify-content: center;
            color: #555;
        }

        .card-content { padding: 15px; }

        .btn {
            display: inline-block;
            background: var(--accent-color);
            color: #000;
            padding: 8px 20px;
            border-radius: 20px;
            text-decoration: none;
            font-weight: bold;
            font-size: 14px;
        }

        .btn:hover { background: #65b8ff; }
    </style>
</head>
<body>

<header>
    <h1>MeawMeawChan</h1>
    <p>探索 AI 镜头下的奇幻动物世界</p>
</header>

<div class="gallery">
    <div class="card">
        <div class="card-img">宇航猫原图预览</div>
        <div class="card-content">
            <h3>Space Cat #01</h3>
            <p>分辨率: 4K (Ultra HD)</p>
            <a href="#" class="btn">免费下载原图</a>
        </div>
    </div>

    <div class="card">
        <div class="card-img">马来貘原图预览</div>
        <div class="card-content">
            <h3>Mystic Tapir</h3>
            <p>分辨率: 4K (Ultra HD)</p>
            <a href="#" class="btn">免费下载原图</a>
        </div>
    </div>
</div>

</body>
</html>
