<template>
  <ul>
    <li v-for="post in posts" :key="post.id">
      <nuxt-link :to="`/posts/${post.id}`">{{ post.title }} {{ post.id }}</nuxt-link>
    </li>
  </ul>
</template>

<script>
import axios from 'axios'

export default {
  async asyncData() {
    const res = await axios.get('https://jsonplaceholder.typicode.com/posts')
    return { posts: res.data }
  }
}
</script>
