<template>
    <!-- Stat Card -->
    <!-- Description -->
  <q-page class="flex flex-center">
    <section class="text-body1 text-center text-italic text-justify q-pa-xl">
      {{ description }}
    </section>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'IndexPage',
  data() {
    return {
      description: `The Apogee-class vessel is an effective mix of advanced scientific and military technologies, perfect for long-range exploration of hostile space.

The class features an asymmetric design with a large forward section, usually outfitted with long-range tech scanners. Apogee captains are used to operating alone and tend to be an independent, self-reliant lot. 

The ship can hold its own in one-on-one engagements by smart use of its powerful shield emitter and strong engines. However, its armor rating makes it seem somewhat fragile on paper, and thus it is rarely part of big fleet actions.

The high construction costs typically mean that only affluent tech mining consortiums can afford an Apogee-class vessel that is fully outfitted for an aggressive exploratory role.`,
      id: 'apogee',
      name: 'Apogee',
    };
  },
});
</script>
