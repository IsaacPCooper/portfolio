<template>
  <header
    class="px-4 py-4 items-center justify-center space-x-12 border-b-2 border-blue-500/10 hidden md:flex"
  >
    <nav
      class="flex flex-col align-middle text-white justify-center md:flex-row md:w-full md:justify-evenly md:items-center"
    >
      <div>Isaac Cooper</div>

      <ul class="flex gap-[4vw] mt-3 mb-3">
        <li>
          <a
            class="hover:text-green-500 transition ease-in delay-75"
            href="#myStack"
            >My Stack
          </a>
        </li>
        <li>
          <a
            class="hover:text-green-500 transition ease-in delay-75"
            href="#projects"
            >My Projects
          </a>
        </li>
        <li>
          <a
            class="hover:text-green-500 transition ease-in delay-75"
            href="#bio"
            >About Me</a
          >
        </li>
      </ul>
      <button
        class="bg-red-500 p-2 rounded-lg thick-shadow hover:bg-blue-500 transition-colors duration-200"
        href="#contact"
      >
        Get In Touch
      </button>
    </nav>
  </header>
</template>