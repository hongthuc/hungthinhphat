<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG HƯNG THỊNH PHÁT | hungthinhphat.com</title>
    <meta name="description" content="CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG HƯNG THỊNH PHÁT - Chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện và nội thất trọn gói uy tín tại Đà Nẵng. Hotline: 0796 579 869.">

    <!-- =========================================================================
         META THUMBNAIL CHIA SẺ LINK (OG TAGS & TWITTER CARD) SỬ DỤNG LOGO CÔNG TY
         Lưu ý: Khi đưa lên hosting WordPress/Flatsome, hãy tải file logo PNG lên
         và cập nhật đường dẫn tuyệt đối tại thẻ og:image bên dưới.
         ========================================================================= -->
    <meta property="og:type" content="website">
    <meta property="og:locale" content="vi_VN">
    <meta property="og:site_name" content="Kiến Trúc Xây Dựng Hưng Thịnh Phát">
    <meta property="og:title" content="CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG HƯNG THỊNH PHÁT - Đà Nẵng">
    <meta property="og:description" content="Thiết kế Kiến trúc - Thi công xây dựng trọn gói - Nội thất nhà phố, biệt thự, căn hộ, khách sạn tại Đà Nẵng. Hotline: 0796 579 869.">
    <meta property="og:url" content="https://hungthinhphat.com/">
    <meta property="og:image" content="https://hungthinhphat.com/wp-content/uploads/logo-hungthinhphat-thumbnail.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG HƯNG THỊNH PHÁT">
    <meta name="twitter:description" content="Thiết kế - Xây dựng - Nội thất trọn gói tại Đà Nẵng. Địa chỉ: 4361/2 Âu Cơ, P. Liên Chiểu, TP Đà Nẵng.">
    <meta name="twitter:image" content="https://hungthinhphat.com/wp-content/uploads/logo-hungthinhphat-thumbnail.png">

    <!-- Favicon sử dụng biểu tượng Logo Hưng Thịnh Phát (SVG gọn nhẹ) -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='10' fill='%230F2942'/%3E%3Cpath d='M12 46V26L32 12L52 26V46H44V30L32 21L20 30V46H12Z' fill='%23C8922A'/%3E%3Crect x='27' y='32' width='10' height='14' fill='%23FFFFFF'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter tối ưu hiển thị tiếng Việt sắc nét -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        /* Bảng màu đồng bộ hoàn toàn theo Logo Hưng Thịnh Phát */
                        brand: {
                            navy: '#0F2942',       /* Xanh dương kiến trúc chủ đạo */
                            navyDark: '#091B2C',   /* Xanh đậm footer & hover */
                            navyLight: '#1A3E63',  /* Xanh phụ */
                            gold: '#C8922A',       /* Vàng đồng sang trọng */
                            goldLight: '#DFAC45',  /* Vàng sáng điểm nhấn */
                            goldBg: '#FBF6EC',     /* Nền vàng kem nhạt */
                        }
                    }
                }
            }
        }
    </script>

    <!-- Custom CSS tối ưu Flatsome layout, chống tràn viền 100% và chuẩn 95% trên máy tính -->
    <style>
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
            -webkit-font-smoothing: antialiased;
        }

        /* Khung chứa chuẩn 95% màn hình trên máy tính, 100% có padding an toàn trên điện thoại */
        .htp-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 768px) {
            .htp-container {
                width: 95%;
                max-width: 1680px;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu dropdown Flatsome đơn giản, mượt mà */
        .nav-item {
            position: relative;
        }
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }
        .nav-item:hover .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Đường gạch chân tiêu đề đặc trưng phong cách Flatsome */
        .section-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .section-heading::after {
            content: "";
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 56px;
            height: 3px;
            background-color: #C8922A;
            border-radius: 999px;
        }
        .section-heading-left::after {
            left: 0;
            transform: none;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi bật */
        @keyframes pulseRing {
            0% {
                box-shadow: 0 0 0 0 rgba(200, 146, 42, 0.55);
            }
            70% {
                box-shadow: 0 0 0 12px rgba(200, 146, 42, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(200, 146, 42, 0);
            }
        }
        .hotline-pulse {
            animation: pulseRing 2s infinite;
        }

        /* Banner tự trượt - đảm bảo 2 slide kích thước bằng nhau tuyệt đối */
        .banner-track {
            display: flex;
            width: 200%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .banner-slide {
            width: 50%;
            flex-shrink: 0;
            position: relative;
        }

        /* Chống tràn ảnh và iframe tuyệt đối */
        img, iframe, svg {
            max-width: 100%;
        }

        /* Tối ưu ảnh card giữ tỷ lệ đều đẹp giống Flatsome */
        .card-img-wrap {
            position: relative;
            width: 100%;
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #E2E8F0;
        }
        .card-img-wrap img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
            display: block;
        }
        .project-card:hover .card-img-wrap img {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="bg-white text-slate-800 pb-16 md:pb-0">

    <!-- =========================================================================
         1. TOP BAR ĐƠN GIẢN CHUẨN FLATSOME (KHÔNG CÓ THANH UXBUILDER)
         ========================================================================= -->
    <div class="bg-brand-navy text-slate-200 text-xs border-b border-white/10">
        <div class="htp-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                    <a href="tel:0796579869" class="hover:text-brand-gold transition font-medium">0796 579 869</a>
                </span>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                    <span>4361/2 Âu Cơ, Phường Liên Chiểu, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-3 text-slate-300">
                <span>hungthinhphat.com</span>
                <span class="text-white/30">|</span>
                <span>MST: 0402200175</span>
            </div>
        </div>
    </div>

    <!-- =========================================================================
         2. HEADER CHÍNH - LOGO GỌN NHỎ, MENU 1 HÀNG KHÔNG XUỐNG DÒNG, KHÔNG NÚT GỌI NGAY
         ========================================================================= -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="htp-container h-16 md:h-[70px] flex items-center justify-between gap-3">

            <!-- Logo Công Ty Chuyên Nghiệp (Thiết kế gọn nhỏ, sắc nét bằng SVG) -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Hưng Thịnh Phát Trang Chủ">
                <svg class="w-9 h-9 md:w-10 md:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="64" height="64" rx="10" fill="#0F2942"/>
                    <rect x="2" y="2" width="60" height="60" rx="8" stroke="#C8922A" stroke-width="2" stroke-opacity="0.75"/>
                    <!-- Biểu tượng kiến trúc mái nhà & trụ cột vững chãi -->
                    <path d="M12 45V27L32 13L52 27V45H45V30.5L32 21.5L19 30.5V45H12Z" fill="#C8922A"/>
                    <path d="M24 45V33H30V45H24Z" fill="#FFFFFF"/>
                    <path d="M34 45V29H40V45H34Z" fill="#FFFFFF" fill-opacity="0.9"/>
                    <rect x="11" y="48" width="42" height="3" rx="1.5" fill="#C8922A"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-[13px] md:text-[15px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition whitespace-nowrap">
                        HƯNG THỊNH PHÁT
                    </div>
                    <div class="text-[9.5px] md:text-[10px] font-semibold tracking-wider text-brand-gold uppercase whitespace-nowrap">
                        Kiến Trúc &amp; Xây Dựng
                    </div>
                </div>
            </a>

            <!-- Menu Desktop: Chữ nhỏ gọn, viết liền trên 1 hàng, tuyệt đối không xuống dòng -->
            <nav class="hidden lg:flex items-center justify-end flex-1 gap-1 xl:gap-2" aria-label="Menu chính">
                <a href="#trang-chu" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13.5px] font-semibold text-brand-navy hover:text-brand-gold transition whitespace-nowrap">
                    Trang chủ
                </a>
                <a href="#gioi-thieu" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">
                    Giới thiệu
                </a>

                <!-- Danh mục Công trình thực tế (giống web mẫu tintruongthinh.com) -->
                <div class="nav-item">
                    <a href="#cong-trinh" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap inline-flex items-center gap-1">
                        <span>Công trình thực tế</span>
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full w-56 bg-white border border-slate-200 rounded-lg shadow-lg py-1.5 z-50">
                        <a href="#cong-trinh" onclick="filterProjects('khach-san')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Khách sạn – Căn hộ – Phòng trọ</a>
                        <a href="#cong-trinh" onclick="filterProjects('biet-thu')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Biệt thự</a>
                        <a href="#cong-trinh" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Nhà phố</a>
                        <a href="#cong-trinh" onclick="filterProjects('van-phong')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Văn phòng</a>
                    </div>
                </div>

                <!-- Danh mục Lĩnh vực hoạt động -->
                <div class="nav-item">
                    <a href="#dich-vu" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap inline-flex items-center gap-1">
                        <span>Lĩnh vực hoạt động</span>
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full w-56 bg-white border border-slate-200 rounded-lg shadow-lg py-1.5 z-50">
                        <a href="#dich-vu" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Thiết kế Kiến trúc – Nội thất</a>
                        <a href="#cong-trinh" onclick="filterProjects('phan-tho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Thi công phần thô</a>
                        <a href="#cong-trinh" onclick="filterProjects('hoan-thien')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Thi công hoàn thiện</a>
                        <a href="#cong-trinh" onclick="filterProjects('noi-that')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Thi công nội thất</a>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">
                    Dự án Đà Nẵng
                </a>

                <div class="nav-item">
                    <a href="#bao-gia" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap inline-flex items-center gap-1">
                        <span>Báo giá</span>
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute right-0 top-full w-52 bg-white border border-slate-200 rounded-lg shadow-lg py-1.5 z-50">
                        <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Báo giá thiết kế kiến trúc</a>
                        <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Báo giá thi công phần thô</a>
                        <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Báo giá thi công hoàn thiện</a>
                        <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldBg hover:text-brand-navy">Báo giá thi công trọn gói</a>
                    </div>
                </div>

                <a href="#tin-tuc" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">
                    Tin tức
                </a>
                <a href="#lien-he" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">
                    Liên hệ
                </a>
            </nav>

            <!-- Nút Mở Menu trên Điện thoại / Tablet -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden p-2 rounded-lg text-brand-navy hover:bg-slate-100 focus:outline-none" aria-label="Mở menu">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
                </svg>
            </button>
        </div>

        <!-- Menu Di Động Dạng Xổ Xuống Gọn Đẹp -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-md">
            <div class="htp-container py-3 flex flex-col gap-1 text-sm font-medium text-slate-700">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg hover:bg-brand-goldBg hover:text-brand-navy">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg hover:bg-brand-goldBg hover:text-brand-navy">Giới thiệu công ty</a>
                <a href="#dich-vu" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg hover:bg-brand-goldBg hover:text-brand-navy">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg hover:bg-brand-goldBg hover:text-brand-navy">Công trình thi công thực tế</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg hover:bg-brand-goldBg hover:text-brand-navy">Dự án tại Đà Nẵng</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg hover:bg-brand-goldBg hover:text-brand-navy">Đối tác tiêu biểu</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg hover:bg-brand-goldBg hover:text-brand-navy">Yêu cầu &amp; Báo giá</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg hover:bg-brand-goldBg hover:text-brand-navy">Tin tức &amp; Kiến thức</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg hover:bg-brand-goldBg hover:text-brand-navy">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <!-- =========================================================================
         3. HAI ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP - KÍCH THƯỚC BẰNG NHAU TUYỆT ĐỐI
            CHỮ NẰM TRỌN TRONG BANNER, CÁCH XA VIỀN, KHÔNG MẤT CHỮ TRÊN ĐIỆN THOẠI & PC
         ========================================================================= -->
    <section id="trang-chu" class="w-full bg-brand-navy pt-3 pb-4 md:py-5">
        <div class="htp-container">
            <div id="heroSlider" class="relative w-full overflow-hidden rounded-xl shadow-lg bg-brand-navyDark">
                <!-- Khung trượt chứa đúng 2 banner kích thước đồng đều -->
                <div id="bannerTrack" class="banner-track">

                    <!-- BANNER 1 -->
                    <div class="banner-slide min-h-[290px] sm:min-h-[370px] md:min-h-[450px] lg:min-h-[500px] flex items-center">
                        <img
                            src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1400"
                            alt="Thi công xây dựng trọn gói Hưng Thịnh Phát Đà Nẵng"
                            class="absolute inset-0 w-full h-full object-cover"
                            onerror="this.onerror=function(){this.src='https://placehold.co/1400x520/0F2942/C8922A?text=HUNG+THINH+PHAT+CONSTRUCTION';}; this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1400';"
                        >
                        <!-- Lớp phủ màu đồng bộ thương hiệu giúp chữ rõ nét tuyệt đối -->
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/55"></div>

                        <!-- Vùng chữ cách xa 4 viền banner an toàn cho cả Mobile và Desktop -->
                        <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-14 md:px-24 md:py-16">
                            <div class="max-w-2xl">
                                <p class="text-[11px] sm:text-xs md:text-sm font-semibold tracking-widest uppercase text-brand-goldLight mb-2 sm:mb-3">
                                    CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG HƯNG THỊNH PHÁT
                                </p>
                                <h1 class="text-lg sm:text-2xl md:text-4xl font-extrabold text-white leading-snug mb-3 sm:mb-4">
                                    THIẾT KẾ KIẾN TRÚC &amp; THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                                    Cam kết An toàn – Chất lượng – Đúng tiến độ cho mọi công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng.
                                </p>
                                <div class="flex flex-wrap items-center gap-3">
                                    <a href="#bao-gia" class="inline-block bg-brand-gold hover:bg-brand-goldLight text-white text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg transition shadow">
                                        Nhận báo giá miễn phí
                                    </a>
                                    <a href="#cong-trinh" class="inline-block bg-white/15 hover:bg-white/25 text-white border border-white/40 text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg transition">
                                        Xem công trình thực tế
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 (Cùng chiều cao & căn lề an toàn tuyệt đối như Banner 1) -->
                    <div class="banner-slide min-h-[290px] sm:min-h-[370px] md:min-h-[450px] lg:min-h-[500px] flex items-center">
                        <img
                            src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1400"
                            alt="Kiến tạo không gian sống đẳng cấp Hưng Thịnh Phát"
                            class="absolute inset-0 w-full h-full object-cover"
                            onerror="this.onerror=function(){this.src='https://placehold.co/1400x520/0F2942/C8922A?text=DU+AN+DA+NANG+-+HUNG+THINH+PHAT';}; this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1400';"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/55"></div>

                        <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-14 md:px-24 md:py-16">
                            <div class="max-w-2xl">
                                <p class="text-[11px] sm:text-xs md:text-sm font-semibold tracking-widest uppercase text-brand-goldLight mb-2 sm:mb-3">
                                    GIẢI PHÁP KHÔNG GIAN BỀN VỮNG • HUNGTHINHPHAT.COM
                                </p>
                                <h2 class="text-lg sm:text-2xl md:text-4xl font-extrabold text-white leading-snug mb-3 sm:mb-4">
                                    THI CÔNG PHẦN THÔ, HOÀN THIỆN &amp; NỘI THẤT CHUẨN KỸ THUẬT
                                </h2>
                                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                                    Đội ngũ kỹ sư và kiến trúc sư tận tâm trực tiếp giám sát tại công trình, minh bạch vật tư, bảo hành kết cấu dài lâu.
                                </p>
                                <div class="flex flex-wrap items-center gap-3">
                                    <a href="#du-an-da-nang" class="inline-block bg-brand-gold hover:bg-brand-goldLight text-white text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg transition shadow">
                                        Xem dự án Đà Nẵng
                                    </a>
                                    <a href="tel:0796579869" class="inline-block bg-white/15 hover:bg-white/25 text-white border border-white/40 text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg transition">
                                        Tư vấn: 0796 579 869
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng Trái / Phải đặt sát mép ngoài, không che chữ -->
                <button id="prevBanner" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
                </button>
                <button id="nextBanner" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
                </button>

                <!-- Dấu chấm chỉ báo 2 banner đặt gọn sát đáy -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBanner(0)" id="dot0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-brand-gold transition-all"></button>
                    <button type="button" onclick="goToBanner(1)" id="dot1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         4. DỊCH VỤ TIÊU BIỂU (3 CỘT CHUẨN FLATSOME GIỐNG WEB MẪU TINTRUONGTHINH.COM)
         ========================================================================= -->
    <section id="dich-vu" class="py-10 md:py-14 bg-white">
        <div class="htp-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-xl md:text-2xl font-extrabold text-brand-navy uppercase">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Giải pháp đồng bộ từ khâu lên ý tưởng kiến trúc, thi công xây dựng phần thô đến hoàn thiện nội thất chìa khóa trao tay.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-5">
                <!-- Dịch vụ 1: Thiết kế -->
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-6 text-center hover:border-brand-gold hover:shadow-md transition">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center">
                        <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/></svg>
                    </div>
                    <h3 class="text-base font-bold text-brand-navy uppercase mb-2">Thiết Kế Kiến Trúc</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Thiết kế kiến trúc nhà phố, biệt thự, căn hộ, khách sạn và văn phòng tối ưu công năng, ánh sáng tự nhiên và thẩm mỹ bền vững.
                    </p>
                </div>

                <!-- Dịch vụ 2: Thi công -->
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-6 text-center hover:border-brand-gold hover:shadow-md transition">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center">
                        <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
                    </div>
                    <h3 class="text-base font-bold text-brand-navy uppercase mb-2">Thi Công Xây Dựng</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chuẩn kỹ thuật kết cấu, sử dụng vật tư chính hãng, đúng tiến độ cam kết.
                    </p>
                </div>

                <!-- Dịch vụ 3: Nội thất -->
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-6 text-center hover:border-brand-gold hover:shadow-md transition">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center">
                        <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 6a2 2 0 012-2h12a2 2 0 012 2v12a2 2 0 01-2 2H6a2 2 0 01-2-2V6zm4 4h8m-8 4h5"/></svg>
                    </div>
                    <h3 class="text-base font-bold text-brand-navy uppercase mb-2">Thi Công Nội Thất</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Sản xuất và lắp đặt nội thất phòng khách, bếp, phòng ngủ, văn phòng tinh tế, đồng bộ bản vẽ 3D với mức đầu tư hợp lý nhất.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         5. GIỚI THIỆU CÔNG TY & THẾ MẠNH (BỐ CỤC ĐƠN GIẢN DỄ DỰNG LẠI UXBUILDER)
         ========================================================================= -->
    <section id="gioi-thieu" class="py-10 md:py-14 bg-slate-50 border-y border-slate-200/80">
        <div class="htp-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center mb-10">
                <div class="lg:col-span-6">
                    <p class="text-xs font-bold uppercase tracking-wider text-brand-gold mb-2">Về chúng tôi</p>
                    <h2 class="section-heading section-heading-left text-xl md:text-2xl font-extrabold text-brand-navy uppercase mb-4">
                        CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG HƯNG THỊNH PHÁT
                    </h2>
                    <p class="text-sm text-slate-700 leading-relaxed mb-3">
                        <strong>Hưng Thịnh Phát</strong> chuyên Thiết kế Kiến trúc – Thi công xây dựng – Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực Đà Nẵng và miền Trung.
                    </p>
                    <p class="text-sm text-slate-700 leading-relaxed mb-5">
                        Với phương châm đặt chữ <strong>“TÂM”</strong> và uy tín nghề nghiệp lên hàng đầu, mỗi công trình do Hưng Thịnh Phát thực hiện đều đảm bảo 4 tiêu chuẩn cốt lõi: <strong>An toàn – Chất lượng – Tiến độ – Sự hài lòng của khách hàng</strong>.
                    </p>
                    <div class="grid grid-cols-3 gap-3 text-center">
                        <div class="bg-white rounded-lg p-3 border border-slate-200">
                            <div class="text-lg md:text-xl font-extrabold text-brand-navy">100%</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Vật tư chuẩn</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 border border-slate-200">
                            <div class="text-lg md:text-xl font-extrabold text-brand-gold">24/7</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Tư vấn miễn phí</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 border border-slate-200">
                            <div class="text-lg md:text-xl font-extrabold text-brand-navy">5 Năm</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Bảo hành kết cấu</div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-6">
                    <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
                        <img
                            src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w1000"
                            alt="Công trình thi công thực tế Hưng Thịnh Phát"
                            class="w-full h-64 sm:h-80 object-cover block"
                            onerror="this.onerror=function(){this.src='https://placehold.co/800x500/0F2942/C8922A?text=HUNG+THINH+PHAT';}; this.src='https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000';"
                        >
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh của chúng tôi -->
            <div class="text-center mb-6">
                <h3 class="section-heading text-lg md:text-xl font-extrabold text-brand-navy uppercase">
                    Thế Mạnh Của Chúng Tôi
                </h3>
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-goldBg text-brand-gold flex items-center justify-center shrink-0">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy mb-1">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Kỹ sư giàu kinh nghiệm trực tiếp chỉ huy công trường cùng tổ đội thợ lành nghề.</p>
                    </div>
                </div>
                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-goldBg text-brand-gold flex items-center justify-center shrink-0">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy mb-1">Cập nhật xu hướng kiến trúc hiện đại</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Áp dụng vật liệu mới, giải pháp chống nóng và phương pháp thi công tối ưu nhất.</p>
                    </div>
                </div>
                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-goldBg text-brand-gold flex items-center justify-center shrink-0">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy mb-1">Giám sát tiến độ chuẩn xác</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Báo cáo hình ảnh thi công hàng ngày giúp gia chủ dễ dàng theo dõi từ xa.</p>
                    </div>
                </div>
                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-goldBg text-brand-gold flex items-center justify-center shrink-0">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy mb-1">Bảo hành công trình lâu dài</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Chế độ hậu mãi nhanh chóng, đồng hành bảo trì suốt quá trình gia chủ sử dụng.</p>
                    </div>
                </div>
                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-goldBg text-brand-gold flex items-center justify-center shrink-0">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy mb-1">Chi phí minh bạch, không phát sinh</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục rõ ràng ngay từ đầu, tối ưu ngân sách chủ đầu tư.</p>
                    </div>
                </div>
                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-goldBg text-brand-gold flex items-center justify-center shrink-0">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-5 0a4 4 0 11-8 0 4 4 0 018 0z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">Hỗ trợ xin phép xây dựng, tư vấn phong thủy và giải pháp mặt bằng hoàn toàn miễn phí.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         6. CÔNG TRÌNH THI CÔNG THỰC TẾ (9 ẢNH THỰC TẾ TỪ GOOGLE DRIVE)
            DANH MỤC GỌN 1 HÀNG KHÔNG XUỐNG DÒNG TÊN DANH MỤC, LƯỚI 2 CỘT TRÊN MOBILE
            KHÔNG DÙNG NHÃN DÁN TRÊN ẢNH, TÊN SẢN PHẨM HIỂN THỊ ĐẦY ĐỦ KHÔNG THIẾU CHỮ
         ========================================================================= -->
    <section id="cong-trinh" class="py-10 md:py-14 bg-white">
        <div class="htp-container">
            <div class="text-center mb-6">
                <h2 class="section-heading text-xl md:text-2xl font-extrabold text-brand-navy uppercase">
                    Công Trình Thi Công Thực Tế
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Hình ảnh thực tế thi công phần thô, hoàn thiện và bàn giao công trình do Hưng Thịnh Phát trực tiếp thực hiện.
                </p>
            </div>

            <!-- Thanh Danh Mục Sản Phẩm / Công Trình (Lấy theo web mẫu tintruongthinh.com)
                 Chữ nhỏ gọn, từng tên danh mục viết liền trên 1 hàng không gãy chữ -->
            <div id="categoryTabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
                <button type="button" data-cat="all" onclick="filterProjects('all')" class="cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-brand-navy text-white border-brand-navy">
                    Tất cả
                </button>
                <button type="button" data-cat="nha-pho" onclick="filterProjects('nha-pho')" class="cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-white text-slate-700 border-slate-300 hover:border-brand-navy hover:text-brand-navy">
                    Nhà phố
                </button>
                <button type="button" data-cat="biet-thu" onclick="filterProjects('biet-thu')" class="cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-white text-slate-700 border-slate-300 hover:border-brand-navy hover:text-brand-navy">
                    Biệt thự
                </button>
                <button type="button" data-cat="khach-san" onclick="filterProjects('khach-san')" class="cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-white text-slate-700 border-slate-300 hover:border-brand-navy hover:text-brand-navy">
                    Khách sạn - Căn hộ - Phòng trọ
                </button>
                <button type="button" data-cat="van-phong" onclick="filterProjects('van-phong')" class="cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-white text-slate-700 border-slate-300 hover:border-brand-navy hover:text-brand-navy">
                    Văn phòng
                </button>
                <button type="button" data-cat="phan-tho" onclick="filterProjects('phan-tho')" class="cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-white text-slate-700 border-slate-300 hover:border-brand-navy hover:text-brand-navy">
                    Thi công phần thô
                </button>
                <button type="button" data-cat="hoan-thien" onclick="filterProjects('hoan-thien')" class="cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-white text-slate-700 border-slate-300 hover:border-brand-navy hover:text-brand-navy">
                    Thi công hoàn thiện
                </button>
                <button type="button" data-cat="noi-that" onclick="filterProjects('noi-that')" class="cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-white text-slate-700 border-slate-300 hover:border-brand-navy hover:text-brand-navy">
                    Thi công nội thất
                </button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3-4 cột trên máy tính -->
            <div id="constructionGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Dữ liệu 9 ảnh thi công thực tế được render sạch qua JavaScript bên dưới -->
            </div>
        </div>
    </section>

    <!-- =========================================================================
         7. DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH DỰ ÁN TỪ GOOGLE DRIVE)
            CHIA 2 CỘT TRÊN ĐIỆN THOẠI, KHÔNG NHÃN DÁN, HIỂN THỊ ĐỦ TÊN DỰ ÁN
         ========================================================================= -->
    <section id="du-an-da-nang" class="py-10 md:py-14 bg-slate-50 border-y border-slate-200/80">
        <div class="htp-container">
            <div class="text-center mb-7">
                <h2 class="section-heading text-xl md:text-2xl font-extrabold text-brand-navy uppercase">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Tổng hợp các công trình nhà ở, biệt thự, căn hộ và văn phòng Hưng Thịnh Phát đã thiết kế và thi công tại các quận Liên Chiểu, Hải Châu, Sơn Trà, Cẩm Lệ, Ngũ Hành Sơn, Thanh Khê.
                </p>
            </div>

            <!-- Lưới 2 cột trên điện thoại, 3 cột tablet, 5 cột trên máy tính để 10 dự án chia 2 hàng đều đẹp -->
            <div id="daNangGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Dữ liệu 10 dự án Đà Nẵng được render sạch qua JavaScript bên dưới -->
            </div>
        </div>
    </section>

    <!-- =========================================================================
         8. DANH MỤC CÁC ĐỐI TÁC CUNG ỨNG VẬT TƯ & XÂY DỰNG
         ========================================================================= -->
    <section id="doi-tac" class="py-10 md:py-12 bg-white">
        <div class="htp-container">
            <div class="text-center mb-7">
                <h2 class="section-heading text-xl md:text-2xl font-extrabold text-brand-navy uppercase">
                    Đối Tác Tiêu Biểu
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-xl mx-auto">
                    Hưng Thịnh Phát cam kết đồng hành cùng các thương hiệu vật liệu xây dựng hàng đầu, đảm bảo độ bền vượt thời gian cho công trình.
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm font-extrabold tracking-tight text-brand-navy">HÒA PHÁT</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thép Xây Dựng</span>
                </div>
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm font-extrabold tracking-tight text-brand-navy">SÔNG GIANH</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Xi Măng Cao Cấp</span>
                </div>
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm font-extrabold tracking-tight text-brand-navy">DULUX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn Nội Ngoại Thất</span>
                </div>
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm font-extrabold tracking-tight text-brand-navy">ĐỒNG TÂM</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gạch Ốp Lát</span>
                </div>
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm font-extrabold tracking-tight text-brand-navy">XINGFA</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Cửa Nhôm Kính</span>
                </div>
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm font-extrabold tracking-tight text-brand-navy">INAX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thiết Bị Vệ Sinh</span>
                </div>
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm font-extrabold tracking-tight text-brand-navy">AN CƯỜNG</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gỗ Nội Thất</span>
                </div>
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm font-extrabold tracking-tight text-brand-navy">CADIVI</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Dây Cáp Điện</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         9. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (THEO BỐ CỤC TINTRUONGTHINH.COM)
         ========================================================================= -->
    <section id="bao-gia" class="py-10 md:py-14 bg-brand-navy text-white">
        <div class="htp-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <!-- Cột thông tin cam kết báo giá -->
                <div class="lg:col-span-5">
                    <p class="text-xs font-bold uppercase tracking-widest text-brand-goldLight mb-2">Miễn phí tư vấn &amp; khái toán</p>
                    <h2 class="text-xl md:text-2xl font-extrabold uppercase leading-snug mb-4">
                        Đăng Ký Yêu Cầu Tư Vấn &amp; Nhận Báo Giá Chi Tiết
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-5">
                        Quý khách đang có kế hoạch xây dựng nhà phố, biệt thự, căn hộ cho thuê hay cải tạo văn phòng tại Đà Nẵng? Hãy để lại thông tin, kỹ sư Hưng Thịnh Phát sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết trong vòng 24 giờ.
                    </p>
                    <div class="space-y-3 text-xs sm:text-sm text-slate-200">
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-goldLight flex items-center justify-center shrink-0">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                            </span>
                            <span>Hotline / Zalo: <strong class="text-white">0796 579 869</strong></span>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-goldLight flex items-center justify-center shrink-0">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                            </span>
                            <span>4361/2 Âu Cơ, Phường Liên Chiểu, TP Đà Nẵng</span>
                        </div>
                    </div>
                </div>

                <!-- Cột Form nhập liệu gọn đẹp -->
                <div class="lg:col-span-7">
                    <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên của quý khách" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại *</label>
                                <input id="qPhone" type="tel" required placeholder="Nhập số điện thoại liên hệ" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                            </div>
                            <div>
                                <label for="qType" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                                <select id="qType" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-brand-navy">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Thi công nội thất">Thi công nội thất</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label for="qBudget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-brand-navy">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                            <div class="sm:col-span-2">
                                <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Yêu cầu chi tiết (diện tích đất, số tầng, khu vực...)</label>
                                <textarea id="qNote" rows="3" placeholder="Ví dụ: Xây nhà phố 3 tầng diện tích 5x20m tại Liên Chiểu, Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-navy"></textarea>
                            </div>
                        </div>

                        <!-- Hộp thông báo phản hồi ngay trên form (không dùng alert) -->
                        <div id="formFeedback" class="hidden mt-4 p-3.5 rounded-lg text-xs sm:text-sm font-medium"></div>

                        <div class="mt-5">
                            <button type="submit" class="w-full sm:w-auto px-7 py-3 bg-brand-gold hover:bg-brand-goldLight text-white text-sm font-bold rounded-lg transition shadow">
                                Gửi Yêu Cầu Báo Giá Ngay
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         10. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & CẨM NANG XÂY DỰNG)
         ========================================================================= -->
    <section id="tin-tuc" class="py-10 md:py-14 bg-white">
        <div class="htp-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-xl md:text-2xl font-extrabold text-brand-navy uppercase">
                    Tin Tức &amp; Cẩm Nang Xây Dựng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Chia sẻ kiến thức thực tế về thiết kế kiến trúc, kỹ thuật thi công và kinh nghiệm xây dựng nhà đẹp tại Đà Nẵng.
                </p>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Bài viết 1 -->
                <article onclick="openArticle(0)" class="project-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="card-img-wrap">
                        <img src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w800" alt="Hướng dẫn bảo dưỡng bê tông móng đúng kỹ thuật" onerror="this.onerror=function(){this.src='https://placehold.co/600x450/0F2942/C8922A?text=Bao+Duong+Be+Tong';}; this.src='https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800';">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col">
                        <div class="text-[11px] text-brand-gold font-semibold mb-1">Kỹ thuật thi công</div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy leading-snug mb-2 break-words">
                            Hướng dẫn bảo dưỡng bê tông móng đúng chuẩn kỹ thuật
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed flex-1">
                            Quy trình giữ ẩm và kiểm tra cường độ bê tông giúp nền móng ngôi nhà đạt độ bền vững tối đa.
                        </p>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article onclick="openArticle(1)" class="project-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="card-img-wrap">
                        <img src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w800" alt="Kinh nghiệm xây nhà trọn gói không phát sinh chi phí" onerror="this.onerror=function(){this.src='https://placehold.co/600x450/0F2942/C8922A?text=Xay+Nha+Tron+Goi';}; this.src='https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800';">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col">
                        <div class="text-[11px] text-brand-gold font-semibold mb-1">Kinh nghiệm xây nhà</div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy leading-snug mb-2 break-words">
                            3 lưu ý quan trọng khi xây nhà trọn gói tại Đà Nẵng
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed flex-1">
                            Cách kiểm soát ngân sách, chọn nhà thầu uy tín và nghiệm thu từng giai đoạn thi công minh bạch.
                        </p>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article onclick="openArticle(2)" class="project-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="card-img-wrap">
                        <img src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w800" alt="Thiết kế nội thất tối ưu không gian nhà phố" onerror="this.onerror=function(){this.src='https://placehold.co/600x450/0F2942/C8922A?text=Thiet+Ke+Noi+That';}; this.src='https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800';">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col">
                        <div class="text-[11px] text-brand-gold font-semibold mb-1">Kiến trúc – Nội thất</div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy leading-snug mb-2 break-words">
                            Tối ưu ánh sáng và thông gió tự nhiên cho nhà phố hiện đại
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed flex-1">
                            Giải pháp giếng trời và bố trí nội thất khoa học mang lại cảm giác rộng thoáng cho nhà ống.
                        </p>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article onclick="openArticle(3)" class="project-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="card-img-wrap">
                        <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w800" alt="Bảng giá thiết kế và thi công xây dựng mới nhất" onerror="this.onerror=function(){this.src='https://placehold.co/600x450/0F2942/C8922A?text=Bao+Gia+Xay+Dung';}; this.src='https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800';">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col">
                        <div class="text-[11px] text-brand-gold font-semibold mb-1">Báo giá tham khảo</div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy leading-snug mb-2 break-words">
                            Đơn giá thi công phần thô và hoàn thiện nhà ở mới nhất
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed flex-1">
                            Cách tính diện tích xây dựng theo m2 sàn, phần móng, mái và danh mục vật liệu hoàn thiện đi kèm.
                        </p>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         11. BẢN ĐỒ GOOGLE MAPS & FANPAGE CHÍNH THỨC NGOÀI TRANG CHỦ
         ========================================================================= -->
    <section id="lien-he" class="py-10 md:py-14 bg-slate-50 border-t border-slate-200">
        <div class="htp-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-xl md:text-2xl font-extrabold text-brand-navy uppercase">
                    Bản Đồ Chỉ Đường &amp; Fanpage Công Ty
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Địa chỉ văn phòng: 4361/2 Âu Cơ, Phường Liên Chiểu, TP Đà Nẵng • Hotline: 0796 579 869
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột Trái: Ảnh / Bản Đồ Google Map thực tế đưa ra ngoài trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="px-4 py-3 bg-brand-navy text-white flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-semibold">
                            <svg class="w-4 h-4 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                            <span>Vị Trí Công Ty Trên Google Maps</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=4361%2F2+Au+Co+Lien+Chieu+Da+Nang" target="_blank" rel="noopener noreferrer" class="text-[11px] sm:text-xs text-brand-goldLight hover:underline whitespace-nowrap">
                            Mở bản đồ lớn →
                        </a>
                    </div>
                    <div class="w-full h-[300px] sm:h-[340px] flex-1 bg-slate-100">
                        <iframe
                            title="Bản đồ Công ty TNHH Kiến Trúc Xây Dựng Hưng Thịnh Phát - 4361/2 Âu Cơ, Liên Chiểu, Đà Nẵng"
                            src="https://maps.google.com/maps?q=Au%20Co,%20Lien%20Chieu,%20Da%20Nang,%20Vietnam&t=&z=15&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0 block"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen>
                        </iframe>
                    </div>
                </div>

                <!-- Cột Phải: Fanpage Facebook Đưa Ra Ngoài Trang Chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-semibold">
                            <svg class="w-4 h-4 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                            <span>Fanpage Facebook Chính Thức</span>
                        </div>
                        <span class="text-[11px] bg-white/20 px-2 py-0.5 rounded">Trực tuyến</span>
                    </div>

                    <!-- Khối hiển thị Fanpage trực quan, tải nhanh, không bị chặn trình duyệt -->
                    <div class="relative h-36 bg-brand-navy overflow-hidden">
                        <img
                            src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800"
                            alt="Ảnh bìa Fanpage Kiến Trúc Xây Dựng Hưng Thịnh Phát"
                            class="w-full h-full object-cover opacity-80"
                            onerror="this.onerror=function(){this.src='https://placehold.co/800x300/0F2942/C8922A?text=FANPAGE+HUNG+THINH+PHAT';}; this.src='https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800';"
                        >
                        <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/30 to-transparent"></div>
                        <div class="absolute bottom-3 left-4 right-4 flex items-center gap-3">
                            <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white shadow flex items-center justify-center shrink-0">
                                <svg class="w-9 h-9" viewBox="0 0 64 64" fill="none">
                                    <path d="M12 45V27L32 13L52 27V45H45V30.5L32 21.5L19 30.5V45H12Z" fill="#C8922A"/>
                                    <rect x="25" y="32" width="14" height="13" fill="#FFFFFF"/>
                                </svg>
                            </div>
                            <div class="min-w-0 text-white">
                                <h3 class="text-sm font-bold leading-tight">Kiến Trúc Xây Dựng Hưng Thịnh Phát</h3>
                                <p class="text-[11px] text-slate-200 mt-0.5">Thiết kế &amp; Thi công trọn gói Đà Nẵng</p>
                            </div>
                        </div>
                    </div>

                    <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                        <div class="text-xs text-slate-600 leading-relaxed space-y-2">
                            <p>Theo dõi Fanpage <strong>Kiến Trúc Xây Dựng Hưng Thịnh Phát</strong> để cập nhật hình ảnh thi công công trình mới mỗi ngày, mẫu nhà đẹp và ưu đãi miễn phí thiết kế khi xây nhà trọn gói.</p>
                            <div class="bg-slate-50 border border-slate-200 rounded-lg p-3 text-[11.5px] text-slate-700">
                                <div class="font-semibold text-brand-navy mb-1">Cập nhật mới nhất tại công trường Đà Nẵng:</div>
                                <p>Bàn giao công trình nhà phố 3 tầng hiện đại tại Quận Liên Chiểu đúng tiến độ, gia chủ hài lòng 100% về chất lượng hoàn thiện.</p>
                            </div>
                        </div>

                        <div class="grid grid-cols-2 gap-2.5">
                            <a href="https://www.facebook.com/search/top?q=Kien+Truc+Xay+Dung+Hung+Thinh+Phat+Da+Nang" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 px-3 bg-[#1877F2] hover:bg-[#1465D1] text-white text-xs font-semibold rounded-lg transition">
                                <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                                <span>Theo dõi Trang</span>
                            </a>
                            <a href="https://zalo.me/0796579869" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 px-3 bg-brand-navy hover:bg-brand-navyLight text-white text-xs font-semibold rounded-lg transition">
                                <span>Nhắn tin tư vấn</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         12. FOOTER CHUẨN FLATSOME ĐỒNG BỘ MÀU LOGO
         ========================================================================= -->
    <footer class="bg-brand-navyDark text-slate-300 pt-10 pb-8 border-t-4 border-brand-gold">
        <div class="htp-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin doanh nghiệp -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-2.5 mb-4">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none">
                            <rect width="64" height="64" rx="10" fill="#0F2942"/>
                            <rect x="2" y="2" width="60" height="60" rx="8" stroke="#C8922A" stroke-width="2"/>
                            <path d="M12 45V27L32 13L52 27V45H45V30.5L32 21.5L19 30.5V45H12Z" fill="#C8922A"/>
                            <rect x="26" y="32" width="12" height="13" fill="#FFFFFF"/>
                        </svg>
                        <div>
                            <div class="text-sm font-extrabold text-white">CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG HƯNG THỊNH PHÁT</div>
                            <div class="text-[11px] text-brand-goldLight font-medium">Website: hungthinhphat.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><strong class="text-white">Địa chỉ:</strong> 4361/2 Âu Cơ, Phường Liên Chiểu, TP Đà Nẵng</li>
                        <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0796579869" class="text-brand-goldLight hover:underline font-semibold">0796 579 869</a></li>
                        <li><strong class="text-white">Mã số thuế:</strong> 0402200175</li>
                        <li><strong class="text-white">Website:</strong> hungthinhphat.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="text-sm font-bold text-white uppercase mb-3 border-b border-brand-gold/50 pb-1.5 inline-block">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#dich-vu" class="hover:text-brand-goldLight transition">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('phan-tho')" class="hover:text-brand-goldLight transition">Thi công phần thô</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('hoan-thien')" class="hover:text-brand-goldLight transition">Thi công hoàn thiện</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('noi-that')" class="hover:text-brand-goldLight transition">Thi công nội thất trọn gói</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm & Báo giá -->
                <div class="lg:col-span-4">
                    <h4 class="text-sm font-bold text-white uppercase mb-3 border-b border-brand-gold/50 pb-1.5 inline-block">
                        Danh Mục Công Trình &amp; Hỗ Trợ
                    </h4>
                    <ul class="grid grid-cols-2 gap-y-2 gap-x-3 text-xs sm:text-sm">
                        <li><a href="#cong-trinh" onclick="filterProjects('nha-pho')" class="hover:text-brand-goldLight transition">Nhà phố hiện đại</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('biet-thu')" class="hover:text-brand-goldLight transition">Biệt thự cao cấp</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('khach-san')" class="hover:text-brand-goldLight transition">Khách sạn – Căn hộ</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('van-phong')" class="hover:text-brand-goldLight transition">Văn phòng công ty</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-goldLight transition">Dự án tại Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition">Đăng ký báo giá</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                Copyright 2026 © CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG HƯNG THỊNH PHÁT (hungthinhphat.com). All rights reserved.
            </div>
        </div>
    </footer>

    <!-- =========================================================================
         13. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
             TƯƠNG THÍCH HOÀN HẢO TRÊN MÁY TÍNH (NỔI GÓC PHẢI) VÀ ĐIỆN THOẠI (THANH ĐÁY)
         ========================================================================= -->
    <!-- Phiên bản Máy Tính (Desktop Floating Dock góc dưới bên phải) -->
    <div class="hidden md:flex fixed right-4 bottom-6 z-50 flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/search/top?q=Kien+Truc+Xay+Dung+Hung+Thinh+Phat+Da+Nang" target="_blank" rel="noopener noreferrer" aria-label="Facebook Hưng Thịnh Phát" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D1] text-white px-3.5 py-2.5 rounded-full shadow-lg transition">
            <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0796579869" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0796579869" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white px-3.5 py-2.5 rounded-full shadow-lg transition">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] text-[10px] font-black flex items-center justify-center shrink-0">Z</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Hotline nổi bật có hiệu ứng sóng -->
        <a href="tel:0796579869" aria-label="Gọi Hotline 0796579869" class="hotline-pulse flex items-center gap-2 bg-brand-gold hover:bg-brand-goldLight text-white px-4 py-2.5 rounded-full shadow-lg transition">
            <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            <span class="text-xs font-extrabold whitespace-nowrap">0796 579 869</span>
        </a>
    </div>

    <!-- Phiên bản Điện Thoại (Thanh liên hệ 3 nút cố định gọn đẹp ở đáy màn hình, không tràn viền) -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-slate-200 shadow-[0_-4px_12px_rgba(0,0,0,0.08)] px-2 py-2">
        <div class="grid grid-cols-3 gap-2">
            <a href="tel:0796579869" class="flex items-center justify-center gap-1.5 bg-brand-gold text-white py-2.5 px-2 rounded-lg text-xs font-bold shadow-sm active:scale-95 transition">
                <svg class="w-4 h-4 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                <span class="whitespace-nowrap">Hotline</span>
            </a>
            <a href="https://zalo.me/0796579869" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 bg-[#0068FF] text-white py-2.5 px-2 rounded-lg text-xs font-bold shadow-sm active:scale-95 transition">
                <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] text-[9px] font-black flex items-center justify-center shrink-0">Z</span>
                <span class="whitespace-nowrap">Zalo</span>
            </a>
            <a href="https://www.facebook.com/search/top?q=Kien+Truc+Xay+Dung+Hung+Thinh+Phat+Da+Nang" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 bg-[#1877F2] text-white py-2.5 px-2 rounded-lg text-xs font-bold shadow-sm active:scale-95 transition">
                <svg class="w-4 h-4 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                <span class="whitespace-nowrap">Facebook</span>
            </a>
        </div>
    </div>

    <!-- =========================================================================
         14. MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH & BÀI VIẾT (GỌN ĐẸP, KHÔNG DÙNG ALERT)
         ========================================================================= -->
    <div id="detailModal" class="hidden fixed inset-0 z-[60] bg-black/70 backdrop-blur-xs flex items-center justify-center p-4" onclick="closeModalOnBackdrop(event)">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
            <button type="button" onclick="closeDetailModal()" aria-label="Đóng" class="absolute top-3 right-3 z-10 w-8 h-8 rounded-full bg-black/50 hover:bg-brand-navy text-white flex items-center justify-center transition">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>
            <div id="modalImageWrap" class="w-full bg-slate-100">
                <img id="modalImg" src="" alt="" class="w-full max-h-[420px] object-cover block">
            </div>
            <div class="p-5 sm:p-6">
                <div id="modalCategory" class="text-xs font-bold text-brand-gold uppercase mb-1"></div>
                <h3 id="modalTitle" class="text-base sm:text-lg font-extrabold text-brand-navy mb-2"></h3>
                <p id="modalDesc" class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4"></p>
                <div class="flex flex-wrap items-center gap-3 pt-2 border-t border-slate-100">
                    <a href="#bao-gia" onclick="closeDetailModal()" class="px-4 py-2 bg-brand-gold hover:bg-brand-goldLight text-white text-xs sm:text-sm font-semibold rounded-lg transition">
                        Yêu cầu báo giá mẫu này
                    </a>
                    <a href="tel:0796579869" class="px-4 py-2 bg-brand-navy hover:bg-brand-navyLight text-white text-xs sm:text-sm font-semibold rounded-lg transition">
                        Gọi: 0796 579 869
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- =========================================================================
         15. JAVASCRIPT ĐIỀU KHIỂN BANNER, DỮ LIỆU GOOGLE DRIVE, BỘ LỌC & FORM
         ========================================================================= -->
    <script>
        /* =====================================================================
           A. HÀM TẠO LINK ẢNH GOOGLE DRIVE ỔN ĐỊNH + FALLBACK TỰ ĐỘNG
           ===================================================================== */
        function getDriveImg(fileId) {
            return `https://lh3.googleusercontent.com/d/${fileId}=w1000`;
        }

        function getDriveFallback(fileId, label) {
            const safeLabel = encodeURIComponent(label || 'Hung Thinh Phat');
            return `this.onerror=function(){this.src='https://placehold.co/800x600/0F2942/C8922A?text=${safeLabel}';}; this.src='https://drive.google.com/thumbnail?id=${fileId}&sz=w1000';`;
        }

        /* =====================================================================
           B. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (PHÂN LOẠI CHUẨN WEB MẪU)
           ===================================================================== */
        const constructionProjects = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô Nhà Phố 3 Tầng Hiện Đại',
                categoryName: 'Nhà phố • Thi công phần thô',
                cats: ['nha-pho', 'phan-tho'],
                desc: 'Hạng mục thi công khung kết cấu bê tông cốt thép, xây tường gạch chuẩn kỹ thuật và kiểm định độ phẳng nghiêm ngặt tại công trường.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Căn Hộ Cho Thuê Tiêu Chuẩn Cao',
                categoryName: 'Khách sạn - Căn hộ - Phòng trọ',
                cats: ['khach-san', 'hoan-thien'],
                desc: 'Thiết kế và thi công trọn gói tòa nhà căn hộ dịch vụ tối ưu công năng khai thác, hệ thống điện nước âm tường an toàn tuyệt đối.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thiết Kế & Thi Công Biệt Thự 2 Mặt Tiền',
                categoryName: 'Biệt thự • Thi công trọn gói',
                cats: ['biet-thu', 'hoan-thien'],
                desc: 'Công trình biệt thự kiến trúc hiện đại với hình khối sắc nét, vật liệu mặt tiền bền đẹp theo khí hậu miền Trung.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Hoàn Thiện Nhà Phố Mặt Tiền 5m',
                categoryName: 'Nhà phố • Thi công hoàn thiện',
                cats: ['nha-pho', 'hoan-thien'],
                desc: 'Hoàn thiện ốp lát, sơn nước cao cấp, lắp đặt cửa nhôm kính và hệ thống chiếu sáng đồng bộ theo đúng bản vẽ thiết kế.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Kết Cấu Móng & Khung Bê Tông Cốt Thép',
                categoryName: 'Thi công phần thô',
                cats: ['phan-tho', 'nha-pho'],
                desc: 'Gia công lắp dựng cốt thép đúng chủng loại thiết kế, giám sát đổ bê tông tươi và bảo dưỡng liên tục đảm bảo kết cấu vững chắc.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Nội Thất Trọn Gói Phòng Khách - Bếp',
                categoryName: 'Thi công nội thất',
                cats: ['noi-that'],
                desc: 'Thi công hoàn thiện nội thất gỗ công nghiệp chống ẩm cao cấp, tối ưu không gian sinh hoạt ấm cúng và tiện nghi.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thiết Kế & Thi Công Văn Phòng Làm Việc Hiện Đại',
                categoryName: 'Văn phòng • Thi công nội thất',
                cats: ['van-phong', 'noi-that'],
                desc: 'Không gian văn phòng chuyên nghiệp, tối ưu ánh sáng và bố trí phòng họp, khu làm việc khoa học cho doanh nghiệp.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Hoàn Thiện Khách Sạn Mini & Homestay',
                categoryName: 'Khách sạn - Căn hộ - Phòng trọ',
                cats: ['khach-san', 'hoan-thien'],
                desc: 'Thi công trọn gói công trình lưu trú phong cách hiện đại, tối ưu suất đầu tư và đảm bảo tiến độ khai trương cho chủ đầu tư.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Thi Công Trọn Gói Biệt Thự Sân Vườn Sang Trọng',
                categoryName: 'Biệt thự • Thi công trọn gói',
                cats: ['biet-thu', 'phan-tho', 'hoan-thien'],
                desc: 'Thi công đồng bộ từ phần móng, kết cấu, hoàn thiện kiến trúc đến tiểu cảnh sân vườn thoáng mát cho gia đình.'
            }
        ];

        /* =====================================================================
           C. DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (GOOGLE DRIVE)
           ===================================================================== */
        const daNangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Nhà Phố Hiện Đại 3 Tầng - Quận Liên Chiểu, Đà Nẵng',
                area: 'Quận Liên Chiểu, Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng thiết kế mặt tiền thoáng đẹp, thi công trọn gói bởi đội ngũ kỹ sư Hưng Thịnh Phát.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Biệt Thự Phố Sang Trọng - Khu Đô Thị Hòa Xuân, Đà Nẵng',
                area: 'Hòa Xuân, Cẩm Lệ, Đà Nẵng',
                desc: 'Biệt thự phố kiến trúc tối giản sang trọng, tối ưu không gian xanh và ánh sáng tự nhiên tại Khu đô thị Hòa Xuân.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Căn Hộ Dịch Vụ Cho Thuê - Quận Sơn Trà, Đà Nẵng',
                area: 'Quận Sơn Trà, Đà Nẵng',
                desc: 'Tòa nhà căn hộ cho thuê cao cấp gần biển, tối ưu số lượng phòng và hệ thống phòng cháy chữa cháy đạt chuẩn.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Nhà Phố Kết Hợp Kinh Doanh - Đường Âu Cơ, Liên Chiểu',
                area: 'Phường Liên Chiểu, Đà Nẵng',
                desc: 'Thiết kế tầng trệt thông thoáng phục vụ kinh doanh kết hợp không gian sinh hoạt riêng tư tiện nghi ở các tầng trên.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Thi Công Trọn Gói Nhà Anh Minh - Quận Cẩm Lệ, Đà Nẵng',
                area: 'Quận Cẩm Lệ, Đà Nẵng',
                desc: 'Dự án xây nhà trọn gói chìa khóa trao tay, bàn giao đúng tiến độ cam kết và không phát sinh chi phí.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Khách Sạn Boutique Biển - Quận Ngũ Hành Sơn, Đà Nẵng',
                area: 'Quận Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Công trình khách sạn lưu trú kiến trúc tinh tế, vật liệu hoàn thiện chống ăn mòn vùng ven biển Đà Nẵng.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Nhà Phố 2 Mặt Tiền - Khu Đô Thị Phước Lý, Đà Nẵng',
                area: 'Phước Lý, Liên Chiểu, Đà Nẵng',
                desc: 'Thiết kế kiến trúc khai thác tối đa lợi thế lô góc 2 mặt tiền, tạo điểm nhấn nổi bật cho toàn tuyến phố.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Văn Phòng Công Ty Thương Mại - Quận Hải Châu, Đà Nẵng',
                area: 'Quận Hải Châu, Đà Nẵng',
                desc: 'Thi công hoàn thiện mặt tiền kính và không gian văn phòng làm việc hiện đại ngay trung tâm thành phố Đà Nẵng.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Thi Công Nhà Ở Gia Đình - Khu Nam Việt Á, Đà Nẵng',
                area: 'Nam Việt Á, Ngũ Hành Sơn',
                desc: 'Ngôi nhà gia đình thiết kế khoa học với 4 phòng ngủ, phòng thờ và sân thượng thư giãn xanh mát.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Biệt Thự Nghỉ Dưỡng Sân Vườn - Quận Thanh Khê, Đà Nẵng',
                area: 'Quận Thanh Khê, Đà Nẵng',
                desc: 'Biệt thự sân vườn sang trọng kết hợp nội thất tinh tế, mang lại không gian nghỉ ngơi lý tưởng cho gia đình.'
            }
        ];

        /* =====================================================================
           D. DỮ LIỆU CHI TIẾT BÀI VIẾT TRANG CHỦ
           ===================================================================== */
        const articlesData = [
            {
                category: 'Kỹ thuật thi công',
                title: 'Hướng dẫn bảo dưỡng bê tông móng đúng chuẩn kỹ thuật',
                imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                desc: 'Sau khi đổ bê tông móng khoảng 4–6 giờ (khi bề mặt bắt đầu se cứng), cần tiến hành tưới nước giữ ẩm liên tục trong tối thiểu 7 ngày đầu tiên, đặc biệt trong điều kiện thời tiết nắng nóng tại Đà Nẵng. Việc che phủ bằng bao tải ẩm hoặc nilon giúp hạn chế hiện tượng nứt co ngót dẻo và giúp bê tông đạt đúng mác thiết kế.'
            },
            {
                category: 'Kinh nghiệm xây nhà',
                title: '3 lưu ý quan trọng khi xây nhà trọn gói tại Đà Nẵng',
                imgId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                desc: 'Thứ nhất: Chuẩn bị hồ sơ thiết kế chi tiết kiến trúc, kết cấu và điện nước trước khi khởi công để tránh đập phá sửa đổi. Thứ hai: Bảng chủng loại vật tư phần thô và hoàn thiện phải ghi rõ thương hiệu, quy cách trong hợp đồng. Thứ ba: Chọn đơn vị thi công có kỹ sư giám sát trực tiếp và chế độ bảo hành rõ ràng.'
            },
            {
                category: 'Kiến trúc – Nội thất',
                title: 'Tối ưu ánh sáng và thông gió tự nhiên cho nhà phố hiện đại',
                imgId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                desc: 'Với đặc trưng nhà phố có chiều sâu lớn, việc bố trí giếng trời tại khu vực cầu thang và khoảng thông tầng phía sau giúp luồng khí nóng thoát lên trên, tạo đối lưu gió mát mẻ quanh năm. Kết hợp hệ cửa kính lớn và lam chắn nắng giúp giảm đáng kể chi phí điện năng.'
            },
            {
                category: 'Báo giá tham khảo',
                title: 'Đơn giá thi công phần thô và hoàn thiện nhà ở mới nhất',
                imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                desc: 'Đơn giá xây dựng phụ thuộc vào quy mô diện tích sàn, điều kiện hẻm vận chuyển vật tư, phong cách kiến trúc (hiện đại hay tân cổ điển) và gói vật liệu hoàn thiện. Liên hệ ngay Hưng Thịnh Phát qua Hotline 0796 579 869 để được kỹ sư khảo sát thực tế và lập bảng dự toán chi tiết miễn phí.'
            }
        ];

        /* =====================================================================
           E. RENDER DANH SÁCH CÔNG TRÌNH THỰC TẾ & LỌC DANH MỤC
           ===================================================================== */
        function renderConstruction(filterCat = 'all') {
            const grid = document.getElementById('constructionGrid');
            if (!grid) return;

            const items = filterCat === 'all'
                ? constructionProjects
                : constructionProjects.filter(item => item.cats.includes(filterCat));

            grid.innerHTML = items.map((item, idx) => `
                <div onclick="openProjectModal('construction', ${constructionProjects.indexOf(item)})"
                     class="project-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-brand-gold hover:shadow-md transition flex flex-col">
                    <div class="card-img-wrap">
                        <img
                            src="${getDriveImg(item.id)}"
                            alt="${item.title}"
                            loading="lazy"
                            onerror="${getDriveFallback(item.id, 'Cong Trinh Thuc Te')}"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12px] sm:text-[13.5px] font-bold text-brand-navy leading-snug break-words whitespace-normal">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1.5 break-words">
                            ${item.categoryName}
                        </p>
                    </div>
                </div>
            `).join('');
        }

        function filterProjects(cat) {
            // Cập nhật trạng thái nút danh mục đang chọn
            const buttons = document.querySelectorAll('.cat-btn');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat') === cat) {
                    btn.className = 'cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-brand-navy text-white border-brand-navy';
                } else {
                    btn.className = 'cat-btn px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap border transition bg-white text-slate-700 border-slate-300 hover:border-brand-navy hover:text-brand-navy';
                }
            });
            renderConstruction(cat);
        }

        /* =====================================================================
           F. RENDER 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
           ===================================================================== */
        function renderDaNangProjects() {
            const grid = document.getElementById('daNangGrid');
            if (!grid) return;

            grid.innerHTML = daNangProjects.map((item, index) => `
                <div onclick="openProjectModal('danang', ${index})"
                     class="project-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-brand-gold hover:shadow-md transition flex flex-col">
                    <div class="card-img-wrap">
                        <img
                            src="${getDriveImg(item.id)}"
                            alt="${item.title}"
                            loading="lazy"
                            onerror="${getDriveFallback(item.id, 'Du An Da Nang')}"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy leading-snug break-words whitespace-normal">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] text-brand-gold font-medium mt-1.5 break-words">
                            ${item.area}
                        </p>
                    </div>
                </div>
            `).join('');
        }

        /* =====================================================================
           G. ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG ĐIỆN THOẠI
           ===================================================================== */
        let currentBanner = 0;
        const totalBanners = 2;
        let bannerInterval = null;

        function updateBannerUI() {
            const track = document.getElementById('bannerTrack');
            const dot0 = document.getElementById('dot0');
            const dot1 = document.getElementById('dot1');
            if (!track) return;

            track.style.transform = `translateX(-${currentBanner * 50}%)`;
            if (dot0 && dot1) {
                dot0.className = currentBanner === 0
                    ? 'w-6 h-2 rounded-full bg-brand-gold transition-all'
                    : 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
                dot1.className = currentBanner === 1
                    ? 'w-6 h-2 rounded-full bg-brand-gold transition-all'
                    : 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
            }
        }

        function goToBanner(index) {
            currentBanner = (index + totalBanners) % totalBanners;
            updateBannerUI();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                currentBanner = (currentBanner + 1) % totalBanners;
                updateBannerUI();
            }, 5000);
        }

        /* =====================================================================
           H. MODAL CHI TIẾT CÔNG TRÌNH / BÀI VIẾT
           ===================================================================== */
        function openProjectModal(type, index) {
            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImg');
            const cat = document.getElementById('modalCategory');
            const title = document.getElementById('modalTitle');
            const desc = document.getElementById('modalDesc');

            const item = type === 'construction' ? constructionProjects[index] : daNangProjects[index];
            if (!item || !modal) return;

            img.src = getDriveImg(item.id);
            img.alt = item.title;
            img.onerror = function() {
                this.onerror = function() {
                    this.src = 'https://placehold.co/800x500/0F2942/C8922A?text=HUNG+THINH+PHAT';
                };
                this.src = `https://drive.google.com/thumbnail?id=${item.id}&sz=w1000`;
            };
            cat.textContent = type === 'construction' ? item.categoryName : `Dự án tại ${item.area}`;
            title.textContent = item.title;
            desc.textContent = item.desc;

            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function openArticle(index) {
            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImg');
            const cat = document.getElementById('modalCategory');
            const title = document.getElementById('modalTitle');
            const desc = document.getElementById('modalDesc');
            const item = articlesData[index];
            if (!item || !modal) return;

            img.src = getDriveImg(item.imgId);
            img.alt = item.title;
            cat.textContent = item.category;
            title.textContent = item.title;
            desc.textContent = item.desc;

            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            if (modal) modal.classList.add('hidden');
            document.body.style.overflow = '';
        }

        function closeModalOnBackdrop(e) {
            if (e.target.id === 'detailModal') closeDetailModal();
        }

        /* =====================================================================
           I. MENU ĐIỆN THOẠI & XỬ LÝ FORM YÊU CẦU BÁO GIÁ
           ===================================================================== */
        function closeMobileMenu() {
            const menu = document.getElementById('mobileMenu');
            if (menu) menu.classList.add('hidden');
        }

        document.addEventListener('DOMContentLoaded', function () {
            try {
                // Khởi tạo dữ liệu công trình & dự án
                renderConstruction('all');
                renderDaNangProjects();

                // Khởi chạy slider 2 banner tự trượt
                updateBannerUI();
                resetBannerTimer();

                const prevBtn = document.getElementById('prevBanner');
                const nextBtn = document.getElementById('nextBanner');
                if (prevBtn) prevBtn.addEventListener('click', () => goToBanner(currentBanner - 1));
                if (nextBtn) nextBtn.addEventListener('click', () => goToBanner(currentBanner + 1));

                // Vuốt chạm chuyển banner trên điện thoại
                const slider = document.getElementById('heroSlider');
                let touchStartX = 0;
                if (slider) {
                    slider.addEventListener('touchstart', e => {
                        touchStartX = e.changedTouches[0].screenX;
                    }, { passive: true });
                    slider.addEventListener('touchend', e => {
                        const diff = touchStartX - e.changedTouches[0].screenX;
                        if (Math.abs(diff) > 40) {
                            goToBanner(diff > 0 ? currentBanner + 1 : currentBanner - 1);
                        }
                    }, { passive: true });
                }

                // Toggle menu mobile
                const menuBtn = document.getElementById('mobileMenuBtn');
                const mobileMenu = document.getElementById('mobileMenu');
                if (menuBtn && mobileMenu) {
                    menuBtn.addEventListener('click', () => {
                        mobileMenu.classList.toggle('hidden');
                    });
                }

                // Xử lý Form yêu cầu báo giá (hiển thị thông báo trực tiếp, không dùng alert)
                const quoteForm = document.getElementById('quoteForm');
                const feedback = document.getElementById('formFeedback');
                if (quoteForm && feedback) {
                    quoteForm.addEventListener('submit', function (e) {
                        e.preventDefault();
                        const name = document.getElementById('qName').value.trim();
                        const phone = document.getElementById('qPhone').value.trim();
                        const type = document.getElementById('qType').value;

                        if (!name || !phone) {
                            feedback.className = 'mt-4 p-3.5 rounded-lg text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                            feedback.textContent = 'Vui lòng nhập đầy đủ họ tên và số điện thoại để chúng tôi liên hệ tư vấn.';
                            return;
                        }

                        feedback.className = 'mt-4 p-3.5 rounded-lg text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
                        feedback.textContent = `Cảm ơn anh/chị ${name}! Yêu cầu báo giá hạng mục "${type}" đã được tiếp nhận. Kỹ sư Hưng Thịnh Phát sẽ liên hệ qua số ${phone} trong thời gian sớm nhất.`;
                        quoteForm.reset();
                    });
                }
            } catch (err) {
                console.error('Lỗi khởi tạo giao diện:', err);
            }
        });
    </script>
</body>
</html>
