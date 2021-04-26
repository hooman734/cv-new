<template>
  <div class="flex justify-center my-auto">
    <div class="flex flex-col align-middle">
      <!--      <div class="image rounded-full h-60 w-60 flex items-center justify-center shadow-lg self-center p-6"></div>-->
      <!--  -->
      <div class="flex flex-col">
        <p class="font-bold text-gray-700 font-sans text-2xl">Profile</p>
        <p class="font-semibold">Seeking a Full-Stack Software Development position</p>
      </div>
      <!--  -->
      <div class="ml-5">
        <div class="flex flex-col">
          <p class="font-bold text-gray-700 font-sans text-2xl">Personal Details</p>
          <p class="text-green-900 font-bold text-xl">
            <font-awesome-icon icon="calendar-alt"/>
            Birthdate
          </p>
          <p class="font-light mb-4">1981</p>
          <p class="text-green-900 font-bold text-xl">
            <font-awesome-icon icon="globe-asia"/>
            Nationality
          </p>
          <p class="font-light mb-4">Iranian</p>
          <p class="text-green-900 font-bold text-xl">
            <font-awesome-icon icon="map-marker-alt"/>
            Address
          </p>
          <p class="font-light mb-4">Komitas, Yerevan</p>
        </div>
<!--        -->
        <div class="flex flex-col">
          <p class="font-bold text-gray-700 font-sans text-2xl">Contact</p>
          <p class="text-green-900 font-bold text-xl">
            <font-awesome-icon icon="inbox"/>
            Email
          </p>
          <p class="font-light mb-4">hesamyan@gmail.com</p>
          <p class="text-green-900 font-bold text-xl">
            <font-awesome-icon icon="phone-square-alt"/>
            Phone
          </p>
          <p class="font-light mb-4">+374-77-281-774</p>
        </div>

        <div class="flex flex-col">
          <p class="font-bold text-gray-700 font-sans text-2xl">Links</p>
          <p class="text-green-900 font-bold text-xl">
            <font-awesome-icon icon="link"/>
            Linkedin
          </p>
          <a target="_blank" href="https://www.linkedin.com/in/hesamyan/">
            <p class="font-light mb-4">linkedin.com/in/hesamyan</p>
          </a>

          <p class="text-green-900 font-bold text-xl">
            <font-awesome-icon icon="link"/>
            Github
          </p>
          <a target="_blank" href="https://github.com/hooman734/">
            <p class="font-light mb-4">github.com/hooman734</p>
          </a>

        </div>
      </div>

      <!--  -->

      <!--  -->

      <!-- -->


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
.image {
  background-image: url("../assets/hooman.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

</style>
