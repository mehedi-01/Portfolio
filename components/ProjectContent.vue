<template>
  <div
    ref="rootDiv"
    class="flex flex-row absolute left-0 w-full top-0 h-full justify-center items-center duration-500 transition-all"
  >
    <div class="flex flex-col flex-1 h-4/5 items-start justify-start">
      <!-- <img
        src="/images/mingming.png"
        class="mt-8 border-white shadow-xl shadow-black/50 rounded-full"
        alt="MingPV"
        width="300"
        height="300"
        sizes="(max-width: 400px) 100vw, 400px"
        loading="lazy"
        placeholder="blur"
      /> -->
    </div>
    <div
      class="flex flex-col w-[100%] xl:w-[60%] pt-[10vh] xl:pt-0 h-full xl:mt-0 xl:h-4/5 items-center font-serif bg-stone-700/70 backdrop-blur-md rounded-md pb-6"
    >
      <div
        class="w-full my-8 font-serif text-xl md:text-3xl text-stone-200/80 font-bold"
      >
        My Work
      </div>
      <div
        class="w-full h-fit grid grid-cols-1 md:grid-cols-2 gap-4 px-4 overflow-y-scroll"
      >
        <div
          class="bg-stone-900/40 flex flex-col gap-2 items-start rounded-md pb-4 px-2 pt-2"
        >
          <div class="flex w-full justify-center mt-2">
            <NuxtImg
              src="/images/ecommerce.png"
              width="400"
              height="200"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            E-Commerce - app
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
            Style Hub is a user-friendly e-commerce app designed to make online shopping fast, secure, and convenient. 
            Browse a wide range of products across categories like electronics, fashion, home essentials, and more. 
            Enjoy personalized recommendations, easy search filters, and seamless checkout with multiple payment options. 
            Track your orders in real-time and manage your wishlist effortlessly.
          </div>
          <div class="flex w-full h-full justify-end items-end">
            <a
              class="flex flex-row justify-end items-center gap-1 pr-4 py-2 underline underline-offset-4 text-sm font-sans hover:text-white/60"
              href="blank ehane pdf file use kora lagbe"
              target="_blank"
              rel="noopener noreferrer"
            >
              Learn more
              <Icon
                name="material-symbols:arrow-right-alt"
                class="duration-300 transition-all text-xl text-stone-200"
              />
            </a>
          </div>
        </div>
        <div
          class="bg-stone-900/40 flex flex-col gap-2 items-start rounded-md pb-4 px-2 pt-2"
        >
          <div class="flex w-full justify-center mt-2 bg-black/60">
            <NuxtImg
              src="/images/care.png"
              width="200"
              height="200"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            Health & Beauty / Skin Care
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
            SkinStudio is your ultimate online destination for healthy and glowing skin. 
            Discover expert tips, product recommendations, and personalized skincare routines designed to meet your unique skin needs. 
            Whether you’re dealing with acne, dryness, or aging, our website provides trusted guidance and high-quality skincare products to help you achieve your best skin.
          </div>
          <div class="flex w-full h-full justify-end items-end">
            <a
              class="flex flex-row justify-end items-center gap-1 pr-4 py-2 underline underline-offset-4 text-sm font-sans hover:text-white/60"
              href="blank ehane pdf file use kora lagbe"
              target="_blank"
              rel="noopener noreferrer"
            >
              Learn more
              <Icon
                name="material-symbols:arrow-right-alt"
                class="duration-300 transition-all text-xl text-stone-200"
              />
            </a>
          </div>
        </div>
        <div
          class="bg-stone-900/40 flex flex-col gap-2 items-start rounded-md pb-4 px-2 pt-2"
        >
          <div class="flex w-full justify-center mt-2">
            <NuxtImg
              src="/images/dashboard.png"
              width="400"
              height="300"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            Quarrier Service Dashboard
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
            The Parcel Wave is a comprehensive dashboard designed to streamline and manage quarrier operations efficiently. 
            It provides real-time insights into quarry activities, material inventory, orders, and workforce management. 
            With an intuitive interface, users can monitor operations, track shipments, and make data-driven decisions to optimize productivity.
          </div>
          <div class="flex w-full h-full justify-end items-end">
            <a
              class="flex flex-row justify-end items-center gap-1 pr-4 py-2 underline underline-offset-4 text-sm font-sans hover:text-white/60"
              href="blank ehane pdf file use kora lagbe"
              target="_blank"
              rel="noopener noreferrer"
            >
              Learn more
              <Icon
                name="material-symbols:arrow-right-alt"
                class="duration-300 transition-all text-xl text-stone-200"
              />
            </a>
          </div>
        </div>
        <div
          class="bg-stone-900/40 flex flex-col gap-2 items-start rounded-md pb-4 px-2 pt-2"
        >
          <div class="flex w-full justify-center mt-2">
            <NuxtImg
              src="/images/furniture.png"
              width="250"
              height="400"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            Furniture & Home Decor website
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
          Elegant is your ultimate destination for stylish, high-quality furniture and home décor.
          Explore a wide range of products including sofas, beds, dining sets, office furniture, and decorative accessories
          that blend comfort, functionality, and design. Our website makes it easy to browse, compare, and purchase furniture that suits your taste and lifestyle.
          </div>
          <div class="flex w-full h-full justify-end items-end">
            <a
              class="flex flex-row justify-end items-center gap-1 pr-4 py-2 underline underline-offset-4 text-sm font-sans hover:text-white/60"
              href="blank ehane pdf file use kora lagbe"
              target="_blank"
              rel="noopener noreferrer"
            >
              Learn more
              <Icon
                name="material-symbols:arrow-right-alt"
                class="duration-300 transition-all text-xl text-stone-200"
              />
            </a>
          </div>
        </div>
        <div
          class="bg-stone-900/40 flex flex-col gap-2 items-start rounded-md pb-4 px-2 pt-2"
        >
          <div class="flex w-full justify-center mt-2">
            <NuxtImg
              src="/images/cleaning.png"
              width="400"
              height="200"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            Services / Car Care app
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
            Wash & Go is a convenient car wash and detailing app that brings professional car cleaning services right to your doorstep. 
            Schedule washes, choose from a variety of services, and get your car sparkling clean without leaving home. Enjoy hassle-free booking, secure payments, 
            and real-time updates on your service.
          </div>
          <div class="flex w-full h-full justify-end items-end">
            <!-- <a
              class=" flex flex-row justify-end items-center gap-1 pr-4 py-2 underline underline-offset-4 text-sm font-sans hover:text-white/60"
              href="https://github.com/MingPV/Game-Shelf"
              target="_blank"
              rel="noopener noreferrer"
            >
              Learn more
              <Icon
                name="material-symbols:arrow-right-alt"
                class="duration-300 transition-all text-xl text-stone-200"
              />
            </a> -->
          </div>
        </div>
        <div
          class="bg-stone-900/40 flex flex-col gap-2 items-start rounded-md pb-4 px-2 pt-2"
        >
          <div class="flex w-full justify-center mt-2">
            <NuxtImg
              src="/images/portfolio_1.png"
              width="400"
              height="200"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            Portfolio - 3D website
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
            A modern portfolio website featuring interactive 3D graphics built
            with Three.js for dynamic visuals and Nuxt.js for server-side
            rendering and smooth user experience. The site showcases projects
            and skills with engaging 3D elements and animations.
          </div>
          <div class="flex w-full h-full justify-end items-end">
            <a
              class="flex flex-row justify-end items-center gap-1 pr-4 py-2 underline underline-offset-4 text-sm font-sans hover:text-white/60"
              href="blank ehane pdf file use kora lagbe"
              target="_blank"
              rel="noopener noreferrer"
            >
              Learn more
              <Icon
                name="material-symbols:arrow-right-alt"
                class="duration-300 transition-all text-xl text-stone-200"
              />
            </a>
          </div>
        </div>
      </div>
    </div>
    <div
      class="xl:flex flex-col hidden w-[5%] h-4/5 justify-center items-center"
    >
      <Icon
        name="hugeicons:vertical-scroll-point"
        class="duration-300 transition-all text-4xl text-stone-700/70 animate-pulse"
      />
    </div>
  </div>
</template>

<script lang="ts" setup>
const rootDiv = ref<HTMLElement | null>(null);

onMounted(() => {});
</script>

<style></style>
