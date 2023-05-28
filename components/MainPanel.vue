<template>
  <div class="flex justify-center my-auto mx-3">
    <div class="flex-flex-col align-middle justify-center flex-grow">
      <!--  Experience  -->
      <div class="mt-3 md:mt-10">
        <p ref="topic2" class="font-bold text-gray-700 font-sans">
          <font-awesome-icon icon="briefcase" />
          Experience
        </p>
        <!-- Custom component -->
        <experience
          topic="Parab"
          subTopic="Iran - Armenia"
          date="2015 - Present"
          description1="Mechanical / Civil Engineer at Parab Consultation Company"
          description2="Mechanical and Civil Supervisor and Designer"
          :items="[
            'Supervising Various Construction Projects in Armenia as the Representative of the Company',
            'Utilizing Mechanical Designing Demands of Clients and Also Mechanical Standards and Codes to Design Plans and Generate Records',
            'Make Decisions in Place in Case of Encountering a Necessity of Instant Direction to the Firm Company in Line With the Core Designing Team',
          ]"
        ></experience>
        <experience
          topic="Urban Construction Organization"
          subTopic="Iran - Armenia"
          date="2009 - Present"
          description1="Mechanical Designer Engineer at Urban Construction Organization of Golestan Province"
          description2=""
          :items="[
            'Utilizing The Official Mechanical Standards and Codes, Chapters 14, 16, and 17 as the Standardized Instructions of Mechanical Installments, and all Types of Approved Pipings',
            'Utilizing The Official Mechanical Standards and Codes, Chapters 19, 21, and 22 as the Standardized Instructions of Maintenace and Energy Efficiency Designs',
          ]"
        ></experience>
        <experience
          topic="Talos | AGCS"
          subTopic="USA - Armenia"
          date="2022 - 2023"
          description1="Intern Software Engineer at Talos|AGCS"
          description2=""
          :items="[
            'Working as a Software Engineer working on .Net Projects especially, Including Client-Side ones Using ASP.NET Core Blazor and Windows Presentation Foundation (WPF)',
          ]"
        ></experience>
        <experience
          topic="Manvelyan"
          subTopic="Armenia"
          date="2021 - 2022"
          description1="Full-Stack Software Developer at Manvelyan Consulting Company"
          description2=""
          :items="[
            'Utilizing TypeScript, Angular, Material UI, and Reactive Forms in the Front-End - subtrackr.no',
            'Utilizing Spring-Boot, Ngnix, PostgreSQL, and S3 for the Back-End RESTful API',
            'Utilizing Docker, docker-compose, and BitBucket Pipeline in the CI/CD',
          ]"
        ></experience>
        <experience
          topic="Rahsaz"
          subTopic="Iran"
          date="2005 - 2014"
          description1="Mechanical Engineer of Rahsaz Firm Company"
          description2=""
          :items="[
            'Utilized Provided Construction Documents, and Design Records to Direct the Workers of the Company to Meet the Projects\’ Inspectors\’ Requirements',
            'Had Regular Meetings With the Projects’ Owners and their Designees, and also Engineering Inspection Team to Ensure Maintaining Project’s Workflow',
          ]"
        ></experience>
        <!-- /Custom component -->
        <div ref="body2" class="ml-2 md:ml-9">
          <div class="flex flex-row flex-wrap justify-between">
            <p class="text-green-900 font-bold">
              <font-awesome-icon class="text-xs" icon="dot-circle" />
              AUA
            </p>
            <p class="text-green-900 font-bold">2020 - 2020</p>
          </div>
          <div class="pl-5 pb-4 text-justify break-all">
            <p class="text-gray-400 text-sm mb-1.5">Yerevan, Armenia</p>
            <p class="font-semibold">Graduate School Internship Project</p>
            <ul class="list-inside list-disc">
              <li>
                Used Python, TKinter to create a download-manager with chunking
                support and GUI S3 browser
              </li>
              <li>
                Used Node.js, Socket.IO, and React/Redux to create an online
                chat room with channel support
              </li>
              <li>
                Used .NET Core to create a public traffic transportation
                monitoring with route suggestions
              </li>
            </ul>
          </div>
        </div>
        <!--  Education  -->
        <div>
          <p ref="topic1" class="font-bold text-gray-700 font-sans">
            <font-awesome-icon icon="graduation-cap" />
            Education
          </p>
          <div ref="body1" class="ml-2 md:ml-9">
            <!--  -->
            <div class="flex flex-row flex-wrap justify-between">
              <p class="text-green-900 font-bold">
                <font-awesome-icon class="text-xs" icon="dot-circle" />
                Concordia University
              </p>
              <p class="text-green-900 font-bold">Present</p>
            </div>
            <div class="border-l-4 pl-5">
              <p class="text-gray-400 text-sm mb-1.5">Montreal, Canada</p>
              <p class="font-semibold pb-4">
                Master's in Mechanical Engineering Student
              </p>
            </div>
            <!--  -->
            <div class="flex flex-row flex-wrap justify-between">
              <p class="text-green-900 font-bold">
                <font-awesome-icon class="text-xs" icon="dot-circle" />
                American University of Armenia
              </p>
              <p class="text-green-900 font-bold">2017 - 2020</p>
            </div>
            <div class="border-l-4 pl-5 pb-4 text-justify break-all">
              <p class="text-gray-400 text-sm mb-1.5">Yerevan, Armenia</p>
              <p class="font-semibold">
                Master of Science in Computer and Information Science
              </p>
              <p class="font-semibold">
                Following are some prominent courses during my education at AUA
              </p>
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
            <div class="flex flex-row flex-wrap justify-between">
              <p class="text-green-900 font-bold">
                <font-awesome-icon class="text-xs" icon="dot-circle" />
                Azad University
              </p>
              <p class="text-green-900 font-bold">2011 - 2014</p>
            </div>
            <div class="border-l-4 pl-5">
              <p class="text-gray-400 text-sm mb-1.5">Gorgan, Iran</p>
              <p class="font-semibold pb-4">
                Bachelor of Science in Civil Engineering
              </p>
            </div>
            <div class="flex flex-row flex-wrap justify-between">
              <p class="text-green-900 font-bold">
                <font-awesome-icon class="text-xs" icon="dot-circle" />
                Mazandaran University
              </p>
              <p class="text-green-900 font-bold">1999 - 2004</p>
            </div>
            <div class="pl-5">
              <p class="text-gray-400 text-sm mb-1.5">Babol, Iran</p>
              <p class="font-semibold">
                Bachelor of Science in Mechanical Engineering
              </p>
            </div>
          </div>
        </div>
        <!--  Skills  -->
        <div id="skills" class="flex flex-row flex-wrap align-baseline">
          <!--  Technical Skills  -->
          <div class="mt-3 md:mt-10">
            <p ref="topic3" class="font-bold text-gray-700 font-sans">
              <font-awesome-icon icon="puzzle-piece" />
              Technical Skills
            </p>
            <div ref="body3" class="ml-2 md:ml-9">
              <div class="flex flex-row justify-between">
                <p class="text-green-900 font-bold">
                  <font-awesome-icon class="text-xs" icon="dot-circle" />
                  Programming Language
                </p>
              </div>
              <div class="border-l-4 pl-5 pb-4">
                <div
                  class="
                    flex flex-wrap flex-row
                    align-middle
                    justify-start
                    font-black
                    text-sm
                  "
                >
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    C#
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    C++
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Java
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Golang
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Python
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    JavaScript
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    TypeScript
                  </p>
                </div>
              </div>
              <div class="flex flex-row justify-between">
                <p class="text-green-900 font-bold">
                  <font-awesome-icon class="text-xs" icon="dot-circle" />
                  Front End
                </p>
              </div>
              <div class="border-l-4 pl-5 pb-4">
                <div
                  class="
                    flex flex-row flex-wrap
                    align-middle
                    justify-start
                    font-black
                    text-sm
                  "
                >
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    HTML
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    CSS
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    jQuery
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Tailwind
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Bootstrap
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Semantic-UI
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Angular
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    React
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Vue
                  </p>
                </div>
              </div>
              <div class="flex flex-row justify-between">
                <p class="text-green-900 font-bold">
                  <font-awesome-icon class="text-xs" icon="dot-circle" />
                  Back End
                </p>
              </div>
              <div class="border-l-4 pl-5 pb-4">
                <div
                  class="
                    flex flex-row flex-wrap
                    align-middle
                    justify-start
                    font-black
                    text-sm
                  "
                >
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Node.js
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Express.js
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    .NET Core
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Flask
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Django
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Spring
                  </p>
                </div>
              </div>
              <div class="flex flex-row justify-between">
                <p class="text-green-900 font-bold">
                  <font-awesome-icon class="text-xs" icon="dot-circle" />
                  Libraries
                </p>
              </div>
              <div class="border-l-4 pl-5 pb-4">
                <div
                  class="
                    flex flex-row flex-wrap
                    align-middle
                    justify-start
                    font-black
                    text-sm
                  "
                >
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Tkinter
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Sequelize.js
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Entity Framework.Core
                  </p>
                </div>
              </div>
              <div class="flex flex-row justify-between">
                <p class="text-green-900 font-bold">
                  <font-awesome-icon class="text-xs" icon="dot-circle" />
                  Database / Storage
                </p>
              </div>
              <div class="border-l-4 pl-5 pb-4">
                <div
                  class="
                    flex flex-row flex-wrap
                    align-middle
                    justify-start
                    font-black
                    text-sm
                  "
                >
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    SQLite
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    ​MySQL
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Postgres
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Oracle SQL
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    MongoDB
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    S3
                  </p>
                </div>
              </div>
              <div class="flex flex-row justify-between">
                <p class="text-green-900 font-bold">
                  <font-awesome-icon class="text-xs" icon="dot-circle" />
                  Application Software
                </p>
              </div>
              <div class="pl-5 pb-4">
                <div
                  class="
                    flex flex-row flex-wrap
                    align-middle
                    justify-start
                    font-black
                    text-sm
                  "
                >
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Git
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Linux
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Heroku
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Vercel
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    Docker
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    docker-compose
                  </p>
                  <p
                    class="
                      ring-gray-100
                      rounded
                      bg-gray-100 bg-clip-padding
                      p-1
                      m-1
                    "
                  >
                    localstack
                  </p>
                </div>
              </div>
            </div>
          </div>
          <!--  General Skills  -->
          <div class="mt-3 md:mt-10">
            <p ref="topic4" class="font-bold text-gray-700 font-sans">
              <font-awesome-icon icon="wrench" />
              General Skills
            </p>
            <div ref="body4" class="ml-2 md:ml-9">
              <div class="flex flex-row justify-between">
                <p class="text-green-900 font-bold">
                  <font-awesome-icon class="text-xs" icon="dot-circle" />
                  IELTS General
                </p>
              </div>
              <div class="border-l-4 pb-4">
                <div class="">
                  <progress-bar percent="72.22">6.5</progress-bar>
                </div>
              </div>
              <!--              -->
              <div class="flex flex-row justify-between">
                <p class="text-green-900 font-bold">
                  <font-awesome-icon class="text-xs" icon="dot-circle" />
                  TOEFL Academic
                </p>
              </div>
              <div class="pb-4">
                <div class="">
                  <progress-bar percent="72.66">86</progress-bar>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!---->

        <div class="mt-3 md:mt-10">
          <div id="articles" class="container">
            <p ref="topic5" class="font-bold text-gray-700 font-sans">
              <font-awesome-icon icon="pen-nib" />
              Articles
            </p>
            <div
              ref="body5"
              class="
                flex flex-row flex-wrap
                justify-center
                md:justify-start
                content-evenly
                ml-2
                md:ml-9
              "
            >
              <article-cp
                topic="Experience With F#"
                link="https://hesamyan.medium.com/experience-with-f-618118e99408"
                date="Mar 3 - 2021"
              >
                <div class="cursor-help">
                  Here I am going to share my experience with F# — the
                  functional-first, general-purpose, strongly typed,
                  multi-paradigm programming language — which I have recently
                  started to learn.
                </div>
              </article-cp>
              <article-cp
                topic="Setting up Dockerfile & GitHub Workflow"
                link="https://hesamyan.medium.com/setting-up-dockerfile-github-workflow-86cafd82cf97"
                date="Jan 30 - 2021"
              >
                <div class="cursor-help">
                  Here I want to tell my experience with Docker builder and
                  GitHub Workflow. I had a React project developed using Next.js
                  and stored in my GitHub account for a while, so it came to my
                  mind to fiddle with this repository using.
                </div>
              </article-cp>
              <article-cp
                topic="Implementing four types of linked-lists"
                link="https://hesamyan.medium.com/implementing-four-types-of-linked-lists-d812d5c39812"
                date="Dec 31 - 2020"
              >
                <div class="cursor-help">
                  I recently have developed four types of linked-lists, namely:
                  singly-linked-list—doubly-linked-list—circular-singly-linked-list—circular-doubly-linked-list.
                </div>
              </article-cp>
              <article-cp
                topic="Switching from NetworkManager to systemd-networkd"
                link="https://hesamyan.medium.com/switching-from-networkmanager-to-systemd-networkd-dcbda0b15056"
                date="Dec 24 - 2020"
              >
                <div class="cursor-help">
                  As the letter ‘d’ in the name of “systemd-networkd” infers for
                  “daemon” mode, this service is meant to manage all network
                  stuff in the background rather than “NetworkManager” is for
                  setting network graphically up with the help of its GUI.
                </div>
              </article-cp>
              <article-cp
                topic="Deploying a React Web Application that's created by create-react-app"
                link="https://hesamyan.medium.com/deploying-a-react-web-application-thats-created-by-create-react-app-2234ddf8eafa"
                date="Dec 9 - 2020"
              >
                <div class="cursor-help">
                  Introduction Upon the completion of my React web app that was
                  initially made by create-react-app, I tried to deploy it on
                  Heroku, but it basically seemed a bit difficult. To get some
                  clues for resolving that, as googling has been always the
                  primitive choice, so I did it.
                </div>
              </article-cp>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import gsap from "gsap";
