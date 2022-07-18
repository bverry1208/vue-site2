<template>
    <HeaderSection />
    <SliderSection />
    <TextSection />
    <ImageSection />
    <CardSection />
    <BannerSection />
    <Card02Section />
    <FooterSection />
</template>


<script>
import HeaderSection from "./components/HeaderSection.vue";
import SliderSection from "./components/SliderSection.vue";
import TextSection from "./components/TextSection.vue";
import ImageSection from "./components/ImageSection.vue";
import CardSection from "./components/CardSection.vue";
import BannerSection from "./components/BannerSection.vue";
import Card02Section from "./components/Card02Section.vue";
import FooterSection from "./components/FooterSection.vue";

export default {
    name: 'App',
    components: {
        HeaderSection,
        SliderSection,
        TextSection,
        ImageSection,
        CardSection,
        BannerSection,
        Card02Section,
        FooterSection
    }
}


</script>


<style>
@import "./App.css";
</style>