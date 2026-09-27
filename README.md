<!DOCTYPE html>
<html lang="ckb" dir="rtl" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ڕێنمایی دەروونی و پەروەردەیی | دەروو جبار قادر</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0fdf4',
                            100: '#dcfce7',
                            500: '#10b981',
                            600: '#059669',
                            700: '#047857',
                        },
                        calm: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            500: '#0ea5e9',
                            600: '#0284c7',
                            700: '#0369a1',
                        }
                    },
                    fontFamily: {
                        sans: ['system-ui', '-apple-system', 'BlinkMacSystemFont', '"Segoe UI"', 'Roboto', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f5f9;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
    </style>
</head>
<body class="bg-slate-50 dark:bg-slate-900 text-slate-800 dark:text-slate-100 font-sans transition-colors duration-300">

    <header class="sticky top-0 z-50 bg-white/90 dark:bg-slate-900/90 backdrop-blur-md border-b border-slate-200 dark:border-slate-800 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <div class="flex items-center gap-3">
                    <div class="w-12 h-12 rounded-2xl bg-gradient-to-tr from-brand-600 to-calm-500 flex items-center justify-center text-white shadow-md shadow-brand-500/20">
                        <i class="fa-solid fa-hands-holding-child text-2xl"></i>
                    </div>
                    <div>
                        <span class="text-xl font-bold bg-gradient-to-r from-brand-700 to-calm-600 dark:from-brand-400 dark:to-calm-400 bg-clip-text text-transparent">ڕێنمایی دەروونی و پەروەردەیی</span>
                        <p class="text-xs text-slate-500 dark:text-slate-400">پاڵپشتی و گەشەپێدانی فیکری و دەروونی</p>
                    </div>
                </div>

                <nav class="hidden md:flex items-center gap-8">
                    <a href="#home" class="font-medium text-brand-600 dark:text-brand-400 hover:text-brand-700 transition">سەرەتا</a>
                    <a href="#special-education" class="font-medium text-slate-600 dark:text-slate-300 hover:text-brand-600 transition">پەروەردەی تایبەت</a>
                    <a href="#mental-health" class="font-medium text-slate-600 dark:text-slate-300 hover:text-brand-600 transition">تەندروستی دەروونی</a>
                    <a href="#books" class="font-medium text-slate-600 dark:text-slate-300 hover:text-brand-600 transition">کتێبەکان</a>
                    <a href="#resources" class="font-medium text-slate-600 dark:text-slate-300 hover:text-brand-600 transition">سەرچاوەکان</a>
                    <a href="#consultation" class="font-medium text-slate-600 dark:text-slate-300 hover:text-brand-600 transition">راوێژکاری</a>
                    <a href="#about" class="font-medium text-slate-600 dark:text-slate-300 hover:text-brand-600 transition">دەربارەی ئێمە</a>
                </nav>

                <div class="flex items-center gap-4">
                    <button id="theme-toggle" class="p-2.5 rounded-xl bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300 hover:bg-slate-200 dark:hover:bg-slate-700 transition" aria-label="گۆڕینی دۆخی ڕووناک/تاریک">
                        <i class="fa-solid fa-moon dark:hidden text-lg"></i>
                        <i class="fa-solid fa-sun hidden dark:block text-lg text-amber-400"></i>
                    </button>
                    <a href="#consultation" class="hidden sm:inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium shadow-lg shadow-brand-600/20 transition transform active:scale-95">
                        داوای ڕاوێژ بکە
                    </a>
                    <button id="mobile-menu-btn" class="md:hidden p-2.5 rounded-xl bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300">
                        <i class="fa-solid fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <div id="mobile-menu" class="hidden md:hidden bg-white dark:bg-slate-900 border-b border-slate-200 dark:border-slate-800 px-4 pt-2 pb-6 space-y-3">
            <a href="#home" class="block px-3 py-2 rounded-lg font-medium text-brand-600 bg-brand-50 dark:bg-slate-800">سەرەتا</a>
            <a href="#special-education" class="block px-3 py-2 rounded-lg font-medium text-slate-600 dark:text-slate-300 hover:bg-slate-100 dark:hover:bg-slate-800">پەروەردەی تایبەت</a>
            <a href="#mental-health" class="block px-3 py-2 rounded-lg font-medium text-slate-600 dark:text-slate-300 hover:bg-slate-100 dark:hover:bg-slate-800">تەندروستی دەروونی</a>
            <a href="#books" class="block px-3 py-2 rounded-lg font-medium text-slate-600 dark:text-slate-300 hover:bg-slate-100 dark:hover:bg-slate-800">کتێبەکان</a>
            <a href="#resources" class="block px-3 py-2 rounded-lg font-medium text-slate-600 dark:text-slate-300 hover:bg-slate-100 dark:hover:bg-slate-800">سەرچاوەکان</a>
            <a href="#consultation" class="block px-3 py-2 rounded-lg font-medium text-slate-600 dark:text-slate-300 hover:bg-slate-100 dark:hover:bg-slate-800">راوێژکاری</a>
            <a href="#about" class="block px-3 py-2 rounded-lg font-medium text-slate-600 dark:text-slate-300 hover:bg-slate-100 dark:hover:bg-slate-800">دەربارەی ئێمە</a>
        </div>
    </header>

    <section id="home" class="relative overflow-hidden pt-16 pb-24 lg:pt-24 lg:pb-32 bg-gradient-to-b from-brand-50/50 via-calm-50/30 to-transparent dark:from-slate-900 dark:via-slate-900 dark:to-slate-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-7 space-y-6 text-center lg:text-right">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-brand-100 dark:bg-brand-900/40 text-brand-700 dark:text-brand-300 text-sm font-semibold">
                        <i class="fa-solid fa-seedling text-brand-600 dark:text-brand-400"></i>
                        پەروەردەی سەردەمی و پاراستنی ئارامی دەروونی
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight text-slate-900 dark:text-white leading-[1.2]">
                        پەروەردەی تایبەت و تێگەیشتن لە <span class="bg-gradient-to-r from-brand-600 to-calm-500 bg-clip-text text-transparent">پێویستییەکان</span>
                    </h1>
                    <p class="text-lg text-slate-600 dark:text-slate-300 max-w-2xl mx-auto lg:mx-0 leading-relaxed">
                        ئەم پلاتفۆرمە لەلایەن <span class="font-bold text-brand-600 dark:text-brand-400">دەروو جبار قادر</span> (خوێندکاری پەروەردەی تایبەت لە زانکۆی چەرموو) بەڕێوەدەچێت، بۆ پێشکەشکردنی ڕێنمایی زانستی و هۆشیاری دەروونی.
                    </p>
                    <div class="flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-4">
                        <a href="#consultation" class="px-7 py-3.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium shadow-lg shadow-brand-600/25 transition transform hover:-translate-y-0.5 flex items-center gap-2">
                            <span>دەستپێکردن و ڕاوێژ</span>
                            <i class="fa-solid fa-arrow-left text-sm"></i>
                        </a>
                        <a href="#special-education" class="px-7 py-3.5 rounded-xl bg-white dark:bg-slate-800 hover:bg-slate-100 dark:hover:bg-slate-700 text-slate-700 dark:text-slate-200 border border-slate-200 dark:border-slate-700 font-medium shadow-sm transition">
                            بینینی بابەتەکان
                        </a>
                    </div>
                </div>

                <div class="lg:col-span-5 relative">
                    <div class="relative mx-auto max-w-md lg:max-w-none">
                        <div class="absolute -top-4 -right-4 w-72 h-72 bg-brand-200/50 dark:bg-brand-900/20 rounded-full blur-3xl -z-10"></div>
                        <div class="absolute -bottom-4 -left-4 w-72 h-72 bg-calm-200/50 dark:bg-calm-900/20 rounded-full blur-3xl -z-10"></div>
                        
                        <div class="bg-white dark:bg-slate-800 rounded-3xl p-6 shadow-xl border border-slate-100 dark:border-slate-700 space-y-6">
                            <div class="flex items-center gap-4 p-4 rounded-2xl bg-brand-50 dark:bg-slate-700/50">
                                <div class="w-12 h-12 rounded-xl bg-brand-600 text-white flex items-center justify-center text-xl flex-shrink-0">
                                    <i class="fa-solid fa-brain"></i>
                                </div>
                                <div>
                                    <h3 class="font-bold text-slate-900 dark:text-white">تەندروستی دەروونی بنەمایە</h3>
                                    <p class="text-xs text-slate-500 dark:text-slate-400">کۆنتڕۆڵکردنی دڵەڕاوکێ و فشاری دەروونی.</p>
                                </div>
                            </div>
                            <div class="flex items-center gap-4 p-4 rounded-2xl bg-calm-50 dark:bg-slate-700/50">
                                <div class="w-12 h-12 rounded-xl bg-calm-600 text-white flex items-center justify-center text-xl flex-shrink-0">
                                    <i class="fa-solid fa-puzzle-piece"></i>
                                </div>
                                <div>
                                    <h3 class="font-bold text-slate-900 dark:text-white">پەروەردەی تایبەت و ئالنگارییەکان</h3>
                                    <p class="text-xs text-slate-500 dark:text-slate-400">تێگەیشتن لە ئاستەنگە فێرکارییەکان.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="special-education" class="py-20 bg-white dark:bg-slate-900/50 border-t border-slate-200 dark:border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full bg-calm-100 dark:bg-calm-900/40 text-calm-700 dark:text-calm-300 text-sm font-semibold">بەشی تایبەت</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 dark:text-white">پەروەردەی تایبەت، ئالنگارییەکان و زیانەکان</h2>
                <p class="text-slate-600 dark:text-slate-300">تێگەیشتن لەو ئاستەنگ و بەربەستانەی کە کەسانی خاوەن پێویستی تایبەت ڕووبەڕوویان دەبنەوە.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-slate-50 dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between hover:shadow-lg transition group">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-brand-100 dark:bg-brand-900/50 text-brand-600 dark:text-brand-400 flex items-center justify-center text-2xl group-hover:bg-brand-600 group-hover:text-white transition">
                            <i class="fa-solid fa-book-open-reader"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 dark:text-white">کێشەکانی فێربوون</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 leading-relaxed">کاریگەری کێشەکانی خوێندنەوە و نووسین لەسەر متمانەبەخۆبوونی منداڵ.</p>
                    </div>
                    <button onclick="openArticleModal('کێشەکانی فێربوون و ئالنگارییەکانی', 'کێشەکانی فێربوون جۆرێکە لە جیاوازی لە شێوازی کارکردنی مێشکدا. نەناسینەوەی دەبێتە هۆی دروستبوونی دڵەڕاوکێ و هەستی کەمتربوون لە قوتابیدا.')" class="mt-6 inline-flex items-center gap-2 text-brand-600 dark:text-brand-400 font-semibold text-sm hover:underline">
                        <span>خوێندنەوەی زیاتر</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-slate-50 dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between hover:shadow-lg transition group">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-calm-100 dark:bg-calm-900/50 text-calm-600 dark:text-calm-400 flex items-center justify-center text-2xl group-hover:bg-calm-600 group-hover:text-white transition">
                            <i class="fa-solid fa-puzzle-piece"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 dark:text-white">ئاوتیزم و کۆمەڵگە</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 leading-relaxed">هەستیاری زێدەڕۆ و سەختییەکانی تێکەڵاوبوونی کۆمەڵایەتی منداڵانی ئاوتیزم.</p>
                    </div>
                    <button onclick="openArticleModal('ئالنگارییەکانی ئاوتیزم و کۆمەڵگە', 'منداڵانی تووشبوو بە ئاوتیزم بەدەست هەستیاری توند بە دەنگ و ڕووناکی دەناڵێنن. نەزانی دەوروبەر سەبارەت بەم دۆخە دەبێتە هۆی فشارێکی گەورە.')" class="mt-6 inline-flex items-center gap-2 text-calm-600 dark:text-calm-400 font-semibold text-sm hover:underline">
                        <span>خوێندنەوەی زیاتر</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-slate-50 dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between hover:shadow-lg transition group">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-amber-100 dark:bg-amber-900/50 text-amber-600 dark:text-amber-400 flex items-center justify-center text-2xl group-hover:bg-amber-600 group-hover:text-white transition">
                            <i class="fa-solid fa-bolt"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 dark:text-white">فشاری دەروونی و ADHD</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 leading-relaxed">ناتوانایی لە ڕاگرتنی سەرنج و چالاکی زیادە کە دەبێتە هۆی سەختی لە خوێندن.</p>
                    </div>
                    <button onclick="openArticleModal('فشاری دەروونی و ADHD', 'منداڵانی خاوەن نیشانەی ADHD بەهۆی جووڵەی زیادەوە ڕووبەڕووی سزای نادروست دەبنەوە لە پۆلدا، کە زیانی دەروونی هەیە.')" class="mt-6 inline-flex items-center gap-2 text-amber-600 dark:text-amber-400 font-semibold text-sm hover:underline">
                        <span>خوێندنەوەی زیاتر</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-slate-50 dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between hover:shadow-lg transition group">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-emerald-100 dark:bg-emerald-900/50 text-emerald-600 dark:text-emerald-400 flex items-center justify-center text-2xl group-hover:bg-emerald-600 group-hover:text-white transition">
                            <i class="fa-solid fa-people-group"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 dark:text-white">بەربەست و جیاکاری</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 leading-relaxed">ڕووبەڕووبوونەوەی جیاکاری و نەبوونی ژینگەی گونجاو لە شوێنە گشتییەکاندا.</p>
                    </div>
                    <button onclick="openArticleModal('بەربەستە کۆمەڵایەتییەکان و جیاکاری', 'نەبوونی ژینگەی تەلارسازی گونجاو و جیاکاری دەروونی لە کۆمەڵگەدا زیانێکی گەورەیە. هۆشیارکردنەوەی کۆمەڵگە چارەسەرە.')" class="mt-6 inline-flex items-center gap-2 text-emerald-600 dark:text-emerald-400 font-semibold text-sm hover:underline">
                        <span>خوێندنەوەی زیاتر</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section id="mental-health" class="py-20 bg-slate-100/50 dark:bg-slate-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full bg-brand-100 dark:bg-brand-900/40 text-brand-700 dark:text-brand-300 text-sm font-semibold">تەندروستی دەروونی</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 dark:text-white">ئارامی دەروونی و چاودێری خودی</h2>
                <p class="text-slate-600 dark:text-slate-300">ڕێنمایی دەروونی برای ئەوەی ژیانێکی هاوسەنگ، ئارام و بەرهەمدار بەڕێوەببەیت.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white dark:bg-slate-800 rounded-3xl p-8 border border-slate-200 dark:border-slate-700 space-y-4 shadow-sm">
                    <div class="w-12 h-12 rounded-2xl bg-calm-100 dark:bg-calm-900 text-calm-600 dark:text-calm-400 flex items-center justify-center text-xl">
                        <i class="fa-solid fa-spa"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 dark:text-white">مدیریتکردنی فشاری دەروونی</h3>
                    <p class="text-sm text-slate-600 dark:text-slate-300 leading-relaxed">فێربوونی تەکنیکەکانی هەناسەدانی قووڵ، ڕێدۆزی و ڕێکخستنی کات.</p>
                    <button onclick="openArticleModal('مدیریتکردنی فشاری دەروونی', 'هەناسەدانی قووڵ بۆ ماوەی ٥ خولەک لە ڕۆژێکدا سیستەمی دەماری هێور دەکاتەوە.')" class="text-brand-600 dark:text-brand-400 text-sm font-semibold inline-flex items-center gap-1 hover:underline pt-2">
                        <span>زیاتر بخوێنەوە</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-white dark:bg-slate-800 rounded-3xl p-8 border border-slate-200 dark:border-slate-700 space-y-4 shadow-sm">
                    <div class="w-12 h-12 rounded-2xl bg-brand-100 dark:bg-brand-900 text-brand-600 dark:text-brand-400 flex items-center justify-center text-xl">
                        <i class="fa-solid fa-heart-pulse"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 dark:text-white">کەمکردنەوەی دڵەڕاوکێ</h3>
                    <p class="text-sm text-slate-600 dark:text-slate-300 leading-relaxed">ڕێکارە پراکتیکییەکان بۆ زاڵبوون بەسەر دڵەڕاوکێی توند.</p>
                    <button onclick="openArticleModal('کەمکردنەوەی دڵەڕاوکێ', 'تەکنیکی 5-4-3-2-1 بەکاربهێنە بۆ گەڕانەوەی مێشک بۆ باری ئارامی.')" class="text-brand-600 dark:text-brand-400 text-sm font-semibold inline-flex items-center gap-1 hover:underline pt-2">
                        <span>زیاتر بخوێنەوە</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-white dark:bg-slate-800 rounded-3xl p-8 border border-slate-200 dark:border-slate-700 space-y-4 shadow-sm">
                    <div class="w-12 h-12 rounded-2xl bg-amber-100 dark:bg-amber-900 text-amber-600 dark:text-amber-400 flex items-center justify-center text-xl">
                        <i class="fa-solid fa-user-shield"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 dark:text-white">چاودێری و خۆشەویستی خودی</h3>
                    <p class="text-sm text-slate-600 dark:text-slate-300 leading-relaxed">گرنگیدان بە خود وەک بنەمایەک بۆ پێشکەشکردنی هاوکاری.</p>
                    <button onclick="openArticleModal('چاودێری خودی', 'تا خۆت بەهێز و ئارام نەبیت، ناتوانیت پاڵپشتی کەسانی تر بکەیت.')" class="text-brand-600 dark:text-brand-400 text-sm font-semibold inline-flex items-center gap-1 hover:underline pt-2">
                        <span>زیاتر بخوێنەوە</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section id="books" class="py-20 bg-white dark:bg-slate-900/50 border-t border-slate-200 dark:border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full bg-brand-100 dark:bg-brand-900/40 text-brand-700 dark:text-brand-300 text-sm font-semibold">کۆگای کتێبەکان</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 dark:text-white">کتێبە دەروونی و پەروەردەییەکان</h2>
                <p class="text-slate-600 dark:text-slate-300">لیستێک لە کتێب و سەرچاوە زانستییە گرنگەکانی بواری دەروونناسی، گەشەی منداڵ و پەروەردەی تایبەت.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-slate-50 dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between space-y-4 shadow-sm">
                    <div class="flex items-start gap-4">
                        <div class="w-14 h-20 rounded-xl bg-gradient-to-tr from-brand-600 to-calm-500 text-white flex items-center justify-center text-xl flex-shrink-0 shadow-md">
                            <i class="fa-solid fa-book"></i>
                        </div>
                        <div class="space-y-1">
                            <span class="text-xs text-brand-600 dark:text-brand-400 font-semibold">دەروونناسی و گەشە</span>
                            <h4 class="font-bold text-slate-900 dark:text-white text-base">بنەماکانی پەروەردەی تایبەت</h4>
                            <p class="text-xs text-slate-500 dark:text-slate-400">نووسین: دەروو جبار قادر</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 dark:text-slate-300 leading-relaxed">ڕێبەری گشتگیر بۆ ناسینەوەی پێویستییە تایبەتەکان.</p>
                    <button onclick="downloadNotice()" class="w-full py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-xs transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-download"></i>
                        <span>داگرتنی کتێب (PDF)</span>
                    </button>
                </div>

                <div class="bg-slate-50 dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between space-y-4 shadow-sm">
                    <div class="flex items-start gap-4">
                        <div class="w-14 h-20 rounded-xl bg-gradient-to-tr from-calm-600 to-indigo-500 text-white flex items-center justify-center text-xl flex-shrink-0 shadow-md">
                            <i class="fa-solid fa-book-open"></i>
                        </div>
                        <div class="space-y-1">
                            <span class="text-xs text-calm-600 dark:text-calm-400 font-semibold">تەندروستی دەروونی</span>
                            <h4 class="font-bold text-slate-900 dark:text-white text-base">هۆشیاری دەروونی و دڵەڕاوکێ</h4>
                            <p class="text-xs text-slate-500 dark:text-slate-400">ڕێبەری پڕاکتیکی</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 dark:text-slate-300 leading-relaxed">ڕزگاربوون لە فشارە دەروونییەکانی ژیانی سەردەم.</p>
                    <button onclick="downloadNotice()" class="w-full py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-xs transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-download"></i>
                        <span>داگرتنی کتێب (PDF)</span>
                    </button>
                </div>

                <div class="bg-slate-50 dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between space-y-4 shadow-sm">
                    <div class="flex items-start gap-4">
                        <div class="w-14 h-20 rounded-xl bg-gradient-to-tr from-amber-600 to-orange-500 text-white flex items-center justify-center text-xl flex-shrink-0 shadow-md">
                            <i class="fa-solid fa-book-bookmark"></i>
                        </div>
                        <div class="space-y-1">
                            <span class="text-xs text-amber-600 dark:text-amber-400 font-semibold">ڕێبەری خێزان</span>
                            <h4 class="font-bold text-slate-900 dark:text-white text-base">مامەڵەکردن لەگەڵ منداڵی خاوەن پێویستی تایبەت</h4>
                            <p class="text-xs text-slate-500 dark:text-slate-400">دەستیار بۆ دایک و باوکان</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 dark:text-slate-300 leading-relaxed">ڕێنمایی ڕۆژانە بۆ دروستکردنی پەیوەندی بەهێز.</p>
                    <button onclick="downloadNotice()" class="w-full py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-xs transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-download"></i>
                        <span>داگرتنی کتێب (PDF)</span>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section id="resources" class="py-20 bg-slate-100/50 dark:bg-slate-900 border-t border-slate-200 dark:border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full bg-calm-100 dark:bg-calm-900/40 text-calm-700 dark:text-calm-300 text-sm font-semibold">سەرچاوەی خێرا</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 dark:text-white">فایل و وڵامنامەی فێرکاری</h2>
                <p class="text-slate-600 dark:text-slate-300">فایل و ڕێنمایینامەی بەسوود بە شێوەی PDF.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex items-center justify-between">
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 rounded-xl bg-red-100 dark:bg-red-900/50 text-red-600 dark:text-red-400 flex items-center justify-center text-xl flex-shrink-0">
                            <i class="fa-solid fa-file-pdf"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-slate-900 dark:text-white text-sm">ڕێنمایی دایک و باوک بۆ کێشەکان</h4>
                            <p class="text-xs text-slate-500 dark:text-slate-400">PDF • ٢.٤ مێگابایت</p>
                        </div>
                    </div>
                    <button onclick="downloadNotice()" class="p-3 rounded-xl bg-brand-600 hover:bg-brand-700 text-white transition shadow-sm">
                        <i class="fa-solid fa-download"></i>
                    </button>
                </div>

                <div class="bg-white dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex items-center justify-between">
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 rounded-xl bg-red-100 dark:bg-red-900/50 text-red-600 dark:text-red-400 flex items-center justify-center text-xl flex-shrink-0">
                            <i class="fa-solid fa-file-pdf"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-slate-900 dark:text-white text-sm">تەکنیکەکانی هێورکردنەوەی دەروونی</h4>
                            <p class="text-xs text-slate-500 dark:text-slate-400">PDF • ١.٨ مێگابایت</p>
                        </div>
                    </div>
                    <button onclick="downloadNotice()" class="p-3 rounded-xl bg-brand-600 hover:bg-brand-700 text-white transition shadow-sm">
                        <i class="fa-solid fa-download"></i>
                    </button>
                </div>

                <div class="bg-white dark:bg-slate-800 rounded-3xl p-6 border border-slate-200 dark:border-slate-700 flex items-center justify-between">
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 rounded-xl bg-red-100 dark:bg-red-900/50 text-red-600 dark:text-red-400 flex items-center justify-center text-xl flex-shrink-0">
                            <i class="fa-solid fa-file-pdf"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-slate-900 dark:text-white text-sm">ڕێبەری مامۆستا بۆ منداڵانی ADHD</h4>
                            <p class="text-xs text-slate-500 dark:text-slate-400">PDF • ٣.١ مێگابایت</p>
                        </div>
                    </div>
                    <button onclick="downloadNotice()" class="p-3 rounded-xl bg-brand-600 hover:bg-brand-700 text-white transition shadow-sm">
                        <i class="fa-solid fa-download"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section id="consultation" class="py-20 bg-gradient-to-t from-brand-50/40 to-transparent dark:from-slate-900">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-white dark:bg-slate-800 rounded-3xl shadow-xl border border-slate-200 dark:border-slate-700 p-8 sm:p-12">
                <div class="text-center max-w-xl mx-auto mb-10 space-y-3">
                    <span class="px-3.5 py-1 rounded-full bg-brand-100 dark:bg-brand-900 text-brand-700 dark:text-brand-300 text-sm font-semibold">پەیوەندی و ڕاوێژ</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-slate-900 dark:text-white">پرسیارێک یان داوای ڕاوێژکاریت هەیە؟</h2>
                    <p class="text-sm text-slate-600 dark:text-slate-300">فۆرمەکە پڕبکەرەوە و دەروو جبار قادر لە زوترین کاتدا وەڵامت دەداتەوە.</p>
                </div>

                <form id="consultation-form" onsubmit="handleFormSubmit(event)" class="space-y-6">
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-2">ناوی تەواو</label>
                            <input type="text" id="name" required class="w-full px-4 py-3 rounded-xl bg-slate-50 dark:bg-slate-900 border border-slate-200 dark:border-slate-700 focus:outline-none focus:ring-2 focus:ring-brand-500 text-slate-800 dark:text-slate-100" placeholder="ناوی خۆت بنووسە">
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-2">ئیمەیڵ یان ژمارەی تەلەفۆن</label>
                            <input type="text" id="contact" required class="w-full px-4 py-3 rounded-xl bg-slate-50 dark:bg-slate-900 border border-slate-200 dark:border-slate-700 focus:outline-none focus:ring-2 focus:ring-brand-500 text-slate-800 dark:text-slate-100" placeholder="email@example.com">
                        </div>
                    </div>

                    <div>
                        <label class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-2">جۆری راوێژکاری یان بابەت</label>
                        <select id="category" class="w-full px-4 py-3 rounded-xl bg-slate-50 dark:bg-slate-900 border border-slate-200 dark:border-slate-700 focus:outline-none focus:ring-2 focus:ring-brand-500 text-slate-800 dark:text-slate-100">
                            <option value="special-ed">پەروەردەی تایبەت و کێشەکانی فێربوون</option>
                            <option value="mental-health">تەندروستی دەروونی و دڵەڕاوکێ</option>
                            <option value="child-dev">گەشەی منداڵ و ڕەفتار</option>
                            <option value="other">بابەتی تر</option>
                        </select>
                    </div>

                    <div>
                        <label class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-2">پرسیار یان کێشەکەت بە وردی باس بکە</label>
                        <textarea id="message" rows="4" required class="w-full px-4 py-3 rounded-xl bg-slate-50 dark:bg-slate-900 border border-slate-200 dark:border-slate-700 focus:outline-none focus:ring-2 focus:ring-brand-500 text-slate-800 dark:text-slate-100" placeholder="لێرە دەتوانیت پرسیارەکەت بنووسیت..."></textarea>
                    </div>

                    <button type="submit" class="w-full py-4 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-bold shadow-lg shadow-brand-600/25 transition transform active:scale-[0.99] flex items-center justify-center gap-2">
                        <span>ناردنی داواکاری</span>
                        <i class="fa-solid fa-paper-plane text-sm"></i>
                    </button>
                </form>

                <div id="success-box" class="hidden mt-6 p-4 rounded-2xl bg-emerald-50 dark:bg-emerald-900/40 border border-emerald-200 dark:border-emerald-800 text-emerald-800 dark:text-emerald-200 text-center font-medium flex items-center justify-center gap-3">
                    <i class="fa-solid fa-circle-check text-xl text-emerald-600 dark:text-emerald-400"></i>
                    <span>سوپاس بۆ داواکارییەکەت! پەیامەکەت بە سەرکەوتوویی گەیشت و لە زوترین کاتدا وەڵامت دەدرێتەوە.</span>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-20 bg-white dark:bg-slate-900/50 border-t border-slate-200 dark:border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-6 space-y-6">
                    <span class="px-3.5 py-1 rounded-full bg-brand-100 dark:bg-brand-900/40 text-brand-700 dark:text-brand-300 text-sm font-semibold">دەربارەی پلاتفۆرم</span>
                    <h2 class="text-3xl font-extrabold text-slate-900 dark:text-white">ئامانج و دیدگای ئێمە</h2>
                    <p class="text-slate-600 dark:text-slate-300 leading-relaxed">
                        ئەم پلاتفۆرمە پڕۆژەیەکی پەروەردەیی و مرۆڤدۆستانەیە کە لەلایەن <span class="font-bold text-brand-600 dark:text-brand-400">دەروو جبار قادر</span> (خوێندکاری پەروەردەی تایبەت لە زانکۆی چەرموو) دامەزراوە. ئامانجمان بڵاوکردنەوەی هۆشیاری دەروونی و پێشکەشکردنی ڕێنمایی زانستییە بە زمانە شیرینەکەی کوردی.
                    </p>
                    <div class="grid grid-cols-2 gap-4 pt-2">
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded-full bg-brand-100 dark:bg-brand-900 text-brand-600 flex items-center justify-center text-sm">
                                <i class="fa-solid fa-check"></i>
                            </div>
                            <span class="font-medium text-sm">ڕێنمایی زانستی</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded-full bg-brand-100 dark:bg-brand-900 text-brand-600 flex items-center justify-center text-sm">
                                <i class="fa-solid fa-check"></i>
                            </div>
                            <span class="font-medium text-sm">پاراستنی نهێنی</span>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-6">
                    <div class="bg-gradient-to-tr from-brand-600 to-calm-500 rounded-3xl p-8 text-white shadow-xl space-y-6">
                        <div class="w-16 h-16 rounded-2xl bg-white/20 flex items-center justify-center text-3xl">
                            <i class="fa-solid fa-graduation-cap"></i>
                        </div>
                        <h3 class="text-2xl font-bold">دامەزرێنەری پڕۆژە</h3>
                        <p class="text-white/90 leading-relaxed text-sm">
                            "ئامانجم لە دروستکردنی ئەم پلاتفۆرمە ئەوەیە ببێتە پردێکی زانستی و دەروونی لە نێوان دایک و باوکان، مامۆستایان و پسپۆڕاندا تاوەکو باشترین ژینگە بۆ منداڵان دابین بکەین."
                        </p>
                        <div class="pt-2 font-semibold text-white/95">
                            — دەروو جبار قادر <span class="text-xs font-normal block opacity-85">خوێندکاری پەروەردەی تایبەت • زانکۆی چەرموو</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-slate-900 text-slate-400 py-12 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-12">
                <div class="md:col-span-2 space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-xl bg-brand-600 flex items-center justify-center text-white">
                            <i class="fa-solid fa-hands-holding-child"></i>
                        </div>
                        <span class="text-lg font-bold text-white">ڕێنمایی دەروونی و پەروەردەیی</span>
                    </div>
                    <p class="text-sm max-w-sm text-slate-400">
                        پلاتفۆرمی نیشتمانی بۆ هۆشیاری دەروونی و پەروەردەی تایبەت — دابینکراو لەلایەن دەروو جبار قادر.
                    </p>
                </div>
                <div>
                    <h4 class="text-white font-bold mb-4">بەشە سەرەکییەکان</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#special-education" class="hover:text-white transition">پەروەردەی تایبەت</a></li>
                        <li><a href="#mental-health" class="hover:text-white transition">تەندروستی دەروونی</a></li>
                        <li><a href="#books" class="hover:text-white transition">کتێبەکان</a></li>
                        <li><a href="#consultation" class="hover:text-white transition">داوای ڕاوێژ</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-white font-bold mb-4">پەیوەندی و زانیاری</h4>
                    <ul class="space-y-2 text-sm">
                        <li><i class="fa-solid fa-envelope ml-2 text-brand-500"></i> darwjabar@gmail.com</li>
                        <li><i class="fa-solid fa-phone ml-2 text-brand-500"></i> 07702122873</li>
                        <li><i class="fa-solid fa-location-dot ml-2 text-brand-500"></i> چەمچەماڵ، زانکۆی چەرموو</li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-slate-800 pt-8 flex flex-col sm:flex-row items-center justify-between text-xs">
                <p>&copy; ٢٠٢٦ ڕێنمایی دەروونی و پەروەردەیی. دروستکراوە لەلایەن دەروو جبار قادر.</p>
                <div class="flex gap-4 mt-4 sm:mt-0">
                    <a href="#" class="hover:text-white transition"><i class="fa-brands fa-facebook-f text-lg"></i></a>
                    <a href="#" class="hover:text-white transition"><i class="fa-brands fa-instagram text-lg"></i></a>
                    <a href="#" class="hover:text-white transition"><i class="fa-brands fa-telegram text-lg"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <div id="article-modal" class="fixed inset-0 z-50 hidden bg-slate-900/60 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white dark:bg-slate-800 rounded-3xl max-w-lg w-full p-6 sm:p-8 shadow-2xl border border-slate-200 dark:border-slate-700 space-y-4 relative">
            <button onclick="closeArticleModal()" class="absolute top-4 left-4 p-2 rounded-full bg-slate-100 dark:bg-slate-700 text-slate-500 hover:text-slate-800 dark:hover:text-white transition">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            <h3 id="modal-title" class="text-xl font-bold text-slate-900 dark:text-white">ناونیشانی وتار</h3>
            <p id="modal-content" class="text-sm text-slate-600 dark:text-slate-300 leading-relaxed">وردەکاری و ناوەڕۆکی وتارەکە...</p>
            <div class="pt-4 flex justify-end">
                <button onclick="closeArticleModal()" class="px-5 py-2.5 rounded-xl bg-brand-600 text-white font-medium text-sm">داخستن</button>
            </div>
        </div>
    </div>

    <script>
        // Theme Toggle Logic
        const themeToggleBtn = document.getElementById('theme-toggle');
        const htmlElement = document.documentElement;

        if (localStorage.theme === 'dark' || (!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
            htmlElement.classList.add('dark');
        } else {
            htmlElement.classList.remove('dark');
        }

        themeToggleBtn.addEventListener('click', () => {
            if (htmlElement.classList.contains('dark')) {
                htmlElement.classList.remove('dark');
                localStorage.theme = 'light';
            } else {
                htmlElement.classList.add('dark');
                localStorage.theme = 'dark';
            }
        });

        // Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        mobileMenu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Article Modal Functions
        function openArticleModal(title, content) {
            document.getElementById('modal-title').innerText = title;
            document.getElementById('modal-content').innerText = content;
            document.getElementById('article-modal').classList.remove('hidden');
        }

        function closeArticleModal() {
            document.getElementById('article-modal').classList.add('hidden');
        }

        // Consultation Form Handler
        function handleFormSubmit(event) {
            event.preventDefault();
            const successBox = document.getElementById('success-box');
            successBox.classList.remove('hidden');
            document.getElementById('consultation-form').reset();
            
            setTimeout(() => {
                successBox.classList.add('hidden');
            }, 6000);
        }

        // Download Notice Notification
        function downloadNotice() {
            alert('فایلەکە یان کتێبەکە بە سەرکەوتوویی داگیرا!');
        }
    </script>
</body>
</html>
