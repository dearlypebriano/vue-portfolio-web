<script setup>
import RotatingCard from "../../../examples/cards/rotatingCards/RotatingCard.vue";
import RotatingCardFront from "../../../examples/cards/rotatingCards/RotatingCardFront.vue";
import RotatingCardBack from "../../../examples/cards/rotatingCards/RotatingCardBack.vue";
import DefaultInfoCard from "../../../examples/cards/infoCards/DefaultInfoCard.vue";
</script>
<template>
  <section class="my-5 py-5">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-4 ms-auto me-auto p-lg-4 mt-lg-0 mt-4">
          <RotatingCard>
            <RotatingCardFront
              image="https://images.unsplash.com/photo-1569683795645-b62e50fbf103?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=987&q=80"
              icon="touch_app"
              title="Feel the <br /> Website Portfolio"
              description="Saya menggunakan semua code yang ada pada Bootstrap dan tailwind agar bisa membuat website seperti ini."
            />

            <RotatingCardBack
              image="https://images.unsplash.com/photo-1498889444388-e67ea62c464b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1365&q=80"
              title="Discover Website"
              description="Terimakasih, telah mendatangi website saya, selamat menikmati pemandangan system yang sudah saya buat."
              
            />
          </RotatingCard>
        </div>
        <div class="col-lg-6 ms-auto">
          <div class="row justify-content-start">
            <DefaultInfoCard
              icon="content_copy"
              title="Full Documentation"
              description="Selama pembuatan website dan Software engineer, saya belajar banyak hal mulai dari Problem Solving
              yang berbeda beda setiap projectnya, dan saya juga belajar banyak hal lain."
            />
            <DefaultInfoCard
              icon="flip_to_front"
              title="Bootstrap 5 & Tailwind"
              description="Bootstrap 5 Dan Tailwind adalah salah satu Framework CSS yang bisa membantu anda dalam pengembangan 
              website, khususnya untuk para Front End, sangat cocok jika kurang tau-menau mengenai styling."
            />
          </div>
          <div class="row justify-content-start mt-5">
            <DefaultInfoCard
              class="mt-3"
              icon="price_change"
              title="Save Time & Money"
              description="Membuat design, Tampilan Website, Operasi Website dan lain-lain membutuhkan waktu yang bisa dibilang
              cukup lama dan memakan banyak sekali waktu, akan tetapi perjuangan kita sebagai seorang programmer tidak mudah
              menyerah, kita selalu bisa menghadapi masalah yang ada dan membuat masalah itu menjadi selesai, dengan begitu
              kita bisa mendapatkan uang dengan skill yang kita miliki."
            />
            <DefaultInfoCard
              class="mt-3"
              icon="devices"
              title="Fully Responsive"
              description="Pastinya kalian sudah tidak asing lagi dengan kata Responsive, Responsive adalah ebuah metode atau pendekatan sistem web desain yang bertujuan memberikan pengalaman berselancar yang optimal dalam berbagai perangkat, baik mobile maupun komputer meja."
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
