<template>
  <footer>
    <div
      class="flex flex-col md:flex-row lg:flex-row sm:flex-col items-center justify-between shadow bg-gradient-to-r from-indigo-950 from-10% via-fuchsia-500 via-50% to-rose-500 to-90% px-4"
    >
      <div class="flex flex-col py-4 mr-10">
        <img
          class="inline-block h-32 w-32 mr-10 rounded-full"
          src="logo.png"
          alt="logo"
        />
        <div class="mt-2 mr10">
          <p class="text-white leading-loose">
            پاسخگویی شما از شنبه تا چهارشنبه <br />
            از ساعت 8:00 تا 18:00 می باشیم
          </p>
        </div>
      </div>
      <div class="flex flex-col">
        <div class="flex flex-row mt-10">
          <p class="text-white">ما را در فضای مجازی دنبال کنید:</p>
          <div class="mt-10 mb-6">
            <button
              type="button"
              data-te-ripple-init
              data-te-ripple-color="light"
              class="mb-2 inline-block rounded-full p-3 text-xs font-medium uppercase leading-normal text-white shadow-md transition duration-150 ease-in-out hover:shadow-lg focus:shadow-lg focus:outline-none focus:ring-0 active:shadow-lg bg-rose-500 hover:bg-indigo-600"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-4 w-4"
                fill="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"
                />
              </svg>
            </button>
          </div>
        </div>
        <div class="mx-auto w-full max-w-sm rounded-md bg-yellow-500 mb-6">
          <div class="sm:mx-auto sm:w-full sm:max-w-sm">
            <form class="px-6 pt-4" action="#" method="POST">
              <div>
                <h1 class="block font-bold leading-6 text-black pb-4">
                  از جدیدترین تورها مطلع باشید!
                </h1>
                <label
                  for="email"
                  class="block font-bold leading-6 text-gray-900"
                  >با وارد کردن ایمیل خود از جدیدترین تورها با خبر شوید</label
                >
                <div class="mt-2 flex flex-row pb-4">
                  <input
                    id="email"
                    name="email"
                    type="email"
                    autocomplete="email"
                    required
                    class="block px-10 py-2 rounded-full py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6 bg-white border border-gray-500"
                    placeholder="ایمیل"
                  />
                  <button
                    type="submit"
                    class="flex justify-center rounded-full bg-gray-300 px-4 py-2 font-bold font-semibold leading-6 text-black shadow-sm hover:bg-gray-500 mr-4"
                  >
                    اشتراک
                  </button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
      <div class="flex flex-col ml-10">
        <div class="flex flex-row-reverse">
          <ul>
            <li class="text-white py-2">راه های ارتباطی با ما:</li>
            <li class="text-white py-2">
              <a href="#" class="hover:text-black">86043550</a> _
              <a href="#" class="hover:text-black">09126118386</a>
            </li>
            <li class="text-white py-2">
              <a href="#" class="hover:text-black">Admin@gmail.com</a>
            </li>
            <li class="text-white pt-2">آدرس</li>
            <li class="text-white pb-4">شریعتی _ هویزه</li>
          </ul>
        </div>
      </div>
    </div>
    <!--footer info-->
    <div
      class="items-center justify-between border-t shadow bg-gradient-to-r from-indigo-950 from-20% via-fuchsia-500 via-40% to-rose-500 to-70% py-2 drop-shadow-2xl"
    >
      <p class="text-center text-white">کلیه حقوق محفوض است</p>
    </div>
  </footer>
</template>