<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Visionary Business Solutions</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html { scroll-behavior: smooth; }
    .fade-in { animation: fadeIn 1s ease-in-out; }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body class="font-sans antialiased text-gray-900">

  <!-- Sticky Nav -->
  <header class="bg-white fixed w-full z-50 shadow-sm">
    <nav class="max-w-7xl mx-auto flex items-center justify-between p-6">
      <img src="VBS.png" alt="VBS Logo" class="h-10" />
      <ul class="hidden md:flex space-x-8 text-sm">
        <li><a href="#about" class="hover:text-blue-700">About</a></li>
        <li><a href="#services" class="hover:text-blue-700">Services</a></li>
        <li><a href="#consulting" class="hover:text-blue-700">Consulting</a></li>
        <li><a href="#team" class="hover:text-blue-700">Team</a></li>
        <li><a href="#milestones" class="hover:text-blue-700">Milestones</a></li>
        <li><a href="#insights" class="hover:text-blue-700">Insights</a></li>
        <li><a href="#contact" class="hover:text-blue-700">Contact</a></li>
      </ul>
      <button id="menu-toggle" class="md:hidden">
        <svg class="h-6 w-6 text-gray-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </nav>
    <div id="mobile-menu" class="md:hidden hidden px-6 pb-4">
      <a href="#about" class="block py-2">About</a>
      <a href="#services" class="block py-2">Services</a>
      <a href="#consulting" class="block py-2">Consulting</a>
      <a href="#team" class="block py-2">Team</a>
      <a href="#milestones" class="block py-2">Milestones</a>
      <a href="#insights" class="block py-2">Insights</a>
      <a href="#contact" class="block py-2">Contact</a>
    </div>
  </header>

  <main class="pt-28">

    <!-- Hero Section -->
    <section class="relative w-full h-screen bg-cover bg-center text-white" style="background-image:url('hero.jpg')">
      <div class="absolute inset-0 bg-black opacity-50"></div>
      <div class="relative z-10 flex flex-col justify-center items-center h-full px-4 fade-in">
        <h1 class="text-4xl md:text-6xl font-bold text-center max-w-3xl">Empowering Growth Through Visionary Strategy</h1>
        <p class="mt-4 text-lg md:text-xl max-w-2xl text-center">Innovate. Elevate. Succeed.</p>
        <a href="#insights" class="mt-6 inline-block bg-blue-700 hover:bg-blue-800 text-white px-8 py-3 rounded">Explore Insights</a>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="py-20 px-4 bg-gray-50">
      <div class="max-w-5xl mx-auto text-center fade-in">
        <h2 class="text-3xl font-semibold mb-4">About Visionary Business Solutions</h2>
        <p class="text-gray-700 leading-relaxed mb-4">VBS is a consulting firm that equips SMEs and startups with data-driven strategies and digital transformation tools. Founded in South Africa by Tinotenda L. Msanu Chitanda and Noluthando Musewe, VBS combines deep industry knowledge with agile delivery.</p>
        <p class="text-gray-700 leading-relaxed">We partner with organizations across Africa and the world to drive sustainable growth, scalability, and competitive advantage.</p>
      </div>
    </section>

    <!-- Services -->
    <section id="services" class="py-20 px-4">
      <div class="max-w-5xl mx-auto fade-in">
        <h2 class="text-3xl font-semibold mb-8 text-center">Our Core Services</h2>
        <div class="grid md:grid-cols-2 gap-8">
          <div class="p-6 bg-white shadow rounded-lg hover:shadow-lg transition">
            <h3 class="text-xl font-bold mb-2">Business Strategy</h3>
            <p>We craft tailored strategies aligned with market trends, financial goals, and growth ambitions.</p>
          </div>
          <div class="p-6 bg-white shadow rounded-lg hover:shadow-lg transition">
            <h3 class="text-xl font-bold mb-2">Market Research</h3>
            <p>Comprehensive studies and analytics to inform product positioning, customer segmentation, and expansion strategies.</p>
          </div>
          <div class="p-6 bg-white shadow rounded-lg hover:shadow-lg transition">
            <h3 class="text-xl font-bold mb-2">Digital Transformation</h3>
            <p>AI-driven automation, system integrations, and IT architecture designed to enhance efficiency.</p>
          </div>
          <div class="p-6 bg-white shadow rounded-lg hover:shadow-lg transition">
            <h3 class="text-xl font-bold mb-2">Ongoing Advisory</h3>
            <p>Monthly check-ins, KPI tracking, and strategic updates to navigate evolving challenges.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Consulting -->
    <section id="consulting" class="py-20 px-4 bg-gray-50">
      <div class="max-w-5xl mx-auto fade-in">
        <h2 class="text-3xl font-semibold mb-6 text-center">Why Consulting Matters</h2>
        <p class="text-gray-700 mb-6 leading-relaxed text-center">With the global consulting market expected to surpass US$ 300B by 2026, SMEs must embrace advisory services for competitive edge. Digital adoption and strategic clarity are no longer optional—they’re essential today.</p>
        <ul class="grid md:grid-cols-3 gap-6">
          <li class="bg-white p-6 shadow rounded-lg">
            <h4 class="font-semibold mb-2">Data‑Driven Insights</h4>
            <p>We use analytics and real-time metrics to inform high-impact decisions.</p>
          </li>
          <li class="bg-white p-6 shadow rounded-lg">
            <h4 class="font-semibold mb-2">Digital Enablement</h4>
            <p>Cloud, AI, and automation to power operational transformation.</p>
          </li>
          <li class="bg-white p-6 shadow rounded-lg">
            <h4 class="font-semibold mb-2">SME‑Focused</h4>
            <p>We adapt enterprise-grade solutions into agile, affordable offerings.</p>
          </li>
        </ul>
      </div>
    </section>

    <!-- Team -->
    <section id="team" class="py-20 px-4">
      <div class="max-w-4xl mx-auto text-center fade-in">
        <h2 class="text-3xl font-semibold mb-4">Meet Our Leadership</h2>
        <p class="text-gray-700 mb-8">Our team combines seasoned consulting expertise with entrepreneurial passion.</p>
        <div class="grid md:grid-cols-3 gap-8">
          <div><h4 class="font-bold">Tinotenda L. M. Chitanda</h4><p class="text-gray-600">Founder & CEO</p></div>
          <div><h4 class="font-bold">Noluthando Musewe</h4><p class="text-gray-600">Co‑Founder & COO</p></div>
          <div><h4 class="font-bold">Leslie Boatwright</h4><p class="text-gray-600">Chief Financial Officer</p></div>
        </div>
      </div>
    </section>

    <!-- Milestones -->
    <section id="milestones" class="py-20 px-4 bg-gray-50">
      <div class="max-w-4xl mx-auto fade-in">
        <h2 class="text-3xl font-semibold mb-4 text-center">Our Roadmap</h2>
        <ol class="list-decimal list-inside text-gray-700 space-y-2 max-w-md mx-auto">
          <li><strong>2026:</strong> Launch subscription advisory platform</li>
          <li><strong>2027:</strong> Expand into three regional markets</li>
          <li><strong>2030:</strong> Go global with consulting platform</li>
          <li><strong>2035:</strong> Become leader in AI-driven SME consulting</li>
        </ol>
      </div>
    </section>

    <!-- Insights -->
    <section id="insights" class="py-20 px-4">
      <div class="max-w-5xl mx-auto fade-in">
        <h2 class="text-3xl font-semibold mb-8 text-center">Latest Insights</h2>
        <div class="grid md:grid-cols-3 gap-8">
          <!-- Article Cards: include thumbnails -->
          <div class="bg-white shadow rounded-lg overflow-hidden hover:shadow-lg transition">
            <img src="thumb1.jpg" alt="AI article" class="w-full h-40 object-cover" />
            <div class="p-4"><h3 class="font-bold mb-2">AI’s Disruption in SMEs</h3><p class="text-gray-600 text-sm mb-4">How AI adoption is transforming small businesses.</p><a href="#" class="text-blue-700 hover:underline">Read more →</a></div>
          </div>
          <!-- Replicate two more cards -->
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="py-20 px-4 bg-gray-50">
      <div class="max-w-3xl mx-auto fade-in text-center">
        <h2 class="text-3xl font-semibold mb-4">Let’s Talk Strategy</h2>
        <form action="https://formspree.io/f/yourFormID" method="POST" class="grid gap-4">
          <input name="name" placeholder="Name" class="p-3 border rounded" required />
          <input name="email" type="email" placeholder="Email" class="p-3 border rounded" required />
          <textarea name="message" rows="5" placeholder="Your Message" class="p-3 border rounded"></textarea>
          <button type="submit" class="bg-blue-700 hover:bg-blue-800 text-white py-3 rounded">Send Message</button>
        </form>
      </div>
    </section>

  </main>

  <footer class="bg-white border-t py-8">
    <div class="max-w-5xl mx-auto text-center text-gray-600 text-sm">
      &copy; 2025 Visionary Business Solutions | Contact: hello@vbs.co.za | +27 12 345 6789
    </div>
  </footer>

  <script>
    // Mobile menu toggle
    const btn = document.getElementById('menu-toggle');
    const menu = document.getElementById('mobile-menu');
    btn.addEventListener('click', () => menu.classList.toggle('hidden'));
  </script>

</body>
</html>
