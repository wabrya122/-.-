<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع رصد الدرجات وترتيب الجدول الدراسي</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f9f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            display: flex;
            justify-content: space-between;
            padding: 20px;
        }

        .section {
            width: 48%;
            background-color: #e6f9e6;
            padding: 20px;
            border-radius: 8px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 8px;
            text-align: center;
        }

        h2 {
            color: #47a447;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>موقع رصد الدرجات وترتيب الجدول الدراسي</h1>
</header>

<div class="container">
    <!-- جدول رصد الدرجات -->
    <div class="section">
        <h2>رصد الدرجات</h2>
        <table id="gradesTable">
            <tr>
                <th>اسم الطالب</th>
                <th>الدرجة</th>
            </tr>
            <tr>
                <td>أحمد</td>
                <td>95</td>
            </tr>
            <tr>
                <td>مريم</td>
                <td>89</td>
            </tr>
            <tr>
                <td>سارة</td>
                <td>78</td>
            </tr>
        </table>
    </div>

    <!-- جدول ترتيب الجدول الدراسي -->
    <div class="section">
        <h2>الجدول الدراسي واليومي</h2>
        <table id="scheduleTable">
            <tr>
                <th>اليوم</th>
                <th>الوقت</th>
                <th>المادة</th>
            </tr>
            <tr>
                <td>الأحد</td>
                <td>8:00 AM</td>
                <td>رياضيات</td>
            </tr>
            <tr>
                <td>الإثنين</td>
                <td>10:00 AM</td>
                <td>علوم</td>
            </tr>
            <tr>
                <td>الثلاثاء</td>
                <td>1:00 PM</td>
                <td>لغة عربية</td>
            </tr>
        </table>
    </div>
</div>

<footer>
    <p>&copy; 2025 موقع رصد الدرجات. جميع الحقوق محفوظة.</p>
</footer>

</body>
</html>
