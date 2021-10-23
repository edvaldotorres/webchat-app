<template>
  <app-layout title="Dashboard">
    <template #header>
      <h2 class="font-semibold text-xl text-gray-800 leading-tight">Chat</h2>
    </template>

    <div class="py-12">
      <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
        <div
          class="bg-white overflow-hidden shadow-xl sm:rounded-lg flex"
          style="min-height: 400px; max-height: 400px"
        >
          <!--List Users-->
          <div
            class="
              w-3/12
              bg-gray-200 bg-opacity-25
              border-r border-gray-200
              overflow-y-scroll
            "
          >
            <ul>
              <li
                class="
                  p-6
                  text-lg text-gray-600
                  font-semibold
                  border-b border-gray-200
                  hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer
                "
              >
                <p class="flex items-center">
                  Teste 1
                  <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                </p>
              </li>
              <li
                class="
                  p-6
                  text-lg text-gray-600
                  font-semibold
                  border-b border-gray-200
                  hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer
                "
              >
                <p class="flex items-center">
                  Teste 2
                  <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                </p>
              </li>
              <li
                class="
                  p-6
                  text-lg text-gray-600
                  font-semibold
                  border-b border-gray-200
                  hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer
                "
              >
                <p class="flex items-center">
                  Teste 3
                  <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                </p>
              </li>
              <li
                class="
                  p-6
                  text-lg text-gray-600
                  font-semibold
                  border-b border-gray-200
                  hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer
                "
              >
                <p class="flex items-center">
                  Teste 4
                  <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                </p>
              </li>
              <li
                class="
                  p-6
                  text-lg text-gray-600
                  font-semibold
                  border-b border-gray-200
                  hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer
                "
              >
                <p class="flex items-center">
                  Teste 5
                  <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                </p>
              </li>
              <li
                class="
                  p-6
                  text-lg text-gray-600
                  font-semibold
                  border-b border-gray-200
                  hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer
                "
              >
                <p class="flex items-center">
                  Teste 6
                  <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                </p>
              </li>
              <li
                class="
                  p-6
                  text-lg text-gray-600
                  font-semibold
                  border-b border-gray-200
                  hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer
                "
              >
                <p class="flex items-center">
                  Teste 7
                  <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                </p>
              </li>
              <li
                class="
                  p-6
                  text-lg text-gray-600
                  font-semibold
                  border-b border-gray-200
                  hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer
                "
              >
                <p class="flex items-center">
                  Teste 8
                  <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                </p>
              </li>
            </ul>
          </div>
          <!--Box menssage-->
          <div class="w-9/12 flex flex-col justify-between">
            <!--Menssage-->
            <div class="w-full p-6 flex flex-col overflow-y-scroll">
              <div class="w-full mb-3 text-right">
                <p
                  class="
                    inline-block
                    p-2
                    rounded-md
                    bg-indigo-300 bg-opacity-25
                  "
                  style="max-width: 75%"
                >
                  Olá.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3">
                <p
                  class="inline-block p-2 rounded-md bg-gray-300 bg-opacity-25"
                  style="max-width: 75%"
                >
                  Oi!.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3 text-right">
                <p
                  class="
                    inline-block
                    p-2
                    rounded-md
                    bg-indigo-300 bg-opacity-25
                  "
                  style="max-width: 75%"
                >
                  Olá.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3">
                <p
                  class="inline-block p-2 rounded-md bg-gray-300 bg-opacity-25"
                  style="max-width: 75%"
                >
                  Oi!.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3 text-right">
                <p
                  class="
                    inline-block
                    p-2
                    rounded-md
                    bg-indigo-300 bg-opacity-25
                  "
                  style="max-width: 75%"
                >
                  Olá.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3">
                <p
                  class="inline-block p-2 rounded-md bg-gray-300 bg-opacity-25"
                  style="max-width: 75%"
                >
                  Oi!.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3 text-right">
                <p
                  class="
                    inline-block
                    p-2
                    rounded-md
                    bg-indigo-300 bg-opacity-25
                  "
                  style="max-width: 75%"
                >
                  Olá.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3">
                <p
                  class="inline-block p-2 rounded-md bg-gray-300 bg-opacity-25"
                  style="max-width: 75%"
                >
                  Oi!.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3 text-right">
                <p
                  class="
                    inline-block
                    p-2
                    rounded-md
                    bg-indigo-300 bg-opacity-25
                  "
                  style="max-width: 75%"
                >
                  Olá.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3">
                <p
                  class="inline-block p-2 rounded-md bg-gray-300 bg-opacity-25"
                  style="max-width: 75%"
                >
                  Oi!.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3 text-right">
                <p
                  class="
                    inline-block
                    p-2
                    rounded-md
                    bg-indigo-300 bg-opacity-25
                  "
                  style="max-width: 75%"
                >
                  Olá.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3">
                <p
                  class="inline-block p-2 rounded-md bg-gray-300 bg-opacity-25"
                  style="max-width: 75%"
                >
                  Oi!.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3 text-right">
                <p
                  class="
                    inline-block
                    p-2
                    rounded-md
                    bg-indigo-300 bg-opacity-25
                  "
                  style="max-width: 75%"
                >
                  Olá.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3">
                <p
                  class="inline-block p-2 rounded-md bg-gray-300 bg-opacity-25"
                  style="max-width: 75%"
                >
                  Oi!.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3 text-right">
                <p
                  class="
                    inline-block
                    p-2
                    rounded-md
                    bg-indigo-300 bg-opacity-25
                  "
                  style="max-width: 75%"
                >
                  Olá.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3">
                <p
                  class="inline-block p-2 rounded-md bg-gray-300 bg-opacity-25"
                  style="max-width: 75%"
                >
                  Oi!.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3 text-right">
                <p
                  class="
                    inline-block
                    p-2
                    rounded-md
                    bg-indigo-300 bg-opacity-25
                  "
                  style="max-width: 75%"
                >
                  Olá.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
              <div class="w-full mb-3">
                <p
                  class="inline-block p-2 rounded-md bg-gray-300 bg-opacity-25"
                  style="max-width: 75%"
                >
                  Oi!.
                </p>
                <span class="block mt-1 text-xs text-gray-500"
                  >22/10/2021 01:50</span
                >
              </div>
            </div>
            <!--Form-->
            <div
              class="
                w-full
                bg-gray-200 bg-opacity-25
                p-6
                border-t border-gray-200
              "
            >
              <form>
                <div class="flex rounded-md overflow-hidden border-gray-300">
                  <input
                    type="text"
                    class="flex-1 px-4 py-2 text-sm focus:outline-none"
                  />
                  <button
                    type="submit"
                    class="
                      bg-indigo-500
                      hover:bg-indigo-600
                      text-white
                      px-4
                      py-2
                    "
                  >
                    Enviar
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </app-layout>
</template>

<script>
import { defineComponent } from "vue";
import AppLayout from "@/Layouts/AppLayout.vue";

export default defineComponent({
  components: {
    AppLayout,
  },
});
</script>