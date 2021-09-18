<template>

    <div class="p-20 max-w-md m-auto bg-yellow-500 rounded-xl shadow-md">
      <h1>{{ msg }}</h1>
      <div class="dropdown">
      </div>
    </div>
    
</template>

<script>
export default {
  name: 'DropDownList',
  props: {
    msg: String
  }
}
</script>
