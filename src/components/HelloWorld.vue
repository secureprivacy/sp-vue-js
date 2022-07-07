<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Guide to embed trust badge on any page element.
      <a href="javascript:void(0);" onclick="window.sp.showPrivacyBanner();">
        Click here to open Preference center
      </a>
    </p>

    <p>
      The details of those methods can be found in this support article
      <a target="_blank"
        href="https://support.secureprivacy.ai/support/solutions/articles/80000874914-developer-guide-for-javascript-methods"
      >
        Guide
      </a>
    </p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
