<template>
    <div>
        <h1>Wejapa Task</h1>
        <p> {{ name }} </p>
        <p> {{ slack }}</p>
    </div>
</template>

<script>
export default {
  name: 'MyName',
  props: {
    name : String,
    slack: String
  }
}
</script>