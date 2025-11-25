
<html lang="vi" class="scroll-smooth">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daniel Mvch - Nhà phát triển & Thiết kế Giao diện</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0a0a0a;
            color: #e2e8f0; /* slate-200 */
        }

        .gradient-bg {
            background-image: radial-gradient(circle at 50% 0%, rgba(30, 41, 59, 0.5) 0%, rgba(10, 10, 10, 0) 40%);
        }

        .glassmorphism {
            background: rgba(17, 24, 39, 0.6);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .scroll-reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
        }

        .scroll-reveal.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>

<body class="gradient-bg">

    <!-- Header -->
    <header id="header" class="glassmorphism sticky top-0 z-50 transition-all duration-300">
        <div class="container mx-auto px-6 py-4">
            <nav class="flex items-center justify-between">
                <a href="#" class="text-2xl font-bold text-white tracking-wider">Daniel<span class="text-sky-400"> </span>Mvch</a>
                <div class="hidden md:flex items-center space-x-6">
                    <a href="#about" class="text-slate-300 hover:text-sky-400 transition-colors duration-300">Tôi</a>
                    <a href="#journey" class="text-slate-300 hover:text-sky-400 transition-colors duration-300">Hành trình</a>
                    <a href="#projects" class="text-slate-300 hover:text-sky-400 transition-colors duration-300">Dự án</a>
                    <a href="#stories" class="text-slate-300 hover:text-sky-400 transition-colors duration-300">Câu chuyện</a>
                    <a href="#faq" class="text-slate-300 hover:text-sky-400 transition-colors duration-300">Hỏi đáp</a>
                    <a href="#contact" class="text-slate-300 hover:text-sky-400 transition-colors duration-300">Liên hệ</a>
                </div>
                <a href="#contact" class="hidden md:inline-block bg-sky-500 text-white font-semibold px-5 py-2 rounded-lg hover:bg-sky-600 transition-all duration-300 transform hover:scale-105">
                    Bắt đầu dự án
                </a>
                <button id="mobile-menu-button" class="md:hidden text-white">
                    <i data-lucide="menu"></i>
                </button>
            </nav>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4">
            <a href="#about" class="block py-2 text-slate-300 hover:text-sky-400">Tôi</a>
            <a href="#journey" class="block py-2 text-slate-300 hover:text-sky-400">Hành trình</a>
            <a href="#projects" class="block py-2 text-slate-300 hover:text-sky-400">Dự án</a>
            <a href="#stories" class="block py-2 text-slate-300 hover:text-sky-400">Câu chuyện</a>
            <a href="#faq" class="block py-2 text-slate-300 hover:text-sky-400">Hỏi đáp</a>
            <a href="#contact" class="block py-2 text-slate-300 hover:text-sky-400">Liên hệ</a>
             <a href="#contact" class="block mt-4 bg-sky-500 text-white font-semibold px-5 py-2 rounded-lg text-center hover:bg-sky-600 transition-all duration-300">
                Bắt đầu dự án
            </a>
        </div>
    </header>

    <main class="container mx-auto px-6">

        <!-- Hero Section -->
        <section id="home" class="min-h-screen flex items-center pt-16 md:pt-0">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="text-center md:text-left">
                    <h1 class="text-4xl md:text-6xl font-extrabold text-white leading-tight mb-4">
                        Hành trình <span class="text-sky-400">Sáng tạo</span> & Phát triển sự nghiệp
                    </h1>
                    <p class="text-lg text-slate-400 mb-8 max-w-xl mx-auto md:mx-0">
                        "Daniel Mvch" nơi bạn xem trọn cuộc đời tôi
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 justify-center md:justify-start">
                        <a href="#projects" class="bg-sky-500 text-white font-semibold px-8 py-3 rounded-lg hover:bg-sky-600 transition-all duration-300 transform hover:scale-105 flex items-center justify-center gap-2">
                            <i data-lucide="folder-kanban"></i>
                            Dự án của tôi
                        </a>
                        <a href="#contact" class="bg-slate-700 text-white font-semibold px-8 py-3 rounded-lg hover:bg-slate-600 transition-all duration-300 transform hover:scale-105 flex items-center justify-centerp-2">
                             <i data-lucide="send"></i>
                            Liên hệ
                        </a>
                    </div>
                </div>
                <div class="relative flex justify-center items-center">
                     <div class="absolute w-72 h-72 sm:w-96 sm:h-96 bg-sky-500/20 rounded-full blur-3xl"></div>
                    <img src="https://res.cloudinary.com/drp5y2a3d/image/upload/v1760816034/IMG_4574_-_Copy_hljasj.jpg" alt="Daniel Mvch" class="relative w-72 h-72 sm:w-96 sm:h-96 object-cover rounded-full border-4 border-slate-800 shadow-2xl shadow-sky-900/50">
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-24 scroll-reveal">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white">Về tôi</h2>
                <p class="text-slate-400 mt-4">Kỹ năng và đam mê của tôi.</p>
            </div>
            <div class="grid md:grid-cols-5 gap-12 items-center">
                <div class="md:col-span-2">
                    <img src="https://res.cloudinary.com/drp5y2a3d/image/upload/v1760816155/IMG_4527_-_Copy_z1wock.jpg" alt="Daniel Mvch Workspace" class="rounded-xl shadow-lg w-full h-auto">
                </div>
                <div class="md:col-span-3">
                    <h3 class="text-3xl font-semibold text-white mb-4">Chào bạn, tôi là Daniel Mvch.</h3>
                    <p class="text-slate-300 mb-6">
                       Xin chào mọi người,

