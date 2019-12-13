<template>
  <section class="books">
    <Book
      thumbnail="https://lr-assets.storage.googleapis.com/kids/covers/_hires_imported/9781906230012.jpg"
      title="The Great Expectation"
      previewText="A great book" />

      <Book
      thumbnail="https://images-na.ssl-images-amazon.com/images/I/81RxHgynh6L.jpg"
      title="We are all Grata"
      previewText="Environements" />
  </section>
</template>

<script>
import Book from '@/components/Book'
export default {
  components: {
    Book
  }
}
</script>

<style scoped>
.books {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
}
</style>
