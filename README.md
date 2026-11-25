<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nhôm Kính Trần Hoàng Đà Nẵng | Cửa Nhôm Xingfa, Cửa Kính Cường Lực Uy Tín</title>
  <meta name="description" content="Nhôm Kính Trần Hoàng chuyên thiết kế, gia công và thi công cửa nhôm Xingfa, cửa kính cường lực, cửa nhựa lõi thép, cầu thang kính, kính ốp bếp, phòng tắm kính tại TP. Đà Nẵng. Hotline: 0905.044.794." />

  <!-- Meta Thumbnail / Open Graph sử dụng Logo trang web khi chia sẻ link -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="Nhôm Kính Trần Hoàng" />
  <meta property="og:title" content="Nhôm Kính Trần Hoàng Đà Nẵng - nhomkinhtranhoang.com" />
  <meta property="og:description" content="Chuyên thiết kế, thi công cửa nhôm Xingfa, cửa kính cường lực, cầu thang kính, phòng tắm kính, kính ốp bếp uy tín hàng đầu tại TP. Đà Nẵng. Hotline: 0905.044.794." />
  <meta property="og:url" content="https://nhomkinhtranhoang.com" />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1FyG6vYZm_5tIYGhIOC4NS9BkdBdB81Ly" />
  <meta property="og:image:alt" content="Logo Nhôm Kính Trần Hoàng" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Nhôm Kính Trần Hoàng Đà Nẵng - nhomkinhtranhoang.com" />
  <meta name="twitter:description" content="Thi công cửa nhôm Xingfa, cửa kính cường lực chuyên nghiệp tại Đà Nẵng - Hotline: 0905.044.794" />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1FyG6vYZm_5tIYGhIOC4NS9BkdBdB81Ly" />
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1FyG6vYZm_5tIYGhIOC4NS9BkdBdB81Ly" />

  <!-- Font chữ Inter chuẩn hiện đại & dễ đọc -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              DEFAULT: '#0B4A8B',
              dark: '#07315E',
              light: '#1565C0',
              soft: '#EFF6FF',
              accent: '#D97706',
              accentHover: '#B45309',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Biến màu đồng bộ theo nhận diện Nhôm Kính & dễ tùy chỉnh trong Flatsome */
    :root {
      --brand-primary: #0B4A8B;
      --brand-primary-dark: #07315E;
      --brand-accent: #D97706;
      --text-main: #1E293B;
    }

    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
    }

    body {
      font-family: 'Inter', sans-serif;
      color: var(--text-main);
      background-color: #F8FAFC;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
      margin: 0;
      padding: 0;
    }

    /* Chiều ngang giao diện máy tính bằng 95% màn hình, điện thoại căn giữa chuẩn không tràn viền */
    .container-95 {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .container-95 {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Flatsome Section Heading chuẩn */
    .section-title-bar {
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 14px;
      margin-bottom: 1.5rem;
    }

    .section-title-bar::before,
    .section-title-bar::after {
      content: "";
      flex: 1;
      height: 1.5px;
      background: linear-gradient(90deg, transparent, #CBD5E1, transparent);
    }

    /* Dropdown menu mượt kiểu Flatsome */
    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(6px);
      transition: all 0.2s ease;
    }

    .nav-item:hover .nav-dropdown,
    .nav-item:focus-within .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Banner 2 slide đồng kích thước tuyệt đối bằng CSS Grid chồng lớp */
    .hero-slider-grid {
      display: grid;
      grid-template-columns: 1fr;
      grid-template-rows: 1fr;
    }

    .hero-slide {
      grid-area: 1 / 1 / 2 / 2;
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
      transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
    }

    .hero-slide.active {
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
      z-index: 10;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi bật */
    @keyframes subtlePulse {
      0%, 100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.45); }
      50% { box-shadow: 0 0 0 10px rgba(220, 38, 38, 0); }
    }

    .pulse-hotline {
      animation: subtlePulse 2.2s infinite;
    }

    @keyframes subtlePulseZalo {
      0%, 100% { box-shadow: 0 0 0 0 rgba(0, 104, 255, 0.4); }
      50% { box-shadow: 0 0 0 10px rgba(0, 104, 255, 0); }
    }

    .pulse-zalo {
      animation: subtlePulseZalo 2.5s infinite;
    }
  </style>
</head>

<body class="antialiased selection:bg-brand selection:text-white">

  <!-- ===================================================================== -->
  <!-- 1. TOP BAR NHỎ GỌN (CHỈ THÔNG TIN CƠ BẢN, KHÔNG CÓ THANH UXBUILDER)   -->
  <!-- ===================================================================== -->
  <div class="bg-brand-dark text-white text-xs py-1.5 border-b border-white/10">
    <div class="container-95 flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1 text-slate-200">
        <span class="inline-flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a2 2 0 01-2.828 0l-4.243-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span>Tp. Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          <span>Tư vấn &amp; khảo sát 24/7</span>
        </span>
      </div>
      <div class="flex items-center gap-3 text-slate-200">
        <span class="text-[11px] sm:text-xs font-medium">nhomkinhtranhoang.com</span>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- 2. HEADER FLATSOME (LOGO GỌN NHỎ, KHÔNG CÓ NÚT GỌI NGAY TRÁNH TRÀN)   -->
  <!-- ===================================================================== -->
  <header class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-200">
    <!-- Hàng trên Header: Logo gọn nhỏ + Thanh tìm kiếm sản phẩm (không đặt nút Gọi ngay) -->
    <div class="bg-white py-2.5">
      <div class="container-95 flex items-center justify-between gap-3">
        <!-- Logo Nhôm Kính Trần Hoàng (chỉnh gọn nhỏ) -->
        <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
          <img
            src="https://lh3.googleusercontent.com/d/1FyG6vYZm_5tIYGhIOC4NS9BkdBdB81Ly"
            data-fallback="https://drive.google.com/thumbnail?id=1FyG6vYZm_5tIYGhIOC4NS9BkdBdB81Ly&sz=w400"
            data-placeholder="https://placehold.co/120x60/0B4A8B/FFFFFF?text=TRAN+HOANG"
            onerror="handleImgFallback(this)"
            alt="Logo Nhôm Kính Trần Hoàng"
            class="h-10 sm:h-11 w-auto max-w-[115px] object-contain rounded"
          />
          <div class="leading-tight">
            <div class="text-sm sm:text-base font-extrabold text-brand tracking-tight uppercase group-hover:text-brand-light transition">
              NHÔM KÍNH TRẦN HOÀNG
            </div>
            <div class="text-[11px] text-slate-500 font-medium hidden sm:block">
              Chuyên thi công Nhôm Xingfa &amp; Kính Cường Lực Đà Nẵng
            </div>
          </div>
        </a>

        <!-- Ô tìm kiếm sản phẩm gọn gàng trên máy tính -->
        <div class="hidden md:flex items-center flex-1 max-w-md ml-auto">
          <form onsubmit="handleSearchSubmit(event)" class="relative w-full">
            <input
              id="headerSearchInput"
              type="text"
              placeholder="Tìm cửa nhôm Xingfa, phòng tắm kính, kính ốp bếp..."
              class="w-full pl-4 pr-10 py-2 text-xs sm:text-sm bg-slate-50 border border-slate-300 rounded-lg focus:outline-none focus:border-brand focus:bg-white transition"
            />
            <button type="submit" aria-label="Tìm kiếm" class="absolute right-1.5 top-1/2 -translate-y-1/2 p-1.5 text-slate-500 hover:text-brand rounded-md">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-4.35-4.35M10.5 18a7.5 7.5 0 100-15 7.5 7.5 0 000 15z"/></svg>
            </button>
          </form>
        </div>

        <!-- Nút mở menu trên điện thoại -->
        <button
          id="mobileMenuToggle"
          type="button"
          aria-label="Mở danh mục"
          class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg border border-slate-200 text-brand hover:bg-brand-soft transition"
        >
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
      </div>
    </div>

    <!-- Thanh Menu chính trên Máy tính (viết liền 1 hàng, chữ nhỏ gọn, KHÔNG xuống dòng tên danh mục) -->
    <nav class="hidden lg:block bg-brand text-white" aria-label="Danh mục trang web">
      <div class="container-95">
        <ul class="flex flex-wrap xl:flex-nowrap items-center justify-center gap-x-1 xl:gap-x-2 py-1">
          <li class="shrink-0">
            <a href="#trang-chu" class="block px-2.5 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight whitespace-nowrap rounded hover:bg-white/15 transition">
              Trang chủ
            </a>
          </li>
          <li class="shrink-0">
            <a href="#gioi-thieu" class="block px-2.5 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight whitespace-nowrap rounded hover:bg-white/15 transition">
              Giới thiệu
            </a>
          </li>

          <!-- Dropdown: Cửa nhôm xingfa -->
          <li class="nav-item relative shrink-0">
            <a href="#san-pham-xingfa" class="inline-flex items-center gap-1 px-2.5 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight whitespace-nowrap rounded hover:bg-white/15 transition">
              <span>Cửa nhôm xingfa</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <ul class="nav-dropdown absolute left-0 top-full w-56 bg-white text-slate-800 rounded-b-lg shadow-xl border border-slate-200 py-1.5 z-50">
              <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('xep-truot')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </li>

          <li class="shrink-0">
            <a href="#danh-muc-san-pham" class="block px-2.5 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight whitespace-nowrap rounded hover:bg-white/15 transition">
              Cửa kính cường lực
            </a>
          </li>

          <!-- Dropdown: Sản phẩm -->
          <li class="nav-item relative shrink-0">
            <a href="#danh-muc-san-pham" class="inline-flex items-center gap-1 px-2.5 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight whitespace-nowrap rounded hover:bg-white/15 transition">
              <span>Sản phẩm</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <ul class="nav-dropdown absolute left-0 top-full w-52 bg-white text-slate-800 rounded-b-lg shadow-xl border border-slate-200 py-1.5 z-50">
              <li><a href="#san-pham-xingfa" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Cửa nhựa lõi thép</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Cửa kính tự động</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Cầu thang kính</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Kính ốp bếp</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính')" class="block px-4 py-2 text-[13px] font-medium whitespace-nowrap hover:bg-brand-soft hover:text-brand transition">Phòng tắm kính</a></li>
            </ul>
          </li>

          <li class="shrink-0">
            <a href="#cong-trinh" class="block px-2.5 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight whitespace-nowrap rounded hover:bg-white/15 transition">
              Công trình
            </a>
          </li>
          <li class="shrink-0">
            <a href="#bao-gia" class="block px-2.5 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight whitespace-nowrap rounded hover:bg-white/15 transition">
              Báo giá
            </a>
          </li>
          <li class="shrink-0">
            <a href="#tin-tuc" class="block px-2.5 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight whitespace-nowrap rounded hover:bg-white/15 transition">
              Tin tức
            </a>
          </li>
          <li class="shrink-0">
            <a href="#lien-he" class="block px-2.5 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight whitespace-nowrap rounded hover:bg-white/15 transition">
              Liên hệ
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- ===================================================================== -->
  <!-- MENU DRAWER TRÊN ĐIỆN THOẠI (FLATSOME OFF-CANVAS CHUẨN MƯỢT)          -->
  <!-- ===================================================================== -->
  <div id="mobileMenuOverlay" class="fixed inset-0 bg-slate-900/50 z-50 hidden lg:hidden" onclick="closeMobileMenu()"></div>
  <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[82%] max-w-[320px] bg-white z-50 transform -translate-x-full transition-transform duration-300 shadow-2xl overflow-y-auto lg:hidden">
    <div class="flex items-center justify-between p-4 border-b border-slate-200 bg-brand text-white">
      <span class="font-bold text-sm uppercase tracking-wide">Danh mục trang web</span>
      <button type="button" onclick="closeMobileMenu()" aria-label="Đóng menu" class="p-1.5 rounded-lg hover:bg-white/15">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
    </div>

    <!-- Tìm kiếm trên mobile -->
    <div class="p-3 border-b border-slate-100">
      <form onsubmit="handleMobileSearch(event)" class="relative">
        <input id="mobileSearchInput" type="text" placeholder="Tìm sản phẩm..." class="w-full pl-3 pr-9 py-2 text-sm bg-slate-50 border border-slate-200 rounded-lg focus:outline-none focus:border-brand" />
        <button type="submit" aria-label="Tìm" class="absolute right-2 top-1/2 -translate-y-1/2 text-slate-500 p-1">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-4.35-4.35M10.5 18a7.5 7.5 0 100-15 7.5 7.5 0 000 15z"/></svg>
        </button>
      </form>
    </div>

    <nav class="p-2 text-sm font-medium text-slate-700 divide-y divide-slate-100">
      <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-3 hover:text-brand hover:bg-brand-soft rounded-lg">Trang chủ</a>
      <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-3 hover:text-brand hover:bg-brand-soft rounded-lg">Giới thiệu</a>

      <!-- Accordion: Cửa nhôm xingfa -->
      <div>
        <button type="button" onclick="toggleMobileSub('subXingfa', this)" class="w-full flex items-center justify-between px-3 py-3 text-left hover:text-brand hover:bg-brand-soft rounded-lg">
          <span>Cửa nhôm xingfa</span>
          <svg class="w-4 h-4 transition-transform" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div id="subXingfa" class="hidden pl-5 pb-2 space-y-1 text-xs text-slate-600">
          <a href="#san-pham-xingfa" onclick="filterProducts('1-canh'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 1 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('2-canh'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 2 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('3-canh'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 3 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('4-canh'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 4 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('xep-truot'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 5 cánh</a>
        </div>
      </div>

      <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-3 hover:text-brand hover:bg-brand-soft rounded-lg">Cửa kính cường lực</a>

      <!-- Accordion: Sản phẩm -->
      <div>
        <button type="button" onclick="toggleMobileSub('subSanPham', this)" class="w-full flex items-center justify-between px-3 py-3 text-left hover:text-brand hover:bg-brand-soft rounded-lg">
          <span>Sản phẩm</span>
          <svg class="w-4 h-4 transition-transform" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div id="subSanPham" class="hidden pl-5 pb-2 space-y-1 text-xs text-slate-600">
          <a href="#san-pham-xingfa" onclick="closeMobileMenu()" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Cửa nhựa lõi thép</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Cửa kính tự động</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Cầu thang kính</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Kính ốp bếp</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính'); closeMobileMenu();" class="block py-2 hover:text-brand">+ Phòng tắm kính</a>
        </div>
      </div>

      <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-3 py-3 hover:text-brand hover:bg-brand-soft rounded-lg">Công trình</a>
      <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3 py-3 hover:text-brand hover:bg-brand-soft rounded-lg">Báo giá</a>
      <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3 py-3 hover:text-brand hover:bg-brand-soft rounded-lg">Tin tức</a>
      <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-3 hover:text-brand hover:bg-brand-soft rounded-lg">Liên hệ</a>
    </nav>
  </aside>

  <main id="trang-chu">

    <!-- =================================================================== -->
    <!-- 3. 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP - KÍCH THƯỚC BẰNG NHAU           -->
    <!-- Ảnh và chữ nằm hoàn toàn trong banner, cách xa viền, không mất chữ  -->
    <!-- =================================================================== -->
    <section class="py-3 sm:py-4 bg-slate-100">
      <div class="container-95">
        <div
          id="heroSlider"
          class="relative rounded-2xl overflow-hidden shadow-lg bg-brand-dark select-none"
        >
          <div class="hero-slider-grid">

            <!-- BANNER 1 -->
            <div class="hero-slide active relative flex items-center bg-gradient-to-br from-[#072B52] via-[#0B4A8B] to-[#0E3F73]">
              <!-- Ảnh nền công trình mờ nhẹ nằm hoàn toàn trong khung banner -->
              <img
                src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                data-fallback="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1400"
                data-placeholder="https://placehold.co/1400x520/072B52/FFFFFF?text=NHOM+KINH+TRAN+HOANG"
                onerror="handleImgFallback(this)"
                alt="Thi công cửa nhôm Xingfa cao cấp tại Đà Nẵng"
                class="absolute inset-0 w-full h-full object-cover opacity-20"
              />

              <!-- Vùng nội dung thụt sâu vào trong (cách xa viền ảnh banner ở cả Mobile & Desktop) -->
              <div class="relative z-10 w-full px-10 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-12 md:py-14 lg:py-16">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                  <div class="lg:col-span-7 text-white text-center lg:text-left">
                    <p class="text-xs sm:text-sm font-semibold uppercase tracking-widest text-amber-300 mb-2">
                      Nhôm Kính Trần Hoàng • TP. Đà Nẵng
                    </p>
                    <h1 class="text-xl sm:text-3xl md:text-4xl font-extrabold leading-snug mb-3">
                      CỬA NHÔM XINGFA NHẬP KHẨU CHÍNH HÃNG TẠI ĐÀ NẴNG
                    </h1>
                    <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-6 max-w-2xl mx-auto lg:mx-0">
                      Chuyên gia công &amp; lắp đặt cửa đi, cửa sổ nhôm Xingfa hệ 55, xếp trượt, phụ kiện đồng bộ chính hãng. Cách âm, cách nhiệt bền bỉ trước khí hậu miền Trung.
                    </p>
                    <div class="flex flex-wrap items-center justify-center lg:justify-start gap-3">
                      <a href="#bao-gia" class="px-5 py-2.5 bg-amber-500 hover:bg-amber-600 text-white text-xs sm:text-sm font-bold rounded-lg shadow transition">
                        Nhận báo giá ngay
                      </a>
                      <a href="#san-pham-xingfa" class="px-5 py-2.5 bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold rounded-lg transition">
                        Xem mẫu sản phẩm
                      </a>
                    </div>
                  </div>
                  <!-- Khung hình minh họa gọn gàng nằm bên trong banner -->
                  <div class="lg:col-span-5 flex justify-center">
                    <div class="w-full max-w-[340px] sm:max-w-[400px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-white/10">
                      <img
                        src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                        data-fallback="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w900"
                        data-placeholder="https://placehold.co/640x400/0B4A8B/FFFFFF?text=CUA+NHOM+XINGFA"
                        onerror="handleImgFallback(this)"
                        alt="Mẫu cửa nhôm Xingfa Trần Hoàng"
                        class="w-full h-full object-cover"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER 2 -->
            <div class="hero-slide relative flex items-center bg-gradient-to-br from-[#062647] via-[#0F4C81] to-[#135D96]">
              <!-- Ảnh nền công trình mờ nhẹ -->
              <img
                src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
                data-fallback="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w1400"
                data-placeholder="https://placehold.co/1400x520/062647/FFFFFF?text=THI+CONG+KINH+CUONG+LUC"
                onerror="handleImgFallback(this)"
                alt="Thi công kính cường lực, cầu thang kính, phòng tắm kính Đà Nẵng"
                class="absolute inset-0 w-full h-full object-cover opacity-20"
              />

              <!-- Vùng nội dung thụt sâu vào trong đồng đều với Banner 1 -->
              <div class="relative z-10 w-full px-10 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-12 md:py-14 lg:py-16">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                  <div class="lg:col-span-7 text-white text-center lg:text-left">
                    <p class="text-xs sm:text-sm font-semibold uppercase tracking-widest text-amber-300 mb-2">
                      Thiết Kế &amp; Thi Công Trọn Gói • Uy Tín
                    </p>
                    <h2 class="text-xl sm:text-3xl md:text-4xl font-extrabold leading-snug mb-3">
                      KÍNH CƯỜNG LỰC, PHÒNG TẮM KÍNH &amp; CẦU THANG KÍNH ĐẸP
                    </h2>
                    <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-6 max-w-2xl mx-auto lg:mx-0">
                      Kiến tạo không gian hiện đại cho nhà phố, biệt thự, khách sạn &amp; resort tại Đà Nẵng. Đo đạc tận nơi miễn phí, thi công chuẩn xác, bảo hành chu đáo.
                    </p>
                    <div class="flex flex-wrap items-center justify-center lg:justify-start gap-3">
                      <a href="#cong-trinh" class="px-5 py-2.5 bg-amber-500 hover:bg-amber-600 text-white text-xs sm:text-sm font-bold rounded-lg shadow transition">
                        Xem công trình thực tế
                      </a>
                      <a href="tel:0905044794" class="px-5 py-2.5 bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold rounded-lg transition">
                        Hotline: 0905.044.794
                      </a>
                    </div>
                  </div>
                  <!-- Khung hình minh họa đồng kích thước với Banner 1 -->
                  <div class="lg:col-span-5 flex justify-center">
                    <div class="w-full max-w-[340px] sm:max-w-[400px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-white/10">
                      <img
                        src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                        data-fallback="https://drive.google.com/thumbnail?id=1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH&sz=w900"
                        data-placeholder="https://placehold.co/640x400/0F4C81/FFFFFF?text=PHONG+TAM+KINH"
                        onerror="handleImgFallback(this)"
                        alt="Thi công phòng tắm kính & kính cường lực Đà Nẵng"
                        class="w-full h-full object-cover"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Nút điều hướng trái / phải đặt sát mép ngoài vùng chữ -->
          <button
            type="button"
            onclick="changeSlide(-1)"
            aria-label="Banner trước"
            class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition"
          >
            <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
          </button>
          <button
            type="button"
            onclick="changeSlide(1)"
            aria-label="Banner tiếp theo"
            class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition"
          >
            <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
          </button>

          <!-- Chấm chỉ báo 2 banner -->
          <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" onclick="goToSlide(0)" aria-label="Slide 1" class="slider-dot w-7 h-2 rounded-full bg-amber-400 transition-all"></button>
            <button type="button" onclick="goToSlide(1)" aria-label="Slide 2" class="slider-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- 4. DANH MỤC SẢN PHẨM NỔI BẬT (GIỐNG WEB MẪU - CHỮ NHỎ GỌN)          -->
    <!-- =================================================================== -->
    <section id="danh-muc-san-pham" class="py-8 sm:py-10 bg-white border-b border-slate-200/80">
      <div class="container-95">
        <div class="section-title-bar">
          <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase tracking-wide text-center px-2">
            DANH MỤC SẢN PHẨM
          </h2>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
          <!-- Danh mục 1: Cửa nhôm xingfa -->
          <a href="#san-pham-xingfa" onclick="filterProducts('all')" class="group block bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                data-fallback="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w600"
                data-placeholder="https://placehold.co/400x300/0B4A8B/FFFFFF?text=Cua+Nhom+Xingfa"
                onerror="handleImgFallback(this)"
                alt="Cửa nhôm xingfa"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              />
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 uppercase group-hover:text-brand transition leading-snug">
                Cửa nhôm xingfa
              </h3>
            </div>
          </a>

          <!-- Danh mục 2: Cửa nhựa lõi thép -->
          <a href="#bao-gia" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="group block bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
                data-fallback="https://drive.google.com/thumbnail?id=1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA&sz=w600"
                data-placeholder="https://placehold.co/400x300/0B4A8B/FFFFFF?text=Cua+Nhua+Loi+Thep"
                onerror="handleImgFallback(this)"
                alt="Cửa nhựa lõi thép"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              />
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 uppercase group-hover:text-brand transition leading-snug">
                Cửa nhựa lõi thép
              </h3>
            </div>
          </a>

          <!-- Danh mục 3: Cửa tự động -->
          <a href="#bao-gia" onclick="selectCategoryQuote('Cửa kính tự động')" class="group block bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
                data-fallback="https://drive.google.com/thumbnail?id=1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ&sz=w600"
                data-placeholder="https://placehold.co/400x300/0B4A8B/FFFFFF?text=Cua+Tu+Dong"
                onerror="handleImgFallback(this)"
                alt="Cửa tự động"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              />
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 uppercase group-hover:text-brand transition leading-snug">
                Cửa tự động
              </h3>
            </div>
          </a>

          <!-- Danh mục 4: Cầu thang kính -->
          <a href="#bao-gia" onclick="selectCategoryQuote('Cầu thang kính')" class="group block bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
                data-fallback="https://drive.google.com/thumbnail?id=1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul&sz=w600"
                data-placeholder="https://placehold.co/400x300/0B4A8B/FFFFFF?text=Cau+Thang+Kinh"
                onerror="handleImgFallback(this)"
                alt="Cầu thang kính"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              />
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 uppercase group-hover:text-brand transition leading-snug">
                Cầu thang kính
              </h3>
            </div>
          </a>

          <!-- Danh mục 5: Kính ốp bếp -->
          <a href="#bao-gia" onclick="selectCategoryQuote('Kính ốp bếp')" class="group block bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
                data-fallback="https://drive.google.com/thumbnail?id=1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb&sz=w600"
                data-placeholder="https://placehold.co/400x300/0B4A8B/FFFFFF?text=Kinh+Op+Bep"
                onerror="handleImgFallback(this)"
                alt="Kính ốp bếp"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              />
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 uppercase group-hover:text-brand transition leading-snug">
                Kính ốp bếp
              </h3>
            </div>
          </a>

          <!-- Danh mục 6: Phòng tắm kính -->
          <a href="#bao-gia" onclick="selectCategoryQuote('Phòng tắm kính')" class="group block bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                data-fallback="https://drive.google.com/thumbnail?id=1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH&sz=w600"
                data-placeholder="https://placehold.co/400x300/0B4A8B/FFFFFF?text=Phong+Tam+Kinh"
                onerror="handleImgFallback(this)"
                alt="Phòng tắm kính"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              />
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 uppercase group-hover:text-brand transition leading-snug">
                Phòng tắm kính
              </h3>
            </div>
          </a>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- 5. SẢN PHẨM CỬA NHÔM XINGFA - 2 CỘT TRÊN MOBILE, GIÁ & GIẢM GIÁ %   -->
    <!-- =================================================================== -->
    <section id="san-pham-xingfa" class="py-10 sm:py-12 bg-slate-50">
      <div class="container-95">
        <div class="section-title-bar">
          <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase tracking-wide text-center px-2">
            BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
          </h2>
        </div>

        <!-- Bộ lọc nhanh sản phẩm gọn gàng -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
          <button type="button" onclick="filterProducts('all')" data-filter="all" class="prod-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-brand text-white transition">Tất cả</button>
          <button type="button" onclick="filterProducts('1-canh')" data-filter="1-canh" class="prod-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-white text-slate-700 border border-slate-200 hover:border-brand transition">1 cánh</button>
          <button type="button" onclick="filterProducts('2-canh')" data-filter="2-canh" class="prod-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-white text-slate-700 border border-slate-200 hover:border-brand transition">2 cánh</button>
          <button type="button" onclick="filterProducts('3-canh')" data-filter="3-canh" class="prod-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-white text-slate-700 border border-slate-200 hover:border-brand transition">3 cánh</button>
          <button type="button" onclick="filterProducts('4-canh')" data-filter="4-canh" class="prod-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-white text-slate-700 border border-slate-200 hover:border-brand transition">4 cánh</button>
          <button type="button" onclick="filterProducts('xep-truot')" data-filter="xep-truot" class="prod-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-white text-slate-700 border border-slate-200 hover:border-brand transition">Xếp trượt / Mở hất</button>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên máy tính -->
        <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
          <!-- Sản phẩm sẽ được render tự động từ dữ liệu bên dưới -->
        </div>

        <p id="productEmptyMsg" class="hidden text-center text-sm text-slate-500 py-8">
          Không tìm thấy sản phẩm phù hợp với từ khóa của bạn.
        </p>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- 6. GIỚI THIỆU NHÔM KÍNH TRẦN HOÀNG & THÔNG SỐ UY TÍN                -->
    <!-- =================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-12 bg-white border-y border-slate-200">
      <div class="container-95">
        <div class="section-title-bar">
          <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase tracking-wide text-center px-2">
            NHÔM KÍNH TRẦN HOÀNG – ĐÀ NẴNG
          </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-start">
          <!-- Cột giới thiệu -->
          <div class="lg:col-span-7 space-y-3.5 text-sm sm:text-[15px] text-slate-600 leading-relaxed">
            <p>
              <strong class="text-brand">Nhôm Kính Trần Hoàng</strong> là đơn vị chuyên thiết kế, gia công và thi công lắp đặt trọn gói các hạng mục nhôm kính cao cấp tại <strong>TP. Đà Nẵng</strong> và khu vực miền Trung.
            </p>
            <p>
              Các dòng sản phẩm chủ lực của chúng tôi bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu</strong>, <strong>Cửa kính cường lực</strong>, <strong>Cửa nhựa lõi thép</strong>, <strong>Cửa kính tự động</strong>, <strong>Cầu thang kính</strong>, <strong>Kính ốp bếp</strong> và <strong>Phòng tắm kính</strong> hiện đại.
            </p>
            <p>
              Với đội ngũ thợ kỹ thuật giàu kinh nghiệm, máy móc gia công hiện đại cùng quy trình khảo sát – báo giá minh bạch, Nhôm Kính Trần Hoàng cam kết mang đến những bộ cửa bền đẹp, kín khít, thẩm mỹ và an toàn tuyệt đối cho mọi ngôi nhà phố, biệt thự, khách sạn và công trình dự án.
            </p>
          </div>

          <!-- Cột bảng cam kết dịch vụ gọn đẹp kiểu web mẫu -->
          <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 overflow-hidden">
            <div class="bg-brand text-white px-4 py-3 text-sm font-bold uppercase tracking-wide">
              Cam kết dịch vụ tại Trần Hoàng
            </div>
            <div class="divide-y divide-slate-200 text-xs sm:text-sm">
              <div class="flex items-center justify-between px-4 py-3 gap-2">
                <span class="font-semibold text-slate-700">Hotline tư vấn</span>
                <a href="tel:0905044794" class="font-bold text-red-600 hover:underline">0905.044.794</a>
              </div>
              <div class="flex items-center justify-between px-4 py-3 gap-2">
                <span class="font-semibold text-slate-700">Khảo sát &amp; lắp đặt</span>
                <span class="text-slate-600 text-right">Đo đạc tư vấn tận nơi miễn phí</span>
              </div>
              <div class="flex items-center justify-between px-4 py-3 gap-2">
                <span class="font-semibold text-slate-700">Chất lượng vật tư</span>
                <span class="text-slate-600 text-right">Nhôm Xingfa &amp; phụ kiện chính hãng</span>
              </div>
              <div class="flex items-center justify-between px-4 py-3 gap-2">
                <span class="font-semibold text-slate-700">Chế độ bảo hành</span>
                <span class="text-slate-600 text-right">Bảo hành kỹ thuật &amp; phụ kiện dài hạn</span>
              </div>
            </div>
          </div>
        </div>

        <!-- 4 Con số nổi bật Flatsome -->
        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5 mt-8">
          <div class="bg-brand-soft border border-blue-100 rounded-xl p-4 sm:p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand">150+</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Dự án đã hoàn thành</div>
          </div>
          <div class="bg-brand-soft border border-blue-100 rounded-xl p-4 sm:p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand">50+</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Kỹ thuật viên kinh nghiệm</div>
          </div>
          <div class="bg-brand-soft border border-blue-100 rounded-xl p-4 sm:p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand">100+</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Mẫu sản phẩm đa dạng</div>
          </div>
          <div class="bg-brand-soft border border-blue-100 rounded-xl p-4 sm:p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand">100%</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Khách hàng hài lòng</div>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- 7. CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG                                    -->
    <!-- =================================================================== -->
    <section id="cong-trinh" class="py-10 sm:py-12 bg-slate-50">
      <div class="container-95">
        <div class="section-title-bar">
          <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase tracking-wide text-center px-2">
            CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
          </h2>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
          <!-- Dự án 1 -->
          <article class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                data-fallback="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w800"
                data-placeholder="https://placehold.co/640x400/0B4A8B/FFFFFF?text=MY+SON+HERITAGE+RESORT"
                onerror="handleImgFallback(this)"
                alt="DỰ ÁN RESORT MỸ SƠN 4 SAO MY SON HERITAGE RESORT & SPA"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand transition leading-snug">
                DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT &amp; SPA”
              </h3>
              <p class="text-xs text-slate-500 mt-2">Thi công trọn gói hệ cửa nhôm kính &amp; vách kính cao cấp.</p>
            </div>
          </article>

          <!-- Dự án 2 -->
          <article class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy"
                data-fallback="https://drive.google.com/thumbnail?id=1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy&sz=w800"
                data-placeholder="https://placehold.co/640x400/0B4A8B/FFFFFF?text=KHACH+SAN+GODEN+LINE"
                onerror="handleImgFallback(this)"
                alt="THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand transition leading-snug">
                THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE
              </h3>
              <p class="text-xs text-slate-500 mt-2">Hạng mục cửa nhôm Xingfa cách âm &amp; phòng tắm kính cường lực.</p>
            </div>
          </article>

          <!-- Dự án 3 -->
          <article class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
                data-fallback="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w800"
                data-placeholder="https://placehold.co/640x400/0B4A8B/FFFFFF?text=KHACH+SAN+RUBY+LIGHT"
                onerror="handleImgFallback(this)"
                alt="DỰ ÁN KHÁCH SẠN RUBY LIGHT"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand transition leading-snug">
                DỰ ÁN KHÁCH SẠN RUBY LIGHT
              </h3>
              <p class="text-xs text-slate-500 mt-2">Lắp đặt mặt dựng kính, cửa đi và cửa sổ nhôm Xingfa tại Đà Nẵng.</p>
            </div>
          </article>

          <!-- Dự án 4 -->
          <article class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1za_IJpAm850uulT6IuhBsk1THb3LuPuc"
                data-fallback="https://drive.google.com/thumbnail?id=1za_IJpAm850uulT6IuhBsk1THb3LuPuc&sz=w800"
                data-placeholder="https://placehold.co/640x400/0B4A8B/FFFFFF?text=RAON+DA+NANG+BEACH+HOTEL"
                onerror="handleImgFallback(this)"
                alt="THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand transition leading-snug">
                THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL
              </h3>
              <p class="text-xs text-slate-500 mt-2">Hệ cửa nhôm kính chống chịu gió biển &amp; vách kính ban công.</p>
            </div>
          </article>

          <!-- Dự án 5 -->
          <article class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64"
                data-fallback="https://drive.google.com/thumbnail?id=1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64&sz=w800"
                data-placeholder="https://placehold.co/640x400/0B4A8B/FFFFFF?text=KHACH+SAN+JOLIA"
                onerror="handleImgFallback(this)"
                alt="THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand transition leading-snug">
                THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA
              </h3>
              <p class="text-xs text-slate-500 mt-2">Thi công cửa kính tự động sảnh chính &amp; hệ cửa phòng nghỉ.</p>
            </div>
          </article>

          <!-- Dự án 6 -->
          <article class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt"
                data-fallback="https://drive.google.com/thumbnail?id=1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt&sz=w800"
                data-placeholder="https://placehold.co/640x400/0B4A8B/FFFFFF?text=KHACH+SAN+SOHO"
                onerror="handleImgFallback(this)"
                alt="THI CÔNG DỰ ÁN KHÁCH SẠN SOHO"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand transition leading-snug">
                THI CÔNG DỰ ÁN KHÁCH SẠN SOHO
              </h3>
              <p class="text-xs text-slate-500 mt-2">Hoàn thiện hạng mục cửa nhôm kính, lan can &amp; vách tắm kính.</p>
            </div>
          </article>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- 8. FORM YÊU CẦU & ĐĂNG KÝ NHẬN BÁO GIÁ NGAY TRÊN TRANG CHỦ          -->
    <!-- =================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-12 bg-brand text-white">
      <div class="container-95">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
          <!-- Nội dung kêu gọi bên trái -->
          <div class="lg:col-span-5 space-y-4">
            <h2 class="text-xl sm:text-2xl font-extrabold uppercase tracking-wide leading-snug">
              ĐĂNG KÝ NHẬN TƯ VẤN &amp; BÁO GIÁ CHI TIẾT
            </h2>
            <p class="text-sm text-blue-100 leading-relaxed">
              Quý khách cần báo giá thi công cửa nhôm Xingfa, cửa kính cường lực, cầu thang kính, phòng tắm kính hoặc kính ốp bếp tại Đà Nẵng? Vui lòng để lại thông tin, kỹ thuật viên Nhôm Kính Trần Hoàng sẽ liên hệ khảo sát và gửi bảng giá tốt nhất trong vòng 15 phút.
            </p>
            <div class="space-y-2.5 pt-2 text-sm text-blue-50">
              <div class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                <span>Hotline / Zalo: <strong class="text-white">0905.044.794</strong></span>
              </div>
              <div class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a2 2 0 01-2.828 0l-4.243-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                <span>Địa chỉ: <strong class="text-white">Tp. Đà Nẵng</strong></span>
              </div>
              <div class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9"/></svg>
                <span>Website: <strong class="text-white">nhomkinhtranhoang.com</strong></span>
              </div>
            </div>
          </div>

          <!-- Form yêu cầu báo giá bên phải -->
          <div class="lg:col-span-7 bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl">
            <form id="quoteForm" onsubmit="handleQuoteSubmit(event)" class="space-y-4">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                  <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand transition" />
                </div>
                <div>
                  <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                  <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905.xxx.xxx" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand transition" />
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="qCategory" class="block text-xs font-semibold text-slate-700 mb-1.5">Hạng mục cần báo giá</label>
                  <select id="qCategory" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-brand transition">
                    <option value="Cửa nhôm xingfa">Cửa nhôm xingfa</option>
                    <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                    <option value="Cầu thang kính">Cầu thang kính</option>
                    <option value="Kính ốp bếp">Kính ốp bếp</option>
                    <option value="Phòng tắm kính">Phòng tắm kính</option>
                    <option value="Hạng mục khác">Hạng mục khác</option>
                  </select>
                </div>
                <div>
                  <label for="qAddress" class="block text-xs font-semibold text-slate-700 mb-1.5">Khu vực công trình</label>
                  <input id="qAddress" type="text" placeholder="Quận/Huyện tại TP. Đà Nẵng" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand transition" />
                </div>
              </div>

              <div>
                <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Nội dung yêu cầu (kích thước dự kiến, số lượng bộ cửa...)</label>
                <textarea id="qNote" rows="3" placeholder="Mô tả sơ bộ hạng mục cần thi công để chúng tôi báo giá chính xác nhất..." class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand transition"></textarea>
              </div>

              <button type="submit" class="w-full sm:w-auto px-7 py-3 bg-amber-500 hover:bg-amber-600 text-white text-sm font-bold uppercase tracking-wide rounded-lg shadow transition">
                Gửi yêu cầu báo giá
              </button>

              <!-- Hộp thông báo sau khi gửi form (không dùng alert) -->
              <div id="quoteFeedback" class="hidden p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- 9. DANH MỤC CÁC BÀI VIẾT & TIN TỨC TRANG CHỦ                        -->
    <!-- =================================================================== -->
    <section id="tin-tuc" class="py-10 sm:py-12 bg-white">
      <div class="container-95">
        <div class="section-title-bar">
          <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase tracking-wide text-center px-2">
            TIN TỨC &amp; BÀI VIẾT NỔI BẬT
          </h2>
        </div>

        <!-- Danh mục lọc bài viết -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
          <button type="button" onclick="filterPosts('all')" data-postcat="all" class="post-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-brand text-white transition">Tất cả bài viết</button>
          <button type="button" onclick="filterPosts('xingfa')" data-postcat="xingfa" class="post-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition">Cửa nhôm Xingfa</button>
          <button type="button" onclick="filterPosts('kinh-nghiem')" data-postcat="kinh-nghiem" class="post-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition">Kinh nghiệm chọn cửa</button>
          <button type="button" onclick="filterPosts('tu-van')" data-postcat="tu-van" class="post-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition">Tư vấn &amp; Báo giá</button>
        </div>

        <!-- Lưới bài viết -->
        <div id="postGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
          <!-- Render tự động bằng JS -->
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- 10. ĐỐI TÁC CỦA CHÚNG TÔI                                           -->
    <!-- =================================================================== -->
    <section class="py-8 sm:py-10 bg-slate-50 border-t border-slate-200">
      <div class="container-95">
        <div class="section-title-bar">
          <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase tracking-wide text-center px-2">
            ĐỐI TÁC CỦA CHÚNG TÔI
          </h2>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
            <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" data-fallback="https://drive.google.com/thumbnail?id=13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk&sz=w400" data-placeholder="https://placehold.co/200x90/FFFFFF/0B4A8B?text=DOI+TAC+1" onerror="handleImgFallback(this)" alt="Đối tác Nhôm Kính Trần Hoàng 1" class="max-h-14 sm:max-h-16 w-auto object-contain" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
            <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" data-fallback="https://drive.google.com/thumbnail?id=1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq&sz=w400" data-placeholder="https://placehold.co/200x90/FFFFFF/0B4A8B?text=DOI+TAC+2" onerror="handleImgFallback(this)" alt="Đối tác Nhôm Kính Trần Hoàng 2" class="max-h-14 sm:max-h-16 w-auto object-contain" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
            <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" data-fallback="https://drive.google.com/thumbnail?id=1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn&sz=w400" data-placeholder="https://placehold.co/200x90/FFFFFF/0B4A8B?text=DOI+TAC+3" onerror="handleImgFallback(this)" alt="Đối tác Nhôm Kính Trần Hoàng 3" class="max-h-14 sm:max-h-16 w-auto object-contain" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
            <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" data-fallback="https://drive.google.com/thumbnail?id=1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT&sz=w400" data-placeholder="https://placehold.co/200x90/FFFFFF/0B4A8B?text=DOI+TAC+4" onerror="handleImgFallback(this)" alt="Đối tác Nhôm Kính Trần Hoàng 4" class="max-h-14 sm:max-h-16 w-auto object-contain" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
            <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-" data-fallback="https://drive.google.com/thumbnail?id=1SDcarhnX0yypmqdbawICjYBRtFnKngn-&sz=w400" data-placeholder="https://placehold.co/200x90/FFFFFF/0B4A8B?text=DOI+TAC+5" onerror="handleImgFallback(this)" alt="Đối tác Nhôm Kính Trần Hoàng 5" class="max-h-14 sm:max-h-16 w-auto object-contain" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
            <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" data-fallback="https://drive.google.com/thumbnail?id=1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg&sz=w400" data-placeholder="https://placehold.co/200x90/FFFFFF/0B4A8B?text=DOI+TAC+6" onerror="handleImgFallback(this)" alt="Đối tác Nhôm Kính Trần Hoàng 6" class="max-h-14 sm:max-h-16 w-auto object-contain" />
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- 11. BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGAY TRÊN TRANG CHỦ        -->
    <!-- =================================================================== -->
    <section id="lien-he" class="py-10 sm:py-12 bg-white border-t border-slate-200">
      <div class="container-95">
        <div class="section-title-bar">
          <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase tracking-wide text-center px-2">
            BẢN ĐỒ ĐƯỜNG ĐI &amp; FANPAGE FACEBOOK
          </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
          <!-- Google Map TP. Đà Nẵng -->
          <div class="lg:col-span-7 bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
            <div class="px-4 py-3 bg-slate-100 border-b border-slate-200 flex items-center justify-between gap-2">
              <span class="text-xs sm:text-sm font-bold text-brand uppercase">Bản đồ Google Map – TP. Đà Nẵng</span>
              <a
                href="https://www.google.com/maps/search/?api=1&query=Da+Nang+Vietnam"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold text-brand hover:underline shrink-0"
              >
                Mở bản đồ lớn
              </a>
            </div>
            <div class="w-full h-[300px] sm:h-[340px] flex-1">
              <iframe
                title="Bản đồ Nhôm Kính Trần Hoàng TP. Đà Nẵng"
                src="https://www.google.com/maps?q=Da+Nang,+Vietnam&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <!-- Fanpage Facebook Nhôm Kính Trần Hoàng -->
          <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
            <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between gap-2">
              <span class="text-xs sm:text-sm font-bold uppercase inline-flex items-center gap-2">
                <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M22 12a10 10 0 10-11.56 9.88v-6.99H7.9V12h2.54V9.8c0-2.51 1.49-3.89 3.78-3.89 1.09 0 2.24.2 2.24.2v2.46h-1.26c-1.24 0-1.63.77-1.63 1.56V12h2.78l-.44 2.89h-2.34v6.99A10 10 0 0022 12z"/></svg>
                Fanpage Nhôm Kính Trần Hoàng
              </span>
              <a
                href="https://www.facebook.com/profile.php?id=100083219918196"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold bg-white/20 hover:bg-white/30 px-2.5 py-1 rounded transition"
              >
                Truy cập trang
              </a>
            </div>

            <div class="p-4 flex-1 flex flex-col justify-between gap-4">
              <!-- Thẻ giới thiệu Fanpage trực quan (hiển thị đẹp ngay cả khi trình duyệt chặn iframe bên thứ 3) -->
              <div class="bg-white rounded-xl border border-slate-200 p-4 flex items-center gap-3.5 shadow-sm">
                <img
                  src="https://lh3.googleusercontent.com/d/1FyG6vYZm_5tIYGhIOC4NS9BkdBdB81Ly"
                  data-fallback="https://drive.google.com/thumbnail?id=1FyG6vYZm_5tIYGhIOC4NS9BkdBdB81Ly&sz=w300"
                  data-placeholder="https://placehold.co/80x80/0B4A8B/FFFFFF?text=TH"
                  onerror="handleImgFallback(this)"
                  alt="Fanpage Nhôm Kính Trần Hoàng"
                  class="w-14 h-14 rounded-xl object-contain border border-slate-200 p-1 bg-white shrink-0"
                />
                <div class="min-w-0">
                  <h3 class="text-sm font-bold text-slate-900 leading-snug">Nhôm Kính Trần Hoàng</h3>
                  <p class="text-xs text-slate-500 mt-0.5">Thiết kế &amp; thi công công trình nhôm kính tại TP. Đà Nẵng</p>
                  <a
                    href="https://www.facebook.com/profile.php?id=100083219918196"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center gap-1.5 mt-2 px-3 py-1.5 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold rounded-lg transition"
                  >
                    Theo dõi Fanpage
                  </a>
                </div>
              </div>

              <!-- Facebook Page Plugin chính thức -->
              <div class="w-full overflow-hidden rounded-xl border border-slate-200 bg-white min-h-[180px]">
                <iframe
                  title="Fanpage Facebook Nhôm Kính Trần Hoàng"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100083219918196&tabs=&width=500&height=180&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  class="w-full h-[180px] border-0 overflow-hidden"
                  scrolling="no"
                  frameborder="0"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                  loading="lazy"
                ></iframe>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- ===================================================================== -->
  <!-- 12. FOOTER FLATSOME CHUYÊN NGHIỆP                                     -->
  <!-- ===================================================================== -->
  <footer class="bg-brand-dark text-slate-200 pt-10 pb-20 lg:pb-8">
    <div class="container-95">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/15">
        <!-- Cột 1: Thông tin liên hệ -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5 bg-white/95 p-2 rounded-lg w-fit">
            <img
              src="https://lh3.googleusercontent.com/d/1FyG6vYZm_5tIYGhIOC4NS9BkdBdB81Ly"
              data-fallback="https://drive.google.com/thumbnail?id=1FyG6vYZm_5tIYGhIOC4NS9BkdBdB81Ly&sz=w300"
              data-placeholder="https://placehold.co/100x45/0B4A8B/FFFFFF?text=TRAN+HOANG"
              onerror="handleImgFallback(this)"
              alt="Logo Nhôm Kính Trần Hoàng"
              class="h-9 w-auto object-contain"
            />
          </div>
          <h3 class="text-sm font-bold text-white uppercase tracking-wide pt-1">NHÔM KÍNH TRẦN HOÀNG</h3>
          <ul class="space-y-1.5 text-xs sm:text-sm text-slate-300">
            <li>Địa chỉ: Tp. Đà Nẵng</li>
            <li>Hotline / Zalo: <a href="tel:0905044794" class="text-amber-400 font-bold hover:underline">0905.044.794</a></li>
            <li>Website: <a href="#trang-chu" class="hover:text-white">nhomkinhtranhoang.com</a></li>
            <li>Fanpage: <a href="https://www.facebook.com/profile.php?id=100083219918196" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">Nhôm Kính Trần Hoàng</a></li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h3 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-1.5 border-b border-white/15">Cửa Nhôm Xingfa</h3>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('xep-truot')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h3 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-1.5 border-b border-white/15">Danh Mục Sản Phẩm</h3>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa nhôm xingfa</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cầu thang kính</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Kính ốp bếp &amp; Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h3 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-1.5 border-b border-white/15">Liên Kết Nhanh</h3>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#gioi-thieu" class="hover:text-amber-300 transition">Giới thiệu công ty</a></li>
            <li><a href="#cong-trinh" class="hover:text-amber-300 transition">Công trình đã thi công</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">Đăng ký nhận báo giá</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-300 transition">Tin tức &amp; Tư vấn</a></li>
            <li><a href="#lien-he" class="hover:text-amber-300 transition">Bản đồ &amp; Liên hệ</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <p>© 2026 Bản quyền thuộc về <strong class="text-white">Nhôm Kính Trần Hoàng</strong> – nhomkinhtranhoang.com</p>
        <p>Thiết kế chuẩn giao diện Flatsome • TP. Đà Nẵng</p>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- 13. CÁC NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE (MOBILE & PC)     -->
  <!-- ===================================================================== -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-40 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/profile.php?id=100083219918196"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Nhắn tin Facebook Nhôm Kính Trần Hoàng"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
    >
      <svg class="w-5 h-5 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22 12a10 10 0 10-11.56 9.88v-6.99H7.9V12h2.54V9.8c0-2.51 1.49-3.89 3.78-3.89 1.09 0 2.24.2 2.24.2v2.46h-1.26c-1.24 0-1.63.77-1.63 1.56V12h2.78l-.44 2.89h-2.34v6.99A10 10 0 0022 12z"/></svg>
      <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0905044794"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Chat Zalo 0905.044.794"
      class="pulse-zalo group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
    >
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Hotline -->
    <a
      href="tel:0905044794"
      aria-label="Gọi Hotline 0905.044.794"
      class="pulse-hotline group flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition"
    >
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      <span class="text-xs font-extrabold pr-1">0905.044.794</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- 14. MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT                            -->
  <!-- ===================================================================== -->
  <div id="detailModal" class="fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-3 sm:p-5" onclick="closeModalOnBackdrop(event)">
    <div class="bg-white rounded-2xl max-w-xl w-full max-h-[88vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-200 sticky top-0 bg-white">
        <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-brand pr-4"></h3>
        <button type="button" onclick="closeDetailModal()" aria-label="Đóng" class="p-1.5 rounded-lg text-slate-500 hover:bg-slate-100 hover:text-slate-800">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div id="modalBody" class="p-5 space-y-4 text-sm text-slate-600 leading-relaxed"></div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT XỬ LÝ SLIDER, SẢN PHẨM, BÀI VIẾT, FORM & FALLBACK ẢNH      -->
  <!-- ===================================================================== -->
  <script>
    /* 1. Xử lý dự phòng tải ảnh Google Drive nếu một đường dẫn gặp giới hạn */
    function handleImgFallback(img) {
      try {
        if (!img.dataset.triedFallback && img.dataset.fallback) {
          img.dataset.triedFallback = 'true';
          img.src = img.dataset.fallback;
        } else if (img.dataset.placeholder && img.src !== img.dataset.placeholder) {
          img.src = img.dataset.placeholder;
        }
      } catch (err) {
        console.error('Lỗi tải ảnh dự phòng:', err);
      }
    }

    /* 2. Dữ liệu 6 sản phẩm Cửa nhôm Xingfa chuẩn kèm giá & % giảm giá góc trên bên trái */
    const PRODUCTS = [
      {
        id: 1,
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        category: '1-canh',
        fileId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: '2.450.000 ₫',
        price: '2.100.000 ₫',
        discount: '-14%',
        specs: 'Thanh nhôm Xingfa hệ 55 dày 2.0mm, kính cường lực 8mm – 10mm, phụ kiện Kinlong đồng bộ chính hãng, gioăng kép EPDM kín khít tuyệt đối.'
      },
      {
        id: 2,
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        category: '2-canh',
        fileId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: '2.500.000 ₫',
        price: '2.100.000 ₫',
        discount: '-16%',
        specs: 'Thiết kế 2 cánh mở quay sang trọng cho cửa chính hoặc cửa ban công. Nhôm Xingfa nhập khẩu tem đỏ, chống cong vênh, cách âm và chống nước mưa vượt trội.'
      },
      {
        id: 3,
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        category: '3-canh',
        fileId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: '2.550.000 ₫',
        price: '2.150.000 ₫',
        discount: '-16%',
        specs: 'Giải pháp tối ưu cho mặt tiền rộng vừa, kết cấu vững chắc với nhôm Xingfa hệ 55, sơn tĩnh điện ngoài trời bền màu, khóa đa điểm an toàn.'
      },
      {
        id: 4,
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        category: '4-canh',
        fileId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: '2.600.000 ₫',
        price: '2.100.000 ₫',
        discount: '-19%',
        specs: 'Mẫu cửa mặt tiền đẳng cấp cho nhà phố và biệt thự. Mở rộng tối đa không gian đón sáng, chịu lực gió mạnh, thẩm mỹ hiện đại.'
      },
      {
        id: 5,
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: 'xep-truot',
        fileId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: '2.650.000 ₫',
        price: '2.200.000 ₫',
        discount: '-17%',
        specs: 'Cửa đi xếp trượt nhôm Xingfa hệ 63 (từ 3 đến 5 cánh hoặc nhiều hơn), vận hành êm ái trên ray trượt chịu lực, mở thông thoáng gần như 100% diện tích.'
      },
      {
        id: 6,
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: 'xep-truot',
        fileId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: '2.350.000 ₫',
        price: '1.950.000 ₫',
        discount: '-17%',
        specs: 'Cửa sổ mở hất góc 45 độ giúp thông gió ngay cả khi trời mưa, thanh định vị chống va đập gió, phù hợp nhà phố, chung cư và khách sạn tại Đà Nẵng.'
      }
    ];

    /* 3. Dữ liệu danh mục bài viết trang chủ */
    const POSTS = [
      {
        id: 1,
        cat: 'xingfa',
        catLabel: 'Cửa nhôm Xingfa',
        date: '2026',
        fileId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển tại Đà Nẵng không?',
        excerpt: 'Khám phá khả năng chống ăn mòn, chịu bão gió và cách nhiệt vượt trội của hệ cửa nhôm Xingfa sơn tĩnh điện cao cấp.',
        content: 'Đà Nẵng có khí hậu ven biển với độ ẩm cao và mùa mưa bão khắc nghiệt. Cửa nhôm Xingfa nhập khẩu với lớp sơn tĩnh điện cao cấp kết hợp hệ gioăng kép EPDM và keo silicone trung tính giúp chống oxy hóa, ngăn nước tuyệt đối và chịu được áp lực gió mạnh, là lựa chọn bền bỉ hàng đầu cho công trình tại Đà Nẵng.'
      },
      {
        id: 2,
        cat: 'tu-van',
        catLabel: 'Tư vấn & Báo giá',
        date: '2026',
        fileId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        title: 'Báo giá thi công cửa nhôm Xingfa nhập khẩu tại Đà Nẵng mới nhất',
        excerpt: 'Cập nhật chi tiết đơn giá m2 cửa đi mở quay 1-4 cánh, cửa xếp trượt và các yếu tố ảnh hưởng đến chi phí lắp đặt.',
        content: 'Đơn giá cửa nhôm Xingfa phụ thuộc vào hệ nhôm (hệ 55, hệ 93, hệ 63), độ dày kính cường lực (8mm, 10mm, kính hộp cách âm) và bộ phụ kiện đi kèm. Tại Nhôm Kính Trần Hoàng, chúng tôi báo giá trực tiếp tại xưởng không qua trung gian, miễn phí khảo sát đo đạc tận công trình tại TP. Đà Nẵng.'
      },
      {
        id: 3,
        cat: 'kinh-nghiem',
        catLabel: 'Kinh nghiệm chọn cửa',
        date: '2026',
        fileId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        title: 'So sánh cửa nhôm Xingfa và cửa nhựa lõi thép: Nên chọn loại nào?',
        excerpt: 'Phân tích ưu nhược điểm về độ bền, thẩm mỹ, khả năng cách âm và chi phí đầu tư giữa hai dòng cửa phổ biến.',
        content: 'Cửa nhôm Xingfa nổi bật với khung mảnh sang trọng, chịu lực cao, đa dạng màu sắc (xám ghi, đen, trắng, vân gỗ) phù hợp cửa mặt tiền và cửa lớn. Trong khi đó, cửa nhựa lõi thép uPVC có ưu thế cách âm tốt và giá thành kinh tế cho cửa phòng ngủ, cửa vệ sinh. Tùy ngân sách và vị trí lắp đặt, Trần Hoàng sẽ tư vấn phương án tối ưu nhất.'
      },
      {
        id: 4,
        cat: 'kinh-nghiem',
        catLabel: 'Kinh nghiệm chọn cửa',
        date: '2026',
        fileId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        title: 'Kinh nghiệm chọn phòng tắm kính & kính ốp bếp cường lực bền đẹp',
        excerpt: 'Hướng dẫn chọn độ dày kính an toàn, bản lề inox 304 chống gỉ và màu kính ốp bếp hài hòa phong thủy.',
        content: 'Với phòng tắm kính cường lực, nên sử dụng kính 10mm tôi nhiệt đạt chuẩn cùng phụ kiện inox 304 chống gỉ sét trong môi trường ẩm ướt. Đối với kính ốp bếp, kính cường lực 8mm sơn màu chịu nhiệt giúp không gian bếp luôn sáng bóng, dễ lau chùi dầu mỡ và không bị mốc đường ron như gạch men thông thường.'
      }
    ];

    /* 4. Render lưới sản phẩm (2 cột trên điện thoại, hiển thị đầy đủ tên không cắt chữ) */
    function renderProducts(list) {
      const grid = document.getElementById('productGrid');
      const emptyMsg = document.getElementById('productEmptyMsg');
      if (!grid) return;

      if (!list || list.length === 0) {
        grid.innerHTML = '';
        emptyMsg.classList.remove('hidden');
        return;
      }

      emptyMsg.classList.add('hidden');
      grid.innerHTML = list.map((p) => `
        <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal(${p.id})">
            <!-- Nhãn giảm giá % ở góc trên bên trái -->
            <span class="absolute top-2 left-2 z-10 bg-red-600 text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 rounded-md shadow">
              ${p.discount}
            </span>
            <img
              src="https://lh3.googleusercontent.com/d/${p.fileId}"
              data-fallback="https://drive.google.com/thumbnail?id=${p.fileId}&sz=w700"
              data-placeholder="https://placehold.co/500x375/0B4A8B/FFFFFF?text=NHOM+XINGFA"
              onerror="handleImgFallback(this)"
              alt="${p.name}"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
            />
          </div>

          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2.5">
            <!-- Tên sản phẩm đầy đủ, không cắt bớt chữ, không tràn viền trên điện thoại -->
            <h3
              onclick="openProductModal(${p.id})"
              class="text-xs sm:text-sm md:text-[15px] font-bold text-slate-800 hover:text-brand cursor-pointer leading-snug break-words"
            >
              ${p.name}
            </h3>

            <div>
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2.5">
                <span class="text-sm sm:text-base font-extrabold text-red-600">${p.price}</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${p.oldPrice}</span>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-1.5">
                <button
                  type="button"
                  onclick="openProductModal(${p.id})"
                  class="w-full py-1.5 px-2 text-[11px] sm:text-xs font-semibold rounded-lg border border-brand text-brand hover:bg-brand-soft transition"
                >
                  Xem nhanh
                </button>
                <a
                  href="#bao-gia"
                  onclick="selectCategoryQuote('${p.name}')"
                  class="w-full py-1.5 px-2 text-center text-[11px] sm:text-xs font-bold rounded-lg bg-brand hover:bg-brand-dark text-white transition"
                >
                  Báo giá
                </a>
              </div>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterProducts(cat) {
      document.querySelectorAll('.prod-filter-btn').forEach((btn) => {
        const active = btn.dataset.filter === cat;
        btn.className = active
          ? 'prod-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-brand text-white transition'
          : 'prod-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-white text-slate-700 border border-slate-200 hover:border-brand transition';
      });
      const filtered = cat === 'all' ? PRODUCTS : PRODUCTS.filter((p) => p.category === cat);
      renderProducts(filtered);
    }

    /* 5. Render danh mục bài viết trang chủ */
    function renderPosts(list) {
      const grid = document.getElementById('postGrid');
      if (!grid) return;

      grid.innerHTML = list.map((post) => `
        <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] bg-slate-200 overflow-hidden cursor-pointer" onclick="openPostModal(${post.id})">
            <img
              src="https://lh3.googleusercontent.com/d/${post.fileId}"
              data-fallback="https://drive.google.com/thumbnail?id=${post.fileId}&sz=w600"
              data-placeholder="https://placehold.co/480x300/0B4A8B/FFFFFF?text=TIN+TUC"
              onerror="handleImgFallback(this)"
              alt="${post.title}"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between gap-3">
            <div>
              <div class="text-[11px] font-semibold text-brand uppercase mb-1.5">${post.catLabel}</div>
              <h3 onclick="openPostModal(${post.id})" class="text-sm font-bold text-slate-800 hover:text-brand cursor-pointer leading-snug mb-2">
                ${post.title}
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">${post.excerpt}</p>
            </div>
            <button
              type="button"
              onclick="openPostModal(${post.id})"
              class="w-fit text-xs font-bold text-brand hover:text-amber-600 inline-flex items-center gap-1 transition"
            >
              <span>Đọc chi tiết</span>
              <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
            </button>
          </div>
        </article>
      `).join('');
    }

    function filterPosts(cat) {
      document.querySelectorAll('.post-filter-btn').forEach((btn) => {
        const active = btn.dataset.postcat === cat;
        btn.className = active
          ? 'post-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-brand text-white transition'
          : 'post-filter-btn px-3.5 py-1.5 text-xs sm:text-sm font-semibold rounded-lg bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition';
      });
      const filtered = cat === 'all' ? POSTS : POSTS.filter((p) => p.cat === cat);
      renderPosts(filtered);
    }

    /* 6. Auto-sliding 2 Banner chuyên nghiệp + hỗ trợ vuốt cảm ứng trên điện thoại */
    let currentSlide = 0;
    let sliderTimer = null;

    function updateSlides() {
      const slides = document.querySelectorAll('.hero-slide');
      const dots = document.querySelectorAll('.slider-dot');
      slides.forEach((slide, idx) => {
        slide.classList.toggle('active', idx === currentSlide);
      });
      dots.forEach((dot, idx) => {
        if (idx === currentSlide) {
          dot.classList.remove('w-2.5', 'bg-white/50');
          dot.classList.add('w-7', 'bg-amber-400');
        } else {
          dot.classList.remove('w-7', 'bg-amber-400');
          dot.classList.add('w-2.5', 'bg-white/50');
        }
      });
    }

    function changeSlide(step) {
      const slides = document.querySelectorAll('.hero-slide');
      currentSlide = (currentSlide + step + slides.length) % slides.length;
      updateSlides();
      resetSliderTimer();
    }

    function goToSlide(index) {
      currentSlide = index;
      updateSlides();
      resetSliderTimer();
    }

    function resetSliderTimer() {
      if (sliderTimer) clearInterval(sliderTimer);
      sliderTimer = setInterval(() => {
        const slides = document.querySelectorAll('.hero-slide');
        currentSlide = (currentSlide + 1) % slides.length;
        updateSlides();
      }, 5000);
    }

    /* Hỗ trợ vuốt ngang trên điện thoại cho Banner */
    function initBannerTouchSwipe() {
      const sliderEl = document.getElementById('heroSlider');
      if (!sliderEl) return;
      let startX = 0;
      sliderEl.addEventListener('touchstart', (e) => {
        startX = e.changedTouches[0].screenX;
      }, { passive: true });
      sliderEl.addEventListener('touchend', (e) => {
        const endX = e.changedTouches[0].screenX;
        if (startX - endX > 45) changeSlide(1);
        else if (endX - startX > 45) changeSlide(-1);
      }, { passive: true });
    }

    /* 7. Menu Mobile Drawer */
    function openMobileMenu() {
      document.getElementById('mobileMenuOverlay').classList.remove('hidden');
      document.getElementById('mobileMenuDrawer').classList.remove('-translate-x-full');
      document.body.style.overflow = 'hidden';
    }

    function closeMobileMenu() {
      document.getElementById('mobileMenuOverlay').classList.add('hidden');
      document.getElementById('mobileMenuDrawer').classList.add('-translate-x-full');
      document.body.style.overflow = '';
    }

    function toggleMobileSub(id, btn) {
      const el = document.getElementById(id);
      if (!el) return;
      el.classList.toggle('hidden');
      const icon = btn.querySelector('svg');
      if (icon) icon.classList.toggle('rotate-180');
    }

    /* 8. Tìm kiếm sản phẩm nhanh */
    function runProductSearch(keyword) {
      const q = (keyword || '').trim().toLowerCase();
      if (!q) {
        filterProducts('all');
        return;
      }
      const matched = PRODUCTS.filter((p) => p.name.toLowerCase().includes(q) || p.specs.toLowerCase().includes(q));
      renderProducts(matched);
      document.getElementById('san-pham-xingfa').scrollIntoView({ behavior: 'smooth' });
    }

    function handleSearchSubmit(e) {
      e.preventDefault();
      runProductSearch(document.getElementById('headerSearchInput').value);
    }

    function handleMobileSearch(e) {
      e.preventDefault();
      runProductSearch(document.getElementById('mobileSearchInput').value);
      closeMobileMenu();
    }

    /* 9. Tự chọn hạng mục vào Form Báo Giá */
    function selectCategoryQuote(label) {
      const selectEl = document.getElementById('qCategory');
      const noteEl = document.getElementById('qNote');
      if (selectEl) {
        let matched = false;
        Array.from(selectEl.options).forEach((opt) => {
          if (opt.value.toLowerCase() === label.toLowerCase()) {
            selectEl.value = opt.value;
            matched = true;
          }
        });
        if (!matched) {
          selectEl.value = 'Cửa nhôm xingfa';
          if (noteEl) noteEl.value = 'Quan tâm sản phẩm: ' + label;
        }
      }
    }

    /* 10. Xử lý gửi Form yêu cầu & báo giá (dùng hộp thông báo nội tuyến, không dùng alert) */
    function handleQuoteSubmit(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const category = document.getElementById('qCategory').value;
      const feedback = document.getElementById('quoteFeedback');

      if (!name || !phone) {
        feedback.className = 'p-3.5 rounded-lg bg-red-50 border border-red-200 text-red-700 text-xs sm:text-sm font-medium';
        feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để chúng tôi liên hệ báo giá.';
        feedback.classList.remove('hidden');
        return;
      }

      feedback.className = 'p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium';
      feedback.innerHTML = `Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá hạng mục <strong>${category}</strong> đã được ghi nhận. Nhôm Kính Trần Hoàng sẽ gọi lại số <strong>${phone}</strong> sớm nhất hoặc liên hệ trực tiếp Hotline <a href="tel:0905044794" class="underline font-bold">0905.044.794</a>.`;
      feedback.classList.remove('hidden');
      document.getElementById('quoteForm').reset();
    }

    /* 11. Modal xem nhanh sản phẩm & đọc chi tiết bài viết */
    function openProductModal(id) {
      const p = PRODUCTS.find((item) => item.id === id);
      if (!p) return;
      document.getElementById('modalTitle').textContent = p.name;
      document.getElementById('modalBody').innerHTML = `
        <div class="relative rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
          <span class="absolute top-3 left-3 bg-red-600 text-white text-xs font-extrabold px-2.5 py-1 rounded-md shadow">${p.discount}</span>
          <img
            src="https://lh3.googleusercontent.com/d/${p.fileId}"
            data-fallback="https://drive.google.com/thumbnail?id=${p.fileId}&sz=w800"
            data-placeholder="https://placehold.co/640x400/0B4A8B/FFFFFF?text=NHOM+XINGFA"
            onerror="handleImgFallback(this)"
            alt="${p.name}"
            class="w-full h-full object-cover"
          />
        </div>
        <div class="flex items-baseline gap-3">
          <span class="text-xl font-extrabold text-red-600">${p.price}</span>
          <span class="text-sm text-slate-400 line-through">${p.oldPrice}</span>
          <span class="text-xs text-slate-500">/ m² (tham khảo)</span>
        </div>
        <p>${p.specs}</p>
        <div class="flex flex-wrap gap-2.5 pt-2">
          <a href="#bao-gia" onclick="selectCategoryQuote('${p.name}'); closeDetailModal();" class="px-5 py-2.5 bg-brand hover:bg-brand-dark text-white text-xs sm:text-sm font-bold rounded-lg transition">
            Nhận báo giá mẫu này
          </a>
          <a href="tel:0905044794" class="px-5 py-2.5 bg-red-600 hover:bg-red-700 text-white text-xs sm:text-sm font-bold rounded-lg transition">
            Gọi: 0905.044.794
          </a>
        </div>
      `;
      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function openPostModal(id) {
      const post = POSTS.find((item) => item.id === id);
      if (!post) return;
      document.getElementById('modalTitle').textContent = post.title;
      document.getElementById('modalBody').innerHTML = `
        <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
          <img
            src="https://lh3.googleusercontent.com/d/${post.fileId}"
            data-fallback="https://drive.google.com/thumbnail?id=${post.fileId}&sz=w800"
            data-placeholder="https://placehold.co/640x400/0B4A8B/FFFFFF?text=BAI+VIET"
            onerror="handleImgFallback(this)"
            alt="${post.title}"
            class="w-full h-full object-cover"
          />
        </div>
        <div class="text-xs font-semibold text-brand uppercase">${post.catLabel} • Nhôm Kính Trần Hoàng Đà Nẵng</div>
        <p>${post.content}</p>
        <div class="p-3.5 rounded-xl bg-brand-soft border border-blue-100 text-xs sm:text-sm text-slate-700">
          Cần tư vấn kỹ thuật và khảo sát tận nơi tại Đà Nẵng? Liên hệ ngay Hotline/Zalo: <a href="tel:0905044794" class="font-bold text-red-600">0905.044.794</a>.
        </div>
      `;
      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function closeModalOnBackdrop(e) {
      if (e.target && e.target.id === 'detailModal') {
        closeDetailModal();
      }
    }

    /* 12. Khởi chạy toàn bộ trang sau khi tải xong */
    window.addEventListener('DOMContentLoaded', () => {
      document.getElementById('mobileMenuToggle').addEventListener('click', openMobileMenu);
      renderProducts(PRODUCTS);
      renderPosts(POSTS);
      updateSlides();
      resetSliderTimer();
      initBannerTouchSwipe();
    });
  </script>
</body>
</html>
