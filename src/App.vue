<template>
  <section>
    <h1>vue-electron</h1>
    <main>
      Running on {{process.platform}}.
    </main>
  </section>
</template>

<script>
export default {
  data: () => ({
    process
  })
};
</script>