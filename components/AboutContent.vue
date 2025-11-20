<template>
  <div
    ref="rootDiv"
    class="flex flex-row absolute left-auto w-auto top-20 right-60 h-auto justify-center items-center gap-12 duration-500 transition-all"
  >
    <div
      class="flex flex-row w-[80%] mt-[10vh] lg:mt-0 lg:w-[80%] lg:ml-12 h-full lg:h-4/5 items-start justify-center font-serif bg-stone-700/70 backdrop-blur-md rounded-md"
    >
      <div
        class="w-1/3 h-full pt-8 hidden md:flex flex-col items-center justify-start"
      >
        <NuxtImg
          src="/images/nnnn.jpg"
          alt="Mehedi Hasan"
          width="400"
          height="500"
          class="rounded-lg shadow-lg"
          format="webp"
          placeholder
        />
        <div class="flex flex-col items-start w-full mt-8 gap-3">
          <div class="font-bold text-stone-100 ml-10">
            Name : Mehedi
          </div>
          <div class="font-bold text-stone-100 ml-10">
            Full Name : Md Mehedi Hasan
          </div>
          <div class="flex flex-row flex-wrap items-center gap-4 ml-6">
            <Icon
              name="uil:behance"
              class="duration-300 transition-all text-3xl"
            />
            <a
              href="https://www.behance.net/mehediuiux-01"
              class="text-stone-200/90 hover:text-stone-100 text-sm"
            >
              mehediuiux01
            </a>
          </div>
          <div class="flex flex-row flex-wrap items-center gap-4 ml-6">
            <Icon
              name="devicon:linkedin"
              class="duration-300 transition-all text-3xl"
            />
            <a
              href="https://www.linkedin.com/in/mehediuiux37/"
              class="text-stone-200/90 hover:text-stone-100 text-sm"
            >
              mehediuiux37
            </a>
          </div>
                    <div class="flex flex-row items-center gap-4 mt-2 ml-6">
            <Icon
              name="uil:github"
              class="text-stone-100/80 duration-300 transition-all text-3xl"
            />
            <a
              href="https://github.com/Mehedi-01"
              class="text-stone-200/90 hover:text-stone-100 text-sm"
            >
              mehedi-01
            </a>
          </div>
        </div>
      </div>
      <div
        class="w-full mx-4 md:w-2/3 h-auto flex flex-col justify-start md:mx-2 pt-10 pb-15"
      >
        <div
          class="text-2xl md:text-2xl xl:text-6xl font-bold mb-0 text-stone-300/90"
        >
          About Me
        </div>
        <div class="flex flex-row w-full justify-center">
          <NuxtImg
            src="/images/Na.jpg"
            alt="MingPV"
            width="300"
            height="300"
            class="rounded-lg shadow-lg md:hidden"
            format="webp"
            placeholder
          />
        </div>
        <div
          class="md:ml-8 mt-2 text-stone-200/70 text-start md:text-left text-xs md:text-sm lg:text-lg"
        >
          Hi, I'm Mehedi, a software engineering student from Daffodil International University with a
          passion for Ui/Ux design and software design. I have experience in ui/ux design, software product development and various programming languages. I am always eager to learn
          new technologies.
        </div>
        <div
          class="w-full h-full bg-stone-900/40 mt-4 flex flex-col gap-4 lg:gap-3 justify-start items-start"
        >
          <div
            class="my-1 mx-1 md:mx-6 w-full flex justify-start items-start flex-col"
          >
            <div class="font-bold text-stone-200">Education</div>
            <div
              class="flex flex-wrap gap-1 lg:gap-4 font-semibold font-sans text-xs md:text-sm lg:text-lg ml-2 text-stone-400"
            >
              <div>
                Bachelor of Science in Software Engineering 
              </div>
              <div>Daffodil International University</div>
            </div>
          </div>
          <div
            class="my-0 mx-3 md:mx-6 w-full flex justify-start items-start flex-col"
          >
            <div class="font-bold text-stone-200">UI/UX Skills</div>
            <div class="flex flex-col items-start">
              <div
                class="flex flex-col text-left gap-1 lg:gap- font-semibold font-sans text-xs md:text-sm lg:text-lg ml-2 text-stone-400"
              >
                <div>User Interview</div>
                <div>Usability Testing</div>
                <div>User Flow</div>
                <div>Sitemap</div>
                <div>Wireframing</div>
                <div>Prototyping</div>
                <div>Visual Design</div>
                <div>Interaction Design</div>
                <div>Competitive Analysis</div>
                <div>Information Architecture</div>
                <div>Design Hierarchy</div>
              </div>
            </div>
          </div>
          <div
            class="my-1 mx-2 md:mx-6 w-full flex justify-start items-start flex-col"
          >
            <div class="font-bold  text-stone-200">Tools</div>
            <div class="flex flex-col  items-start">
              <div
                class="flex flex-col text-left gap-1 lg:gap-1 font-semibold font-sans text-xs md:text-sm lg:text-lg ml-2 text-stone-400"
              >
                <div>Figma</div>
                <div>Adobe Photoshop</div>
                <div>VS Code</div>
              </div>
            </div>
                        <div class="font-bold text-stone-200">Technical skills</div>
            <div class="flex flex-col  items-start">
              <div
                class="flex flex-col text-left gap-1 lg:gap-1 font-semibold font-sans text-xs md:text-sm lg:text-lg ml-2 text-stone-400"
              >
                <div>UI/UX</div>
                <div>HTML</div>
                <div>CSS</div>
                <div>Bootstrap</div>
                <div>Tailwind CSS</div>
                <div>JavaScript</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div
      class="lg:flex flex-col hidden lg:w-[1%] h-7/15 items-start justify-start"
    >
    </div>
  </div>
</template>

<script lang="ts" setup>
const rootDiv = ref<HTMLElement | null>(null);

onMounted(() => {
  if (rootDiv.value) {
    // rootDiv.value.classList.add("translate-x-20");
    // rootDiv.value.classList.add("animate-once");
    // function handleAnimationEnd() {
    //   rootDiv.value?.classList.remove("translate-x-20");
    //   rootDiv.value?.classList.remove("animate-once");
    //   rootDiv.value?.removeEventListener("animationend", handleAnimationEnd);
    // }
    // rootDiv.value.addEventListener("animationend", handleAnimationEnd);
  }
});
</script>

<style></style>
