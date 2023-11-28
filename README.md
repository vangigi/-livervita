<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LiverVita</title>
    <style>
        /* 基础样式 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f0f0f0; /* 整体背景颜色 */
            line-height: 1.6;
        }

        /* 顶部导航栏 */
        header {
            background: #004d40; /* 深绿色背景 */
            color: white;
            padding: 1rem 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        /* 导航链接 */
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.2s;
        }

        nav a:hover {
            color: #47a447; /* 醒目的绿色 */
        }

        /* 主标题 */
        .title {
            color: #004d40; /* 深绿色 */
            text-align: center;
            padding: 2rem 0;
        }

        /* 特色区块 */
        .feature {
            background: #e8f5e9; /* 浅绿色背景 */
            padding: 2rem;
            margin: 1rem 0;
            text-align: center;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        /* 底部样式 */
        footer {
            background: #004d40; /* 深绿色背景 */
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <a href="#home">首页</a>
            <a href="#products">产品</a>
            <a href="#health-info">健康知识</a>
            <a href="#about">关于我们</a>
            <a href="#contact">联系方式</a>
        </nav>
    </header>

    <div class="title">
        <h1>LiverVita</h1>
    </div>

    <section id="products" class="feature">
        <h2>我们的产品</h2>
        <p>探索高品质的肝脏保健品。</p>
    </section>

    <section id="health-info" class="feature">
        <h2>肝脏健康知识</h2>
        <p>最新的肝脏保健信息和研究。</p>
    </section>

    <section id="about" class="feature">
        <h2>关于LiverVita</h2>
        <p>了解我们的品牌故事和愿景。</p>
    </section>

    <section id="contact" class="feature">
        <h2>联系我们</h2>
        <p>有任何问题，请随时联系我们。</p>
    </section>

    <footer>
        <p>&copy; 2023 LiverVita. 版权所有。</p>
    </footer>

</body>
</html>
