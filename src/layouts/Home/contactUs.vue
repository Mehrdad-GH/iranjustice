<template>
  <div class="w-full mt-[600px] justify-center items-center hidden lg:flex">
    <div>
      <div
        class="absolute translate-y-40 p-8 -translate-x-8 w-56 h-24 bg-white shadow-2xl rounded-[27px] z-50"
      >
        <div class="-translate-y-14 translate-x-10">
          <img class="" src="/images/phone.png" alt="" />
          <div class="-translate-y-28 mt-1 -translate-x-14">
            <h1>Phone number</h1>
            <p class="text-sm">(512)555-1234</p>
          </div>
        </div>
      </div>
    </div>

    <div class="flex items-end justify-start mb-52">
      <img class="absolute z-50" src="/images/Guy.svg" alt="" />
    </div>

    <div class="w-[70%] h-[390px] bg-zinc-200 rounded-[25px] z-40">
      <div class="flex flex-col ml-20 w-4/12 mt-10 justify-center h-full">
        <h1 class="text-2xl mb-20">
          <span class="text-gold"> Consultation </span> request
        </h1>

        <p class="text-sm">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Impedit,
          dignissimos.adipisicing elit. Impedit, dignissimos.adipisicing elit.
          Impedit, dignissimos.
        </p>
      </div>
    </div>

    <div class="absolute flex translate-x-72 -translate-y-10 z-50">
      <div class="w-[480px] h-[615px] bg-white rounded-[27px] shadow z-40 p-5">
        <div class="flex flex-col">
          <div>
            <div class="relative mt-2 rounded-md shadow-sm mb-4">
              <div
                class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
              >
                <span class="text-gray-900 sm:text-sm"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="25"
                    viewBox="0 0 24 25"
                    fill="none"
                  >
                    <g opacity="0.1">
                      <path
                        d="M16.3402 2.5C19.7302 2.5 22.0002 4.88 22.0002 8.42V16.59C22.0002 20.12 19.7302 22.5 16.3402 22.5H7.67018C4.28018 22.5 2.00018 20.12 2.00018 16.59V8.42C2.00018 4.88 4.28018 2.5 7.67018 2.5H16.3402ZM16.4802 11.301C15.8202 11.301 15.2802 11.84 15.2802 12.5C15.2802 13.16 15.8202 13.7 16.4802 13.7C17.1402 13.7 17.6702 13.16 17.6702 12.5C17.6702 11.84 17.1402 11.301 16.4802 11.301ZM12.0002 11.301C11.3402 11.301 10.8002 11.84 10.8002 12.5C10.8002 13.16 11.3402 13.7 12.0002 13.7C12.6602 13.7 13.2002 13.16 13.2002 12.5C13.2002 11.84 12.6602 11.301 12.0002 11.301ZM7.52018 11.301C6.86018 11.301 6.32018 11.84 6.32018 12.5C6.32018 13.16 6.86018 13.7 7.52018 13.7C8.18018 13.7 8.72018 13.16 8.72018 12.5C8.72018 11.84 8.18018 11.301 7.52018 11.301Z"
                        fill="black"
                      />
                    </g></svg
                ></span>
              </div>
              <input
                type="text"
                name="price"
                id="price"
                class="block w-full rounded-[15px] border-0 pl-11 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
                placeholder=" Subject"
              />
            </div>
          </div>

          <div>
            <div class="relative mt-2 rounded-[15px] shadow-sm mb-4">
              <div
                class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
              >
                <span class="text-gray-500 sm:text-sm"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="25"
                    viewBox="0 0 24 25"
                    fill="none"
                  >
                    <g opacity="0.1">
                      <path
                        d="M12 15.6739C16.3386 15.6739 20 16.3789 20 19.099C20 21.82 16.3146 22.5 12 22.5C7.66237 22.5 4 21.795 4 19.075C4 16.3539 7.68538 15.6739 12 15.6739ZM12 2.5C14.9391 2.5 17.294 4.85402 17.294 7.79105C17.294 10.7281 14.9391 13.0831 12 13.0831C9.0619 13.0831 6.70601 10.7281 6.70601 7.79105C6.70601 4.85402 9.0619 2.5 12 2.5Z"
                        fill="black"
                      />
                    </g></svg
                ></span>
              </div>
              <input
                type="text"
                name="price"
                id="price"
                class="block w-full rounded-[15px] border-0 pl-11 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
                placeholder="Name & family"
              />
            </div>
          </div>

          <div>
            <div class="relative mt-2 rounded-md shadow-sm mb-4">
              <div
                class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
              >
                <span class="text-gray-500 sm:text-sm"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                  >
                    <g opacity="0.1">
                      <path
                        d="M12.02 2C17.7 2 22 6.65699 22 11.985C22 18.1642 16.96 22 12 22C10.36 22 8.54 21.5593 7.08 20.698C6.57 20.3876 6.14 20.1572 5.59 20.3375L3.57 20.9384C3.06 21.0986 2.6 20.698 2.75 20.1572L3.42 17.9139C3.53 17.6034 3.51 17.2729 3.35 17.0125C2.49 15.4301 2 13.6975 2 12.015C2 6.74712 6.21 2 12.02 2ZM16.59 10.7431C15.88 10.7431 15.31 11.314 15.31 12.025C15.31 12.7261 15.88 13.307 16.59 13.307C17.3 13.307 17.87 12.7261 17.87 12.025C17.87 11.314 17.3 10.7431 16.59 10.7431ZM11.98 10.7431C11.28 10.7331 10.7 11.314 10.7 12.015C10.7 12.7261 11.27 13.2969 11.98 13.307C12.69 13.307 13.26 12.7261 13.26 12.025C13.26 11.314 12.69 10.7431 11.98 10.7431ZM7.37 10.7431C6.66 10.7431 6.09 11.314 6.09 12.025C6.09 12.7261 6.67 13.307 7.37 13.307C8.08 13.2969 8.65 12.7261 8.65 12.025C8.65 11.314 8.08 10.7431 7.37 10.7431Z"
                        fill="black"
                      />
                    </g></svg
                ></span>
              </div>
              <input
                type="text"
                name="price"
                id="price"
                class="block w-full rounded-[15px] border-0 pl-11 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
                placeholder=" Phone number "
              />
            </div>
          </div>

          <div>
            <div class="relative mt-2 rounded-md shadow-sm mb-4">
              <div
                class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
              >
                <span class="text-gray-500 sm:text-sm"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                  >
                    <g opacity="0.1">
                      <path
                        d="M12.02 2C17.7 2 22 6.65699 22 11.985C22 18.1642 16.96 22 12 22C10.36 22 8.54 21.5593 7.08 20.698C6.57 20.3876 6.14 20.1572 5.59 20.3375L3.57 20.9384C3.06 21.0986 2.6 20.698 2.75 20.1572L3.42 17.9139C3.53 17.6034 3.51 17.2729 3.35 17.0125C2.49 15.4301 2 13.6975 2 12.015C2 6.74712 6.21 2 12.02 2ZM16.59 10.7431C15.88 10.7431 15.31 11.314 15.31 12.025C15.31 12.7261 15.88 13.307 16.59 13.307C17.3 13.307 17.87 12.7261 17.87 12.025C17.87 11.314 17.3 10.7431 16.59 10.7431ZM11.98 10.7431C11.28 10.7331 10.7 11.314 10.7 12.015C10.7 12.7261 11.27 13.2969 11.98 13.307C12.69 13.307 13.26 12.7261 13.26 12.025C13.26 11.314 12.69 10.7431 11.98 10.7431ZM7.37 10.7431C6.66 10.7431 6.09 11.314 6.09 12.025C6.09 12.7261 6.67 13.307 7.37 13.307C8.08 13.2969 8.65 12.7261 8.65 12.025C8.65 11.314 8.08 10.7431 7.37 10.7431Z"
                        fill="black"
                      />
                    </g></svg
                ></span>
              </div>
              <textarea
                id="about"
                name="about"
                rows="5"
                placeholder=" Your message"
                class="block w-full rounded-[15px] border-0 pl-11 py-5 pr-5 resize-none text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
              ></textarea>
            </div>
          </div>

          <div class="flex justify-end">
            <div class="relative mt-2 rounded-md shadow-sm mb-4">
              <div
                class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
              >
                <span class="text-gray-500 sm:text-sm"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                  >
                    <g opacity="0.1">
                      <path
                        d="M16.3402 2C19.7302 2 22.0002 4.38 22.0002 7.92V16.09C22.0002 19.62 19.7302 22 16.3402 22H7.67018C4.28018 22 2.00018 19.62 2.00018 16.09V7.92C2.00018 4.38 4.28018 2 7.67018 2H16.3402ZM16.4802 10.801C15.8202 10.801 15.2802 11.34 15.2802 12C15.2802 12.66 15.8202 13.2 16.4802 13.2C17.1402 13.2 17.6702 12.66 17.6702 12C17.6702 11.34 17.1402 10.801 16.4802 10.801ZM12.0002 10.801C11.3402 10.801 10.8002 11.34 10.8002 12C10.8002 12.66 11.3402 13.2 12.0002 13.2C12.6602 13.2 13.2002 12.66 13.2002 12C13.2002 11.34 12.6602 10.801 12.0002 10.801ZM7.52018 10.801C6.86018 10.801 6.32018 11.34 6.32018 12C6.32018 12.66 6.86018 13.2 7.52018 13.2C8.18018 13.2 8.72018 12.66 8.72018 12C8.72018 11.34 8.18018 10.801 7.52018 10.801Z"
                        fill="black"
                      />
                    </g></svg
                ></span>
              </div>

              <input
                type="number "
                name="price"
                id="price"
                class="w-80 rounded-[15px] border-0 pl-11 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
                placeholder="  captcha "
              />
            </div>
          </div>

          <div class="absolute bottom-16 mb-3">
            <h1
              class="w-fit rounded-[15px] border-0 pl-7 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
            >
              858569
            </h1>
          </div>

          <div>
            <button
              class="w-full bg-gold rounded-[10px] opacity-75 hover:opacity-100 transition-opacity text-white font-bold py-2 px-4"
            >
              Submit
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div
    class="w-full mt-20 justify-center items-center flex flex-wrap lg:hidden"
  >
    <div class="flex justify-start">
      <div
        class="w-10 h-[300px] translate-x-7 -translate-y-5 bg-slate-800 rounded-[25px] -z-40"
      ></div>
    </div>

    <div class="flex items-end justify-start mb-52 ">
      <img class="absolute z-10 w-72 m" src="/images/resGuy.png" alt="" />
    </div>

    <div class="w-[80%] h-[390px] flex p-5 bg-zinc-200 rounded-[25px] z-0">
      <div class="w-full flex flex-col mt-5 justify-center h-full text-center">
        <h1 class="text-2xl mt-">
          <span class="text-gold"> Consultation </span>request
        </h1>

        <p class="text-sm mb-1 mt-5">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem, earum.
        </p>
        <div
          class="flex mb-10 translate-y-10 w-full h-20 bg-white shadow-2xl rounded-[27px] items-center"
        >
          <span class="flex justify-center ml-10 bg-gold w-20 rounded-xl"
            ><svg
              class="w-7"
              xmlns="http://www.w3.org/2000/svg"
              width="50"
              height="50"
              viewBox="0 0 50 50"
              fill="none"
            >
              <path
                opacity="0.4"
                d="M29.9021 5.20825C37.6125 6.0645 43.7042 12.1478 44.5687 19.8583"
                stroke="white"
                stroke-width="2.38"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                opacity="0.4"
                d="M29.9021 12.5896C33.5917 13.3063 36.475 16.1917 37.1937 19.8813"
                stroke="white"
                stroke-width="2.38"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M22.9823 25.9841C31.2927 34.2923 33.178 24.6806 38.4693 29.9683C43.5704 35.0682 46.5046 36.0899 40.0392 42.5514C39.2296 43.202 34.086 51.0296 16.0093 32.9576C-2.06961 14.8833 5.75325 9.73418 6.40404 8.92481C12.8828 2.44543 13.8892 5.39447 18.9904 10.4944C24.2794 15.7843 14.6719 17.6758 22.9823 25.9841Z"
                stroke="white"
                stroke-width="2.38"
                stroke-linecap="round"
                stroke-linejoin="round"
              /></svg
          ></span>

          <div class="flex flex-col items-center text-md justify-center w-full">
            <h1 class="bold">Phone number</h1>
            <p class="text-sm bold">(512)555-1234</p>
          </div>
        </div>
      </div>
    </div>
    <div class="w-full -translate-y-5 flex z-0">
      <div class="w-[480px] h-[615px] bg-white rounded-[27px] shadow z-40 p-5">
        <div class="flex flex-col">
          <div class="relative rounded-md shadow-sm mb-4">
            <div
              class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
            >
              <span class="text-gray-500 sm:text-sm"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="25"
                  viewBox="0 0 24 25"
                  fill="none"
                >
                  <g opacity="0.1">
                    <path
                      d="M16.3402 2.5C19.7302 2.5 22.0002 4.88 22.0002 8.42V16.59C22.0002 20.12 19.7302 22.5 16.3402 22.5H7.67018C4.28018 22.5 2.00018 20.12 2.00018 16.59V8.42C2.00018 4.88 4.28018 2.5 7.67018 2.5H16.3402ZM16.4802 11.301C15.8202 11.301 15.2802 11.84 15.2802 12.5C15.2802 13.16 15.8202 13.7 16.4802 13.7C17.1402 13.7 17.6702 13.16 17.6702 12.5C17.6702 11.84 17.1402 11.301 16.4802 11.301ZM12.0002 11.301C11.3402 11.301 10.8002 11.84 10.8002 12.5C10.8002 13.16 11.3402 13.7 12.0002 13.7C12.6602 13.7 13.2002 13.16 13.2002 12.5C13.2002 11.84 12.6602 11.301 12.0002 11.301ZM7.52018 11.301C6.86018 11.301 6.32018 11.84 6.32018 12.5C6.32018 13.16 6.86018 13.7 7.52018 13.7C8.18018 13.7 8.72018 13.16 8.72018 12.5C8.72018 11.84 8.18018 11.301 7.52018 11.301Z"
                      fill="black"
                    />
                  </g></svg
              ></span>
            </div>
            <input
              type="text"
              name="price"
              id="price"
              class="block w-full rounded-[15px] border-0 pl-11 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
              placeholder=" Subject"
            />
          </div>
        </div>

        <div>
          <div class="relative mt-2 rounded-[15px] shadow-sm mb-4">
            <div
              class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
            >
              <span class="text-gray-500 sm:text-sm"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="25"
                  viewBox="0 0 24 25"
                  fill="none"
                >
                  <g opacity="0.1">
                    <path
                      d="M12 15.6739C16.3386 15.6739 20 16.3789 20 19.099C20 21.82 16.3146 22.5 12 22.5C7.66237 22.5 4 21.795 4 19.075C4 16.3539 7.68538 15.6739 12 15.6739ZM12 2.5C14.9391 2.5 17.294 4.85402 17.294 7.79105C17.294 10.7281 14.9391 13.0831 12 13.0831C9.0619 13.0831 6.70601 10.7281 6.70601 7.79105C6.70601 4.85402 9.0619 2.5 12 2.5Z"
                      fill="black"
                    />
                  </g></svg
              ></span>
            </div>
            <input
              type="text"
              name="price"
              id="price"
              class="block w-full rounded-[15px] border-0 pl-11 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
              placeholder="Name & family"
            />
          </div>
        </div>

        <div>
          <div class="relative mt-2 rounded-md shadow-sm mb-4">
            <div
              class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
            >
              <span class="text-gray-500 sm:text-sm"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  fill="none"
                >
                  <g opacity="0.1">
                    <path
                      d="M12.02 2C17.7 2 22 6.65699 22 11.985C22 18.1642 16.96 22 12 22C10.36 22 8.54 21.5593 7.08 20.698C6.57 20.3876 6.14 20.1572 5.59 20.3375L3.57 20.9384C3.06 21.0986 2.6 20.698 2.75 20.1572L3.42 17.9139C3.53 17.6034 3.51 17.2729 3.35 17.0125C2.49 15.4301 2 13.6975 2 12.015C2 6.74712 6.21 2 12.02 2ZM16.59 10.7431C15.88 10.7431 15.31 11.314 15.31 12.025C15.31 12.7261 15.88 13.307 16.59 13.307C17.3 13.307 17.87 12.7261 17.87 12.025C17.87 11.314 17.3 10.7431 16.59 10.7431ZM11.98 10.7431C11.28 10.7331 10.7 11.314 10.7 12.015C10.7 12.7261 11.27 13.2969 11.98 13.307C12.69 13.307 13.26 12.7261 13.26 12.025C13.26 11.314 12.69 10.7431 11.98 10.7431ZM7.37 10.7431C6.66 10.7431 6.09 11.314 6.09 12.025C6.09 12.7261 6.67 13.307 7.37 13.307C8.08 13.2969 8.65 12.7261 8.65 12.025C8.65 11.314 8.08 10.7431 7.37 10.7431Z"
                      fill="black"
                    />
                  </g></svg
              ></span>
            </div>
            <input
              type="text"
              name="price"
              id="price"
              class="block w-full rounded-[15px] border-0 pl-11 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
              placeholder=" phone number "
            />
          </div>
        </div>

        <div>
          <div class="relative mt-2 rounded-md shadow-sm mb-4">
            <div
              class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
            >
              <span class="text-gray-500 sm:text-sm"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  fill="none"
                >
                  <g opacity="0.1">
                    <path
                      d="M12.02 2C17.7 2 22 6.65699 22 11.985C22 18.1642 16.96 22 12 22C10.36 22 8.54 21.5593 7.08 20.698C6.57 20.3876 6.14 20.1572 5.59 20.3375L3.57 20.9384C3.06 21.0986 2.6 20.698 2.75 20.1572L3.42 17.9139C3.53 17.6034 3.51 17.2729 3.35 17.0125C2.49 15.4301 2 13.6975 2 12.015C2 6.74712 6.21 2 12.02 2ZM16.59 10.7431C15.88 10.7431 15.31 11.314 15.31 12.025C15.31 12.7261 15.88 13.307 16.59 13.307C17.3 13.307 17.87 12.7261 17.87 12.025C17.87 11.314 17.3 10.7431 16.59 10.7431ZM11.98 10.7431C11.28 10.7331 10.7 11.314 10.7 12.015C10.7 12.7261 11.27 13.2969 11.98 13.307C12.69 13.307 13.26 12.7261 13.26 12.025C13.26 11.314 12.69 10.7431 11.98 10.7431ZM7.37 10.7431C6.66 10.7431 6.09 11.314 6.09 12.025C6.09 12.7261 6.67 13.307 7.37 13.307C8.08 13.2969 8.65 12.7261 8.65 12.025C8.65 11.314 8.08 10.7431 7.37 10.7431Z"
                      fill="black"
                    />
                  </g></svg
              ></span>
            </div>
            <textarea
              id="about"
              name="about"
              rows="5"
              placeholder=" your message "
              class="block w-full resize-none rounded-[15px] border-0 pl-11 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
            ></textarea>
          </div>
        </div>

        <div class="flex justify-end">
          <div class="relative mt-2 rounded-md shadow-sm mb-4">
            <div
              class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3"
            >
              <span class="text-gray-500 sm:text-sm"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  fill="none"
                >
                  <g opacity="0.1">
                    <path
                      d="M16.3402 2C19.7302 2 22.0002 4.38 22.0002 7.92V16.09C22.0002 19.62 19.7302 22 16.3402 22H7.67018C4.28018 22 2.00018 19.62 2.00018 16.09V7.92C2.00018 4.38 4.28018 2 7.67018 2H16.3402ZM16.4802 10.801C15.8202 10.801 15.2802 11.34 15.2802 12C15.2802 12.66 15.8202 13.2 16.4802 13.2C17.1402 13.2 17.6702 12.66 17.6702 12C17.6702 11.34 17.1402 10.801 16.4802 10.801ZM12.0002 10.801C11.3402 10.801 10.8002 11.34 10.8002 12C10.8002 12.66 11.3402 13.2 12.0002 13.2C12.6602 13.2 13.2002 12.66 13.2002 12C13.2002 11.34 12.6602 10.801 12.0002 10.801ZM7.52018 10.801C6.86018 10.801 6.32018 11.34 6.32018 12C6.32018 12.66 6.86018 13.2 7.52018 13.2C8.18018 13.2 8.72018 12.66 8.72018 12C8.72018 11.34 8.18018 10.801 7.52018 10.801Z"
                      fill="black"
                    />
                  </g></svg
              ></span>
            </div>

            <input
              type="number "
              name="price"
              id="price"
              class="w-52 rounded-[15px] border-0 pl-10 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
              placeholder=" captcha  "
            />
          </div>
        </div>

        <div class="absolute bottom-16 mb-9">
          <h1
            class="w-fit rounded-[15px] border-0 pl-7 py-5 pr-5 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-secondary sm:text-sm sm:leading-6"
          >
            858569
          </h1>
        </div>

        <div>
          <button
            class="w-full bg-gold rounded-[10px] opacity-75 hover:opacity-100 transition-opacity text-white font-bold py-2 px-4"
          >
            Submit
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
