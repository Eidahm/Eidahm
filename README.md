- <!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>حاسبة تكلفة التصميم</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container"> 
        <h1>حاسبة تكلفة التصميم</h1>
        <label for="projectType">نوع المشروع:</label>
        <select id="projectType">
            <option value="residential">سكني</option>
            <option value="commercial">تجاري</option>
            <option value="facade">واجهة سكنية</option>
        </select>

        <div id="dimensions">
            <label for="length">الطول (م):</label>
            <input type="number" id="length" placeholder="أدخل الطول" />
            <label for="width">العرض (م):</label>
            <input type="number" id="width" placeholder="أدخل العرض" />
        </div>

        <button onclick="calculateCost()">احسب التكلفة</button>
        <p id="result"></p>
    </div>

    <script src="script.js"></script>
</body>
</html>
