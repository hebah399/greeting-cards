<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بطاقات التهنئة</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>اختر بطاقة واكتب اسمك</h1>

        <div class="card-container">
            <img src="test.jpg" class="card" onclick="selectCard('test.jpg')">
            <img src="cards/card2.jpg" class="card" onclick="selectCard('cards/card2.jpg')">
        </div>

        <input type="text" id="username" placeholder="اكتب اسمك هنا" class="input-field">
        <button onclick="generateCard()" class="generate-button">إنشاء البطاقة</button>

        <!-- معاينة البطاقة -->
        <div id="preview" class="preview-container" style="display:none;">
            <div class="card-preview">
                <img id="previewImage" src="" alt="البطاقة" class="preview-image">
                <p id="previewText" class="preview-text"></p>
            </div>
            <button onclick="downloadCard()" class="download-button">تحميل البطاقة</button>
        </div>
    </div>

    <script>
        let selectedCard = "";

        function selectCard(imagePath) {
            selectedCard = imagePath;
        }

        function generateCard() {
            if (!selectedCard) {
                alert("يرجى اختيار بطاقة أولاً!");
                return;
            }

            let username = document.getElementById("username").value.trim();
            if (username === "") {
                alert("يرجى إدخال اسمك!");
                return;
            }

            // عرض البطاقة مع الاسم داخل الصورة
            document.getElementById("preview").style.display = "block";
            document.getElementById("previewImage").src = selectedCard;
            document.getElementById("previewText").textContent = username;
        }

        function downloadCard() {
            let username = document.getElementById("username").value.trim();
            if (!username || !selectedCard) return;

            // إنشاء رابط لتحميل الصورة
            window.location.href = `generate.php?image=${selectedCard}&text=${encodeURIComponent(username)}`;
        }
    </script>
</body>
</html>


<style>/* تنسيق العام للصفحة */
body {
    font-family: 'Arial', sans-serif;
    background: linear-gradient(to right, #ff7e5f, #feb47b);
    color: #fff;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    text-align: center;
    padding: 20px;
    background: rgba(0, 0, 0, 0.6);
    border-radius: 10px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

h1 {
    font-size: 36px;
    color: #fff;
    margin-bottom: 30px;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
}

/* تنسيق للبطاقات */
.card-container {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin-bottom: 30px;
}

.card {
    width: 250px;
    height: 350px;
    border-radius: 10px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    cursor: pointer;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
}

/* تنسيق للحقل النصي */
.input-field {
    width: 80%;
    padding: 12px;
    font-size: 18px;
    border: 2px solid #fff;
    border-radius: 5px;
    margin-bottom: 20px;
    background: rgba(255, 255, 255, 0.2);
    color: #fff;
}

.input-field:focus {
    outline: none;
    border-color: #ff7e5f;
}

/* تنسيق للأزرار */
.generate-button {
    background-color: #ff7e5f;
    color: #fff;
    font-size: 20px;
    padding: 15px 25px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.generate-button:hover {
    background-color: #feb47b;
}

/* تنسيق المعاينة */
.preview-container {
    margin-top: 20px;
    text-align: center;
}

.card-preview {
    position: relative;
}

.preview-image {
    width: 50%;
    height: auto;
    border-radius: 10px;
}

.preview-text {
    position: absolute;
    bottom: 50px;
    left: 50%;
    transform: translateX(-50%);
    font-size: 24px;
    color: #fff;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
}

.download-button {
    background-color: #ff7e5f;
    color: #fff;
    font-size: 18px;
    padding: 12px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.download-button:hover {
    background-color: #feb47b;
}

</style>