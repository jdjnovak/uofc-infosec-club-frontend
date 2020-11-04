<template>
  <section class="py-8 w-full">
    <div class="shadow overflow-x-auto scrolling-touch rounded border-b border-gray-200">
      <table id="resources" class="min-w-full">
        <thead class="bg-primary text-white">
          <tr>
            <th class="hidden md:table-cell w-1/6 text-center py-3 px-4 uppercase font-semibold text-sm">Category</th>
          </tr>
        </thead>
        <tbody class="bg-gray-100 text-gray-700 font-display">
          <tr class="hidden md:table-cell w-1/6 py-3 px-4">
            <td class="float-left">Title</td>
            <td class="float-right">Description</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>
</template>
<style>
#resources thead {
  /* background-color: #12418f !important; */
  color: #FFF !important;
}
#resources tbody {
  padding-top: 10px;
  padding-bottom: 10px;
}
</style>
<script>
export default {
  name: 'ResourceCategory',
  data () {

  },
  methods: {

  },
  computed: {
  },
  watch: {
  }
}
</script>
