<template>
  <div>
    <h1>Home Page</h1>
    <div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed eget diam vestibulum, pharetra ex nec, ultricies lorem. Donec id dictum eros. Cras sed leo libero. Nulla nec libero nec turpis pretium facilisis. Nunc vel sem vitae eros aliquam ultrices at sed ligula. Aenean porta sem ac ornare finibus. Praesent velit nisl, sodales non leo eget, elementum pulvinar ante. Nullam suscipit sit amet dui vel tincidunt. Vestibulum sit amet sem tincidunt, sodales eros non, feugiat turpis. Sed ut rhoncus ligula. Nam nisl sapien, maximus ac quam vel, sodales interdum nulla. Nunc mi est, mollis at ligula a, aliquet auctor libero. Nullam sit amet ligula pretium, feugiat velit sed, consectetur mauris. Morbi interdum consequat nisl, vitae blandit dui. Pellentesque a ipsum pharetra, porta nunc a, porttitor lectus.</p>
      <p>Ut vel tempor justo. Aenean ut odio et dolor porttitor tincidunt non at tortor. Morbi congue, lorem at lacinia vehicula, tortor mi ornare sem, at faucibus eros nisl id purus. Aenean id justo bibendum, tempor nisl at, vestibulum sapien. Nulla maximus, est ut fringilla posuere, risus eros ultrices diam, vel euismod urna ante et justo. Nam ornare, enim sit amet sagittis lobortis, enim odio commodo tortor, sit amet posuere dolor nisi eget lorem. Pellentesque quis nibh sed dolor fermentum porta. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vivamus accumsan nisl vitae est ultricies, in dignissim risus vehicula. In vitae tempor ipsum, sit amet cursus libero. Vivamus lectus velit, ornare sit amet laoreet id, hendrerit nec libero.</p>
      <p>Nullam dignissim in justo et porta. Donec quis justo ante. Pellentesque id ante tellus. Nulla facilisi. Proin consequat vulputate mauris, at scelerisque neque varius vel. In urna diam, volutpat eget velit a, feugiat malesuada ex. Fusce ultricies justo non posuere malesuada. Nulla facilisi. Vivamus ultrices a elit eget pulvinar.</p>
      <p>Vestibulum efficitur, lectus sit amet tincidunt interdum, lacus odio commodo odio, ut luctus leo mauris ac dui. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nunc euismod lorem tellus. Morbi sit amet egestas quam, nec porta libero. Curabitur eu pulvinar mi. Sed nunc ante, ultricies nec erat sed, placerat eleifend tellus. Donec convallis at urna ut facilisis. Ut dictum mi ex, sit amet porta ante imperdiet ut. Fusce faucibus vel mauris ac aliquam. Nunc laoreet molestie turpis, eget pellentesque purus iaculis ut. Ut non tincidunt tellus. Phasellus ac magna dapibus, efficitur lectus et, venenatis magna. Etiam elementum dolor sit amet dui convallis, et aliquam purus efficitur. Donec sit amet ipsum in mauris interdum pellentesque sit amet ac lacus.</p>
      <p>Ut in venenatis ante. Maecenas interdum sem ut ipsum imperdiet aliquet. Aliquam eget nisi ante. Donec sit amet molestie leo. Etiam blandit imperdiet quam a vulputate. Phasellus condimentum dui justo, in iaculis augue porttitor id. Quisque rhoncus nibh tortor. Vestibulum non massa nec metus convallis rhoncus et quis tortor. Aliquam et rutrum quam. Nunc quis bibendum velit. Nullam ornare ligula at mi placerat, vel vehicula risus euismod. Phasellus neque elit, molestie et justo nec, faucibus blandit mauris. Integer lobortis ipsum consequat lectus semper tempus. Maecenas vehicula tellus velit, eget hendrerit lorem faucibus in.</p>
    </div>
  </div>
</template>
<script>
import Header from "~/components/Header.vue";
export default {
  data() {
    return {
      userId: ""
    };
  },
  components: { Header },
  methods: {
    onLoadUser() {
      this.$router.push("/users/" + this.userId);
    }
  },
  layout: "users"
};
</script>

<style>
</style>
