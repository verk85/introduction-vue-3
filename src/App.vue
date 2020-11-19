<template>
  <div>
    <h1>Hello Vue</h1>
    <p>{{ helloWorld }}</p>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      helloWorld: 'This is a Vue3 App.',
    };
  },
};
</script>
