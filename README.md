# Safe-Route
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Safe Route</title> <!-- Đã thay đổi tiêu đề trang web -->
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e5f7e0; /* Màu nền xanh lá nhạt */
            color: #333;
            text-align: center; /* Căn lề giữa cho toàn bộ nội dung */
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        /* Header Styles */
        header {
            background-color: #4CAF50; /* Xanh lá cây đậm */
            color: white;
            text-align: center;
            padding: 50px 0;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
        }

        header p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        /* Navigation Menu */
        nav {
            background-color: #2E7D32; /* Xanh đậm hơn cho menu */
            padding: 10px 0;
        }

        nav ul {
            padding: 0;
            margin: 0;
            list-style: none;
        }

        nav ul li {
            display: inline-block;
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            padding: 10px 20px;
            display: inline-block;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: #66BB6A; /* Màu xanh nhạt khi hover */
        }

        /* Section Styles */
        .section {
            margin-top: 40px;
            padding: 20px;
            border-radius: 8px;
            background-color: #A5D6A7; /* Xanh lá nhạt cho nội dung */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center; /* Căn lề giữa */
        }

        .section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #2E7D32; /* Xanh đậm cho tiêu đề */
        }

        .section p {
            font-size: 1.2em;
            color: #333;
        }

        .section img {
            width: 100%;
            max-width: 600px;
            margin-top: 20px;
            border-radius: 8px;
        }

        /* Footer Styles */
        footer {
            background-color: #388E3C; /* Xanh đậm cho chân trang */
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            .container {
                width: 95%;
            }

            nav ul li {
                display: block;
                margin-bottom: 10px;
            }

            .section img {
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Safe Route</h1> <!-- Đã thay đổi tiêu đề chính hiển thị trên web -->
            <p>Cập nhật thông tin thời tiết và các hiện tượng thiên tai gây ảnh hưởng đến giao thông</p>
        </div>
    </header>

    <!-- Navigation Menu -->
    <nav>
        <ul>
            <li><a href="#capnhat">Cập Nhật Thiên Tai</a></li>
            <li><a href="#bando">Bản Đồ Thời Gian Thực</a></li>
            <li><a href="#canhbao">Cảnh Báo Giao Thông</a></li>
            <li><a href="#tuvan">Tư Vấn Lộ Trình</a></li>
            <li><a href="#huongdan">Hướng Dẫn An Toàn</a></li>
        </ul>
    </nav>

    <!-- Cập Nhật Thiên Tai Section -->
    <section id="capnhat" class="section">
        <h2>Cập Nhật Thiên Tai</h2>
        <p>Cập nhật thông tin về các hiện tượng thiên tai như mưa bão, lũ lụt, sạt lở đất, động đất, sương mù, gây ảnh hưởng đến giao thông.</p>
        <a href="http://www.dmc.gov.vn/thong-tin-thien-tai-pt32.html?lang=vi-VN" target="_blank">
            <img src="https://bcp.cdnchinhphu.vn/Uploaded/nguyendieuhuong/2020_10_29/thientai.jpg" alt="Thiên tai ảnh hưởng đến giao thông">
        </a>
    </section>

    <!-- Bản Đồ Thời Gian Thực Section -->
    <section id="bando" class="section">
        <h2>Bản Đồ Thời Gian Thực</h2>
        <p>Hiển thị bản đồ chi tiết về các vùng bị ảnh hưởng, giúp người dùng biết được khu vực nào đang gặp vấn đề.</p>
        <!-- Link bản đồ lồng vào ảnh -->
        <a href="https://vrain.vn/20/overview?public_map=windy" target="_blank">
            <img src="https://media-cdn-v2.laodong.vn/storage/newsportal/2024/10/3/1402840/NGAP-4.jpg?w=660" alt="Bản đồ thiên tai">
        </a>
    </section>

    <!-- Cảnh Báo Giao Thông Section -->
    <section id="canhbao" class="section">
        <h2>Cảnh Báo Giao Thông</h2>
        <p>Thông báo về đường bị ngập, kẹt xe do thời tiết, hoặc các khu vực cần tránh để đảm bảo an toàn.</p>
        <a href="https://www.laodong.vn/giao-thong/duong-ngap-lut-gay-kho-khan-cho-nguoi-tham-gia-giao-thong-123456.ldo" target="_blank">Xem chi tiết</a>
    </section>

    <!-- Tư Vấn Lộ Trình Section -->
    <section id="tuvan" class="section">
        <h2>Tư Vấn Lộ Trình</h2>
        <p>Đề xuất các tuyến đường an toàn hơn khi khu vực chính đang bị ảnh hưởng bởi thiên tai.</p>
        <a href="https://vnexpress.net/tin-tuc/giao-thong/giai-phap-dieu-huong-an-toan-cho-nguoi-tham-gia-giao-thong-1234567.html" target="_blank">Xem chi tiết</a>
    </section>

    <!-- Hướng Dẫn An Toàn Section -->
    <section id="huongdan" class="section">
        <h2>Hướng Dẫn An Toàn</h2>
        <p>Cung cấp các biện pháp an toàn cho người tham gia giao thông trong điều kiện thời tiết xấu.</p>
        <ul>
            <li><a href="https://youtu.be/yn4JtjN6Z5I" target="_blank">Xem video hướng dẫn an toàn 1</a></li>
            <li><a href="https://www.youtube.com/watch?v=djkMmCwUKW0" target="_blank">Xem video hướng dẫn an toàn 2</a></li>
            <li><a href="https://www.dienmayxanh.com/kinh-nghiem-hay/nhung-luu-y-khi-di-chuyen-trong-mua-mua-de-an-toan-1351890" target="_blank">Bài viết về lưu ý khi di chuyển trong mưa</a></li>
        </ul>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Safe Route. Tất cả các quyền được bảo lưu.</p>
        </div>
    </footer>
</body>
</html>
