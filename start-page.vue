<template>
    <div class="hello">Start here {{who}}</div>
</template>

<script>
module.exports = {
  data: function() {
    return {
      who: "world"
    };
  }
};
</script>

<style>
.hello {
  background-color: #ffe;
}
</style>