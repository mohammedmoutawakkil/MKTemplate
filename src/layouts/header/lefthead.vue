<template>
    <div>
        <p class="text-center text-capitalize fs-1 fw-bold">MK template</p>
        <p class="text-secondary">This text is styled with some of the text formatting properties. The heading uses the text-align, text-transform, and color properties.
        The paragraph is indented, aligned, and the space between characters is specified. The underline is removed from this colored.</p>
        <a href="#" class="btn text-uppercase text-light fw-bold px-sm-4 py-sm-3 Stars">Github Star</a>
    </div>
</template>

<script>
    export default {
        name:'lefthead'
    }
</script>

<style scoped>
div {
  padding: 8px;
  position: relative;
}

p:first-child {
  color: #667EEA;
}

p {
  text-align: justify;
  letter-spacing: 3px;
  line-height: 1.6;
}
.Stars{
  background-color: #334155;
}
</style>