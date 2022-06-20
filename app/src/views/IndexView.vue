<template>
  <div>
    <image-header />
    <buttons-menu />
  </div>
</template>

<script>
import ImageHeader from "@/components/ImageHeader";
import ButtonsMenu from "@/components/ButtonsMenu";
export default {
  name: "IndexView",
  components: { ButtonsMenu, ImageHeader },
};
</script>
