ص<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تم سحب بياناتك! 😱</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: orange ;
            text-align: center;
            padding: 50px;
        }
        h1 {
            color: #ff0000;
            font-size: 3em;
        }
        p {
            font-size: 1.5em;
            color: #333;
        }
        .loading-bar {
            width: 80%;
            height: 30px;
            background-color: #ddd;
            margin: 50px auto;
            border-radius: 15px;
            overflow: hidden;
            position: relative;
        }
        .loading-progress {
            width: 0%;
            height: 100%;
            background-color: #ff0000;
            position: absolute;
            top: 0;
            left: 0;
            animation: load 10s linear forwards;
        }
        @keyframes load {
            0% { width: 0%; }
            100% { width: 100%; }
        }
        .hidden {
            display: none;
        }
        .funny-message {
            font-size: 2em;
            color: #008000;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>⚠️ تنبيه! ⚠️</h1>
    <p>لقد تم اكتشاف محاولة سحب بياناتك الشخصية!</p>
    <div class="loading-bar">
        <div class="loading-progress"></div>
    
    </div>
    <p>جاري تحميل تفاصيل العملية...</p>
    <div id="funnyMessage" class="hidden">
        <p class="funny-message">تم سحب بعض بياناتك من قبل جهاز galaxy  note8   
        
        
        1562   .    صورة
        244 .       فديو 
        112 .    جهة اتصال
        
        </p>
        
    </div>

    <script>
        setTimeout(function() {
            document.getElementById('funnyMessage').classList.remove('hidden');
        }, 9000); // 5 ثواني
    </script>
</body>
</html>
