<template>
  <div>
    <navbar-component />
    <main>
      <div
        class="relative pt-16 pb-32 flex content-center items-center justify-center"
        style="min-height: 66vh"
      >
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style="background-image: url('/img/top_ppl.jpg')"
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-0 bg-black"
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
              class="text-yellow-300 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
      </div>

      <section class="pb-20 bg-yellow-300">
        <div class="container relative mx-auto pt-12" id="about">
          <div class="items-center flex flex-wrap">
            <div class="w-full lg:w-10/12 px-4 ml-auto mr-auto text-center">
              <div class="pr-12">
                <h1 class="text-black font-semibold text-5xl">
                  Your Trusted Communications Partner in Japan
                </h1>
                <p class="mt-4 text-lg text-gray-800">
                  We're a Tokyo-based boutique communications agency
                  specializing in representing overseas businesses. Our tailored
                  and innovative PR solutions drive engagement in the Japanese
                  market. With our wealth of PR experience, deep rooted media
                  connections, and a one-stop-solution, we go way beyond PR. We
                  deliver highly polished and professional work across all media
                  and channels including online and digital. We specialise in
                  removing the communication gap that often exists when overseas
                  organizations try to tell their story in Japan.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="container mx-auto px-4 mt-12">
          <div class="flex flex-wrap">
            <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-yellow-100 w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-blue-400"
                  >
                    <!-- <i class="fas fa-award"></i> -->
                    <img src="/svg/pie.svg" alt="" />
                  </div>
                  <h6 class="text-xl font-semibold">Business Focus</h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    We listen and learn, to fully understand our client’s
                    business strategy. We deliver solutions directly aligned to
                    our client’s strategy and vision. We work with clients from
                    a wide range of business sectors, such as: technology
                    (start-ups, AI, robotics, e-commerce, social media);
                    manufacturers; retailers; healthcare; beauty;
                    pharmaceutical; and not-for-profit organizations (NPOs).
                  </p>
                </div>
              </div>
            </div>
            <div class="w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-yellow-100 w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-purple-400"
                  >
                    <!-- <i class="fas fa-retweet"></i> -->
                    <img src="/svg/glasses.svg" alt="" />
                  </div>
                  <h6 class="text-xl font-semibold">
                    Expert Skills & Resources
                  </h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Our in-house team are all experienced PR and communications
                    professionals. Our robust network of specialists is on call
                    to support on a wide range of industry needs and unique
                    client requirements. We work thoughtfully and thoroughly,
                    and understand that details matter.
                  </p>
                </div>
              </div>
            </div>
            <div class="pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-yellow-100 w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-600"
                  >
                    <!-- <i class="fas fa-fingerprint"></i> -->
                    <img src="/svg/japan.svg" alt="" />
                  </div>
                  <h6 class="text-xl font-semibold">
                    Japanese Market Knowledge
                  </h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Japan is our native market. We are a Japanese business, and
                    understand the Japanese business ecosystem. We have an
                    extensive network of contacts within the Japanese media,
                    marketing, and user insights industries. Our results and
                    achievements have cemented our strong reputation among
                    Japanese media leaders and opinionmakers.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="relative py-20" id="services">
        <div
          class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
          style="height: 80px"
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
          <ServicesComponent />
        </div>
      </section>

      <section class="pb-20 relative block bg-blue-100" id="references">
        <div
          class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
          style="height: 80px"
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
              class="text-blue-100 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
        <div class="container mx-auto px-4 lg:pt-24 lg:pb-48">
          <div class="flex flex-wrap items-center mt-16">
            <div class="w-full md:w-7/12 px-4 mr-auto ml-auto">
              <!-- <div
                class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-gray-100"
              >
                
                <img src="/svg/happybubble.svg" alt="" />
              </div> -->
              <ContactComponent />
              <!-- <h3 class="text-3xl mb-2 font-semibold leading-normal">
                Find Yourself In Good Company
              </h3>
              <p
                class="text-lg font-light leading-relaxed mt-4 mb-2 text-gray-700"
              >
                Since 2007 we've helped several distinguished brands communicate
                better in Japan.
              </p>
              <div class="lg:flex w-100 justify-evenly">
                <img src="/clients/aw.png" class="w-3/4 lg:w-1/3" />
                <img src="/clients/sphero.png" class="w-3/4 lg:w-1/3" />
                <img src="/clients/softbank.png" class="w-3/4 lg:w-1/3" />
              </div> -->
            </div>
            <div class="w-full md:w-3/12 px-4 mr-auto ml-auto">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-pink-600"
              >
                <img
                  alt="..."
                  src="/img/natsuko3.jpg"
                  class="w-full align-middle rounded-t-lg"
                />
                <blockquote class="relative p-4 mb-4">
                  <svg
                    preserveAspectRatio="none"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 583 95"
                    class="absolute left-0 w-full block"
                    style="height: 95px; top: -94px"
                  >
                    <polygon
                      points="-30,95 583,95 583,65"
                      class="text-pink-600 fill-current"
                    ></polygon>
                  </svg>
                  <h4 class="text-md font-bold text-white">
                    Our Founder and CEO
                  </h4>
                  <p class="font-light mt-2 text-white mb-3">
                    Natsuko Mochizuki is a driven, focused, Marketing & PR
                    professional with over 25 years’ experience in the industry.
                  </p>
                  <a href="/ceo" class="font-bold text-white mt-8">Full Bio</a>
                </blockquote>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- <section class="relative py-20 bg-gray-800" id="contact">
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
              class="text-gray-800 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
        <div class="container mx-auto px-4">
          <ContactComponent />
        </div>
      </section> -->
    </main>
    <footer-component />
  </div>
</template>
<script>
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
import ServicesComponent from "../components/Services.vue";
import ContactComponent from "../components/ContactMinimal.vue";
export default {
  name: "landing-page",
  components: {
    NavbarComponent,
    FooterComponent,
    ServicesComponent,
    ContactComponent,
  },
};
</script>
