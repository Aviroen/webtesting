<template>
  <div class="banner1-container1 thq-section-padding">
    <div class="banner1-max-width thq-section-max-width">
      <div class="banner1-container2">
        <h2 class="banner1-title thq-heading-2">
          <slot name="heading1">
            <!--Default content for heading1-->
            <div class="banner1-fragment2">
              <span class="banner1-text3">Company Name</span>
            </div>
          </slot>
        </h2>
        <h3 class="banner1-text1 thq-heading-3">
          <slot name="content1">
            <!--Default content for content1-->
            <div class="banner1-fragment1">
              <span class="banner1-text2">Company mission statement</span>
            </div>
          </slot>
        </h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Banner1',
  props: {},
}
</script>

<style scoped>
.banner1-container1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  position: relative;
  align-items: center;
}
 
.banner1-max-width {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.banner1-container2 {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.banner1-title {
  text-align: center;
}
 
.banner1-text1 {
  text-align: center;
}
 
.banner1-fragment1 {
  display: contents;
}
 
.banner1-text2 {
  display: inline-block;
}
 
.banner1-fragment2 {
  display: contents;
}
 
.banner1-text3 {
  display: inline-block;
}
</style>
