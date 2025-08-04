# lavisha-electrical<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lavisha - Jasa Listrik Profesional</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .service-card:hover { transform: translateY(-5px); transition: all 0.3s ease; }
        .floating { animation: float 3s ease-in-out infinite; }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        .logo-glow {
            filter: drop-shadow(0 0 8px rgba(59, 130, 246, 0.3));
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <!-- Lavisha Logo -->
                        <div class="logo-glow mr-3">
                            <svg width="40" height="40" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                                <!-- Outer Circle -->
                                <circle cx="50" cy="50" r="48" fill="url(#logoGradient)" stroke="#1e40af" stroke-width="2"/>
                                
                                <!-- Lightning Bolt -->
                                <path d="M35 25 L55 25 L45 45 L60 45 L40 75 L50 50 L35 50 Z" 
                                      fill="#fbbf24" stroke="#f59e0b" stroke-width="1.5" stroke-linejoin="round"/>
                                
                                <!-- Circuit Lines -->
                                <g stroke="#60a5fa" stroke-width="2" fill="none">
                                    <path d="M20 35 L30 35 M70 35 L80 35"/>
                                    <path d="M20 65 L30 65 M70 65 L80 65"/>
                                    <circle cx="25" cy="35" r="2" fill="#60a5fa"/>
                                    <circle cx="75" cy="35" r="2" fill="#60a5fa"/>
                                    <circle cx="25" cy="65" r="2" fill="#60a5fa"/>
                                    <circle cx="75" cy="65" r="2" fill="#60a5fa"/>
                                </g>
                                
                                <!-- Gradient Definition -->
                                <defs>
                                    <linearGradient id="logoGradient" x1="0%" y1="0%" x2="100%" y2="100%">
                                        <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:1" />
                                        <stop offset="100%" style="stop-color:#1e40af;stop-opacity:1" />
                                    </linearGradient>
                                </defs>
                            </svg>
                        </div>
                        <h1 class="text-2xl font-bold text-blue-600">LAVISHA</h1>
                    </div>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-4">
                        <a href="#home" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">Beranda</a>
                        <a href="#services" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">Layanan</a>
                        <a href="#about" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">Tentang</a>
                        <a href="#contact" class="bg-blue-600 text-white px-4 py-2 rounded-md text-sm font-medium hover:bg-blue-700 transition-colors">Kontak</a>
                    </div>
                </div>
                <div class="md:hidden">
                    <button id="mobile-menu-btn" class="text-gray-700 hover:text-blue-600">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="md:hidden hidden bg-white border-t">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#home" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Beranda</a>
                <a href="#services" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Layanan</a>
                <a href="#about" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Tentang</a>
                <a href="#contact" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Kontak</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg pt-20 pb-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center">
                <div class="floating mb-8">
                    <div class="inline-block p-6 bg-white rounded-full shadow-2xl">
                        <!-- Large Hero Logo -->
                        <svg width="120" height="120" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                            <!-- Outer Circle -->
                            <circle cx="50" cy="50" r="48" fill="url(#heroLogoGradient)" stroke="#1e40af" stroke-width="2"/>
                            
                            <!-- Lightning Bolt -->
                            <path d="M35 25 L55 25 L45 45 L60 45 L40 75 L50 50 L35 50 Z" 
                                  fill="#fbbf24" stroke="#f59e0b" stroke-width="1.5" stroke-linejoin="round"/>
                            
                            <!-- Circuit Lines -->
                            <g stroke="#60a5fa" stroke-width="2" fill="none">
                                <path d="M20 35 L30 35 M70 35 L80 35"/>
                                <path d="M20 65 L30 65 M70 65 L80 65"/>
                                <circle cx="25" cy="35" r="2" fill="#60a5fa"/>
                                <circle cx="75" cy="35" r="2" fill="#60a5fa"/>
                                <circle cx="25" cy="65" r="2" fill="#60a5fa"/>
                                <circle cx="75" cy="65" r="2" fill="#60a5fa"/>
                            </g>
                            
                            <!-- Gradient Definition -->
                            <defs>
                                <linearGradient id="heroLogoGradient" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:1" />
                                    <stop offset="100%" style="stop-color:#1e40af;stop-opacity:1" />
                                </linearGradient>
                            </defs>
                        </svg>
                    </div>
                </div>
                <h1 class="text-4xl md:text-6xl font-bold text-white mb-6">
                    LAVISHA
                    <span class="block text-2xl md:text-3xl font-normal mt-2">Jasa Listrik Profesional</span>
                </h1>
                <p class="text-xl text-white mb-8 max-w-3xl mx-auto">
                    Solusi terpercaya untuk semua kebutuhan instalasi listrik rumah dan bisnis Anda. 
                    Berpengalaman, berlisensi, dan siap melayani 24/7.
                </p>
                <div class="space-x-4">
                    <a href="https://wa.me/6289636368627?text=Halo%20Lavisha!%0D%0A%0D%0ASaya%20tertarik%20untuk%20konsultasi%20gratis%20mengenai%20kebutuhan%20listrik%20saya.%0D%0A%0D%0ADetail%20kebutuhan:%0D%0A-%0D%0A-%0D%0A-%0D%0A%0D%0ATerima%20kasih!" target="_blank" class="bg-white text-blue-600 px-8 py-3 rounded-lg font-semibold hover:bg-gray-100 transition-colors inline-block">
                        Konsultasi Gratis
                    </a>
                    <a href="#services" class="border-2 border-white text-white px-8 py-3 rounded-lg font-semibold hover:bg-white hover:text-blue-600 transition-colors inline-block">
                        Lihat Layanan
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Layanan Kami</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">
                    Kami menyediakan berbagai layanan listrik profesional untuk memenuhi kebutuhan Anda
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="service-card bg-gray-50 p-6 rounded-xl shadow-md">
                    <div class="text-blue-600 mb-4">
                        <svg class="w-12 h-12" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M3 4a1 1 0 011-1h12a1 1 0 011 1v2a1 1 0 01-1 1H4a1 1 0 01-1-1V4zM3 10a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H4a1 1 0 01-1-1v-6zM14 9a1 1 0 00-1 1v6a1 1 0 001 1h2a1 1 0 001-1v-6a1 1 0 00-1-1h-2z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">Instalasi Listrik Rumah</h3>
                    <p class="text-gray-600 mb-4">Pemasangan instalasi listrik baru untuk rumah tinggal dengan standar SNI dan keamanan terjamin.</p>
                    <ul class="text-sm text-gray-500 space-y-1">
                        <li>• Pemasangan kabel dan saklar</li>
                        <li>• Instalasi stop kontak</li>
                        <li>• Pemasangan lampu</li>
                    </ul>
                </div>

                <!-- Service 2 -->
                <div class="service-card bg-gray-50 p-6 rounded-xl shadow-md">
                    <div class="text-blue-600 mb-4">
                        <svg class="w-12 h-12" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M11.49 3.17c-.38-1.56-2.6-1.56-2.98 0a1.532 1.532 0 01-2.286.948c-1.372-.836-2.942.734-2.106 2.106.54.886.061 2.042-.947 2.287-1.561.379-1.561 2.6 0 2.978a1.532 1.532 0 01.947 2.287c-.836 1.372.734 2.942 2.106 2.106a1.532 1.532 0 012.287.947c.379 1.561 2.6 1.561 2.978 0a1.533 1.533 0 012.287-.947c1.372.836 2.942-.734 2.106-2.106a1.533 1.533 0 01.947-2.287c1.561-.379 1.561-2.6 0-2.978a1.532 1.532 0 01-.947-2.287c.836-1.372-.734-2.942-2.106-2.106a1.532 1.532 0 01-2.287-.947zM10 13a3 3 0 100-6 3 3 0 000 6z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">Perbaikan & Maintenance</h3>
                    <p class="text-gray-600 mb-4">Layanan perbaikan dan perawatan sistem listrik untuk menjaga performa optimal.</p>
                    <ul class="text-sm text-gray-500 space-y-1">
                        <li>• Troubleshooting masalah listrik</li>
                        <li>• Penggantian komponen rusak</li>
                        <li>• Maintenance berkala</li>
                    </ul>
                </div>

                <!-- Service 3 -->
                <div class="service-card bg-gray-50 p-6 rounded-xl shadow-md">
                    <div class="text-blue-600 mb-4">
                        <svg class="w-12 h-12" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">Upgrade Panel Listrik</h3>
                    <p class="text-gray-600 mb-4">Peningkatan kapasitas dan modernisasi panel listrik untuk kebutuhan yang lebih besar.</p>
                    <ul class="text-sm text-gray-500 space-y-1">
                        <li>• Upgrade MCB dan panel</li>
                        <li>• Penambahan daya listrik</li>
                        <li>• Instalasi grounding</li>
                    </ul>
                </div>

                <!-- Service 4 -->
                <div class="service-card bg-gray-50 p-6 rounded-xl shadow-md">
                    <div class="text-blue-600 mb-4">
                        <svg class="w-12 h-12" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">Listrik Komersial</h3>
                    <p class="text-gray-600 mb-4">Solusi instalasi listrik untuk bangunan komersial, kantor, dan industri.</p>
                    <ul class="text-sm text-gray-500 space-y-1">
                        <li>• Instalasi gedung perkantoran</li>
                        <li>• Sistem pencahayaan komersial</li>
                        <li>• Instalasi mesin industri</li>
                    </ul>
                </div>

                <!-- Service 5 -->
                <div class="service-card bg-gray-50 p-6 rounded-xl shadow-md">
                    <div class="text-blue-600 mb-4">
                        <svg class="w-12 h-12" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">Layanan Darurat 24/7</h3>
                    <p class="text-gray-600 mb-4">Siap melayani panggilan darurat listrik kapan saja, 24 jam sehari 7 hari seminggu.</p>
                    <ul class="text-sm text-gray-500 space-y-1">
                        <li>• Respons cepat dalam 1 jam</li>
                        <li>• Teknisi berpengalaman</li>
                        <li>• Peralatan lengkap</li>
                    </ul>
                </div>

                <!-- Service 6 -->
                <div class="service-card bg-gray-50 p-6 rounded-xl shadow-md">
                    <div class="text-blue-600 mb-4">
                        <svg class="w-12 h-12" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M3 4a1 1 0 011-1h12a1 1 0 011 1v2a1 1 0 01-1 1H4a1 1 0 01-1-1V4zM3 10a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H4a1 1 0 01-1-1v-6zM14 9a1 1 0 00-1 1v6a1 1 0 001 1h2a1 1 0 001-1v-6a1 1 0 00-1-1h-2z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">Smart Home Installation</h3>
                    <p class="text-gray-600 mb-4">Instalasi sistem rumah pintar dengan teknologi terkini untuk kenyamanan maksimal.</p>
                    <ul class="text-sm text-gray-500 space-y-1">
                        <li>• Smart switch dan dimmer</li>
                        <li>• Sistem otomasi rumah</li>
                        <li>• Integrasi IoT devices</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">Mengapa Memilih Lavisha?</h2>
                    <p class="text-lg text-gray-600 mb-8">
                        Dengan pengalaman lebih dari 10 tahun di bidang instalasi listrik, Lavisha telah menjadi pilihan utama 
                        untuk kebutuhan listrik rumah dan bisnis di seluruh Indonesia.
                    </p>
                    
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 w-6 h-6 bg-blue-600 rounded-full flex items-center justify-center mt-1">
                                <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/>
                                </svg>
                            </div>
                            <div class="ml-4">
                                <h3 class="text-lg font-semibold text-gray-900">Teknisi Berlisensi & Berpengalaman</h3>
                                <p class="text-gray-600">Tim teknisi profesional dengan sertifikasi resmi dan pengalaman bertahun-tahun.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 w-6 h-6 bg-blue-600 rounded-full flex items-center justify-center mt-1">
                                <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/>
                                </svg>
                            </div>
                            <div class="ml-4">
                                <h3 class="text-lg font-semibold text-gray-900">Garansi Pekerjaan</h3>
                                <p class="text-gray-600">Semua pekerjaan dilengkapi dengan garansi untuk memberikan ketenangan pikiran.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 w-6 h-6 bg-blue-600 rounded-full flex items-center justify-center mt-1">
                                <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/>
                                </svg>
                            </div>
                            <div class="ml-4">
                                <h3 class="text-lg font-semibold text-gray-900">Harga Transparan</h3>
                                <p class="text-gray-600">Estimasi biaya yang jelas dan transparan tanpa biaya tersembunyi.</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="relative">
                    <div class="bg-blue-600 rounded-2xl p-8 text-white">
                        <div class="grid grid-cols-2 gap-6">
                            <div class="text-center">
                                <div class="text-3xl font-bold mb-2">1000+</div>
                                <div class="text-blue-100">Proyek Selesai</div>
                            </div>
                            <div class="text-center">
                                <div class="text-3xl font-bold mb-2">10+</div>
                                <div class="text-blue-100">Tahun Pengalaman</div>
                            </div>
                            <div class="text-center">
                                <div class="text-3xl font-bold mb-2">24/7</div>
                                <div class="text-blue-100">Layanan Darurat</div>
                            </div>
                            <div class="text-center">
                                <div class="text-3xl font-bold mb-2">100%</div>
                                <div class="text-blue-100">Kepuasan Pelanggan</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Hubungi Kami</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">
                    Siap membantu kebutuhan listrik Anda. Konsultasi gratis dan estimasi biaya tanpa komitmen.
                </p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <!-- Contact Info -->
                <div class="space-y-8">
                    <div class="flex items-start">
                        <div class="flex-shrink-0 w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center">
                            <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                            </svg>
                        </div>
                        <div class="ml-4">
                            <h3 class="text-lg font-semibold text-gray-900">Telepon</h3>
                            <p class="text-gray-600">62 8963636-8627</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="flex-shrink-0 w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center">
                            <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                            </svg>
                        </div>
                        <div class="ml-4">
                            <h3 class="text-lg font-semibold text-gray-900">Email</h3>
                            <p class="text-gray-600">totohermanto.everest3@gmail.com</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="flex-shrink-0 w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center">
                            <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                            </svg>
                        </div>
                        <div class="ml-4">
                            <h3 class="text-lg font-semibold text-gray-900">Alamat</h3>
                            <p class="text-gray-600">Jl. Bhakti RT004/006<br>Kel. Sudimara Pinang, Kec. Pinang</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="flex-shrink-0 w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center">
                            <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
                            </svg>
                        </div>
                        <div class="ml-4">
                            <h3 class="text-lg font-semibold text-gray-900">Jam Operasional</h3>
                            <p class="text-gray-600">Senin - Jumat: 08:00 - 17:00</p>
                            <p class="text-gray-600">Sabtu: 08:00 - 15:00</p>
                            <p class="text-red-600 font-medium">Darurat: 24/7</p>
                        </div>
                    </div>
                </div>
                
                <!-- Contact Form -->
                <div class="bg-gray-50 p-8 rounded-xl">
                    <h3 class="text-xl font-semibold text-gray-900 mb-6">Minta Penawaran</h3>
                    <form id="contact-form" class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-2">Nama Lengkap</label>
                            <input type="text" id="name" name="name" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-600 focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="phone" class="block text-sm font-medium text-gray-700 mb-2">Nomor Telepon</label>
                            <input type="tel" id="phone" name="phone" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-600 focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="service" class="block text-sm font-medium text-gray-700 mb-2">Jenis Layanan</label>
                            <select id="service" name="service" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-600 focus:border-transparent">
                                <option value="">Pilih layanan...</option>
                                <option value="Instalasi Listrik Rumah">Instalasi Listrik Rumah</option>
                                <option value="Perbaikan & Maintenance">Perbaikan & Maintenance</option>
                                <option value="Upgrade Panel Listrik">Upgrade Panel Listrik</option>
                                <option value="Listrik Komersial">Listrik Komersial</option>
                                <option value="Layanan Darurat">Layanan Darurat</option>
                                <option value="Smart Home Installation">Smart Home Installation</option>
                            </select>
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-2">Deskripsi Kebutuhan</label>
                            <textarea id="message" name="message" rows="4" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-600 focus:border-transparent" placeholder="Jelaskan kebutuhan listrik Anda..."></textarea>
                        </div>
                        
                        <button type="submit" class="w-full bg-green-600 text-white py-3 px-6 rounded-lg font-semibold hover:bg-green-700 transition-colors flex items-center justify-center">
                            <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.885 3.700"/>
                            </svg>
                            Kirim ke WhatsApp
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- WhatsApp Float Button -->
    <div class="fixed bottom-6 right-6 z-50">
        <a href="https://wa.me/6289636368627?text=Halo%20Lavisha!%0D%0A%0D%0ASaya%20tertarik%20dengan%20layanan%20listrik%20Anda.%20Mohon%20informasi%20lebih%20lanjut.%0D%0A%0D%0ATerima%20kasih!" 
           target="_blank" 
           class="bg-green-500 hover:bg-green-600 text-white w-16 h-16 rounded-full shadow-lg transition-all duration-300 hover:scale-110 flex items-center justify-center">
            <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24">
                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.885 3.700"/>
            </svg>
        </a>
    </div>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div class="col-span-1 md:col-span-2">
                    <div class="flex items-center mb-4">
                        <!-- Footer Logo -->
                        <div class="mr-3">
                            <svg width="32" height="32" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                                <!-- Outer Circle -->
                                <circle cx="50" cy="50" r="48" fill="url(#footerLogoGradient)" stroke="#60a5fa" stroke-width="2"/>
                                
                                <!-- Lightning Bolt -->
                                <path d="M35 25 L55 25 L45 45 L60 45 L40 75 L50 50 L35 50 Z" 
                                      fill="#fbbf24" stroke="#f59e0b" stroke-width="1.5" stroke-linejoin="round"/>
                                
                                <!-- Circuit Lines -->
                                <g stroke="#60a5fa" stroke-width="2" fill="none">
                                    <path d="M20 35 L30 35 M70 35 L80 35"/>
                                    <path d="M20 65 L30 65 M70 65 L80 65"/>
                                    <circle cx="25" cy="35" r="2" fill="#60a5fa"/>
                                    <circle cx="75" cy="35" r="2" fill="#60a5fa"/>
                                    <circle cx="25" cy="65" r="2" fill="#60a5fa"/>
                                    <circle cx="75" cy="65" r="2" fill="#60a5fa"/>
                                </g>
                                
                                <!-- Gradient Definition -->
                                <defs>
                                    <linearGradient id="footerLogoGradient" x1="0%" y1="0%" x2="100%" y2="100%">
                                        <stop offset="0%" style="stop-color:#60a5fa;stop-opacity:1" />
                                        <stop offset="100%" style="stop-color:#3b82f6;stop-opacity:1" />
                                    </linearGradient>
                                </defs>
                            </svg>
                        </div>
                        <h3 class="text-2xl font-bold">LAVISHA</h3>
                    </div>
                    <p class="text-gray-300 mb-4">
                        Solusi terpercaya untuk semua kebutuhan instalasi listrik rumah dan bisnis Anda. 
                        Melayani dengan profesional dan berkualitas sejak 2014.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-300 hover:text-white transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                            </svg>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-white transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M22.46 6c-.77.35-1.6.58-2.46.69.88-.53 1.56-1.37 1.88-2.38-.83.5-1.75.85-2.72 1.05C18.37 4.5 17.26 4 16 4c-2.35 0-4.27 1.92-4.27 4.29 0 .34.04.67.11.98C8.28 9.09 5.11 7.38 3 4.79c-.37.63-.58 1.37-.58 2.15 0 1.49.75 2.81 1.91 3.56-.71 0-1.37-.2-1.95-.5v.03c0 2.08 1.48 3.82 3.44 4.21a4.22 4.22 0 0 1-1.93.07 4.28 4.28 0 0 0 4 2.98 8.521 8.521 0 0 1-5.33 1.84c-.34 0-.68-.02-1.02-.06C3.44 20.29 5.7 21 8.12 21 16 21 20.33 14.46 20.33 8.79c0-.19 0-.37-.01-.56.84-.6 1.56-1.36 2.14-2.23z"/>
                            </svg>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-white transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12.017 0C5.396 0 .029 5.367.029 11.987c0 5.079 3.158 9.417 7.618 11.174-.105-.949-.199-2.403.041-3.439.219-.937 1.406-5.957 1.406-5.957s-.359-.72-.359-1.781c0-1.663.967-2.911 2.168-2.911 1.024 0 1.518.769 1.518 1.688 0 1.029-.653 2.567-.992 3.992-.285 1.193.6 2.165 1.775 2.165 2.128 0 3.768-2.245 3.768-5.487 0-2.861-2.063-4.869-5.008-4.869-3.41 0-5.409 2.562-5.409 5.199 0 1.033.394 2.143.889 2.741.099.12.112.225.085.345-.09.375-.293 1.199-.334 1.363-.053.225-.172.271-.402.165-1.495-.69-2.433-2.878-2.433-4.646 0-3.776 2.748-7.252 7.92-7.252 4.158 0 7.392 2.967 7.392 6.923 0 4.135-2.607 7.462-6.233 7.462-1.214 0-2.357-.629-2.75-1.378l-.748 2.853c-.271 1.043-1.002 2.35-1.492 3.146C9.57 23.812 10.763 24.009 12.017 24.009c6.624 0 11.99-5.367 11.99-11.988C24.007 5.367 18.641.001.012.001z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Layanan</h4>
                    <ul class="space-y-2 text-gray-300">
                        <li><a href="#" class="hover:text-white transition-colors">Instalasi Rumah</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Perbaikan Listrik</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Upgrade Panel</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Listrik Komersial</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Smart Home</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Kontak</h4>
                    <ul class="space-y-2 text-gray-300">
                        <li>62 8963636-8627</li>
                        <li>totohermanto.everest3@gmail.com</li>
                        <li>Jl. Bhakti RT004/006<br>Kel. Sudimara Pinang, Kec. Pinang</li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-300">
                <p>&copy; 2024 Lavisha. Semua hak dilindungi undang-undang.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    // Close mobile menu if open
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        // Contact form submission
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form data
            const formData = new FormData(this);
            const name = formData.get('name');
            const phone = formData.get('phone');
            const service = formData.get('service');
            const message = formData.get('message');
            
            // Create WhatsApp message
            const whatsappMessage = `Halo Lavisha!%0D%0A%0D%0ASaya ingin menggunakan jasa listrik Anda:%0D%0A%0D%0ANama: ${name}%0D%0ATelepon: ${phone}%0D%0ALayanan: ${service}%0D%0AKebutuhan: ${message}%0D%0A%0D%0AMohon informasi lebih lanjut. Terima kasih!`;
            
            // Open WhatsApp
            window.open(`https://wa.me/6289636368627?text=${whatsappMessage}`, '_blank');
            
            // Reset form
            this.reset();
        });

        // Add scroll effect to navbar
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('nav');
            if (window.scrollY > 50) {
                navbar.classList.add('shadow-lg');
            } else {
                navbar.classList.remove('shadow-lg');
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'96a0ef0393e15844',t:'MTc1NDM0MDY5Ni4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
