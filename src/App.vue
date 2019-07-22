<template>
  <form method="get" action="">
    <hooper>
      <slide>
        slide 1
      </slide>
      <slide>
        slide 2
      </slide>
      <pagination slot="hooper-addons" />
    </hooper>
  </form>
</template>

<script>
import { Hooper, Slide, Pagination } from 'hooper';
import 'hooper/dist/hooper.css';

export default {
  name: 'App',
  components: {
    Hooper,
    Slide,
    Pagination,
  }
};
</script>

<style>
.hooper-slide {
  background-color: lightgreen;
}
</style>
