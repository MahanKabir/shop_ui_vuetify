<template>
<v-app>

    <nuxt/>
    <f></f>

</v-app>

</template>


<script>
import SlideShow from '~/components/slideshow.vue'
import Header from '~/components/header.vue'
import Footer from '~/components/footer.vue'
import CardPage from '~/components/Product/CardPage.vue'
import TabPage from '~/components/Product/TabPage'
import ModalPage from '~/components/Product/ModalPage'
import CarouselsPage from '~/components/Product/CarouselsPage'


export default {
    components:{
        slideshow: SlideShow,
        h: Header,
        f: Footer,
        CardPage: CardPage,
        TabPage:TabPage,
        ModalPage: ModalPage,
        CarouselsPage: CarouselsPage,
    }
}
</script>

