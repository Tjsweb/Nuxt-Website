<template>
    <div>
        <AppHeader />
        <AppHead />
        <AppPortfolio />
        <Nuxt />
        <AboutUs />
        <ContactUs />
        <AppFooter />
        <AppCopyright />
    </div>
</template>

<script>

import AppHeader from '~/components/AppHeader.vue';
import AppHead from '~/components/Inc/AppHead.vue';
import AppFooter from '~/components/Inc/AppFooter.vue';
import AppCopyright from '~/components/Inc/AppCopyright.vue';
import AboutUs from '~/components/Inc/AboutUs.vue';
import ContactUs from '~/components/Inc/ContactUs.vue';
import AppPortfolio from '~/components/Inc/AppPortfolio.vue';

export default {
    name: 'AppDefault',
    components: {
    AppHeader,
    AppHead,
    AppFooter,
    AppCopyright,
    AboutUs,
    ContactUs,
    AppPortfolio
}
}

</script>