import ScrollToPlugin from "gsap/dist/ScrollTrigger";
gsap.registerPlugin(ScrollToPlugin);
import { library } from "@fortawesome/fontawesome-svg-core";
import {
  faGraduationCap,
  faDotCircle,
  faBriefcase,
  faPuzzlePiece,
  faWrench,
  faPenNib,
} from "@fortawesome/free-solid-svg-icons";
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import Experience from "./Experience.vue";

library.add(
  faGraduationCap,
  faDotCircle,
  faBriefcase,
  faPuzzlePiece,
  faWrench,
  faPenNib
);

Vue.component("font-awesome-icon", FontAwesomeIcon);

export default {
  components: { Experience },
  name: "MainPanel",
  mounted() {
    gsap.from(this.$refs.topic1, {
      duration: 2,
      fontSize: "4rem",
      x: "4rem",
      opacity: 0,
      ease: "back.out(1.7)",
      scrollTrigger: {
        trigger: this.$refs.topic1,
      },
    });
    gsap.from(this.$refs.topic2, {
      duration: 1,
      fontSize: "4rem",
      x: "4rem",
      opacity: 0,
      ease: "back.out(1.7)",
      scrollTrigger: {
        trigger: this.$refs.topic2,
      },
    });
    gsap.from(this.$refs.topic3, {
      duration: 1,
      fontSize: "4rem",
      x: "4rem",
      opacity: 0,
      ease: "back.out(1.7)",
      scrollTrigger: {
        trigger: this.$refs.topic3,
      },
    });
    gsap.from(this.$refs.topic4, {
      duration: 1,
      fontSize: "4rem",
      x: "4rem",
      opacity: 0,
      ease: "back.out(1.7)",
      scrollTrigger: {
        trigger: this.$refs.topic4,
      },
    });
    gsap.from(this.$refs.topic5, {
      duration: 1,
      fontSize: "4rem",
      x: "4rem",
      opacity: 0,
      ease: "back.out(1.7)",
      scrollTrigger: {
        trigger: this.$refs.topic5,
      },
    });

    //

    gsap.from(this.$refs.body1, {
      duration: 1,
      x: "-4rem",
      opacity: 0,
      delay: 0.5,
      scrollTrigger: {
        trigger: this.$refs.topic1,
      },
    });
    gsap.from(this.$refs.body2, {
      duration: 1,
      x: "-4rem",
      opacity: 0,
      delay: 0.5,
      scrollTrigger: {
        trigger: this.$refs.topic2,
      },
    });
    gsap.from(this.$refs.body3, {
      duration: 1,
      x: "-4rem",
      opacity: 0,
      delay: 0.5,
      scrollTrigger: {
        trigger: this.$refs.topic3,
      },
    });
    gsap.from(this.$refs.body4, {
      duration: 1,
      x: "-4rem",
      opacity: 0,
      delay: 0.5,
      scrollTrigger: {
        trigger: this.$refs.topic4,
      },
    });
    gsap.from(this.$refs.body5, {
      duration: 1,
      x: "-4rem",
      opacity: 0,
      delay: 0.5,
      scrollTrigger: {
        trigger: this.$refs.topic5,
      },
    });
  },
};
</script>

<style scoped>
</style>
