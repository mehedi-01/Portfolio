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
              src="/images/1.png"
              width="600"
              height="400"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
          Shubheccha App - Redesign and Case Study
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
           Shubheccha' is a sophisticated mobile application specially designed for Non-Resident Bangladeshis (NRBs), 
           enabling them to effortlessly complete various critical services and functions of the Bangladesh Government (such as passport,
            National ID, visa, land-related information, etc.) from anywhere in the world. 
            It is an integrated platform designed to further strengthen the connection between expatriates and their homeland.
          </div>
          <div class="flex w-full h-full justify-end items-end">
            <a
              class="flex flex-row justify-end items-center gap-1 pr-4 py-2 underline underline-offset-4 text-sm font-sans hover:text-white/60"
              href="https://www.behance.net/gallery/237557517/Shubheccha-App-Redesign-and-Case-Study"
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
              src="/images/Cover Page.png"
              width="600"
              height="400"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            Rocket Fintech App Redesign & Case Study
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
          I’m excited to share my in-depth redesign of the Rocket Fintech App, where I explored how a modern digital
          banking experience can be made faster,
          clearer, and more intuitive for users.
          </div>
          <div class="flex w-full h-full justify-end items-end">
            <a
              class="flex flex-row justify-end items-center gap-1 pr-4 py-2 underline underline-offset-4 text-sm font-sans hover:text-white/60"
              href="https://www.behance.net/gallery/239608561/Rocket-Fintech-App-Redesign-Case-Study"
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
              src="/images/fashion.png"
              width="600"
              height="400"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            Minimal fashion app UI with smooth flow and style vibes
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
            This project focuses on smooth onboarding, clear navigation, soft color palettes, and high-impact product visuals.
            I explored design principles such as spacing, typography balance, visual hierarchy, and seamless interactions to make the browsing and purchasing process effortless.
            Each component is designed to guide users intuitively, reduce cognitive load, and enhance visual exploration.
          </div>
          <div class="flex w-full h-full justify-end items-end">
            <a
              class="flex flex-row justify-end items-center gap-1 pr-4 py-2 underline underline-offset-4 text-sm font-sans hover:text-white/60"
              href="https://www.behance.net/gallery/239093831/Minimal-fashion-app-UI-with-smooth-flow-and-style-vibes"
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
              src="/images/4 copy.png"
              width="600"
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
              src="/images/SKIN.png"
              width="600"
              height="400"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            Skin Studio – Modern Skincare E-Commerce UI/UX Design
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
            A clean, elegant, and nature-inspired UI design created for a skincare brand focused on purity, self-care, and daily wellness.
            The visual direction blends soft neutrals, natural textures, and high-quality product imagery to create a calm and premium shopping experience.
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
              src="/images/dash.png"
              width="600"
              height="400"
              class="shadow-lg"
              format="webp"
              placeholder
            />
          </div>
          <div class="ml-8 my-2 text-stone-100/80 font-semibold">
            Parcel Wave — Logistics Dashboard
          </div>
          <div class="ml-4 mr-1 text-stone-100 text-start text-md">
          Parcel Wave is a clean and intuitive logistics dashboard designed to simplify shipment tracking, order management, route monitoring, and business analytics. 
          The goal was to create a seamless experience where admins can easily visualize large datasets, monitor real-time deliveries, and make informed decisions.
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
