<script setup lang="ts">
</script>

<template>
  <div class="min-h-screen bg-[#eafce4] text-slate-800 font-sans p-4 sm:p-8 flex justify-center">
    <div class="max-w-4xl w-full bg-white rounded-3xl shadow-xl overflow-hidden px-6 sm:px-16 py-8 sm:py-12 space-y-12">

      <header class="flex items-center justify-between">
        <div class="font-bold text-xl tracking-tight">Kent</div>
        <nav class="hidden sm:flex items-center space-x-6 text-sm font-medium text-slate-600">
          <a href="#home" class="hover:text-black">Home</a>
          <a href="#about" class="hover:text-black">About</a>
          <a href="#process" class="hover:text-black">Process</a>
          <a href="#portfolio" class="hover:text-black">Portfolio</a>
          <a href="#skills" class="hover:text-black">Skills</a>
          <a href="#contact" class="bg-[#bcf078] hover:bg-[#aae860] text-slate-900 px-4 py-2 rounded-full font-semibold transition">Contact</a>
        </nav>
      </header>

      <!-- Hero Section -->
      <section id="home" class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center bg-gradient-to-b from-[#f4fde0] to-transparent p-8 rounded-3xl">
        <div class="space-y-6">
          <h1 class="text-4xl sm:text-5xl font-extrabold tracking-tight leading-tight">
            Hello , I'm <br />Kent
          </h1>
          <p class="text-slate-600 text-sm sm:text-base leading-relaxed">
            Hi there! I'm a fourth-year Computer Engineering student with a deep passion for building practical projects, mastering new technologies, and exploring where hardware meets software. Whether it's coding software, tinkering with embedded systems, or designing intelligent solutions, I love turning complex problems into working systems.
          </p>
          <div>
            <a
                href="/cvkent.pdf"
                download="Kent_Heinz_Vinson_Peralta_CV.pdf"
                class="inline-block bg-[#bcf078] hover:bg-[#aae860] text-slate-900 font-semibold px-6 py-3 rounded-full text-sm transition shadow-sm"
            >
              Download CV
            </a>
          </div>
        </div>

        <div class="flex justify-center">
          <!-- Profile image placeholder box -->
          <div class="w-64 h-64 sm:w-72 sm:h-72 bg-[#d7f7be] rounded-3xl flex items-center justify-center border-4 border-white shadow-md overflow-hidden">
            <img src="/kent.jpg" />
          </div>
        </div>
      </section>

      <section id="about" class="space-y-4">
        <h2 class="text-xs uppercase tracking-widest font-bold text-slate-400">My Philosophy</h2>
        <div class="text-2xl sm:text-3xl font-black text-slate-900">
          Build. Build. Build.
        </div>
      </section>

      <section id="process" class="space-y-6">
        <h2 class="text-2xl font-bold text-slate-900">What I Focus On</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
          <div class="border border-slate-100 bg-slate-50/50 p-6 rounded-2xl space-y-2">
            <span class="text-xs font-bold px-2.5 py-1 bg-[#bcf078] text-slate-900 rounded-full inline-block">01</span>
            <h3 class="font-bold text-lg text-slate-900">Building Solutions</h3>
            <p class="text-slate-600 text-sm">Crafting software applications and web platforms.</p>
          </div>
          <div class="border border-slate-100 bg-slate-50/50 p-6 rounded-2xl space-y-2">
            <span class="text-xs font-bold px-2.5 py-1 bg-[#bcf078] text-slate-900 rounded-full inline-block">02</span>
            <h3 class="font-bold text-lg text-slate-900">Smart Hardware</h3>
            <p class="text-slate-600 text-sm">Exploring IoT devices and embedded systems.</p>
          </div>
          <div class="border border-slate-100 bg-slate-50/50 p-6 rounded-2xl space-y-2">
            <span class="text-xs font-bold px-2.5 py-1 bg-[#bcf078] text-slate-900 rounded-full inline-block">03</span>
            <h3 class="font-bold text-lg text-slate-900">Core Infrastructure</h3>
            <p class="text-slate-600 text-sm">Working with computer networks and databases.</p>
          </div>
          <div class="border border-slate-100 bg-slate-50/50 p-6 rounded-2xl space-y-2">
            <span class="text-xs font-bold px-2.5 py-1 bg-[#bcf078] text-slate-900 rounded-full inline-block">04</span>
            <h3 class="font-bold text-lg text-slate-900">Next-Gen Tech</h3>
            <p class="text-slate-600 text-sm">Diving into artificial intelligence and systems engineering.</p>
          </div>
        </div>
      </section>

      <section id="portfolio" class="space-y-6">
        <h2 class="text-2xl font-bold text-slate-900">Projects & Experience</h2>
        <div class="grid grid-cols-1 sm:grid-cols-3 gap-6">
          <div class="border border-slate-100 bg-white p-6 rounded-2xl shadow-sm space-y-3">
            <span class="text-xs font-semibold text-emerald-600 bg-emerald-50 px-2 py-1 rounded">Project Manager</span>
            <h3 class="font-bold text-slate-900">Sangguniang Kabataan Record Management System</h3>
          </div>
          <div class="border border-slate-100 bg-white p-6 rounded-2xl shadow-sm space-y-3">
            <span class="text-xs font-semibold text-emerald-600 bg-emerald-50 px-2 py-1 rounded">Quality Assurance</span>
            <h3 class="font-bold text-slate-900">Tapat Kalusugan: Barangay Children Vaccination & Appointment System</h3>
          </div>
          <div class="border border-slate-100 bg-white p-6 rounded-2xl shadow-sm space-y-3">
            <span class="text-xs font-semibold text-emerald-600 bg-emerald-50 px-2 py-1 rounded">Co-author</span>
            <h3 class="font-bold text-slate-900">Waveldec: An Automatic Water Tank Monitoring System</h3>
          </div>
        </div>
      </section>

      <section id="skills" class="space-y-6">
        <h2 class="text-2xl font-bold text-slate-900">Skills & Expertise</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6 text-sm">
          <div class="space-y-4 border border-slate-100 bg-slate-50/30 p-6 rounded-2xl">
            <div>
              <strong class="text-slate-900 block mb-1">Languages</strong>
              <p class="text-slate-600">Filipino, English</p>
            </div>
            <div>
              <strong class="text-slate-900 block mb-1">Programming</strong>
              <p class="text-slate-600">C, C++, Python, JAVA</p>
            </div>
            <div>
              <strong class="text-slate-900 block mb-1">Software & Tools</strong>
              <p class="text-slate-600">Microsoft Office, AutoCAD, Modelsim, Multisim, KiCad, Canva</p>
            </div>
          </div>

          <div class="space-y-4 border border-slate-100 bg-slate-50/30 p-6 rounded-2xl">
            <div>
              <strong class="text-slate-900 block mb-1">Hardware & Technical Skills</strong>
              <p class="text-slate-600">Basic circuit design and troubleshooting, Microcontroller programming (Arduino), PCB design, Logic simulation and testing</p>
            </div>
            <div>
              <strong class="text-slate-900 block mb-1">Soft Skills</strong>
              <p class="text-slate-600">Strong written and verbal communication, Highly organized and efficient, Proven leadership and team motivation</p>
            </div>
          </div>
        </div>
      </section>

      <footer id="contact" class="border-t border-slate-100 pt-8 flex flex-col sm:flex-row justify-between items-start sm:items-center gap-6">
        <div class="space-y-1">
          <h2 class="text-xl font-bold text-slate-900">Kent Heinz Vinson U. Peralta</h2>
          <p class="text-slate-500 text-sm">Caggay Tuguegarao City 3500</p>
          <p class="text-slate-500 text-sm">📱 09057513099</p>
          <p class="text-slate-500 text-sm">✉️ <a href="mailto:peraltakentheinzvinson@gmail.com" class="hover:underline text-slate-700">peraltakentheinzvinson@gmail.com</a></p>
        </div>

        <div class="space-y-2">
          <span class="text-xs uppercase font-bold tracking-wider text-slate-400 block">Socials</span>
          <a
              href="https://www.linkedin.com/in/kent-heinz-vinson-peralta-733003313"
              target="_blank"
              rel="noopener"
              class="inline-flex items-center space-x-2 text-sm font-medium text-slate-700 hover:text-black bg-slate-50 border border-slate-200 px-4 py-2 rounded-xl transition"
          >
            <span>LinkedIn Profile</span>
          </a>
        </div>
      </footer>

    </div>
  </div>
</template>

<style scoped>
</style>