Tôi là Ksor Nhăk, một cái tên mang đậm dấu ấn của quê hương Gia Lai, nhưng mọi người cũng có thể gọi tôi thân mật là Daniel. Tôi là một người con của dân tộc Jrai và là một Cơ đốc nhân.


                    </p>
                    <p class="text-slate-300 mb-8">
                    Hiện tại, tôi đang là sinh viên tại trường Đại học HUTECH, theo đuổi đam mê của mình với chuyên ngành Digital Marketing. Tôi có một niềm yêu thích lớn dành cho lĩnh vực truyền thông và luôn hào hứng với việc khám phá, chia sẻ những điều mới mẻ, những ý tưởng sáng tạo đến với mọi người.
                    </p>
                    <h4 class="text-xl font-semibold text-white mb-4">Công nghệ tôi sử dụng:</h4>
                    <div class="flex flex-wrap gap-4">
                        <span class="flex items-center gap-2 bg-slate-800 px-4 py-2 rounded-md text-sm font-medium"><i data-lucide="Facebook" class="text-sky-400 w-5 h-5"></i>Facebook</span>
                        <span class="flex items-center gap-2 bg-slate-800 px-4 py-2 rounded-md text-sm font-medium"><i data-lucide="leaf" class="text-green-400 w-5 h-5"></i>Tiktok</span>
                        <span class="flex items-center gap-2 bg-slate-800 px-4 py-2 rounded-md text-sm font-medium"><i data-lucide="wind" class="text-cyan-400 w-5 h-5"></i>Capcut</span>
                        <span class="flex items-center gap-2 bg-slate-800 px-4 py-2 rounded-md text-sm font-medium"><i data-lucide="type" class="text-blue-400 w-5 h-5"></i>Các công cụ AI</span>
                        <span class="flex items-center gap-2 bg-slate-800 px-4 py-2 rounded-md text-sm font-medium"><i data-lucide="figma" class="text-purple-400 w-5 h-5"></i>Instar</span>
                        <span class="flex items-center gap-2 bg-slate-800 px-4 py-2 rounded-md text-sm font-medium"><i data-lucide="Youtube" class="text-yellow-400 w-5 h-5"></i>Youtube</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Journey Section -->
        <section id="journey" class="py-24 scroll-reveal">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white">Hành trình của tôi</h2>
                <p class="text-slate-400 mt-4">Các cột mốc quan trọng trong sự nghiệp và học vấn.</p>
            </div>
            <div class="relative max-w-3xl mx-auto">
                <!-- The vertical line -->
                <div class="absolute left-3 md:left-1/2 w-0.5 h-full bg-slate-700 transform md:-translate-x-1/2"></div>
                
                <!-- Timeline Block -->
                <div class="relative mb-10 pl-10 md:pl-0">
                    <!-- Dot -->
                    <div class="absolute left-3 md:left-1/2 w-4 h-4 mt-2 bg-sky-400 rounded-full transform -translate-x-1/2 border-4 border-slate-800"></div>
                    <!-- Content -->
                    <div class="md:w-1/2 md:ml-auto md:pl-8">
                         <div class="bg-slate-900/50 border border-slate-800 p-6 rounded-xl">
                            <span class="text-sm font-semibold text-sky-400">2025</span>
                            <h3 class="text-xl font-bold text-white mt-1">Học Đại học</h3>
                            <p class="text-slate-400 mt-2">Hutech_Digital Marketing - Làm việc tại Amazing Center (  TP.HCM ).</p>
                        </div>
                    </div>
                </div>
                
                <!-- Timeline Block -->
                <div class="relative mb-10 pl-10 md:pl-0">
                    <!-- Dot -->
                    <div class="absolute left-3 md:left-1/2 w-4 h-4 mt-2 bg-sky-400 rounded-full transform -translate-x-1/2 border-4 border-slate-800"></div>
                    <!-- Content -->
                    <div class="md:w-1/2 md:mr-auto md:pr-8 md:text-right">
                         <div class="bg-slate-900/50 border border-slate-800 p-6 rounded-xl">
                            <span class="text-sm font-semibold text-sky-400">... </span>
                            <h3 class="text-xl font-bold text-white mt-1">...</h3>
                            <p class="text-slate-400 mt-2">...</p>
                        </div>
                    </div>
                </div>
                
    
                <!-- Timeline Block -->
                <div class="relative mb-10 pl-10 md:pl-0">
                    <!-- Dot -->
                    <div class="absolute left-3 md:left-1/2 w-4 h-4 mt-2 bg-sky-400 rounded-full transform -translate-x-1/2 border-4 border-slate-800"></div>
                    <!-- Content -->
                    <div class="md:w-1/2 md:ml-auto md:pl-8">
                         <div class="bg-slate-900/50 border border-slate-800 p-6 rounded-xl">
                            <span class="text-sm font-semibold text-sky-400">...</span>
                            <h3 class="text-xl font-bold text-white mt-1">...</h3>
                            <p class="text-slate-400 mt-2">...</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-24 scroll-reveal">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white">Các dự án nổi bật</h2>
                <p class="text-slate-400 mt-4">Một vài sản phẩm mà tôi đã tâm huyết xây dựng.</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project Card 1 -->
                <div class="bg-slate-900/50 border border-slate-800 rounded-xl overflow-hidden group transform hover:-translate-y-2 transition-all duration-300 shadow-lg">
                    <img src="https://placehold.co/600x400/1e293b/94a3b8?text=Project+A" alt="Project A" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Trang quản trị Doanh nghiệp</h3>
                        <p class="text-slate-400 mb-4 text-sm">Một dashboard phân tích dữ liệu toàn diện giúp doanh nghiệp theo dõi các chỉ số quan trọng.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-1 rounded">React</span>
                            <span class="bg-red-900 text-red-300 text-xs font-semibold px-2.5 py-1 rounded">D3.js</span>
                            <span class="bg-slate-700 text-slate-300 text-xs font-semibold px-2.5 py-1 rounded">Node.js</span>
                        </div>
                        <div class="flex items-center gap-4 mt-4">
                            <a href="#" class="text-sky-400 hover:text-sky-300 transition-colors duration-300 flex items-center gap-1"><i data-lucide="external-link" class="w-4 h-4"></i>Xem trực tiếp</a>
                            <a href="#" class="text-slate-400 hover:text-white transition-colors duration-300 flex items-center gap-1"><i data-lucide="github" class="w-4 h-4"></i>Mã nguồn</a>
                        </div>
                    </div>
                </div>
                <!-- Project Card 2 -->
                <div class="bg-slate-900/50 border border-slate-800 rounded-xl overflow-hidden group transform hover:-translate-y-2 transition-all duration-300 shadow-lg">
                    <img src="https://placehold.co/600x400/1e293b/94a3b8?text=Project+B" alt="Project B" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Sàn thương mại điện tử</h3>
                        <p class="text-slate-400 mb-4 text-sm">Website thương mại điện tử hiện đại với tính năng giỏ hàng, thanh toán và quản lý sản phẩm.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-gray-800 text-gray-300 text-xs font-semibold px-2.5 py-1 rounded">Next.js</span>
                            <span class="bg-cyan-900 text-cyan-300 text-xs font-semibold px-2.5 py-1 rounded">Tailwind CSS</span>
                            <span class="bg-green-900 text-green-300 text-xs font-semibold px-2.5 py-1 rounded">MongoDB</span>
                        </div>
                        <div class="flex items-center gap-4 mt-4">
                            <a href="#" class="text-sky-400 hover:text-sky-300 transition-colors duration-300 flex items-center gap-1"><i data-lucide="external-link" class="w-4 h-4"></i>Xem trực tiếp</a>
                            <a href="#" class="text-slate-400 hover:text-white transition-colors duration-300 flex items-center gap-1"><i data-lucide="github" class="w-4 h-4"></i>Mã nguồn</a>
                        </div>
                    </div>
                </div>
                <!-- Project Card 3 -->
                <div class="bg-slate-900/50 border border-slate-800 rounded-xl overflow-hidden group transform hover:-translate-y-2 transition-all duration-300 shadow-lg">
                    <img src="https://placehold.co/600x400/1e293b/94a3b8?text=Project+C" alt="Project C" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Ứng dụng Chat thời gian thực</h3>
                        <p class="text-slate-400 mb-4 text-sm">Một ứng dụng trò chuyện nhanh và mượt mà sử dụng công nghệ WebSockets.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                             <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-1 rounded">React</span>
                             <span class="bg-yellow-900 text-yellow-300 text-xs font-semibold px-2.5 py-1 rounded">Firebase</span>
                             <span class="bg-blue-900 text-blue-300 text-xs font-semibold px-2.5 py-1 rounded">TypeScript</span>
                        </div>
                         <div class="flex items-center gap-4 mt-4">
                            <a href="#" class="text-sky-400 hover:text-sky-300 transition-colors duration-300 flex items-center gap-1"><i data-lucide="external-link" class="w-4 h-4"></i>Xem trực tiếp</a>
                            <a href="#" class="text-slate-400 hover:text-white transition-colors duration-300 flex items-center gap-1"><i data-lucide="github" class="w-4 h-4"></i>Mã nguồn</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Stories Section -->
        <section id="stories" class="py-24 scroll-reveal">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white">Câu chuyện & Chia sẻ</h2>
                <p class="text-slate-400 mt-4">Những bài viết về công nghệ, lập trình và cuộc sống.</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Story Card 1 -->
                <div class="bg-slate-900/50 border border-slate-800 rounded-xl overflow-hidden group transform hover:-translate-y-2 transition-all duration-300 shadow-lg">
                    <img src="https://placehold.co/600x400/1e293b/94a3b8?text=Story+1" alt="Story 1" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <p class="text-sm text-sky-400 mb-2">15 Tháng 10, 2025</p>
                        <h3 class="text-xl font-bold text-white mb-2">5 Mẹo để viết mã React sạch hơn</h3>
                        <p class="text-slate-400 mb-4 text-sm">Khám phá các phương pháp tốt nhất để cải thiện chất lượng mã nguồn React của bạn.</p>
                        <a href="#" class="text-sky-400 hover:text-sky-300 transition-colors duration-300 flex items-center gap-1 font-semibold">Đọc thêm <i data-lucide="arrow-right" class="w-4 h-4"></i></a>
                    </div>
                </div>
                <!-- Story Card 2 -->
                <div class="bg-slate-900/50 border border-slate-800 rounded-xl overflow-hidden group transform hover:-translate-y-2 transition-all duration-300 shadow-lg">
                    <img src="https://placehold.co/600x400/1e293b/94a3b8?text=Story+2" alt="Story 2" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <p class="text-sm text-sky-400 mb-2">01 Tháng 10, 2025</p>
                        <h3 class="text-xl font-bold text-white mb-2">Hành trình trở thành lập trình viên</h3>
                        <p class="text-slate-400 mb-4 text-sm">Chia sẻ cá nhân về con đường tôi đã đi và những bài học kinh nghiệm.</p>
                        <a href="#" class="text-sky-400 hover:text-sky-300 transition-colors duration-300 flex items-center gap-1 font-semibold">Đọc thêm <i data-lucide="arrow-right" class="w-4 h-4"></i></a>
                    </div>
                </div>
                <!-- Story Card 3 -->
                <div class="bg-slate-900/50 border border-slate-800 rounded-xl overflow-hidden group transform hover:-translate-y-2 transition-all duration-300 shadow-lg">
                    <img src="https://placehold.co/600x400/1e293b/94a3b8?text=Story+3" alt="Story 3" class="w-full h-48 object-cover">
                    <div class="p-6">
                         <p class="text-sm text-sky-400 mb-2">20 Tháng 9, 2025</p>
                        <h3 class="text-xl font-bold text-white mb-2">Tại sao Tailwind CSS lại tuyệt vời?</h3>
                        <p class="text-slate-400 mb-4 text-sm">Một cái nhìn sâu sắc về lý do tại sao tôi chọn Tailwind CSS cho hầu hết các dự án của mình.</p>
                        <a href="#" class="text-sky-400 hover:text-sky-300 transition-colors duration-300 flex items-center gap-1 font-semibold">Đọc thêm <i data-lucide="arrow-right" class="w-4 h-4"></i></a>
                    </div>
                </div>
            </div>
        </section>
