<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Python Hub — Твой старт в IT с полным комфортом</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-blue-600 tracking-tight">
                <i class="fa-brands fa-python"></i> PYTHON<span class="text-gray-900">HUB</span>
            </div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#about" class="hover:text-blue-600 transition">О нас</a>
                <a href="#characters" class="hover:text-blue-600 transition">Для кого</a>
                <a href="#benefits" class="hover:text-blue-600 transition">Выгоды</a>
                <a href="#faq" class="hover:text-blue-600 transition">FAQ</a>
            </div>
            <button class="bg-blue-600 text-white px-6 py-2 rounded-full hover:bg-blue-700 transition font-semibold">
                Войти
            </button>
        </div>
    </nav>

    <header class="relative bg-gray-900 text-white py-24 overflow-hidden">
        <div class="absolute inset-0 opacity-20 bg-[url('https://images.unsplash.com/photo-1515879218367-8466d910aaa4?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80')] bg-cover bg-center"></div>
        <div class="container mx-auto px-6 relative z-10 text-center">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-6 leading-tight">
                Освой Python в режиме <br><span class="text-blue-400">Full-Stack комфорта</span>
            </h1>
            <p class="text-xl md:text-2xl mb-10 text-gray-300 max-w-3xl mx-auto">
                Обучение с Senior-менторами в хабе, работающем до 00:00. Пока вы кодите, мы присмотрим за вашим ребенком в игровой зоне.
            </p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#contact" class="bg-blue-600 text-white px-10 py-4 rounded-lg text-lg font-bold hover:bg-blue-700 shadow-lg transition">Попробовать бесплатно</a>
                <a href="#benefits" class="bg-white text-gray-900 px-10 py-4 rounded-lg text-lg font-bold hover:bg-gray-100 transition">Узнать больше</a>
            </div>
        </div>
    </header>

    <section id="characters" class="py-20 container mx-auto px-6">
        <h2 class="text-3xl font-bold text-center mb-16">Кому мы помогаем расти?</h2>
        <div class="grid md:grid-cols-2 gap-12">
            <div class="bg-white p-8 rounded-2xl shadow-xl border-t-4 border-blue-600">
                <div class="text-blue-600 text-4xl mb-4"><i class="fa-solid fa-briefcase"></i></div>
                <h3 class="text-2xl font-bold mb-4">Взрослые Свитчеры</h3>
                <p class="text-gray-600 mb-6">Хотите сменить профессию или развить хард-скиллы? Мы создали среду, где быт не отвлекает от кода. Идеально для тех, кто ценит время и результат.</p>
                <ul class="space-y-3">
                    <li><i class="fa-solid fa-check text-green-500 mr-2"></i> Детская комната с няней</li>
                    <li><i class="fa-solid fa-check text-green-500 mr-2"></i> Обучение с нуля до Junior</li>
                    <li><i class="fa-solid fa-check text-green-500 mr-2"></i> Ужин в кафе после работы</li>
                </ul>
            </div>
            <div class="bg-white p-8 rounded-2xl shadow-xl border-t-4 border-orange-500">
                <div class="text-orange-500 text-4xl mb-4"><i class="fa-solid fa-graduation-cap"></i></div>
                <h3 class="text-2xl font-bold mb-4">Амбициозные Студенты</h3>
                <p class="text-gray-600 mb-6">Нужно закрыть сессию, написать диплом или собрать портфолио для первой работы? У нас есть практика, которой не учат в вузе.</p>
                <ul class="space-y-3">
                    <li><i class="fa-solid fa-check text-green-500 mr-2"></i> Скидка 30% по студенческому</li>
                    <li><i class="fa-solid fa-check text-green-500 mr-2"></i> Помощь с курсовыми и дипломами</li>
                    <li><i class="fa-solid fa-check text-green-500 mr-2"></i> Коворкинг открыт до 00:00</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="benefits" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-16">Почему выбирают Python Hub?</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center p-6">
                    <div class="w-16 h-16 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl">
                        <i class="fa-solid fa-clock"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3">Гибкий график</h4>
                    <p class="text-gray-600">Школа и кафе открыты до полуночи. Учитесь онлайн или офлайн, когда вам удобно.</p>
                </div>
                <div class="text-center p-6">
                    <div class="w-16 h-16 bg-green-100 text-green-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl">
                        <i class="fa-solid fa-child"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3">Детская игровая</h4>
                    <p class="text-gray-600">Безопасное пространство с нянями. Ребенок играет — вы строите карьеру в IT.</p>
                </div>
                <div class="text-center p-6">
                    <div class="w-16 h-16 bg-yellow-100 text-yellow-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl">
                        <i class="fa-solid fa-utensils"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3">Собственное кафе</h4>
                    <p class="text-gray-600">Завтраки и ужины прямо в хабе. Не тратьте время на готовку — больше времени на код.</p>
                </div>
                <div class="text-center p-6">
                    <div class="w-16 h-16 bg-purple-100 text-purple-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl">
                        <i class="fa-solid fa-code"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3">Senior-менторство</h4>
                    <p class="text-gray-600">Разбор вашего кода наставниками из топовых компаний. Только реальные проекты.</p>
                </div>
                <div class="text-center p-6">
                    <div class="w-16 h-16 bg-red-100 text-red-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl">
                        <i class="fa-solid fa-percent"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3">Рассрочка 0%</h4>
                    <p class="text-gray-600">Учитесь сейчас — платите потом. Внутренняя система рассрочки без участия банков.</p>
                </div>
                <div class="text-center p-6">
                    <div class="w-16 h-16 bg-teal-100 text-teal-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl">
                        <i class="fa-solid fa-rocket"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3">Быстрый старт</h4>
                    <p class="text-gray-600">Напишете первый работающий скрипт на Python уже на первом занятии.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="faq" class="py-20 container mx-auto px-6 max-w-4xl">
        <h2 class="text-3xl font-bold text-center mb-16">Ответы на ваши сомнения</h2>
        <div class="space-y-6">
            <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-blue-600">
                <h5 class="font-bold text-lg mb-2">А если я задержусь на работе и пропущу?</h5>
                <p class="text-gray-600">Все уроки дублируются в онлайн-формате, а наш хаб открыт до 00:00 — вы всегда сможете просмотреть запись и задать вопрос ментору.</p>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-blue-600">
                <h5 class="font-bold text-lg mb-2">Я гуманитарий, это не слишком сложно?</h5>
                <p class="text-gray-600">Мы обучаем «от простого к сложному». Личный ментор разберет вашу ошибку за 30 минут и не даст бросить обучение.</p>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-blue-600">
                <h5 class="font-bold text-lg mb-2">Что даст ваш сертификат на рынке?</h5>
                <p class="text-gray-600">Это подтверждение реального опыта: к концу курса в вашем портфолио будет 4+ проекта на GitHub, которые ценят HR.</p>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-6">Готовы изменить жизнь?</h2>
            <p class="mb-10 text-gray-400">Оставьте заявку на пробный день в Python Hub</p>
            <form class="max-w-md mx-auto flex flex-col gap-4">
                <input type="text" placeholder="Ваше имя" class="px-6 py-3 rounded-lg bg-gray-800 border border-gray-700 focus:outline-none focus:border-blue-500">
                <input type="tel" placeholder="Номер телефона" class="px-6 py-3 rounded-lg bg-gray-800 border border-gray-700 focus:outline-none focus:border-blue-500">
                <button class="bg-blue-600 py-3 rounded-lg font-bold hover:bg-blue-700 transition">Записаться на тест-драйв</button>
            </form>
            <div class="mt-12 text-gray-500 text-sm">
                &copy; 2026 Python Hub. Все права защищены.
            </div>
        </div>
    </footer>

</body>
</html>
