<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Mẫu</title>
    <style>
	h1{
			display: none;
			}
        /* Cài đặt chung */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #FFE4B5, white);
        }

        /* Pano đầu trang */
        .header {
            background-color: #FF7F50;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }

        /* Nội dung giữa trang */
        .content {
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 20px;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .content img {
            max-width: 300px;
            height: auto;
            border-radius: 10px;
            margin-right: 20px;
        }

        .content .text {
            font-family: 'Lora', serif;
            text-align: justify;
            font-size: 16px;
            line-height: 1.6;
        }

        /* Bảng cuối trang */
        .footer-table {
            width: 100%;
            margin: 20px auto;
            border-collapse: collapse;
            text-align: center;
        }

        .footer-table th, .footer-table td {
            border: 1px solid #ddd;
            padding: 10px;
        }

        .footer-table th {
            background-color: #FF7F50;
            color: white;
        }
    </style>
</head>
<body>

    <!-- Pano đầu trang -->
    <div class="header">
        Pano Đầu Trang
    </div>

    <!-- Nội dung giữa trang -->
    <div class="content">
        <img src="462644434_494027767023134_9100106116697837757_n.jpg" alt="Placeholder Image">
        <div class="text">
            Đây là một đoạn văn mẫu sử dụng phông chữ Lora, căn đều hai bên. Bạn có thể thay thế đoạn văn này bằng nội dung tùy ý. Văn bản này giúp trình bày một cách chuyên nghiệp và dễ đọc.
        </div>
    </div>

    <!-- Bảng cuối trang -->
    <table class="footer-table">
         <tr>
					<th>Ngày sinh</th>
                    <th>Chiều cao</th>
                    <th> Cân nặng</th>
                    <th>Số điện thoại</th>
                    <th>Email</th>
                    <th>Cung hoàng đạo</th>
                    <th>Nickname</th>
                    <th>Liên hệ facebook</th>
                </tr>
            </thead>
            <tbody>
                <!-- 2 hàng -->
                <tr>
					<td>24/07/2007 </td>
                    <td>1,73m </td>
                    <td>60 kg</td>
                    <td>0939764810</td>
                    <td>trongduyhotro2007@gmail.com</td>
                    <td>Sư Tử</td>
                    <td>YuD</td>
                    <td><a href="https://www.facebook.com/duy.trong.3975?locale=vi_VN"> Trần Trọng Duy </a></td>
                </tr>
    </table>

</body>
</html>

