<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>খাজা আজমীর কম্পিউটার | ডিজিটাল স্মার্ট সেবা কেন্দ্র</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { font-family: 'Hind Siliguri', sans-serif; background: #f8fafc; }
        .hero-gradient { background: linear-gradient(135deg, #004d33 0%, #006a4e 100%); }
        .glass-effect { background: rgba(255, 255, 255, 0.95); backdrop-filter: blur(10px); }
        .service-card { transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275); cursor: pointer; border: 1px solid #e2e8f0; }
        .service-card:hover { transform: translateY(-10px); box-shadow: 0 20px 25px -5px rgba(0, 106, 78, 0.2); border-color: #006a4e; }
        .premium-border { border-top: 5px solid #f47920; }
        @keyframes pulse-custom { 0% { transform: scale(1); } 50% { transform: scale(1.05); } 100% { transform: scale(1); } }
        .animate-premium { animation: pulse-custom 2s infinite; }
    </style>
</head>
<body class="pb-32">

    <header class="hero-gradient text-white pt-12 pb-20 px-4 text-center relative overflow-hidden">
        <div class="absolute top-0 left-0 w-full h-full opacity-10 pointer-events-none">
            <i class="fas fa-microchip text-[200px] absolute -top-10 -left-10"></i>
            <i class="fas fa-globe text-[150px] absolute -bottom-10 -right-10"></i>
        </div>

        <div class="relative z-10">
            <div class="bg-white/20 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4 border-2 border-yellow-400 animate-premium">
                <i class="fas fa-laptop-code text-4xl text-yellow-300"></i>
            </div>
            <h1 class="text-4xl md:text-6xl font-black mb-2 tracking-tighter uppercase">খাজা আজমীর কম্পিউটার</h1>
            <div class="h-1.5 w-40 bg-gradient-to-r from-transparent via-yellow-400 to-transparent mx-auto mb-4 rounded-full"></div>
            <p class="text-xl md:text-2xl font-semibold text-yellow-100">ডিজিটাল ভূমি ও স্মার্ট অনলাইন সার্ভিস পোর্টাল</p>
            <div class="mt-6 inline-block glass-effect px-8 py-2 rounded-2xl border border-white/30 text-green-900 font-bold shadow-xl">
                <i class="fas fa-user-check mr-2"></i> অনার: মোঃ শহীদুল আলম সৌরভ
            </div>
        </div>
    </header>

    <div class="bg-white border-b border-gray-200 py-3 shadow-sm">
        <div class="container mx-auto px-4 flex items-center">
            <span class="bg-red-600 text-white text-[10px] font-bold px-3 py-1 rounded-full mr-3 animate-pulse uppercase">জরুরি:</span>
            <marquee class="text-gray-700 font-bold text-sm">
                আসসালামু আলাইকুম, খাজা আজমীর কম্পিউটারে আপনাকে স্বাগতম! এখানে ভূমি উন্নয়ন কর (খাজনা), নামজারি, এনআইডি সংশোধন, জন্ম নিবন্ধন, ই-পাসপোর্ট এবং সকল সিমে মোবাইল রিচার্জের শতভাগ বিশ্বস্ত সেবা প্রদান করা হয়। যোগাযোগ: 01806730271
            </marquee>
        </div>
    </div>

    <main class="container mx-auto px-4 -mt-10 relative z-20">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4 md:gap-6">
            
            <div class="service-card bg-white p-6 rounded-[2rem] text-center premium-border">
                <div class="w-14 h-14 bg-green-50 rounded-2xl flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-map-marked-alt text-3xl text-green-700"></i>
                </div>
                <h3 class="font-bold text-gray-800">ভূমি সেবা</h3>
                <p class="text-[10px] text-green-600 font-bold mt-1 uppercase">খাজনা ও দাখিলা</p>
            </div>

            <div class="service-card bg-white p-6 rounded-[2rem] text-center premium-border">
                <div class="w-14 h-14 bg-blue-50 rounded-2xl flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-fingerprint text-3xl text-blue-700"></i>
                </div>
                <h3 class="font-bold text-gray-800">এনআইডি</h3>
                <p class="text-[10px] text-blue-600 font-bold mt-1 uppercase">সংশোধন ও কপি</p>
            </div>

            <div class="service-card bg-white p-6 rounded-[2rem] text-center premium-border">
                <div class="w-14 h-14 bg-orange-50 rounded-2xl flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-sim-card text-3xl text-orange-600"></i>
                </div>
                <h3 class="font-bold text-gray-800">রিচার্জ</h3>
                <p class="text-[10px] text-orange-600 font-bold mt-1 uppercase">সকল সিম সাহায্য</p>
            </div>

            <div class="service-card bg-white p-6 rounded-[2rem] text-center premium-border">
                <div class="w-14 h-14 bg-purple-50 rounded-2xl flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-file-signature text-3xl text-purple-700"></i>
                </div>
                <h3 class="font-bold text-gray-800">আবেদন</h3>
                <p class="text-[10px] text-purple-600 font-bold mt-1 uppercase">সরকারি চাকরি</p>
            </div>

        </div>

        <div class="mt-12 max-w-4xl mx-auto">
            <div class="bg-white rounded-[3rem] shadow-2xl overflow-hidden border border-gray-100 grid md:grid-cols-2">
                <div class="p-10 text-center border-b md:border-b-0 md:border-r border-gray-100">
                    <h3 class="text-xl font-bold text-gray-800 mb-6 flex items-center justify-center gap-2">
                        <i class="fas fa-coins text-yellow-500"></i> ডিজিটাল পেমেন্ট
                    </h3>
                    <div class="flex justify-center gap-8 mb-8">
                        <div class="hover:scale-110 transition">
                            <img src="https://img.icons8.com/color/48/null/bkash.png" class="w-12 h-12 mx-auto mb-2">
                            <span class="text-[10px] font-black text-pink-600 uppercase">বিকাশ</span>
                        </div>
                        <div class="hover:scale-110 transition">
                            <img src="https://freelogopng.com/images/all_img/1679248787nagad-logo-png.png" class="w-12 h-8 mx-auto object-contain mt-2 mb-2">
                            <span class="text-[10px] font-black text-orange-600 uppercase">নগদ</span>
                        </div>
                    </div>
                    <div class="bg-green-50 p-4 rounded-2xl border-2 border-dashed border-green-200">
                        <p class="text-sm text-green-700 font-bold">ব্যক্তিগত নাম্বার:</p>
                        <p class="text-2xl font-black text-green-900 tracking-tighter">01806730271</p>
                    </div>
                </div>

                <div class="p-10 text-center bg-slate-50">
                    <h3 class="text-xl font-bold text-gray-800 mb-6">আমাদের কিউআর কোড</h3>
                    <div class="bg-white p-4 inline-block rounded-3xl shadow-xl border-4 border-green-700 mb-4 animate-premium">
                        <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://sowrob220-cmy.github.io/Seba-Creative-Point/&color=006a4e" class="w-32 h-32 rounded-lg">
                    </div>
                    <p class="text-[10px] text-gray-500 font-bold uppercase">স্ক্যান করে আমাদের ডিজিটাল সেবা কার্ডটি সেভ করুন</p>
                </div>
            </div>
        </div>
    </main>

    <nav class="fixed bottom-6 left-1/2 -translate-x-1/2 w-[92%] md:w-auto glass-effect px-8 py-4 rounded-[2.5rem] shadow-[0_15px_50px_-15px_rgba(0,0,0,0.3)] border border-white/50 flex justify-around md:gap-16 items-center z-50">
        <a href="tel:01806730271" class="text-gray-400 hover:text-green-700 transition">
            <i class="fas fa-phone-alt text-2xl"></i>
            <span class="block text-[8px] font-bold uppercase mt-1">কল দিন</span>
        </a>
        
        <a href="https://wa.me/8801806730271" class="bg-green-700 text-white px-10 py-4 rounded-full font-black flex items-center gap-3 shadow-xl transform active:scale-90 transition-all hover:bg-green-800">
            <i class="fab fa-whatsapp text-3xl"></i> হোয়াটসঅ্যাপ
        </a>

        <a href="https://www.facebook.com/search/top?q=মোঃ শহীদুল আলম সৌরভ" target="_blank" class="text-gray-400 hover:text-blue-600 transition">
            <i class="fab fa-facebook-messenger text-2xl"></i>
            <span class="block text-[8px] font-bold uppercase mt-1">মেসেঞ্জার</span>
        </a>
    </nav>

    <footer class="mt-20 text-center text-gray-400 pb-10">
        <p class="text-xs font-bold uppercase tracking-widest">&copy; 2026 খাজা আজমীর কম্পিউটার | সকল স্বত্ব সংরক্ষিত</p>
    </div>

</body>
</html>
