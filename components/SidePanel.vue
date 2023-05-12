<template>
  <div class="flex justify-center my-auto">
    <div class="flex flex-col align-middle">
      <div class="ml-5">
        <div class="flex flex-col">
          <p class="font-bold text-gray-700 font-sans text-xl">Profile</p>
          <div class="">
            <p id="txt" ref="info" class="font-semibold mb-4 text-justify break-all hover:text-green-900 tracking-tighter"></p>
          </div>

        </div>
        <div id="info" class="flex flex-row xl:flex-col flex-wrap justify-between">
          <div class="flex flex-col">
            <p class="font-bold text-gray-700 font-sans mt-3 md:mt-10">Personal Details</p>
            <p class="text-green-900 font-bold">
              <font-awesome-icon icon="calendar-alt"/>
              Birthdate
            </p>
            <p class="font-light mb-4 font-mono">1981</p>
            <p class="text-green-900 font-bold">
              <font-awesome-icon icon="globe-asia"/>
              Nationality
            </p>
            <p class="font-light mb-4 font-mono">Iranian</p>
            <p class="text-green-900 font-bold">
              <font-awesome-icon icon="map-marker-alt"/>
              Address
            </p>
            <p class="font-light mb-4 font-mono">Komitas, Yerevan</p>
          </div>
          <div class="flex flex-col">
            <p class="font-bold text-gray-700 font-sans mt-3 md:mt-10">Contact</p>
            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon icon="inbox"/>
              Email
            </p>
            <p class="font-light mb-4 font-mono">
              <a target="_blank" href="mailto:hesamyan@outlook.com">hesamyan@outlook.com</a></p>
            <p class="text-green-900 font-bold">
              <font-awesome-icon icon="phone-square-alt"/>
              Phone
            </p>
            <p class="font-light mb-4 font-mono"><a target="_blank" href="tel:+37433281774">+374-33-281-774</a></p>
          </div>
          <div class="flex flex-col">
            <p class="font-bold text-gray-700 font-sans mt-3 md:mt-10">Links</p>
            <p class="text-green-900 font-bold">
              <font-awesome-icon icon="link"/>
              Linkedin
            </p>
            <a target="_blank" href="https://www.linkedin.com/in/hesamyan/">
              <p class="font-light mb-4 font-mono">linkedin.com/in/hesamyan</p>
            </a>

            <p class="text-green-900 font-bold">
              <font-awesome-icon icon="link"/>
              Github
            </p>
            <a target="_blank" href="https://github.com/hooman734/">
              <p class="font-light mb-4 font-mono">github.com/hooman734</p>
            </a>
            
            <p class="text-green-900 font-bold">
              <font-awesome-icon icon="link"/>
              Gitlab
            </p>
            <a target="_blank" href="https://gitlab.com/hooman734">
              <p class="font-light mb-4 font-mono">gitlab.com/hooman734</p>
            </a>

            <p class="text-green-900 font-bold">
              <font-awesome-icon icon="link"/>
              Diploma
            </p>
            <a target="_blank" href="https://hooman734.github.io/assets/Masters-Diploma.pdf">
              <p class="font-light mb-4 font-mono">Master's Diploma</p>
            </a>

          </div>
        </div>

        </div>


<!--        -->






    </div>
  </div>

</template>

<script>
import Vue from 'vue'
import gsap from 'gsap'
import TextPlugin from 'gsap/dist/TextPlugin'
gsap.registerPlugin(TextPlugin)

import {library} from '@fortawesome/fontawesome-svg-core'
import {
  faInbox,
  faGlobeAsia,
  faMapMarkerAlt,
  faCalendarAlt,
  faPhoneSquareAlt,
  faLink
} from '@fortawesome/free-solid-svg-icons'
import {FontAwesomeIcon} from '@fortawesome/vue-fontawesome'

library.add(faInbox, faGlobeAsia, faMapMarkerAlt, faCalendarAlt, faPhoneSquareAlt, faLink)

Vue.component('font-awesome-icon', FontAwesomeIcon)
export default {
  name: "SidePanel",
  mounted() {
    gsap.to(this.$refs.info, {duration: 10, text: "As a Mechanical / Civil Supervisor and Designer, I bring a unique blend of skills to my work, including experience managing multiple construction projects in Armenia, designing plans that meet client demands and industry standards, and providing quick direction to my team when needed.\n" +
        "I received my Master's degree at the American University of Armenia in 2020 in Computer Science, which has helped me develop a strong foundation in software development and stay up-to-date with the latest industry trends.\n" +
      "In addition to my profession as a representative of Parab consulting company, I am also an Intern Software Engineer at Talos|AGCS company, where I use my skills as a Software Developer to stay abreast of new technologies and trends. I am particularly interested in Microsoft Blazor, which provides the ability to develop in both front and back ends using only C#."})
  }
}

</script>

<style scoped>


</style>
