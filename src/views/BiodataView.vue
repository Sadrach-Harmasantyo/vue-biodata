<script setup lang="ts">
// You can add any imports or logic here
</script>

<template>
  <div class="max-w-4xl mx-auto p-8 font-sans bg-white rounded-lg shadow-md">
    <div class="flex flex-col md:flex-row items-center gap-8 mb-8">
      <div class="w-48 h-48">
        <!-- Replace with your actual image path -->
        <img 
          src="../assets/profile_photo.png" 
          alt="Profile Photo" 
          class="w-full h-full object-cover rounded-full border-4 border-emerald-600"
        />
      </div>
      <div class="text-center md:text-left">
        <h1 class="text-3xl font-bold text-gray-800 mt-0">Sadrach Harmasantyo</h1>
        <p class="text-xl text-gray-600 mb-4">Information Systems Student</p>
        <p class="flex items-center justify-center md:justify-start gap-2 my-2 text-gray-600">
          <span class="w-5 h-5 inline-block bg-vue-green rounded-full items-center justify-center text-white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-emerald-600" viewBox="0 0 20 20" fill="currentColor">
              <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z" />
              <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z" />
            </svg>
          </span> 
          harmasantyosadrach@gmail.com
        </p>
        <p class="flex items-center justify-center md:justify-start gap-2 my-2 text-gray-600">
          <span class="w-5 h-5 inline-block bg-vue-green rounded-full items-center justify-center text-white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-emerald-600" viewBox="0 0 20 20" fill="currentColor">
              <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z" />
            </svg>
          </span> 
          08123456789
        </p>
        <p class="flex items-center justify-center md:justify-start gap-2 my-2 text-gray-600">
          <span class="w-5 h-5 inline-block bg-vue-green rounded-full items-center justify-center text-white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-emerald-600" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd" />
            </svg>
          </span> 
          Malang City
        </p>
        <div class="flex flex-wrap justify-center md:justify-start gap-3 mt-4">
          <a href="https://linkedin.com/in/sadrach-harmasantyo" target="_blank" class="text-blue-600 hover:text-blue-800 flex items-center gap-1">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
              <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/>
            </svg>
            LinkedIn
          </a>
          <a href="https://github.com/Sadrach-Harmasantyo" target="_blank" class="text-gray-800 hover:text-gray-600 flex items-center gap-1">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
              <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
            </svg>
            GitHub
          </a>
          <a href="https://sadrach-harmasantyo.vercel.app" target="_blank" class="text-purple-600 hover:text-purple-800 flex items-center gap-1">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
              <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm1 16.057v-3.057h2.994c-.059 1.143-.212 2.24-.456 3.279-.823-.12-1.674-.188-2.538-.222zm1.957 2.162c-.499 1.33-1.159 2.497-1.957 3.456v-3.62c.666.028 1.319.081 1.957.164zm-1.957-7.219v-3.015c.868-.034 1.721-.103 2.548-.224.238 1.027.389 2.111.446 3.239h-2.994zm0-5.014v-3.661c.806.969 1.471 2.15 1.971 3.496-.642.084-1.3.137-1.971.165zm2.703-3.267c1.237.496 2.354 1.228 3.29 2.146-.642.234-1.311.442-2.019.607-.344-.992-.775-1.91-1.271-2.753zm-7.241 13.56c-.244-1.039-.398-2.136-.456-3.279h2.994v3.057c-.865.034-1.714.102-2.538.222zm2.538 1.776v3.62c-.798-.959-1.458-2.126-1.957-3.456.638-.083 1.291-.136 1.957-.164zm-2.994-7.055c.057-1.128.207-2.212.446-3.239.827.121 1.68.19 2.548.224v3.015h-2.994zm1.024-5.179c.5-1.346 1.165-2.527 1.97-3.496v3.661c-.671-.028-1.329-.081-1.97-.165zm-2.005-.35c-.708-.165-1.377-.373-2.018-.607.937-.918 2.053-1.65 3.29-2.146-.496.844-.927 1.762-1.272 2.753zm-.549 1.918c-.264 1.151-.434 2.36-.492 3.611h-3.933c.165-1.658.739-3.197 1.617-4.518.88.361 1.816.67 2.808.907zm.009 9.262c-.988.236-1.92.542-2.797.9-.89-1.328-1.471-2.879-1.637-4.551h3.934c.058 1.265.231 2.488.5 3.651zm.553 1.917c.342.976.768 1.881 1.257 2.712-1.223-.49-2.326-1.211-3.256-2.115.636-.229 1.299-.435 1.999-.597zm9.924 0c.7.163 1.362.367 1.999.597-.931.903-2.034 1.625-3.257 2.116.489-.832.915-1.737 1.258-2.713zm.553-1.917c.27-1.163.442-2.386.501-3.651h3.934c-.167 1.672-.748 3.223-1.638 4.551-.877-.358-1.81-.664-2.797-.9zm.501-5.651c-.058-1.251-.229-2.46-.492-3.611.992-.237 1.929-.546 2.809-.907.877 1.321 1.451 2.86 1.616 4.518h-3.933z"/>
            </svg>
            Portfolio
          </a>
        </div>
      </div>
    </div>

    <div class="mb-8">
      <h2 class="text-2xl font-medium text-gray-800 border-b border-gray-300 pb-2 mb-4">About Me</h2>
      <p class="text-gray-600 text-justify">
        I am a motivated sixth-semester Information Systems student at Brawijaya University with expertise in full-stack web development. I have a
        strong foundation in HTML, CSS, and JavaScript and specialize in front-end technologies such as ReactJS, Next.js, Vue.js, TypeScript, and
        TailwindCSS. Additionally, I am proficient in backend development using PHP, Laravel, and MySQL. I am continuously honing my skills through
        hands-on projects to build efficient and scalable web applications. My goal is to become a well-rounded developer capable of delivering end-to-end solutions.
      </p>
    </div>

    <div class="mb-8">
      <h2 class="text-2xl font-medium text-gray-800 border-b border-gray-300 pb-2 mb-4">Education</h2>
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Information System</h3>
        <p class="italic text-gray-600 my-1">Aug 2022 - Present</p>
        <p class="italic text-gray-600 my-1">Brawijaya University</p>
        <p class="text-gray-600 font-medium">GPA: 3.95 / 4.0</p>
        <p class="text-gray-600 mt-2">Achieved a GPA of 3.95 during six semesters at Brawijaya University, with a focus on computer science and business concepts.</p>
        <p class="text-gray-600 mt-2">Actively participated in the following organizations:</p>
        <ul class="list-disc pl-5 text-gray-600 mt-1">
          <li>KBMDSI: Contributed as a Frontend Web Developer in the Information and Technology Development Division.</li>
          <li>POROS: Served as a member of the Frontend Web and Internal Division.</li>
          <li>RAION: Worked as a Programmer for Apps and Internal Division projects.</li>
        </ul>
        <p class="text-gray-600 mt-2">Developed and strengthened skills in technical development, teamwork, and leadership through these organizational roles.</p>
      </div>
      
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Science</h3>
        <p class="italic text-gray-600 my-1">Jul 2019 - Jun 2022</p>
        <p class="italic text-gray-600 my-1">Saint Joseph College Senior High School</p>
        <p class="text-gray-600 font-medium">GPA: 90</p>
      </div>
    </div>

    <div class="mb-8">
      <h2 class="text-2xl font-medium text-gray-800 border-b border-gray-300 pb-2 mb-4 text-justify">Work Experience</h2>

      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Fullstack Web Developer</h3>
        <p class="italic text-gray-600 my-1">Feb 2024 – April 2025</p>
        <p class="italic text-gray-600 my-1">Information System Laboratory, FILKOM Brawijaya University</p>
        <p class="text-gray-600 mt-1">
            Led the development of a web-based attendance and logbook system tailored for student employees, streamlining daily reporting and task tracking. Additionally, designed and built an e-commerce platform to support local SMEs (UMKM), enhancing their digital presence and sales reach.
        </p>
        <ul class="list-disc pl-5 text-gray-600 mt-2">
            <li>Engineered user-friendly, scalable web applications using Laravel, Livewire, and TailwindCSS.</li>
            <li>Focused on creating seamless user experiences and responsive design for both internal tools and public-facing platforms.</li>
        </ul>
      </div>

      
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Frontend Web Developer</h3>
        <p class="italic text-gray-600 my-1">Feb 2024 - Dec 2024</p>
        <p class="italic text-gray-600 my-1">POROS (Organization Of Open Source) Brawijaya University</p>
        <p class="text-gray-600 mt-1">Develop and enhance the organization's website interface. Build robust, scalable, and dynamic user interfaces to improve overall user experience.</p>
        <ul class="list-disc pl-5 text-gray-600 mt-2">
          <li>Utilized Next.js, TypeScript and TailwindCSS for modern web development.</li>
        </ul>
      </div>
      
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Frontend Web Developer</h3>
        <p class="italic text-gray-600 my-1">Feb 2024 - Dec 2024</p>
        <p class="italic text-gray-600 my-1">KBMDSI (Keluarga Besar Mahasiswa Sistem Informasi) Brawijaya University</p>
        <ul class="list-disc pl-5 text-gray-600 mt-2">
          <li>Design and implement user-friendly interfaces for the department's website. Utilize ReactJS, JavaScript, and Framer Motion to create engaging and interactive web experiences. Ensure usability and accessibility of the website.</li>
          <li>Work closely with team members to gather requirements and deliver a seamless user experience. Align development efforts with the organization's goals and vision.</li>
        </ul>
      </div>
      
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Programmer Apps</h3>
        <p class="italic text-gray-600 my-1">Feb 2023 - Dec 2024</p>
        <p class="italic text-gray-600 my-1">Raion Community Brawijaya University</p>
        <ul class="list-disc pl-5 text-gray-600 mt-2">
          <li>Develop Android applications using Kotlin and Firebase. Enhance mobile app development skills through designing, building user-friendly applications.</li>
          <li>Collaborate with team members to gather requirements, implement features, and ensure the applications meet user needs. Adhere to best practices in coding and software development. Focus on ensuring application performance, usability, and security.</li>
        </ul>
      </div>
      
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Deputy In Charge Raion Upgrading Event</h3>
        <p class="italic text-gray-600 my-1">Nov 2024</p>
        <p class="italic text-gray-600 my-1">Raion Community Brawijaya University</p>
        <p class="text-gray-600 mt-1">Organized, managed, and coordinated committees for internal events within the Raion community to foster self-development and enhance organizational knowledge.</p>
      </div>

      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Consumption and Health Committee</h3>
        <p class="italic text-gray-600 my-1">Nov 2023</p>
        <p class="italic text-gray-600 my-1">BIOS (Badan Internal Olahraga dan Seni) Brawijaya University</p>
        <p class="text-gray-600 mt-1">Provided adequate catering and ensured participants' safety by offering first aid supplies, preventing serious injuries and promoting a wellrounded event experience.</p>
      </div>

      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Equipment Committee Raion Academy Event</h3>
        <p class="italic text-gray-600 my-1">Oct 2023</p>
        <p class="italic text-gray-600 my-1">Raion Community Brawijaya University</p>
        <p class="text-gray-600 mt-1">Ensured the availability and quality of all event equipment, making certain that everything was complete and ready for use to support a smooth and successful event experience.</p>
      </div>
    
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Public Relation Committee Raion Insight Event</h3>
        <p class="italic text-gray-600 my-1">Sep 2023</p>
        <p class="italic text-gray-600 my-1">Raion Community Brawijaya University</p>
        <p class="text-gray-600 mt-1">Communicated important information to participants regarding events, ensuring clear and effective dissemination of details to enhance engagement and preparedness.</p>
      </div>
        
    </div>

    <div class="mb-8">
      <h2 class="text-2xl font-medium text-gray-800 border-b border-gray-300 pb-2 mb-4">Skills</h2>
      <p class="text-gray-600 mb-3">Web Development Tech Stacks:</p>
      <div class="flex flex-wrap gap-3">
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">HTML</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">CSS</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">JavaScript</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">ReactJS</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">NextJS</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">VueJS</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">TypeScript</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">PHP</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">Laravel</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">TailwindCSS</div>
        <div class="bg-emerald-600 text-white bg-opacity-10 px-4 py-2 rounded-full text-sm font-medium">MySQL</div>
      </div>
    </div>
    
    <div class="mb-8">
      <h2 class="text-2xl font-medium text-gray-800 border-b border-gray-300 pb-2 mb-4">Projects</h2>
      
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Rent Office Website</h3>
        <p class="italic text-gray-600 my-1">Jan 2025 - Feb 2025</p>
        <p class="text-gray-600 mt-1"><strong>Objective:</strong> Develop a Rent Office Website that allows users to search for office spaces, make bookings, and receive real-time notifications, ensuring a seamless rental experience.</p>
        <p class="text-gray-600 mt-2"><strong>Features:</strong></p>
        <ul class="list-disc pl-5 text-gray-600 mt-1">
          <li>Office Search & Booking – Users can easily find and book office spaces.</li>
          <li>Manual Payment Integration – Supports offline/manual payment processing.</li>
          <li>SMS/WhatsApp Notifications – Real-time updates via Twilio.</li>
          <li>Admin Dashboard – Built with FilamentPHP for managing offices, transactions, and city listings.</li>
          <li>Secure API Endpoints – Custom API keys and CORS protection for security.</li>
        </ul>
        <p class="text-gray-600 mt-2"><strong>Tech Stack:</strong> Laravel 11, ReactJS, FilamentPHP, MySQL, Twilio API</p>
      </div>
      
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Online Course Website</h3>
        <p class="italic text-gray-600 my-1">Jan 2025 - Jan 2025</p>
        <p class="text-gray-600 mt-1"><strong>Objective:</strong> Develop a full-featured Online Course Platform that allows students to enroll in courses, while providing teachers and admins with tools for efficient course and user management.</p>
        <p class="text-gray-600 mt-2"><strong>Features:</strong></p>
        <ul class="list-disc pl-5 text-gray-600 mt-1">
          <li>Role-Based Access Control – Secure user roles for students, teachers, and admins using Laravel 11, Breeze, and Spatie Permission.</li>
          <li>Subscription-Based Model – Students can subscribe and enroll in premium courses.</li>
          <li>Comprehensive CMS – Teachers and admins can manage courses, users, and payments efficiently.</li>
          <li>Modern UI/UX – Fully responsive design with Tailwind CSS.</li>
          <li>Secure Authentication – Includes login, registration, and user management.</li>
        </ul>
        <p class="text-gray-600 mt-2"><strong>Tech Stack:</strong> Laravel 11, Tailwind CSS, Blade Template, Breeze, Spatie Permission, MySQL</p>
      </div>
      
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">POROS Website</h3>
        <p class="italic text-gray-600 my-1">Sep 2024 - Nov 2024</p>
        <p class="text-gray-600 mt-1"><strong>Role:</strong> Front-End Web Developer for the POROS organization at Brawijaya University.</p>
        <p class="text-gray-600 mt-2"><strong>Responsibilities:</strong> Develop and enhance the organization's website interface. Also, build robust, scalable, and dynamic user interfaces to improve overall user experience. Worked closely with team members to aligned with the organization's goals and vision.</p>
        <p class="text-gray-600 mt-2"><strong>Tech Stack:</strong> Utilized Next.js, TypeScript and TailwindCSS for modern web development.</p>
      </div>
      
      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">KBMDSI Website</h3>
        <p class="italic text-gray-600 my-1">Mar 2024 - Sep 2024</p>
        <p class="text-gray-600 mt-1"><strong>Role:</strong> Front-End Web Developer</p>
        <p class="text-gray-600 mt-2"><strong>Responsibilities:</strong> Design and implement user-friendly interfaces for the department's website. Utilize ReactJS, JavaScript, and Framer Motion to create engaging and interactive web experiences.</p>
        <p class="text-gray-600 mt-2"><strong>Tech Stack:</strong> ReactJS, JavaScript, Framer Motion, Tailwind CSS</p>
      </div>

      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Pokemon Website</h3>
        <p class="italic text-gray-600 my-1">Jan 2024 - Feb 2024</p>
        <p class="text-gray-600 mt-1"><strong>Objective:</strong> Designed and developed a Pokémon-themed website to enhance expertise in modern front-end development.</p>
        <p class="text-gray-600 mt-2"><strong>Features:</strong> Implemented a search functionality to allow users to find specific Pokémon, Built a seamless pagination system to browse through Pokémon data efficiently, Added skeleton loaders to enhance user experience during data fetching.</p>
        <p class="text-gray-600 mt-2"><strong>Tech Stack:</strong> React Vite, JavaScript, PokeAPI V2, Axios, TailwindCSS, and Redux.</p>
      </div>

      <div class="mb-6">
        <h3 class="text-xl font-medium text-gray-800 mb-1">Gym Exercise Website</h3>
        <p class="italic text-gray-600 my-1">Dec 2023 - Jan 2024</p>
        <p class="text-gray-600 mt-1"><strong>Objective:</strong> Designed and developed a Gym Exercise website to enhance skills in modern front-end development.</p>
        <p class="text-gray-600 mt-2"><strong>Features:</strong> Implemented a search functionality to allow users to find exercise, Displayed exercises with similar muscle groups and provided tailored recommendations for an enhanced workout experience.</p>
        <p class="text-gray-600 mt-2"><strong>Tech Stack:</strong> Utilized ReactJS, MaterialUI, and RapidAPI.</p>
      </div>

    </div>

    <div class="mb-8">
        <h2 class="text-2xl font-medium text-gray-800 border-b border-gray-300 pb-2 mb-4">Certifications</h2>

        <div class="mb-4 flex justify-between">
            <h3 class="text-lg font-medium text-gray-800 mb-1">Belajar Membuat Aplikasi Web dengan React</h3>
            <p class="italic text-gray-600 my-1">Sep 2024</p>
        </div>

        <div class="mb-4 flex justify-between">
            <h3 class="text-lg font-medium text-gray-800 mb-1"> Belajar Membuat Front-End Web untuk Pemula by Dicoding Indonesia</h3>
            <p class="italic text-gray-600 my-1">Oct 2023</p>
        </div>

        <div class="mb-4 flex justify-between">
            <h3 class="text-lg font-medium text-gray-800 mb-1">Belajar Dasar Pemrograman JavaScript by Dicoding Indonesia</h3>
            <p class="italic text-gray-600 my-1">Sep 2023</p>
        </div>

        <div class="mb-4 flex justify-between">
            <h3 class="text-lg font-medium text-gray-800 mb-1">Belajar Dasar Pemrograman Web by Dicoding Indonesia</h3>
            <p class="italic text-gray-600 my-1">Sep 2023</p>
        </div>
    
    </div>
  </div>
</template>