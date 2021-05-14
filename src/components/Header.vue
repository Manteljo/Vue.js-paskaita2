<template>
  <header>
    <h1>This is the Heading</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fuga minus
      reiciendis hic quas facere pariatur dolor, dolorem quisquam delectus
      architecto, tempore eos nihil facilis temporibus ex. Voluptatum quas
      necessitatibus repellendus?
    </p>
    <Button text="This is yet another Button" />
  </header>
</template>

<script>
import Button from "./Button";

export default {
  name: "Header",
  components: { Button },
};
</script>

<style></style>
