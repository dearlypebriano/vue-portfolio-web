<script setup>
import DefaultCounterCard from "../../../examples/cards/counterCards/DefaultCounterCard.vue";
</script>

<template>
  <section class="pt-3 pb-4" id="count-stats">
    <div class="container">
      <div class="row">
        <div class="col-lg-9 z-index-2 border-radius-xl mx-auto py-3">
          <div class="row">
            <div class="col-md-4 position-relative">
              <DefaultCounterCard
                color="success"
                title="Web Developers"
                description="Sudah 3 Tahun saya mendalami untuk melakukan pengembangan menjadi Web Developers, dan saya berhasil membangun website Portfolio saya sendiri secara Full Stack dengan menggunakan Framework Vue Js dan Laravel"
                :count="1"
                suffix=" Tahun"
                :duration="3000"
                divider="vertical"
              />
            </div>
            <div class="col-md-4 position-relative">
              <DefaultCounterCard
                color="success"
                title="Software Engineer"
                description="Saya sudah cukup mendalami tentang pengembangan Software, dan saya berhasil membuat
                Software yaitu, Software Kasir sederhana, yang dibangun menggunakan CPP / C++ dan Java"
                :count="3"
                suffix=" Tahun"
                :duration="3000"
                divider="vertical"
              />
            </div>
            <div class="col-md-4">
              <DefaultCounterCard
                color="success"
                title="Pengembangan Logic"
                description="Selama 4 tahun saya mempelajari Website Dan Software, saya lebih berfokus kepada Logic yang ada
                pada Website maupun Software tersebut, biasa disebut sebagai Back End"
                :count="1460"
                suffix=" Hari"
                :duration="20000"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
