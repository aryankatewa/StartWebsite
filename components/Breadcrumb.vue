<template>
  <div>
    <v-breadcrumbs :items="items" class="my-4 mx-n7">
      <template v-slot:divider>
        <v-icon color="grey">mdi-greater-than</v-icon>
      </template>
    </v-breadcrumbs>

   
  </div>
</template>

<script>
  export default {
    data: () => ({
      items: [
        {
          text: 'Home',
          disabled: false,
          href: 'breadcrumbs_dashboard',
        },
        {
          text: 'Categories',
          disabled: false,
          href: 'breadcrumbs_link_1',
        },
       {
          text: 'Penne Alfredo',
          disabled: false,
          href: 'breadcrumbs_link_1',
        },
        
      ],
    }),
  }
</script>