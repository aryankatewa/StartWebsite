<template>
  <div>
    <v-breadcrumbs :items="items" divider="-"></v-breadcrumbs>

    
  </div>
</template>
<script>
  export default {
    data: () => ({
      items: [
        {
          text: 'Home',
          disabled: false,
          href: 'breadcrumbs_Home',
        },
        {
          text: 'Continental',
          disabled: false,
          href: 'breadcrumbs_Continental',
        },
        {
          text: 'Penne Alfredo',
          disabled: false,
          href: 'breadcrumbs_Penne Alfredo',
        },
      ],
    }),
  }
</script>