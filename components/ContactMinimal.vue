<template>
  <div>
    <h4 class="text-2xl font-semibold">Contact Us</h4>
    <p class="leading-relaxed mt-1 mb-4 text-gray-600">
      Please complete this form and we will get back to you.
    </p>
    <form
      action="/thankyou/"
      method="post"
      name="registration-form"
      data-netlify="true"
      data-netlify-honeypot="bot-field"
    >
      <input type="hidden" name="form-name" value="registration-form" />

      <div class="relative w-full mb-3 mt-8">
        <label
          class="block uppercase text-gray-700 text-xs font-bold mb-2"
          for="full-name"
          >Full Name</label
        ><input
          type="text"
          name="full_name"
          id="full_name"
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
          name="email"
          id="email"
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
          name="message"
          id="message"
          class="border-0 px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full"
          placeholder="Type a message..."
        ></textarea>
      </div>
      <div class="text-center mt-6 mb-6">
        <button
          class="bg-pink-600 text-white active:bg-gray-700 text-sm font-bold uppercase px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1"
          type="button"
          style="transition: all 0.15s ease 0s"
        >
          Send Message
        </button>
      </div>
    </form>
  </div>
</template>
