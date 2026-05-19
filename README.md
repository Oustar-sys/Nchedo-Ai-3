# Nchedo-Ai-3
Tryer
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nchedo AI</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-slate-100 text-slate-900">
  <header class="bg-white border-b sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Nchedo AI</h1>
      <nav class="flex gap-4 text-sm">
        <a href="#dashboard">Dashboard</a>
        <a href="#video">Video Generator</a>
        <a href="#uploads">Uploads</a>
        <a href="#apk">APK Builder</a>
      </nav>
    </div>
  </header>  <section class="max-w-7xl mx-auto px-6 py-16 text-center">
    <h2 class="text-6xl font-bold">Nchedo AI</h2>
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
