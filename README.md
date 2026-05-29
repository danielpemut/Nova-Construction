# Nova-Construction
Professional Construction Website for nova construction 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nova Construction | Real Estate, Materials & Equipment</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Smooth scrolling */
        html { scroll-behavior: smooth; }
        /* Custom scrollbar for dark theme */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #111827; }
        ::-webkit-scrollbar-thumb { background: #374151; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #4b5563; }
    </style>
</head>
<body class="bg-gray-900 text-gray-100 font-sans">

    <!-- 1. NAVIGATION BAR -->
    <nav class="bg-gray-950/90 backdrop-blur-md sticky top-0 z-50 border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <div class="flex items-center gap-2">
                    <i class="fa-solid fa-helmet-safety text-amber-500 text-3xl"></i>
                    <span class="text-2xl font-black tracking-wider text-white">NOVA<span class="text-amber-500">CONSTRUCTION</span></span>
                </div>
                <div class="hidden md:flex space-x-8 text-sm font-medium tracking-wide">
                    <a href="#hero" class="text-amber-500 transition">Home</a>
                    <a href="#marketplace" class="text-gray-300 hover:text-amber-500 transition">Marketplace</a>
                    <a href="#gallery" class="text-gray-300 hover:text-amber-500 transition">Projects</a>
                    <a href="#financing" class="text-gray-300 hover:text-amber-500 transition">Financing</a>
                    <a href="#testimonials" class="text-gray-300 hover:text-amber-500 transition">Testimonials</a>
                </div>
                <div>
                    <a href="#inquiry" class="bg-amber-500 hover:bg-amber-600 text-gray-950 px-5 py-2.5 rounded-md font-bold text-sm transition shadow-lg shadow-amber-500/10">Get a Quote</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- 2. HERO SECTION -->
    <section id="hero" class="relative bg-[url('https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=1920&q=80')] bg-cover bg-center h-[85vh] flex items-center">
        <div class="absolute inset-0 bg-gradient-to-r from-gray-950 via-gray-950/80 to-transparent"></div>
        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 w-full z-10">
            <span class="text-amber-500 font-bold tracking-widest uppercase text-xs bg-amber-500/10 px-3 py-1 rounded-full border border-amber-500/20">Building the Future</span>
            <h1 class="text-4xl md:text-6xl font-black text-white mt-4 max-w-3xl leading-tight">
                Premium Real Estate & <br><span class="text-amber-500">Industrial Solutions</span>
            </h1>
            <p class="mt-6 text-gray-400 text-lg max-w-xl">
                From heavy machinery rentals and raw material sourcing to luxury real estate developments—Nova handles it all with precision.
            </p>
            <div class="mt-10 flex flex-wrap gap-4">
                <a href="#marketplace" class="bg-amber-500 hover:bg-amber-600 text-gray-950 px-8 py-3.5 rounded-md font-bold transition">Explore Marketplace</a>
                <a href="#financing" class="bg-transparent hover:bg-gray-800 border border-gray-600 text-white px-8 py-3.5 rounded-md font-bold transition">Apply for a Loan</a>
            </div>
        </div>
    </section>

    <!-- 3. SEARCH & FILTER SECTION -->
    <section class="relative -mt-16 z-20 max-w-6xl mx-auto px-4">
        <div class="bg-gray-950 p-6 rounded-xl border border-gray-800 shadow-2xl">
            <form class="grid grid-cols-1 md:grid-cols-4 gap-4">
                <div>
                    <label class="block text-xs font-semibold text-gray-400 uppercase mb-2">Category</label>
                    <select class="w-full bg-gray-900 border border-gray-700 rounded-md p-3 text-sm text-white focus:outline-none focus:border-amber-500">
                        <option>All Categories</option>
                        <option>Real Estate (Sales/Rent)</option>
                        <option>Heavy Equipment</option>
                        <option>Construction Materials</option>
                    </select>
                </div>
                <div>
                    <label class="block text-xs font-semibold text-gray-400 uppercase mb-2">Status</label>
                    <select class="w-full bg-gray-900 border border-gray-700 rounded-md p-3 text-sm text-white focus:outline-none focus:border-amber-500">
                        <option>For Sale & Rent</option>
                        <option>For Sale Only</option>
                        <option>For Rent Only</option>
                    </select>
                </div>
                <div>
                    <label class="block text-xs font-semibold text-gray-400 uppercase mb-2">Price Range</label>
                    <select class="w-full bg-gray-900 border border-gray-700 rounded-md p-3 text-sm text-white focus:outline-none focus:border-amber-500">
                        <option>Any Budget</option>
                        <option>$1,000 - $10,000</option>
                        <option>$10,000 - $50,000</option>
                        <option>$50,000+</option>
                    </select>
                </div>
                <div class="flex items-end">
                    <button type="button" class="w-full bg-amber-500 hover:bg-amber-600 text-gray-950 font-bold p-3 rounded-md transition text-sm flex items-center justify-center gap-2">
                        <i class="fa-solid fa-magnifying-glass"></i> Filter Results
                    </button>
                </div>
            </form>
        </div>
    </section>

    <!-- 4. FEATURED ITEMS / MARKETPLACE -->
    <section id="marketplace" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
        <div class="text-center max-w-3xl mx-auto mb-16">
            <h2 class="text-3xl md:text-4xl font-extrabold text-white">Featured Marketplace</h2>
            <div class="h-1 w-20 bg-amber-500 mx-auto mt-4 rounded"></div>
            <p class="text-gray-400 mt-4">Browse our premium fleet of machinery, raw building materials, and ready-to-develop land or property portfolios.</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Item 1: Heavy Machine -->
            <div class="bg-gray-950 rounded-xl overflow-hidden border border-gray-800 hover:border-amber-500/50 transition duration-300 group">
                <div class="relative h-56 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1579616710305-314f6978aa3d?auto=format&fit=crop&w=600&q=80" alt="Excavator" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    <span class="absolute top-4 left-4 bg-amber-500 text-gray-950 text-xs font-black px-2.5 py-1 rounded">FOR RENT</span>
                </div>
                <div class="p-6">
                    <span class="text-amber-500 text-xs font-bold uppercase tracking-wider">Heavy Machinery</span>
                    <h3 class="text-xl font-bold text-white mt-1">CAT 320 Hydraulic Excavator</h3>
                    <p class="text-gray-400 text-sm mt-2">High performance, reliable field excavator ideal for deep digging and earthmoving tasks.</p>
                    <div class="mt-6 pt-4 border-t border-gray-800 flex justify-between items-center">
                        <span class="text-xl font-extrabold text-white">$450 <span class="text-xs text-gray-400 font-normal">/ day</span></span>
                        <a href="#inquiry" class="text-sm font-bold text-amber-500 hover:underline">Inquire Now →</a>
                    </div>
                </div>
            </div>

            <!-- Item 2: Building/Real Estate -->
            <div class="bg-gray-950 rounded-xl overflow-hidden border border-gray-800 hover:border-amber-500/50 transition duration-300 group">
                <div class="relative h-56 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?auto=format&fit=crop&w=600&q=80" alt="Apartment Complex" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    <span class="absolute top-4 left-4 bg-emerald-500 text-white text-xs font-black px-2.5 py-1 rounded">FOR SALE</span>
                </div>
                <div class="p-6">
                    <span class="text-amber-500 text-xs font-bold uppercase tracking-wider">Real Estate</span>
                    <h3 class="text-xl font-bold text-white mt-1">Aero-View Commercial Complex</h3>
                    <p class="text-gray-400 text-sm mt-2">Prime corporate space located in the central business hub with premium amenities.</p>
                    <div class="mt-6 pt-4 border-t border-gray-800 flex justify-between items-center">
                        <span class="text-xl font-extrabold text-white">$1,250,000</span>
                        <a href="#inquiry" class="text-sm font-bold text-amber-500 hover:underline">Inquire Now →</a>
                    </div>
                </div>
            </div>

            <!-- Item 3: Lands -->
            <div class="bg-gray-950 rounded-xl overflow-hidden border border-gray-800 hover:border-amber-500/50 transition duration-300 group">
                <div class="relative h-56 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?auto=format&fit=crop&w=600&q=80" alt="Industrial Land" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    <span class="absolute top-4 left-4 bg-emerald-500 text-white text-xs font-black px-2.5 py-1 rounded">FOR SALE</span>
                </div>
                <div class="p-6">
                    <span class="text-amber-500 text-xs font-bold uppercase tracking-wider">Plots & Lands</span>
                    <h3 class="text-xl font-bold text-white mt-1">12-Acre Industrial Zoning Lot</h3>
                    <p class="text-gray-400 text-sm mt-2">Strategically positioned ready-to-build lot with full utilities and road connection access.</p>
                    <div class="mt-6 pt-4 border-t border-gray-800 flex justify-between items-center">
                        <span class="text-xl font-extrabold text-white">$420,000</span>
                        <a href="#inquiry" class="text-sm font-bold text-amber-500 hover:underline">Inquire Now →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. PROJECT GALLERY (Machinery in Action, Land Dev, Infrastructure) -->
    <section id="gallery" class="bg-gray-950 py-20 border-y border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl md:text-4xl font-extrabold text-white">Project Gallery</h2>
                <div class="h-1 w-20 bg-amber-500 mx-auto mt-4 rounded"></div>
                <p class="text-gray-400 mt-4">Take a look inside our real active job sites, modern infrastructure operations, and land transformations.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Gallery 1: Machinery in action -->
                <div class="relative group overflow-hidden rounded-lg h-80 shadow-lg">
                    <img src="https://images.unsplash.com/photo-1535732759880-bbd5c7265e3f?auto=format&fit=crop&w=600&q=80" alt="Machinery in action" class="w-full h-full object-cover transition duration-500 group-hover:scale-110">
                    <div class="absolute inset-0 bg-gradient-to-t from-gray-950 via-gray-950/40 to-transparent flex flex-col justify-end p-6 opacity-90 group-hover:opacity-100 transition">
                        <span class="text-amber-400 text-xs font-bold tracking-wider uppercase">Heavy Duty Operations</span>
                        <h4 class="text-xl font-bold text-white mt-1">Site Excavation & Deep Grating</h4>
                    </div>
                </div>

                <!-- Gallery 2: Land Development -->
                <div class="relative group overflow-hidden rounded-lg h-80 shadow-lg">
                    <img src="https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=600&q=80" alt="Land development" class="w-full h-full object-cover transition duration-500 group-hover:scale-110">
                    <div class="absolute inset-0 bg-gradient-to-t from-gray-950 via-gray-950/40 to-transparent flex flex-col justify-end p-6 opacity-90 group-hover:opacity-100 transition">
                        <span class="text-amber-400 text-xs font-bold tracking-wider uppercase">Land Development</span>
                        <h4 class="text-xl font-bold text-white mt-1">Foundations & Urban Leveling</h4>
                    </div>
                </div>

                <!-- Gallery 3: Infrastructure -->
                <div class="relative group overflow-hidden rounded-lg h-80 shadow-lg">
                    <img src="https://images.unsplash.com/photo-1590069261209-f8e9b8642343?auto=format&fit=crop&w=600&q=80" alt="Infrastructure" class="w-full h-full object-cover transition duration-500 group-hover:scale-110">
                    <div class="absolute inset-0 bg-gradient-to-t from-gray-950 via-gray-950/40 to-transparent flex flex-col justify-end p-6 opacity-90 group-hover:opacity-100 transition">
                        <span class="text-amber-400 text-xs font-bold tracking-wider uppercase">Infrastructure</span>
                        <h4 class="text-xl font-bold text-white mt-1">Highway & Bridge Networks</h4>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 6. LOAN & FINANCING APPLICATION FEATURE -->
    <section id="financing" class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
        <div class="bg-gradient-to-br from-gray-950 to-gray-900 rounded-2xl p-8 md:p-12 border border-amber-500/20 shadow-2xl relative overflow-hidden">
            <div class="absolute -right-16 -bottom-16 w-64 h-64 bg-amber-500/5 rounded-full blur-3xl"></div>
            
            <div class="grid grid-cols-1 lg:grid-cols-5 gap-8 items-center">
                <div class="lg:col-span-2">
                    <span class="text-amber-500 text-sm font-bold uppercase tracking-widest">Nova Capital</span>
                    <h2 class="text-3xl font-extrabold text-white mt-2">Need Project Financing?</h2>
                    <p class="text-gray-400 text-sm mt-4 leading-relaxed">
                        Apply for flexible, low-interest commercial asset and real estate procurement loans directly through Nova. Get approved in under 48 hours.
                    </p>
                    <ul class="mt-6 space-y-2 text-sm text-gray-300">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-amber-500 text-xs"></i> Competitive industry interest rates</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-amber-500 text-xs"></i> Zero hidden processing fees</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-amber-500 text-xs"></i> Custom repayment durations</li>
                    </ul>
                </div>
                
                <!-- Loan Form -->
                <div class="lg:col-span-3 bg-gray-900 p-6 rounded-xl border border-gray-800">
                    <form>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-semibold text-gray-400 mb-1">Company/Full Name</label>
                                <input type="text" placeholder="John Doe" class="w-full bg-gray-950 border border-gray-800 rounded p-2.5 text-sm text-white focus:outline-none focus:border-amber-500">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-gray-400 mb-1">Email Address</label>
                                <input type="email" placeholder="john@example.com" class="w-full bg-gray-950 border border-gray-800 rounded p-2.5 text-sm text-white focus:outline-none focus:border-amber-500">
                            </div>
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-4">
                            <div>
                                <label class="block text-xs font-semibold text-gray-400 mb-1">Required Amount ($)</label>
                                <input type="number" placeholder="e.g. 50000" class="w-full bg-gray-950 border border-gray-800 rounded p-2.5 text-sm text-white focus:outline-none focus:border-amber-500">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-gray-400 mb-1">Loan Purpose</label>
                                <select class="w-full bg-gray-950 border border-gray-800 rounded p-2.5 text-sm text-gray-400 focus:outline-none focus:border-amber-500">
                                    <option>Equipment Leasing</option>
                                    <option>Real Estate / Land Acquisition</option>
                                    <option>Materials Sourcing</option>
                                </select>
                            </div>
                        </div>
                        <button type="button" class="w-full mt-6 bg-amber-500 hover:bg-amber-600 text-gray-950 font-bold py-3 rounded text-sm transition">
                            Submit Pre-Approval Application
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- 7. TESTIMONIALS SECTION -->
    <section id="testimonials" class="bg-gray-950 py-20 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl md:text-4xl font-extrabold text-white">Trusted by Developers</h2>
                <div class="h-1 w-20 bg-amber-500 mx-auto mt-4 rounded"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-gray-900 p-6 rounded-xl border border-gray-800 relative">
                    <span class="text-6xl text-amber-500/10 absolute top-2 right-4 font-serif">“</span>
                    <div class="flex text-amber-500 gap-1 text-xs mb-4">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    </div>
                    <p class="text-gray-300 text-sm italic leading-relaxed">
                        "Nova provided top-tier machinery for our highway project. Their response time was incredible, and the heavy machinery worked flawlessly on-site."
                    </p>
                    <div class="mt-6 flex items-center gap-3">
                        <div class="w-10 h-10 bg-amber-500 rounded-full flex items-center justify-center text-gray-950 font-bold text-sm">MT</div>
                        <div>
                            <h4 class="text-sm font-bold text-white">Marcus Vance</h4>
                            <p class="text-xs text-gray-500">Apex Infra Director</p>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 2 -->
                <div class="bg-gray-900 p-6 rounded-xl border border-gray-800 relative">
                    <span class="text-6xl text-amber-500/10 absolute top-2 right-4 font-serif">“</span>
                    <div class="flex text-amber-500 gap-1 text-xs mb-4">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    </div>
                    <p class="text-gray-300 text-sm italic leading-relaxed">
                        "We acquired 4 prime commercial plots safely through Nova's brokerage. The transparency and seamless financing options made it easy."
                    </p>
                    <div class="mt-6 flex items-center gap-3">
                        <div class="w-10 h-10 bg-amber-500 rounded-full flex items-center justify-center text-gray-950 font-bold text-sm">SK</div>
                        <div>
                            <h4 class="text-sm font-bold text-white">Sarah Jenkins</h4>
                            <p class="text-xs text-gray-500">Vertex Properties CEO</p>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 3 -->
                <div class="bg-gray-900 p-6 rounded-xl border border-gray-800 relative">
                    <span class="text-6xl text-amber-500/10 absolute top-2 right-4 font-serif">“</span>
                    <div class="flex text-amber-500 gap-1 text-xs mb-4">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    </div>
                    <p class="text-gray-300 text-sm italic leading-relaxed">
                        "Their material bulk supply rates saved us roughly 15% on aggregate concrete and structural steel costs this quarter alone."
                    </p>
                    <div class="mt-6 flex items-center gap-3">
                        <div class="w-10 h-10 bg-amber-500 rounded-full flex items-center justify-center text-gray-950 font-bold text-sm">DK</div>
                        <div>
                            <h4 class="text-sm font-bold text-white">David Kross</h4>
                            <p class="text-xs text-gray-500">Lead Project Architect</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 8. INQUIRY FORM SECTION -->
    <section id="inquiry" class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
        <div class="text-center max-w-2xl mx-auto mb-12">
            <h2 class="text-3xl font-extrabold text-white">General Quotation & Inquiry</h2>
            <p class="text-gray-400 text-sm mt-2">Have a question about purchasing, logistics, or renting specific models? Shoot us an inquiry.</p>
        </div>

        <form class="bg-gray-950 p-8 rounded-xl border border-gray-800 space-y-6">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                    <label class="block text-xs font-semibold text-gray-400 uppercase mb-2">First & Last Name</label>
                    <input type="text" required class="w-full bg-gray-900 border border-gray-700 rounded p-3 text-sm text-white focus:outline-none focus:border-amber-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-gray-400 uppercase mb-2">Phone Number</label>
                    <input type="tel" class="w-full bg-gray-900 border border-gray-700 rounded p-3 text-sm text-white focus:outline-none focus:border-amber-500">
                </div>
            </div>
            <div>
                <label class="block text-xs font-semibold text-gray-400 uppercase mb-2">Nature of Request</label>
                <select class="w-full bg-gray-900 border border-gray-700 rounded p-3 text-sm text-white focus:outline-none focus:border-amber-500">
                    <option>Equipment Procurement / Rental Inquiry</option>
                    <option>Real Estate Listing / Land Procurement</option>
                    <option>Bulk Material Pricing Quote</option>
                    <option>Other General Services</option>
                </select>
            </div>
            <div>
                <label class="block text-xs font-semibold text-gray-400 uppercase mb-2">Message Description</label>
                <textarea rows="5" placeholder="List specific technical features, items, or requirements..." class="w-full bg-gray-900 border border-gray-700 rounded p-3 text-sm text-white focus:outline-none focus:border-amber-500"></textarea>
            </div>
            <button type="submit" class="w-full bg-amber-500 hover:bg-amber-600 text-gray-950 font-bold py-3.5 rounded text-sm transition tracking-wider uppercase">
                Send Request Securely
            </button>
        </form>
    </section>

    <!-- 9. FOOTER SECTION -->
    <footer class="bg-gray-950 text-gray-500 text-sm py-12 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-6">
            <div class="flex items-center gap-2">
                <i class="fa-solid fa-helmet-safety text-amber-500 text-2xl"></i>
                <span class="text-lg font-black tracking-wider text-white">NOVA<span class="text-amber-500">CONSTRUCTION</span></span>
            </div>
            <div class="flex space-x-6 text-xs uppercase tracking-widest">
                <a href="#hero" class="hover:text-white transition">Privacy Policy</a>
                <a href="#marketplace" class="hover:text-white transition">Terms of Sale</a>
                <a href="#financing" class="hover:text-white transition">Lending License</a>
            </div>
            <p class="text-xs">&copy; 2026 Nova Construction Co. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
