<template>
    <section class="post-list">
        <PostPreview 
            id="1"
            thumbnail="https://img.freepik.com/free-photo/tech-devices-and-icons-connected-to-digital-planet-earth_117023-449.jpg?size=626&ext=jpg"
            title="Hello there!"
            previewText="First post"
        />
        <PostPreview 
            id="2"
            thumbnail="https://www.ukrartmedia.com/servers-storage/2017/01/tech1-672x492.jpg"
            title="Hi!"
            previewText="Second post"
        />
        <PostPreview 
            id="3"
            thumbnail="https://thumbs.dreamstime.com/t/%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F-%D1%82%D0%B5%D1%85%D0%BD%D0%BE-%D0%BE%D0%B3%D0%B8%D1%8F-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%B8-%D0%B2-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82%D0%B5-75784736.jpg"
            title="I'm glad to see you!"
            previewText="Third post"
        />
    </section>
</template>

<script>
import PostPreview from "@/components/Posts/PostPreview";

export default {
  components: {
    PostPreview
  }
}
</script>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>