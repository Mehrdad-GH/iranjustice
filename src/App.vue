<template>
  <pageHeader />
  <main class=" mx-auto">
    <Section1 />
    <LastCourse />
    <Aboutus />
    <Section7 />
    <CourseSlider />
    <Contact />
    <FAQ />
    <PageFooter />
  </main>
  
</template>

<script setup>

import pageHeader from "./layouts/pageHeader.vue";
import FAQ from "./layouts/Home/FAQ.vue";
import Section1 from "./layouts/Home/Section1.vue";
import Aboutus from "./layouts/Home/Aboutus.vue";
import Section7 from "./layouts/Home/Section7.vue";
import Contact from "./layouts/Home/contactUs.vue"
import CourseSlider from "./layouts/Home/CourseSlider.vue";
import LastCourse from "./layouts/Home/LastCourse.vue";
import PageFooter from "./layouts/Home/PageFooter.vue";
</script>


