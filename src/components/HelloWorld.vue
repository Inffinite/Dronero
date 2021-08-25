<template>
  <div class="all">
    <div class="drones">
      <div class="d-content">
        <div class="drone">
          <div class="drone-inner">
            <div class="d-img-wr">
              <img class="drone-img" src="../assets/drone1.png">
            </div>

            <div class="d-name">
              GoPro karma
            </div>

            <div class="d-price-wr">
              <div class="d-price">
                $ 665
              </div>
            </div>
          </div>
        </div>

        <div class="drone">
          <div class="drone-inner">
            <div class="d-img-wr">
              <img class="drone-img2" src="../assets/drone2.png">
            </div>

            <div class="d-name">
              DJI Inspire v
            </div>

            <div class="d-price-wr">
              <div class="d-price">
                $ 425
              </div>
            </div>
          </div>
        </div>

        <div class="drone">
          <div class="drone-inner">
            <div class="d-img-wr">
              <img class="drone-img2" src="../assets/drone3.png">
            </div>

            <div class="d-name">
              DJI Inspire
            </div>

            <div class="d-price-wr">
              <div class="d-price">
                $ 473
              </div>
            </div>
          </div>
        </div>

        <div class="drone">
          <div class="drone-inner">
            <div class="d-img-wr">
              <img class="drone-img2" src="../assets/drone4.png">
            </div>

            <div class="d-name">
              Parrot
            </div>

            <div class="d-price-wr">
              <div class="d-price">
                $ 665
              </div>
            </div>
          </div>
        </div>

        <div class="drone">
          <div class="drone-inner">
            <div class="d-img-wr">
              <img class="drone-img2" src="../assets/drone5.png">
            </div>

            <div class="d-name">
              Zazzle
            </div>

            <div class="d-price-wr">
              <div class="d-price">
                $ 334
              </div>
            </div>
          </div>
        </div>

        <div class="drone">
          <div class="drone-inner">
            <div class="d-img-wr">
              <img class="drone-img2" src="../assets/drone6.png">
            </div>

            <div class="d-name">
              Hexacopter
            </div>

            <div class="d-price-wr">
              <div class="d-price">
                $ 654
              </div>
            </div>
          </div>
        </div>

        <div class="drone">
          <div class="drone-inner">
            <div class="d-img-wr">
              <img class="drone-img2" src="../assets/drone7.png">
            </div>

            <div class="d-name">
              Phantom
            </div>

            <div class="d-price-wr">
              <div class="d-price">
                $ 557
              </div>
            </div>
          </div>
        </div>

        <div class="drone">
          <div class="drone-inner">
            <div class="d-img-wr">
              <img class="drone-img2" src="../assets/drone8.png">
            </div>

            <div class="d-name">
              DJI Mavic
            </div>

            <div class="d-price-wr">
              <div class="d-price">
                $ 239
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>

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
              <button @click="page2()" class="hire-btn">Hire Drone</button>
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
          <button @click="page2()" class="hire-btn">Hire Drone</button>
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

  methods: {
    page2(){
      gsap.to(".hello", {
        ease: "power3.easeOut",
        display: "none",
        opacity: 0,
        duration: 0.5,
      });

      gsap.to(".drones", {
        ease: "power3.easeOut",
        display: "block",
        duration: 0.5,
      });
    }
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "../styles/Hello.css";
</style>
