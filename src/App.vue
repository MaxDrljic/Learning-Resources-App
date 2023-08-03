<template>
    <ul></ul>
</template>

<script>
export default {
    data() {
        return {
            storedResources: [
                {
                    id: "official-guide", 
                    title: "Official Guide",
                    description: "The official Vue.js documentation.",
                    link: "https://vuejs.org/guide/introduction.html"
                },
                {
                    id: "google", 
                    title: "Google",
                    description: "Learn how to google the right way!",
                    link: "https://www.google.org/"
                }
            ]
        }
    },
};
</script>