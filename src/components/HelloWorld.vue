<template>
  <div>
    <div class="hello">
      <div class="bottom-mesh">
        <div class="b-m">
          
        </div>
      </div>

      <div class="details-wr">
        <div>
          <div class="title">Dronero</div>

          <div class="s-wr">
            <div class="subtitle">Unmanned aircraft services for hire</div>
          </div>

          <div class="d-controls">
            <div class="hire-w">
              <button class="hire-btn">Hire Drone</button>
            </div>

            <div class="learn-more">
              Learn More
              <svg
                class="l-icon"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
          </div>
        </div>
      </div>

      <div class="circle-wr">
        <div class="circle">
          <div class="circle-2">
            <div class="circle-3">
              <div class="circle-4">
                <div class="circle-5">
                  <img class="drone1" src="../assets/drone1.png" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="details-mb">
        <div class="title">Dronero</div>

        <div class="s-wr">
          <div class="subtitle">Unmanned aircraft services for hire</div>
        </div>

        <div class="hire-w">
          <button class="hire-btn">Hire Drone</button>
        </div>

        <div class="learn-more">
          Learn More
          <svg
            class="l-icon"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
              clip-rule="evenodd"
            />
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import gsap from "gsap";

export default {
  name: "HelloWorld",

  async mounted() {
    await gsap.to(".circle-5", {
      ease: "power3.easeOut",
      display: "flex",
      opacity: 1,
      duration: 0.5,
    });

    await gsap.to(".circle-4", {
      ease: "power3.easeOut",
      display: "flex",
      opacity: 1,
      duration: 0.5,
    });

    await gsap.to(".circle-3", {
      ease: "power3.easeOut",
      display: "flex",
      opacity: 1,
      duration: 0.5,
    });

    await gsap.to(".circle-2", {
      ease: "power3.easeOut",
      display: "flex",
      opacity: 1,
      duration: 0.5,
    });

    await gsap.to(".circle", {
      ease: "power3.easeOut",
      display: "flex",
      opacity: 1,
      duration: 0.5,
    });

    await gsap.to(".drone1", {
      ease: "power3.easeOut",
      opacity: 1,
      duration: 0.5,
    });

    await gsap.to(".drone1", {
      ease: "power3.easeOut",
      rotate: -20,
      duration: 0.5,
    });

    await gsap.to(".title", {
      ease: "power3.easeOut",
      y: 0,
      opacity: 1,
      duration: 0.8,
    });

    await gsap.to(".subtitle", {
      ease: "power3.easeOut",
      y: 0,
      opacity: 1,
      duration: 0.8,
    });

    await gsap.to(".hire-btn", {
      ease: "power3.easeOut",
      y: 0,
      opacity: 1,
      duration: 0.8,
    });

    await gsap.to(".learn-more", {
      ease: "power3.easeOut",
      y: 0,
      opacity: 1,
      duration: 0.8,
    });
  },

  methods: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "../styles/Hello.css";
</style>
