<template>
  <div>
    <!--text title!-->
    <div
      class="flex flex-col md:flex-row-reverse lg:flex-row-reverse sm:flex-col mt-32 items-center mb-24"
    >
      <img
        src="international-tour.jpg"
        class="w-32 h-32 md:w-60 md:h-60 lg:w-80 lg:h-80 mr-20 ml-20"
      />
      <div class="p-4">
        <div class="flow-root">
          <div class="text-2xl text-orange-500 mt-10 mr-20">تورهای خارجی</div>
        </div>
        <p class="flow-root mt-6 mr-20 ml-20 leading-loose">
          معمولا پر طرفدارترین تورهای خارجی تور ترکیه ، تور ایتالیا و تور آلمان
          می باشد. این تورهای مسفارتی همه روزه با پروازهای مختلف از تهران و
          شهرستان ها با هتل ها مختلف برگزار می شوند.
        </p>
      </div>
    </div>

    <!--menu!-->
    <div
      class="flex justify-between shadow bg-gradient-to-r from-indigo-950 from-10% via-fuchsia-500 via-50% to-rose-500 to-90% px-6 py-4 mt-10"
    >
      <a href="#" class="text-white mr-6 font-bold">تورهای خارجی</a>
      <a
        href="#"
        class="text-black rounded-full ring-gray-300 ring-2 px-2 bg-white text-black font-bold hover:text-orange-500"
      >
        مشاهده تورها
      </a>
    </div>
    <!--menu box!-->
    <div class="flex flex-col md:flex-row lg:flex-row overflow-x-scroll md:overflow-hidden lg:overflow-hidden">
      <span
        class="shadow-md  md:mr-2 lg:mr-4 mr-0 bg-white overflow-hidden mt-10 mx-auto border-solid border border-gray-300 rounded-md"
      >
        <img class="h-48 w-full object-cover" src="turkish.jpg" alt="turkish" />
        <ul class="flex flex-col">
          <div class="h-48 px-3">
            <div class="flex flex-row-reverse justify-end items-center mr-4">
              <h2 class="font-bold text-black py-3 mr-2">ترکیه _ استانبول</h2>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"
                />
              </svg>
            </div>

            <div class="flex flex-row-reverse justify-end items-center mr-2">
              <p class="text-gray-600 py-3 mr-2">دو شب</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-4 h-4"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M21.752 15.002A9.718 9.718 0 0118 15.75c-5.385 0-9.75-4.365-9.75-9.75 0-1.33.266-2.597.748-3.752A9.753 9.753 0 003 11.25C3 16.635 7.365 21 12.75 21a9.753 9.753 0 009.002-5.998z"
                />
              </svg>
            </div>
            <div class="flex flex-row-reverse justify-end items-center mr-2">
              <p class="text-gray-600 py-3 mr-2">5 ستاره</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-5 h-5"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3.75 21h16.5M4.5 3h15M5.25 3v18m13.5-18v18M9 6.75h1.5m-1.5 3h1.5m-1.5 3h1.5m3-6H15m-1.5 3H15m-1.5 3H15M9 21v-3.375c0-.621.504-1.125 1.125-1.125h3.75c.621 0 1.125.504 1.125 1.125V21"
                />
              </svg>
            </div>
          </div>
          <div class="">
            <p class="text-gray-500 justify-center items-center pr-4 pb-4">
              شهری که نیم وجودش اروپا و نیم دیگرش <br />
              آسیاست، شهر گنبد ایاصوفیه، شاهکار <br />
              بیزینس و...
            </p>
          </div>
        </ul>
        <NuxtLink
          to="/firstpagetours"
          class="grid justify-items-center rounded-full bg-blue-600 text-white font-bold w-20 mx-24 mb-2 py-2"
        >
          بیشتر
        </NuxtLink>
      </span>

      <span
        class="shadow-md mr-4 bg-white overflow-hidden mt-10 mx-auto border-solid border border-gray-300 rounded-md"
      >
        <img class="h-48 w-full object-cover" src="turkish.jpg" alt="turkish" />
        <ul class="flex flex-col">
          <div class="h-48 px-3">
            <div class="flex flex-row-reverse justify-end items-center mr-4">
              <h2 class="font-bold text-black py-3 mr-2">ایتالیا _ رم</h2>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"
                />
              </svg>
            </div>

            <div class="flex flex-row-reverse justify-end items-center mr-2">
              <p class="text-gray-600 py-3 mr-2">دو شب</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-4 h-4"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M21.752 15.002A9.718 9.718 0 0118 15.75c-5.385 0-9.75-4.365-9.75-9.75 0-1.33.266-2.597.748-3.752A9.753 9.753 0 003 11.25C3 16.635 7.365 21 12.75 21a9.753 9.753 0 009.002-5.998z"
                />
              </svg>
            </div>
            <div class="flex flex-row-reverse justify-end items-center mr-2">
              <p class="text-gray-600 py-3 mr-2">5 ستاره</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-5 h-5"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3.75 21h16.5M4.5 3h15M5.25 3v18m13.5-18v18M9 6.75h1.5m-1.5 3h1.5m-1.5 3h1.5m3-6H15m-1.5 3H15m-1.5 3H15M9 21v-3.375c0-.621.504-1.125 1.125-1.125h3.75c.621 0 1.125.504 1.125 1.125V21"
                />
              </svg>
            </div>
          </div>
          <div class="">
            <p class="text-gray-500 justify-center items-center pr-4 pb-4">
              شهری که نیم وجودش اروپا و نیم دیگرش <br />
              آسیاست، شهر گنبد ایاصوفیه، شاهکار <br />
              بیزینس و...
            </p>
          </div>
        </ul>
        <a
          href="#"
          class="grid justify-items-center rounded-full bg-blue-600 text-white font-bold w-20 mx-24 mb-2 py-2"
        >
        بیشتر
        </a>
      </span>

      <span
        class="shadow-md mr-4 bg-white overflow-hidden mt-10 mx-auto border-solid border border-gray-300 rounded-md"
      >
        <img class="h-48 w-full object-cover" src="turkish.jpg" alt="turkish" />
        <ul class="flex flex-col">
          <div class="h-48 px-3">
            <div class="flex flex-row-reverse justify-end items-center mr-4">
              <h2 class="font-bold text-black py-3 mr-2">اسپانیا _ مادرید</h2>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"
                />
              </svg>
            </div>

            <div class="flex flex-row-reverse justify-end items-center mr-2">
              <p class="text-gray-600 py-3 mr-2">دو شب</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-4 h-4"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M21.752 15.002A9.718 9.718 0 0118 15.75c-5.385 0-9.75-4.365-9.75-9.75 0-1.33.266-2.597.748-3.752A9.753 9.753 0 003 11.25C3 16.635 7.365 21 12.75 21a9.753 9.753 0 009.002-5.998z"
                />
              </svg>
            </div>
            <div class="flex flex-row-reverse justify-end items-center mr-2">
              <p class="text-gray-600 py-3 mr-2">5 ستاره</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-5 h-5"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3.75 21h16.5M4.5 3h15M5.25 3v18m13.5-18v18M9 6.75h1.5m-1.5 3h1.5m-1.5 3h1.5m3-6H15m-1.5 3H15m-1.5 3H15M9 21v-3.375c0-.621.504-1.125 1.125-1.125h3.75c.621 0 1.125.504 1.125 1.125V21"
                />
              </svg>
            </div>
          </div>
          <div class="">
            <p class="text-gray-500 justify-center items-center pr-4 pb-4">
              شهری که نیم وجودش اروپا و نیم دیگرش <br />
              آسیاست، شهر گنبد ایاصوفیه، شاهکار <br />
              بیزینس و...
            </p>
          </div>
        </ul>
        <a
          href="#"
          class="grid justify-items-center rounded-full bg-blue-600 text-white font-bold w-20 mx-24 mb-2 py-2"
        >
       بیشتر
        </a>
      </span>

      <span
        class="shadow-md mr-4 bg-white overflow-hidden mt-10 mx-auto border-solid border border-gray-300 rounded-md"
      >
        <img class="h-48 w-full object-cover" src="turkish.jpg" alt="turkish" />
        <ul class="flex flex-col">
          <div class="h-48 px-3">
            <div class="flex flex-row-reverse justify-end items-center mr-4">
              <h2 class="font-bold text-black py-3 mr-2">کانادا _ تورنتو</h2>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"
                />
              </svg>
            </div>

            <div class="flex flex-row-reverse justify-end items-center mr-2">
              <p class="text-gray-600 py-3 mr-2">دو شب</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-4 h-4"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M21.752 15.002A9.718 9.718 0 0118 15.75c-5.385 0-9.75-4.365-9.75-9.75 0-1.33.266-2.597.748-3.752A9.753 9.753 0 003 11.25C3 16.635 7.365 21 12.75 21a9.753 9.753 0 009.002-5.998z"
                />
              </svg>
            </div>
            <div class="flex flex-row-reverse justify-end items-center mr-2">
              <p class="text-gray-600 py-3 mr-2">5 ستاره</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-5 h-5"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3.75 21h16.5M4.5 3h15M5.25 3v18m13.5-18v18M9 6.75h1.5m-1.5 3h1.5m-1.5 3h1.5m3-6H15m-1.5 3H15m-1.5 3H15M9 21v-3.375c0-.621.504-1.125 1.125-1.125h3.75c.621 0 1.125.504 1.125 1.125V21"
                />
              </svg>
            </div>
          </div>
          <div class="">
            <p class="text-gray-500 justify-center items-center pr-4 pb-4">
              شهری که نیم وجودش اروپا و نیم دیگرش <br />
              آسیاست، شهر گنبد ایاصوفیه، شاهکار <br />
              بیزینس و...
            </p>
          </div>
        </ul>
        <NuxtLink
          to="/firstpagetours"
          class="grid justify-items-center rounded-full bg-blue-600 text-white font-bold w-20 mx-24 mb-2 py-2"
        >
          بیشتر
        </NuxtLink>
      </span>
    </div>
  </div>
</template>
