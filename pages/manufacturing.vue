<template>
  <div>
    <NavOne />
    <PageHeader title="Manufacturing" image="/assets/images/markets.jpg" />
    <Manufacturing />
   
    <div class="border-bottom"></div>
    <Gallery />
    <CallToActionOne />
    <Footer />
  </div>

</template>
<script>
  import NavOne from "../components/NavOne";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import Manufacturing from "../components/Manufacturing";
   import Gallery from "../components/Gallery";
  
  import CallToActionOne from "../components/CallToActionOne";
  export default {
    components: {
      CallToActionOne,
      Gallery,
      Manufacturing,
      Footer,
      PageHeader,
      NavOne
    },
    head(){
      return {
        title: "ADFG | Manufacturing"
      }
    }
  }
</script>
