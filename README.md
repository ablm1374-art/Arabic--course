# Arabic--course<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>آموزش زبان عربی</title>
    <link href="https://fonts.googleapis.com/css2?family=Vazir&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Vazir', sans-serif;
            direction: rtl;
            background-color: #f9fafb;
            margin: 0;
            padding: 0;
        }
        .btn {
            padding: 10px 20px;
            border-radius: 8px;
            background-color: #1E40AF;
            color: white;
            text-align: center;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #2563eb;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-10px);
        }
    </style>
</head>
<body>

    <!-- هدر -->
    <header class="bg-blue-800 text-white p-4 flex justify-between items-center">
        <div class="text-2xl font-bold">لوگوی سایت</div>
        <nav>
            <ul class="flex space-x-6">
                <li><a href="#" class="hover:underline">خانه</a></li>
                <li><a href="#courses" class="hover:underline">دوره‌ها</a></li>
                <li><a href="#features" class="hover:underline">ویژگی‌ها</a></li>
                <li><a href="#sample" class="hover:underline">نمونه درس</a></li>
                <li><a href="#contact" class="hover:underline">تماس</a></li>
            </ul>
        </nav>
    </header>

    <!-- هیرو (Hero Section) -->
    <section class="bg-blue-900 text-white text-center py-20">
        <h1 class="text-4xl mb-4">آموزش زبان عربی برای همه (۱۰ سال به بالا)</h1>
        <div class="space-x-4">
            <a href="#" class="btn">شروع رایگان</a>
            <a href="#about" class="btn">درباره ما</a>
        </div>
    </section>

    <!-- بخش معرفی دوره‌ها -->
    <section id="courses" class="py-20 px-8 text-center">
        <h2 class="text-3xl font-bold mb-8">دوره‌های آموزشی</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="card bg-white">
                <h3 class="text-xl font-bold">دوره مقدماتی</h3>
                <p>آموزش اصول ابتدایی زبان عربی.</p>
            </div>
            <div class="card bg-white">
                <h3 class="text-xl font-bold">دوره متوسط</h3>
                <p>تقویت مهارت‌های زبانی با تمرینات کاربردی.</p>
            </div>
            <div class="card bg-white">
                <h3 class="text-xl font-bold">دوره پیشرفته</h3>
                <p>ارتقاء تسلط بر زبان عربی به سطح پیشرفته.</p>
            </div>
        </div>
    </section>

    <!-- بخش ویژگی‌ها -->
    <section id="features" class="bg-gray-100 py-20 px-8 text-center">
        <h2 class="text-3xl font-bold mb-8">ویژگی‌های سایت</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
            <div>
                <div class="text-blue-800 mb-4">🎥</div>
                <h3 class="font-bold mb-2">ویدیوهای آموزشی</h3>
                <p>دوره‌های آموزشی با محتوای ویدیویی.</p>
            </div>
            <div>
                <div class="text-green-500 mb-4">📝</div>
                <h3 class="font-bold mb-2">تمرین‌های تعاملی</h3>
                <p>تمرینات با امکان تعامل و بازخورد.</p>
            </div>
            <div>
                <div class="text-orange-500 mb-4">🎮</div>
                <h3 class="font-bold mb-2">گیمیفیکیشن</h3>
                <p>یادگیری به سبک بازی برای افزایش انگیزه.</p>
            </div>
            <div>
                <div class="text-blue-500 mb-4">📊</div>
                <h3 class="font-bold mb-2">پنل پیشرفت</h3>
                <p>نمایش پیشرفت شما در طول دوره.</p>
            </div>
        </div>
    </section>

    <!-- بخش نمونه درس -->
    <section id="sample" class="py-20 px-8 text-center">
        <h2 class="text-3xl font-bold mb-8">نمونه درس</h2>
        <div class="max-w-sm mx-auto bg-white p-6 rounded-lg shadow-lg">
            <div class="flashcard text-center" onclick="flipFlashcard()">
                <div class="front bg-blue-900 text-white p-4 rounded-lg">
                    <h3 class="text-xl">کتاب</h3>
                </div>
                <div class="back bg-orange-500 text-white p-4 rounded-lg hidden">
                    <h3 class="text-xl">کتاب - اسم معرفه</h3>
                    <p>تلفظ: "کتاب" به معنای کتاب در زبان فارسی است.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- نوار پیشرفت -->
    <section id="progress" class="py-20 px-8 text-center">
        <h2 class="text-3xl font-bold mb-8">نوار پیشرفت شما</h2>
        <div class="w-full bg-gray-200 rounded-full h-2.5 mb-4">
            <div class="bg-green-500 h-2.5 rounded-full" style="width: 60%;"></div>
        </div>
        <p>60% از دوره‌ها را تمام کرده‌اید.</p>
    </section>

    <!-- فوتر -->
    <footer id="contact" class="bg-blue-800 text-white py-8 text-center">
        <p>تماس با ما: info@arabiccourse.com</p>
        <div class="space-x-4">
            <a href="#" class="hover:underline">Instagram</a>
            <a href="#" class="hover:underline">Telegram</a>
            <a href="#" class="hover:underline">LinkedIn</a>
        </div>
    </footer>

    <script>
        function flipFlashcard() {
            const flashcard = document.querySelector('.flashcard');
            flashcard.classList.toggle('flipped');
            const front = flashcard.querySelector('.front');
            const back = flashcard.querySelector('.back');
            if (flashcard.classList.contains('flipped')) {
                front.classList.add('hidden');
                back.classList.remove('hidden');
            } else {
                front.classList.remove('hidden');
                back.classList.add('hidden');
            }
        }
    </script>
</body>
</html>
