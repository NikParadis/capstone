<template>
  <article class="mt-10 md:mt-6 mx-auto mb-4 p-8 md:p-20 max-w-4xl">
    <nuxt-link class="text-lg hover:underline" to="/blog">&#8592; back to posts</nuxt-link>
    <h1 class="text-4xl font-semibold leading-tight mt-2">{{ article.title }}</h1>
    <p class="text-gray-700 mb-2">Written by {{article.author}} </br> {{ article.date }}</p>
     <div class="h-56 my-4">
              <img
                class="object-cover object-center rounded-md h-full w-full"
                :src="article.img"
              />
            </div>
    <nuxt-content class="leading-relaxed list-decimal" :document="article" />
    <prev-next class="mt-4 text-xl" :prev="prev" :next="next" />
  </article>
</template>


 <style lang="postcss">
.nuxt-content h2 {
  font-weight: 600;
  font-size: 28px;
}
.nuxt-content h3 {
  font-weight: bold;
  font-size: 22px;
}
.nuxt-content p {
  margin-bottom: 20px;
  font-size: 22px;
}
ol {
  @apply .list-decimal;
  @apply text-xl;
  @apply list-inside;
  @apply ml-2;
  @apply mb-4;
}
li {
  @apply mb-2;
}
article {
  margin-top: 8rem;
}
</style>
   
<script>
export default {
  async asyncData({ $content, params }) {
    // fetch our article here
    const article = await $content("articles", params.slug).fetch();
    console.log(article);
    const [prev, next] = await $content("articles")
      .only(["title", "slug", "img"])
      .sortBy("createdAt", "asc")
      .surround(params.slug)
      .fetch();

    return { article, prev, next };
  },
  

  methods: {
    formatDate(date) {
      const options = { year: "numeric", month: "long", day: "numeric" };
      return new Date(date).toLocaleDateString("en", options);
    }
  },
    transition: "fade"

};
</script>