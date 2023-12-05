<template>
  <header class="z-20">
    <div
      class="container mx-auto flex justify-between items-center px-10 lg:px-32 py-5"
    >
      <a href="#" class="z-0">
        <img class="-z-50" src="/images/Logo.png" alt="logo" />
      </a>
      <div class="flex items-center gap-5 z-20">
        <nav
          class="navbar w-[690px] h-[83px] bg-white/30 backdrop-blur rounded-full flex items-center justify-center max-lg:hidden"
        >
          <ul
            class="flex justify-center item-center flex-col p-4 md:p-0 mt-4 border rounded-lg md:flex-row md:space-x-8 md:mt-0 md:border-0 text-black/50"
          >
            <li class="group">
              <a
                href="#"
                class="py-2 pl-3 pr-4 rounded group-hover:text-black after:duration-300 after:ease-in-out flex justify-center relative group-hover:after:absolute group-hover:after:-bottom-1 group-hover:after:bg-black group-hover:after:h-1 group-hover:after:rounded group-hover:after:w-full"
                aria-current="page"
                >ARTICLE</a
              >
            </li>
            <li class="group">
              <a
                href="#"
                class="py-2 pl-3 pr-4 rounded group-hover:text-black after:duration-300 after:ease-in-out flex justify-center relative group-hover:after:absolute group-hover:after:-bottom-1 group-hover:after:bg-black group-hover:after:h-1 group-hover:after:rounded group-hover:after:w-full"
                aria-current="page"
                >CLASS</a
              >
            </li>
            <li class="group">
              <a
                href="#"
                class="py-2 pl-3 pr-4 rounded group-hover:text-black after:duration-300 after:ease-in-out flex justify-center relative group-hover:after:absolute group-hover:after:-bottom-1 group-hover:after:bg-black group-hover:after:h-1 group-hover:after:rounded group-hover:after:w-full"
                aria-current="page"
              >
                GALLERY</a
              >
            </li>
            <li class="group">
              <a
                href="#"
                class="py-2 pl-3 pr-4 rounded group-hover:text-black after:duration-300 after:ease-in-out flex justify-center relative group-hover:after:absolute group-hover:after:-bottom-1 group-hover:after:bg-black group-hover:after:h-1 group-hover:after:rounded group-hover:after:w-full"
                aria-current="page"
                >INTRODUCTION
              </a>
            </li>
            <li class="group">
              <a
                href="#"
                class="py-2 pl-3 pr-4 rounded group-hover:text-black after:duration-300 after:ease-in-out flex justify-center relative group-hover:after:absolute group-hover:after:-bottom-1 group-hover:after:bg-black group-hover:after:h-1 group-hover:after:rounded group-hover:after:w-full"
                aria-current="page"
                >ABOUT US</a
              >
            </li>
          </ul>
        </nav>
        <div class="flex gap-3 items-center">
          <div class="max-lg:hidden">
            <button
              class="rounded-lg bg-gold p-2 flex items-center text-white gap-2"
              dir="ltr"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="21"
                height="21"
                viewBox="0 0 21 21"
                fill="none"
              >
                <path
                  opacity="0.4"
                  d="M12.6475 2.3374C15.6931 2.67562 18.0993 5.07854 18.4409 8.12415"
                  stroke="white"
                  stroke-width="1.36207"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  opacity="0.4"
                  d="M12.6475 5.25293C14.1049 5.53601 15.2438 6.67575 15.5277 8.13314"
                  stroke="white"
                  stroke-width="1.36207"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M9.91424 10.5438C13.1968 13.8256 13.9415 10.029 16.0316 12.1176C18.0465 14.1321 19.2055 14.5357 16.6517 17.088C16.3319 17.3449 14.3002 20.4368 7.1599 13.2984C0.0187326 6.15903 3.10876 4.12514 3.36582 3.80544C5.92495 1.24609 6.32246 2.41096 8.33743 4.42541C10.4266 6.51493 6.63164 7.26208 9.91424 10.5438Z"
                  stroke="white"
                  stroke-width="1.36207"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
              (512) 555-1234
            </button>
          </div>
        </div>

        <div
        ref="nav"
          class="lg:hidden fixed w-56 h-full top-0 transition-all duration-500 -right-full bg-black/90"
        >
          <span @click="CloseNav" class="text-red-500 cursor-pointer "
            ><svg 
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-8 h-8"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M9.75 9.75l4.5 4.5m0-4.5l-4.5 4.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
              />
            </svg>
          </span>

          <ul>
            <li class="group"><a :class="hover" href="">ARTICLE</a></li>
            <li class="group"><a :class="hover" href="">CLASS</a></li>
            <li class="group"><a :class="hover" href="">GALLERY</a></li>
            <li class="group"><a :class="hover" href="">INTRODUCTION</a></li>
            <li class="group"><a :class="hover" href="">ABOUT US</a></li>
          </ul>
        </div>

        <button
          @click="OpenNav"
          class="border  rounded-lg p-1 bg-slate-200/10 lg:hidden"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
          >
            <path
              d="M2 5.995C2 5.445 2.446 5 2.995 5L11.005 5C11.2689 5 11.522 5.10483 11.7086 5.29143C11.8952 5.47803 12 5.73111 12 5.995C12 6.25889 11.8952 6.51197 11.7086 6.69857C11.522 6.88517 11.2689 6.99 11.005 6.99L2.995 6.99C2.445 6.99 2 6.545 2 5.995ZM2 12C2 11.45 2.446 11.005 2.995 11.005L21.005 11.005C21.2689 11.005 21.522 11.1098 21.7086 11.2964C21.8952 11.483 22 11.7361 22 12C22 12.2639 21.8952 12.517 21.7086 12.7036C21.522 12.8902 21.2689 12.995 21.005 12.995L2.995 12.995C2.445 12.995 2 12.549 2 12ZM2.995 17.01C2.73111 17.01 2.47803 17.1148 2.29143 17.3014C2.10483 17.488 2 17.7411 2 18.005C2 18.2689 2.10483 18.522 2.29143 18.7086C2.47803 18.8952 2.73111 19 2.995 19L15.005 19C15.1357 19 15.2651 18.9743 15.3858 18.9243C15.5065 18.8743 15.6162 18.801 15.7086 18.7086C15.801 18.6162 15.8743 18.5065 15.9243 18.3858C15.9743 18.2651 16 18.1357 16 18.005C16 17.8743 15.9743 17.7449 15.9243 17.6242C15.8743 17.5035 15.801 17.3938 15.7086 17.3014C15.6162 17.209 15.5065 17.1357 15.3858 17.0857C15.2651 17.0357 15.1357 17.01 15.005 17.01L2.995 17.01Z"
              fill="#1E2D48"
            />
          </svg>
        </button>
      </div>
    </div>
  </header>

  <section></section>
</template>

<script setup>
import { ref } from "vue";

const hover =
  " mt-16 text-white group-hover:text-gold after:duration-300 after:ease-in-out flex justify-center relative group-hover:after:absolute group-hover:after:-bottom-1 group-hover:after:bg-gold group-hover:after:h-1 group-hover:after:rounded group-hover:after:w-full";
const nav=ref(null)
  const OpenNav = ()=>{
nav.value.style.right = "0"
  }

  const CloseNav = ()=>{
nav.value.style.right = "-500px"
  }
  
</script>

<style scoped>
</style>
