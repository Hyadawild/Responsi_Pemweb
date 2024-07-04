<template>
  <section  class=" bg-transparent " id="project">
    <div class="container mx-auto py-8">
    <h2 class="text-3xl font-semibold text-center mb-8">My project </h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
      <div data-aos="flip-right" v-for="(project, index) in projects" :key="index" class="glass-effect p-6 text-white">
        <img :src="project.image" alt="" class="w-full h-40 object-cover rounded-lg mb-4" />
        <h3 class="text-xl font-semibold mb-2">{{ project.title }}</h3>
        <p class="mb-4">{{ project.description }}</p>
        
      </div>
    </div>
  </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection',
  data() {
    return {
      projects: [
        {
          title: 'Korepi',
          description: 'Sebuah software extensi game untuk game Genshin Impact yang memiliki berbagai fitur intuk meningkakan pengalaman bermain game Genshin Impact. Project ini menggunakan DLL injecting dengan base unity ',
          image: 'https://korepi.com/logo2.svg',
        },
        {
          title: 'Waifus Marketplace',
          description: 'Website untuk merating waifu dalam anime dengan Pure CSS menggunakan mongoDB sebagai database dan ',
          image: 'https://cdn.discordapp.com/attachments/1258095681491697704/1258096362415718420/torino_-_114766733_169.jpg?ex=6686cd0b&is=66857b8b&hm=2235aa8a34fb0d2c4eaaa71c9ba0f9433d0ed34a8f948541ccb51014618bf261&',
        },
        {
          title: 'Discord Indomie Bot',
          description: 'Bot Discord dibuat dengan Typescript dengan framework discord js untuk memudahkan berjalannya server indomie yang memiliki fitur moderation, music playing, entertaiment games, auto prune,dll.',
          image: 'https://cdn.discordapp.com/attachments/1258095681491697704/1258096613490954250/chibi_ayaka__by_emilyyeh_dg1bgh4.jpg?ex=6686cd46&is=66857bc6&hm=36d2b7b870e3ede144daee51cf80f968576cab68e2e8710393a9ac934c4b2196&',
        },
        {
          title: 'Road to Radiant',
          description: 'Slamet Esport goes to radiant peak rank Platinum 3.',
          image: 'https://cdn.discordapp.com/attachments/1258095681491697704/1258101313762492466/Radiant_Rank.webp?ex=6686d1a7&is=66858027&hm=3d2473d2bb2f56edb4278f8804ecc1b1731f1a414eb55b6ef1c6a99e03e229f2&',
        },
       {
         title: 'Wareg Catering',
          description: 'Frontend mobile app dengan react native untuk kebutuhan catering online ditujukan untuk mahasiswa dan perantauan.',
          image: 'https://img.freepik.com/premium-vector/catering-service-logo-vector-isolated-white-background-eps-10_399089-1877.jpg',
        },

      ],
    };
  },
};
</script>

<style scoped>
.projects {
  padding: 50px 0;
  background: #e9ecef;
}

.glass-effect {
  background: rgba(255, 255, 255, 0.2);
  backdrop-filter: blur(10px);
  border-radius: 1rem;
  padding: 1.5rem;
}
</style>
