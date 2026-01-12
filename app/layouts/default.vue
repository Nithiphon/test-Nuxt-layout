<template>
  <div>
    <!-- Navbar -->
    
     <nav class=" hero navbar navbar-expand-lg  bg-dark ">
        <div class="container">
          <div class=" text-hero rounded-3">
            <h2 class="text-white fw-bold"> เว็บไซต์แนะนำสถานที่ท่องเที่ยว</h2>
            <p class="text-white fw-light">เว็บไซต์ทดสอบ สร้างขึ้นเพื่อทดสอบ layout</p>
          </div>
       <div class="d-flex gap-3 fs-5">
          <NuxtLink to="/" class="text-white text-decoration-none mx-3">หน้าแรก</NuxtLink>
           <NuxtLink to="/about" class="text-white text-decoration-none mx-3">เกี่ยวกับเรา</NuxtLink>
       </div>
        </div>
     </nav>
    
    
   
   
    <main class="pt-2 m-5">
      <NuxtPage />
    </main>

    <!-- Footer -->
  <div class="bg-dark text-white pt-3 pb-3">
    <footer class="text-center">
      <p>@ 2026 testwebsite</p>
    </footer>
    </div>
  </div>
</template>

<style scoped>

  .hero{
    background-color:#3366FF;
  }
  </style>

<script setup>
  useHead({
    link: [
      {
      rel: "stylesheet",
      href: "https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
      }
    ],
    script: [
      {
        src: "https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
      }
    ]
  })
</script>