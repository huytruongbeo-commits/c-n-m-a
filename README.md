<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang thông tin cá nhân</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        .container {
            border: 1px solid #000;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        .intro-section {
            border: 1px solid #ccc;
            padding: 10px;
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .avatar {
            width: 100px;
            height: auto;
            margin-right: 20px;
        }
        table {
            border-collapse: collapse;
            width: 300px;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 5px;
            text-align: left;
        }
        h2, h3 {
            margin-top: 0;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>NGUYỄN VĂN A</h1>
    <h3>Trang thông tin cá nhân</h3>

    <div class="intro-section">
        <img src="https://via.placeholder.com/100" alt="Avatar" class="avatar">
        <div>
            <strong>Giới thiệu bản thân</strong>
            <p>
                Xin chào! Tôi là <strong>Nguyễn Văn A</strong>, sinh viên ngành <strong>Công nghệ thông tin</strong>. 
                Tôi yêu thích lập trình và thiết kế web. Mục tiêu của tôi là trở thành một <u>lập trình viên chuyên nghiệp</u>.
            </p>
            <p>Tôi đang học tại <strong>Đại học Trà Vinh</strong>. Tôi luôn cố gắng học tập và phát triển kỹ năng mỗi ngày.</p>
        </div>
    </div>

    <h4>Thông tin chi tiết</h4>
    <table>
        <tr>
            <th>Thông tin</th>
            <th>Nội dung</th>
        </tr>
        <tr>
            <td>Họ và tên</td>
            <td>Nguyễn Văn A</td>
        </tr>
        <tr>
            <td>Tuổi</td>
            <td>20</td>
        </tr>
        <tr>
            <td>Lớp</td>
            <td>DH21IT01</td>
        </tr>
        <tr>
            <td>Trường</td>
            <td>Đại học Trà Vinh</td>
        </tr>
    </table>

    <h4>Sở thích</h4>
    <ul>
        <li>Nghe nhạc</li>
        <li>Xem phim</li>
        <li>Chơi thể thao</li>
    </ul>

    <h4>Kỹ năng và mục tiêu</h4>
    <ol>
        <li>Biết HTML cơ bản</li>
        <li>Đang học CSS và JavaScript</li>
        <li>Muốn làm website cá nhân</li>
    </ol>

    <h4>Liên hệ</h4>
    <p>Facebook: <a href="#">Trang Facebook của tôi</a></p>
    <p>Email: <a href="mailto:example@gmail.com">example@gmail.com</a></p>
</div>

</body>
</html>
