<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KBHAZ | Born of Nature, Powered by Within</title>
    <script src="https://cdn.tailwindcss.com?plugins=forms,typography,aspect-ratio,line-clamp"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@300;400;500&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #F5F2ED;
            --text-color: #1C1917;
            --accent-color: #788C5D;
        }
        body {
            font-family: 'Inter', 'Noto Serif SC', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            line-height: 1.5;
        }
        .font-serif-brand {
            font-family: 'Noto Serif SC', 'Georgia', serif;
        }
        [lang-content] { display: none; }
        .lang-active { display: block; }
        span.lang-active { display: inline; }
    </style>
</head>
<body class="text-[#1C1917] antialiased">

    <!-- Navigation -->
    <nav class="flex items-center justify-between px-8 py-6 max-w-7xl mx-auto">
        <div class="text-2xl font-serif-brand tracking-widest font-medium">KBHAZ</div>
        <div class="hidden md:flex space-x-12 text-sm font-medium tracking-wide uppercase">
            <a href="#" class="hover:opacity-60 transition-opacity">
                <span lang-content="en" class="lang-active">Home</span>
                <span lang-content="zh">首页</span>
            </a>
            <a href="#" class="hover:opacity-60 transition-opacity">
                <span lang-content="en" class="lang-active">Our Story</span>
                <span lang-content="zh">品牌故事</span>
            </a>
            <a href="#" class="hover:opacity-60 transition-opacity">
                <span lang-content="en" class="lang-active">Collections</span>
                <span lang-content="zh">系列展示</span>
            </a>
            <a href="#" class="hover:opacity-60 transition-opacity">
                <span lang-content="en" class="lang-active">Eco-Commitment</span>
                <span lang-content="zh">环保承诺</span>
            </a>
        </div>
        <div class="flex items-center space-x-6">
            <button id="lang-toggle" class="text-[10px] tracking-widest uppercase border border-[#1C1917]/20 px-2 py-1 rounded hover:bg-[#1C1917]/5 transition-all">
                EN / 中文
            </button>
            <a href="#" class="text-sm font-medium border-b border-[#1C1917] pb-1 hover:opacity-50 transition-all">
                <span lang-content="en" class="lang-active">Contact</span>
                <span lang-content="zh">联系我们</span>
            </a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative min-h-[85vh] flex items-center overflow-hidden px-8">
        <div class="absolute top-1/4 right-0 w-96 h-96 bg-[#788C5D]/10 rounded-full blur-[100px] -z-10"></div>
        <div class="max-w-7xl mx-auto w-full grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
            <div>
                <span class="inline-block px-3 py-1 text-xs font-semibold tracking-widest text-[#788C5D] uppercase bg-[#788C5D]/10 rounded-full mb-8">Sustainable · Minimalist · Elegant</span>
                <h1 class="text-5xl md:text-7xl font-serif-brand font-light leading-tight mb-8">
                    <div lang-content="en" class="lang-active">Born of Nature,<br/><span class="font-medium">Powered by Within</span></div>
                    <div lang-content="zh">生于自然，<br/><span class="font-medium">蕴力于内</span></div>
                </h1>
                <p class="max-w-md text-lg text-[#1C1917] font-light leading-relaxed mb-12">
                    <span lang-content="en" class="lang-active">KBHAZ combines sustainable materials with modern minimalist aesthetics, crafting unique footwear and apparel for gentle yet determined souls.</span>
                    <span lang-content="zh">KBHAZ 致力于将可持续材料与现代简约美学结合，为温柔且坚定的灵魂打造独一无二的鞋履与服饰。</span>
                </p>
                <div class="flex space-x-8">
                    <button class="px-10 py-4 bg-[#1C1917] text-[#F5F2ED] text-sm font-medium tracking-wide hover:opacity-90">
                        <span lang-content="en" class="lang-active">Explore Collections</span>
                        <span lang-content="zh">探索系列</span>
                    </button>
                    <button class="px-10 py-4 border border-[#1C1917] text-sm font-medium tracking-wide hover:bg-[#1C1917]/5">
                        <span lang-content="en" class="lang-active">Our Story</span>
                        <span lang-content="zh">品牌故事</span>
                    </button>
                </div>
            </div>
            <div class="relative">
                <div class="aspect-[3/4] w-full bg-[#E5E1DA] overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1549298916-b41d501d3772?q=80&w=1000&auto=format&fit=crop" alt="KBHAZ" class="w-full h-full object-cover">
                </div>
                <div class="absolute -bottom-6 -left-6 bg-white/80 backdrop-blur-md p-8 shadow-xl hidden md:block">
                    <p class="text-[10px] tracking-widest uppercase text-[#788C5D] font-bold mb-2">Philosophy</p>
                    <p class="text-xl font-serif-brand italic">
                        <span lang-content="en" class="lang-active">“Simplicity reveals<br/>the inner essence”</span>
                        <span lang-content="zh">“减法，是为了让<br/>内核更清晰”</span>
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Brand Values -->
    <section class="py-24 bg-white/40">
        <div class="max-w-7xl mx-auto px-8 text-center">
            <h2 class="text-3xl font-serif-brand mb-16">
                <span lang-content="en" class="lang-active">Our Sustainable Ethos</span>
                <span lang-content="zh">我们的可持续理念</span>
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
                <div>
                    <h3 class="font-medium mb-3">
                        <span lang-content="en" class="lang-active">Conscious Materials</span>
                        <span lang-content="zh">纯粹材质</span>
                    </h3>
                    <p class="text-sm text-[#1C1917]/60">
                        <span lang-content="en" class="lang-active">We source high-quality, eco-friendly materials to reduce environmental impact.</span>
                        <span lang-content="zh">我们采购高品质环保材料，致力于降低对环境的影响。</span>
                    </p>
                </div>
                <div>
                    <h3 class="font-medium mb-3">
                        <span lang-content="en" class="lang-active">Timeless Design</span>
                        <span lang-content="zh">简约设计</span>
                    </h3>
                    <p class="text-sm text-[#1C1917]/60">
                        <span lang-content="en" class="lang-active">Creating pieces that transcend seasons and trends, returning to the essence.</span>
                        <span lang-content="zh">打造超越季节与潮流的经典单品，让美感回归事物本真。</span>
                    </p>
                </div>
                <div>
                    <h3 class="font-medium mb-3">
                        <span lang-content="en" class="lang-active">Ethical Craft</span>
                        <span lang-content="zh">公平足迹</span>
                    </h3>
                    <p class="text-sm text-[#1C1917]/60">
                        <span lang-content="en" class="lang-active">Respecting every artisan involved in the making of KBHAZ.</span>
                        <span lang-content="zh">每一个针脚，都包含着对环境与工匠的尊重。</span>
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Curated Collections -->
    <section class="py-24 px-8">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-3xl font-serif-brand mb-12 text-center">
                <span lang-content="en" class="lang-active">Curated Essentials</span>
                <span lang-content="zh">精选系列</span>
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="group"><div class="aspect-[4/5] bg-[#E5E1DA] mb-4"><img src="https://images.unsplash.com/photo-1543163521-1bf539c55dd2?q=80&w=800&auto=format&fit=crop" class="w-full h-full object-cover"></div>
                    <h4 class="font-serif-brand text-lg"><span lang-content="en" class="lang-active">The Eco-Step</span><span lang-content="zh">环保鞋履</span></h4>
                </div>
                <div class="group"><div class="aspect-[4/5] bg-[#E5E1DA] mb-4"><img src="https://images.unsplash.com/photo-1594633312681-425c7b97ccd1?q=80&w=800&auto=format&fit=crop" class="w-full h-full object-cover"></div>
                    <h4 class="font-serif-brand text-lg"><span lang-content="en" class="lang-active">Natural Fiber Wear</span><span lang-content="zh">天然纤维服饰</span></h4>
                </div>
                <div class="group"><div class="aspect-[4/5] bg-[#E5E1DA] mb-4"><img src="https://images.unsplash.com/photo-1584917865442-de89df76afd3?q=80&w=800&auto=format&fit=crop" class="w-full h-full object-cover"></div>
                    <h4 class="font-serif-brand text-lg"><span lang-content="en" class="lang-active">Recycled Leather Totes</span><span lang-content="zh">再生皮革包袋</span></h4>
                </div>
            </div>
        </div>
    </section>

    <script>
        const langToggle = document.getElementById('lang-toggle');
        let currentLang = 'en';
        langToggle.addEventListener('click', () => {
            currentLang = currentLang === 'en' ? 'zh' : 'en';
            document.querySelectorAll('[lang-content]').forEach(el => {
                el.classList.toggle('lang-active', el.getAttribute('lang-content') === currentLang);
            });
            document.title = currentLang === 'en' ? 'KBHAZ | Born of Nature, Powered by Within' : 'KBHAZ | 生于自然，蕴力于内';
        });
    </script>
</body>
</html>
