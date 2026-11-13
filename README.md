<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Trầm Hương Duy Đức - Tinh Hoa Trầm Hương Thiên Nhiên Đà Nẵng | tramhuongduyduc.com</title>
    <meta name="description" content="Trầm Hương Duy Đức (tramhuongduyduc.com) chuyên cung cấp Chuỗi trầm hương 108 hạt, Vòng tay phong thủy, Nhang trầm không tăm, Trầm miếng giác xông, Tượng trầm cảnh uy tín tại 12 Bàu Trảng 2, Thanh Khê, Đà Nẵng. Hotline: 0905.244.307">
    
    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://tramhuongduyduc.com/">
    <meta property="og:title" content="Trầm Hương Duy Đức - Trầm Hương Thiên Nhiên Uy Tín Đà Nẵng">
    <meta property="og:description" content="Chuyên chuỗi trầm hương, vòng tay phong thủy, nhang trầm, thác lư xông, trầm cảnh cao cấp. Đ/c: 12 Bàu Trảng 2, P. Thanh Khê, TP. Đà Nẵng - ĐT: 0905.244.307">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM=w800">
    <meta property="og:image:alt" content="Logo Trầm Hương Duy Đức">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM=w800">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM=w200" type="image/png">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter & Playfair Display -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:ital,wght@0,600;0,700;1,600&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        tram: {
                            50: '#fdfaf6',
                            100: '#f9f1e6',
                            200: '#f0dec4',
                            300: '#e3c296',
                            400: '#d4af37', // Vàng kim chủ đạo theo logo
                            500: '#b8860b',
                            600: '#7a4924',
                            700: '#5a3214', // Nâu trầm chủ đạo theo logo
                            800: '#42220b',
                            900: '#2b1506',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Playfair Display', 'serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền & chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden !important;
            margin: 0;
            padding: 0;
            background-color: #fdfaf6;
            color: #2b1506;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính đúng bằng 95% kích thước màn hình máy tính */
        .flatsome-container {
            width: 100%;
            padding-left: 10px;
            padding-right: 10px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95% !important;
                max-width: 95% !important;
                padding-left: 0;
                padding-right: 0;
                margin-left: auto;
                margin-right: auto;
            }
        }

        /* Style chuẩn Flatsome Section Title */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e6d5b8;
            padding-bottom: 8px;
        }
        .section-title-main {
            position: relative;
            font-weight: 700;
            text-transform: uppercase;
            color: #42220b;
            letter-spacing: 0.02em;
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 2px;
            background-color: #b8860b;
        }

        /* Đảm bảo tên sản phẩm hiển thị đầy đủ, không bị thiếu chữ và không tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
            display: block;
        }

        /* Danh mục trên máy tính: từng mục không được tự gãy chữ xuống dòng */
        .nav-cat-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(212, 175, 55, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(212, 175, 55, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(212, 175, 55, 0); }
        }
        .contact-pulse {
            animation: pulse-ring 2s infinite;
        }

        /* Ẩn thanh cuộn ngang cho danh mục điện thoại nhưng vẫn vuốt mượt */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="font-sans antialiased selection:bg-tram-700 selection:text-white">

    <!-- ==========================================
         FLATSOME HEADER WRAPPER
         (Không để nút gọi ngay trên Header để tránh tràn viền)
    =========================================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-40 border-b border-tram-200">
        
        <!-- Top Bar chuẩn Flatsome -->
        <div class="bg-tram-900 text-tram-100 text-[11px] sm:text-xs py-1.5 border-b border-tram-700/60">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-3 truncate max-w-full">
                    <span class="inline-flex items-center gap-1 text-tram-300 font-medium truncate">
                        <i class="fa-solid fa-location-dot text-tram-400"></i>
                        <span>12 Bàu Trảng 2, Phường Thanh Khê, Tp.Đà Nẵng</span>
                    </span>
                    <span class="hidden md:inline-block text-tram-600">|</span>
                    <span class="hidden md:inline-flex items-center gap-1 text-tram-200">
                        <i class="fa-solid fa-globe text-tram-400"></i>
                        <span>tramhuongduyduc.com</span>
                    </span>
                </div>
                <div class="hidden sm:flex items-center gap-4 text-[11px] text-tram-200">
                    <a href="#bao-gia" class="hover:text-tram-400 transition">Chính sách đại lý</a>
                    <span>•</span>
                    <a href="#san-pham-noi-bat" class="hover:text-tram-400 transition">Hướng dẫn đặt hàng</a>
                    <span>•</span>
                    <a href="https://www.facebook.com/duc.nguyenle.56" target="_blank" rel="noopener noreferrer" class="hover:text-tram-400 transition inline-flex items-center gap-1">
                        <i class="fa-brands fa-facebook"></i> Facebook Duy Đức
                    </a>
                </div>
            </div>
        </div>

        <!-- Header Main (Logo chỉnh gọn nhỏ lại, Thanh tìm kiếm, Giỏ hàng - Không để nút Gọi ngay) -->
        <div class="bg-white py-2.5">
            <div class="flatsome-container flex items-center justify-between gap-2 sm:gap-4">
                
                <!-- Nút Menu trên Điện thoại -->
                <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg text-tram-800 hover:bg-tram-100 border border-tram-200 flex-shrink-0">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>

                <!-- Logo Trầm Hương Duy Đức (Đã chỉnh gọn nhỏ lại tinh tế) -->
                <a href="#" class="flex items-center gap-2 sm:gap-2.5 flex-shrink-0 group">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-full overflow-hidden border-2 border-tram-400 shadow-sm bg-tram-900 flex items-center justify-center flex-shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM=w400" 
                             data-drive-id="1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM"
                             onerror="handleDriveImgError(this, 'Logo')"
                             alt="Logo Trầm Hương Duy Đức" 
                             class="w-full h-full object-cover">
                    </div>
                    <div class="flex flex-col">
                        <span class="font-serif font-bold text-sm sm:text-base md:text-lg text-tram-800 tracking-wide leading-tight group-hover:text-tram-600 transition">
                            TRẦM HƯƠNG DUY ĐỨC
                        </span>
                        <span class="text-[10px] sm:text-[11px] text-tram-600 font-medium tracking-wider uppercase">
                            tramhuongduyduc.com
                        </span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm chuẩn Flatsome (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-4">
                    <div class="flex w-full rounded-full border border-tram-300 bg-tram-50 overflow-hidden focus-within:border-tram-600 transition">
                        <select id="desktopSearchCat" onchange="filterByCategory(this.value)" class="bg-tram-100 text-tram-800 text-xs font-medium px-3 py-2 border-r border-tram-200 focus:outline-none cursor-pointer">
                            <option value="all">Tất cả danh mục</option>
                            <option value="chuoi-tram">Chuỗi trầm hương</option>
                            <option value="vong-tay">Vòng tay phong thủy</option>
                            <option value="nhang-tram">Nhang trầm - Thác lư xông</option>
                            <option value="tram-mieng">Trầm hương miếng - Giác xông</option>
                            <option value="tranh-tuong">Tranh - Tượng trầm cảnh</option>
                            <option value="tram-chim">Trầm chìm VIP cao cấp</option>
                        </select>
                        <input id="desktopSearchInput" type="text" oninput="searchProducts(this.value)" placeholder="Tìm vòng trầm 108 hạt, nhang trầm, giác xông..." class="w-full px-3.5 py-2 text-xs bg-transparent text-tram-900 focus:outline-none">
                        <button onclick="searchProducts(document.getElementById('desktopSearchInput').value)" class="bg-tram-700 hover:bg-tram-800 text-tram-400 px-4 flex items-center justify-center transition">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Giỏ hàng gọn gàng (Không có nút gọi ngay trên header để tránh tràn viền) -->
                <div class="flex items-center gap-2 flex-shrink-0">
                    <button onclick="openCartModal()" class="inline-flex items-center gap-1.5 px-2.5 sm:px-3 py-1.5 rounded-full border border-tram-300 bg-tram-50 hover:bg-tram-700 hover:text-white text-tram-800 text-xs font-semibold transition">
                        <i class="fa-solid fa-bag-shopping text-tram-600 group-hover:text-white"></i>
                        <span class="hidden sm:inline">Giỏ hàng</span>
                        <span id="cartCountBadge" class="bg-tram-700 text-tram-300 text-[10px] font-bold px-1.5 py-0.5 rounded-full">0</span>
                    </button>
                </div>

            </div>

            <!-- Thanh tìm kiếm gọn trên Điện thoại -->
            <div class="flatsome-container mt-2 md:hidden">
                <div class="flex w-full rounded-full border border-tram-300 bg-tram-50 overflow-hidden">
                    <input id="mobileSearchInput" type="text" oninput="searchProducts(this.value)" placeholder="Tìm kiếm sản phẩm trầm hương..." class="w-full px-3 py-1.5 text-xs bg-transparent text-tram-900 focus:outline-none">
                    <button onclick="searchProducts(document.getElementById('mobileSearchInput').value)" class="bg-tram-700 text-tram-300 px-3.5 flex items-center justify-center">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- ==========================================
             THANH DANH MỤC TRÊN MÁY TÍNH & ĐIỆN THOẠI
             - Trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2, tuyệt đối không gãy chữ trong tên danh mục (whitespace-nowrap)
        =========================================== -->
        <nav class="bg-tram-800 text-white border-t border-tram-700">
            <div class="flatsome-container">
                <!-- Menu Máy tính: tự cân đối trên 1 hàng hoặc hàng 2, mỗi tên danh mục nằm liền 1 khối -->
                <ul class="hidden lg:flex flex-wrap items-center justify-center gap-x-3 xl:gap-x-4 gap-y-1 py-2 text-[11.5px] xl:text-[12px] font-medium">
                    <li>
                        <a href="#trang-chu" onclick="filterByCategory('all')" class="nav-cat-item px-2 py-1 rounded bg-tram-700 text-tram-300 font-semibold hover:bg-tram-600 transition">
                            <i class="fa-solid fa-house mr-1 text-[10px]"></i> Trang chủ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-noi-bat" onclick="filterByCategory('chuoi-tram')" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Chuỗi trầm hương 108 hạt
                        </a>
                    </li>
                    <li>
                        <a href="#vong-tay-section" onclick="filterByCategory('vong-tay')" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Vòng tay phong thủy
                        </a>
                    </li>
                    <li>
                        <a href="#vong-tay-section" onclick="filterByCategory('vong-tay')" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Vòng trầm hương bọc vàng
                        </a>
                    </li>
                    <li>
                        <a href="#vat-pham-section" onclick="filterByCategory('tranh-tuong')" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Mặt tượng đeo cổ
                        </a>
                    </li>
                    <li>
                        <a href="#nhang-tram-section" onclick="filterByCategory('nhang-tram')" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Nhang trầm - Thác lư xông
                        </a>
                    </li>
                    <li>
                        <a href="#nhang-tram-section" onclick="filterByCategory('tram-mieng')" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Trầm hương miếng - Giác xông
                        </a>
                    </li>
                    <li>
                        <a href="#vat-pham-section" onclick="filterByCategory('tranh-tuong')" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Tranh - Tượng trầm cảnh
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-noi-bat" onclick="filterByCategory('tram-chim')" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Trầm chìm VIP cao cấp
                        </a>
                    </li>
                    <li>
                        <a href="#kien-thuc-section" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Kiến thức phong thủy
                        </a>
                    </li>
                    <li>
                        <a href="#bao-gia" class="nav-cat-item px-2 py-1 rounded hover:bg-tram-700 hover:text-tram-300 transition">
                            Báo giá & Liên hệ
                        </a>
                    </li>
                </ul>

                <!-- Thanh danh mục rút gọn cuộn ngang trên Điện thoại -->
                <div class="flex lg:hidden items-center gap-1.5 overflow-x-auto no-scrollbar py-2 text-[11px] font-medium">
                    <a href="#san-pham-noi-bat" onclick="filterByCategory('all')" class="nav-cat-item px-2.5 py-1 rounded-full bg-tram-700 text-tram-300 font-semibold flex-shrink-0">
                        Tất cả
                    </a>
                    <a href="#san-pham-noi-bat" onclick="filterByCategory('chuoi-tram')" class="nav-cat-item px-2.5 py-1 rounded-full bg-tram-900/60 hover:bg-tram-700 text-tram-100 flex-shrink-0">
                        Chuỗi trầm hương
                    </a>
                    <a href="#vong-tay-section" onclick="filterByCategory('vong-tay')" class="nav-cat-item px-2.5 py-1 rounded-full bg-tram-900/60 hover:bg-tram-700 text-tram-100 flex-shrink-0">
                        Vòng tay phong thủy
                    </a>
                    <a href="#nhang-tram-section" onclick="filterByCategory('nhang-tram')" class="nav-cat-item px-2.5 py-1 rounded-full bg-tram-900/60 hover:bg-tram-700 text-tram-100 flex-shrink-0">
                        Nhang trầm - Thác lư
                    </a>
                    <a href="#nhang-tram-section" onclick="filterByCategory('tram-mieng')" class="nav-cat-item px-2.5 py-1 rounded-full bg-tram-900/60 hover:bg-tram-700 text-tram-100 flex-shrink-0">
                        Trầm miếng - Giác xông
                    </a>
                    <a href="#vat-pham-section" onclick="filterByCategory('tranh-tuong')" class="nav-cat-item px-2.5 py-1 rounded-full bg-tram-900/60 hover:bg-tram-700 text-tram-100 flex-shrink-0">
                        Tượng trầm cảnh
                    </a>
                    <a href="#san-pham-noi-bat" onclick="filterByCategory('tram-chim')" class="nav-cat-item px-2.5 py-1 rounded-full bg-tram-900/60 hover:bg-tram-700 text-tram-100 flex-shrink-0">
                        Trầm chìm VIP
                    </a>
                </div>
            </div>
        </nav>
    </header>

    <!-- Menu Drawer trên Điện thoại -->
    <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileMenu()" class="absolute inset-0 bg-black/60 backdrop-blur-xs"></div>
        <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col z-10 overflow-y-auto">
            <div class="p-3.5 bg-tram-800 text-white flex items-center justify-between">
                <span class="font-serif font-bold text-sm text-tram-300">DANH MỤC SẢN PHẨM</span>
                <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded-full bg-tram-700 text-white flex items-center justify-center">
                    <i class="fa-solid fa-xmark text-sm"></i>
                </button>
            </div>
            <ul class="divide-y divide-tram-100 text-xs font-medium text-tram-900">
                <li><a href="#san-pham-noi-bat" onclick="filterByCategory('all'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50 font-semibold text-tram-700">Tất cả sản phẩm Trầm Hương</a></li>
                <li><a href="#san-pham-noi-bat" onclick="filterByCategory('chuoi-tram'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Chuỗi trầm hương (108 hạt, 216 hạt)</a></li>
                <li><a href="#vong-tay-section" onclick="filterByCategory('vong-tay'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Vòng tay phong thủy Nam & Nữ</a></li>
                <li><a href="#vong-tay-section" onclick="filterByCategory('vong-tay'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Vòng trầm hương bọc vàng</a></li>
                <li><a href="#vat-pham-section" onclick="filterByCategory('tranh-tuong'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Mặt tượng đeo cổ</a></li>
                <li><a href="#nhang-tram-section" onclick="filterByCategory('nhang-tram'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Nhang trầm - Thác lư xông</a></li>
                <li><a href="#nhang-tram-section" onclick="filterByCategory('tram-mieng'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Trầm hương miếng - Giác xông</a></li>
                <li><a href="#vat-pham-section" onclick="filterByCategory('tranh-tuong'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Tranh - Tượng trầm cảnh</a></li>
                <li><a href="#san-pham-noi-bat" onclick="filterByCategory('tram-chim'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Trầm chìm VIP cao cấp</a></li>
                <li><a href="#kien-thuc-section" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Kiến thức & Tin tức Phong thủy</a></li>
                <li><a href="#bao-gia" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-tram-50">Yêu cầu báo giá & Liên hệ</a></li>
            </ul>
            <div class="mt-auto p-4 bg-tram-50 border-t border-tram-200 text-xs space-y-1.5">
                <p class="font-bold text-tram-800">TRẦM HƯƠNG DUY ĐỨC</p>
                <p class="text-tram-700"><i class="fa-solid fa-location-dot text-tram-500 mr-1"></i> 12 Bàu Trảng 2, P. Thanh Khê, Đà Nẵng</p>
                <p class="text-tram-700"><i class="fa-solid fa-phone text-tram-500 mr-1"></i> 0905.244.307</p>
            </div>
        </div>
    </div>

    <!-- ==========================================
         FLATSOME SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP
         - Kích thước 2 banner bằng nhau tuyệt đối
         - Banner điện thoại được thiết kế MỚI hoàn toàn khác với banner máy tính
         - Chữ chỉnh nhỏ lại nằm gọn 100% bên trong ảnh banner, không tràn viền
    =========================================== -->
    <section id="trang-chu" class="py-3 sm:py-4">
        <div class="flatsome-container">
            <div class="relative rounded-xl overflow-hidden shadow-md border border-tram-300 bg-tram-900">
                
                <!-- ==================== SLIDE 1 ==================== -->
                <div id="bannerSlide0" class="banner-slide transition-opacity duration-500 opacity-100">
                    
                    <!-- BANNER 1 - GIAO DIỆN MÁY TÍNH (hidden md:flex) - Cao cố định 380px -->
                    <div class="hidden md:flex w-full h-[380px] bg-gradient-to-r from-[#261105] via-[#47230d] to-[#2b1406] relative items-center justify-between px-10 lg:px-14 overflow-hidden">
                        <!-- Họa tiết nền trầm hương sang trọng -->
                        <div class="absolute inset-0 opacity-15 pointer-events-none" style="background-image: radial-gradient(#d4af37 1px, transparent 1px); background-size: 24px 24px;"></div>
                        
                        <!-- Khung nội dung chữ nhỏ gọn nằm trọn bên trong Banner Máy Tính -->
                        <div class="relative z-10 w-[56%] max-w-xl bg-tram-900/75 border border-tram-400/50 rounded-xl p-6 backdrop-blur-xs">
                            <p class="text-tram-400 text-xs font-semibold uppercase tracking-widest mb-1.5">
                                Tinh Hoa Trầm Hương Tự Nhiên Việt Nam
                            </p>
                            <h1 class="font-serif font-bold text-2xl lg:text-3xl text-white leading-snug mb-2">
                                TRẦM HƯƠNG DUY ĐỨC
                            </h1>
                            <p class="text-tram-100 text-xs lg:text-sm leading-relaxed mb-4">
                                Chuyên chế tác và cung cấp Chuỗi Trầm Hương 108 Hạt, Vòng Tay Phong Thủy, Trầm Chìm Tự Nhiên, Nhang Trầm & Thác Khói nguyên chất 100% tại Đà Nẵng.
                            </p>
                            <div class="flex flex-wrap items-center gap-3 text-xs text-tram-200 mb-4">
                                <span class="px-2.5 py-1 rounded bg-tram-800 border border-tram-400/40">
                                    <i class="fa-solid fa-phone text-tram-400 mr-1"></i> Hotline: 0905.244.307
                                </span>
                                <span class="px-2.5 py-1 rounded bg-tram-800 border border-tram-400/40">
                                    <i class="fa-solid fa-location-dot text-tram-400 mr-1"></i> 12 Bàu Trảng 2, P. Thanh Khê, Đà Nẵng
                                </span>
                            </div>
                            <div class="flex items-center gap-3">
                                <a href="#san-pham-noi-bat" class="px-4 py-2 rounded-lg bg-tram-400 hover:bg-tram-300 text-tram-900 font-bold text-xs uppercase tracking-wider transition shadow">
                                    Khám Phá Sản Phẩm
                                </a>
                                <a href="#bao-gia" class="px-4 py-2 rounded-lg border border-tram-400 text-tram-300 hover:bg-tram-800 font-semibold text-xs uppercase tracking-wider transition">
                                    Nhận Báo Giá Ngay
                                </a>
                            </div>
                        </div>

                        <!-- Khung ảnh thực tế sản phẩm bên phải Banner Máy Tính -->
                        <div class="relative z-10 w-[40%] flex items-center justify-center gap-3">
                            <div class="w-44 h-44 lg:w-52 lg:h-52 rounded-2xl overflow-hidden border-2 border-tram-400 shadow-2xl transform -rotate-3 bg-tram-800">
                                <img src="https://lh3.googleusercontent.com/d/1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam=w800"
                                     data-drive-id="1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam"
                                     onerror="handleDriveImgError(this, 'Vòng Trầm Hương')"
                                     alt="Vòng Trầm Hương Duy Đức" class="w-full h-full object-cover">
                            </div>
                            <div class="w-36 h-36 lg:w-44 lg:h-44 rounded-2xl overflow-hidden border-2 border-tram-300 shadow-xl transform rotate-3 bg-tram-800 hidden xl:block">
                                <img src="https://lh3.googleusercontent.com/d/1SYfpAmouYH7GsC721KqBHf2tCg6w9Kgh=w800"
                                     data-drive-id="1SYfpAmouYH7GsC721KqBHf2tCg6w9Kgh"
                                     onerror="handleDriveImgError(this, 'Chuỗi Trầm 108 Hạt')"
                                     alt="Chuỗi Trầm Hương 108 Hạt" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 1 - GIAO DIỆN ĐIỆN THOẠI THIẾT KẾ RIÊNG (flex md:hidden) - Cao cố định 240px -->
                    <div class="flex md:hidden w-full h-[240px] bg-gradient-to-br from-[#2b1406] via-[#4a240e] to-[#261105] relative items-center justify-between px-3.5 py-3 overflow-hidden">
                        <div class="w-[62%] pr-2 flex flex-col justify-center">
                            <span class="text-[10px] text-tram-400 font-semibold uppercase tracking-wider mb-0.5">
                                Trầm Thiên Nhiên 100%
                            </span>
                            <h2 class="font-serif font-bold text-sm text-white leading-tight mb-1">
                                TRẦM HƯƠNG DUY ĐỨC
                            </h2>
                            <p class="text-[11px] text-tram-100 leading-snug mb-2">
                                Chuỗi trầm 108 hạt, Vòng tay phong thủy, Nhang trầm & Giác xông cao cấp.
                            </p>
                            <div class="text-[10px] text-tram-300 space-y-0.5 mb-2">
                                <p class="truncate"><i class="fa-solid fa-phone text-tram-400 mr-1"></i>0905.244.307</p>
                                <p class="truncate"><i class="fa-solid fa-location-dot text-tram-400 mr-1"></i>12 Bàu Trảng 2, Thanh Khê, ĐN</p>
                            </div>
                            <div>
                                <a href="#san-pham-noi-bat" class="inline-block px-2.5 py-1 rounded bg-tram-400 text-tram-900 font-bold text-[10px] uppercase">
                                    Xem Sản Phẩm
                                </a>
                            </div>
                        </div>
                        <div class="w-[38%] flex items-center justify-center">
                            <div class="w-28 h-28 rounded-xl overflow-hidden border-2 border-tram-400 shadow-lg bg-tram-800">
                                <img src="https://lh3.googleusercontent.com/d/1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam=w600"
                                     data-drive-id="1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam"
                                     onerror="handleDriveImgError(this, 'Trầm Hương')"
                                     alt="Sản phẩm Trầm Hương Duy Đức" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                </div>

                <!-- ==================== SLIDE 2 ==================== -->
                <div id="bannerSlide1" class="banner-slide hidden transition-opacity duration-500 opacity-100">
                    
                    <!-- BANNER 2 - GIAO DIỆN MÁY TÍNH (hidden md:flex) - Kích thước bằng đúng Slide 1 (380px) -->
                    <div class="hidden md:flex w-full h-[380px] bg-gradient-to-r from-[#1f1209] via-[#522b12] to-[#291507] relative items-center justify-between px-10 lg:px-14 overflow-hidden">
                        <div class="absolute inset-0 opacity-15 pointer-events-none" style="background-image: radial-gradient(#d4af37 1px, transparent 1px); background-size: 24px 24px;"></div>

                        <!-- Khung nội dung chữ nhỏ gọn nằm trọn bên trong Banner Máy Tính -->
                        <div class="relative z-10 w-[56%] max-w-xl bg-tram-900/75 border border-tram-400/50 rounded-xl p-6 backdrop-blur-xs">
                            <p class="text-tram-400 text-xs font-semibold uppercase tracking-widest mb-1.5">
                                Quà Tặng Phong Thủy & Thưởng Trầm Thượng Hạng
                            </p>
                            <h2 class="font-serif font-bold text-2xl lg:text-3xl text-white leading-snug mb-2">
                                BỘ SƯU TẬP TRẦM HƯƠNG VIP
                            </h2>
                            <p class="text-tram-100 text-xs lg:text-sm leading-relaxed mb-4">
                                Tuyển chọn Vòng Trầm Già Dầu, Trầm Sánh Chìm Bọc Vàng, Trầm Miếng Xông Nhà, Nhang Trầm Không Tăm & Tượng Trầm Cảnh mang lại bình an, tài lộc và vượng khí.
                            </p>
                            <div class="flex flex-wrap items-center gap-3 text-xs text-tram-200 mb-4">
                                <span class="px-2.5 py-1 rounded bg-tram-800 border border-tram-400/40">
                                    <i class="fa-solid fa-certificate text-tram-400 mr-1"></i> Bảo hành mùi hương trọn đời
                                </span>
                                <span class="px-2.5 py-1 rounded bg-tram-800 border border-tram-400/40">
                                    <i class="fa-solid fa-truck-fast text-tram-400 mr-1"></i> Giao hàng toàn quốc - Kiểm hàng trước
                                </span>
                            </div>
                            <div class="flex items-center gap-3">
                                <a href="#vong-tay-section" class="px-4 py-2 rounded-lg bg-tram-400 hover:bg-tram-300 text-tram-900 font-bold text-xs uppercase tracking-wider transition shadow">
                                    Bộ Sưu Tập Vòng Trầm
                                </a>
                                <a href="#nhang-tram-section" class="px-4 py-2 rounded-lg border border-tram-400 text-tram-300 hover:bg-tram-800 font-semibold text-xs uppercase tracking-wider transition">
                                    Nhang & Giác Xông
                                </a>
                            </div>
                        </div>

                        <!-- Khung ảnh thực tế sản phẩm bên phải Banner Máy Tính -->
                        <div class="relative z-10 w-[40%] flex items-center justify-center gap-3">
                            <div class="w-44 h-44 lg:w-52 lg:h-52 rounded-2xl overflow-hidden border-2 border-tram-400 shadow-2xl transform rotate-2 bg-tram-800">
                                <img src="https://lh3.googleusercontent.com/d/1dOpYD6HEfAu_zsBxZL1Mgv5LQczo2UYZ=w800"
                                     data-drive-id="1dOpYD6HEfAu_zsBxZL1Mgv5LQczo2UYZ"
                                     onerror="handleDriveImgError(this, 'Trầm Hương VIP')"
                                     alt="Bộ sưu tập Trầm Hương Duy Đức" class="w-full h-full object-cover">
                            </div>
                            <div class="w-36 h-36 lg:w-44 lg:h-44 rounded-2xl overflow-hidden border-2 border-tram-300 shadow-xl transform -rotate-2 bg-tram-800 hidden xl:block">
                                <img src="https://lh3.googleusercontent.com/d/1kdtLUOXuyN1Or7ZU9vwrpiUfRU_adfnj=w800"
                                     data-drive-id="1kdtLUOXuyN1Or7ZU9vwrpiUfRU_adfnj"
                                     onerror="handleDriveImgError(this, 'Vật Phẩm Trầm')"
                                     alt="Vật Phẩm Trầm Hương" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 - GIAO DIỆN ĐIỆN THOẠI THIẾT KẾ RIÊNG (flex md:hidden) - Kích thước bằng đúng Slide 1 (240px) -->
                    <div class="flex md:hidden w-full h-[240px] bg-gradient-to-br from-[#221004] via-[#542c13] to-[#2b1406] relative items-center justify-between px-3.5 py-3 overflow-hidden">
                        <div class="w-[62%] pr-2 flex flex-col justify-center">
                            <span class="text-[10px] text-tram-400 font-semibold uppercase tracking-wider mb-0.5">
                                Quà Tặng Phong Thủy
                            </span>
                            <h2 class="font-serif font-bold text-sm text-white leading-tight mb-1">
                                TRẦM CHÌM & NHANG TRẦM
                            </h2>
                            <p class="text-[11px] text-tram-100 leading-snug mb-2">
                                Hương thơm ngọt dịu tự nhiên, thu hút bình an, may mắn & tài lộc.
                            </p>
                            <div class="text-[10px] text-tram-300 space-y-0.5 mb-2">
                                <p class="truncate"><i class="fa-solid fa-check text-tram-400 mr-1"></i>Cam kết tự nhiên 100%</p>
                                <p class="truncate"><i class="fa-solid fa-globe text-tram-400 mr-1"></i>tramhuongduyduc.com</p>
                            </div>
                            <div>
                                <a href="#bao-gia" class="inline-block px-2.5 py-1 rounded bg-tram-400 text-tram-900 font-bold text-[10px] uppercase">
                                    Nhận Báo Giá
                                </a>
                            </div>
                        </div>
                        <div class="w-[38%] flex items-center justify-center">
                            <div class="w-28 h-28 rounded-xl overflow-hidden border-2 border-tram-400 shadow-lg bg-tram-800">
                                <img src="https://lh3.googleusercontent.com/d/1dOpYD6HEfAu_zsBxZL1Mgv5LQczo2UYZ=w600"
                                     data-drive-id="1dOpYD6HEfAu_zsBxZL1Mgv5LQczo2UYZ"
                                     onerror="handleDriveImgError(this, 'Trầm Cảnh')"
                                     alt="Trầm Hương Cao Cấp" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng Banner Trái / Phải -->
                <button onclick="prevBanner()" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-tram-400 text-white hover:text-tram-900 flex items-center justify-center transition z-20">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="nextBanner()" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-tram-400 text-white hover:text-tram-900 flex items-center justify-center transition z-20">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm tròn chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button id="bannerDot0" onclick="goToBanner(0)" class="w-6 h-1.5 rounded-full bg-tram-400 transition-all"></button>
                    <button id="bannerDot1" onclick="goToBanner(1)" class="w-2 h-1.5 rounded-full bg-white/50 transition-all"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ
         - Lấy đúng hệ thống danh mục từ trang mẫu tramhuongdanang.vn
         - Chữ danh mục ở trang chủ nhỏ gọn, đẹp mắt trên cả máy tính và điện thoại
    =========================================== -->
    <section class="py-4">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base">
                        <i class="fa-solid fa-layer-group text-tram-500 mr-1.5"></i> DANH MỤC SẢN PHẨM
                    </h2>
                    <span class="text-[11px] text-tram-600 hidden sm:inline">Chọn danh mục để lọc nhanh</span>
                </div>
            </div>

            <!-- Lưới Danh Mục nhỏ gọn: 3 cột trên điện thoại, 7 cột trên máy tính -->
            <div class="grid grid-cols-3 sm:grid-cols-4 lg:grid-cols-7 gap-2 sm:gap-3">
                
                <button onclick="filterByCategory('chuoi-tram')" class="group bg-white hover:bg-tram-50 p-2.5 rounded-xl border border-tram-200 hover:border-tram-400 shadow-xs flex flex-col items-center text-center transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-tram-300 mb-1.5 bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam=w300" data-drive-id="1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam" onerror="handleDriveImgError(this, 'Chuỗi Trầm')" alt="Chuỗi trầm hương" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-semibold text-tram-800 group-hover:text-tram-600 leading-tight">Chuỗi trầm hương</span>
                </button>

                <button onclick="filterByCategory('vong-tay')" class="group bg-white hover:bg-tram-50 p-2.5 rounded-xl border border-tram-200 hover:border-tram-400 shadow-xs flex flex-col items-center text-center transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-tram-300 mb-1.5 bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1SYfpAmouYH7GsC721KqBHf2tCg6w9Kgh=w300" data-drive-id="1SYfpAmouYH7GsC721KqBHf2tCg6w9Kgh" onerror="handleDriveImgError(this, 'Vòng Tay')" alt="Vòng tay phong thủy" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-semibold text-tram-800 group-hover:text-tram-600 leading-tight">Vòng tay phong thủy</span>
                </button>

                <button onclick="filterByCategory('vong-tay')" class="group bg-white hover:bg-tram-50 p-2.5 rounded-xl border border-tram-200 hover:border-tram-400 shadow-xs flex flex-col items-center text-center transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-tram-300 mb-1.5 bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1dOpYD6HEfAu_zsBxZL1Mgv5LQczo2UYZ=w300" data-drive-id="1dOpYD6HEfAu_zsBxZL1Mgv5LQczo2UYZ" onerror="handleDriveImgError(this, 'Bọc Vàng')" alt="Vòng trầm bọc vàng" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-semibold text-tram-800 group-hover:text-tram-600 leading-tight">Vòng trầm bọc vàng</span>
                </button>

                <button onclick="filterByCategory('nhang-tram')" class="group bg-white hover:bg-tram-50 p-2.5 rounded-xl border border-tram-200 hover:border-tram-400 shadow-xs flex flex-col items-center text-center transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-tram-300 mb-1.5 bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1kdtLUOXuyN1Or7ZU9vwrpiUfRU_adfnj=w300" data-drive-id="1kdtLUOXuyN1Or7ZU9vwrpiUfRU_adfnj" onerror="handleDriveImgError(this, 'Nhang Trầm')" alt="Nhang trầm - Thác lư xông" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-semibold text-tram-800 group-hover:text-tram-600 leading-tight">Nhang trầm - Thác lư</span>
                </button>

                <button onclick="filterByCategory('tram-mieng')" class="group bg-white hover:bg-tram-50 p-2.5 rounded-xl border border-tram-200 hover:border-tram-400 shadow-xs flex flex-col items-center text-center transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-tram-300 mb-1.5 bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1_5Gbpb61zpTaPuEp0kCcUsAHME_JnT_K=w300" data-drive-id="1_5Gbpb61zpTaPuEp0kCcUsAHME_JnT_K" onerror="handleDriveImgError(this, 'Giác Xông')" alt="Trầm hương miếng - Giác xông" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-semibold text-tram-800 group-hover:text-tram-600 leading-tight">Trầm miếng - Giác xông</span>
                </button>

                <button onclick="filterByCategory('tranh-tuong')" class="group bg-white hover:bg-tram-50 p-2.5 rounded-xl border border-tram-200 hover:border-tram-400 shadow-xs flex flex-col items-center text-center transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-tram-300 mb-1.5 bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1q2ARJowuXZyCdYBGYvwZQVm2o-fP5mSJ=w300" data-drive-id="1q2ARJowuXZyCdYBGYvwZQVm2o-fP5mSJ" onerror="handleDriveImgError(this, 'Tượng Trầm')" alt="Tranh - Tượng trầm cảnh" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-semibold text-tram-800 group-hover:text-tram-600 leading-tight">Tượng trầm - Mặt đeo cổ</span>
                </button>

                <button onclick="filterByCategory('tram-chim')" class="col-span-3 sm:col-span-1 group bg-white hover:bg-tram-50 p-2.5 rounded-xl border border-tram-200 hover:border-tram-400 shadow-xs flex sm:flex-col items-center justify-center gap-2 sm:gap-0 text-center transition">
                    <div class="w-10 h-10 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-tram-300 sm:mb-1.5 bg-tram-100 flex-shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1r_mIywU7mdqhcs_SXJD3e_xOEPk0yare=w300" data-drive-id="1r_mIywU7mdqhcs_SXJD3e_xOEPk0yare" onerror="handleDriveImgError(this, 'Trầm VIP')" alt="Trầm chìm VIP cao cấp" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-semibold text-tram-800 group-hover:text-tram-600 leading-tight">Trầm chìm VIP cao cấp</span>
                </button>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME SECTION 3: SẢN PHẨM BÁN CHẠY & NỔI BẬT
         - Sử dụng trực tiếp 7 ảnh sản phẩm thực tế trong Google Drive
         - Chia đúng 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
         - Giá giảm & % giảm giá góc trên bên trái chuẩn Flatsome
         - Không để các nhãn dán dư thừa ở trang chủ
         - Tên sản phẩm hiển thị đầy đủ không thiếu chữ, không tràn viền
    =========================================== -->
    <section id="san-pham-noi-bat" class="py-5">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal flex-wrap gap-2">
                    <h2 class="section-title-main text-sm sm:text-base">
                        SẢN PHẨM TRẦM HƯƠNG NỔI BẬT
                    </h2>
                    <div class="flex flex-wrap items-center gap-1.5 text-[11px]">
                        <button onclick="filterByCategory('all')" class="cat-filter-btn px-2.5 py-1 rounded bg-tram-700 text-white font-medium" data-cat="all">Tất cả</button>
                        <button onclick="filterByCategory('chuoi-tram')" class="cat-filter-btn px-2.5 py-1 rounded bg-white border border-tram-200 text-tram-800 hover:bg-tram-100" data-cat="chuoi-tram">Chuỗi trầm 108 hạt</button>
                        <button onclick="filterByCategory('vong-tay')" class="cat-filter-btn px-2.5 py-1 rounded bg-white border border-tram-200 text-tram-800 hover:bg-tram-100" data-cat="vong-tay">Vòng tay phong thủy</button>
                        <button onclick="filterByCategory('nhang-tram')" class="cat-filter-btn px-2.5 py-1 rounded bg-white border border-tram-200 text-tram-800 hover:bg-tram-100" data-cat="nhang-tram">Nhang trầm</button>
                        <button onclick="filterByCategory('tram-mieng')" class="cat-filter-btn px-2.5 py-1 rounded bg-white border border-tram-200 text-tram-800 hover:bg-tram-100" data-cat="tram-mieng">Giác xông</button>
                    </div>
                </div>
            </div>

            <!-- Grid sản phẩm: 2 cột trên Điện thoại, 4 cột trên Máy tính -->
            <div id="featuredProductsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Được render tự động bằng JavaScript bên dưới từ mảng dữ liệu chuẩn -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME SECTION 4: VÒNG TAY PHONG THỦY & CHUỖI TRẦM HƯƠNG
         (Bố cục giống web mẫu tramhuongdanang.vn)
    =========================================== -->
    <section id="vong-tay-section" class="py-5 bg-tram-100/50 border-t border-b border-tram-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal flex-wrap gap-2">
                    <h2 class="section-title-main text-sm sm:text-base">
                        VÒNG TAY PHONG THỦY & CHUỖI TRẦM HƯƠNG
                    </h2>
                    <div class="flex flex-wrap items-center gap-2 text-[11px] text-tram-700 font-medium">
                        <span class="whitespace-nowrap">Chuỗi trầm 108 hạt</span> •
                        <span class="whitespace-nowrap">Chuỗi trầm mix charm</span> •
                        <span class="whitespace-nowrap">Vòng trầm đơn nam</span> •
                        <span class="whitespace-nowrap">Vòng trầm đơn nữ</span> •
                        <span class="whitespace-nowrap">Vòng trầm bọc vàng</span>
                    </div>
                </div>
            </div>

            <div id="braceletProductsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Render tự động -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME SECTION 5: VẬT PHẨM PHONG THỦY - NHANG TRẦM - GIÁC XÔNG - TRẦM CẢNH
         (Bố cục giống web mẫu tramhuongdanang.vn)
    =========================================== -->
    <section id="nhang-tram-section" class="py-5">
        <div class="flatsome-container">
            <div id="vat-pham-section" class="section-title-container">
                <div class="section-title-normal flex-wrap gap-2">
                    <h2 class="section-title-main text-sm sm:text-base">
                        VẬT PHẨM PHONG THỦY • NHANG TRẦM • GIÁC XÔNG
                    </h2>
                    <div class="flex flex-wrap items-center gap-2 text-[11px] text-tram-700 font-medium">
                        <span class="whitespace-nowrap">Mặt tượng đeo cổ</span> •
                        <span class="whitespace-nowrap">Nhang trầm - Thác lư xông</span> •
                        <span class="whitespace-nowrap">Trầm hương miếng - Giác xông</span> •
                        <span class="whitespace-nowrap">Tranh - Tượng trầm cảnh</span>
                    </div>
                </div>
            </div>

            <div id="incenseProductsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Render tự động -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME SECTION 6: GIỚI THIỆU TRẦM HƯƠNG DUY ĐỨC (Chuẩn mẫu tramhuongdanang.vn)
    =========================================== -->
    <section class="py-6 bg-white border-t border-b border-tram-200">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-7 space-y-3 text-xs sm:text-sm text-tram-800 leading-relaxed">
                    <h2 class="font-serif font-bold text-lg sm:text-xl text-tram-800 uppercase border-l-4 border-tram-400 pl-3">
                        TRẦM HƯƠNG DUY ĐỨC: ĐỊA CHỈ TRẦM HƯƠNG UY TÍN TẠI ĐÀ NẴNG
                    </h2>
                    <p>
                        <strong>Trầm Hương Duy Đức (<a href="https://tramhuongduyduc.com" class="text-tram-600 underline">tramhuongduyduc.com</a>)</strong> là thương hiệu uy tín chuyên chế tác và phân phối các dòng sản phẩm trầm hương thiên nhiên tại Đà Nẵng và trên toàn quốc. Tọa lạc tại <strong>12 Bàu Trảng 2, Phường Thanh Khê, Tp. Đà Nẵng</strong>, chúng tôi cam kết mang đến cho quý khách hàng những tuyệt tác trầm hương chuẩn tự nhiên 100%, giữ trọn vẹn hương thơm ngọt thanh sâu lắng của đất trời.
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-2">
                        <div class="p-3 rounded-lg bg-tram-50 border border-tram-200">
                            <p class="font-bold text-tram-800 mb-1"><i class="fa-solid fa-check-circle text-tram-500 mr-1.5"></i> Trầm hương thiên nhiên 100%</p>
                            <p class="text-xs text-tram-700">Cam kết nguồn gốc trầm tự nhiên rõ ràng, không tẩm hóa chất, an toàn tuyệt đối cho sức khỏe.</p>
                        </div>
                        <div class="p-3 rounded-lg bg-tram-50 border border-tram-200">
                            <p class="font-bold text-tram-800 mb-1"><i class="fa-solid fa-check-circle text-tram-500 mr-1.5"></i> Đa dạng vật phẩm phong thủy</p>
                            <p class="text-xs text-tram-700">Từ chuỗi 108 hạt, vòng tay nam nữ, nhang nụ trầm, giác xông đến tượng trầm cảnh cao cấp.</p>
                        </div>
                        <div class="p-3 rounded-lg bg-tram-50 border border-tram-200">
                            <p class="font-bold text-tram-800 mb-1"><i class="fa-solid fa-check-circle text-tram-500 mr-1.5"></i> Chế tác thủ công tinh xảo</p>
                            <p class="text-xs text-tram-700">Từng hạt trầm được tiện mộc tỉ mỉ, giữ nguyên vân dầu tự nhiên và hương thơm bền lâu.</p>
                        </div>
                        <div class="p-3 rounded-lg bg-tram-50 border border-tram-200">
                            <p class="font-bold text-tram-800 mb-1"><i class="fa-solid fa-check-circle text-tram-500 mr-1.5"></i> Tư vấn & Bảo hành tận tâm</p>
                            <p class="text-xs text-tram-700">Hỗ trợ chọn vòng hợp mệnh phong thủy, thay dây đánh bóng và bảo hành uy tín qua Hotline 0905.244.307.</p>
                        </div>
                    </div>
                </div>

                <!-- Khung bộ ảnh thực tế tại cửa hàng -->
                <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
                    <div class="rounded-xl overflow-hidden border border-tram-300 aspect-square bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1_5Gbpb61zpTaPuEp0kCcUsAHME_JnT_K=w600" data-drive-id="1_5Gbpb61zpTaPuEp0kCcUsAHME_JnT_K" onerror="handleDriveImgError(this, 'Thực tế 1')" alt="Ảnh thực tế Trầm Hương Duy Đức 1" class="w-full h-full object-cover">
                    </div>
                    <div class="rounded-xl overflow-hidden border border-tram-300 aspect-square bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1q2ARJowuXZyCdYBGYvwZQVm2o-fP5mSJ=w600" data-drive-id="1q2ARJowuXZyCdYBGYvwZQVm2o-fP5mSJ" onerror="handleDriveImgError(this, 'Thực tế 2')" alt="Ảnh thực tế Trầm Hương Duy Đức 2" class="w-full h-full object-cover">
                    </div>
                    <div class="rounded-xl overflow-hidden border border-tram-300 aspect-square bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1r_mIywU7mdqhcs_SXJD3e_xOEPk0yare=w600" data-drive-id="1r_mIywU7mdqhcs_SXJD3e_xOEPk0yare" onerror="handleDriveImgError(this, 'Thực tế 3')" alt="Ảnh thực tế Trầm Hương Duy Đức 3" class="w-full h-full object-cover">
                    </div>
                    <div class="rounded-xl overflow-hidden border border-tram-300 aspect-square bg-tram-900 flex flex-col items-center justify-center p-3 text-center">
                        <img src="https://lh3.googleusercontent.com/d/1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM=w300" data-drive-id="1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM" onerror="handleDriveImgError(this, 'Logo')" alt="Logo Trầm Hương Duy Đức" class="w-16 h-16 rounded-full object-cover border border-tram-400 mb-2">
                        <span class="font-serif font-bold text-xs text-tram-300">TRẦM HƯƠNG DUY ĐỨC</span>
                        <span class="text-[11px] text-tram-100 mt-0.5">0905.244.307</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
    =========================================== -->
    <section id="bao-gia" class="py-6 bg-tram-800 text-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                
                <!-- Thông tin cam kết báo giá -->
                <div class="lg:col-span-5 space-y-3">
                    <span class="text-tram-400 text-xs font-semibold uppercase tracking-wider">Hỗ Trợ Khách Hàng 24/7</span>
                    <h2 class="font-serif font-bold text-xl sm:text-2xl text-white leading-snug">
                        ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ SỈ / LẺ
                    </h2>
                    <p class="text-xs sm:text-sm text-tram-100 leading-relaxed">
                        Quý khách cần tư vấn chọn <strong>Vòng Trầm Hương hợp mệnh</strong>, đặt <strong>Set quà tặng doanh nghiệp</strong> hoặc nhận <strong>bảng giá sỉ đại lý</strong>, vui lòng điền thông tin bên cạnh. Trầm Hương Duy Đức sẽ liên hệ lại ngay!
                    </p>
                    <div class="space-y-2 pt-2 text-xs sm:text-sm text-tram-200">
                        <p class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone-volume text-tram-400 w-4"></i>
                            <span>Hotline / Zalo: <strong class="text-tram-300">0905.244.307</strong></span>
                        </p>
                        <p class="flex items-center gap-2.5">
                            <i class="fa-solid fa-location-dot text-tram-400 w-4"></i>
                            <span>Địa chỉ: <strong>12 Bàu Trảng 2, Phường Thanh Khê, Tp.Đà Nẵng</strong></span>
                        </p>
                        <p class="flex items-center gap-2.5">
                            <i class="fa-brands fa-facebook text-tram-400 w-4"></i>
                            <span>Facebook: <a href="https://www.facebook.com/duc.nguyenle.56" target="_blank" rel="noopener noreferrer" class="underline text-tram-300">facebook.com/duc.nguyenle.56</a></span>
                        </p>
                    </div>
                </div>

                <!-- Form Yêu Cầu & Báo Giá -->
                <div class="lg:col-span-7">
                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-tram-900 rounded-xl p-4 sm:p-6 shadow-xl border-2 border-tram-400">
                        <h3 class="font-bold text-sm sm:text-base text-tram-800 uppercase mb-3 border-b border-tram-200 pb-2">
                            <i class="fa-solid fa-file-signature text-tram-600 mr-1.5"></i> GỬI YÊU CẦU & NHẬN BÁO GIÁ NGAY
                        </h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 mb-3">
                            <div>
                                <label class="block text-xs font-semibold text-tram-800 mb-1">Họ và tên của bạn *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 rounded-lg border border-tram-300 text-xs focus:outline-none focus:border-tram-600">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-tram-800 mb-1">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="Nhập số điện thoại..." class="w-full px-3 py-2 rounded-lg border border-tram-300 text-xs focus:outline-none focus:border-tram-600">
                            </div>
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 mb-3">
                            <div>
                                <label class="block text-xs font-semibold text-tram-800 mb-1">Danh mục sản phẩm quan tâm</label>
                                <select id="qCategory" class="w-full px-3 py-2 rounded-lg border border-tram-300 text-xs bg-white focus:outline-none focus:border-tram-600">
                                    <option value="Chuỗi trầm hương 108 hạt">Chuỗi trầm hương 108 hạt</option>
                                    <option value="Vòng tay trầm hương phong thủy">Vòng tay trầm hương phong thủy</option>
                                    <option value="Vòng trầm hương bọc vàng">Vòng trầm hương bọc vàng</option>
                                    <option value="Nhang trầm - Thác lư xông">Nhang trầm - Thác lư xông</option>
                                    <option value="Trầm hương miếng - Giác xông">Trầm hương miếng - Giác xông</option>
                                    <option value="Tranh - Tượng trầm cảnh">Tranh - Tượng trầm cảnh</option>
                                    <option value="Trầm chìm VIP / Báo giá sỉ đại lý">Trầm chìm VIP / Báo giá sỉ đại lý</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-tram-800 mb-1">Hình thức nhận báo giá</label>
                                <select id="qType" class="w-full px-3 py-2 rounded-lg border border-tram-300 text-xs bg-white focus:outline-none focus:border-tram-600">
                                    <option value="Mua lẻ & Tư vấn hợp mệnh">Mua lẻ & Tư vấn hợp mệnh</option>
                                    <option value="Mua sỉ / Chính sách đại lý">Mua sỉ / Chính sách đại lý</option>
                                    <option value="Đặt quà tặng số lượng lớn">Đặt quà tặng số lượng lớn</option>
                                </select>
                            </div>
                        </div>
                        <div class="mb-3">
                            <label class="block text-xs font-semibold text-tram-800 mb-1">Ghi chú yêu cầu (Size tay, năm sinh, số lượng...)</label>
                            <textarea id="qNote" rows="2" placeholder="Ví dụ: Tư vấn vòng trầm nam size 12mm hợp mệnh Kim..." class="w-full px-3 py-2 rounded-lg border border-tram-300 text-xs focus:outline-none focus:border-tram-600"></textarea>
                        </div>
                        <button type="submit" class="w-full py-2.5 rounded-lg bg-tram-700 hover:bg-tram-900 text-tram-300 font-bold text-xs sm:text-sm uppercase tracking-wider transition shadow">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ
                        </button>
                        <div id="quoteSuccessMsg" class="hidden mt-3 p-2.5 rounded-lg bg-green-50 border border-green-300 text-green-800 text-xs font-medium text-center"></div>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (KIẾN THỨC & TIN TỨC)
    =========================================== -->
    <section id="kien-thuc-section" class="py-6">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base">
                        <i class="fa-solid fa-book-open text-tram-600 mr-1.5"></i> KIẾN THỨC PHONG THỦY & TIN TỨC TRẦM HƯƠNG
                    </h2>
                    <span class="text-xs text-tram-600 hidden sm:inline">Cẩm nang chơi trầm chuẩn tự nhiên</span>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl border border-tram-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam=w500" data-drive-id="1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam" onerror="handleDriveImgError(this, 'Bài viết 1')" alt="Trầm hương chìm nước là gì" class="w-full h-full object-cover hover:scale-105 transition">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-tram-600 font-semibold uppercase">Kiến thức Trầm Hương</span>
                            <h3 class="font-bold text-xs sm:text-sm text-tram-900 mt-1 mb-1.5 leading-snug">
                                Trầm Hương Chìm Nước Là Gì? Vì Sao Giá Trị Cao Hơn Các Loại Trầm Khác?
                            </h3>
                            <p class="text-xs text-tram-700 leading-relaxed">
                                Tìm hiểu nguyên nhân vì sao lượng tinh dầu tích tụ lâu năm giúp khối gỗ trầm chìm hoàn toàn trong nước và mang giá trị sưu tầm cao...
                            </p>
                        </div>
                        <button onclick="openArticleModal(0)" class="mt-3 text-left text-xs font-semibold text-tram-600 hover:text-tram-800">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl border border-tram-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1SYfpAmouYH7GsC721KqBHf2tCg6w9Kgh=w500" data-drive-id="1SYfpAmouYH7GsC721KqBHf2tCg6w9Kgh" onerror="handleDriveImgError(this, 'Bài viết 2')" alt="Cách phân biệt trầm hương thật giả" class="w-full h-full object-cover hover:scale-105 transition">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-tram-600 font-semibold uppercase">Kinh nghiệm chọn trầm</span>
                            <h3 class="font-bold text-xs sm:text-sm text-tram-900 mt-1 mb-1.5 leading-snug">
                                Cách Phân Biệt Trầm Hương Thật Giả Chuẩn Xác Từ Chuyên Gia Duy Đức
                            </h3>
                            <p class="text-xs text-tram-700 leading-relaxed">
                                Hướng dẫn quan sát vân dầu tự nhiên, cảm nhận mùi hương ngọt dịu thoang thoảng để phân biệt trầm tự nhiên với trầm nấu dầu...
                            </p>
                        </div>
                        <button onclick="openArticleModal(1)" class="mt-3 text-left text-xs font-semibold text-tram-600 hover:text-tram-800">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl border border-tram-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1_5Gbpb61zpTaPuEp0kCcUsAHME_JnT_K=w500" data-drive-id="1_5Gbpb61zpTaPuEp0kCcUsAHME_JnT_K" onerror="handleDriveImgError(this, 'Bài viết 3')" alt="Trầm hương xông nhà có tác dụng gì" class="w-full h-full object-cover hover:scale-105 transition">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-tram-600 font-semibold uppercase">Phong thủy đời sống</span>
                            <h3 class="font-bold text-xs sm:text-sm text-tram-900 mt-1 mb-1.5 leading-snug">
                                Trầm Hương Xông Nhà Có Tác Dụng Gì? Cách Xông Trầm Đón Tài Lộc
                            </h3>
                            <p class="text-xs text-tram-700 leading-relaxed">
                                Xông trầm hương miếng và nụ trầm giúp thanh lọc không khí, khử uế khí, mang lại nguồn năng lượng ấm áp cho gia đạo và cửa hàng...
                            </p>
                        </div>
                        <button onclick="openArticleModal(2)" class="mt-3 text-left text-xs font-semibold text-tram-600 hover:text-tram-800">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl border border-tram-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-tram-100">
                        <img src="https://lh3.googleusercontent.com/d/1dOpYD6HEfAu_zsBxZL1Mgv5LQczo2UYZ=w500" data-drive-id="1dOpYD6HEfAu_zsBxZL1Mgv5LQczo2UYZ" onerror="handleDriveImgError(this, 'Bài viết 4')" alt="Ý nghĩa đeo vòng tay trầm hương 108 hạt" class="w-full h-full object-cover hover:scale-105 transition">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-tram-600 font-semibold uppercase">Tư vấn phong thủy</span>
                            <h3 class="font-bold text-xs sm:text-sm text-tram-900 mt-1 mb-1.5 leading-snug">
                                Đeo Vòng Tay Trầm Hương 108 Hạt Có Tác Dụng Gì? 4 Công Dụng Nổi Bật
                            </h3>
                            <p class="text-xs text-tram-700 leading-relaxed">
                                Chuỗi 108 hạt trầm hương tượng trưng cho sự bình an, giúp giảm căng thẳng mệt mỏi và thu hút may mắn trong công việc kinh doanh...
                            </p>
                        </div>
                        <button onclick="openArticleModal(3)" class="mt-3 text-left text-xs font-semibold text-tram-600 hover:text-tram-800">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </button>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME SECTION 9: FACEBOOK & BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ
         - Đưa Facebook https://www.facebook.com/duc.nguyenle.56 ra ngoài trang chủ
         - Đưa ảnh & bản đồ Google Map địa chỉ 12 Bàu Trảng 2, Phường Thanh Khê, Tp.Đà Nẵng ra ngoài trang chủ
    =========================================== -->
    <section class="py-6 bg-white border-t border-tram-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base">
                        <i class="fa-solid fa-map-location-dot text-tram-600 mr-1.5"></i> KẾT NỐI FACEBOOK & BẢN ĐỒ CHỈ ĐƯỜNG TRẦM HƯƠNG DUY ĐỨC
                    </h2>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                
                <!-- Khung Facebook Chính Thức ngoài trang chủ -->
                <div class="lg:col-span-5 bg-tram-50 rounded-xl border border-tram-200 p-4 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between border-b border-tram-200 pb-3 mb-3">
                            <div class="flex items-center gap-2.5">
                                <div class="w-12 h-12 rounded-full overflow-hidden border-2 border-[#1877F2] bg-tram-900 flex-shrink-0">
                                    <img src="https://lh3.googleusercontent.com/d/1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM=w300" data-drive-id="1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM" onerror="handleDriveImgError(this, 'FB')" alt="Facebook Trầm Hương Duy Đức" class="w-full h-full object-cover">
                                </div>
                                <div>
                                    <h3 class="font-bold text-sm text-tram-900 flex items-center gap-1">
                                        Trầm Hương Duy Đức
                                        <i class="fa-solid fa-circle-check text-[#1877F2] text-xs"></i>
                                    </h3>
                                    <p class="text-[11px] text-tram-600">Facebook: Nguyễn Lê Đức (@duc.nguyenle.56)</p>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/duc.nguyenle.56" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold flex items-center gap-1.5 shadow-xs transition">
                                <i class="fa-brands fa-facebook"></i> Kết nối
                            </a>
                        </div>

                        <p class="text-xs text-tram-800 mb-3 leading-relaxed">
                            Theo dõi trang Facebook chính thức của <strong>Trầm Hương Duy Đức</strong> để xem video quay cận cảnh từng thớ dầu trầm hương thực tế và cập nhật ưu đãi mới nhất mỗi ngày.
                        </p>

                        <!-- Hình ảnh bài đăng thực tế từ Google Drive trên khung Facebook -->
                        <div class="grid grid-cols-3 gap-2 mb-3">
                            <a href="https://www.facebook.com/duc.nguyenle.56" target="_blank" rel="noopener noreferrer" class="rounded-lg overflow-hidden aspect-square border border-tram-200 block">
                                <img src="https://lh3.googleusercontent.com/d/1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam=w300" data-drive-id="1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam" onerror="handleDriveImgError(this, 'FB 1')" alt="Ảnh Facebook 1" class="w-full h-full object-cover hover:scale-105 transition">
                            </a>
                            <a href="https://www.facebook.com/duc.nguyenle.56" target="_blank" rel="noopener noreferrer" class="rounded-lg overflow-hidden aspect-square border border-tram-200 block">
                                <img src="https://lh3.googleusercontent.com/d/1SYfpAmouYH7GsC721KqBHf2tCg6w9Kgh=w300" data-drive-id="1SYfpAmouYH7GsC721KqBHf2tCg6w9Kgh" onerror="handleDriveImgError(this, 'FB 2')" alt="Ảnh Facebook 2" class="w-full h-full object-cover hover:scale-105 transition">
                            </a>
                            <a href="https://www.facebook.com/duc.nguyenle.56" target="_blank" rel="noopener noreferrer" class="rounded-lg overflow-hidden aspect-square border border-tram-200 block">
                                <img src="https://lh3.googleusercontent.com/d/1kdtLUOXuyN1Or7ZU9vwrpiUfRU_adfnj=w300" data-drive-id="1kdtLUOXuyN1Or7ZU9vwrpiUfRU_adfnj" onerror="handleDriveImgError(this, 'FB 3')" alt="Ảnh Facebook 3" class="w-full h-full object-cover hover:scale-105 transition">
                            </a>
                        </div>
                    </div>

                    <a href="https://www.facebook.com/duc.nguyenle.56" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-semibold text-xs text-center block transition">
                        <i class="fa-brands fa-facebook-messenger mr-1.5"></i> Truy Cập Facebook: facebook.com/duc.nguyenle.56
                    </a>
                </div>

                <!-- Khung Bản Đồ Google Maps & Ảnh Sơ Đồ Địa Chỉ 12 Bàu Trảng 2 ngoài trang chủ -->
                <div class="lg:col-span-7 bg-tram-50 rounded-xl border border-tram-200 p-4 flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                        <div>
                            <h3 class="font-bold text-sm text-tram-900">
                                <i class="fa-solid fa-location-dot text-red-600 mr-1"></i> Địa chỉ: 12 Bàu Trảng 2, Phường Thanh Khê, Tp.Đà Nẵng
                            </h3>
                            <p class="text-xs text-tram-700">Điện thoại chỉ đường: <strong>0905.244.307</strong> (Mở cửa: 07:30 - 21:30 hàng ngày)</p>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=12+B%C3%A0u+Tr%E1%BA%A3ng+2+Ph%C6%B0%E1%BB%9Dng+Thanh+Kh%C3%AA+Đ%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-tram-700 hover:bg-tram-900 text-tram-300 text-xs font-semibold flex items-center gap-1.5 transition">
                            <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps Lớn
                        </a>
                    </div>

                    <!-- Bản đồ Google Maps trực tiếp ngoài trang chủ -->
                    <div class="w-full h-64 sm:h-72 rounded-xl overflow-hidden border border-tram-300 shadow-inner bg-tram-100 relative">
                        <iframe 
                            title="Bản đồ Google Map Trầm Hương Duy Đức 12 Bàu Trảng 2 Thanh Khê Đà Nẵng"
                            src="https://maps.google.com/maps?q=12%20B%C3%A0u%20Tr%E1%BA%A3ng%202,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME SECTION 10: DANH MỤC CÁC ĐỐI TÁC ĐỒNG HÀNH
    =========================================== -->
    <section class="py-6 bg-tram-100/60 border-t border-tram-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base">
                        <i class="fa-solid fa-handshake text-tram-600 mr-1.5"></i> ĐỐI TÁC ĐỒNG HÀNH & LIÊN KẾT
                    </h2>
                    <span class="text-xs text-tram-600 hidden sm:inline">Hợp tác phát triển bền vững</span>
                </div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="bg-white p-3 rounded-xl border border-tram-200 flex flex-col items-center justify-center text-center shadow-2xs">
                    <i class="fa-solid fa-award text-2xl text-tram-500 mb-1.5"></i>
                    <span class="text-xs font-bold text-tram-800">Hội Trầm Hương VN</span>
                    <span class="text-[10px] text-tram-600">Đối tác chuyên môn</span>
                </div>
                <div class="bg-white p-3 rounded-xl border border-tram-200 flex flex-col items-center justify-center text-center shadow-2xs">
                    <i class="fa-solid fa-tree text-2xl text-tram-600 mb-1.5"></i>
                    <span class="text-xs font-bold text-tram-800">Làng Nghề Tiên Cảnh</span>
                    <span class="text-[10px] text-tram-600">Nguồn nguyên liệu Dó Bầu</span>
                </div>
                <div class="bg-white p-3 rounded-xl border border-tram-200 flex flex-col items-center justify-center text-center shadow-2xs">
                    <i class="fa-solid fa-gem text-2xl text-tram-500 mb-1.5"></i>
                    <span class="text-xs font-bold text-tram-800">Phong Thủy Đà Thành</span>
                    <span class="text-[10px] text-tram-600">Đối tác phân phối</span>
                </div>
                <div class="bg-white p-3 rounded-xl border border-tram-200 flex flex-col items-center justify-center text-center shadow-2xs">
                    <i class="fa-solid fa-truck-fast text-2xl text-tram-600 mb-1.5"></i>
                    <span class="text-xs font-bold text-tram-800">Viettel Post</span>
                    <span class="text-[10px] text-tram-600">Đối tác vận chuyển COD</span>
                </div>
                <div class="bg-white p-3 rounded-xl border border-tram-200 flex flex-col items-center justify-center text-center shadow-2xs">
                    <i class="fa-solid fa-box-open text-2xl text-tram-500 mb-1.5"></i>
                    <span class="text-xs font-bold text-tram-800">Giao Hàng Nhanh</span>
                    <span class="text-[10px] text-tram-600">Giao nhanh toàn quốc</span>
                </div>
                <div class="bg-white p-3 rounded-xl border border-tram-200 flex flex-col items-center justify-center text-center shadow-2xs">
                    <i class="fa-solid fa-building-columns text-2xl text-tram-600 mb-1.5"></i>
                    <span class="text-xs font-bold text-tram-800">Vietcombank & VietQR</span>
                    <span class="text-[10px] text-tram-600">Đối tác thanh toán</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FLATSOME FOOTER
    =========================================== -->
    <footer class="bg-tram-900 text-tram-100 pt-8 pb-20 sm:pb-8 border-t-4 border-tram-400">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-tram-700 text-xs">
                
                <!-- Cột 1: Thông tin liên hệ -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM=w200" data-drive-id="1JvTmrpglCH_eyMVMotOcMBPoMYRW6SvM" onerror="handleDriveImgError(this, 'Logo')" alt="Logo Trầm Hương Duy Đức" class="w-10 h-10 rounded-full object-cover border border-tram-400">
                        <div>
                            <h3 class="font-serif font-bold text-sm text-tram-300 uppercase">TRẦM HƯƠNG DUY ĐỨC</h3>
                            <p class="text-[11px] text-tram-400">tramhuongduyduc.com</p>
                        </div>
                    </div>
                    <p class="text-tram-200 leading-relaxed">
                        Chuyên cung cấp sản phẩm trầm hương phong thủy tự nhiên: Chuỗi hạt 108, vòng tay nam nữ, nhang trầm, giác xông, tượng trầm cảnh và quà tặng cao cấp.
                    </p>
                    <ul class="space-y-1.5 text-tram-100">
                        <li><i class="fa-solid fa-location-dot text-tram-400 w-4"></i> <strong>Địa chỉ:</strong> 12 Bàu Trảng 2, Phường Thanh Khê, Tp.Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-tram-400 w-4"></i> <strong>Hotline / Zalo:</strong> <a href="tel:0905244307" class="text-tram-300 font-bold">0905.244.307</a></li>
                        <li><i class="fa-solid fa-globe text-tram-400 w-4"></i> <strong>Website:</strong> tramhuongduyduc.com</li>
                        <li><i class="fa-brands fa-facebook text-tram-400 w-4"></i> <strong>Facebook:</strong> <a href="https://www.facebook.com/duc.nguyenle.56" target="_blank" rel="noopener noreferrer" class="underline hover:text-tram-300">facebook.com/duc.nguyenle.56</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="font-bold text-sm text-tram-300 uppercase mb-3 border-b border-tram-700 pb-1.5">DANH MỤC SẢN PHẨM</h4>
                    <ul class="space-y-2 text-tram-200">
                        <li><a href="#san-pham-noi-bat" onclick="filterByCategory('chuoi-tram')" class="hover:text-tram-400 transition">• Chuỗi trầm hương 108 hạt & 216 hạt</a></li>
                        <li><a href="#vong-tay-section" onclick="filterByCategory('vong-tay')" class="hover:text-tram-400 transition">• Vòng tay trầm hương phong thủy</a></li>
                        <li><a href="#vong-tay-section" onclick="filterByCategory('vong-tay')" class="hover:text-tram-400 transition">• Vòng trầm hương bọc vàng</a></li>
                        <li><a href="#nhang-tram-section" onclick="filterByCategory('nhang-tram')" class="hover:text-tram-400 transition">• Nhang trầm không tăm & Thác lư xông</a></li>
                        <li><a href="#nhang-tram-section" onclick="filterByCategory('tram-mieng')" class="hover:text-tram-400 transition">• Trầm hương miếng, giác xông, bột trầm</a></li>
                        <li><a href="#vat-pham-section" onclick="filterByCategory('tranh-tuong')" class="hover:text-tram-400 transition">• Tranh - Tượng trầm cảnh & Mặt Phật</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách khách hàng -->
                <div>
                    <h4 class="font-bold text-sm text-tram-300 uppercase mb-3 border-b border-tram-700 pb-1.5">CHÍNH SÁCH & HỖ TRỢ</h4>
                    <ul class="space-y-2 text-tram-200">
                        <li><a href="#bao-gia" class="hover:text-tram-400 transition">• Hướng dẫn mua hàng & Đặt hàng</a></li>
                        <li><a href="#bao-gia" class="hover:text-tram-400 transition">• Chính sách bảo hành mùi hương</a></li>
                        <li><a href="#bao-gia" class="hover:text-tram-400 transition">• Chính sách đổi trả sản phẩm</a></li>
                        <li><a href="#bao-gia" class="hover:text-tram-400 transition">• Hình thức vận chuyển & Kiểm hàng COD</a></li>
                        <li><a href="#bao-gia" class="hover:text-tram-400 transition">• Chính sách chiết khấu Đại lý / Khách sỉ</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Cam kết chất lượng -->
                <div>
                    <h4 class="font-bold text-sm text-tram-300 uppercase mb-3 border-b border-tram-700 pb-1.5">CAM KẾT TỪ DUY ĐỨC</h4>
                    <div class="p-3.5 rounded-xl bg-tram-800 border border-tram-600 space-y-2 text-tram-100">
                        <p><i class="fa-solid fa-shield-halved text-tram-400 mr-1.5"></i> Đền bù gấp 10 lần nếu phát hiện trầm giả, trầm tẩm hóa chất.</p>
                        <p><i class="fa-solid fa-box text-tram-400 mr-1.5"></i> Tặng kèm hộp nhung sang trọng, thẻ bảo hành & dây dự phòng.</p>
                        <p><i class="fa-solid fa-headset text-tram-400 mr-1.5"></i> Hỗ trợ tư vấn trực tiếp qua Zalo / Hotline: <strong class="text-tram-300">0905.244.307</strong></p>
                    </div>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-[11px] text-tram-300 gap-2 text-center">
                <p>Copyright 2026 © <strong>tramhuongduyduc.com</strong> - Trầm Hương Duy Đức Đà Nẵng.</p>
                <p>Địa chỉ: 12 Bàu Trảng 2, Phường Thanh Khê, Tp. Đà Nẵng | SĐT: 0905.244.307</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         - Tương thích trên cả máy tính và điện thoại
         - Không gây tràn viền
    =========================================== -->
    <div class="fixed bottom-3 right-3 z-40 flex flex-col items-end gap-2">
        
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0905244307" target="_blank" rel="noopener noreferrer" 
           class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg border border-white/30 transition transform hover:-translate-y-0.5">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[10px] flex items-center justify-center flex-shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook nổi bật -->
        <a href="https://www.facebook.com/duc.nguyenle.56" target="_blank" rel="noopener noreferrer" 
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg border border-white/30 transition transform hover:-translate-y-0.5">
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center flex-shrink-0">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span class="text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0905244307" 
           class="contact-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg border border-tram-300 transition">
            <span class="w-6 h-6 rounded-full bg-white text-red-600 flex items-center justify-center flex-shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-bold pr-1">0905.244.307</span>
        </a>

    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT HÀNG NHANH
    =========================================== -->
    <div id="productModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3 bg-black/65 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border border-tram-300 max-h-[90vh] overflow-y-auto">
            <div class="p-3.5 bg-tram-800 text-white flex items-center justify-between">
                <span class="font-serif font-bold text-sm text-tram-300">CHI TIẾT SẢN PHẨM TRẦM HƯƠNG DUY ĐỨC</span>
                <button onclick="closeProductModal()" class="w-7 h-7 rounded-full bg-tram-700 text-white flex items-center justify-center">
                    <i class="fa-solid fa-xmark text-sm"></i>
                </button>
            </div>
            <div id="productModalContent" class="p-4 sm:p-6"></div>
        </div>
    </div>

    <!-- ==========================================
         MODAL GIỎ HÀNG
    =========================================== -->
    <div id="cartModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3 bg-black/65 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-lg w-full overflow-hidden shadow-2xl border border-tram-300 max-h-[90vh] flex flex-col">
            <div class="p-3.5 bg-tram-800 text-white flex items-center justify-between">
                <span class="font-serif font-bold text-sm text-tram-300"><i class="fa-solid fa-bag-shopping mr-1.5"></i> GIỎ HÀNG CỦA BẠN</span>
                <button onclick="closeCartModal()" class="w-7 h-7 rounded-full bg-tram-700 text-white flex items-center justify-center">
                    <i class="fa-solid fa-xmark text-sm"></i>
                </button>
            </div>
            <div id="cartModalBody" class="p-4 overflow-y-auto flex-1 space-y-3 text-xs"></div>
        </div>
    </div>

    <!-- ==========================================
         MODAL ĐỌC BÀI VIẾT KIẾN THỨC
    =========================================== -->
    <div id="articleModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3 bg-black/65 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-xl w-full overflow-hidden shadow-2xl border border-tram-300 max-h-[88vh] flex flex-col">
            <div class="p-3.5 bg-tram-800 text-white flex items-center justify-between">
                <span class="font-serif font-bold text-sm text-tram-300">KIẾN THỨC TRẦM HƯƠNG DUY ĐỨC</span>
                <button onclick="closeArticleModal()" class="w-7 h-7 rounded-full bg-tram-700 text-white flex items-center justify-center">
                    <i class="fa-solid fa-xmark text-sm"></i>
                </button>
            </div>
            <div id="articleModalBody" class="p-4 sm:p-5 overflow-y-auto text-xs sm:text-sm space-y-3 text-tram-900 leading-relaxed"></div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM, SLIDER, GIỎ HÀNG & FALLBACK ẢNH GOOGLE DRIVE
    =========================================== -->
    <script>
        /* Xử lý dự phòng đa tầng cho ảnh Google Drive để luôn hiển thị 100% */
        function handleDriveImgError(imgEl, labelText) {
            const driveId = imgEl.getAttribute('data-drive-id');
            const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
            if (driveId && step === 0) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w800';
            } else if (driveId && step === 1) {
                imgEl.setAttribute('data-fallback-step', '2');
                imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
            } else {
                imgEl.onerror = null;
                imgEl.src = 'https://placehold.co/600x600/42220b/d4af37?text=' + encodeURIComponent(labelText || 'Tram Huong Duy Duc');
            }
        }

        /* Danh sách 7 ID ảnh thực tế từ Google Drive của khách hàng */
        const DRIVE_IMAGES = {
            img1: '1E7I7zffwwecFTB7EBK4cm7G-PH8xPYam',
            img2: '1SYfpAmouYH7GsC721KqBHf2tCg6w9Kgh',
            img3: '1dOpYD6HEfAu_zsBxZL1Mgv5LQczo2UYZ',
            img4: '1kdtLUOXuyN1Or7ZU9vwrpiUfRU_adfnj',
            img5: '1_5Gbpb61zpTaPuEp0kCcUsAHME_JnT_K',
            img6: '1q2ARJowuXZyCdYBGYvwZQVm2o-fP5mSJ',
            img7: '1r_mIywU7mdqhcs_SXJD3e_xOEPk0yare'
        };

        /* Dữ liệu Sản phẩm chuẩn theo danh mục web mẫu tramhuongdanang.vn kết hợp 7 ảnh thực tế */
        const PRODUCTS = [
            {
                id: 1,
                name: 'VÒNG TRẦM HƯƠNG THIÊN NHIÊN 108 HẠT MIX CHARM PHONG THỦY',
                category: 'chuoi-tram',
                categoryName: 'Chuỗi trầm hương',
                driveId: DRIVE_IMAGES.img1,
                oldPrice: 1200000,
                price: 960000,
                discount: 20,
                section: 'both-bracelet',
                desc: 'Chuỗi 108 hạt trầm hương tự nhiên 100%, vân dầu đẹp, hương thơm dịu nhẹ giúp an thần, thu hút bình an và tài lộc.'
            },
            {
                id: 2,
                name: 'CHUỖI TRẦM BÔNG 8MM 108 HẠT MỘC TỰ NHIÊN 100% BÔNG DẦU ĐẸP',
                category: 'chuoi-tram',
                categoryName: 'Chuỗi trầm hương',
                driveId: DRIVE_IMAGES.img2,
                oldPrice: 3600000,
                price: 3000000,
                discount: 17,
                section: 'both-bracelet',
                desc: 'Chuỗi trầm hương bông dầu mộc 100% không đánh sáp, thớ dầu rõ nét, hương thơm ngọt thanh tự nhiên.'
            },
            {
                id: 3,
                name: 'VÒNG TAY TRẦM HƯƠNG TỐC KIẾN TỰ NHIÊN SIZE NAM NỮ',
                category: 'vong-tay',
                categoryName: 'Vòng tay phong thủy',
                driveId: DRIVE_IMAGES.img3,
                oldPrice: 1100000,
                price: 750000,
                discount: 32,
                section: 'both-bracelet',
                desc: 'Vòng tay trầm hương tốc kiến rừng tự nhiên, hạt tròn đều, mùi thơm ấm áp bền lâu, tặng kèm hộp nhung sang trọng.'
            },
            {
                id: 4,
                name: 'VÒNG TRẦM HƯƠNG TỐC KIẾN BỌC VÀNG PHONG THỦY SANG TRỌNG',
                category: 'vong-tay',
                categoryName: 'Vòng trầm hương bọc vàng',
                driveId: DRIVE_IMAGES.img4,
                oldPrice: 6800000,
                price: 6000000,
                discount: 12,
                section: 'both-bracelet',
                desc: 'Vòng trầm hương khối đốt trúc bọc kim tiền sang trọng, biểu tượng chiêu tài lộc và may mắn cho người đeo.'
            },
            {
                id: 5,
                name: 'TRẦM HƯƠNG MIẾNG XÔNG NHÀ - GIÁC XÔNG TRẦM TỰ NHIÊN CAO CẤP',
                category: 'tram-mieng',
                categoryName: 'Trầm hương miếng - Giác xông',
                driveId: DRIVE_IMAGES.img5,
                oldPrice: 480000,
                price: 400000,
                discount: 17,
                section: 'both-incense',
                desc: 'Trầm miếng xông đốt tự nhiên nhiều dầu, khói thơm ngọt sâu giúp thanh lọc không khí, xông nhà mới, khai trương.'
            },
            {
                id: 6,
                name: 'NHANG TRẦM KHÔNG TĂM THƯỢNG HẠNG & NỤ TRẦM HƯƠNG NGUYÊN CHẤT',
                category: 'nhang-tram',
                categoryName: 'Nhang trầm - Thác lư xông',
                driveId: DRIVE_IMAGES.img6,
                oldPrice: 200000,
                price: 150000,
                discount: 25,
                section: 'both-incense',
                desc: 'Làm từ 100% bột trầm hương nguyên chất tự nhiên, không hóa chất, dùng cho thác khói, lư xông và phòng trà.'
            },
            {
                id: 7,
                name: 'TƯỢNG TRẦM CẢNH PHONG THỦY & MẶT TƯỢNG PHẬT BẢN MỆNH TRẦM HƯƠNG',
                category: 'tranh-tuong',
                categoryName: 'Tranh - Tượng trầm cảnh',
                driveId: DRIVE_IMAGES.img7,
                oldPrice: 1200000,
                price: 850000,
                discount: 29,
                section: 'both-incense',
                desc: 'Chế tác thủ công tỉ mỉ từ phôi trầm hương tự nhiên, thích hợp trưng bàn làm việc, ô tô hoặc đeo cổ hộ mệnh.'
            },
            {
                id: 8,
                name: 'VÒNG TRẦM VIP GIÀ DẦU BANH ĐỎ 108 HẠT 8MM CAO CẤP DUY ĐỨC',
                category: 'tram-chim',
                categoryName: 'Trầm chìm VIP cao cấp',
                driveId: DRIVE_IMAGES.img1,
                oldPrice: 18000000,
                price: 16000000,
                discount: 11,
                section: 'both-bracelet',
                desc: 'Dòng trầm hương VIP già dầu banh đỏ quý hiếm, hương sống ngọt sâu quyến rũ, kèm chứng nhận bảo hành trọn đời.'
            },
            {
                id: 9,
                name: 'VÒNG TRẦM HƯƠNG THIÊN NHIÊN MIX LU THỐNG ĐỦ MỆNH NAM NỮ',
                category: 'vong-tay',
                categoryName: 'Vòng tay phong thủy',
                driveId: DRIVE_IMAGES.img2,
                oldPrice: 360000,
                price: 250000,
                discount: 31,
                section: 'bracelet-only',
                desc: 'Vòng trầm hương tự nhiên kết hợp charm Lu Thống phong thủy hanh thông mọi việc, đủ màu theo ngũ hành.'
            },
            {
                id: 10,
                name: 'VÒNG TAY TRẦM HƯƠNG 12MM BÔNG DẦU ĐẸP THƠM SỐNG RÕ',
                category: 'vong-tay',
                categoryName: 'Vòng trầm đơn nam',
                driveId: DRIVE_IMAGES.img3,
                oldPrice: 1500000,
                price: 1250000,
                discount: 17,
                section: 'bracelet-only',
                desc: 'Size hạt 12mm mạnh mẽ, nam tính, sớ dầu chạy đều quanh hạt, càng đeo càng lên nước bóng đẹp.'
            },
            {
                id: 11,
                name: 'COMBO VÒNG TRẦM HƯƠNG ĐEO CỔ VÀ VÒNG ĐEO TAY PHONG THỦY',
                category: 'chuoi-tram',
                categoryName: 'Chuỗi trầm hương',
                driveId: DRIVE_IMAGES.img4,
                oldPrice: 900000,
                price: 650000,
                discount: 28,
                section: 'bracelet-only',
                desc: 'Bộ đôi chuỗi đeo cổ và vòng tay trầm hương đồng bộ, thích hợp làm quà biếu tặng người thân, đối tác.'
            },
            {
                id: 12,
                name: 'BỘ LƯ XÔNG TRẦM & THÁC KHÓI TRẦM HƯƠNG PHONG THỦY CAO CẤP',
                category: 'nhang-tram',
                categoryName: 'Nhang trầm - Thác lư xông',
                driveId: DRIVE_IMAGES.img5,
                oldPrice: 450000,
                price: 350000,
                discount: 22,
                section: 'incense-only',
                desc: 'Dụng cụ thưởng trầm tinh tế dùng đốt nụ trầm, trầm miếng, giác xông giúp lan tỏa hương trầm ấm cúng.'
            }
        ];

        function formatVND(amount) {
            return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + '₫';
        }

        /* Tạo HTML chuẩn Flatsome cho từng thẻ sản phẩm:
           - Chỉ có duy nhất badge -% giảm giá ở góc trên bên trái (top-2 left-2)
           - Không có nhãn dán phụ nào khác
           - Tên sản phẩm hiển thị đầy đủ 100%, không bị cắt chữ hay tràn ra ngoài */
        function createProductCardHTML(product) {
            const imgUrl = 'https://lh3.googleusercontent.com/d/' + product.driveId + '=w600';
            return `
                <div class="bg-white rounded-xl border border-tram-200 hover:border-tram-400 shadow-xs hover:shadow-md transition flex flex-col justify-between overflow-hidden group">
                    <div>
                        <div onclick="openProductModal(${product.id})" class="relative aspect-square w-full bg-tram-100 overflow-hidden cursor-pointer">
                            <!-- Badge % giảm giá góc trên bên trái chuẩn Flatsome -->
                            <span class="absolute top-2 left-2 z-10 bg-[#b91c1c] text-white text-[10px] sm:text-xs font-bold px-2 py-0.5 rounded-md shadow">
                                -${product.discount}%
                            </span>
                            <img src="${imgUrl}"
                                 data-drive-id="${product.driveId}"
                                 onerror="handleDriveImgError(this, '${product.categoryName}')"
                                 alt="${product.name}"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <p class="text-[10px] text-tram-600 uppercase tracking-wider mb-1">${product.categoryName}</p>
                            <h3 onclick="openProductModal(${product.id})" class="product-title-full font-semibold text-xs sm:text-[13px] text-tram-900 hover:text-tram-600 cursor-pointer mb-2">
                                ${product.name}
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 border-t border-tram-100">
                        <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                            <del class="text-[11px] text-gray-400">${formatVND(product.oldPrice)}</del>
                            <span class="text-xs sm:text-sm font-bold text-[#b91c1c]">${formatVND(product.price)}</span>
                        </div>
                        <div class="grid grid-cols-2 gap-1.5">
                            <button onclick="addToCart(${product.id})" class="py-1.5 px-2 rounded-lg bg-tram-100 hover:bg-tram-200 text-tram-800 font-semibold text-[11px] transition text-center">
                                + Giỏ hàng
                            </button>
                            <button onclick="openProductModal(${product.id})" class="py-1.5 px-2 rounded-lg bg-tram-700 hover:bg-tram-900 text-tram-300 font-semibold text-[11px] transition text-center">
                                Mua ngay
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        function renderAllSections(filterCat = 'all', searchKeyword = '') {
            const featuredGrid = document.getElementById('featuredProductsGrid');
            const braceletGrid = document.getElementById('braceletProductsGrid');
            const incenseGrid = document.getElementById('incenseProductsGrid');

            const keyword = searchKeyword.trim().toLowerCase();

            // Lọc danh sách sản phẩm nổi bật
            const featuredList = PRODUCTS.slice(0, 8).filter(p => {
                const matchCat = (filterCat === 'all') || (p.category === filterCat);
                const matchSearch = !keyword || p.name.toLowerCase().includes(keyword) || p.categoryName.toLowerCase().includes(keyword);
                return matchCat && matchSearch;
            });

            if (featuredList.length === 0) {
                featuredGrid.innerHTML = `<div class="col-span-2 lg:col-span-4 py-8 text-center text-xs text-tram-700 bg-white rounded-xl border border-tram-200">Không tìm thấy sản phẩm phù hợp. <button onclick="filterByCategory('all')" class="underline font-bold text-tram-800 ml-1">Xem tất cả sản phẩm</button></div>`;
            } else {
                featuredGrid.innerHTML = featuredList.map(createProductCardHTML).join('');
            }

            // Vòng tay & Chuỗi trầm
            const braceletList = PRODUCTS.filter(p => p.category === 'chuoi-tram' || p.category === 'vong-tay' || p.category === 'tram-chim').slice(0, 8);
            braceletGrid.innerHTML = braceletList.map(createProductCardHTML).join('');

            // Nhang trầm, Giác xông, Trầm cảnh
            const incenseList = PRODUCTS.filter(p => p.category === 'nhang-tram' || p.category === 'tram-mieng' || p.category === 'tranh-tuong');
            incenseGrid.innerHTML = incenseList.map(createProductCardHTML).join('');
        }

        function filterByCategory(cat) {
            document.querySelectorAll('.cat-filter-btn').forEach(btn => {
                if (btn.getAttribute('data-cat') === cat) {
                    btn.className = 'cat-filter-btn px-2.5 py-1 rounded bg-tram-700 text-white font-medium';
                } else {
                    btn.className = 'cat-filter-btn px-2.5 py-1 rounded bg-white border border-tram-200 text-tram-800 hover:bg-tram-100';
                }
            });
            renderAllSections(cat, '');
            const el = document.getElementById('san-pham-noi-bat');
            if (el) el.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }

        function searchProducts(keyword) {
            renderAllSections('all', keyword);
        }

        /* Slider 2 Banner Tự Trượt Chuyên Nghiệp */
        let currentBanner = 0;
        const totalBanners = 2;
        let bannerInterval = null;

        function showBanner(index) {
            currentBanner = (index + totalBanners) % totalBanners;
            for (let i = 0; i < totalBanners; i++) {
                const slide = document.getElementById('bannerSlide' + i);
                const dot = document.getElementById('bannerDot' + i);
                if (i === currentBanner) {
                    slide.classList.remove('hidden');
                    dot.className = 'w-6 h-1.5 rounded-full bg-tram-400 transition-all';
                } else {
                    slide.classList.add('hidden');
                    dot.className = 'w-2 h-1.5 rounded-full bg-white/50 transition-all';
                }
            }
        }
        function nextBanner() {
            showBanner(currentBanner + 1);
            resetBannerTimer();
        }
        function prevBanner() {
            showBanner(currentBanner - 1);
            resetBannerTimer();
        }
        function goToBanner(idx) {
            showBanner(idx);
            resetBannerTimer();
        }
        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBanner(currentBanner + 1);
            }, 4500);
        }

        /* Menu Mobile */
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        /* Giỏ hàng & Đặt hàng */
        let cart = [];

        function updateCartBadge() {
            const count = cart.reduce((sum, item) => sum + item.qty, 0);
            document.getElementById('cartCountBadge').textContent = count;
        }

        function addToCart(productId) {
            const prod = PRODUCTS.find(p => p.id === productId);
            if (!prod) return;
            const existing = cart.find(i => i.id === productId);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ ...prod, qty: 1 });
            }
            updateCartBadge();
            openCartModal();
        }

        function openCartModal() {
            const modal = document.getElementById('cartModal');
            const body = document.getElementById('cartModalBody');
            if (cart.length === 0) {
                body.innerHTML = `<p class="text-center py-8 text-tram-700">Chưa có sản phẩm trong giỏ hàng.</p>`;
            } else {
                let total = 0;
                const itemsHtml = cart.map((item, idx) => {
                    total += item.price * item.qty;
                    return `
                        <div class="flex items-center justify-between gap-2 pb-2.5 border-b border-tram-100">
                            <div class="flex items-center gap-2.5">
                                <img src="https://lh3.googleusercontent.com/d/${item.driveId}=w200" data-drive-id="${item.driveId}" onerror="handleDriveImgError(this, 'SP')" class="w-12 h-12 rounded-lg object-cover border border-tram-200">
                                <div>
                                    <p class="font-semibold text-tram-900 leading-snug">${item.name}</p>
                                    <p class="text-[#b91c1c] font-bold">${formatVND(item.price)} x ${item.qty}</p>
                                </div>
                            </div>
                            <button onclick="removeCartItem(${idx})" class="text-red-600 hover:text-red-800 p-1">
                                <i class="fa-solid fa-trash-can"></i>
                            </button>
                        </div>
                    `;
                }).join('');

                body.innerHTML = `
                    <div class="space-y-2">${itemsHtml}</div>
                    <div class="pt-3 flex items-center justify-between font-bold text-sm text-tram-900">
                        <span>Tổng cộng:</span>
                        <span class="text-[#b91c1c]">${formatVND(total)}</span>
                    </div>
                    <div class="pt-3 space-y-2">
                        <a href="https://zalo.me/0905244307" target="_blank" rel="noopener noreferrer" class="block w-full py-2.5 rounded-lg bg-[#0068ff] text-white font-bold text-center">
                            Đặt Hàng Nhanh Qua Zalo (0905.244.307)
                        </a>
                        <a href="tel:0905244307" class="block w-full py-2.5 rounded-lg bg-tram-700 text-tram-300 font-bold text-center">
                            Gọi Điện Xác Nhận Giao Tận Nơi: 0905.244.307
                        </a>
                    </div>
                `;
            }
            modal.classList.remove('hidden');
        }

        function removeCartItem(index) {
            cart.splice(index, 1);
            updateCartBadge();
            openCartModal();
        }

        function closeCartModal() {
            document.getElementById('cartModal').classList.add('hidden');
        }

        /* Modal Xem Chi Tiết Sản Phẩm */
        function openProductModal(productId) {
            const p = PRODUCTS.find(item => item.id === productId);
            if (!p) return;
            const content = document.getElementById('productModalContent');
            content.innerHTML = `
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 items-start">
                    <div class="relative rounded-xl overflow-hidden border border-tram-300 aspect-square bg-tram-100">
                        <span class="absolute top-2 left-2 bg-[#b91c1c] text-white text-xs font-bold px-2.5 py-1 rounded-md">-${p.discount}%</span>
                        <img src="https://lh3.googleusercontent.com/d/${p.driveId}=w800" data-drive-id="${p.driveId}" onerror="handleDriveImgError(this, 'SP')" alt="${p.name}" class="w-full h-full object-cover">
                    </div>
                    <div class="space-y-2.5 text-xs">
                        <span class="text-tram-600 font-semibold uppercase">${p.categoryName}</span>
                        <h3 class="font-bold text-sm sm:text-base text-tram-900 leading-snug">${p.name}</h3>
                        <div class="flex items-baseline gap-2 py-1">
                            <del class="text-gray-400 text-xs">${formatVND(p.oldPrice)}</del>
                            <span class="text-base sm:text-lg font-bold text-[#b91c1c]">${formatVND(p.price)}</span>
                        </div>
                        <p class="text-tram-800 leading-relaxed">${p.desc}</p>
                        <ul class="bg-tram-50 p-3 rounded-lg border border-tram-200 space-y-1 text-tram-800">
                            <li>✓ Chất liệu: Trầm hương thiên nhiên 100%</li>
                            <li>✓ Kèm hộp nhung sang trọng, thẻ bảo hành & dây dự phòng</li>
                            <li>✓ Địa chỉ xem trực tiếp: 12 Bàu Trảng 2, P. Thanh Khê, Đà Nẵng</li>
                            <li>✓ Hotline / Zalo tư vấn: <strong>0905.244.307</strong></li>
                        </ul>
                        <div class="grid grid-cols-2 gap-2 pt-2">
                            <button onclick="addToCart(${p.id}); closeProductModal();" class="py-2.5 px-3 rounded-lg bg-tram-700 hover:bg-tram-900 text-tram-300 font-bold uppercase text-center">
                                Thêm Vào Giỏ
                            </button>
                            <a href="https://zalo.me/0905244307" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 rounded-lg bg-[#0068ff] hover:bg-blue-700 text-white font-bold uppercase text-center">
                                Tư Vấn Zalo
                            </a>
                        </div>
                    </div>
                </div>
            `;
            document.getElementById('productModal').classList.remove('hidden');
        }

        function closeProductModal() {
            document.getElementById('productModal').classList.add('hidden');
        }

        /* Xử lý Form Báo Giá Trang Chủ */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value;
            const phone = document.getElementById('qPhone').value;
            const cat = document.getElementById('qCategory').value;
            const msgBox = document.getElementById('quoteSuccessMsg');
            msgBox.innerHTML = `Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá mục <strong>${cat}</strong> đã được ghi nhận. Trầm Hương Duy Đức (0905.244.307) sẽ liên hệ tư vấn ngay cho bạn!`;
            msgBox.classList.remove('hidden');
            e.target.reset();
        }

        /* Dữ liệu Bài Viết Kiến Thức */
        const ARTICLES = [
            {
                title: 'Trầm Hương Chìm Nước Là Gì? Vì Sao Giá Trị Cao Hơn Các Loại Trầm Khác?',
                content: 'Trầm hương chìm nước là phần gỗ cây Dó Bầu tích tụ hàm lượng tinh dầu trầm hương cực kỳ lớn qua hàng chục năm trong tự nhiên. Khi tỷ trọng dầu lớn hơn nước, khối trầm hoặc hạt vòng trầm sẽ chìm hoàn toàn dưới đáy nước. Đây là dòng trầm quý hiếm bậc nhất, có hương thơm ngọt sâu bền bỉ và giá trị phong thủy, sưu tầm rất cao tại Trầm Hương Duy Đức.'
            },
            {
                title: 'Cách Phân Biệt Trầm Hương Thật Giả Chuẩn Xác Từ Chuyên Gia Duy Đức',
                content: 'Trầm hương thật tự nhiên có màu sắc mộc mạc, các đường vân dầu len lỏi tự nhiên không đều tăm tắp, cầm chắc tay và có mùi thơm dịu nhẹ, ngọt thanh, càng đeo ấm cơ thể càng tỏa hương. Ngược lại, trầm giả nấu hóa chất thường có màu đen bóng bất thường và mùi hắc nồng ngay từ đầu nhưng nhanh bay mùi.'
            },
            {
                title: 'Trầm Hương Xông Nhà Có Tác Dụng Gì? Cách Xông Trầm Đón Tài Lộc',
                content: 'Xông trầm hương miếng, giác xông hoặc nụ trầm hương vào dịp tân gia, khai trương, lễ Tết hay mỗi ngày giúp thanh lọc không khí, khử mùi ẩm mốc, xua tan uế khí và thu hút vượng khí, tài lộc cho gia chủ. Tại Trầm Hương Duy Đức (12 Bàu Trảng 2, Thanh Khê, Đà Nẵng), chúng tôi cung cấp đầy đủ trầm miếng và thác lư xông nguyên chất 100%.'
            },
            {
                title: 'Đeo Vòng Tay Trầm Hương 108 Hạt Có Tác Dụng Gì? 4 Công Dụng Nổi Bật',
                content: 'Chuỗi vòng trầm hương 108 hạt biểu trưng cho việc cầu chứng 108 pháp Tam Muội, đoạn trừ 108 phiền não trong cuộc sống. Đeo chuỗi 108 hạt trên cổ tay vừa là món trang sức phong thủy sang trọng, vừa giúp tâm trí thư thái, ngủ ngon và thu hút quý nhân phù trợ trong kinh doanh.'
            }
        ];

        function openArticleModal(idx) {
            const art = ARTICLES[idx];
            if (!art) return;
            document.getElementById('articleModalBody').innerHTML = `
                <h3 class="font-serif font-bold text-base sm:text-lg text-tram-800">${art.title}</h3>
                <p>${art.content}</p>
                <div class="p-3 rounded-lg bg-tram-50 border border-tram-200 text-xs text-tram-800">
                    <p><strong>Liên hệ tư vấn trực tiếp tại Trầm Hương Duy Đức:</strong></p>
                    <p>• Địa chỉ: 12 Bàu Trảng 2, Phường Thanh Khê, Tp.Đà Nẵng</p>
                    <p>• Hotline / Zalo: 0905.244.307 | Website: tramhuongduyduc.com</p>
                </div>
            `;
            document.getElementById('articleModal').classList.remove('hidden');
        }

        function closeArticleModal() {
            document.getElementById('articleModal').classList.add('hidden');
        }

        /* Khởi chạy khi tải trang */
        window.onload = function() {
            renderAllSections('all', '');
            resetBannerTimer();
        };
    </script>
</body>
</html>
