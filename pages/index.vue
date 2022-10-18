<template>
  <div>
    <navbar-component />
    <main>
      <div
        class="relative pt-16 pb-32 flex content-center items-center justify-center"
        style="min-height: 75vh"
      >
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style="background-image: url('/img/top_ppl.jpg')"
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-50 bg-black"
          ></span>
        </div>
        <div class="container relative mx-auto">
          <div class="items-center flex flex-wrap">
            <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
              <div class="pr-12">
                <h1 class="text-white font-semibold text-5xl">
                  Your Trusted Partner in Japan
                </h1>
                <p class="mt-4 text-lg text-gray-300">
                  Japanese Communications Solutions for Overseas Businesses
                </p>
              </div>
            </div>
          </div>
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
      </div>
      <section class="pb-20 bg-gray-300 -mt-24" id="about">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap">
            <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
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
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
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
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
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
          <div class="flex flex-wrap items-center mt-32">
            <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">
              <div
                class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-gray-100"
              >
                <!-- <i class="fas fa-user-friends text-xl"></i> -->
                <img src="/svg/happybubble.svg" alt="" />
              </div>
              <h3 class="text-3xl mb-2 font-semibold leading-normal">
                Working with us is a pleasure
              </h3>
              <p
                class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-700"
              >
                Moonlight Wave has the resources, experience, knowledge, and
                contacts to drive your local engagement in Japan. We specialise
                in removing the communication gap that often exists when
                overseas organizations try to tell their story in Japan.
              </p>
              <!-- <p
                class="text-lg font-light leading-relaxed mt-0 mb-4 text-gray-700"
              >
                The kit comes with three pre-built pages to help you get started
                faster. You can change the text and images and you're good to
                go. Just make sure you enable them first via JavaScript.
              </p>
       -->
            </div>
            <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-pink-600"
              >
                <img
                  alt="..."
                  src="/img/natsuko3.jpg"
                  class="w-full align-middle rounded-t-lg"
                />
                <blockquote class="relative p-8 mb-4">
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
                  <h4 class="text-xl font-bold text-white">
                    Our Founder and CEO
                  </h4>
                  <p class="text-md font-light mt-2 text-white mb-3">
                    Natsuko Mochizuki is a driven, focused, Marketing & PR
                    professional with over 25 years’ experience in the industry
                  </p>
                  <a href="/ceo" class="font-bold text-white mt-8">Full Bio</a>
                </blockquote>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="relative py-20">
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
          <div class="items-center flex flex-wrap">
            <div class="w-full md:w-4/12 ml-auto mr-auto px-4">
              <img
                alt="..."
                class="max-w-full rounded-lg shadow-lg mb-5"
                src="/img/tokyo2.png"
              />
            </div>
            <div class="w-full md:w-5/12 ml-auto mr-auto px-4" id="story">
              <div class="md:pr-12">
                <div
                  class="text-pink-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-pink-300"
                >
                  <!-- <i class="fas fa-rocket text-xl"></i> -->
                  <img src="/svg/steps.svg" alt="" />
                </div>
                <h3 class="text-3xl font-semibold">Our story</h3>
                <p class="mt-4 text-lg leading-relaxed text-gray-600">
                  Our boutique communications agency was established in 2007. We
                  are specialists in representing overseas corporations and
                  organizations in Japan. We deliver tailored and innovative PR
                  solutions that help drive engagement in the Japanese market.
                  With our wealth of PR experience in Japan, deep rooted media
                  connections, and a one-stop-solution, we can support our
                  clients beyond PR. We deliver highly polished and professional
                  work across all media and channels in Japan. Our online and
                  digital capabilities bring flexibility for our clients in a
                  fast moving and unpredictable world.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="pb-20 relative block bg-gray-900" id="services">
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
              class="text-gray-900 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
        <div class="container mx-auto px-4 lg:pt-24 lg:pb-64">
          <div class="flex flex-wrap text-center justify-center">
            <div class="w-full lg:w-6/12 px-4">
              <h2 class="text-4xl font-semibold text-white pt-5">What We Do</h2>
              <!-- <p class="text-lg leading-relaxed mt-4 mb-4 text-gray-500">
                Put the potentially record low maximum sea ice extent tihs year
                down to low ice. According to the National Oceanic and
                Atmospheric Administration, Ted, Scambos.
              </p> -->
            </div>
          </div>
          <div class="flex flex-wrap mt-12 justify-center">
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <!-- <i class="fas fa-medal text-xl"></i> -->
                <img src="/svg/megaphone.svg" alt="" />
              </div>
              <h6 class="text-xl mt-5 font-semibold text-white">
                Communications
              </h6>
              <p class="mt-2 mb-4 text-gray-500">
                Unique Japanese communication strategies based on local market
                insights, and our client’s business strategy. Our thorough
                planning and execution deliver the high standards required by
                the Japanese media and businesses we work with.
              </p>
            </div>
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-poll text-xl"></i>
              </div>
              <h5 class="text-xl mt-5 font-semibold text-white">
                Media Relations
              </h5>
              <p class="mt-2 mb-4 text-gray-500">
                We have strong relationships with professionals across all types
                of media in Japan. We know who to contact, and we know how to
                approach them to share our stories.
              </p>
            </div>
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-lightbulb text-xl"></i>
              </div>
              <h5 class="text-xl mt-5 font-semibold text-white">Events</h5>
              <p class="mt-2 mb-4 text-gray-500">
                We create and deliver impactful PR events – both face to face,
                and online. These include: press conferences, round tables,
                one-to-one interviews, and briefing sessions. Our events drive
                original news creation and deeper community development.
              </p>
            </div>
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-lightbulb text-xl"></i>
              </div>
              <h5 class="text-xl mt-5 font-semibold text-white">
                Start-up Support
              </h5>
              <p class="mt-2 mb-4 text-gray-500">
                For start-ups entering the Japanese market, we can support with
                marketing, branding and other communication needs to enable you
                to quickly increase awareness and credibility. For Japanese
                startups, we provide special assistance for global expansion,
                with the opportunity to team up with our global partners in
                various areas. Please contact us for more details.
              </p>
            </div>
          </div>
          <div class="flex flex-wrap mt-12 justify-center">
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-medal text-xl"></i>
              </div>
              <h6 class="text-xl mt-5 font-semibold text-white">
                Social Media
              </h6>
              <p class="mt-2 mb-4 text-gray-500">
                We use international and Japanese social media tools to share
                stories and localized client news, developing brand engagement
                and growing a local Japanese fan platform.
              </p>
            </div>
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-poll text-xl"></i>
              </div>
              <h5 class="text-xl mt-5 font-semibold text-white">
                Community Relations
              </h5>
              <p class="mt-2 mb-4 text-gray-500">
                We have strong working relationships with many local
                communities. We believe in diversity, inclusiveness, supporting
                others, and working together to help society.
              </p>
            </div>
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-lightbulb text-xl"></i>
              </div>
              <h5 class="text-xl mt-5 font-semibold text-white">
                Localization
              </h5>
              <p class="mt-2 mb-4 text-gray-500">
                Japan can be surprisingly localized. Even the language people
                use every day at work and at home can be localized. We
                understand this challenge, and the subtle nuances required for
                smooth friction-free communication in Japan.
              </p>
            </div>
            <div class="w-full lg:w-3/12 px-4 text-center">
              <div
                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
              >
                <i class="fas fa-lightbulb text-xl"></i>
              </div>
              <h5 class="text-xl mt-5 font-semibold text-white">Beyond PR</h5>
              <p class="mt-2 mb-4 text-gray-500 pb-5">
                Our one-stop-shop helps our clients go ‘Beyond PR’. For example:
                we can coordinate market research in Japan; we can support
                overseas marketing teams with local activities; we can source
                Japanese information for foreign media; and we can source local
                subject matter experts and deliver highly bespoke solutions to
                meet unique client needs.
              </p>
            </div>
          </div>
        </div>
      </section>
      <section class="relative block py-24 lg:pt-0 bg-gray-900" id="contact">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap justify-center lg:-mt-64 -mt-48">
            <div class="w-full lg:w-6/12 px-4">
              <div
                class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-300"
              >
                <div class="flex-auto p-5 lg:p-10">
                  <h4 class="text-2xl font-semibold">Want to work with us?</h4>
                  <p class="leading-relaxed mt-1 mb-4 text-gray-600">
                    Complete this form and we will get back to you in 24 hours.
                  </p>
                  <div class="relative w-full mb-3 mt-8">
                    <label
                      class="block uppercase text-gray-700 text-xs font-bold mb-2"
                      for="full-name"
                      >Full Name</label
                    ><input
                      type="text"
                      class="border-0 px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full"
                      placeholder="Full Name"
                      style="transition: all 0.15s ease 0s"
                    />
                  </div>
                  <div class="relative w-full mb-3">
                    <label
                      class="block uppercase text-gray-700 text-xs font-bold mb-2"
                      for="email"
                      >Email</label
                    ><input
                      type="email"
                      class="border-0 px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full"
                      placeholder="Email"
                      style="transition: all 0.15s ease 0s"
                    />
                  </div>
                  <div class="relative w-full mb-3">
                    <label
                      class="block uppercase text-gray-700 text-xs font-bold mb-2"
                      for="message"
                      >Message</label
                    ><textarea
                      rows="4"
                      cols="80"
                      class="border-0 px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full"
                      placeholder="Type a message..."
                    ></textarea>
                  </div>
                  <div class="text-center mt-6">
                    <button
                      class="bg-gray-900 text-white active:bg-gray-700 text-sm font-bold uppercase px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      style="transition: all 0.15s ease 0s"
                    >
                      Send Message
                    </button>
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
  name: "landing-page",
  components: {
    NavbarComponent,
    FooterComponent,
  },
};
</script>
