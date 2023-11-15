<template>
  <section>
    <div class="tw-container tw-mx-auto tw-w-full md:tw-pt-20">
      <div class="tw-mx-auto tw-mt-10 tw-grid dark:tw-text-orange-50 lg:tw-gap-20 xl:tw-grid-cols-3">
        <div class="tw-text-center">
          <span
            aria-hidden="true"
            class="tw-i-ph-atom-light tw-inline-block tw-h-16 tw-w-16 tw-text-indigo-500 dark:tw-text-purple-400 md:tw-h-28 md:tw-w-28"
          />
          <h3 class="tw-mb-5 tw-text-xl tw-font-semibold tw-text-indigo-800 dark:tw-text-indigo-100 md:tw-mb-10 md:tw-text-5xl">
            Design
          </h3>
          <div  class="tw-text-justify">
            <p>
              <!-- With a keen eye for design and a focus on user experience, I'm great at creating
              <span class="tw-font-semibold dark:tw-text-indigo-100">
                delightful interfaces that seamlessly blend aesthetics with functionality.</span>
              <br><br>
              I'm a big fan of "designing with code": By developing living style guides, it is often easier for teams to maintain scalable
              and consistent UIs. However, I still mostly use tools like Figma for ideation and sketching,
              and to create wireframes and mockups. -->

              With a keen eye for design and a focus on user experience, our team excels at creating interfaces that seamlessly 
              blend aesthetics with functionality.We navigate the intricate balance between visual appeal and user-centric design, 
              ensuring an intuitive experience for our clients.<br> <br> Our proficiency in design systems making it 
              easier for teams to build and maintain digital experiences that stand the test of time.
            
            </p>
          </div>
        </div>
        <div class="tw-mt-10 tw-text-center md:tw-mt-20 lg:tw-mt-0">
          <span
            aria-hidden="true"
            class="tw-i-ph-magic-wand-light tw-inline-block tw-h-16 tw-w-16 tw-text-indigo-500 dark:tw-text-purple-400 md:tw-h-28 md:tw-w-28"
          />
          <h3 class="tw-mb-5 tw-text-xl tw-font-semibold tw-text-indigo-800 dark:tw-text-indigo-100 md:tw-mb-10 md:tw-text-5xl">
            Development
          </h3>
          <p class="tw-text-justify">
            <span class="tw-font-semibold dark:tw-text-indigo-100">
              <!--Writing code is my favorite way to bring designs to life: -->
            </span>
            <!-- As an "architect" of user interfaces, I make sure that every button click, every animation and UI element responds intuitively.<br><br> -->
            <!-- By now, I've got a versatile technical skill set and I'm experienced in different front&#8209;end frameworks and libraries. -->
            <!-- That means I can pick the perfect tools for each project. -->
           
          
            As architects of user interfaces, we ensure that every button click, animation, and design element responds intuitively. Our versatile 
              technical skill set and experience with different front-end frameworks and libraries empower us to select the perfect tools for each project.<br><br>
               This adaptability allows us to deliver not just functional solutions but also ones that are optimized for performance, responsiveness, and 
               innovation.

          </p>
        </div>
        <div class="tw-mt-10 tw-text-center md:tw-mt-20 lg:tw-mt-0">
          <span
            aria-hidden="true"
            class="tw-i-ph-heart-light tw-inline-block tw-h-16 tw-w-16 tw-text-indigo-500 dark:tw-text-purple-400 md:tw-h-28 md:tw-w-28"
          />

          <h3 class="tw-mb-5 tw-text-xl tw-font-semibold tw-text-indigo-800 dark:tw-text-indigo-100 md:tw-mb-10 md:tw-text-5xl">
            A11y
          </h3>
          <p class="tw-text-justify">
            <span class="tw-font-semibold dark:tw-text-indigo-100">
              <!-- My goal is to make the web a more accessible and engaging place. -->
            </span> 
            <!-- While there's still a lot to learn (and always will be), I am doing my best to build applications that
            are inclusive and smoothly adapt to different devices and screen sizes.<br><br>
            <wbr>
            Using end-to-end testing tools like Cypress.io, I furthermore ensure that the front&#8209;end functions
            correctly and meets high-quality standards. -->


            Our commitment extends to ensuring that the applications we develop are inclusive and smoothly adapt to environment. Utilizing 
              end-to-end testing tools like Cypress, we guarantee that our application solution functions correctly and meets the highest 
              quality standards.<br> <br>Our approach to accessibility is not just a compliance checkbox but a commitment to creating 
              digital experiences that everyone can enjoy.
            
          </p>
        </div>
      </div>
    </div>


    <the-tech-stack />

    <next-section-link
      container-class="tw-block md:tw-mt-40 md:tw-mb-40"
      target="#contact"
      title="Contact Us"
    />
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import NextSectionLink from './NextSectionLink.vue'
import TheTechStack from './TheTechStack.vue'

export default defineComponent({
  components: {
    NextSectionLink,
    TheTechStack,
  },
})
</script>