<template>
  <div class="card m-3 p-0" style="width: 18rem;">
    <img :src="card.imgSrc" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">{{ card.title }}</h5>
      <h6 style="font-weight:lighter;" class="card-subtitle mb-2 text-muted">{{ card.subtitle }}</h6>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    card: {
      type: Object,
      required: true
    }
  }
}
</script>