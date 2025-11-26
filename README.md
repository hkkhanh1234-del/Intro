
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới thiệu Kim Khánh</title>
    <style>
        :root {
            --primary: #003161;
            --secondary: #006A67;
            --bg: #FFF4B7;
            --text: #0b0b0b;
            --card-bg: white;
            --radius: 12px;
            --shadow: 0 6px 18px rgba(0,0,0,0.15);
        }

        body {
            margin: 0;
            font-family: "Segoe UI", Arial, sans-serif;
            background: var(--bg);
            color: var(--text);
        }

        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            text-align: center;
            padding: 50px 20px;
            box-shadow: var(--shadow);
        }

        header img {
            width: 120px;
            border-radius: 50%;
            border: 4px solid var(--bg);
            margin-bottom: 15px;
        }

        header h1 {
            margin: 10px 0;
            font-size: 36px;
        }

        header p {
            font-size: 18px;
            opacity: 0.9;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .card {
            background: var(--card-bg);
            padding: 25px;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            margin-bottom: 25px;
            transition: 0.25s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h2 {
            margin-top: 0;
            color: var(--primary);
        }

        .card ul {
            padding-left: 20px;
        }

        .card a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 18px;
            background: var(--secondary);
            color: white;
            border-radius: 8px;
            text-decoration: none;
            transition: 0.25s;
        }

        .card a:hover {
            background: var(--primary);
        }

        footer {
            text-align: center;
            padding: 15px;
            background: var(--primary);
            color: var(--bg);
            margin-top: 40px;
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <img src="https://raw.githubusercontent.com/daisubinta/Nhom4tin12anh.github.io/refs/heads/main/golden-retriever-tongue-out.jpg" alt="Kim Khánh">
    <h1>Huỳnh Kim Khánh</h1>
    <p>Lớp 12A • Sáng tạo nội dung & lập trình web</p>
</header>

<div class="container">

    <div class="card">
        <h2>Giới thiệu</h2>
        <p>Mình là Huỳnh Kim Khánh, học sinh lớp 12A. Mình yêu thích viết, thiết kế giao diện web, khám phá ý tưởng mới và học ngôn ngữ. Mình luôn cố gắng cải thiện bản thân qua từng dự án và học hỏi thêm điều mới.</p>
    </div>

    <div class="card">
        <h2>Sở thích</h2>
        <ul>
            <li>🏊‍♂️ Bơi lội và đi biển</li>
            <li>🎨 Thiết kế bằng Canva & lập trình giao diện web</li>
            <li>📚 Đọc sách phát triển bản thân</li>
            <li>🌍 Khám phá ngôn ngữ mới: Tiếng Trung, Tây Ban Nha...</li>
        </ul>
    </div>

    <div class="card">
        <h2>Công cụ mình dùng</h2>
        <ul>
            <li>💡 Figma, Canva, Visual Studio Code</li>
            <li>📬 Email Marketing, Copywriting</li>
            <li>🌐 HTML, CSS, GitHub Pages</li>
        </ul>
    </div>

    <div class="card">
        <h2>Liên kết</h2>
        <a href="https://hkkhanh1234.github.io" target="_blank">Trang cá nhân / Portfolio</a>
    </div>

</div>

<footer>
    © 2025 Huỳnh Kim Khánh | Lớp 12A
</footer>

</body>
</html>
