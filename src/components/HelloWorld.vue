<template>
  <img class="h-10 w-10 rounded-full" src="../assets/shannon_nyc.jpg" alt="" />
  <ul class="divide-y divide-gray-200">
    <li v-for="person in people" :key="person.email" class="py-4 flex">
      
      <div class="ml-3">
        <p class="text-sm font-medium text-gray-900">{{ person.name }}</p>
        <p class="text-sm text-gray-500">{{ person.email }}</p>
      </div>
    </li>
  </ul>
</template>

<script>
const people = [
  {
    name: 'Todd Whitten',
    email: 'todd.ryan.whitten@gmail.com'
  },
]

export default {
  setup() {
    return {
      people,
    }
  },
}
</script>



<!-- <template>
  <img src="../assets/shannon_nyc.jpg" />
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script> -->
