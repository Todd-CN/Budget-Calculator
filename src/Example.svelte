<span> Hello from example world! </span>
<!-- This will override the global scope, and it is only
scoped to this component, meaning that the css we created here
won't bleed into other spans we create in other components -->

<style>
  span {
    background: red;
    color: white;
  }
</style>
