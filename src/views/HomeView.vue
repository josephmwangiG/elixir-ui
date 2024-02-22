<script setup lang="ts"></script>

<template>
  <main>
    <div class="bg-white">
      <div class="border py-3 px-6">
        <div class="flex justify-between">
          <div class="flex items-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-red-500"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9H3m2 6H3m18-6h-2m2 6h-2M7 19h10a2 2 0 002-2V7a2 2 0 00-2-2H7a2 2 0 00-2 2v10a2 2 0 002 2zM9 9h6v6H9V9z"
              />
            </svg>
            <span class="ml-2 font-semibold text-[#252C32]">What a Market</span>
          </div>

          <div class="ml-6 flex flex-1 gap-x-3">
            <div
              class="flex cursor-pointer select-none items-center gap-x-2 rounded-md border bg-[#4094F7] py-2 px-4 text-white hover:bg-blue-500"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="2"
              >
                <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
              </svg>
              <span class="text-sm font-medium">Categories</span>
            </div>

            <input
              type="text"
              class="w-full rounded-md border border-[#DDE2E4] px-3 py-2 text-sm"
              value="DJI phantom"
            />
          </div>

          <div class="ml-2 flex">
            <div
              class="flex cursor-pointer items-center gap-x-1 rounded-md py-2 px-4 hover:bg-gray-100"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5 text-gray-500"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path d="M4 3a2 2 0 100 4h12a2 2 0 100-4H4z" />
                <path
                  fill-rule="evenodd"
                  d="M3 8h14v7a2 2 0 01-2 2H5a2 2 0 01-2-2V8zm5 3a1 1 0 011-1h2a1 1 0 110 2H9a1 1 0 01-1-1z"
                  clip-rule="evenodd"
                />
              </svg>
              <span class="text-sm font-medium">Orders</span>
            </div>

            <div
              class="flex cursor-pointer items-center gap-x-1 rounded-md py-2 px-4 hover:bg-gray-100"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5 text-gray-500"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M3.172 5.172a4 4 0 015.656 0L10 6.343l1.172-1.171a4 4 0 115.656 5.656L10 17.657l-6.828-6.829a4 4 0 010-5.656z"
                  clip-rule="evenodd"
                />
              </svg>
              <span class="text-sm font-medium">Favorites</span>
            </div>

            <div
              class="flex cursor-pointer items-center gap-x-1 rounded-md py-2 px-4 hover:bg-gray-100"
            >
              <div class="relative">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 text-gray-500"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                >
                  <path
                    d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"
                  />
                </svg>
                <span
                  class="absolute -top-2 -right-2 flex h-4 w-4 items-center justify-center rounded-full bg-red-500 p-2 text-xs text-white"
                  >3</span
                >
              </div>
              <span class="text-sm font-medium">Cart</span>
            </div>

            <div
              class="ml-2 flex cursor-pointer items-center gap-x-1 rounded-md border py-2 px-4 hover:bg-gray-100"
            >
              <span class="text-sm font-medium">Sign in</span>
            </div>
          </div>
        </div>

        <div class="mt-4 flex items-center justify-between">
          <div class="flex gap-x-2 py-1 px-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5 text-gray-500"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z"
                clip-rule="evenodd"
              />
            </svg>
            <span class="text-sm font-medium">California</span>
          </div>

          <div class="flex gap-x-8">
            <span class="cursor-pointer rounded-sm py-1 px-2 text-sm font-medium hover:bg-gray-100"
              >Best seller</span
            >
            <span class="cursor-pointer rounded-sm py-1 px-2 text-sm font-medium hover:bg-gray-100"
              >New Releases</span
            >
            <span class="cursor-pointer rounded-sm py-1 px-2 text-sm font-medium hover:bg-gray-100"
              >Books</span
            >
            <span class="cursor-pointer rounded-sm py-1 px-2 text-sm font-medium hover:bg-gray-100"
              >Computers</span
            >
            <span class="cursor-pointer rounded-sm py-1 px-2 text-sm font-medium hover:bg-gray-100"
              >Fashion</span
            >
            <span class="cursor-pointer rounded-sm py-1 px-2 text-sm font-medium hover:bg-gray-100"
              >Health</span
            >
            <span class="cursor-pointer rounded-sm py-1 px-2 text-sm font-medium hover:bg-gray-100"
              >Pharmacy</span
            >
            <span class="cursor-pointer rounded-sm py-1 px-2 text-sm font-medium hover:bg-gray-100"
              >Toys & Games</span
            >
          </div>

          <span class="cursor-pointer rounded-sm py-1 px-2 text-sm font-medium hover:bg-gray-100"
            >Becoma a seller</span
          >
        </div>
      </div>
    </div>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/gh/Loopple/loopple-public-assets@main/riva-dashboard-tailwind/riva-dashboard.css"
    />
    <div class="flex flex-wrap -mx-3 mb-5">
      <div class="w-full max-w-full px-3 mb-6 mx-auto">
        <div
          class="relative flex-[1_auto] flex flex-col break-words min-w-0 bg-clip-border rounded-[.95rem] bg-white m-5"
        >
          <div
            class="relative flex flex-col min-w-0 break-words border border-dashed bg-clip-border rounded-2xl border-stone-200 bg-light/30"
          >
            <!-- card header -->
            <div
              class="px-9 pt-5 flex justify-between items-stretch flex-wrap min-h-[70px] pb-0 bg-transparent"
            >
              <h3
                class="flex flex-col items-start justify-center m-2 ml-0 font-medium text-xl/tight text-dark"
              >
                <span class="mr-3 font-semibold text-dark">Projects Deliveries</span>
                <span class="mt-1 font-medium text-secondary-dark text-lg/normal"
                  >All projects from the Loopple team</span
                >
              </h3>
              <div class="relative flex flex-wrap items-center my-2">
                <a
                  href="javascript:void(0)"
                  class="inline-block text-[.925rem] font-medium leading-normal text-center align-middle cursor-pointer rounded-2xl transition-colors duration-150 ease-in-out text-light-inverse bg-light-dark border-light shadow-none border-0 py-2 px-5 hover:bg-secondary active:bg-light focus:bg-light"
                >
                  See other projects
                </a>
              </div>
            </div>
            <!-- end card header -->
            <!-- card body  -->
            <div class="flex-auto block py-8 pt-6 px-9">
              <div class="overflow-x-auto">
                <table class="w-full my-0 align-middle text-dark border-neutral-200">
                  <thead class="align-bottom">
                    <tr class="font-semibold text-[0.95rem] text-secondary-dark">
                      <th class="pb-3 text-start min-w-[175px]">TASK</th>
                      <th class="pb-3 text-end min-w-[100px]">OWNER</th>
                      <th class="pb-3 text-end min-w-[100px]">PROGRESS</th>
                      <th class="pb-3 pr-12 text-end min-w-[175px]">STATUS</th>
                      <th class="pb-3 pr-12 text-end min-w-[100px]">DEADLINE</th>
                      <th class="pb-3 text-end min-w-[50px]">DETAILS</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr class="border-b border-dashed last:border-b-0">
                      <td class="p-3 pl-0">
                        <div class="flex items-center">
                          <div class="relative inline-block shrink-0 rounded-2xl me-3">
                            <img
                              src="https://raw.githubusercontent.com/Loopple/loopple-public-assets/main/riva-dashboard-tailwind/img/img-49-new.jpg"
                              class="w-[50px] h-[50px] inline-block shrink-0 rounded-2xl"
                              alt=""
                            />
                          </div>
                          <div class="flex flex-col justify-start">
                            <a
                              href="javascript:void(0)"
                              class="mb-1 font-semibold transition-colors duration-200 ease-in-out text-lg/normal text-secondary-inverse hover:text-primary"
                            >
                              Social Media API
                            </a>
                          </div>
                        </div>
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >Olivia Cambell</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-2 py-1 mr-auto items-center font-semibold text-base/none text-success bg-success-light rounded-lg"
                        >
                          <svg
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke-width="1.5"
                            stroke="currentColor"
                            class="w-5 h-5 mr-1"
                          >
                            <path
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              d="M2.25 18L9 11.25l4.306 4.307a11.95 11.95 0 015.814-5.519l2.74-1.22m0 0l-5.94-2.28m5.94 2.28l-2.28 5.941"
                            />
                          </svg>
                          6.5%
                        </span>
                      </td>
                      <td class="p-3 pr-12 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-4 py-3 mr-auto items-center font-semibold text-[.95rem] leading-none text-primary bg-primary-light rounded-lg"
                        >
                          In Progress
                        </span>
                      </td>
                      <td class="pr-0 text-start">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >2023-08-23</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <button
                          class="ml-auto relative text-secondary-dark bg-light-dark hover:text-primary flex items-center h-[25px] w-[25px] text-base font-medium leading-normal text-center align-middle cursor-pointer rounded-2xl transition-colors duration-200 ease-in-out shadow-none border-0 justify-center"
                        >
                          <span
                            class="flex items-center justify-center p-0 m-0 leading-none shrink-0"
                          >
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
                                d="M8.25 4.5l7.5 7.5-7.5 7.5"
                              />
                            </svg>
                          </span>
                        </button>
                      </td>
                    </tr>
                    <tr class="border-b border-dashed last:border-b-0">
                      <td class="p-3 pl-0">
                        <div class="flex items-center">
                          <div class="relative inline-block shrink-0 rounded-2xl me-3">
                            <img
                              src="https://raw.githubusercontent.com/Loopple/loopple-public-assets/main/riva-dashboard-tailwind/img/img-40-new.jpg"
                              class="w-[50px] h-[50px] inline-block shrink-0 rounded-2xl"
                              alt=""
                            />
                          </div>
                          <div class="flex flex-col justify-start">
                            <a
                              href="javascript:void(0)"
                              class="mb-1 font-semibold transition-colors duration-200 ease-in-out text-lg/normal text-secondary-inverse hover:text-primary"
                            >
                              Geolocation App
                            </a>
                          </div>
                        </div>
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >Luca Micloe</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-2 py-1 mr-auto items-center font-semibold text-base/none text-danger bg-danger-light rounded-lg"
                        >
                          <svg
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke-width="1.5"
                            stroke="currentColor"
                            class="w-5 h-5 mr-1"
                          >
                            <path
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              d="M2.25 6L9 12.75l4.286-4.286a11.948 11.948 0 014.306 6.43l.776 2.898m0 0l3.182-5.511m-3.182 5.51l-5.511-3.181"
                            />
                          </svg>
                          2.7%
                        </span>
                      </td>
                      <td class="p-3 pr-12 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-4 py-3 mr-auto items-center font-semibold text-[.95rem] leading-none text-light-inverse bg-light rounded-lg"
                        >
                          Under Review
                        </span>
                      </td>
                      <td class="pr-0 text-start">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >2024-04-11</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <button
                          class="ml-auto relative text-secondary-dark bg-light-dark hover:text-primary flex items-center h-[25px] w-[25px] text-base font-medium leading-normal text-center align-middle cursor-pointer rounded-2xl transition-colors duration-200 ease-in-out shadow-none border-0 justify-center"
                        >
                          <span
                            class="flex items-center justify-center p-0 m-0 leading-none shrink-0"
                          >
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
                                d="M8.25 4.5l7.5 7.5-7.5 7.5"
                              />
                            </svg>
                          </span>
                        </button>
                      </td>
                    </tr>
                    <tr class="border-b border-dashed last:border-b-0">
                      <td class="p-3 pl-0">
                        <div class="flex items-center">
                          <div class="relative inline-block shrink-0 rounded-2xl me-3">
                            <img
                              src="https://raw.githubusercontent.com/Loopple/loopple-public-assets/main/riva-dashboard-tailwind/img/img-39-new.jpg"
                              class="w-[50px] h-[50px] inline-block shrink-0 rounded-2xl"
                              alt=""
                            />
                          </div>
                          <div class="flex flex-col justify-start">
                            <a
                              href="javascript:void(0)"
                              class="mb-1 font-semibold transition-colors duration-200 ease-in-out text-lg/normal text-secondary-inverse hover:text-primary"
                            >
                              iOS Login <span class="text-sm">(Morra)</span>
                            </a>
                          </div>
                        </div>
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >Bianca Winson</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-2 py-1 mr-auto items-center font-semibold text-base/none text-success bg-success-light rounded-lg"
                        >
                          <svg
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke-width="1.5"
                            stroke="currentColor"
                            class="w-5 h-5 mr-1"
                          >
                            <path
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              d="M2.25 18L9 11.25l4.306 4.307a11.95 11.95 0 015.814-5.519l2.74-1.22m0 0l-5.94-2.28m5.94 2.28l-2.28 5.941"
                            />
                          </svg>
                          6.8%
                        </span>
                      </td>
                      <td class="p-3 pr-12 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-4 py-3 mr-auto items-center font-semibold text-[.95rem] leading-none text-primary bg-primary-light rounded-lg"
                        >
                          In Progress
                        </span>
                      </td>
                      <td class="pr-0 text-start">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >2024-02-10</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <button
                          class="ml-auto relative text-secondary-dark bg-light-dark hover:text-primary flex items-center h-[25px] w-[25px] text-base font-medium leading-normal text-center align-middle cursor-pointer rounded-2xl transition-colors duration-200 ease-in-out shadow-none border-0 justify-center"
                        >
                          <span
                            class="flex items-center justify-center p-0 m-0 leading-none shrink-0"
                          >
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
                                d="M8.25 4.5l7.5 7.5-7.5 7.5"
                              />
                            </svg>
                          </span>
                        </button>
                      </td>
                    </tr>
                    <tr class="border-b border-dashed last:border-b-0">
                      <td class="p-3 pl-0">
                        <div class="flex items-center">
                          <div class="relative inline-block shrink-0 rounded-2xl me-3">
                            <img
                              src="https://raw.githubusercontent.com/Loopple/loopple-public-assets/main/riva-dashboard-tailwind/img/img-47-new.jpg"
                              class="w-[50px] h-[50px] inline-block shrink-0 rounded-2xl"
                              alt=""
                            />
                          </div>
                          <div class="flex flex-col justify-start">
                            <a
                              href="javascript:void(0)"
                              class="mb-1 font-semibold transition-colors duration-200 ease-in-out text-lg/normal text-secondary-inverse hover:text-primary"
                            >
                              Axios Menu
                            </a>
                          </div>
                        </div>
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >Roberto Alliton</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-2 py-1 mr-auto items-center font-semibold text-base/none text-success bg-success-light rounded-lg"
                        >
                          <svg
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke-width="1.5"
                            stroke="currentColor"
                            class="w-5 h-5 mr-1"
                          >
                            <path
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              d="M2.25 18L9 11.25l4.306 4.307a11.95 11.95 0 015.814-5.519l2.74-1.22m0 0l-5.94-2.28m5.94 2.28l-2.28 5.941"
                            />
                          </svg>
                          4.5%
                        </span>
                      </td>
                      <td class="p-3 pr-12 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-4 py-3 mr-auto items-center font-semibold text-[.95rem] leading-none text-success bg-success-light rounded-lg"
                        >
                          Done
                        </span>
                      </td>
                      <td class="pr-0 text-start">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >2023-05-31</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <button
                          class="ml-auto relative text-secondary-dark bg-light-dark hover:text-primary flex items-center h-[25px] w-[25px] text-base font-medium leading-normal text-center align-middle cursor-pointer rounded-2xl transition-colors duration-200 ease-in-out shadow-none border-0 justify-center"
                        >
                          <span
                            class="flex items-center justify-center p-0 m-0 leading-none shrink-0"
                          >
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
                                d="M8.25 4.5l7.5 7.5-7.5 7.5"
                              />
                            </svg>
                          </span>
                        </button>
                      </td>
                    </tr>
                    <tr class="border-b border-dashed last:border-b-0">
                      <td class="p-3 pl-0">
                        <div class="flex items-center">
                          <div class="relative inline-block shrink-0 rounded-2xl me-3">
                            <img
                              src="https://raw.githubusercontent.com/Loopple/loopple-public-assets/main/riva-dashboard-tailwind/img/img-48-new.jpg"
                              class="w-[50px] h-[50px] inline-block shrink-0 rounded-2xl"
                              alt=""
                            />
                          </div>
                          <div class="flex flex-col justify-start">
                            <a
                              href="javascript:void(0)"
                              class="mb-1 font-semibold transition-colors duration-200 ease-in-out text-lg/normal text-secondary-inverse hover:text-primary"
                            >
                              Resto Aperto
                            </a>
                          </div>
                        </div>
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >Michael Kenny</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-2 py-1 mr-auto items-center font-semibold text-base/none text-danger bg-danger-light rounded-lg"
                        >
                          <svg
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke-width="1.5"
                            stroke="currentColor"
                            class="w-5 h-5 mr-1"
                          >
                            <path
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              d="M2.25 6L9 12.75l4.286-4.286a11.948 11.948 0 014.306 6.43l.776 2.898m0 0l3.182-5.511m-3.182 5.51l-5.511-3.181"
                            />
                          </svg>
                          1%
                        </span>
                      </td>
                      <td class="p-3 pr-12 text-end">
                        <span
                          class="text-center align-baseline inline-flex px-4 py-3 mr-auto items-center font-semibold text-[.95rem] leading-none text-warning bg-warning-light rounded-lg"
                        >
                          Postponed
                        </span>
                      </td>
                      <td class="pr-0 text-start">
                        <span class="font-semibold text-light-inverse text-md/normal"
                          >2023-05-15</span
                        >
                      </td>
                      <td class="p-3 pr-0 text-end">
                        <button
                          class="ml-auto relative text-secondary-dark bg-light-dark hover:text-primary flex items-center h-[25px] w-[25px] text-base font-medium leading-normal text-center align-middle cursor-pointer rounded-2xl transition-colors duration-200 ease-in-out shadow-none border-0 justify-center"
                        >
                          <span
                            class="flex items-center justify-center p-0 m-0 leading-none shrink-0"
                          >
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
                                d="M8.25 4.5l7.5 7.5-7.5 7.5"
                              />
                            </svg>
                          </span>
                        </button>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <footer class="bg-white" aria-labelledby="footer-heading">
      <h2 id="footer-heading" class="sr-only">Footer</h2>
      <div class="mx-auto px-6 pb-8 pt-16 sm:pt-24 lg:px-8 lg:pt-32">
        <div class="xl:grid xl:grid-cols-3 xl:gap-8">
          <div class="space-y-8">
            <img
              class="h-20"
              src="https://aaah0mnbncqtinas.public.blob.vercel-storage.com/FX5ATkass4-no-background-VmcZHSX7xE4ng29ATNphGUdb388fxH.png"
              alt="Company name"
            />
            <p class="text-sm leading-6 text-gray-600">
              Making football look better to the world and a more respecful game.
            </p>
            <div class="flex space-x-6">
              <a href="#" class="text-gray-400 hover:text-gray-500">
                <span class="sr-only">Facebook</span>
                <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                  <path
                    fill-rule="evenodd"
                    d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"
                    clip-rule="evenodd"
                  />
                </svg>
              </a>
              <a href="#" class="text-yellow-500 hover:text-gray-500">
                <span class="sr-only">the team is on fire</span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 16 16"
                  fill="currentColor"
                  class="w-4 h-4"
                >
                  <path
                    fill-rule="evenodd"
                    d="M8.074.945A4.993 4.993 0 0 0 6 5v.032c.004.6.114 1.176.311 1.709.16.428-.204.91-.61.7a5.023 5.023 0 0 1-1.868-1.677c-.202-.304-.648-.363-.848-.058a6 6 0 1 0 8.017-1.901l-.004-.007a4.98 4.98 0 0 1-2.18-2.574c-.116-.31-.477-.472-.744-.28Zm.78 6.178a3.001 3.001 0 1 1-3.473 4.341c-.205-.365.215-.694.62-.59a4.008 4.008 0 0 0 1.873.03c.288-.065.413-.386.321-.666A3.997 3.997 0 0 1 8 8.999c0-.585.126-1.14.351-1.641a.42.42 0 0 1 .503-.235Z"
                    clip-rule="evenodd"
                  />
                </svg>
              </a>
              <a href="#" class="text-gray-400 hover:text-blue-4 00">
                <span class="sr-only">X</span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 16 16"
                  fill="currentColor"
                  class="w-4 h-4"
                >
                  <path
                    d="M2.75 2a.75.75 0 0 0-.75.75v10.5a.75.75 0 0 0 1.5 0v-2.624l.33-.083A6.044 6.044 0 0 1 8 11c1.29.645 2.77.807 4.17.457l1.48-.37a.462.462 0 0 0 .35-.448V3.56a.438.438 0 0 0-.544-.425l-1.287.322C10.77 3.808 9.291 3.646 8 3a6.045 6.045 0 0 0-4.17-.457l-.34.085A.75.75 0 0 0 2.75 2Z"
                  />
                </svg>
              </a>
              <a href="#" class="text-gray-400 hover:text-gray-500">
                <span class="sr-only">GitHub</span>
                <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                  <path
                    fill-rule="evenodd"
                    d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                    clip-rule="evenodd"
                  />
                </svg>
              </a>
              <a href="#" class="text-gray-400 hover:text-gray-500">
                <span class="sr-only">YouTube</span>
                <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                  <path
                    fill-rule="evenodd"
                    d="M19.812 5.418c.861.23 1.538.907 1.768 1.768C21.998 8.746 22 12 22 12s0 3.255-.418 4.814a2.504 2.504 0 0 1-1.768 1.768c-1.56.419-7.814.419-7.814.419s-6.255 0-7.814-.419a2.505 2.505 0 0 1-1.768-1.768C2 15.255 2 12 2 12s0-3.255.417-4.814a2.507 2.507 0 0 1 1.768-1.768C5.744 5 11.998 5 11.998 5s6.255 0 7.814.418ZM15.194 12 10 15V9l5.194 3Z"
                    clip-rule="evenodd"
                  />
                </svg>
              </a>
            </div>
          </div>
          <div class="mt-16 grid grid-cols-2 gap-8 xl:col-span-2 xl:mt-0">
            <div class="md:grid md:grid-cols-2 md:gap-8">
              <div>
                <h3 class="text-sm font-semibold leading-6 text-gray-900">Solutions</h3>
                <ul role="list" class="mt-6 space-y-4">
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Marketing</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Analytics</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Commerce</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Insights</a
                    >
                  </li>
                </ul>
              </div>
              <div class="mt-10 md:mt-0">
                <h3 class="text-sm font-semibold leading-6 text-gray-900">Support</h3>
                <ul role="list" class="mt-6 space-y-4">
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Pricing</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Documentation</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Guides</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >API Status</a
                    >
                  </li>
                </ul>
              </div>
            </div>
            <div class="md:grid md:grid-cols-2 md:gap-8">
              <div>
                <h3 class="text-sm font-semibold leading-6 text-gray-900">Company</h3>
                <ul role="list" class="mt-6 space-y-4">
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >About</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Blog</a>
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Jobs</a>
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Press</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Partners</a
                    >
                  </li>
                </ul>
              </div>
              <div class="mt-10 md:mt-0">
                <h3 class="text-sm font-semibold leading-6 text-gray-900">Legal</h3>
                <ul role="list" class="mt-6 space-y-4">
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Claim</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Privacy</a
                    >
                  </li>
                  <li>
                    <a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900"
                      >Terms</a
                    >
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="mt-16 border-t border-gray-900/10 pt-8 sm:mt-20 lg:mt-24">
          <p class="text-xs leading-5 text-gray-500">
            &copy; 2020 Your Company, Inc. All rights reserved.
          </p>
        </div>
      </div>
    </footer>
  </main>
</template>
