<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>BOK DESIGN & BUILD | Thiết Kế & Thi Công Nội Thất Trọn Gói Đà Nẵng - bokdesign.vn</title>
  <meta name="description" content="CÔNG TY TNHH BOK DESIGN & BUILD (bokdesign.vn) - Chuyên thiết kế và thi công nội thất trọn gói nhà phố, căn hộ chung cư, biệt thự, văn phòng tại Đà Nẵng. Địa chỉ: 21 Nguyễn Hành, Phường Cẩm Lệ, TP Đà Nẵng. Hotline: 0396 104 869 – 0938 360 746." />

  <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://bokdesign.vn/" />
  <meta property="og:title" content="BOK DESIGN & BUILD - Thiết Kế & Thi Công Nội Thất Trọn Gói Đà Nẵng" />
  <meta property="og:description" content="Giải pháp thiết kế và thi công nội thất trọn gói uy tín tại Đà Nẵng. Địa chỉ: 21 Nguyễn Hành, P. Cẩm Lệ, TP. Đà Nẵng. ĐT: 0396 104 869 – 0938 360 746." />
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1n0iuG_1s9D3mTEbh-FaIQcjbiRBicevo&sz=w1200" />
  <meta property="og:image:alt" content="Logo BOK DESIGN & BUILD - bokdesign.vn" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1n0iuG_1s9D3mTEbh-FaIQcjbiRBicevo&sz=w1200" />
  <link rel="icon" href="https://drive.google.com/thumbnail?id=1n0iuG_1s9D3mTEbh-FaIQcjbiRBicevo&sz=w256" />

  <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    /* ==========================================================================
       CẤU HÌNH CHUẨN FLATSOME UX BUILDER - BOKDESIGN.VN
       Chiều ngang máy tính: 1500px | Chống tràn viền & chống lệch phải tuyệt đối
       ========================================================================== */
    :root {
      --bok-primary: #1f2a37;      /* Màu chủ đạo theo tông trầm sang trọng của Logo */
      --bok-gold: #b5853b;         /* Màu vàng đồng / gỗ nội thất theo Logo & TVT */
      --bok-gold-dark: #966b28;
      --bok-bg-light: #f7f6f2;
      --bok-text: #222222;
    }

    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden !important;
      margin: 0 !important;
      padding: 0 !important;
      font-family: 'Inter', sans-serif;
      color: var(--bok-text);
      background-color: #ffffff;
      scroll-behavior: smooth;
      -webkit-text-size-adjust: 100%;
    }

    h1, h2, h3, h4, .font-heading {
      font-family: 'Montserrat', sans-serif;
    }

    /* Container chuẩn 1500px trên máy tính, tự động căn giữa không lệch phải */
    .flatsome-container {
      width: 100%;
      max-width: 1500px;
      margin-left: auto !important;
      margin-right: auto !important;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .flatsome-container {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    /* Menu danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, tuyệt đối không xuống dòng */
    .desktop-nav-list {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-wrap: nowrap;
      gap: 4px;
      width: 100%;
    }

    .desktop-nav-item {
      white-space: nowrap !important;
      font-size: 12.5px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.2px;
      padding: 8px 9px;
      color: #1f2a37;
      transition: all 0.2s ease;
      border-radius: 4px;
      flex-shrink: 0;
    }

    @media (min-width: 1280px) {
      .desktop-nav-List {
        gap: 8px;
      }
      .desktop-nav-item {
        font-size: 13px;
        padding: 8px 11px;
      }
    }

    .desktop-nav-item:hover,
    .desktop-nav-item.active {
      color: var(--bok-gold);
      background-color: rgba(181, 133, 59, 0.08);
    }

    /* Danh mục chữ nhỏ gọn ở trang chủ - viết liền trên 1 hàng không rớt chữ */
    .cat-pill-item {
      white-space: nowrap !important;
      font-size: 12px;
      font-weight: 600;
      padding: 7px 12px;
      border: 1px solid #e5e7eb;
      background: #ffffff;
      color: #1f2a37;
      border-radius: 6px;
      transition: all 0.2s ease;
      text-align: center;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
    }

    .cat-pill-item:hover,
    .cat-pill-item.active {
      border-color: var(--bok-gold);
      background-color: var(--bok-gold);
      color: #ffffff;
    }

    /* Tên sản phẩm & dự án: hiển thị đầy đủ, không bị cắt chữ (...) hay tràn ra ngoài */
    .product-title-full {
      font-size: 13px;
      line-height: 1.45;
      font-weight: 600;
      color: #1f2a37;
      white-space: normal !important;
      overflow: visible !important;
      text-overflow: clip !important;
      word-break: break-word;
      display: block;
    }

    @media (min-width: 768px) {
      .product-title-full {
        font-size: 14.5px;
      }
    }

    /* Kích thước cố định bằng nhau cho 2 slide Banner */
    .banner-desktop-frame {
      width: 100%;
      height: 440px;
      position: relative;
      overflow: hidden;
      border-radius: 8px;
    }

    .banner-mobile-frame {
      width: 100%;
      height: 235px;
      position: relative;
      overflow: hidden;
      border-radius: 8px;
    }

    .banner-slide {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
    }

    .banner-slide.active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }

    /* Tiêu đề Section chuẩn Flatsome (Section Title Divider) */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 14px;
      margin-bottom: 10px;
      width: 100%;
    }

    .flatsome-section-title::before,
    .flatsome-section-title::after {
      content: "";
      flex: 1;
      max-width: 120px;
      height: 2px;
      background-color: var(--bok-gold);
      opacity: 0.45;
    }

    /* Card Flatsome đơn giản, dễ dựng lại trên UX Builder */
    .ux-box-card {
      background: #ffffff;
      border: 1px solid #ececec;
      border-radius: 6px;
      overflow: hidden;
      transition: transform 0.25s ease, box-shadow 0.25s ease;
      display: flex;
      flex-direction: column;
      height: 100%;
    }

    .ux-box-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 24px rgba(0, 0, 0, 0.07);
      border-color: #dcdcdc;
    }

    /* Nút nổi liên hệ Zalo, Facebook, Hotline */
    .floating-contact-wrap {
      position: fixed;
      left: 12px;
      bottom: 16px;
      z-index: 90;
      display: flex;
      flex-direction: column;
      gap: 8px;
      max-width: calc(100vw - 24px);
    }

    @keyframes pulseRing {
      0% { box-shadow: 0 0 0 0 rgba(181, 133, 59, 0.55); }
      70% { box-shadow: 0 0 0 10px rgba(181, 133, 59, 0); }
      100% { box-shadow: 0 0 0 0 rgba(181, 133, 59, 0); }
    }

    .btn-floating-pulse {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>

<body>

  <!-- ========================================================================
       1. TOP BAR (Thanh thông tin mỏng phía trên Header)
       ======================================================================== -->
  <div class="w-full bg-[#1f2a37] text-white text-[11.5px] md:text-[12.5px] py-1.5 border-b border-white/10">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 md:gap-5 truncate">
        <span class="inline-flex items-center gap-1.5 truncate">
          <i class="fa-solid fa-building text-[#b5853b]"></i>
          <strong class="font-semibold">CÔNG TY TNHH BOK DESIGN & BUILD</strong>
        </span>
        <span class="hidden md:inline-flex items-center gap-1.5 text-gray-200">
          <i class="fa-solid fa-location-dot text-[#b5853b]"></i>
          21 Nguyễn Hành, Phường Cẩm Lệ, TP Đà Nẵng
        </span>
      </div>
      <div class="flex items-center gap-3 md:gap-4 shrink-0">
        <a href="tel:0396104869" class="hover:text-[#b5853b] transition-colors inline-flex items-center gap-1">
          <i class="fa-solid fa-phone text-[#b5853b] text-[11px]"></i>
          <span>0396 104 869</span>
        </a>
        <span class="text-white/30">|</span>
        <a href="tel:0938360746" class="hover:text-[#b5853b] transition-colors inline-flex items-center gap-1">
          <span>0938 360 746</span>
        </a>
        <span class="hidden sm:inline text-white/30">|</span>
        <a href="https://www.facebook.com/profile.php?id=61591700077408" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex items-center gap-1 hover:text-[#b5853b] transition-colors">
          <i class="fa-brands fa-facebook"></i>
          <span>bokdesign.vn</span>
        </a>
      </div>
    </div>
  </div>

  <!-- ========================================================================
       2. HEADER CHÍNH (Logo thu gọn nhỏ + Danh mục 1 hàng chữ nhỏ, KHÔNG để nút gọi ngay)
       ======================================================================== -->
  <header class="w-full bg-white sticky top-0 z-50 border-b border-gray-200 shadow-sm">
    <div class="flatsome-container">
      <div class="flex items-center justify-between py-2 gap-3">
        
        <!-- Logo chỉnh gọn nhỏ lại theo đúng yêu cầu -->
        <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
          <div class="w-10 h-10 md:w-11 md:h-11 rounded border border-gray-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0">
            <img
              src="https://drive.google.com/thumbnail?id=1n0iuG_1s9D3mTEbh-FaIQcjbiRBicevo&sz=w400"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1n0iuG_1s9D3mTEbh-FaIQcjbiRBicevo';"
              alt="Logo BOK Design & Build - bokdesign.vn"
              class="w-full h-full object-contain"
            />
          </div>
          <div class="leading-tight">
            <span class="block font-heading font-extrabold text-[14px] md:text-[15.5px] tracking-tight text-[#1f2a37] group-hover:text-[#b5853b] transition-colors">
              BOK DESIGN
            </span>
            <span class="block text-[10px] font-semibold uppercase tracking-wider text-[#b5853b]">
              bokdesign.vn
            </span>
          </div>
        </a>

        <!-- Menu Danh Mục Máy Tính: Viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không xuống dòng -->
        <nav class="hidden lg:block flex-1 overflow-hidden px-1" aria-label="Menu chính">
          <ul class="desktop-nav-list">
            <li><a href="#trang-chu" class="desktop-nav-item active">Trang chủ</a></li>
            <li><a href="#gioi-thieu" class="desktop-nav-item">Giới thiệu</a></li>
            <li><a href="#danh-muc-mau" class="desktop-nav-item">Thi công nội thất</a></li>
            <li><a href="#danh-muc-mau" class="desktop-nav-item">Thiết kế nội thất</a></li>
            <li><a href="#san-pham-thuc-te" class="desktop-nav-item">Sản phẩm nội thất</a></li>
            <li><a href="#du-an-da-nang" class="desktop-nav-item">Dự án Đà Nẵng</a></li>
            <li><a href="#doi-tac" class="desktop-nav-item">Đối tác</a></li>
            <li><a href="#tin-tuc" class="desktop-nav-item">Tin tức</a></li>
            <li><a href="#form-bao-gia" class="desktop-nav-item">Báo giá & Liên hệ</a></li>
          </ul>
        </nav>

        <!-- Nút mở menu trên điện thoại (Không để nút Gọi ngay trên Header để tránh tràn viền) -->
        <div class="flex items-center gap-2 lg:hidden shrink-0">
          <button
            type="button"
            onclick="toggleMobileMenu()"
            class="p-2 rounded border border-gray-200 text-[#1f2a37] hover:bg-gray-100 focus:outline-none"
            aria-label="Mở danh mục"
          >
            <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
          </button>
        </div>

      </div>

      <!-- Dòng 2 trên máy tính: Các danh mục con chuẩn mẫu noithattvt.vn viết liền trên 1 hàng chữ nhỏ gọn -->
      <div class="hidden lg:flex items-center justify-center gap-2 py-1.5 border-t border-gray-100 bg-[#faf9f6] -mx-5 px-5">
        <a href="#san-pham-thuc-te" onclick="filterProducts('all')" class="text-[11.5px] font-medium text-gray-700 hover:text-[#b5853b] whitespace-nowrap px-2 py-0.5 rounded">Thi công nội thất chung cư</a>
        <span class="text-gray-300">•</span>
        <a href="#san-pham-thuc-te" onclick="filterProducts('nha-pho')" class="text-[11.5px] font-medium text-gray-700 hover:text-[#b5853b] whitespace-nowrap px-2 py-0.5 rounded">Thi công nội thất nhà phố</a>
        <span class="text-gray-300">•</span>
        <a href="#san-pham-thuc-te" onclick="filterProducts('biet-thu')" class="text-[11.5px] font-medium text-gray-700 hover:text-[#b5853b] whitespace-nowrap px-2 py-0.5 rounded">Thi công nội thất biệt thự, villa</a>
        <span class="text-gray-300">•</span>
        <a href="#san-pham-thuc-te" onclick="filterProducts('tu-bep')" class="text-[11.5px] font-medium text-gray-700 hover:text-[#b5853b] whitespace-nowrap px-2 py-0.5 rounded">Thi công tủ bếp & phòng ăn</a>
        <span class="text-gray-300">•</span>
        <a href="#san-pham-thuc-te" onclick="filterProducts('van-phong')" class="text-[11.5px] font-medium text-gray-700 hover:text-[#b5853b] whitespace-nowrap px-2 py-0.5 rounded">Thi công nội thất văn phòng</a>
        <span class="text-gray-300">•</span>
        <a href="#san-pham-thuc-te" onclick="filterProducts('cua-hang')" class="text-[11.5px] font-medium text-gray-700 hover:text-[#b5853b] whitespace-nowrap px-2 py-0.5 rounded">Thi công nội thất cửa hàng</a>
      </div>
    </div>

    <!-- Menu Điện Thoại (Xổ xuống gọn gàng) -->
    <div id="mobile-nav-drawer" class="hidden lg:hidden bg-white border-t border-gray-200 px-3 py-3">
      <div class="grid grid-cols-2 gap-2 text-[12.5px] font-semibold">
        <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2 rounded bg-gray-50 text-[#1f2a37] whitespace-nowrap"><i class="fa-solid fa-house text-[#b5853b] mr-1.5"></i>Trang chủ</a>
        <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2 rounded bg-gray-50 text-[#1f2a37] whitespace-nowrap"><i class="fa-solid fa-circle-info text-[#b5853b] mr-1.5"></i>Giới thiệu</a>
        <a href="#danh-muc-mau" onclick="toggleMobileMenu()" class="p-2 rounded bg-gray-50 text-[#1f2a37] whitespace-nowrap"><i class="fa-solid fa-hammer text-[#b5853b] mr-1.5"></i>Thi công nội thất</a>
        <a href="#danh-muc-mau" onclick="toggleMobileMenu()" class="p-2 rounded bg-gray-50 text-[#1f2a37] whitespace-nowrap"><i class="fa-solid fa-compass-drafting text-[#b5853b] mr-1.5"></i>Thiết kế nội thất</a>
        <a href="#san-pham-thuc-te" onclick="toggleMobileMenu()" class="p-2 rounded bg-gray-50 text-[#1f2a37] whitespace-nowrap"><i class="fa-solid fa-couch text-[#b5853b] mr-1.5"></i>Sản phẩm thực tế</a>
        <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2 rounded bg-gray-50 text-[#1f2a37] whitespace-nowrap"><i class="fa-solid fa-city text-[#b5853b] mr-1.5"></i>Dự án Đà Nẵng</a>
        <a href="#doi-tac" onclick="toggleMobileMenu()" class="p-2 rounded bg-gray-50 text-[#1f2a37] whitespace-nowrap"><i class="fa-solid fa-handshake text-[#b5853b] mr-1.5"></i>Đối tác</a>
        <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2 rounded bg-gray-50 text-[#1f2a37] whitespace-nowrap"><i class="fa-solid fa-newspaper text-[#b5853b] mr-1.5"></i>Tin tức</a>
        <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="col-span-2 p-2 rounded bg-[#b5853b] text-white text-center whitespace-nowrap"><i class="fa-solid fa-file-signature mr-1.5"></i>Yêu cầu tư vấn & Báo giá</a>
      </div>
    </div>
  </header>

  <!-- ========================================================================
       3. SLIDER 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
          - Thiết kế riêng 2 Banner Máy Tính và 2 Banner Điện Thoại
          - Chữ nhỏ gọn nằm trọn bên trong ảnh banner, không tràn viền
       ======================================================================== -->
  <section id="trang-chu" class="w-full py-3 bg-[#f7f6f2]">
    <div class="flatsome-container">

      <!-- 3A. BANNER DÀNH RIÊNG CHO MÁY TÍNH (2 ảnh kích thước bằng nhau 440px, tự trượt) -->
      <div class="hidden md:block banner-desktop-frame shadow-sm">
        
        <!-- Slide 1 Máy tính -->
        <div class="banner-slide desktop-slide active">
          <img
            src="https://drive.google.com/thumbnail?id=1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf&sz=w1600"
            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf';"
            alt="Banner 1 BOK Design & Build - Thiết kế thi công nội thất Đà Nẵng"
            class="w-full h-full object-cover"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-[#1f2a37]/90 via-[#1f2a37]/70 to-transparent flex items-center">
            <div class="px-10 lg:px-14 max-w-[680px] text-white">
              <p class="text-[12px] font-semibold uppercase tracking-widest text-[#e6be7a] mb-2">
                BOK DESIGN & BUILD – BOKDESIGN.VN
              </p>
              <h1 class="font-heading text-[24px] lg:text-[28px] font-bold leading-snug mb-3 text-white">
                THIẾT KẾ & THI CÔNG NỘI THẤT TRỌN GÓI TẠI ĐÀ NẴNG
              </h1>
              <p class="text-[13.5px] text-gray-200 leading-relaxed mb-4">
                Giải pháp không gian tổng thể cho Nhà phố, Căn hộ chung cư, Biệt thự - Villa, Văn phòng và Showroom. Chủ động sản xuất & thi công chuẩn bản vẽ 3D, tối ưu chi phí.
              </p>
              <div class="text-[12.5px] text-gray-200 space-y-1 mb-5 bg-black/25 p-3 rounded border-l-4 border-[#b5853b]">
                <div><i class="fa-solid fa-location-dot text-[#e6be7a] mr-2"></i>Địa chỉ: 21 Nguyễn Hành, Phường Cẩm Lệ, TP Đà Nẵng</div>
                <div><i class="fa-solid fa-phone-volume text-[#e6be7a] mr-2"></i>Hotline: <strong>0396 104 869 – 0938 360 746</strong></div>
              </div>
              <div class="flex items-center gap-3">
                <a href="#form-bao-gia" class="px-5 py-2.5 rounded bg-[#b5853b] hover:bg-[#966b28] text-white font-semibold text-[13px] transition-colors">
                  NHẬN BÁO GIÁ TRỌN GÓI
                </a>
                <a href="#du-an-da-nang" class="px-5 py-2.5 rounded bg-white/15 hover:bg-white/25 text-white font-semibold text-[13px] border border-white/30 transition-colors">
                  XEM CÔNG TRÌNH THỰC TẾ
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- Slide 2 Máy tính (Cùng kích thước 440px bằng nhau) -->
        <div class="banner-slide desktop-slide">
          <img
            src="https://drive.google.com/thumbnail?id=1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-&sz=w1600"
            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-';"
            alt="Banner 2 BOK Design & Build - Thi công nội thất gỗ cao cấp Đà Nẵng"
            class="w-full h-full object-cover"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-[#1f2a37]/90 via-[#1f2a37]/70 to-transparent flex items-center">
            <div class="px-10 lg:px-14 max-w-[680px] text-white">
              <p class="text-[12px] font-semibold uppercase tracking-widest text-[#e6be7a] mb-2">
                CHẤT LƯỢNG TỪ XƯỞNG SẢN XUẤT ĐẾN CÔNG TRÌNH
              </p>
              <h2 class="font-heading text-[24px] lg:text-[28px] font-bold leading-snug mb-3 text-white">
                NỘI THẤT GỖ HIỆN ĐẠI – CHUẨN TIẾN ĐỘ & BẢO HÀNH DÀI HẠN
              </h2>
              <p class="text-[13.5px] text-gray-200 leading-relaxed mb-4">
                Chuyên thi công tủ bếp, phòng khách, phòng ngủ, vách ốp trang trí, hoàn thiện xây dựng và lắp đặt nội thất trọn gói tại TP. Đà Nẵng và miền Trung.
              </p>
              <div class="text-[12.5px] text-gray-200 space-y-1 mb-5 bg-black/25 p-3 rounded border-l-4 border-[#b5853b]">
                <div><i class="fa-solid fa-check-circle text-[#e6be7a] mr-2"></i>Miễn phí khảo sát mặt bằng & tư vấn giải pháp tại Đà Nẵng</div>
                <div><i class="fa-solid fa-phone-volume text-[#e6be7a] mr-2"></i>Tư vấn 24/7: <strong>0396 104 869 – 0938 360 746</strong></div>
              </div>
              <div class="flex items-center gap-3">
                <a href="#san-pham-thuc-te" class="px-5 py-2.5 rounded bg-[#b5853b] hover:bg-[#966b28] text-white font-semibold text-[13px] transition-colors">
                  XEM HÌNH ẢNH THỰC TẾ
                </a>
                <a href="#form-bao-gia" class="px-5 py-2.5 rounded bg-white/15 hover:bg-white/25 text-white font-semibold text-[13px] border border-white/30 transition-colors">
                  ĐĂNG KÝ KHẢO SÁT
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng Slide Máy Tính -->
        <button type="button" onclick="changeSlide(-1)" class="absolute left-3 top-1/2 -translate-y-1/2 z-10 w-9 h-9 rounded-full bg-black/40 hover:bg-[#b5853b] text-white flex items-center justify-center transition-colors" aria-label="Slide trước">
          <i class="fa-solid fa-chevron-left text-sm"></i>
        </button>
        <button type="button" onclick="changeSlide(1)" class="absolute right-3 top-1/2 -translate-y-1/2 z-10 w-9 h-9 rounded-full bg-black/40 hover:bg-[#b5853b] text-white flex items-center justify-center transition-colors" aria-label="Slide tiếp">
          <i class="fa-solid fa-chevron-right text-sm"></i>
        </button>
      </div>

      <!-- 3B. BANNER THIẾT KẾ MỚI DÀNH RIÊNG CHO ĐIỆN THOẠI (Khác với bản máy tính, chữ nhỏ gọn nằm hết bên trong ảnh, không tràn viền) -->
      <div class="block md:hidden banner-mobile-frame shadow-sm">
        
        <!-- Slide 1 Điện thoại -->
        <div class="banner-slide mobile-slide active">
          <img
            src="https://drive.google.com/thumbnail?id=1TmZhkHrFuChVwR4NCmddR0KBSDCRNO74&sz=w900"
            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1TmZhkHrFuChVwR4NCmddR0KBSDCRNO74';"
            alt="Banner Mobile 1 BOK Design Đà Nẵng"
            class="w-full h-full object-cover"
          />
          <div class="absolute inset-0 bg-[#1f2a37]/80 flex flex-col justify-center items-center text-center px-4 py-3">
            <div class="w-full max-w-[92%] border border-[#b5853b]/50 bg-black/30 rounded p-2.5 text-white">
              <p class="text-[10px] font-bold uppercase tracking-wider text-[#e6be7a] mb-1">
                BOK DESIGN & BUILD • BOKDESIGN.VN
              </p>
              <h2 class="font-heading text-[13.5px] font-bold leading-snug text-white mb-1">
                THIẾT KẾ & THI CÔNG NỘI THẤT ĐÀ NẴNG
              </h2>
              <p class="text-[11px] text-gray-200 leading-tight mb-1.5">
                Nhà phố • Căn hộ • Biệt thự • Tủ bếp • Văn phòng
              </p>
              <p class="text-[10.5px] text-gray-200 leading-tight mb-2">
                ĐC: 21 Nguyễn Hành, P. Cẩm Lệ, TP Đà Nẵng<br />
                ĐT: <strong>0396 104 869 – 0938 360 746</strong>
              </p>
              <a href="#form-bao-gia" class="inline-block px-3 py-1 rounded bg-[#b5853b] text-white text-[10.5px] font-semibold">
                Nhận báo giá ngay
              </a>
            </div>
          </div>
        </div>

        <!-- Slide 2 Điện thoại (Kích thước bằng nhau 235px) -->
        <div class="banner-slide mobile-slide">
          <img
            src="https://drive.google.com/thumbnail?id=1EEodFcV7gBxhAETHP9x7aQNA0QoODj1k&sz=w900"
            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1EEodFcV7gBxhAETHP9x7aQNA0QoODj1k';"
            alt="Banner Mobile 2 BOK Design Đà Nẵng"
            class="w-full h-full object-cover"
          />
          <div class="absolute inset-0 bg-[#1f2a37]/80 flex flex-col justify-center items-center text-center px-4 py-3">
            <div class="w-full max-w-[92%] border border-[#b5853b]/50 bg-black/30 rounded p-2.5 text-white">
              <p class="text-[10px] font-bold uppercase tracking-wider text-[#e6be7a] mb-1">
                CAM KẾT CHẤT LƯỢNG & TIẾN ĐỘ
              </p>
              <h2 class="font-heading text-[13.5px] font-bold leading-snug text-white mb-1">
                THI CÔNG CHUẨN BẢN VẼ – GIÁ TẬN XƯỞNG
              </h2>
              <p class="text-[11px] text-gray-200 leading-tight mb-1.5">
                Khảo sát & Tư vấn miễn phí tại TP. Đà Nẵng
              </p>
              <p class="text-[10.5px] text-gray-200 leading-tight mb-2">
                Website: bokdesign.vn<br />
                Hotline: <strong>0396 104 869 – 0938 360 746</strong>
              </p>
              <a href="#san-pham-thuc-te" class="inline-block px-3 py-1 rounded bg-[#b5853b] text-white text-[10.5px] font-semibold">
                Xem công trình thực tế
              </a>
            </div>
          </div>
        </div>

      </div>

      <!-- Chấm tròn chỉ báo Slide -->
      <div class="flex items-center justify-center gap-2 mt-2.5">
        <button type="button" onclick="setSlide(0)" id="dot-0" class="w-6 h-2 rounded-full bg-[#b5853b] transition-all" aria-label="Slide 1"></button>
        <button type="button" onclick="setSlide(1)" id="dot-1" class="w-2.5 h-2 rounded-full bg-gray-300 transition-all" aria-label="Slide 2"></button>
      </div>

    </div>
  </section>

  <!-- ========================================================================
       4. DANH MỤC SẢN PHẨM & DỊCH VỤ (Lấy theo web mẫu noithattvt.vn)
          - Thiết kế gọn đẹp trên máy tính & điện thoại
          - Chữ danh mục nhỏ gọn, viết liền trên 1 hàng không bị rớt chữ
       ======================================================================== -->
  <section id="danh-muc-mau" class="w-full py-7 bg-white border-b border-gray-100">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <h2 class="font-heading text-[16px] md:text-[20px] font-bold uppercase text-[#1f2a37] text-center">
          DANH MỤC THIẾT KẾ & THI CÔNG NỘI THẤT
        </h2>
      </div>
      <p class="text-center text-[12.5px] md:text-[13.5px] text-gray-600 mb-5">
        Hệ thống danh mục dịch vụ và sản phẩm chủ lực tại <strong>bokdesign.vn</strong>
      </p>

      <!-- Dãy nút danh mục: Trên máy tính nằm gọn trên 1 hàng hoặc hàng 2, tên danh mục viết liền tuyệt đối không xuống dòng -->
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-2.5 mb-5">
        <a href="#san-pham-thuc-te" onclick="filterProducts('chung-cu')" class="cat-pill-item">
          <i class="fa-solid fa-building text-[#b5853b]"></i>
          <span>Nội thất chung cư</span>
        </a>
        <a href="#san-pham-thuc-te" onclick="filterProducts('nha-pho')" class="cat-pill-item">
          <i class="fa-solid fa-house-chimney text-[#b5853b]"></i>
          <span>Nội thất nhà phố</span>
        </a>
        <a href="#san-pham-thuc-te" onclick="filterProducts('biet-thu')" class="cat-pill-item">
          <i class="fa-solid fa-hotel text-[#b5853b]"></i>
          <span>Nội thất biệt thự, villa</span>
        </a>
        <a href="#san-pham-thuc-te" onclick="filterProducts('van-phong')" class="cat-pill-item">
          <i class="fa-solid fa-briefcase text-[#b5853b]"></i>
          <span>Nội thất văn phòng</span>
        </a>
        <a href="#san-pham-thuc-te" onclick="filterProducts('cua-hang')" class="cat-pill-item">
          <i class="fa-solid fa-store text-[#b5853b]"></i>
          <span>Nội thất cửa hàng</span>
        </a>
        <a href="#san-pham-thuc-te" onclick="filterProducts('phong-khach')" class="cat-pill-item">
          <i class="fa-solid fa-couch text-[#b5853b]"></i>
          <span>Nội thất phòng khách</span>
        </a>
        <a href="#san-pham-thuc-te" onclick="filterProducts('tu-bep')" class="cat-pill-item">
          <i class="fa-solid fa-kitchen-set text-[#b5853b]"></i>
          <span>Tủ bếp & Phòng ăn</span>
        </a>
        <a href="#san-pham-thuc-te" onclick="filterProducts('phong-ngu')" class="cat-pill-item">
          <i class="fa-solid fa-bed text-[#b5853b]"></i>
          <span>Nội thất phòng ngủ</span>
        </a>
        <a href="#san-pham-thuc-te" onclick="filterProducts('hoan-thien')" class="cat-pill-item">
          <i class="fa-solid fa-trowel-bricks text-[#b5853b]"></i>
          <span>Cải tạo & Hoàn thiện</span>
        </a>
        <a href="#san-pham-thuc-te" onclick="filterProducts('all')" class="cat-pill-item active">
          <i class="fa-solid fa-layer-group"></i>
          <span>Xem tất cả hạng mục</span>
        </a>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       5. VỀ CHÚNG TÔI & NĂNG LỰC BOK DESIGN & BUILD (Theo bố cục mẫu noithattvt.vn)
       ======================================================================== -->
  <section id="gioi-thieu" class="w-full py-8 bg-[#f7f6f2]">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        
        <!-- Cột nội dung giới thiệu -->
        <div class="lg:col-span-6 space-y-3.5">
          <div class="text-[12px] font-bold uppercase tracking-wider text-[#b5853b]">
            VỀ CHÚNG TÔI – BOKDESIGN.VN
          </div>
          <h2 class="font-heading text-[18px] md:text-[23px] font-bold text-[#1f2a37] leading-snug">
            CÔNG TY TNHH BOK DESIGN & BUILD – ĐƠN VỊ THIẾT KẾ & THI CÔNG NỘI THẤT TRỌN GÓI TẠI ĐÀ NẴNG
          </h2>
          <p class="text-[13.5px] text-gray-700 leading-relaxed">
            <strong>BOK DESIGN & BUILD</strong> là đơn vị chuyên sâu trong lĩnh vực Thiết kế, Sản xuất và Thi công Nội thất – Xây dựng trọn gói tại TP. Đà Nẵng và khu vực miền Trung. Chúng tôi mang đến giải pháp không gian đồng bộ cho <strong>nhà phố, căn hộ chung cư, biệt thự - villa, văn phòng làm việc và cửa hàng kinh doanh</strong>.
          </p>
          <p class="text-[13.5px] text-gray-700 leading-relaxed">
            Sở hữu đội ngũ kiến trúc sư, kỹ sư và thợ lành nghề tâm huyết cùng quy trình sản xuất – lắp đặt trực tiếp không qua trung gian, <strong>bokdesign.vn</strong> giúp khách hàng kiểm soát chặt chẽ chất lượng vật liệu, đảm bảo độ sắc nét thực tế đạt 95% – 100% so với thiết kế 3D và tối ưu ngân sách đầu tư.
          </p>

          <!-- 4 giá trị cốt lõi theo mẫu TVT -->
          <div class="grid grid-cols-2 gap-3 pt-2">
            <div class="bg-white p-3 rounded border border-gray-200">
              <div class="font-heading font-bold text-[15px] text-[#b5853b] mb-0.5">Trực Tiếp Sản Xuất</div>
              <p class="text-[12px] text-gray-600">Chủ động gia công nội thất gỗ, tủ bếp, giường tủ chuẩn kích thước thực tế.</p>
            </div>
            <div class="bg-white p-3 rounded border border-gray-200">
              <div class="font-heading font-bold text-[15px] text-[#b5853b] mb-0.5">Đội Ngũ Lành Nghề</div>
              <p class="text-[12px] text-gray-600">Kiến trúc sư & kỹ thuật viên giám sát xuyên suốt tại công trình Đà Nẵng.</p>
            </div>
            <div class="bg-white p-3 rounded border border-gray-200">
              <div class="font-heading font-bold text-[15px] text-[#b5853b] mb-0.5">Vật Liệu Chính Hãng</div>
              <p class="text-[12px] text-gray-600">Cam kết nguồn gỗ công nghiệp An Cường, phụ kiện Hafele, Blum rõ nguồn gốc.</p>
            </div>
            <div class="bg-white p-3 rounded border border-gray-200">
              <div class="font-heading font-bold text-[15px] text-[#b5853b] mb-0.5">Chi Phí Tối Ưu</div>
              <p class="text-[12px] text-gray-600">Báo giá bóc tách minh bạch từng hạng mục, bảo hành & bảo trì tận tâm.</p>
            </div>
          </div>
        </div>

        <!-- Cột hình ảnh thực tế từ file Google Drive -->
        <div class="lg:col-span-6 grid grid-cols-2 gap-3">
          <div class="rounded overflow-hidden border border-gray-200 bg-white">
            <img
              src="https://drive.google.com/thumbnail?id=13Y4ShtC9ywPSib30OYuFlJtpg1ZCfrQw&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13Y4ShtC9ywPSib30OYuFlJtpg1ZCfrQw';"
              alt="Không gian nội thất thực tế BOK Design & Build"
              class="w-full h-44 md:h-56 object-cover cursor-pointer"
              onclick="openLightbox(this.src, 'Thi công hoàn thiện nội thất thực tế - BOK Design & Build Đà Nẵng')"
            />
          </div>
          <div class="rounded overflow-hidden border border-gray-200 bg-white">
            <img
              src="https://drive.google.com/thumbnail?id=117iNO4EgkWmp7gZ1qAmhBRSSpVuOZ9qP&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/117iNO4EgkWmp7gZ1qAmhBRSSpVuOZ9qP';"
              alt="Thi công nội thất thực tế BOK Design & Build"
              class="w-full h-44 md:h-56 object-cover cursor-pointer"
              onclick="openLightbox(this.src, 'Không gian nội thất thiết kế & thi công trọn gói - BOK Design & Build')"
            />
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       6. DANH MỤC SẢN PHẨM & HẠNG MỤC NỘI THẤT THỰC TẾ (11 Ảnh Google Drive)
          - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính
          - KHÔNG để các nhãn dán (stickers/badges) ở trang chủ
          - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ
       ======================================================================== -->
  <section id="san-pham-thuc-te" class="w-full py-8 bg-white">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <h2 class="font-heading text-[16px] md:text-[20px] font-bold uppercase text-[#1f2a37] text-center">
          SẢN PHẨM & HẠNG MỤC THI CÔNG NỘI THẤT THỰC TẾ
        </h2>
      </div>
      <p class="text-center text-[12.5px] md:text-[13.5px] text-gray-600 mb-6">
        Hình ảnh thực tế các hạng mục nội thất do <strong>BOK DESIGN & BUILD (bokdesign.vn)</strong> thiết kế và thi công hoàn thiện
      </p>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
      <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">

        <!-- Sản phẩm 1 (File: 1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf) -->
        <div class="ux-box-card product-item" data-category="phong-khach nha-pho">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf';"
              alt="Thi công nội thất phòng khách nhà phố hiện đại Đà Nẵng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thi công nội thất phòng khách nhà phố hiện đại Đà Nẵng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Nội thất phòng khách</div>
              <h3 class="product-title-full mb-2">
                Thi công nội thất phòng khách nhà phố hiện đại Đà Nẵng
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Báo giá theo thiết kế</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 2 (File: 1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-) -->
        <div class="ux-box-card product-item" data-category="tu-bep nha-pho">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-';"
              alt="Hệ tủ bếp gỗ MDF chống ẩm phủ Melamine kết hợp bàn đảo"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Hệ tủ bếp gỗ MDF chống ẩm phủ Melamine kết hợp bàn đảo')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Tủ bếp & Phòng ăn</div>
              <h3 class="product-title-full mb-2">
                Hệ tủ bếp gỗ MDF chống ẩm phủ Melamine kết hợp bàn đảo
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Báo giá theo kích thước</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 3 (File: 1TmZhkHrFuChVwR4NCmddR0KBSDCRNO74) -->
        <div class="ux-box-card product-item" data-category="phong-ngu chung-cu">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1TmZhkHrFuChVwR4NCmddR0KBSDCRNO74&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1TmZhkHrFuChVwR4NCmddR0KBSDCRNO74';"
              alt="Combo nội thất phòng ngủ Master giường bọc nệm và tủ áo kịch trần"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Combo nội thất phòng ngủ Master giường bọc nệm và tủ áo kịch trần')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Nội thất phòng ngủ</div>
              <h3 class="product-title-full mb-2">
                Combo nội thất phòng ngủ Master giường bọc nệm và tủ áo kịch trần
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Thi công trọn gói</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 4 (File: 1EEodFcV7gBxhAETHP9x7aQNA0QoODj1k) -->
        <div class="ux-box-card product-item" data-category="chung-cu phong-khach">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1EEodFcV7gBxhAETHP9x7aQNA0QoODj1k&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1EEodFcV7gBxhAETHP9x7aQNA0QoODj1k';"
              alt="Thiết kế thi công nội thất căn hộ chung cư 2 phòng ngủ tại Đà Nẵng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thiết kế thi công nội thất căn hộ chung cư 2 phòng ngủ tại Đà Nẵng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Nội thất chung cư</div>
              <h3 class="product-title-full mb-2">
                Thiết kế thi công nội thất căn hộ chung cư 2 phòng ngủ tại Đà Nẵng
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Thi công trọn gói</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 5 (File: 13Y4ShtC9ywPSib30OYuFlJtpg1ZCfrQw) -->
        <div class="ux-box-card product-item" data-category="phong-khach biet-thu">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=13Y4ShtC9ywPSib30OYuFlJtpg1ZCfrQw&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13Y4ShtC9ywPSib30OYuFlJtpg1ZCfrQw';"
              alt="Hệ kệ tivi treo tường kết hợp vách ốp lam sóng và tủ rượu cánh kính"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Hệ kệ tivi treo tường kết hợp vách ốp lam sóng và tủ rượu cánh kính')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Nội thất phòng khách</div>
              <h3 class="product-title-full mb-2">
                Hệ kệ tivi treo tường kết hợp vách ốp lam sóng và tủ rượu cánh kính
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Báo giá tại xưởng</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 6 (File: 117iNO4EgkWmp7gZ1qAmhBRSSpVuOZ9qP) -->
        <div class="ux-box-card product-item" data-category="nha-pho biet-thu">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=117iNO4EgkWmp7gZ1qAmhBRSSpVuOZ9qP&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/117iNO4EgkWmp7gZ1qAmhBRSSpVuOZ9qP';"
              alt="Thi công nội thất nhà phố 3 tầng phong cách hiện đại ấm cúng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thi công nội thất nhà phố 3 tầng phong cách hiện đại ấm cúng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Nội thất nhà phố</div>
              <h3 class="product-title-full mb-2">
                Thi công nội thất nhà phố 3 tầng phong cách hiện đại ấm cúng
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Thi công trọn gói</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 7 (File: 1acrKuRUxa1ypvTx3RpGkPgB80vIuhAOh) -->
        <div class="ux-box-card product-item" data-category="phong-ngu nha-pho">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1acrKuRUxa1ypvTx3RpGkPgB80vIuhAOh&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1acrKuRUxa1ypvTx3RpGkPgB80vIuhAOh';"
              alt="Hệ tủ quần áo gỗ công nghiệp cánh mở kết hợp bàn trang điểm đồng bộ"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Hệ tủ quần áo gỗ công nghiệp cánh mở kết hợp bàn trang điểm đồng bộ')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Nội thất phòng ngủ</div>
              <h3 class="product-title-full mb-2">
                Hệ tủ quần áo gỗ công nghiệp cánh mở kết hợp bàn trang điểm đồng bộ
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Báo giá theo m²</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 8 (File: 12gGNfau-CvOQDq4PAugha-Ha_mESFyr5) -->
        <div class="ux-box-card product-item" data-category="van-phong cua-hang">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=12gGNfau-CvOQDq4PAugha-Ha_mESFyr5&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/12gGNfau-CvOQDq4PAugha-Ha_mESFyr5';"
              alt="Thiết kế và thi công nội thất văn phòng làm việc kết hợp quầy lễ tân"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thiết kế và thi công nội thất văn phòng làm việc kết hợp quầy lễ tân')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Nội thất văn phòng</div>
              <h3 class="product-title-full mb-2">
                Thiết kế và thi công nội thất văn phòng làm việc kết hợp quầy lễ tân
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Thi công trọn gói</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 9 (File: 13Mhnik-evhl6nsXIUPh83Cp-bPWE3TNK) -->
        <div class="ux-box-card product-item" data-category="tu-bep chung-cu">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=13Mhnik-evhl6nsXIUPh83Cp-bPWE3TNK&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13Mhnik-evhl6nsXIUPh83Cp-bPWE3TNK';"
              alt="Tủ bếp chữ L cánh Acrylic bóng gương kết hợp hệ đèn LED cảm ứng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Tủ bếp chữ L cánh Acrylic bóng gương kết hợp hệ đèn LED cảm ứng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Tủ bếp & Phòng ăn</div>
              <h3 class="product-title-full mb-2">
                Tủ bếp chữ L cánh Acrylic bóng gương kết hợp hệ đèn LED cảm ứng
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Báo giá theo md</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 10 (File: 1tVJrwE5C8r6-Xrk7tAhO6CKT1Yxi9URR) -->
        <div class="ux-box-card product-item" data-category="biet-thu phong-khach">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1tVJrwE5C8r6-Xrk7tAhO6CKT1Yxi9URR&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1tVJrwE5C8r6-Xrk7tAhO6CKT1Yxi9URR';"
              alt="Thiết kế thi công nội thất biệt thự nghỉ dưỡng cao cấp tại Đà Nẵng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thiết kế thi công nội thất biệt thự nghỉ dưỡng cao cấp tại Đà Nẵng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Nội thất biệt thự, villa</div>
              <h3 class="product-title-full mb-2">
                Thiết kế thi công nội thất biệt thự nghỉ dưỡng cao cấp tại Đà Nẵng
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Thi công trọn gói</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 11 (File: 18m_uYDlWv5QAk0WOBszwWmSz7LYl0Jn5) -->
        <div class="ux-box-card product-item" data-category="hoan-thien cua-hang">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=18m_uYDlWv5QAk0WOBszwWmSz7LYl0Jn5&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/18m_uYDlWv5QAk0WOBszwWmSz7LYl0Jn5';"
              alt="Thi công hoàn thiện nội thất gỗ, trần thạch cao và hệ thống ánh sáng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thi công hoàn thiện nội thất gỗ, trần thạch cao và hệ thống ánh sáng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Cải tạo & Hoàn thiện</div>
              <h3 class="product-title-full mb-2">
                Thi công hoàn thiện nội thất gỗ, trần thạch cao và hệ thống ánh sáng
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Khảo sát miễn phí</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 12 (Tổng hợp giải pháp trọn gói BOK Design) -->
        <div class="ux-box-card product-item" data-category="chung-cu nha-pho">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf';"
              alt="Gói thiết kế 3D và thi công nội thất trọn gói căn hộ và nhà phố Đà Nẵng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Gói thiết kế 3D và thi công nội thất trọn gói căn hộ và nhà phố Đà Nẵng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-500 mb-1">Thiết kế & Thi công trọn gói</div>
              <h3 class="product-title-full mb-2">
                Gói thiết kế 3D và thi công nội thất trọn gói căn hộ và nhà phố Đà Nẵng
              </h3>
            </div>
            <div class="pt-2 border-t border-gray-100 flex items-center justify-between text-[12px]">
              <span class="font-semibold text-[#b5853b]">Miễn phí 100% TK 3D</span>
              <a href="#form-bao-gia" class="text-[#1f2a37] hover:text-[#b5853b] font-medium">Tư vấn</a>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       7. DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (Đưa ra ngoài Trang Chủ)
          - Chia 2 cột trên điện thoại, 4 cột trên máy tính
          - Không để nhãn dán, tên dự án hiển thị đầy đủ
       ======================================================================== -->
  <section id="du-an-da-nang" class="w-full py-8 bg-[#f7f6f2] border-t border-gray-200">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <h2 class="font-heading text-[16px] md:text-[20px] font-bold uppercase text-[#1f2a37] text-center">
          DỰ ÁN THIẾT KẾ & THI CÔNG TẠI ĐÀ NẴNG
        </h2>
      </div>
      <p class="text-center text-[12.5px] md:text-[13.5px] text-gray-600 mb-5">
        Các công trình thực tế tiêu biểu do <strong>BOK DESIGN & BUILD</strong> thực hiện tại các quận huyện TP. Đà Nẵng
      </p>

      <!-- Danh mục lọc dự án Đà Nẵng (Chữ nhỏ gọn trên 1 hàng) -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
        <button type="button" onclick="filterProjects('all', this)" class="project-filter-btn cat-pill-item active">Tất cả dự án Đà Nẵng</button>
        <button type="button" onclick="filterProjects('cam-le', this)" class="project-filter-btn cat-pill-item">Khu vực Cẩm Lệ - Hòa Xuân</button>
        <button type="button" onclick="filterProjects('hai-chau', this)" class="project-filter-btn cat-pill-item">Khu vực Hải Châu</button>
        <button type="button" onclick="filterProjects('son-tra', this)" class="project-filter-btn cat-pill-item">Khu vực Sơn Trà - Ngũ Hành Sơn</button>
      </div>

      <!-- Lưới dự án Đà Nẵng: 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">

        <!-- Dự án Đà Nẵng 1 -->
        <div class="ux-box-card project-card" data-region="cam-le">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=117iNO4EgkWmp7gZ1qAmhBRSSpVuOZ9qP&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/117iNO4EgkWmp7gZ1qAmhBRSSpVuOZ9qP';"
              alt="Thiết kế thi công nội thất nhà phố Khu đô thị Hòa Xuân, Cẩm Lệ, Đà Nẵng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thiết kế thi công nội thất nhà phố Khu đô thị Hòa Xuân, Cẩm Lệ, Đà Nẵng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5">
            <div class="text-[11px] text-[#b5853b] font-semibold mb-1">Phường Cẩm Lệ, TP. Đà Nẵng</div>
            <h3 class="product-title-full">
              Thiết kế thi công nội thất nhà phố Khu đô thị Hòa Xuân, Cẩm Lệ, Đà Nẵng
            </h3>
          </div>
        </div>

        <!-- Dự án Đà Nẵng 2 -->
        <div class="ux-box-card project-card" data-region="son-tra">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1EEodFcV7gBxhAETHP9x7aQNA0QoODj1k&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1EEodFcV7gBxhAETHP9x7aQNA0QoODj1k';"
              alt="Thi công nội thất căn hộ Sun Ponte Residence Đà Nẵng trọn gói"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thi công nội thất căn hộ Sun Ponte Residence Đà Nẵng trọn gói')"
            />
          </div>
          <div class="p-2.5 md:p-3.5">
            <div class="text-[11px] text-[#b5853b] font-semibold mb-1">Quận Sơn Trà, TP. Đà Nẵng</div>
            <h3 class="product-title-full">
              Thi công nội thất căn hộ Sun Ponte Residence Đà Nẵng trọn gói
            </h3>
          </div>
        </div>

        <!-- Dự án Đà Nẵng 3 -->
        <div class="ux-box-card project-card" data-region="son-tra">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1TmZhkHrFuChVwR4NCmddR0KBSDCRNO74&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1TmZhkHrFuChVwR4NCmddR0KBSDCRNO74';"
              alt="Thiết kế thi công căn hộ 3 phòng ngủ FPT Plaza Đà Nẵng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thiết kế thi công căn hộ 3 phòng ngủ FPT Plaza Đà Nẵng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5">
            <div class="text-[11px] text-[#b5853b] font-semibold mb-1">Ngũ Hành Sơn, TP. Đà Nẵng</div>
            <h3 class="product-title-full">
              Thiết kế thi công căn hộ 3 phòng ngủ FPT Plaza Đà Nẵng
            </h3>
          </div>
        </div>

        <!-- Dự án Đà Nẵng 4 -->
        <div class="ux-box-card project-card" data-region="hai-chau">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=12gGNfau-CvOQDq4PAugha-Ha_mESFyr5&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/12gGNfau-CvOQDq4PAugha-Ha_mESFyr5';"
              alt="Thiết kế thi công nội thất văn phòng và showroom tại Hải Châu, Đà Nẵng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thiết kế thi công nội thất văn phòng và showroom tại Hải Châu, Đà Nẵng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5">
            <div class="text-[11px] text-[#b5853b] font-semibold mb-1">Quận Hải Châu, TP. Đà Nẵng</div>
            <h3 class="product-title-full">
              Thiết kế thi công nội thất văn phòng và showroom tại Hải Châu, Đà Nẵng
            </h3>
          </div>
        </div>

        <!-- Dự án Đà Nẵng 5 -->
        <div class="ux-box-card project-card" data-region="cam-le">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-';"
              alt="Thi công nội thất phòng bếp và phòng khách nhà phố Nguyễn Hành, Cẩm Lệ"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thi công nội thất phòng bếp và phòng khách nhà phố Nguyễn Hành, Cẩm Lệ')"
            />
          </div>
          <div class="p-2.5 md:p-3.5">
            <div class="text-[11px] text-[#b5853b] font-semibold mb-1">Phường Cẩm Lệ, TP. Đà Nẵng</div>
            <h3 class="product-title-full">
              Thi công nội thất phòng bếp và phòng khách nhà phố Nguyễn Hành, Cẩm Lệ
            </h3>
          </div>
        </div>

        <!-- Dự án Đà Nẵng 6 -->
        <div class="ux-box-card project-card" data-region="son-tra">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1tVJrwE5C8r6-Xrk7tAhO6CKT1Yxi9URR&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1tVJrwE5C8r6-Xrk7tAhO6CKT1Yxi9URR';"
              alt="Thiết kế thi công nội thất Biệt thự Euro Village 2 bên sông Hàn Đà Nẵng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thiết kế thi công nội thất Biệt thự Euro Village 2 bên sông Hàn Đà Nẵng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5">
            <div class="text-[11px] text-[#b5853b] font-semibold mb-1">Phường Cẩm Lệ, TP. Đà Nẵng</div>
            <h3 class="product-title-full">
              Thiết kế thi công nội thất Biệt thự Euro Village 2 bên sông Hàn Đà Nẵng
            </h3>
          </div>
        </div>

        <!-- Dự án Đà Nẵng 7 -->
        <div class="ux-box-card project-card" data-region="hai-chau">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1acrKuRUxa1ypvTx3RpGkPgB80vIuhAOh&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1acrKuRUxa1ypvTx3RpGkPgB80vIuhAOh';"
              alt="Thi công nội thất căn hộ The Filmore Đà Nẵng phong cách hiện đại"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Thi công nội thất căn hộ The Filmore Đà Nẵng phong cách hiện đại')"
            />
          </div>
          <div class="p-2.5 md:p-3.5">
            <div class="text-[11px] text-[#b5853b] font-semibold mb-1">Quận Hải Châu, TP. Đà Nẵng</div>
            <h3 class="product-title-full">
              Thi công nội thất căn hộ The Filmore Đà Nẵng phong cách hiện đại
            </h3>
          </div>
        </div>

        <!-- Dự án Đà Nẵng 8 -->
        <div class="ux-box-card project-card" data-region="cam-le">
          <div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=13Mhnik-evhl6nsXIUPh83Cp-bPWE3TNK&sz=w800"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13Mhnik-evhl6nsXIUPh83Cp-bPWE3TNK';"
              alt="Hoàn thiện trọn gói nội thất gỗ nhà phố Khuê Trung, Cẩm Lệ, Đà Nẵng"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openLightbox(this.src, 'Hoàn thiện trọn gói nội thất gỗ nhà phố Khuê Trung, Cẩm Lệ, Đà Nẵng')"
            />
          </div>
          <div class="p-2.5 md:p-3.5">
            <div class="text-[11px] text-[#b5853b] font-semibold mb-1">Phường Cẩm Lệ, TP. Đà Nẵng</div>
            <h3 class="product-title-full">
              Hoàn thiện trọn gói nội thất gỗ nhà phố Khuê Trung, Cẩm Lệ, Đà Nẵng
            </h3>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       8. DANH MỤC CÁC ĐỐI TÁC (Partners Section chuẩn Flatsome)
       ======================================================================== -->
  <section id="doi-tac" class="w-full py-8 bg-white border-t border-gray-200">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <h2 class="font-heading text-[16px] md:text-[20px] font-bold uppercase text-[#1f2a37] text-center">
          ĐỐI TÁC VẬT LIỆU & THƯƠNG HIỆU ĐỒNG HÀNH
        </h2>
      </div>
      <p class="text-center text-[12.5px] md:text-[13.5px] text-gray-600 mb-6">
        <strong>BOK DESIGN & BUILD</strong> hợp tác cùng các thương hiệu vật liệu nội thất và phụ kiện hàng đầu
      </p>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
        <div class="border border-gray-200 rounded p-4 text-center bg-[#faf9f6] hover:border-[#b5853b] transition-colors">
          <div class="font-heading font-extrabold text-[15px] text-[#1f2a37]">AN CƯỜNG</div>
          <div class="text-[11.5px] text-gray-500 mt-0.5">Gỗ Công Nghiệp Cao Cấp</div>
        </div>
        <div class="border border-gray-200 rounded p-4 text-center bg-[#faf9f6] hover:border-[#b5853b] transition-colors">
          <div class="font-heading font-extrabold text-[15px] text-[#1f2a37]">HAFELE</div>
          <div class="text-[11.5px] text-gray-500 mt-0.5">Phụ Kiện Nội Thất Đức</div>
        </div>
        <div class="border border-gray-200 rounded p-4 text-center bg-[#faf9f6] hover:border-[#b5853b] transition-colors">
          <div class="font-heading font-extrabold text-[15px] text-[#1f2a37]">BLUM</div>
          <div class="text-[11.5px] text-gray-500 mt-0.5">Bản Lề & Ray Trượt Tủ Bếp</div>
        </div>
        <div class="border border-gray-200 rounded p-4 text-center bg-[#faf9f6] hover:border-[#b5853b] transition-colors">
          <div class="font-heading font-extrabold text-[15px] text-[#1f2a37]">MALLOCA</div>
          <div class="text-[11.5px] text-gray-500 mt-0.5">Thiết Bị Nhà Bếp Đồng Bộ</div>
        </div>
        <div class="border border-gray-200 rounded p-4 text-center bg-[#faf9f6] hover:border-[#b5853b] transition-colors">
          <div class="font-heading font-extrabold text-[15px] text-[#1f2a37]">VICOSTONE</div>
          <div class="text-[11.5px] text-gray-500 mt-0.5">Đá Thạch Anh Nhân Tạo</div>
        </div>
        <div class="border border-gray-200 rounded p-4 text-center bg-[#faf9f6] hover:border-[#b5853b] transition-colors">
          <div class="font-heading font-extrabold text-[15px] text-[#1f2a37]">DULUX / JOTUN</div>
          <div class="text-[11.5px] text-gray-500 mt-0.5">Sơn Nước Hoàn Thiện</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Kinh nghiệm nội thất)
       ======================================================================== -->
  <section id="tin-tuc" class="w-full py-8 bg-[#f7f6f2] border-t border-gray-200">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <h2 class="font-heading text-[16px] md:text-[20px] font-bold uppercase text-[#1f2a37] text-center">
          TIN TỨC & CẨM NANG NỘI THẤT ĐÀ NẴNG
        </h2>
      </div>
      <p class="text-center text-[12.5px] md:text-[13.5px] text-gray-600 mb-6">
        Cập nhật báo giá thi công nội thất và kinh nghiệm thiết kế nhà đẹp từ đội ngũ <strong>bokdesign.vn</strong>
      </p>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">

        <article class="ux-box-card">
          <div class="w-full aspect-[16/10] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf&sz=w700"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf';"
              alt="Báo giá thiết kế thi công nội thất chung cư và nhà phố Đà Nẵng trọn gói 2026"
              class="w-full h-full object-cover"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <h3 class="product-title-full mb-1.5">
                Báo giá thiết kế thi công nội thất chung cư và nhà phố Đà Nẵng trọn gói 2026
              </h3>
              <p class="text-[12px] text-gray-600 hidden sm:block">
                Chi tiết bảng giá thiết kế 3D và thi công hoàn thiện nội thất gỗ MDF chống ẩm tại TP. Đà Nẵng...
              </p>
            </div>
            <a href="#form-bao-gia" class="text-[12px] font-semibold text-[#b5853b] mt-2 inline-block">Xem chi tiết →</a>
          </div>
        </article>

        <article class="ux-box-card">
          <div class="w-full aspect-[16/10] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-&sz=w700"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-';"
              alt="Kinh nghiệm lựa chọn vật liệu tủ bếp bền đẹp phù hợp khí hậu miền Trung"
              class="w-full h-full object-cover"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <h3 class="product-title-full mb-1.5">
                Kinh nghiệm lựa chọn vật liệu tủ bếp bền đẹp phù hợp khí hậu miền Trung
              </h3>
              <p class="text-[12px] text-gray-600 hidden sm:block">
                So sánh ưu nhược điểm của gỗ MDF lõi xanh chống ẩm phủ Melamine, Acrylic và nhựa Picomat...
              </p>
            </div>
            <a href="#form-bao-gia" class="text-[12px] font-semibold text-[#b5853b] mt-2 inline-block">Xem chi tiết →</a>
          </div>
        </article>

        <article class="ux-box-card">
          <div class="w-full aspect-[16/10] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=13Y4ShtC9ywPSib30OYuFlJtpg1ZCfrQw&sz=w700"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13Y4ShtC9ywPSib30OYuFlJtpg1ZCfrQw';"
              alt="Xu hướng thiết kế nội thất nhà phố Đà Nẵng tối ưu công năng và ánh sáng tự nhiên"
              class="w-full h-full object-cover"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <h3 class="product-title-full mb-1.5">
                Xu hướng thiết kế nội thất nhà phố Đà Nẵng tối ưu công năng và ánh sáng tự nhiên
              </h3>
              <p class="text-[12px] text-gray-600 hidden sm:block">
                Giải pháp bố trí mặt bằng phòng khách liền bếp giúp mở rộng không gian sống cho nhà phố ống...
              </p>
            </div>
            <a href="#form-bao-gia" class="text-[12px] font-semibold text-[#b5853b] mt-2 inline-block">Xem chi tiết →</a>
          </div>
        </article>

        <article class="ux-box-card">
          <div class="w-full aspect-[16/10] overflow-hidden bg-gray-100">
            <img
              src="https://drive.google.com/thumbnail?id=18m_uYDlWv5QAk0WOBszwWmSz7LYl0Jn5&sz=w700"
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/18m_uYDlWv5QAk0WOBszwWmSz7LYl0Jn5';"
              alt="Quy trình 6 bước thiết kế và thi công nội thất trọn gói tại BOK Design & Build"
              class="w-full h-full object-cover"
            />
          </div>
          <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <h3 class="product-title-full mb-1.5">
                Quy trình 6 bước thiết kế và thi công nội thất trọn gói tại BOK Design & Build
              </h3>
              <p class="text-[12px] text-gray-600 hidden sm:block">
                Từ khảo sát thực tế, lên bản vẽ 2D/3D, bóc tách dự toán đến sản xuất lắp đặt và bàn giao...
              </p>
            </div>
            <a href="#form-bao-gia" class="text-[12px] font-semibold text-[#b5853b] mt-2 inline-block">Xem chi tiết →</a>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       10. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ + FANPAGE + BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ
       ======================================================================== -->
  <section id="form-bao-gia" class="w-full py-8 bg-white border-t border-gray-200">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <h2 class="font-heading text-[16px] md:text-[20px] font-bold uppercase text-[#1f2a37] text-center">
          ĐĂNG KÝ TƯ VẤN & NHẬN BÁO GIÁ – KẾT NỐI BOK DESIGN
        </h2>
      </div>
      <p class="text-center text-[12.5px] md:text-[13.5px] text-gray-600 mb-6">
        Quý khách để lại thông tin bên dưới hoặc liên hệ trực tiếp <strong>0396 104 869 – 0938 360 746</strong> để nhận dự toán chi tiết
      </p>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">

        <!-- CỘT 1 (5/12): FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ -->
        <div class="lg:col-span-5 bg-[#f7f6f2] p-4 md:p-6 rounded border border-gray-200">
          <h3 class="font-heading font-bold text-[15.5px] text-[#1f2a37] uppercase mb-1">
            FORM YÊU CẦU TƯ VẤN & BÁO GIÁ
          </h3>
          <p class="text-[12px] text-gray-600 mb-4">
            Kỹ sư BOK Design & Build sẽ liên hệ tư vấn và gửi bảng báo giá chi tiết trong vòng 15 phút.
          </p>

          <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
            <div>
              <label class="block text-[12px] font-semibold text-[#1f2a37] mb-1">Họ và tên quý khách *</label>
              <input
                type="text"
                id="q-name"
                required
                placeholder="Nhập họ và tên của bạn"
                class="w-full px-3 py-2 text-[13px] rounded border border-gray-300 bg-white focus:outline-none focus:border-[#b5853b]"
              />
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block text-[12px] font-semibold text-[#1f2a37] mb-1">Số điện thoại / Zalo *</label>
                <input
                  type="tel"
                  id="q-phone"
                  required
                  placeholder="VD: 0905 xxx xxx"
                  class="w-full px-3 py-2 text-[13px] rounded border border-gray-300 bg-white focus:outline-none focus:border-[#b5853b]"
                />
              </div>
              <div>
                <label class="block text-[12px] font-semibold text-[#1f2a37] mb-1">Khu vực công trình</label>
                <input
                  type="text"
                  id="q-address"
                  placeholder="VD: Cẩm Lệ, Đà Nẵng"
                  class="w-full px-3 py-2 text-[13px] rounded border border-gray-300 bg-white focus:outline-none focus:border-[#b5853b]"
                />
              </div>
            </div>

            <div>
              <label class="block text-[12px] font-semibold text-[#1f2a37] mb-1">Hạng mục cần tư vấn & báo giá *</label>
              <select
                id="q-service"
                class="w-full px-3 py-2 text-[13px] rounded border border-gray-300 bg-white focus:outline-none focus:border-[#b5853b]"
              >
                <option value="Thiết kế & Thi công nội thất trọn gói">Thiết kế & Thi công nội thất trọn gói</option>
                <option value="Thi công nội thất Nhà phố">Thi công nội thất Nhà phố</option>
                <option value="Thi công nội thất Căn hộ chung cư">Thi công nội thất Căn hộ chung cư</option>
                <option value="Thi công nội thất Biệt thự, Villa">Thi công nội thất Biệt thự, Villa</option>
                <option value="Thi công Tủ bếp & Nội thất gỗ theo yêu cầu">Thi công Tủ bếp & Nội thất gỗ theo yêu cầu</option>
                <option value="Thi công nội thất Văn phòng / Cửa hàng">Thi công nội thất Văn phòng / Cửa hàng</option>
                <option value="Cải tạo & Hoàn thiện công trình xây dựng">Cải tạo & Hoàn thiện công trình xây dựng</option>
              </select>
            </div>

            <div>
              <label class="block text-[12px] font-semibold text-[#1f2a37] mb-1">Yêu cầu chi tiết (Diện tích, số phòng, ngân sách dự kiến...)</label>
              <textarea
                id="q-note"
                rows="3"
                placeholder="Nhập nhu cầu thiết kế, kích thước hoặc yêu cầu báo giá của quý khách..."
                class="w-full px-3 py-2 text-[13px] rounded border border-gray-300 bg-white focus:outline-none focus:border-[#b5853b]"
              ></textarea>
            </div>

            <button
              type="submit"
              class="w-full py-2.5 px-4 rounded bg-[#b5853b] hover:bg-[#966b28] text-white font-heading font-bold text-[13.5px] uppercase transition-colors"
            >
              GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
            </button>
          </form>

          <!-- Hộp thông báo xác nhận gửi Form (Không dùng alert) -->
          <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-900 text-[12.5px]">
            <strong><i class="fa-solid fa-circle-check mr-1"></i>Đã gửi yêu cầu thành công!</strong>
            <p id="quoteSuccessDetail" class="mt-1"></p>
          </div>
        </div>

        <!-- CỘT 2 (3/12): ĐƯA FANPAGE RA NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-3 bg-white p-4 rounded border border-gray-200 flex flex-col justify-between">
          <div>
            <h3 class="font-heading font-bold text-[14.5px] text-[#1f2a37] uppercase mb-3 flex items-center gap-2">
              <i class="fa-brands fa-facebook text-[#1877F2] text-lg"></i>
              <span>FANPAGE CHÍNH THỨC</span>
            </h3>

            <!-- Khung Fanpage BOK Design & Build trực quan ngay ngoài trang chủ -->
            <div class="border border-gray-200 rounded overflow-hidden bg-[#f7f6f2]">
              <div class="relative h-28 w-full overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf&sz=w600"
                  onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GeYkKLOgE6mLjM-6Ha79qz4Peee2yWQf';"
                  alt="Ảnh bìa Fanpage BOK Design & Build"
                  class="w-full h-full object-cover"
                />
                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/35 to-transparent"></div>
                <div class="absolute bottom-2.5 left-2.5 right-2.5 flex items-center gap-2.5">
                  <img
                    src="https://drive.google.com/thumbnail?id=1n0iuG_1s9D3mTEbh-FaIQcjbiRBicevo&sz=w200"
                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1n0iuG_1s9D3mTEbh-FaIQcjbiRBicevo';"
                    alt="Avatar Fanpage BOK Design"
                    class="w-11 h-11 rounded border-2 border-white bg-white object-contain shrink-0"
                  />
                  <div class="text-white overflow-hidden">
                    <a
                      href="https://www.facebook.com/profile.php?id=61591700077408"
                      target="_blank"
                      rel="noopener noreferrer"
                      class="font-bold text-[13.5px] hover:underline block truncate"
                    >
                      BOK Design & Build
                    </a>
                    <span class="text-[11px] text-gray-200 block">Thiết kế & Thi công Nội thất Đà Nẵng</span>
                  </div>
                </div>
              </div>

              <div class="p-3 space-y-2.5">
                <div class="text-[12px] text-gray-700 space-y-1">
                  <div><i class="fa-solid fa-location-dot text-[#b5853b] mr-1.5"></i>21 Nguyễn Hành, P. Cẩm Lệ, Đà Nẵng</div>
                  <div><i class="fa-solid fa-phone text-[#b5853b] mr-1.5"></i>0396 104 869 – 0938 360 746</div>
                  <div><i class="fa-solid fa-globe text-[#b5853b] mr-1.5"></i>Website: <strong>bokdesign.vn</strong></div>
                </div>

                <!-- Ảnh thực tế mới đăng trên Fanpage -->
                <div class="grid grid-cols-3 gap-1.5 pt-1">
                  <img src="https://drive.google.com/thumbnail?id=1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1exhuumOMYDCjTYV4s3t9VzYYH_VJl-v-';" alt="Ảnh fanpage 1" class="w-full h-14 object-cover rounded" />
                  <img src="https://drive.google.com/thumbnail?id=1TmZhkHrFuChVwR4NCmddR0KBSDCRNO74&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1TmZhkHrFuChVwR4NCmddR0KBSDCRNO74';" alt="Ảnh fanpage 2" class="w-full h-14 object-cover rounded" />
                  <img src="https://drive.google.com/thumbnail?id=1EEodFcV7gBxhAETHP9x7aQNA0QoODj1k&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1EEodFcV7gBxhAETHP9x7aQNA0QoODj1k';" alt="Ảnh fanpage 3" class="w-full h-14 object-cover rounded" />
                </div>

                <div class="grid grid-cols-2 gap-2 pt-1">
                  <a
                    href="https://www.facebook.com/profile.php?id=61591700077408"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="py-2 px-2 rounded bg-[#1877F2] hover:bg-blue-700 text-white text-[11.5px] font-semibold text-center"
                  >
                    <i class="fa-brands fa-facebook mr-1"></i>Theo dõi Trang
                  </a>
                  <a
                    href="https://www.facebook.com/profile.php?id=61591700077408"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="py-2 px-2 rounded bg-white border border-gray-300 hover:border-[#1877F2] text-[#1f2a37] text-[11.5px] font-semibold text-center"
                  >
                    <i class="fa-brands fa-facebook-messenger text-[#1877F2] mr-1"></i>Nhắn tin
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- CỘT 3 (4/12): ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAPS RA NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-4 bg-white p-4 rounded border border-gray-200">
          <h3 class="font-heading font-bold text-[14.5px] text-[#1f2a37] uppercase mb-3 flex items-center gap-2">
            <i class="fa-solid fa-map-location-dot text-[#b5853b] text-lg"></i>
            <span>BẢN ĐỒ GOOGLE MAPS TRỤ SỞ</span>
          </h3>

          <div class="rounded overflow-hidden border border-gray-200 mb-3 bg-gray-100">
            <iframe
              title="Bản đồ Google Map BOK DESIGN & BUILD - 21 Nguyễn Hành, Phường Cẩm Lệ, TP Đà Nẵng"
              src="https://maps.google.com/maps?q=21%20Nguy%E1%BB%85n%20H%C3%A0nh,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              width="100%"
              height="240"
              style="border:0; display:block;"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>

          <div class="bg-[#f7f6f2] p-3 rounded border border-gray-200 flex items-center justify-between gap-2">
            <div class="text-[12px] text-[#1f2a37]">
              <strong>Địa chỉ:</strong> 21 Nguyễn Hành, Phường Cẩm Lệ, TP Đà Nẵng
            </div>
            <a
              href="https://www.google.com/maps/search/?api=1&query=21+Nguyễn+Hành,+Phường+Cẩm+Lệ,+TP+Đà+Nẵng"
              target="_blank"
              rel="noopener noreferrer"
              class="shrink-0 px-3 py-1.5 rounded bg-[#1f2a37] hover:bg-[#b5853b] text-white text-[11.5px] font-semibold transition-colors"
            >
              <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ đường
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       11. FOOTER (Chân trang chuẩn mẫu Nội Thất TVT - bokdesign.vn)
       ======================================================================== -->
  <footer class="w-full bg-[#1f2a37] text-gray-200 pt-10 pb-6 border-t-4 border-[#b5853b]">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">

        <!-- Cột 1: Thông tin công ty -->
        <div class="lg:col-span-5 space-y-3">
          <div class="flex items-center gap-3">
            <div class="w-11 h-11 rounded bg-white p-1 flex items-center justify-center shrink-0">
              <img
                src="https://drive.google.com/thumbnail?id=1n0iuG_1s9D3mTEbh-FaIQcjbiRBicevo&sz=w300"
                onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1n0iuG_1s9D3mTEbh-FaIQcjbiRBicevo';"
                alt="Logo BOK DESIGN & BUILD"
                class="w-full h-full object-contain"
              />
            </div>
            <div>
              <h3 class="font-heading font-bold text-[15px] text-white uppercase">
                CÔNG TY TNHH BOK DESIGN & BUILD
              </h3>
              <p class="text-[12px] text-[#e6be7a] font-semibold">Website: bokdesign.vn | MST: 0402347467</p>
            </div>
          </div>

          <ul class="text-[13px] space-y-2 pt-1 text-gray-300">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-[#b5853b] mt-1 shrink-0"></i>
              <span><strong>Địa chỉ:</strong> 21 Nguyễn Hành, Phường Cẩm Lệ, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone-volume text-[#b5853b] shrink-0"></i>
              <span><strong>Điện thoại / Zalo:</strong> <a href="tel:0396104869" class="text-white font-semibold hover:text-[#e6be7a]">0396 104 869</a> – <a href="tel:0938360746" class="text-white font-semibold hover:text-[#e6be7a]">0938 360 746</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-[#b5853b] shrink-0"></i>
              <span><strong>Website:</strong> <a href="https://bokdesign.vn" class="text-white hover:text-[#e6be7a]">https://bokdesign.vn</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-brands fa-facebook text-[#b5853b] shrink-0"></i>
              <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=61591700077408" target="_blank" rel="noopener noreferrer" class="text-white hover:text-[#e6be7a]">BOK Design & Build</a></span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Dịch vụ chính -->
        <div class="lg:col-span-4 space-y-2.5">
          <h4 class="font-heading font-bold text-[14px] text-white uppercase border-b border-white/15 pb-2">
            DỊCH VỤ THIẾT KẾ & THI CÔNG
          </h4>
          <ul class="text-[13px] space-y-2 text-gray-300">
            <li><a href="#san-pham-thuc-te" class="hover:text-[#e6be7a] transition-colors">• Thi công nội thất chung cư Đà Nẵng</a></li>
            <li><a href="#san-pham-thuc-te" class="hover:text-[#e6be7a] transition-colors">• Thi công nội thất nhà phố trọn gói</a></li>
            <li><a href="#san-pham-thuc-te" class="hover:text-[#e6be7a] transition-colors">• Thiết kế & Thi công nội thất biệt thự, villa</a></li>
            <li><a href="#san-pham-thuc-te" class="hover:text-[#e6be7a] transition-colors">• Thiết kế & Thi công nội thất văn phòng, cửa hàng</a></li>
            <li><a href="#san-pham-thuc-te" class="hover:text-[#e6be7a] transition-colors">• Sản xuất lắp đặt tủ bếp, giường, tủ áo theo yêu cầu</a></li>
          </ul>
        </div>

        <!-- Cột 3: Chính sách khách hàng -->
        <div class="lg:col-span-3 space-y-2.5">
          <h4 class="font-heading font-bold text-[14px] text-white uppercase border-b border-white/15 pb-2">
            CHÍNH SÁCH & CAM KẾT
          </h4>
          <ul class="text-[13px] space-y-2 text-gray-300">
            <li><a href="#form-bao-gia" class="hover:text-[#e6be7a] transition-colors">• Chính sách khảo sát & báo giá</a></li>
            <li><a href="#form-bao-gia" class="hover:text-[#e6be7a] transition-colors">• Chính sách vận chuyển & lắp đặt</a></li>
            <li><a href="#form-bao-gia" class="hover:text-[#e6be7a] transition-colors">• Chính sách bảo hành & bảo trì</a></li>
            <li><a href="#form-bao-gia" class="hover:text-[#e6be7a] transition-colors">• Cam kết vật liệu đúng hợp đồng</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-[12px] text-gray-400">
        <div>Copyright 2026 © <strong>bokdesign.vn</strong> – CÔNG TY TNHH BOK DESIGN & BUILD.</div>
        <div>Địa chỉ: 21 Nguyễn Hành, Phường Cẩm Lệ, TP Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- ========================================================================
       12. CÁC NÚT LIÊN HỆ NỔI BẬT (Zalo, Facebook, Hotline)
           Tương thích hoàn hảo trên cả máy tính và điện thoại, không tràn viền
       ======================================================================== -->
  <div class="floating-contact-wrap" aria-label="Nút liên hệ nhanh">
    
    <!-- Nút Zalo nổi bật -->
    <a
      href="https://zalo.me/0396104869"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2 bg-[#0068ff] hover:bg-[#0052cc] text-white px-3 py-2 rounded-full shadow-lg transition-transform hover:scale-105"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-[12px] font-semibold whitespace-nowrap pr-1">Chat Zalo: 0396.104.869</span>
    </a>

    <!-- Nút Facebook Fanpage nổi bật -->
    <a
      href="https://www.facebook.com/profile.php?id=61591700077408"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition-transform hover:scale-105"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="text-[12px] font-semibold whitespace-nowrap pr-1">Fanpage BOK Design</span>
    </a>

    <!-- Nút Hotline 1 -->
    <a
      href="tel:0396104869"
      class="btn-floating-pulse flex items-center gap-2 bg-[#b5853b] hover:bg-[#966b28] text-white px-3 py-2 rounded-full shadow-lg transition-transform hover:scale-105"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#b5853b] flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone text-xs"></i>
      </span>
      <span class="text-[12px] font-bold whitespace-nowrap pr-1">0396 104 869</span>
    </a>

    <!-- Nút Hotline 2 -->
    <a
      href="tel:0938360746"
      class="flex items-center gap-2 bg-[#1f2a37] hover:bg-black text-white px-3 py-2 rounded-full shadow-lg transition-transform hover:scale-105"
    >
      <span class="w-6 h-6 rounded-full bg-[#b5853b] text-white flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-[12px] font-bold whitespace-nowrap pr-1">0938 360 746</span>
    </a>

  </div>

  <!-- ========================================================================
       13. MODAL XEM ẢNH THỰC TẾ RÕ NÉT (Lightbox)
       ======================================================================== -->
  <div
    id="imageLightbox"
    class="fixed inset-0 bg-black/85 z-[100] hidden items-center justify-center p-4"
    onclick="closeLightbox()"
  >
    <div class="relative max-w-4xl w-full bg-white rounded overflow-hidden shadow-2xl" onclick="event.stopPropagation()">
      <div class="flex items-center justify-between px-4 py-2.5 bg-[#1f2a37] text-white">
        <span id="lightboxCaption" class="text-[13px] font-semibold">Hình ảnh thực tế BOK Design & Build</span>
        <button type="button" onclick="closeLightbox()" class="text-white hover:text-[#e6be7a] text-lg px-2">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-2 bg-black flex items-center justify-center">
        <img id="lightboxImg" src="" alt="Xem ảnh lớn" class="max-h-[78vh] w-auto object-contain" />
      </div>
    </div>
  </div>

  <!-- ========================================================================
       JAVASCRIPT ĐIỀU KHIỂN SLIDER TỰ TRƯỢT, LỌC DANH MỤC & FORM BÁO GIÁ
       ======================================================================== -->
  <script>
    // 1. Điều khiển 2 ảnh Banner tự trượt (Đồng bộ cả bản Máy tính & Điện thoại)
    let currentBannerIndex = 0;
    const totalBanners = 2;
    let bannerTimer = null;

    function renderBannerSlide(index) {
      const desktopSlides = document.querySelectorAll('.desktop-slide');
      const mobileSlides = document.querySelectorAll('.mobile-slide');
      const dot0 = document.getElementById('dot-0');
      const dot1 = document.getElementById('dot-1');

      desktopSlides.forEach((slide, i) => {
        slide.classList.toggle('active', i === index);
      });

      mobileSlides.forEach((slide, i) => {
        slide.classList.toggle('active', i === index);
      });

      if (dot0 && dot1) {
        dot0.className = index === 0 ? 'w-6 h-2 rounded-full bg-[#b5853b] transition-all' : 'w-2.5 h-2 rounded-full bg-gray-300 transition-all';
        dot1.className = index === 1 ? 'w-6 h-2 rounded-full bg-[#b5853b] transition-all' : 'w-2.5 h-2 rounded-full bg-gray-300 transition-all';
      }
    }

    function changeSlide(step) {
      currentBannerIndex = (currentBannerIndex + step + totalBanners) % totalBanners;
      renderBannerSlide(currentBannerIndex);
      resetBannerInterval();
    }

    function setSlide(index) {
      currentBannerIndex = index;
      renderBannerSlide(currentBannerIndex);
      resetBannerInterval();
    }

    function resetBannerInterval() {
      if (bannerTimer) clearInterval(bannerTimer);
      bannerTimer = setInterval(() => {
        currentBannerIndex = (currentBannerIndex + 1) % totalBanners;
        renderBannerSlide(currentBannerIndex);
      }, 4500);
    }

    // 2. Đóng/mở Menu trên điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobile-nav-drawer');
      const icon = document.getElementById('mobile-menu-icon');
      if (!drawer) return;
      drawer.classList.toggle('hidden');
      if (icon) {
        icon.className = drawer.classList.contains('hidden') ? 'fa-solid fa-bars text-lg' : 'fa-solid fa-xmark text-lg';
      }
    }

    // 3. Lọc danh mục sản phẩm thực tế
    function filterProducts(category) {
      const items = document.querySelectorAll('.product-item');
      items.forEach((item) => {
        const cats = item.getAttribute('data-category') || '';
        if (category === 'all' || cats.includes(category)) {
          item.style.display = 'flex';
        } else {
          item.style.display = 'none';
        }
      });
    }

    // 4. Lọc danh mục dự án tại Đà Nẵng
    function filterProjects(region, btnElement) {
      const cards = document.querySelectorAll('.project-card');
      cards.forEach((card) => {
        const cardRegion = card.getAttribute('data-region') || '';
        if (region === 'all' || cardRegion === region) {
          card.style.display = 'flex';
        } else {
          card.style.display = 'none';
        }
      });

      const buttons = document.querySelectorAll('.project-filter-btn');
      buttons.forEach((btn) => btn.classList.remove('active'));
      if (btnElement) btnElement.classList.add('active');
    }

    // 5. Xử lý gửi Form Yêu cầu & Báo giá
    function submitQuoteForm(event) {
      event.preventDefault();
      const name = document.getElementById('q-name').value.trim();
      const phone = document.getElementById('q-phone').value.trim();
      const address = document.getElementById('q-address').value.trim() || 'Đà Nẵng';
      const service = document.getElementById('q-service').value;

      const box = document.getElementById('quoteSuccessBox');
      const detail = document.getElementById('quoteSuccessDetail');

      if (box && detail) {
        detail.textContent = `Cảm ơn ${name} (${phone}) tại ${address}. Bộ phận báo giá BOK DESIGN & BUILD đã tiếp nhận yêu cầu "${service}" và sẽ liên hệ lại ngay qua số 0396 104 869 – 0938 360 746.`;
        box.classList.remove('hidden');
        document.getElementById('quoteForm').reset();
      }
    }

    // 6. Xem ảnh lớn Lightbox
    function openLightbox(src, caption) {
      const modal = document.getElementById('imageLightbox');
      const img = document.getElementById('lightboxImg');
      const cap = document.getElementById('lightboxCaption');
      if (modal && img && cap) {
        img.src = src;
        cap.textContent = caption;
        modal.classList.remove('hidden');
        modal.classList.add('flex');
      }
    }

    function closeLightbox() {
      const modal = document.getElementById('imageLightbox');
      if (modal) {
        modal.classList.add('hidden');
        modal.classList.remove('flex');
      }
    }

    window.onload = function () {
      resetBannerInterval();
    };
  </script>
</body>
</html>
