<template>
  <div id="home">
    <articles>
      <banner />
    </articles>
    <whynatural />
    <about />
    <bestseller />
    <spnf />
    <subscribe />
    <testi />

    <!--<social />-->
  </div>
</template>

<script>
  export default {
    name: 'Home',

    components: {
      bestseller: () =>import('@/components/home/bestseller'),
      About: () => import('@/components/home/About'),
      Articles: () => import('@/components/home/Articles'),
      Banner: () => import('@/components/home/Banner'),
      Social: () => import('@/components/home/Social'),
      Subscribe: () => import('@/components/home/Subscribe'),
      whynatural: () => import('@/components/home/whynatural'),
      spnf: () => import('@/components/home/spnf'),
      testi: () => import('@/components/home/testi'),
    },
  }
</script>
