<template>
  <div>
    <navbar-component></navbar-component>
    <main class="profile-page">
      <section class="relative block" style="height: 500px">
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style="background-image: url('/img/natsuko4.png')"
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-50 bg-black"
          ></span>
        </div>
        <div
          class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
          style="height: 70px"
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
              class="text-gray-300 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
      </section>
      <section class="relative py-16 bg-gray-300">
        <div class="container mx-auto px-4">
          <div
            class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-xl rounded-lg -mt-64"
          >
            <div class="px-6">
              <div class="flex flex-wrap justify-center">
                <div
                  class="w-full lg:w-3/12 px-4 lg:order-2 flex justify-center"
                >
                  <div class="relative">
                    <img
                      alt="..."
                      src="/img/natsuko3.jpg"
                      class="shadow-xl rounded-full h-auto align-middle border-none absolute -m-16 -ml-20 lg:-ml-16"
                      style="max-width: 150px"
                    />
                  </div>
                </div>
                <div
                  class="w-full lg:w-4/12 px-4 lg:order-3 lg:text-right lg:self-center"
                >
                  <div class="py-6 px-3 mt-32 sm:mt-0">
                    <button
                      class="bg-pink-500 active:bg-pink-600 uppercase text-white font-bold hover:shadow-md shadow text-xs px-4 py-2 rounded outline-none focus:outline-none sm:mr-2 mb-1"
                      type="button"
                      style="transition: all 0.15s ease 0s"
                    >
                      Email
                    </button>
                  </div>
                </div>
                <div class="w-full lg:w-4/12 px-4 lg:order-1">
                  <div class="flex justify-center py-4 lg:pt-4 pt-8">
                    <!-- <div class="mr-4 p-3 text-center">
                      <span
                        class="text-xl font-bold block uppercase tracking-wide text-gray-700"
                        >22</span
                      ><span class="text-sm text-gray-500">Friends</span>
                    </div> -->
                    <!-- <div class="mr-4 p-3 text-center">
                      <span
                        class="text-xl font-bold block uppercase tracking-wide text-gray-700"
                        >10</span
                      ><span class="text-sm text-gray-500">Photos</span>
                    </div>
                    <div class="lg:mr-4 p-3 text-center">
                      <span
                        class="text-xl font-bold block uppercase tracking-wide text-gray-700"
                        >89</span
                      ><span class="text-sm text-gray-500">Comments</span>
                    </div> -->
                  </div>
                </div>
              </div>
              <div class="text-center mt-12">
                <h3
                  class="text-4xl font-semibold leading-normal mb-2 text-gray-800 mb-2"
                >
                  Natsuko Mochizuki
                </h3>
                <div
                  class="text-sm leading-normal mt-0 mb-2 text-gray-500 font-bold uppercase"
                >
                  <i
                    class="fas fa-map-marker-alt mr-2 text-lg text-gray-500"
                  ></i>
                  Tokyo, Japan
                </div>
                <div class="mb-2 text-gray-700 mt-2">
                  <i class="fas fa-briefcase mr-2 text-lg text-gray-500"></i>
                  CEO and Founder
                </div>
              </div>
              <div class="mt-10 py-10 border-t border-gray-300 text-center">
                <div class="flex flex-wrap justify-center">
                  <div class="w-full lg:w-9/12 px-4">
                    <p class="mb-4 text-lg leading-relaxed text-gray-800">
                      Natsuko is a driven, focused, Marketing & PR professional
                      with over 25 years’ experience in the industry – from high
                      flying graduate at Procter & Gamble, Nike, Uniqlo, to
                      entrepreneurial founder and CEO of Moonlight Wave. Her
                      diverse experience in PR, marketing, brand management,
                      research, and advertising is reflected in the way
                      Moonlight Wave has grown and evolved.
                    </p>
                    <p class="mb-4 text-lg leading-relaxed text-gray-800">
                      Always listening and learning, Natsuko is continually
                      upskilling her team to enable Moonlight Wave to be up to
                      date with trends, technology, business practices, and
                      industry movements. With clients spanning a wide range of
                      sectors and sizes – from tech startups to global brands,
                      from beauty to construction, private ownership to
                      corporate giants – Natsuko has a unique and enviable
                      contact list in nearly every field of business. As well as
                      getting the best results for her clients. she also aims to
                      make a positive impact on society.
                    </p>
                    <p class="mb-4 text-lg leading-relaxed text-gray-800">
                      This has lead Moonlight Wave to work with a number of
                      Foundations and NPOs. Travelling for work and leisure has
                      taken Natsuko to more than 30 countries and 100 cities.
                      Her energy and passion for meeting new people, learning,
                      sharing, and collaborating continue to drive her forward.
                      She is currently Japan’s only member of the Counselors
                      Academy – a section of the Public Relations Society of
                      America (PRSA) – and advisor for Public Relations to the
                      Japanese Government.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer-component></footer-component>
  </div>
</template>
<script>
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
export default {
  name: "profile-page",
  components: {
    NavbarComponent,
    FooterComponent,
  },
};
</script>
