<template>
  <div class="create">
    <form>
        <label for="">Title:</label>
        <input type="text" required>
        <label for="">Content:</label>
        <textarea v-model="body" required></textarea>
        <label>Tags (hit enter to add a tag)</label>
        <input v-model="tag" type="text" name="" id="">
        <button>Add Post</button>
    </form>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>