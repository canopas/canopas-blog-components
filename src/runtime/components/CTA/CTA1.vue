<template>
  <section
    class="cb-relative cb-bg-[#FDE0E2] cb-bg-gradient-background md:cb-mt-0 md:cb-bg-none"
  >
    <div class="md:cb-hidden cb-mb-[-15px] sm:cb-mb-0">
      <img
        :src="background400w"
        alt="background-image"
        class="cb-absolute cb-h-full cb-w-full"
        loading="lazy"
      />
      <div
        class="cb-blog-container cb-sticky cb-flex cb-flex-col cb-items-center cb-justify-center cb-py-20"
      >
        <p
          class="cb-gradient-text cb-flex cb-text-center cb-font-inter-medium cb-text-base cb-leading-[1.21rem]"
        >
          Get started today
        </p>
        <p
          class="cb-mt-6 cb-text-center cb-font-inter-bold cb-text-4xl cb-leading-[2.723rem] cb-text-black-core/[0.85]"
        >
          Let&apos;s build the next big thing!
        </p>
        <p
          class="cb-mt-4 cb-text-center cb-font-inter-regular cb-text-sm cb-leading-[1.313rem] cb-text-black-core/[0.75]"
        >
          Let&apos;s improve your business&apos;s digital strategy and implement
          robust mobile apps to achieve your business objectives. Schedule Your
          Free Consultation Now.
        </p>
        <nuxt-link :to="'/contact'">
          <div
            class="cb-flex cb-items-center cb-mt-10 cb-mx-auto md:cb-mx-0 cb-w-max cb-rounded-full cb-border cb-border-solid cb-border-transparent cb-bg-gradient-to-r cb-from-[#f2709c] cb-to-[#ff9472] hover:cb-shadow-[inset_2px_1000px_1px_#fff] cb-text-center cb-text-[1.1875rem] cb-leading-[1.1875rem] cb-font-inter-semibold cb-tracking-normal cb-text-white cb-active:scale-[0.98]"
          >
            <span class="cb-py-4 cb-px-[1.2rem] cb-hoverable-text cb-inline-block">
              Get Free Consultation
            </span>
          </div>
        </nuxt-link>
      </div>
    </div>

    <div class="cb-hidden md:cb-block">
      <img
        :src="desktop_background2400w"
        alt="background-image"
        class="cb-absolute cb-h-full cb-w-full"
        loading="lazy"
      />
      <div
        class="cb-blog-container cb-sticky z-[1] cb-flex cb-flex-col cb-items-center cb-justify-center cb-py-20 4xl:cb-py-32"
      >
        <p
          class="cb-gradient-text cb-text-center cb-font-inter-medium cb-text-lg cb-leading-[1.375rem] xl:cb-text-xl xl:cb-leading-[1.513rem]"
        >
          Get started today
        </p>
        <p
          class="cb-mt-4 4xl:cb-mt-6 cb-text-center cb-font-inter-bold cb-text-[2.813rem] cb-leading-[3.438rem] cb-text-black-core/[0.85] xl:cb-text-[3.438rem] xl:cb-leading-[4.16rem]"
        >
          Let&apos;s build the next big thing!
        </p>
        <p
          class="cb-mt-4 4xl:cb-mt-6 w-[75%] cb-text-center cb-font-inter-regular cb-text-[1.063rem] cb-leading-[1.625rem] cb-text-black-core/[0.75] xl:cb-text-xl xl:cb-leading-[1.875rem]"
        >
          Let&apos;s improve your business&apos;s digital strategy and implement
          robust mobile apps to achieve your business objectives. Schedule Your
          Free Consultation Now.
        </p>
        <nuxt-link :to="'/contact'">
          <div
            class="cb-flex cb-items-center cb-mt-10 cb-mx-auto md:cb-mx-0 cb-w-max cb-rounded-full cb-border cb-border-solid cb-border-transparent cb-bg-gradient-to-r cb-from-[#f2709c] cb-to-[#ff9472] hover:cb-shadow-[inset_2px_1000px_1px_#fff] cb-text-center cb-text-[1.1875rem] cb-leading-[1.1875rem] cb-font-inter-semibold cb-tracking-normal cb-text-white active:cb-scale-[0.98]"
          >
            <span class="cb-py-4 cb-px-[1.2rem] cb-hoverable-text cb-inline-block">
              Get Free Consultation
            </span>
          </div>
        </nuxt-link>
      </div>
    </div>
  </section>
</template>

<script setup>
import background400w from "./../../assets/images/cta/first-cta-400w.webp";
import desktop_background2400w from "./../../assets/images/cta/first-cta-2400w.webp";
</script>