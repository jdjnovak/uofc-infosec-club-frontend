<template>
  <div class="py-8 text-center w-3/4 mx-auto">
    <br>
    <p class="font-display text-4xl">Resources List</p>
    <div>
      <input type="text" name ="search" placeholder="Search Resources...">
    </div>
    <br>
    <ResourceCategory />
    <!--<ResourcesTableComponent />-->
  </div>
</template>
<style scoped>
  input {
    border-width: 1px;
    border-color: #a0aec0;
    color: #000;
    --placeholder-opacity: 1;
    float: left;
    border-radius: 0.375rem;
    width: 100%;
    padding: 0.5rem;
  }
</style>
<script>
// import ResourcesTableComponent from '@/components/ResourcesTableComponent'
import ResourceCategory from '@/components/ResourceCategory'

export default {
  name: 'Resources',
  components: {
    ResourceCategory
    // ResourcesTableComponent
  }
}
</script>
