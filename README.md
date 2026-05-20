# Nchedo-Ai-3
Tryer
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nchedo AI | Next-Gen Multi-Modal AI Engine</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#0B0F19',
                            card: '#161F30',
                            accent: '#3B82F6',
                            purple: '#8B5CF6',
                            glow: '#00F2FE'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .gradient-text {
            background: linear-gradient(135deg, #3B82F6 0%, #8B5CF6 50%, #00F2FE 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .glow-effect:hover {
            box-shadow: 0 0 20px rgba(59, 130, 246, 0.4);
        }
    </style>
</head>
<body class="bg-brand-dark text-gray-100 font-sans antialiased">

    <!-- Header / Navbar -->
    <header class="sticky top-0 z-50 backdrop-blur-md bg-brand-dark/80 border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <div class="bg-gradient-to-r from-brand-accent to-brand-purple p-2 rounded-lg text-white font-black text-xl tracking-wider">
                    NΩ
                </div>
                <span class="text-xl font-bold tracking-tight text-white">Nchedo <span class="text-brand-accent">AI</span></span>
            </div>
            
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-400">
                <a href="#features" class="hover:text-white transition">Capabilities</a>
                <a href="#playground" class="hover:text-white transition">Studio Playground</a>
                <a href="#compatibility" class="hover:text-white transition">Android Ecosystem</a>
                <a href="#downloads" class="hover:text-white transition">Export Formats</a>
            </nav>

            <div class="flex items-center gap-4">
                <a href="#playground" class="bg-gradient-to-r from-brand-accent to-brand-purple hover:opacity-90 text-white px-5 py-2 rounded-lg text-sm font-semibold transition glow-effect">
                    Launch Engine
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative overflow-hidden pt-20 pb-16 lg:pt-32 lg:pb-24">
        <div class="absolute inset-0 bg-[radial-gradient(circle_at_top_right,rgba(139,92,246,0.15),transparent_45%)]"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">
            <span class="px-3 py-1 text-xs font-semibold tracking-wider text-brand-glow uppercase bg-brand-accent/10 border border-brand-accent/30 rounded-full">
                Introducing Chedo Engine v2.0
            </span>
            <h1 class="mt-6 text-4xl sm:text-6xl font-black tracking-tight max-w-4xl mx-auto leading-none">
                The All-In-One Intelligent <br><span class="gradient-text">Creative AI Engine</span>
            </h1>
            <p class="mt-6 text-lg text-gray-400 max-w-2xl mx-auto leading-relaxed">
                Generate, build, research, and automate across multiple formats with deep contextual reasoning. From infinite-duration cinematic videos to functional Android APKs.
            </p>
            <div class="mt-10 flex flex-wrap justify-center gap-4">
                <a href="#playground" class="bg-white text-brand-dark px-8 py-3.5 rounded-xl font-bold hover:bg-gray-200 transition shadow-lg">
                    Start Creating Free
                </a>
                <a href="#features" class="bg-brand-card border border-gray-700 px-8 py-3.5 rounded-xl font-bold hover:bg-gray-800 transition text-gray-300">
                    Explore Capabilities
                </a>
            </div>
        </div>
    </section>

    <!-- Core Capabilities Grid -->
    <section id="features" class="py-20 border-t border-gray-900 bg-brand-dark">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl font-bold tracking-tight sm:text-4xl">Architected for Endless Modalities</h2>
                <p class="mt-4 text-gray-400">One deployment. Limitless creative and automated outputs powered by contextual deep reasoning.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Feature 1: Adaptive Video -->
                <div class="bg-brand-card p-8 rounded-2xl border border-gray-800 hover:border-gray-700 transition">
                    <div class="w-12 h-12 rounded-xl bg-blue-500/10 flex items-center justify-center text-brand-accent text-xl mb-6">
                        <i class="fa-solid fa-film"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Adaptive Video Generation</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        No fixed durations. Chedo automatically factors prompt complexity, story flow, and pacing to dynamically output short clips or full long-form cinematic visuals.
                    </p>
                </div>

                <!-- Feature 2: Multi-Style Studio -->
                <div class="bg-brand-card p-8 rounded-2xl border border-gray-800 hover:border-gray-700 transition">
                    <div class="w-12 h-12 rounded-xl bg-purple-500/10 flex items-center justify-center text-brand-purple text-xl mb-6">
                        <i class="fa-solid fa-wand-magic-sparkles"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Advanced Multi-Style System</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        Render fluidly in Cinematic Realism, Anime, 3D Animation, Sci-Fi, or Ad Commercials. Equipped with structural physics, lifelike expressions, and exact lip-syncing.
                    </p>
                </div>

                <!-- Feature 3: Deep Reasoning -->
                <div class="bg-brand-card p-8 rounded-2xl border border-gray-800 hover:border-gray-700 transition">
                    <div class="w-12 h-12 rounded-xl bg-teal-500/10 flex items-center justify-center text-brand-glow text-xl mb-6">
                        <i class="fa-solid fa-brain"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Deep Analysis & Research</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        Layered execution paths for cross-functional problem-solving, detailed scripting, heavy codebase architecture, and comprehensive research pipelines.
                    </p>
                </div>

                <!-- Feature 4: Voice Ecosystem -->
                <div class="bg-brand-card p-8 rounded-2xl border border-gray-800 hover:border-gray-700 transition">
                    <div class="w-12 h-12 rounded-xl bg-red-500/10 flex items-center justify-center text-red-400 text-xl mb-6">
                        <i class="fa-solid fa-microphone-lines"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Voice Upload & Cloning</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        Drop voice recordings to map narration or dialogue characters. Features dynamic emotional inflection adjustments to seamlessly integrate sound design.
                    </p>
                </div>

                <!-- Feature 5: Native App Building -->
                <div class="bg-brand-card p-8 rounded-2xl border border-gray-800 hover:border-gray-700 transition">
                    <div class="w-12 h-12 rounded-xl bg-green-500/10 flex items-center justify-center text-green-400 text-xl mb-6">
                        <i class="fa-solid fa-robot"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Natural Language APK Builder</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        Compile operational mobile applications directly from functional text descriptions or standard raw code blocks. Features fully automated UI and backend flow map logic.
                    </p>
                </div>

                <!-- Feature 6: Cross-Android UI -->
                <div class="bg-brand-card p-8 rounded-2xl border border-gray-800 hover:border-gray-700 transition">
                    <div class="w-12 h-12 rounded-xl bg-orange-500/10 flex items-center justify-center text-orange-400 text-xl mb-6">
                        <i class="fa-brands fa-android"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Broad Android Compatibility</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        Engineered to run natively and adapt efficiently to variable compute properties across multiple versions of mobile hardware environments.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Interactive Interface Fix: Studio Playground -->
    <section id="playground" class="py-20 bg-gradient-to-b from-brand-dark via-brand-card/30 to-brand-dark border-t border-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-12">
                <h2 class="text-3xl font-bold tracking-tight">Interactive Generation Sandbox</h2>
                <p class="mt-4 text-gray-400">Test drive the system matrix interfaces. Feed prompts, connect multi-modal media assets, and specify runtime constraints.</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                <!-- Input Panel Matrix -->
                <div class="lg:col-span-7 bg-brand-card rounded-2xl border border-gray-800 p-6 space-y-6">
                    <div>
                        <label class="block text-sm font-semibold text-gray-300 mb-2">1. Select Target Engine Output Model</label>
                        <div class="grid grid-cols-2 sm:grid-cols-4 gap-3">
                            <button onclick="selectMode('video')" id="btn-video" class="p-3 rounded-xl border border-brand-accent bg-brand-accent/10 text-white font-medium text-xs text-center flex flex-col items-center gap-2 transition">
                                <i class="fa-solid fa-video text-base"></i> Video Studio
                            </button>
                            <button onclick="selectMode('app')" id="btn-app" class="p-3 rounded-xl border border-gray-800 bg-brand-dark text-gray-400 font-medium text-xs text-center flex flex-col items-center gap-2 transition">
                                <i class="fa-solid fa-mobile-screen-button text-base"></i> APK Builder
                            </button>
                            <button onclick="selectMode('code')" id="btn-code" class="p-3 rounded-xl border border-gray-800 bg-brand-dark text-gray-400 font-medium text-xs text-center flex flex-col items-center gap-2 transition">
                                <i class="fa-solid fa-code text-base"></i> Code/Script
                            </button>
                            <button onclick="selectMode('research')" id="btn-research" class="p-3 rounded-xl border border-gray-800 bg-brand-dark text-gray-400 font-medium text-xs text-center flex flex-col items-center gap-2 transition">
                                <i class="fa-solid fa-magnifying-glass text-base"></i> Deep Research
                            </button>
                        </div>
                    </div>

                    <!-- Prompt Textarea -->
                    <div>
                        <div class="flex justify-between items-center mb-2">
                            <label class="text-sm font-semibold text-gray-300">2. Define Engine Prompt / Execution Intent</label>
                            <span id="duration-badge" class="text-[11px] bg-purple-500/20 text-brand-purple border border-purple-500/30 px-2 py-0.5 rounded-md font-mono font-semibold">Adaptive Duration Active</span>
                        </div>
                        <textarea id="main-prompt" rows="4" class="w-full bg-brand-dark border border-gray-800 rounded-xl p-4 text-sm text-gray-200 placeholder-gray-600 focus:outline-none focus:border-brand-accent transition" placeholder="Describe the cinematic sequence, structural script logic, or functional application mapping requirements..."></textarea>
                    </div>

                    <!-- Media Upload Drag & Drop Sandbox Component -->
                    <div>
                        <label class="block text-sm font-semibold text-gray-300 mb-2">3. Multi-Modal Reference Asset Upload (Optional)</label>
                        <div class="border-2 border-dashed border-gray-800 hover:border-gray-700 bg-brand-dark/50 rounded-xl p-6 text-center cursor-pointer transition">
                            <input type="file" id="media-field" class="hidden" multiple onchange="handleFileNotification()">
                            <label for="media-field" class="cursor-pointer">
                                <i class="fa-solid fa-cloud-arrow-up text-3xl text-gray-600 mb-3 block"></i>
                                <span class="text-sm font-medium text-gray-300 block">Drop Audio, Images, Video clips or Voice Files</span>
                                <span class="text-xs text-gray-500 mt-1 block">Maximum upload limits standard context mapping up to 250MB</span>
                            </label>
                        </div>
                        <div id="upload-status" class="hidden mt-2 text-xs text-green-400 font-mono flex items-center gap-2">
                            <i class="fa-solid fa-circle-check"></i> Assets attached to execution payload successfully.
                        </div>
                    </div>

                    <button onclick="triggerEngineSimulate()" class="w-full py-4 rounded-xl bg-gradient-to-r from-brand-accent to-brand-purple text-white font-bold hover:opacity-95 transition tracking-wide text-sm flex items-center justify-center gap-2 shadow-lg">
                        <i class="fa-solid fa-play"></i> Initialize Nchedo Context Pipelines
                    </button>
                </div>

                <!-- Live Interface Engine Previews & Generation Feed Component -->
                <div class="lg:col-span-5 bg-brand-card rounded-2xl border border-gray-800 p-6 flex flex-col h-[520px]">
                    <div class="flex items-center justify-between pb-4 border-b border-gray-800 mb-4">
                        <div class="flex items-center gap-2">
                            <span class="w-2.5 h-2.5 rounded-full bg-green-500 animate-pulse"></span>
                            <span class="text-xs uppercase font-mono tracking-wider font-bold text-gray-400">Output Renderer Terminal</span>
                        </div>
                        <span id="output-type" class="text-xs bg-brand-dark border border-gray-800 px-3 py-1 rounded-full font-mono text-brand-accent">Mode: Video</span>
                    </div>

                    <!-- Simulated Idle State -->
                    <div id="idle-output" class="flex-1 flex flex-col items-center justify-center text-center p-4">
                        <div class="w-16 h-16 rounded-full bg-brand-dark border border-gray-800 flex items-center justify-center text-gray-600 text-xl mb-4">
                            <i class="fa-solid fa-terminal"></i>
                        </div>
                        <h4 class="text-sm font-bold text-gray-300">Awaiting Pipeline Signal</h4>
                        <p class="text-xs text-gray-500 max-w-xs mt-1">Configure your generation constraints and launch the engine context matrix processing blocks.</p>
                    </div>

                    <!-- Simulated Loading State -->
                    <div id="loading-output" class="hidden flex-1 flex flex-col items-center justify-center text-center p-4">
                        <svg class="animate-spin h-8 w-8 text-brand-accent mb-4" fill="none" viewBox="0 0 24 24">
                            <circle class="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" stroke-width="4"></circle>
                            <path class="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path>
                        </svg>
                        <h4 class="text-sm font-bold text-gray-300">Executing Multi-Layer Reasoning</h4>
                        <p id="loading-text" class="text-xs text-gray-500 max-w-xs mt-1 font-mono">Analyzing prompt parameters...</p>
                    </div>

                    <!-- Simulated Rendered Content State -->
                    <div id="success-output" class="hidden flex-1 flex flex-col justify-between">
                        <div id="preview-container" class="w-full h-64 bg-brand-dark rounded-xl border border-gray-800 overflow-hidden relative flex items-center justify-center">
                            <!-- Dynamic Content Inserted by JavaScript -->
                        </div>
                        
                        <div class="bg-brand-dark rounded-xl border border-gray-800 p-4 mt-4">
                            <div class="flex items-center justify-between mb-2">
                                <span class="text-xs font-semibold text-gray-400">Package Diagnostics</span>
                                <span class="text-[11px] font-mono text-green-400 bg-green-500/10 px-1.5 py-0.5 rounded">Ready</span>
                            </div>
                            <div class="space-y-1 text-xs font-mono text-gray-500">
                                <p id="diag-1">Format Matrix: MP4 (H.264 High Profile)</p>
                                <p id="diag-2">Calculated Runtime: 01:24 (Adaptive Reasoned)</p>
                                <p id="diag-3">File Size Estimate: 42.6 MB</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Downloads Control Hub -->
    <section id="downloads" class="py-20 border-t border-gray-900 bg-brand-dark">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-5 space-y-6">
                    <span class="text-xs font-bold font-mono text-brand-purple tracking-widest uppercase">Granular Project Controls</span>
                    <h2 class="text-3xl font-bold tracking-tight sm:text-4xl">Complete Ownership of Project Artifacts</h2>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        Nchedo AI never locks your creations behind sandbox runtimes. Download clean, native artifacts optimized directly for production ecosystems, local editing suites, or straight deployment storage arrays.
                    </p>
                    <div class="pt-2">
                        <div class="flex items-center gap-3 text-sm text-gray-300 font-medium">
                            <i class="fa-solid fa-circle-check text-brand-glow"></i> Multi-track Layered Source Projects
                        </div>
                        <div class="flex items-center gap-3 text-sm text-gray-300 font-medium mt-2">
                            <i class="fa-solid fa-circle-check text-brand-glow"></i> Native Signed APK Deployments
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7 grid grid-cols-2 gap-4">
                    <div class="bg-brand-card border border-gray-800 p-5 rounded-xl flex items-center justify-between group hover:border-gray-700 transition">
                        <div class="flex items-center gap-4">
                            <div class="w-10 h-10 rounded-lg bg-blue-500/10 flex items-center justify-center text-brand-accent text-lg"><i class="fa-solid fa-video"></i></div>
                            <div><h4 class="text-sm font-bold text-white">Videos (.mp4)</h4><p class="text-xs text-gray-500">ProRes / H.264 formats</p></div>
                        </div>
                        <button class="text-gray-500 group-hover:text-white transition"><i class="fa-solid fa-download"></i></button>
                    </div>
                    <div class="bg-brand-card border border-gray-800 p-5 rounded-xl flex items-center justify-between group hover:border-gray-700 transition">
                        <div class="flex items-center gap-4">
                            <div class="w-10 h-10 rounded-lg bg-green-500/10 flex items-center justify-center text-green-400 text-lg"><i class="fa-solid fa-box-archive"></i></div>
                            <div><h4 class="text-sm font-bold text-white">Applications (.apk)</h4><p class="text-xs text-gray-500">Targeting Android 10-16</p></div>
                        </div>
                        <button class="text-gray-500 group-hover:text-white transition"><i class="fa-solid fa-download"></i></button>
                    </div>
                    <div class="bg-brand-card border border-gray-800 p-5 rounded-xl flex items-center justify-between group hover:border-gray-700 transition">
                        <div class="flex items-center gap-4">
                            <div class="w-10 h-10 rounded-lg bg-purple-500/10 flex items-center justify-center text-brand-purple text-lg"><i class="fa-solid fa-music"></i></div>
                            <div><h4 class="text-sm font-bold text-white">Audio (.wav / .mp3)</h4><p class="text-xs text-gray-500">Lossless audio exports</p></div>
                        </div>
                        <button class="text-gray-500 group-hover:text-white transition"><i class="fa-solid fa-download"></i></button>
                    </div>
                    <div class="bg-brand-card border border-gray-800 p-5 rounded-xl flex items-center justify-between group hover:border-gray-700 transition">
                        <div class="flex items-center gap-4">
                            <div class="w-10 h-10 rounded-lg bg-orange-500/10 flex items-center justify-center text-orange-400 text-lg"><i class="fa-solid fa-folder-open"></i></div>
                            <div><h4 class="text-sm font-bold text-white">Project Files</h4><p class="text-xs text-gray-500">Structured system nodes</p></div>
                        </div>
                        <button class="text-gray-500 group-hover:text-white transition"><i class="fa-solid fa-download"></i></button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Area -->
    <footer class="bg-brand-dark border-t border-gray-900 py-12 text-center text-xs text-gray-600">
        <p>&copy; 2026 Nchedo AI Engine Systems Inc. Deep Multi-Modal Automation Nodes. All Rights Reserved.</p>
    </footer>

    <!-- Interactive UI Control Script Logic -->
    <script>
        let currentMode = 'video';

        function selectMode(mode) {
            currentMode = mode;
            
            // Reset active styles on all buttons
            ['video', 'app', 'code', 'research'].forEach(m => {
                const btn = document.getElementById(`btn-${m}`);
                btn.className = "p-3 rounded-xl border border-gray-800 bg-brand-dark text-gray-400 font-medium text-xs text-center flex flex-col items-center gap-2 transition";
            });

            // Set state UI on target mode button
            const activeBtn = document.getElementById(`btn-${mode}`);
            activeBtn.className = "p-3 rounded-xl border border-brand-accent bg-brand-accent/10 text-white font-medium text-xs text-center flex flex-col items-center gap-2 transition";

            // Update associated terminal metadata badges & text indicators
            const outputTypeBadge = document.getElementById('output-type');
            const durationBadge = document.getElementById('duration-badge');
            
            if (mode === 'video') {
                outputTypeBadge.innerText = 'Mode: Video Studio';
                durationBadge.innerText = 'Adaptive Duration Active';
                durationBadge.className = "text-[11px] bg-purple-500/20 text-brand-purple border border-purple-500/30 px-2 py-0.5 rounded-md font-mono font-semibold";
            } else if (mode === 'app') {
                outputTypeBadge.innerText = 'Mode: APK Builder';
                durationBadge.innerText = 'Android Target: Auto';
                durationBadge.className = "text-[11px] bg-green-500/20 text-green-400 border border-green-500/30 px-2 py-0.5 rounded-md font-mono font-semibold";
            } else if (mode === 'code') {
                outputTypeBadge.innerText = 'Mode: Logic Compiler';
                durationBadge.innerText = 'Optimized Execution';
                durationBadge.className = "text-[11px] bg-blue-500/20 text-brand-accent border border-brand-accent/30 px-2 py-0.5 rounded-md font-mono font-semibold";
            } else {
                outputTypeBadge.innerText = 'Mode: Deep Deep Research';
                durationBadge.innerText = 'Reasoning Model';
                durationBadge.className = "text-[11px] bg-amber-500/20 text-amber-400 border border-amber-500/30 px-2 py-0.5 rounded-md font-mono font-semibold";
            }
        }

        function handleFileNotification() {
            document.getElementById('upload-status').classList.remove('hidden');
        }

        function triggerEngineSimulate() {
            const promptVal = document.getElementById('main-prompt').value.trim();
            if(!promptVal) {
                alert('Please enter a generation prompt or command intent to warm up engine execution matrices.');
                return;
            }

            // UI State Transitions
            document.getElementById('idle-output').classList.add('hidden');
            document.getElementById('success-output').classList.add('hidden');
            document.getElementById('loading-output').classList.remove('hidden');

            const loadingText = document.getElementById('loading-text');
            
            // Phase 1 Matrix Simulation Loading text
            setTimeout(() => {
                loadingText.innerText = "Running multi-layer contextual parsing grids...";
            }, 1000);

            // Phase 2 Matrix Simulation Loading text
            setTimeout(() => {
                loadingText.innerText = "Finalizing synthesis and output structures...";
            }, 2200);

            // Output Results Injection Mapping
            setTimeout(() => {
                document.getElementById('loading-output').classList.add('hidden');
                document.getElementById('success-output').classList.remove('hidden');

                const previewContainer = document.getElementById('preview-container');
                const d1 = document.getElementById('diag-1');
                const d2 = document.getElementById('diag-2');
                const d3 = document.getElementById('diag-3');

                if (currentMode === 'video') {
                    previewContainer.innerHTML = `
                        <div class="absolute inset-0 bg-cover bg-center opacity-60" style="background-image: url('https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=600&q=80')"></div>
                        <div class="absolute inset-0 flex flex-col items-center justify-center z-10 bg-black/40">
                            <div class="w-12 h-12 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center text-white text-lg border border-white/40 cursor-pointer hover:scale-110 transition"><i class="fa-solid fa-play ml-1"></i></div>
                            <span class="text-xs text-white font-semibold mt-3 bg-brand-dark/80 px-3 py-1 rounded-full border border-gray-800">Preview: Multi-Scene Cinematic Realism</span>
                        </div>
                    `;
                    d1.innerText = "Format Matrix: MP4 (H.264 High Profile / 24fps)";
                    d2.innerText = "Calculated Runtime: 00:52 (Adaptive Reasoned)";
                    d3.innerText = "File Size Estimate: 28.4 MB";
                } else if (currentMode === 'app') {
                    previewContainer.innerHTML = `
                        <div class="text-center p-6">
                            <i class="fa-solid fa-mobile-screen text-4xl text-green-400 mb-3 animate-pulse"></i>
                            <h5 class="text-sm font-bold text-white">Application Manifest Generated</h5>
                            <p class="text-xs text-gray-500 mt-1 max-w-xs mx-auto">Target Android wrapper build compiled cleanly with full compatibility mapping checks.</p>
                        </div>
                    `;
                    d1.innerText = "Target Package: com.chedo.generated.app";
                    d2.innerText = "SDK Compatibility: API Level 21 through 35";
                    d3.innerText = "Compiled File: production_build.apk (14.2 MB)";
                } else if (currentMode === 'code') {
                    previewContainer.innerHTML = `
                        <div class="w-full h-full p-4 font-mono text-left text-[11px] text-blue-400 bg-gray-950 overflow-y-auto">
                            <span class="text-gray-600">// Context Engine Auto-Generated Module Execution Block</span><br>
                            <span class="text-purple-400">import</span> { NchedoCore, MultiModalNode } <span class="text-purple-400">from</span> <span class="text-green-400">'chedo-ai-sdk'</span>;<br><br>
                            <span class="text-purple-400">async function</span> <span class="text-yellow-400">initializePipeline</span>(intent) {<br>
                            &nbsp;&nbsp;<span class="text-purple-400">const</span> engine = <span class="text-purple-400">new</span> <span class="text-yellow-400">NchedoCore</span>({ adaptivePacing: <span class="text-orange-400">true</span> });<br>
                            &nbsp;&nbsp;<span class="text-purple-400">return await</span> engine.<span class="text-yellow-400">processContextPayload</span>(intent);<br>
                            }
                        </div>
                    `;
                    d1.innerText = "Languages Matched: TypeScript / Node ESM Architecture";
                    d2.innerText = "Validation State: Syntax Tree Clear (0 Warnings)";
                    d3.innerText = "Output Matrix: JSON Schema Core Definition Stream";
                } else {
                    previewContainer.innerHTML = `
                        <div class="w-full h-full p-5 text-left overflow-y-auto space-y-3">
                            <h5 class="text-xs font-bold text-brand-glow uppercase tracking-wider font-mono"><i class="fa-solid fa-list-check"></i> Layered Research Synthesizer</h5>
                            <div class="border-l-2 border-gray-800 pl-3 space-y-2 text-xs">
                                <p class="text-gray-300 font-medium">1. Core Contextual Matrix Discovered</p>
                                <p class="text-gray-500">Cross-referenced historical parameters across indexed structural points.</p>
                                <p class="text-gray-300 font-medium">2. Problem Space Optimization Maps</p>
                                <p class="text-gray-500">Automated generation workflows calculated via algorithmic target vectors.</p>
                            </div>
                        </div>
                    `;
                    d1.innerText = "Information Sources: Real-time Context Extraction Network";
                    d2.innerText = "Reasoning Depth Level: 8-Tier Deductive Reasoning Track";
                    d3.innerText = "Report Export: Structured Documentation Ready (.md)";
                }

            }, 3500);
        }
    </script>
</body>
</html>
    <p class="mt-5 text-lg text-slate-600 max-w-3xl mx-auto">
      AI-powered platform for intelligent video generation, voice workflows, media uploads, research, automation, and APK creation.
    </p>
  </section>  <section class="max-w-4xl mx-auto p-6">
    <div class="bg-white rounded-3xl shadow-lg p-8 border">
      <h3 class="text-3xl font-bold mb-5">Login / Signup</h3>
      <form class="space-y-4">
        <input type="text" placeholder="Full Name" class="w-full border rounded-2xl p-4">
        <input type="email" placeholder="Email" class="w-full border rounded-2xl p-4">
        <input type="password" placeholder="Password" class="w-full border rounded-2xl p-4">
        <button class="w-full bg-black text-white p-4 rounded-2xl">Continue</button>
      </form>
    </div>
  </section>  <section id="dashboard" class="max-w-7xl mx-auto px-6 py-16">
    <h3 class="text-4xl font-bold mb-6">AI Dashboard</h3>
    <div class="grid md:grid-cols-4 gap-4">
      <div class="bg-white p-6 rounded-3xl border">Videos Generated: 0</div>
      <div class="bg-white p-6 rounded-3xl border">Voice Uploads: 0</div>
      <div class="bg-white p-6 rounded-3xl border">Projects: 0</div>
      <div class="bg-white p-6 rounded-3xl border">APK Builds: 0</div>
    </div>
  </section>  <section id="video" class="max-w-7xl mx-auto px-6 py-16">
    <div class="bg-white rounded-3xl p-8 border shadow-lg">
      <h3 class="text-4xl font-bold mb-4">AI Video Generator</h3>
      <textarea class="w-full border rounded-2xl p-4 h-40" placeholder="Describe the video..."></textarea>
      <div class="grid md:grid-cols-2 gap-4 mt-4">
        <select class="border rounded-2xl p-4"><option>Video Style</option></select>
        <select class="border rounded-2xl p-4"><option>Aspect Ratio</option></select>
      </div>
      <button class="mt-5 bg-black text-white px-6 py-4 rounded-2xl">Generate Video</button>
    </div>
  </section>  <section id="uploads" class="max-w-7xl mx-auto px-6 py-16">
    <h3 class="text-4xl font-bold mb-6">Media Upload System</h3>
    <div class="grid lg:grid-cols-3 gap-6">
      <div class="bg-white p-6 rounded-3xl border">
        <h4 class="font-bold mb-3">Image Upload</h4>
        <input type="file" accept="image/*">
      </div>
      <div class="bg-white p-6 rounded-3xl border">
        <h4 class="font-bold mb-3">Audio / Voice Upload</h4>
        <input type="file" accept="audio/*">
      </div>
      <div class="bg-white p-6 rounded-3xl border">
        <h4 class="font-bold mb-3">Video Upload</h4>
        <input type="file" accept="video/*">
      </div>
    </div>
  </section>  <section id="apk" class="max-w-7xl mx-auto px-6 py-16">
    <div class="bg-white rounded-3xl p-8 border shadow-lg">
      <h3 class="text-4xl font-bold mb-4">APK Builder</h3>
      <textarea class="w-full border rounded-2xl p-4 h-40" placeholder="Describe the app to build..."></textarea>
      <div class="grid md:grid-cols-2 gap-4 mt-4">
        <input type="text" placeholder="App Name" class="border rounded-2xl p-4">
        <input type="text" placeholder="Package Name" class="border rounded-2xl p-4">
      </div>
      <button class="mt-5 bg-black text-white px-6 py-4 rounded-2xl">Generate APK</button>
    </div>
  </section>  <footer class="text-center py-8 text-slate-500">
    © 2026 Nchedo AI
  </footer>
</body>
</html>
