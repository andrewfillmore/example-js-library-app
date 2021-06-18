<template>
  <div class="home">
    <div id="fullpage">
      <div class="section-top">
        <h1>APPARREL AND ACCESSORIES</h1>
      </div>
      <div class="section fp-auto-height-responsive">
        <h1>Christian Dior</h1>
        <img
          src="https://secureservercdn.net/45.40.145.201/7ge.8d4.myftpupload.com/wp-content/uploads/2021/01/3827._Border.jpg"
          alt=""
        />
      </div>
      <div class="section">
        <div class="slide" data-anchor="slide1">Slide 1</div>
        <div class="slide" data-anchor="slide2">Slide 2</div>
        <div class="slide" data-anchor="slide3">Slide 3</div>
        <div class="slide" data-anchor="slide4">Slide 4</div>
      </div>
      <div class="section fp-auto-height-responsive">
        <h1>Louis Vuitton</h1>
        <img
          src="https://secureservercdn.net/45.40.145.201/7ge.8d4.myftpupload.com/wp-content/uploads/2021/01/LVPatent-2.jpg"
          alt=""
        />
      </div>
      <div class="section fp-auto-height">
        <h1>Prada</h1>
        <img
          src="https://secureservercdn.net/45.40.145.201/7ge.8d4.myftpupload.com/wp-content/uploads/2021/01/2623-1.jpg"
          alt=""
        />
      </div>
      <div class="section fp-auto-height">
        <h1>Fendi</h1>
        <img
          src="https://secureservercdn.net/45.40.145.201/7ge.8d4.myftpupload.com/wp-content/uploads/2021/01/3629.jpg"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
// import axios from "axios";
// import fullPage from "full-page";

// export default defineComponent({
//   setup() {},
// });
</script>

<script type="text/javascript">
$(document).ready(function () {
  $("#fullpage").fullpage({
    //options here
    autoScrolling: true,
    scrollHorizontally: true,
    responsiveHeight: 200,
  });

  //methods
  $.fn.fullpage.setAllowScrolling(false);
});
</script>

<style>
#fullpage {
  background-color: yellow;
}
.content {
  margin: 50px;
}
.section-top {
  color: lightseagreen;
  font-size: 5em;
  text-align: center;
}
.section {
  color: lightseagreen;
  font-size: 5em;
  text-align: center;
}
</style>

// //
<script>
// // import axios from "axios";

// // export default {
// //   data: function () {
// //     return {
// //       message: "Full Page Test",
// //     };
// //   },
// //   created: function () {},
// //   methods: {},
// // };
// //
//
</script>
