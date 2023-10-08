<template>
  <img class="h-10 w-10 rounded-full" src="../assets/splash.jpg" alt="" />
  <ul class="divide-y divide-gray-200">
    <li v-for="person in people" :key="person.email" class="py-4 flex">
      <div class="ml-3">
        <p class="text-sm font-medium text-gray-900">
            <a :href="'mailto:' + person.email">
            {{ person.name }}
            </a>
        </p>
        <p class="text-sm text-gray-500"></p>
      </div>
    </li>
  </ul>
</template>

<script>
const people = [
{
    name: 'Todd Ryan Whitten',
    email: 'todd.ryan.whitten@gmail.com',
    phone: "404-333-4670"
  },
  // {
  //   name: 'Will Marsh Whitten',
  //   email: 'will.marsh.whitten@gmail.com'
  // },
  // {
  //   name: 'Shannon Etheridge Whitten',
  //   email: 'swhitte3@jhu.edu'
  // },
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
