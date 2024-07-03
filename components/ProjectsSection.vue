<template>
  <section  class=" bg-transparent ">
    <div class="container mx-auto py-8">
    <h2 class="text-3xl font-semibold text-center mb-8">My project </h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
      <div v-for="(project, index) in projects" :key="index" class="glass-effect p-6 text-white">
        <img :src="project.image" alt="" class="w-full h-40 object-cover rounded-lg mb-4" />
        <h3 class="text-xl font-semibold mb-2">{{ project.title }}</h3>
        <p class="mb-4">{{ project.description }}</p>
        <button class="bg-blue-500 text-white px-4 py-2 rounded-lg">Learn More</button>
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
          description: 'Ut pretium ultricies dignissim. Sed sit amet mi eget urna placerat vulputate.',
          image: 'https://via.placeholder.com/400x300',
        },
        {
          title: 'Waifus Marketplace',
          description: 'Suspendisse in volutpat massa. Nulla facilisi.',
          image: 'https://via.placeholder.com/400x300',
        },
        {
          title: 'Discord Indomie Bot',
          description: 'Curabitur tristique, mi a mollis sagittis.',
          image: 'https://via.placeholder.com/400x300',
        },
        {
          title: 'Road to Radiant',
          description: 'Curabitur tristique, mi a mollis sagittis.',
          image: 'https://via.placeholder.com/400x300',
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