<section id="journey" class="py-24 scroll-reveal">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white">Hành trình Đức Tin</h2>
                <p class="text-slate-400 mt-4">Các cột mốc quan trọng trong Đức Tin nơi Chúa.</p>
            </div>
            <div class="relative max-w-3xl mx-auto">
                <!-- The vertical line -->
                <div class="absolute left-3 md:left-1/2 w-0.5 h-full bg-slate-700 transform md:-translate-x-1/2"></div>
                
                <!-- Timeline Block -->
                <div class="relative mb-10 pl-10 md:pl-0">
                    <!-- Dot -->
                    <div class="absolute left-3 md:left-1/2 w-4 h-4 mt-2 bg-sky-400 rounded-full transform -translate-x-1/2 border-4 border-slate-800"></div>
                    <!-- Content -->
                    <div class="md:w-1/2 md:ml-auto md:pl-8">
                         <div class="bg-slate-900/50 border border-slate-800 p-6 rounded-xl">
                            <span class="text-sm font-semibold text-sky-400">1/2023</span>
                            <h3 class="text-xl font-bold text-white mt-1">Tin nhận Chúa một cách cá nhân</h3>
                            <p class="text-slate-400 mt-2">Năm ấy là năm  2022, tôi đã được một người anh ở tỉnh Bình Phước cũ là người dân tộc Stiêng qua khích lệ trong việc học tập và cầu nguyện - đọc Kinh Thánh.</p>
                        </div>
                    </div>
                </div>
                
                <!-- Timeline Block -->
                <div class="relative mb-10 pl-10 md:pl-0">
                    <!-- Dot -->
                    <div class="absolute left-3 md:left-1/2 w-4 h-4 mt-2 bg-sky-400 rounded-full transform -translate-x-1/2 border-4 border-slate-800"></div>
                    <!-- Content -->
                    <div class="md:w-1/2 md:mr-auto md:pr-8 md:text-right">
                         <div class="bg-slate-900/50 border border-slate-800 p-6 rounded-xl">
                            <span class="text-sm font-semibold text-sky-400">... </span>
                            <h3 class="text-xl font-bold text-white mt-1">...</h3>
                            <p class="text-slate-400 mt-2">...</p>
                        </div>
                    </div>
                </div>
        <!-- FAQ Section -->
        <section id="faq" class="py-24 scroll-reveal">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white">Câu hỏi thường gặp</h2>
                <p class="text-slate-400 mt-4">Tìm câu trả lời cho các câu hỏi phổ biến.</p>
            </div>
            <div class="max-w-3xl mx-auto space-y-4">
                <!-- FAQ Item 1 -->
                <div class="faq-item bg-slate-900/50 border border-slate-800 rounded-xl">
                    <button class="faq-question w-full flex justify-between items-center text-left p-6">
                        <span class="text-lg font-semibold text-white">Bạn có nhận các dự án freelance không?</span>
                        <i data-lucide="chevron-down" class="faq-icon transition-transform duration-300"></i>
                    </button>
                    <div class="faq-answer overflow-hidden max-h-0 transition-all duration-500 ease-in-out">
                        <p class="p-6 pt-0 text-slate-300">
                            Có, tôi luôn sẵn sàng thảo luận về các cơ hội freelance thú vị. Nếu bạn có một dự án muốn hợp tác, vui lòng gửi email cho tôi qua mục <a href="#contact" class="text-sky-400 hover:underline">Liên hệ</a>.
                        </p>
                    </div>
                </div>
                <!-- FAQ Item 2 -->
                <div class="faq-item bg-slate-900/50 border border-slate-800 rounded-xl">
                    <button class="faq-question w-full flex justify-between items-center text-left p-6">
                        <span class="text-lg font-semibold text-white">Quy trình làm việc của bạn như thế nào?</span>
                        <i data-lucide="chevron-down" class="faq-icon transition-transform duration-300"></i>
                    </button>
                    <div class="faq-answer overflow-hidden max-h-0 transition-all duration-500 ease-in-out">
                        <p class="p-6 pt-0 text-slate-300">
                            Quy trình của tôi thường bắt đầu bằng việc tìm hiểu sâu về yêu cầu dự án. Sau đó là giai đoạn thiết kế (UI/UX), tiếp theo là phát triển, thử nghiệm và cuối cùng là triển khai. Tôi luôn duy trì giao tiếp cởi mở với khách hàng trong suốt quá trình.
                        </p>
                    </div>
                </div>
                <!-- FAQ Item 3 -->
                <div class="faq-item bg-slate-900/50 border border-slate-800 rounded-xl">
                    <button class="faq-question w-full flex justify-between items-center text-left p-6">
                        <span class="text-lg font-semibold text-white">Thời gian hoàn thành một trang web thông thường là bao lâu?</span>
                        <i data-lucide="chevron-down" class="faq-icon transition-transform duration-300"></i>
                    </button>
                    <div class="faq-answer overflow-hidden max-h-0 transition-all duration-500 ease-in-out">
                        <p class="p-6 pt-0 text-slate-300">
                            Thời gian hoàn thành phụ thuộc rất nhiều vào độ phức tạp của dự án. Một trang web danh mục đầu tư đơn giản có thể mất 1-2 tuần, trong khi một ứng dụng web phức tạp hơn có thể mất vài tháng. Hãy liên hệ để chúng ta có thể thảo luận chi tiết hơn về dự án của bạn.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-24 scroll-reveal">
            <div class="text-center max-w-3xl mx-auto">
                <h2 class="text-4xl font-bold text-white">Liên lạc</h2>
                <p class="text-slate-400 mt-4 mb-8">
                    Bạn có một ý tưởng tuyệt vời? Hãy cùng nhau biến nó thành hiện thực. Gửi email cho tôi hoặc kết nối qua mạng xã hội.
                </p>
                <a href="mailto:contact@danielmvch.com" class="inline-block text-2xl font-semibold text-sky-400 hover:text-sky-300 transition-colors duration-300 mb-8">
                    nhakjin.tk@gmail.com
                </a>
                <div class="flex justify-center gap-6">
                    <a href="#" class="text-slate-400 hover:text-white transition-colors duration-300" aria-label="Github">
                        <i data-lucide="github" class="w-8 h-8"></i>
                    </a>
                    <a href="#" class="text-slate-400 hover:text-white transition-colors duration-300" aria-label="LinkedIn">
                        <i data-lucide="linkedin" class="w-8 h-8"></i>
                    </a>
                    <a href="#" class="text-slate-400 hover:text-white transition-colors duration-300" aria-label="Twitter">
                        <i data-lucide="twitter" class="w-8 h-8"></i>
                    </a>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-800">
        <div class="container mx-auto px-6 py-6 text-center text-slate-500">
            <p>&copy; 2025 Daniel Mvch. Đã đăng ký Bản quyền.</p>
        </div>
    </footer>


    <script>
        // Lucide Icons
        lucide.createIcons();

        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        const mobileMenuLinks = mobileMenu.querySelectorAll('a');
        mobileMenuLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
        
        // Header shadow on scroll
        const header = document.getElementById('header');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 10) {
                header.classList.add('shadow-lg', 'shadow-slate-900/50');
            } else {
                header.classList.remove('shadow-lg', 'shadow-slate-900/50');
            }
        });
        
        // Scroll Reveal Animation
        const revealElements = document.querySelectorAll('.scroll-reveal');
        const revealObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                    // Optional: unobserve after revealing
                    // revealObserver.unobserve(entry.target); 
                }
            });
        }, {
            threshold: 0.1
        });

        revealElements.forEach(el => {
            revealObserver.observe(el);
        });

        // FAQ Accordion
        const faqItems = document.querySelectorAll('.faq-item');
        faqItems.forEach(item => {
            const question = item.querySelector('.faq-question');
            const answer = item.querySelector('.faq-answer');
            const icon = item.querySelector('.faq-icon');

            question.addEventListener('click', () => {
                // Close other open answers
                faqItems.forEach(otherItem => {
                    if (otherItem !== item) {
                        const otherAnswer = otherItem.querySelector('.faq-answer');
                        const otherIcon = otherItem.querySelector('.faq-icon');
                        otherAnswer.style.maxHeight = '0px';
                        otherIcon.classList.remove('rotate-180');
                    }
                });

                // Toggle current answer
                const isOpen = answer.style.maxHeight && answer.style.maxHeight !== '0px';
                if (isOpen) {
                    answer.style.maxHeight = '0px';
                    icon.classList.remove('rotate-180');
                } else {
                    answer.style.maxHeight = answer.scrollHeight + 'px';
                    icon.classList.add('rotate-180');
                }
            });
        });

    </script>
</body>

</html>

