<template>
  <div class="flex justify-center my-auto">
    <div class="flex-flex-col align-middle justify-center">


      <div class="">
        <p class="font-bold text-gray-700 font-sans text-2xl">
          <font-awesome-icon icon="graduation-cap"/>
          Education
        </p>
        <div class="ml-9">
        <div class="flex flex-row justify-between">
          <p class="text-green-900 font-bold text-xl">
            <font-awesome-icon class="text-sm" icon="dot-circle"/>
            American University of Armenia
          </p>
          <p class="text-green-900 font-bold">2017 - 2020</p>
        </div>


          <div class="border-l-4 pl-5 pb-4">
            <p class="font-semibold">Master of Science in Computer and Information Science</p>
            <p class="font-semibold">Following are some prominent courses during my education at AUA</p>
            <ul class="list-inside list-disc">
              <li>Data Structures</li>
              <li>Algorithms (Intermediate and Advanced)</li>
              <li>Object-Oriented Programming</li>
              <li>Theory of Computing</li>
              <li>Network Programming</li>
              <li>Computer-Aided Manufacturing (CAM)</li>
              <li>Cryptography</li>
              <li>Image Processing</li>
            </ul>
          </div>

          <div class="flex flex-row justify-between">
            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon class="text-sm" icon="dot-circle"/>
              Azad University
            </p>
            <p class="text-green-900 font-bold">2011 - 2014</p>
          </div>
          <div class="border-l-4 pl-5">
            <p class="font-semibold pb-4">Bachelor of Science in Civil Engineering</p>
          </div>
          <div class="flex flex-row justify-between">
            <p class="text-green-900 font-bold text-xl">
              <font-awesome-icon class="text-sm" icon="dot-circle"/>
              Mazandaran University
            </p>
            <p class="text-green-900 font-bold">1999 - 2004</p>
          </div>

          <div class="pl-5">
            <p class="font-semibold">Bachelor of Science in Mechanical Engineering</p>
          </div>


        </div>
      </div>
    </div>
  </div>

</template>

<script>
import Vue from 'vue'
import {library} from '@fortawesome/fontawesome-svg-core'
import {faGraduationCap, faDotCircle} from '@fortawesome/free-solid-svg-icons'
import {FontAwesomeIcon} from '@fortawesome/vue-fontawesome'

library.add(faGraduationCap, faDotCircle)

Vue.component('font-awesome-icon', FontAwesomeIcon)

export default {
  name: "MainPanel"
}
</script>

<style scoped>

</style>
