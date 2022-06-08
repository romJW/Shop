<template>
  <link href="https://fonts.googleapis.com/css?family=Allison:regular" rel="stylesheet" />
  <link
    href="https://fonts.googleapis.com/css?family=Montserrat:100,200,300,regular,500,600,700,800,900,100italic,200italic,300italic,italic,500italic,600italic,700italic,800italic,900italic"
    rel="stylesheet"
  />
  <link
    href="https://fonts.googleapis.com/css?family=Playfair+Display:regular,500,600,700,800,900,italic,500italic,600italic,700italic,800italic,900italic"
    rel="stylesheet"
  />
  <Header class="mb-[160px]" />
  <Tour class="mb-[160px]" /> 
  <Form class="mb-[160px]" />
  <FeedBack class="mr-[300px] mb-[104px]" />
  <Footer />
</template>

<script>
import Header from './components/Header';
import './assets/tailwind.css';
import Tour from './components/Tour';
import Form from './components/Form';
import FeedBack from './components/FeedBack';
import Footer from './components/Footer';
export default {
  components: {
    Header,
    Tour,
    Form,
    FeedBack,
    Footer
    
  },
};

</script>

<style></style>
