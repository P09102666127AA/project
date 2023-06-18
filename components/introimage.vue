<template>
  <div>
    <div
      id="carouselExampleCaptions"
      class="relative"
      data-te-carousel-init
      data-te-carousel-slide
    >
      <!--Carousel indicators-->
      <div
        class="absolute bottom-0 left-0 right-0 z-[2] mx-[15%] mb-4 flex list-none justify-center p-0"
        data-te-carousel-indicators
      >
        <button
          type="button"
          data-te-target="#carouselExampleCaptions"
          data-te-slide-to="0"
          data-te-carousel-active
          class="mx-[3px] box-content h-[3px] w-[30px] flex-initial cursor-pointer border-0 border-y-[10px] border-solid border-transparent bg-white bg-clip-padding p-0 -indent-[999px] opacity-50 transition-opacity duration-[600ms] ease-[cubic-bezier(0.25,0.1,0.25,1.0)] motion-reduce:transition-none"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-te-target="#carouselExampleCaptions"
          data-te-slide-to="1"
          class="mx-[3px] box-content h-[3px] w-[30px] flex-initial cursor-pointer border-0 border-y-[10px] border-solid border-transparent bg-white bg-clip-padding p-0 -indent-[999px] opacity-50 transition-opacity duration-[600ms] ease-[cubic-bezier(0.25,0.1,0.25,1.0)] motion-reduce:transition-none"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-te-target="#carouselExampleCaptions"
          data-te-slide-to="2"
          class="mx-[3px] box-content h-[3px] w-[30px] flex-initial cursor-pointer border-0 border-y-[10px] border-solid border-transparent bg-white bg-clip-padding p-0 -indent-[999px] opacity-50 transition-opacity duration-[600ms] ease-[cubic-bezier(0.25,0.1,0.25,1.0)] motion-reduce:transition-none"
          aria-label="Slide 3"
        ></button>
      </div>

      <!--Carousel items-->
      <div
        class="relative w-full overflow-hidden after:clear-both after:block "
      >
        <!--First item-->
        <div
          class="relative float-left -mr-[100%] w-full transition-transform duration-[600ms] ease-in-out motion-reduce:transition-none"
          data-te-carousel-active
          data-te-carousel-item
          style="backface-visibility: hidden"
        >
          <img
            src="photo2 .jpg"
            class="block w-full h-45"
            alt="تور مسافرتی ، تور تفریحی ، تور خارجی ، تور های خارجی ، تور ایرانگردی ، رزرو هتل های خارجی ، رزرو هتل های داخلی"
          />
          <div class="top-0 text-center flex flex-col md:absolute lg:absolute">
            <h1
              class="lg:text-2xl md:text-base text-orange-500 md:mt-20 lg:mt-20 md:mx-20 lg:mx-20 flex justify-center mt-10"
            >
              سفر خود را با اطمینان به ما بسپارید!
            </h1>
            <p
              class="mt-14 text-xl text-bold text-violet-800 lg:text-2xl md:text-base md:mx-48 lg:mx-48 flex justify-center mb-10"
            >
              بدرقه پرواز آرین
            </p>
          </div>
        </div>
        <!--Second item-->
        <div
          class="relative float-left -mr-[100%] hidden w-full transition-transform duration-[600ms] ease-in-out motion-reduce:transition-none"
          data-te-carousel-item
          style="backface-visibility: hidden"
        >
          <img
            src="photo2 .jpg"
            class="block w-full h-45"
            alt="تور مسافرتی ، تور تفریحی ، تور خارجی ، تور های خارجی ، تور ایرانگردی ، رزرو هتل های خارجی ، رزرو هتل های داخلی"
          />
          <div class="top-0 text-center flex flex-col md:absolute lg:absolute">
            <h1
              class="lg:text-2xl md:text-base text-orange-500 md:mt-20 lg:mt-20 md:mx-20 lg:mx-20 flex justify-center mt-10"
            >
              سفر خود را با اطمینان به ما بسپارید!
            </h1>
            <p
              class="mt-14 text-xl text-bold text-violet-800 lg:text-2xl md:text-base md:mx-48 lg:mx-48 flex justify-center mb-10"
            >
              بدرقه پرواز آرین
            </p>
          </div>
        </div>
        <!--Third item-->
        <div
          class="relative float-left -mr-[100%] hidden w-full transition-transform duration-[600ms] ease-in-out motion-reduce:transition-none"
          data-te-carousel-item
          style="backface-visibility: hidden"
        >
          <img
            src="photo2 .jpg"
            class="block w-full h-45"
            alt="تور مسافرتی ، تور تفریحی ، تور خارجی ، تور های خارجی ، تور ایرانگردی ، رزرو هتل های خارجی ، رزرو هتل های داخلی"
          />
          <div class="top-0 text-center flex flex-col md:absolute lg:absolute">
            <h1
              class="lg:text-2xl md:text-base text-orange-500 md:mt-20 lg:mt-20 md:mx-20 lg:mx-20 flex justify-center mt-10"
            >
              سفر خود را با اطمینان به ما بسپارید!
            </h1>
            <p
              class="mt-14 text-xl text-bold text-violet-800 lg:text-2xl md:text-base md:mx-48 lg:mx-48 flex justify-center mb-10"
            >
              بدرقه پرواز آرین
            </p>
          </div>
        </div>
      </div>

      <!--Carousel controls - prev item-->
      <button
        class="absolute bottom-0 left-0 top-0 z-[1] flex w-[10%] items-center justify-center border-0 bg-none p-0 text-center text-white opacity-50 transition-opacity duration-150 ease-[cubic-bezier(0.25,0.1,0.25,1.0)] hover:text-white hover:no-underline hover:opacity-90 hover:outline-none focus:text-white focus:no-underline focus:opacity-90 focus:outline-none motion-reduce:transition-none"
        type="button"
        data-te-target="#carouselExampleCaptions"
        data-te-slide="prev"
      >
        <span class="inline-block h-8 w-8">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="h-10 w-10"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15.75 19.5L8.25 12l7.5-7.5"
            />
          </svg>
        </span>
        <span
          class="!absolute !-m-px !h-px !w-px !overflow-hidden !whitespace-nowrap !border-0 !p-0 ![clip:rect(0,0,0,0)]"
          >Previous</span
        >
      </button>
      <!--Carousel controls - next item-->
      <button
        class="absolute bottom-0 right-0 top-0 z-[1] flex w-[10%] items-center justify-center border-0 bg-none p-0 text-center text-white opacity-50 transition-opacity duration-150 ease-[cubic-bezier(0.25,0.1,0.25,1.0)] hover:text-white hover:no-underline hover:opacity-90 hover:outline-none focus:text-white focus:no-underline focus:opacity-90 focus:outline-none motion-reduce:transition-none"
        type="button"
        data-te-target="#carouselExampleCaptions"
        data-te-slide="next"
      >
        <span class="inline-block h-8 w-8">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="h-10 w-10"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M8.25 4.5l7.5 7.5-7.5 7.5"
            />
          </svg>
        </span>
        <span
          class="!absolute !-m-px !h-px !w-px !overflow-hidden !whitespace-nowrap !border-0 !p-0 ![clip:rect(0,0,0,0)]"
          >Next</span
        >
      </button>
    </div>

    <div class="flex justify-center">
      <p class="text-orange-600 text-center font-bold mt-10">
        بدرقه پرواز آرین;مرکز اصلی رزرواسیون کامل ترین
        <span
          class="text-blue-600 inline-flex items-baseline text-center font-bold pt-2"
        >
          تورهای داخلی و خارجی 1402
        </span>
      </p>
    </div>
    <div
      class="text-black mt-4 py-2 text-center dark:text-white px-10 md:mx-10 lg:mx-80"
    >
      با مجوز رسمی از سازمان میراث فرهنگی و گردشگری و بالاترین درصد رضایت
      مسافرین تابحال
    </div>
  </div>
</template>
