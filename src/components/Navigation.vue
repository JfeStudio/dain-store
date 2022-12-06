<template lang="">
  <header
    id="header"
    class="fixed z-[999] w-full py-2 transition-all md:py-3 lg:py-4"
  >
    <div class="container mx-auto">
      <div
        class="navbar flex items-center justify-between md:items-center md:gap-x-12"
      >
        <div class="logo cursor-pointer">
          <i class="icon-logo bx bx-code-curly text-3xl"></i>
        </div>
        <!-- !mobile -->
        <nav
          class="navigation absolute top-10 right-1 w-56 rounded-md bg-holy-blur p-7 opacity-0 shadow-xl transition-all duration-300 ease-in-out md:static md:flex md:w-full md:items-center md:bg-transparent md:p-0 md:opacity-100 md:shadow-none lg:justify-end lg:gap-x-44"
        >
          <ul
            class="menu flex flex-col gap-y-4 md:flex-row md:items-center md:gap-x-8 lg:gap-x-10"
          >
            <li class="text-center">
              <a
                class="md:text-[.7rem] md:text-holy-blur lg:text-sm"
                href="#top"
                >Top</a
              >
            </li>
            <li class="text-center">
              <a
                class="nav-link text-[.8rem] font-semibold text-gray-400 hover:text-dark-scy md:text-[.7rem] md:hover:text-holy-blur lg:text-sm"
                href="#features"
                >Features</a
              >
            </li>
            <li class="text-center">
              <a
                class="nav-link text-[.8rem] font-semibold text-gray-400 hover:text-dark-scy md:text-[.7rem] md:hover:text-holy-blur lg:text-sm"
                href="#reasons"
                >Reasons</a
              >
            </li>
            <li class="text-center">
              <a
                class="nav-link text-[.8rem] font-semibold text-gray-400 hover:text-dark-scy md:text-[.7rem] md:hover:text-holy-blur lg:text-sm"
                href="#alternatives"
                >Alternatives</a
              >
            </li>
          </ul>
          <div
            class="btn-navigation mt-3 border-t md:ml-auto md:mt-0 md:flex md:border-none lg:m-0 lg:gap-x-3"
          >
            <button
              type="submit"
              class="btn-signup text-hover mt-4 block w-full bg-transparent px-7 text-[.8rem] font-semibold text-dark-scy md:mt-0 md:w-[inherit] md:px-5 md:text-[.7rem] md:text-slate-800 lg:text-sm"
            >
              <span class="hover:underline">Mendaftar</span>
            </button>
            <button
              type="submit"
              class="btn-signup bg-cyan bg-hover mt-3 block w-full rounded-full bg-dark-scy px-7 py-[10px] text-[.8rem] font-semibold text-holy-blur shadow-3xl md:mt-0 md:w-[inherit] md:bg-slate-800 md:py-2 md:px-5 md:text-[.7rem] md:text-slate-50 lg:px-6 lg:text-sm"
            >
              Login
            </button>
          </div>
        </nav>
        <button class="block menu-hamburger cursor-pointer md:hidden group">
          <i class="bx bx-menu-alt-right icon text-3xl text-holy-blur"></i>
          <!-- mobile -->
          <nav
            class="absolute z-30 top-0 bg-slate-800 py-14 -right-full w-7/12 h-screen opacity-0 shadow-sm transition-all duration-300 ease-in-out group-focus:right-0 group-focus:opacity-100"
          >
            <ul class="flex flex-col gap-y-5">
              <li class="text-center">
                <a class="text-sm font-semibold text-white" href="#top">Top</a>
              </li>
              <li class="text-center">
                <a class="text-sm font-semibold text-gray-400" href="#features"
                  >Features</a
                >
              </li>
              <li class="text-center">
                <a class="text-sm font-semibold text-gray-400" href="#reasons"
                  >Reasons</a
                >
              </li>
              <li class="text-center">
                <a
                  class="text-sm font-semibold text-gray-400"
                  href="#alternatives"
                  >Alternatives</a
                >
              </li>
            </ul>
          </nav>
        </button>
      </div>
    </div>
  </header>
</template>
<script>
import Menu from "./Menu.vue";
</script>
<style lang=""></style>
