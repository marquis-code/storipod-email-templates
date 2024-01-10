<template>
  <div class="email-template bg-gray-100 p-4 h-screen">
    <div
      class="max-w-3xl mx-auto bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4 space-y-6"
    >
      <header class="flex justify-between items-center">
        <div>
          <img src="@/assets/icons/logo.svg" alt="" />
        </div>
        <div class="flex justify-between items-center gap-x-4">
          <img src="@/assets/icons/gray-twitter.svg" alt="" />
          <img src="@/assets/icons/gray-facebook.svg" alt="" />
          <img src="@/assets/icons/gray-instagram.svg" alt="" />
        </div>
      </header>
      <section
        class="bg-[#e7fbfe] rounded-2xl flex justify-between items-center h-96 p-4"
      >
        <div class="w-4/12">
          <div class="flex justify-center items-center flex-col">
            <h1 class="text-6xl">Welcome</h1>
            <h1 class="text-6xl text-[#279FBD]">"James"</h1>
            <p
              class="text-[#4F4F4F] text-lg font-light max-w-sm w-10/12 text-center leading-loose tracking-wide"
            >
              We’re dying to hear your stories!
            </p>
          </div>
        </div>
        <div class="w-7/12 flex justify-start items-start">
          <img
            src="@/assets/img/animated.png"
            class="h-72 w-full object-center"
            alt=""
          />
        </div>
      </section>
      <section class="flex justify-center items-center flex-col gap-y-4">
        <div class="w-full">
          <span
            class="w-4/12 mx-auto border-4 border-yellow-500 bg-yellow-500 py-0.5 h-0.5 block"
          ></span>
        </div>
        <h1
          class="text-gray-600 font-semibold leading-loose text-lg tracking-wider max-w-md text-center"
        >
          Are you ready to find a whole new audience for the tales you have to
          tell?
        </h1>
      </section>
      <section class="flex justify-center items-center flex-col gap-y-6">
        <img src="@/assets/img/multi-colored.png" alt="" />
        <p class="text-lg leading-loose tracking-wide text-center max-w-sm">
          We’re super thrilled to have you as a member of the
          <span class="font-medium text-[#0BA9B9]">Storipod</span> family!
        </p>
        <button
          class="text-white bg-[#0BA9B9] font-semibold rounded-3xl px-6 py-3"
        >
          Get started Here!
        </button>
      </section>
      <footer class="bg-[#1F1F1F] py-6">
        <div class="flex justify-center items-center flex-col gap-y-6">
          <div class="gap-y-2 flex justify-center items-center flex-col">
            <img src="@/assets/icons/white-logo.svg" alt="" />
            <p class="text-gray-400 text-xs">© 2024 Storipod</p>
          </div>
          <div class="flex justify-between items-center gap-x-4">
            <img src="@/assets/icons/white-twitter.svg" alt="" />
            <img src="@/assets/icons/white-facebook.svg" alt="" />
            <img src="@/assets/icons/white-instagram.svg" alt="" />
          </div>
          <div>
            <p class="text-white">
              Want to unsubscribe?
              <span class="font-bold text-white">Click here</span>.
            </p>
          </div>
        </div>
      </footer>
      <!-- <div class="mb-4">
        <h1 class="block text-gray-700 text-sm font-bold mb-2">Your OTP</h1>
        <p>Your One-Time Password is:</p>
        <p class="text-3xl text-center font-bold">{{ otp }}</p>
      </div>
      <p class="text-sm text-gray-600">
        This password is only valid for the next 10 minutes.
      </p> -->
    </div>
    <div
      class="max-w-3xl mx-auto bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4 space-y-7"
    >
      <header class="flex justify-center items-center flex-col">
        <img src="@/assets/icons/logo.svg" class="h-60 w-60" alt="" />
        <div class="space-y-3 flex justify-center items-center flex-col">
          <h1 class="text-5xl font-semibold">Welcome James!</h1>
          <p class="text-lg font-light text-gray-500">
            Great to have you on board!
          </p>
        </div>
      </header>
      <section class="flex justify-center items-center flex-col gap-y-4">
        <div class="w-full">
          <span
            class="w-2/12 mx-auto border-4 border-yellow-500 bg-yellow-500 py-0.5 h-0.5 block"
          ></span>
        </div>
        <h1 class="text-lg leading-loose tracking-wide text-center max-w-sm">
          We’re super thrilled to have you as a member of the
          <span class="font-medium text-[#0BA9B9]">Storipod</span> family!
        </h1>
      </section>
      <section class="flex justify-center items-center flex-col gap-y-6 py-6">
        <img src="@/assets/img/white-iphones.png" alt="" />
        <p class="text-lg leading-loose tracking-wide text-center max-w-sm">
          We’re committed to fostering a safer and supportive interactive
          community for everyone, here on storipod.
        </p>
        <button
          class="text-white bg-[#0BA9B9] font-semibold rounded-3xl px-6 py-3"
        >
          Get started Here!
        </button>
      </section>
      <footer class="bg-[#1F1F1F] py-6">
        <div class="flex justify-center items-center flex-col gap-y-6">
          <div class="gap-y-2 flex justify-center items-center flex-col">
            <img src="@/assets/icons/white-logo.svg" alt="" />
            <p class="text-gray-400 text-xs">© 2024 Storipod</p>
          </div>
          <div class="flex justify-between items-center gap-x-4">
            <img src="@/assets/icons/white-twitter.svg" alt="" />
            <img src="@/assets/icons/white-facebook.svg" alt="" />
            <img src="@/assets/icons/white-instagram.svg" alt="" />
          </div>
          <div>
            <p class="text-white">
              Want to unsubscribe?
              <span class="font-bold text-white">Click here</span>.
            </p>
          </div>
        </div>
      </footer>
    </div>
    <div
      class="max-w-3xl mx-auto bg-gray-50 shadow-md rounded px-8 pt-6 pb-8 mb-4 space-y-6"
    >
      <header class="flex justify-between items-center">
        <div>
          <img src="@/assets/icons/logo.svg" alt="" class="h-20 w-32" />
        </div>
        <div class="flex justify-between items-center gap-x-4">
          <img src="@/assets/icons/gray-twitter.svg" alt="" />
          <img src="@/assets/icons/gray-facebook.svg" alt="" />
          <img src="@/assets/icons/gray-instagram.svg" alt="" />
        </div>
      </header>
      <section class="bg-white p-10 space-y-6">
        <h1>
          <span class="text-[#000059] text-lg">Welcome, </span>
          <span class="text-blue-600 text-lg">{Customers Name}</span>
        </h1>
        <h1 class="text-2xl font-medium leading-loose tracking-wide">
          Time to let the world hear your amazing stories
        </h1>
        <div class="flex justify-center items-center flex-col gap-6 mt-10">
          <img src="@/assets/img/phone-shuffle.png" class="h-60" alt="" />
          <p class="text-lg font-medium leading-loose tracking-wider text-gray-800">To validate your email address,</p>
          <p class="font-medium leading-loose tracking-wider text-gray-500">Here is your one time password.</p>
          <h1
            class="text-5xl font-medium tracking-widest leading-loose text-gray-700"
          >
            4 5 8 0
          </h1>
        </div>
      </section>
      <section class="space-y-3 mt-6">
        <p class="leading-loose">
          This email was sent to
          <span class="text-blue-600 underline"
            >morounfoluoyebanjo@gmail.com.</span
          >
          If you'd rather not receive this kind of email, Don’t want any more
          emails from storipod?
          <span class="text-blue-600 underline">Unsubscribe.</span>.
        </p>
        <p>© 2023 Storipod LTD. For support email hello@storipod.com</p>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    otp: {
      type: String,
      required: true,
    },
  },
};
</script>
