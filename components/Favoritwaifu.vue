<template>
  
 
  <section class="bg-transparent" id="favorite-characters">
    <div class="container mx-auto py-8">
      <h2 class="text-3xl font-semibold text-center mb-8">Favorite Waifu Category</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 text-center">
        <div 
          data-aos="flip-right" 
          v-for="(character, index) in characters" 
          :key="index" 
          class="glass-effect p-6 text-white cursor-pointer" 
          @click="selectCharacter(character)"
        >
          <img :src="character.image" alt="" class="w-220 h-340 mx-auto object-cover mb-4" />
          <h3 class="text-xl font-semibold mb-2">{{ character.name }}</h3>
          <p class="mb-4">{{ character.description }}</p>
        </div>
      </div>
    </div>

    <!-- Modal -->
    <div v-if="selectedCharacter" class="fixed inset-0 bg-gray-900 bg-opacity-75 flex justify-center items-center">
      <div class="bg-transparent p-6 rounded-lg max-w-lg mx-auto text-black glass-effect ">
        <h3 class="text-2xl text-white font-semibold mb-4">{{ selectedCharacter.name }}</h3>
        <img :src="selectedCharacter.img" alt="" class="w-full h-40 object-cover rounded-lg mb-4" />
        <p class="mb-4 text-white">{{ selectedCharacter.details }}</p>
        <button class="bg-red-500 text-white px-4 py-2 rounded-lg" @click="selectedCharacter = null">Close</button>
      </div>
    </div>
  </section>




</template>

<script>
export default {
  name: 'FavoriteCharactersSection',
  data() {
    return {
      characters: [
        {
          name: 'Kamisato Ayaka',
          description: 'Choose the Waifus, the Prettier there are.',
              image: 'https://cdn.discordapp.com/attachments/1258095681491697704/1258095723367370752/Heron27s_Invitation_Ayaka_3.webp?ex=6686cc72&is=66857af2&hm=aef9e0dffde06f88ea1aaf5137d2de26c5948d8d73db153ab785773641150771&',
          img: 'https://cdn.discordapp.com/attachments/1258095681491697704/1258099815724880024/Kamisato_Ayaka_Wish.webp?ex=6686d042&is=66857ec2&hm=b0e7cd3d8c37da9cf37bcb6bb59bbc49594bb179d0c0fa98cad5f21dda4938c0&',
          details: 'Kamisato Ayaka is a playable Cryo character in Genshin Impact.She is in charge of the internal and external affairs of the Kamisato Clan and is the younger sister of Kamisato Ayato. Beautiful, dignified, and noble, Ayaka has earned the title Shirasagi Himegimi and is considered a model of perfection in Inazuma.',
        },
        {
          name: 'Mahouka',
          description: 'An anime series abaut magical scholl and psyco war.',
          
            image: 'https://cdn.discordapp.com/attachments/1258095681491697704/1258151895021654108/Mahouka-Koukou-no-Rettousei_title_1.png?ex=668700c3&is=6685af43&hm=1655bfaa5c7be437a9ffb9b60f1f0cbe668c8d4882289f80d5ba790eef075744&',
          img:'https://cdn.discordapp.com/attachments/1258095681491697704/1258148993431506954/Charactersmahouka.webp?ex=6686fe0f&is=6685ac8f&hm=00782da7f36e108cb1dd20ecd825ce6c67648103a375fb34a0e2ce84dfd2fd30&',
          details: 'Mahouka Koukou no Rettousei (魔法科高校の劣等生), literally "The Poor Performing Student of a Magic High School", and also known officially as "The Irregular At Magic High School", is a Japanese light novel series written by Sato Tsutomu (佐島勤), with illustrations by Ishida Kana (石田可奈), published by ASCII Media Works under their Dengeki Bunko label.',
          
        },
        {
          name: 'Shiba Miyuki',
          description: 'Pick the most stylish witch hats Studios out there.',
          image: 'https://cdn.discordapp.com/attachments/1258095681491697704/1258151562627256340/OieMahouka28a_1.webp?ex=66870073&is=6685aef3&hm=e9c98c08a80197c12005a0deee16e841bfe5dba3c7dc669b46eb95239a668e90&',
          details: 'Details about Studios category.',
        },
      ],
      selectedCharacter: null,
    };
  },
  methods: {
    selectCharacter(character) {
      this.selectedCharacter = character;
    },
  },
};
</script>


<style scoped>
#favorite-characters {
  padding: 50px 0;
}

.glass-effect {
  background: rgba(255, 255, 255, 0.2);
  backdrop-filter: blur(10px);
  border-radius: 1rem;
  padding: 1.5rem;
}

.no-border {
  border: none;
  outline: none;
  background-color: transparent;
}
.fixed {
  position: fixed;
}

.inset-0 {
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}
</style>
