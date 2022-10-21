<template>
  <footer class="relative bg-white pt-8 pb-6">
    <div
      class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
      style="height: 90px"
    >
      <svg
        class="absolute bottom-0 overflow-hidden"
        xmlns="http://www.w3.org/2000/svg"
        preserveAspectRatio="none"
        version="1.1"
        viewBox="0 0 2560 100"
        x="0"
        y="0"
      >
        <polygon
          class="text-white fill-current"
          points="2560 0 2560 100 0 100"
        ></polygon>
      </svg>
    </div>
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap">
        <div class="w-full lg:w-6/12 px-4 flex flex-col justify-center">
          <h4 class="text-3xl font-semibold">
            Your Trusted Communications Partner in Japan.
          </h4>
          <!-- <h5 class="text-lg mt-0 mb-2 text-gray-700">
            Japanese Communications Solutions for Overseas Businesses
          </h5> -->
        </div>
        <div class="w-full lg:w-6/12 px-4">
          <div class="flex flex-wrap items-top mb-6">
            <div class="w-full lg:w-6/12 px-4 ml-auto">
              <span
                class="block uppercase text-gray-600 text-sm font-semibold mb-2"
                >Address</span
              >
              <ul class="list-unstyled">
                <li>2-10-34 Kamiosaki Shinagawa-ku</li>
                <li>Tokyo 141-0021 Japan</li>
                <li>
                  <a
                    class="text-pink-600 hover:text-gray-900 font-semibold block pb-2 text-sm"
                    href="mailto:info@moonlightwave.com"
                    >info@moonlightwave.com</a
                  >
                </li>
              </ul>
            </div>
            <!-- <div class="w-full lg:w-4/12 px-4 ml-auto">
              <span
                class="block uppercase text-gray-600 text-sm font-semibold mb-2"
                >Collaborations</span
              >
              <ul class="list-unstyled">
                <li>
                  <a
                    class="text-gray-700 hover:text-gray-900 font-semibold block pb-2 text-sm"
                    href="https://github.com/creativetimofficial/argon-design-system/blob/master/LICENSE.md"
                    >Miraindia</a
                  >
                </li>
                <li>
                  <a
                    class="text-gray-700 hover:text-gray-900 font-semibold block pb-2 text-sm"
                    href="https://creative-tim.com/terms"
                    >Moonlink</a
                  >
                </li>
              </ul>
            </div> -->
          </div>
        </div>
      </div>
      <!-- <hr class="my-6 border-gray-400" /> -->
      <div
        class="flex flex-wrap items-center md:justify-between justify-center"
      >
        <div class="w-full md:w-4/12 px-4 mx-auto text-center">
          <div class="text-sm text-gray-600 font-semibold py-1">
            Copyright © {{ date }} Moonlight Wave.
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      date: new Date().getFullYear(),
    };
  },
};
</script>
