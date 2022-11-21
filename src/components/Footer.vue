<template>
  <footer class="mt-0 mb-8 pb-8 text-slate-400">
    <hr class="mt-0" />
    <div class="mb-1" id="copyright">
      Designed and built by
      <a href="https://matthewsetter.com">Matthew Setter</a>. &copy; Twilio
      {{ year }}. All rights reserved.
    </div>
    <div id="image-credits">
      <div>Social media icon credits</div>
      <ul class="list-outside list-disc ml-4">
        <li>
          <a
            href="https://www.flaticon.com/free-icons/twitter-social-badge"
            title="twitter social badge icons"
            >Twitter social badge icons created by Grow studio - Flaticon</a
          >
        </li>
        <li>
          <a
            href="https://www.flaticon.com/free-icons/instagram"
            title="instagram icons"
            >Instagram icons created by riajulislam - Flaticon</a
          >
        </li>
        <li>
          <a
            href="https://www.flaticon.com/free-icons/linkedin"
            title="linkedin icons"
            >Linkedin icons created by Freepik - Flaticon</a
          >
        </li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names,vue/no-reserved-component-names
  name: "Footer",
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>

<style scoped></style>
