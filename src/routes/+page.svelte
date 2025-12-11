<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-canopy-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-canopy-lime)]"></span>
                        <span class="text-white text-sm font-medium">New</span>
                        <span class="text-gray-400 text-sm">AI-powered quote generation</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Stop losing deals to manual quoting errors.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        DealerOS streamlines dealer operations through automated quoting and workflow intelligence. Generate accurate quotes in seconds, eliminate spreadsheet errors, and accelerate your sales cycle.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Request demo
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            See how it works
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-600">Quote #Q-2847</div>
                                <div class="h-8 w-24 bg-green-100 rounded text-green-700 text-xs flex items-center justify-center font-bold">$24,850</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-20 bg-gray-100 rounded-lg w-full flex items-center justify-center text-gray-400 text-xs">Industrial Pump System</div>
                                <div class="h-3 w-full bg-gray-50 rounded"></div>
                                <div class="h-3 w-2/3 bg-gray-50 rounded"></div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-[var(--color-canopy-lime)] p-6">
                                <div class="flex justify-between items-center">
                                    <div class="text-white font-bold text-sm">New Quote</div>
                                    <div class="h-8 w-8 bg-white/20 rounded-full"></div>
                                </div>
                            </div>
                            <div class="p-6 flex-grow">
                                <div class="space-y-4">
                                    <div>
                                        <div class="text-xs text-gray-500 mb-1">Customer</div>
                                        <div class="h-8 w-full bg-gray-50 rounded border border-gray-200 flex items-center px-3 text-xs text-gray-700">Acme Manufacturing</div>
                                    </div>
                                    <div>
                                        <div class="text-xs text-gray-500 mb-1">Product</div>
                                        <div class="h-8 w-full bg-gray-50 rounded border border-gray-200 flex items-center px-3 text-xs text-gray-700">Hydraulic System</div>
                                    </div>
                                    <div>
                                        <div class="text-xs text-gray-500 mb-1">Quantity</div>
                                        <div class="h-8 w-full bg-gray-50 rounded border border-gray-200 flex items-center px-3 text-xs text-gray-700">5 units</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-600">Quote #Q-2849</div>
                                <div class="h-8 w-24 bg-blue-100 rounded text-blue-700 text-xs flex items-center justify-center font-bold">$18,200</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-20 bg-gray-100 rounded-lg w-full flex items-center justify-center text-gray-400 text-xs">Equipment Parts Bundle</div>
                                <div class="h-3 w-full bg-gray-50 rounded"></div>
                                <div class="h-3 w-2/3 bg-gray-50 rounded"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by leading industrial distributors</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-50 grayscale">
                    <!-- Generic Industrial Logos -->
                    <div class="h-8 w-24 bg-white/20 rounded flex items-center justify-center text-white text-xs font-bold">ACME</div>
                    <div class="h-8 w-28 bg-white/20 rounded flex items-center justify-center text-white text-xs font-bold">INDUSTRIAL</div>
                    <div class="h-8 w-32 bg-white/20 rounded flex items-center justify-center text-white text-xs font-bold">SUPPLY CO</div>
                    <div class="h-8 w-24 bg-white/20 rounded flex items-center justify-center text-white text-xs font-bold">PARTS</div>
                    <div class="h-8 w-28 bg-white/20 rounded flex items-center justify-center text-white text-xs font-bold">EQUIPMENT</div>
                </div>
            </div>
        </section>

        <!-- DealerOS Core Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-canopy-lime)] font-mono text-xs tracking-[0.2em] uppercase mb-6">DealerOS Platform</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Automated quoting.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Accelerated sales.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Blue Card -->
                    <div class="bg-gradient-to-br from-[#3B82F6] to-[#1E40AF] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Quote Card -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="flex justify-between items-start mb-4">
                                    <div class="space-y-1">
                                        <div class="text-white/60 text-[10px] uppercase tracking-wider font-medium">Quote Number</div>
                                        <div class="text-white font-mono text-lg tracking-wider">Q-2024-0847</div>
                                    </div>
                                    <div class="bg-green-400/20 text-green-200 px-3 py-1 rounded-full text-xs font-bold">APPROVED</div>
                                </div>
                                <div class="text-white/60 text-[10px] uppercase tracking-wider font-medium mb-1">Total Amount</div>
                                <div class="text-white font-bold text-3xl">$24,850.00</div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-blue-100 flex items-center justify-center text-blue-600">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"/><path fill-rule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm9.707 5.707a1 1 0 00-1.414-1.414L9 12.586l-1.293-1.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/></svg>
                                    </div>
                                    Fast quotes
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-blue-500/30 flex items-center justify-center text-blue-200">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/></svg>
                                    </div>
                                    Zero errors
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Win more deals with speed and accuracy.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Dealer sales teams waste hours on manual spreadsheets and lose deals to quoting errors. DealerOS automates your entire quoting workflow so you can respond faster and close more business.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Platform Features</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Everything you need to streamline dealer operations.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">From quote to close.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        See all features
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-canopy-lime)]"></span>
                                Smart Quoting
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Workflow Automation</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Price Intelligence</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Order Management</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Analytics Dashboard</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Team Collaboration</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Smart Quoting" 
                            description="Generate accurate quotes in seconds. DealerOS eliminates manual spreadsheet errors with intelligent pricing rules and real-time product data, ensuring every quote is perfect."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Workflow Automation" 
                            description="Stop wasting hours on repetitive tasks. Automate quote approvals, customer notifications, and order processing so your team can focus on selling."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Price Intelligence" 
                            description="Win more deals with smart pricing. Real-time market insights and competitor analysis help you price competitively while protecting margins."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Order Management" 
                            description="Track every deal from quote to delivery. Seamlessly convert quotes to orders and monitor fulfillment status in one unified dashboard."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Analytics Dashboard" 
                            description="Make data-driven decisions. Track quote conversion rates, sales velocity, and team performance with real-time dashboards and custom reports."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Team Collaboration" 
                            description="Keep everyone aligned. Share quotes, track revisions, and collaborate with teammates in real-time to close deals faster."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- Embed Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-blue-100 to-indigo-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-blue-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Built for industrial distributors and equipment dealers who compete on speed and accuracy.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        See customer stories
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by leading dealer teams. See how they're winning with DealerOS.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Customer Card -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">ACME Industrial</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-canopy-lime)] flex items-center justify-center text-white font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
                                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path
                                                fill-rule="evenodd"
                                                clip-rule="evenodd"
                                                d="M6.99251 12.196C6.85314 12.5757 6.62925 12.9208 6.33682 13.2067H6.33835C6.00191 13.5351 5.58566 13.7756 5.12816 13.9059C4.67065 14.0362 4.18671 14.0522 3.72118 13.9523C3.25564 13.8524 2.82357 13.64 2.46501 13.3345C2.10645 13.0291 1.83299 12.6406 1.66998 12.2051C1.50697 11.7696 1.45969 11.3012 1.5325 10.8432C1.60532 10.3852 1.79587 9.95244 2.08653 9.58516C2.37718 9.21781 2.75852 8.9277 3.1952 8.74177C3.63188 8.55585 4.10979 8.48002 4.58462 8.52142L4.57074 8.50792C5.0567 8.54782 5.54575 8.48407 6.00378 8.32124C6.4618 8.15846 6.87776 7.90043 7.2226 7.56521C7.56746 7.22998 7.83285 6.82564 8.00036 6.38041C8.16786 5.93517 8.23344 5.45976 8.1924 4.98737L8.20628 5.00087C8.15181 4.43594 8.27796 3.86844 8.56753 3.37575C8.85701 2.88307 9.29579 2.48919 9.82407 2.24782C10.3523 2.00645 10.9443 1.92933 11.5192 2.02701C12.0942 2.12467 12.6243 2.39237 13.037 2.79358C13.4497 3.19479 13.7251 3.70999 13.8256 4.26892C13.926 4.82785 13.8467 5.4033 13.5984 5.9168C13.3501 6.4303 12.9449 6.85685 12.4381 7.13828C11.9313 7.41971 11.3474 7.54233 10.7663 7.4894L10.781 7.5029C10.2949 7.46279 9.80563 7.52632 9.34741 7.68904C8.88919 7.85176 8.47309 8.10975 8.12805 8.44499C7.78301 8.78025 7.51742 9.18466 7.34983 9.63001C7.18224 10.0754 7.11669 10.551 7.15774 11.0235L7.14309 11.01C7.1833 11.4112 7.13189 11.8162 6.99251 12.196Z"
                                                fill="white"
                                            />
                                        </svg>
                                        DealerOS
                                    </div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-4 max-w-md">
                                    <span class="text-[var(--color-canopy-lime)]">50% faster quotes.</span><br>
                                    How ACME Industrial cut quote time from hours to minutes
                                </h3>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-end">
                                <div class="absolute inset-0 bg-gradient-to-br from-blue-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white font-semibold mb-2">Parts Plus</p>
                                    <p class="text-gray-400 text-sm mb-4">95% quote accuracy</p>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-end">
                                <div class="absolute inset-0 bg-gradient-to-br from-green-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white font-semibold mb-2">Equipment Co</p>
                                    <p class="text-gray-400 text-sm mb-4">3x more quotes per day</p>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-blue-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-indigo-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Stop losing deals to slow quotes. <span class="text-[var(--color-canopy-lime)]">Start winning with speed.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Join 100+ dealer teams who've eliminated quoting errors and accelerated their sales cycles with DealerOS.
                        </p>
                        <button class="inline-flex items-center gap-2 bg-[var(--color-canopy-lime)] hover:bg-[var(--color-canopy-lime-hover)] text-white rounded-full px-6 py-3 text-sm font-medium transition-colors">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                            Request a demo
                        </button>
                    </div>
                </div>

                <!-- Integrations -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        ERP systems. CRM platforms.<br>
                        Inventory management. <span class="text-gray-400">Whatever tools you use,<br>DealerOS integrates seamlessly.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        View all integrations
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['Salesforce', 'SAP', 'Oracle', 'NetSuite', 'QuickBooks', 'Microsoft', 'Epicor', 'Infor'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl uppercase tracking-wider">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn more about modern dealer operations.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-gray-200 to-gray-300 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <div class="absolute inset-0 flex items-center justify-center">
                                    <div class="grid grid-cols-6 gap-4 opacity-50">
                                        {#each Array(24) as _}
                                            <svg class="w-6 h-6 text-blue-600 transform -rotate-45" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                                        {/each}
                                    </div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Best Practices</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-blue-600 transition-colors">How top dealers are winning with automated quoting workflows</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-green-400 blur-xl opacity-80"></div>
                                    <div class="w-20 h-20 rounded-full bg-blue-400 blur-xl opacity-80"></div>
                                    <div class="w-12 h-12 rounded-full bg-purple-400 blur-xl opacity-80"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Industry Trends</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-blue-600 transition-colors">The $50B opportunity in wholesale distribution automation</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

