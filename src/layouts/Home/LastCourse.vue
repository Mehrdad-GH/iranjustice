<template>
  <div>
    <div class="flex justify-between lg:px-32 p-10">
      <div class="flex items-center">
        <div class="">
          <h3 class="text-secondary">Latest</h3>
          <h1 class="text-gold">Courses</h1>
        </div>
        <div
          class="w-[64.80px] h-[64.80px] flex justify-center items-center ml-5 bg-gradient-to-bl from-slate-400 to-white rounded-2xl"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="38"
            height="38"
            viewBox="0 0 38 38"
            fill="none"
          >
            <path
              opacity="0.4"
              d="M33.7735 11.7839C33.1101 11.366 32.2947 11.329 31.5996 11.6827L29.2531 12.8674C28.3854 13.3046 27.847 14.1887 27.847 15.1724V24.4088C27.847 25.3926 28.3854 26.2751 29.2531 26.7155L31.598 27.8986C31.9163 28.0625 32.2567 28.1413 32.5971 28.1413C33.0056 28.1413 33.4109 28.0256 33.7735 27.7989C34.4369 27.3826 34.8328 26.6608 34.8328 25.87V13.7145C34.8328 12.9236 34.4369 12.2019 33.7735 11.7839Z"
              fill="#1E2D48"
            />
            <path
              d="M18.8494 31.6665H9.67864C5.84376 31.6665 3.16632 29.0223 3.16632 25.2367V14.3463C3.16632 10.5591 5.84376 7.9165 9.67864 7.9165H18.8494C22.6843 7.9165 25.3617 10.5591 25.3617 14.3463V25.2367C25.3617 29.0223 22.6843 31.6665 18.8494 31.6665Z"
              fill="#1E2D48"
            />
          </svg>
        </div>
      </div>

      <div class="flex items-center ">
        <button class="bg-slate-700 ml-10 rounded-full" @click="goBack">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="39"
            height="39"
            viewBox="0 0 39 39"
            fill="none"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="39"
              height="39"
              viewBox="0 0 39 39"
              fill="none"
            >
              <path
                d="M27.4571 17.7873L16.5001 24.5381C16.2547 24.6885 15.9405 24.6741 15.7108 24.4965C14.6698 23.6948 13.7398 22.882 13.1192 22.1988C13.1192 22.1988 12.5847 21.6515 12.3533 21.3043C11.9798 20.8307 11.8 20.2115 11.8 19.6098C11.8 18.9346 11.997 18.2962 12.3893 17.7857C12.4784 17.6945 12.8176 17.2929 13.138 16.9649C15.0074 14.9232 19.8872 11.5502 22.4538 10.5278C22.8273 10.363 23.8246 10.019 24.3419 9.99976C24.8405 9.99976 25.322 10.1086 25.7846 10.347C26.3536 10.675 26.799 11.1838 27.0491 11.787C27.2101 12.2063 27.4586 13.4639 27.4586 13.5007C27.6196 14.3984 27.74 15.6592 27.7994 17.1313C27.8103 17.3953 27.6775 17.6513 27.4571 17.7873Z"
                fill="white"
              />
              <path
                opacity="0.4"
                d="M26.724 21.4233C27.207 21.124 27.815 21.5065 27.7915 22.0809C27.7337 23.4282 27.6337 24.6154 27.5118 25.4987C27.493 25.5179 27.2445 27.0843 26.9584 27.614C26.4598 28.598 25.4814 29.1997 24.4294 29.1997L24.3419 29.1997C23.6635 29.1821 22.2208 28.5804 22.2208 28.5436C21.494 28.2412 20.5453 27.7292 19.5246 27.1131C19.065 26.8347 19.0541 26.1515 19.5136 25.8683L26.724 21.4233Z"
                fill="white"
              />
            </svg>
          </svg>
        </button>
        <button class="bg-slate-700 rounded-full ml-2" @click="goNext">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="40"
            height="39"
            viewBox="0 0 40 39"
            fill="none"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="40"
              height="39"
              viewBox="0 0 40 39"
              fill="none"
            >
              <path
                d="M12.3429 21.6121L23.2999 14.8613C23.5453 14.7109 23.8595 14.7253 24.0893 14.9029C25.1302 15.7046 26.0603 16.5174 26.6808 17.2006C26.6808 17.2006 27.2154 17.7479 27.4467 18.0951C27.8203 18.5687 28 19.1879 28 19.7896C28 20.4648 27.8031 21.1032 27.4107 21.6137C27.3216 21.7049 26.9825 22.1065 26.662 22.4345C24.7926 24.4762 19.9128 27.8492 17.3463 28.8716C16.9727 29.0364 15.9755 29.3805 15.4581 29.3997C14.9595 29.3997 14.4781 29.2909 14.0154 29.0524C13.4464 28.7244 13.001 28.2156 12.7509 27.6124C12.5899 27.1931 12.3414 25.9355 12.3414 25.8987C12.1804 25.001 12.06 23.7402 12.0006 22.2681C11.9897 22.0041 12.1225 21.7481 12.3429 21.6121Z"
                fill="white"
              />
              <path
                opacity="0.4"
                d="M13.076 17.9761C12.5931 18.2754 11.985 17.8929 12.0085 17.3185C12.0663 15.9712 12.1663 14.784 12.2883 13.9007C12.307 13.8815 12.5555 12.3151 12.8416 11.7854C13.3402 10.8014 14.3187 10.1998 15.3706 10.1998H15.4581C16.1365 10.2174 17.5792 10.819 17.5792 10.8558C18.306 11.1582 19.2548 11.6702 20.2754 12.2863C20.735 12.5647 20.7459 13.2479 20.2864 13.5311L13.076 17.9761Z"
                fill="white"
              />
            </svg>
          </svg>
        </button>
      </div>
    </div>
    <div>
      <swiper-container
        init="true"
        ref="swiperRefres"
        :slidesPerView="3"
        :pagination="{ clickable: true }"
        :modules="modules"
        :breakpoints="{
          '300': {
            slidesPerView: 1,
            spaceBetween: 10,
          },
          '640': {
            slidesPerView: 1,
            spaceBetween: 10,
          },
          '768': {
            slidesPerView: 2,
            spaceBetween: 0,
          },
          '1024': {
            slidesPerView: 2,
            spaceBetween: 10,
          },
          '1350': {
            slidesPerView: 3,
            spaceBetween: 10,
          },
        }"
        class="mySwiper"
      >
        <swiper-slide class="pb-10 flex justify-center" v-for="number in num">
          <div class="w-[285px] h-[500px] bg-white rounded-[26px] shadow">
            <div class="flex flex-col items-center justify-center py-3">
              <img src="/images/Rectangle29.png" alt="" />
              <div
                class="w-[254.40px] h-[55.20px] -translate-y-10 bg-zinc-500 bg-opacity-50 rounded-bl-[26.40px] rounded-br-[26.40px] backdrop-blur-3xl"
              >
                <div class="flex items-center h-full ">
                  <div class="ml-5">duration:</div>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="17"
                    height="17"
                    viewBox="0 0 17 17"
                    fill="none"
                  >
                    <path
                      opacity="0.4"
                      d="M15.0651 8.20011C15.0651 11.8828 12.0804 14.8668 8.39839 14.8668C4.71639 14.8668 1.73172 11.8828 1.73172 8.20011C1.73172 4.51878 4.71639 1.53345 8.39839 1.53345C12.0804 1.53345 15.0651 4.51878 15.0651 8.20011Z"
                      fill="white"
                    />
                    <path
                      d="M10.7812 10.7431C10.6939 10.7431 10.6059 10.7205 10.5252 10.6731L7.90788 9.11181C7.75722 9.02114 7.66455 8.85781 7.66455 8.68181V5.31714C7.66455 5.04114 7.88855 4.81714 8.16455 4.81714C8.44055 4.81714 8.66455 5.04114 8.66455 5.31714V8.39781L11.0379 9.81314C11.2746 9.95514 11.3526 10.2618 11.2112 10.4991C11.1172 10.6558 10.9512 10.7431 10.7812 10.7431Z"
                      fill="white"
                    />
                  </svg>
                  <div class="flex justify-end w-[50%] text-sm mt-1">
                    <p>45 min</p>
                  </div>
                </div>
              </div>
            </div>
            <h1
              class="-translate-y-10 w-[80%] text-center ml-6"
            >
              Lorem ipsum dolor sit amet consectetur ad
            </h1>
            <div class="-translate-y-5">
              <hr
                class="border-dashed  opacity-10 border border-black"
              />
            </div>
            <div class="flex justify-around text-sm -translate-y-2">
              <h2> category:</h2>
              <p class="text-xs">lorem ipsom </p>
            </div>
            <div class="flex justify-around mt-7">
              <button
                class="text-sm text-white px-4 pt-2 pb-2 w-[95.20px] h-[55.40px] bg-gold rounded-[9.60px] shadow-2xl"
              >
                <span>View <br /> Course </span>
              </button>

              <div class="flex flex-col">
                <del class="text-black text-opacity-25 text-base font-normal"
                  >560
                  <span
                    class="text-white text-xs bg-black p-1 rounded-full px-2 py-0"
                    >%15</span
                  ></del
                >
                <h1>450 <span class="text-xs">$</span></h1>
              </div>
            </div>
          </div>
        </swiper-slide>
      </swiper-container>
    </div>
  </div>
</template>

<script setup>
import { register } from "swiper/element/bundle";
import { ref } from "vue";
import { Pagination } from "swiper/modules";
import "swiper/css/pagination";
register();

const modules = [Pagination];
const num = [1, 2, 3, 4, 5];

const swiperRef = ref(null);
const swiperRefres = ref(null);

const goNext = () => {
  swiperRefres.value.swiper.slideNext();
};
const goBack = () => {
  swiperRefres.value.swiper.slidePrev();
};
const next = () => {
  swiperRef.value.swiper.slideNext();
};
const back = () => {
  swiperRef.value.swiper.slidePrev();
};
</script>
