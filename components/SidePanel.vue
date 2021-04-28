<template>
  <div class="flex justify-center my-auto">
    <div class="flex flex-col align-middle">
      <div class="ml-5">
        <div class="flex flex-col">
          <p class="font-bold text-gray-700 font-sans text-xl">Profile</p>
          <div class="">
            <p class="font-semibold mb-4 text-justify font-serif">Seeking a Full-Stack Software Development position Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias itaque minus neque nulla obcaecati, optio quia veritatis. Assumenda cupiditate incidunt laboriosam laudantium maxime obcaecati vero. Commodi eligendi nam necessitatibus quisquam!</p>
          </div>

        </div>
        <div id="info" class="flex flex-row xl:flex-col flex-wrap justify-between">
          <div class="flex flex-col">
            <p class="font-bold text-gray-700 font-sans text-xl mt-3 md:mt-10">Personal Details</p>
            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon icon="calendar-alt"/>
              Birthdate
            </p>
            <p class="font-light mb-4 font-mono">1981</p>
            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon icon="globe-asia"/>
              Nationality
            </p>
            <p class="font-light mb-4 font-mono">Iranian</p>
            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon icon="map-marker-alt"/>
              Address
            </p>
            <p class="font-light mb-4 font-mono">Komitas, Yerevan</p>
          </div>
          <div class="flex flex-col">
            <p class="font-bold text-gray-700 font-sans text-xl mt-3 md:mt-10">Contact</p>
            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon icon="inbox"/>
              Email
            </p>
            <p class="font-light mb-4 font-mono">hesamyan@gmail.com</p>
            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon icon="phone-square-alt"/>
              Phone
            </p>
            <p class="font-light mb-4 font-mono">+374-77-281-774</p>
          </div>
          <div class="flex flex-col">
            <p class="font-bold text-gray-700 font-sans text-xl mt-3 md:mt-10">Links</p>
            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon icon="link"/>
              Linkedin
            </p>
            <a target="_blank" href="https://www.linkedin.com/in/hesamyan/">
              <p class="font-light mb-4 font-mono">linkedin.com/in/hesamyan</p>
            </a>

            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon icon="link"/>
              Github
            </p>
            <a target="_blank" href="https://github.com/hooman734/">
              <p class="font-light mb-4 font-mono">github.com/hooman734</p>
            </a>

            <p class="text-green-900 font-bold text-xl">
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
  name: "SidePanel"
}
</script>

<style scoped>


</style>
