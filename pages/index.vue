<template>
  <div class="page-content-home">
    <!-- Navbar -->
    <Navbar />
    <!-- End Navbar -->
    <div class="hero">
      <div class="hero-overlay"></div>
    </div>

    <section class="page-hero">
      <div class="container">
        <div class="row d-flex justify-content-between align-items-center">
          <div class="col-lg-6 mb-5 text-center text-md-center text-lg-left">
            <h1 class="hero-index mb-2">
              We helps <u class="hero-underline">startup</u> to
            </h1>
            <h1 class="hero-index mb-2">
              getting started & <u class="hero-underline">funding</u>
            </h1>
            <h1 class="hero-index mb-4">their truly needs</h1>
            <p class="mb-4 mt-2">
              Fund the best idea to become <br />
              a real product and be the contributor
            </p>
            <a href="#" class="btn btn-hero">Find a Project</a>
          </div>
          <div class="col-lg-6">
            <div class="image-hero">
              <img
                src="~/assets/images/hero-image.svg"
                alt="imgage-hero"
                class="w-100"
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="page-step">
      <div class="container">
        <div class="row">
          <div class="col-lg-4 text-center text-md-center text-lg-left">
            <h2>Only 3 steps to execute your bright ideas</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-lg-10">
            <img src="~/assets/images/on-progress.svg" alt="" class="w-100" />
          </div>
        </div>
      </div>
    </section>

    <section class="new-project">
      <div class="container">
        <div
          class="row title-project d-flex justify-content-between align-items-center"
        >
          <div class="col-lg-4 text-center text-md-center text-lg-left">
            <h2>
              New projects you can <br />
              taken care of
            </h2>
          </div>
          <div class="col-lg-8 text-center text-md-center text-lg-right">
            <p><a href="#">View All</a></p>
          </div>
        </div>
        <div class="row">
          <div class="col-xs col-sm-12 col-md-6 col-lg-4 col-xl-4 mb-5">
            <div class="card card-project-home">
              <div class="card-body body-project-home">
                <img
                  src="~/assets/images/project-thumbnail-1.svg"
                  alt="thumb-1"
                  class="w-100"
                />
                <h3 class="project-title mt-3">Robotic Hand</h3>
                <p class="project-subtitle">
                  Creating robotic hand for better movement
                </p>

                <div class="progress mt-3">
                  <div
                    class="progress-bar progress-bar-striped progress-bar-animated"
                    role="progressbar"
                    aria-valuenow="20"
                    aria-valuemin="0"
                    aria-valuemax="100"
                    style="width: 20%"
                  ></div>
                </div>
                <div
                  class="roject-text d-flex justify-content-between align-items-center mt-3"
                >
                  <p class="project-percent">20%</p>
                  <p class="project-price text-dark">Rp 100.000.000</p>
                </div>

                <button
                  @click="$router.push({ path: '/projects/1' })"
                  class="btn btn-cta btn-block"
                >
                  Fund Now
                </button>
              </div>
            </div>
          </div>
          <div class="col-xs col-sm-12 col-md-6 col-lg-4 col-xl-4 mb-5">
            <div class="card card-project-home">
              <div class="card-body body-project-home">
                <img
                  src="~/assets/images/project-thumbnail-2.svg"
                  alt="thumb-1"
                  class="w-100"
                />
                <h3 class="project-title mt-3">Auto Pilot Drone</h3>
                <p class="project-subtitle">
                  Self driving drone, no worry to drive again
                </p>

                <div class="progress mt-3">
                  <div
                    class="progress-bar progress-bar-striped progress-bar-animated"
                    role="progressbar"
                    aria-valuenow="45"
                    aria-valuemin="0"
                    aria-valuemax="100"
                    style="width: 45%"
                  ></div>
                </div>
                <div
                  class="roject-text d-flex justify-content-between align-items-center mt-3"
                >
                  <p class="project-percent">45%</p>
                  <p class="project-price text-dark">Rp 80.000.000</p>
                </div>
                <button
                  @click="$router.push({ path: '/projects/1' })"
                  class="btn btn-cta btn-block"
                >
                  Fund Now
                </button>
              </div>
            </div>
          </div>
          <div class="col-xs col-sm-12 col-md-6 col-lg-4 col-xl-4 mb-5">
            <div class="card card-project-home">
              <div class="card-body body-project-home">
                <img
                  src="~/assets/images/project-thumbnail-3.svg"
                  alt="thumb-1"
                  class="w-100"
                />
                <h3 class="project-title mt-3">Wireboard</h3>
                <p class="project-subtitle">
                  The new era of mechanical keyboard
                </p>

                <div class="progress mt-3">
                  <div
                    class="progress-bar progress-bar-striped progress-bar-animated"
                    role="progressbar"
                    aria-valuenow="80"
                    aria-valuemin="0"
                    aria-valuemax="100"
                    style="width: 80%"
                  ></div>
                </div>
                <div
                  class="roject-text d-flex justify-content-between align-items-center mt-3"
                >
                  <p class="project-percent">80%</p>
                  <p class="project-price text-dark">Rp 40.000.000</p>
                </div>
                <button
                  @click="$router.push({ path: '/projects/1' })"
                  class="btn btn-cta btn-block"
                >
                  Fund Now
                </button>
              </div>
            </div>
          </div>
          <div class="col-xs col-sm-12 col-md-6 col-lg-4 col-xl-4 mb-5">
            <div class="card card-project-home">
              <div class="card-body body-project-home">
                <img
                  src="~/assets/images/project-thumbnail-4.svg"
                  alt="thumb-1"
                  class="w-100"
                />
                <h3 class="project-title mt-3">Wireless Earphone</h3>
                <p class="project-subtitle">
                  Just pair to phone and ready to set
                </p>

                <div class="progress mt-3">
                  <div
                    class="progress-bar progress-bar-striped progress-bar-animated"
                    role="progressbar"
                    aria-valuenow="45"
                    aria-valuemin="0"
                    aria-valuemax="100"
                    style="width: 45%"
                  ></div>
                </div>
                <div
                  class="roject-text d-flex justify-content-between align-items-center mt-3"
                >
                  <p class="project-percent">45%</p>
                  <p class="project-price text-dark">Rp 55.000.000</p>
                </div>
                <button
                  @click="$router.push({ path: '/projects/1' })"
                  class="btn btn-cta btn-block"
                >
                  Fund Now
                </button>
              </div>
            </div>
          </div>
          <div class="col-xs col-sm-12 col-md-6 col-lg-4 col-xl-4 mb-5">
            <div class="card card-project-home">
              <div class="card-body body-project-home">
                <img
                  src="~/assets/images/project-thumbnail-5.svg"
                  alt="thumb-1"
                  class="w-100"
                />
                <h3 class="project-title mt-3">Auto Heater</h3>
                <p class="project-subtitle">
                  Make the room keep warm automatically
                </p>

                <div class="progress mt-3">
                  <div
                    class="progress-bar progress-bar-striped progress-bar-animated"
                    role="progressbar"
                    aria-valuenow="70"
                    aria-valuemin="0"
                    aria-valuemax="100"
                    style="width: 70%"
                  ></div>
                </div>
                <div
                  class="roject-text d-flex justify-content-between align-items-center mt-3"
                >
                  <p class="project-percent">70%</p>
                  <p class="project-price text-dark">Rp 75.000.000</p>
                </div>
                <button
                  @click="$router.push({ path: '/projects/1' })"
                  class="btn btn-cta btn-block"
                >
                  Fund Now
                </button>
              </div>
            </div>
          </div>
          <div class="col-xs col-sm-12 col-md-6 col-lg-4 col-xl-4 mb-5">
            <div class="card card-project-home">
              <div class="card-body body-project-home">
                <img
                  src="~/assets/images/project-thumbnail-6.svg"
                  alt="thumb-1"
                  class="w-100"
                />
                <h3 class="project-title mt-3">Smart Lock</h3>
                <p class="project-subtitle">
                  Open the door with just one tap and click
                </p>

                <div class="progress mt-3">
                  <div
                    class="progress-bar progress-bar-striped progress-bar-animated"
                    role="progressbar"
                    aria-valuenow="80"
                    aria-valuemin="0"
                    aria-valuemax="100"
                    style="width: 80%"
                  ></div>
                </div>
                <div
                  class="roject-text d-flex justify-content-between align-items-center mt-3"
                >
                  <p class="project-percent">80%</p>
                  <p class="project-price text-dark">Rp 40.000.000</p>
                </div>
                <button
                  @click="$router.push({ path: '/projects/1' })"
                  class="btn btn-cta btn-block"
                >
                  Fund Now
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="testimonial">
      <div class="testimonial-overlay"></div>
      <div class="container">
        <div class="row title-testimoni">
          <div class="col lg-3 text-center text-md-center text-lg-left">
            <h2>
              See What Our <br />
              Happy Clients Say
            </h2>
          </div>
        </div>
        <div class="row justify-content-around">
          <div class="col-lg-1 d-none d-lg-block mt-2">
            <div class="testi-line">
              <img
                src="~/assets/images/testimonial-line.svg"
                alt="testimonial-line"
                class="w-100"
              />
            </div>
          </div>
          <div class="col-lg-9 text-center text-md-center text-lg-left">
            <div class="testi-text">
              <h3>
                “Funding at Bucker is very easy and comfortable. Just need to
                find an idea, click and already funding.”
              </h3>
              <h4>Shopie Nicole</h4>
              <p>Project Manager</p>
            </div>
            <div
              class="testimonial-icon mt-5 text-center text-md-center text-lg-left"
            >
              <img
                src="~/assets/images/testimonial-1-icon.png"
                alt=""
                class="inline-block testimonial-user mr-3"
              />
              <img
                src="~/assets/images/testimonial-2-icon.png"
                alt=""
                class="inline-block testimonial-user mr-3"
              />
              <img
                src="~/assets/images/testimonial-3-icon.png"
                alt=""
                class="inline-block testimonial-user active mr-3 rounded-circle"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
    <CallToAction />
    <Footer />
  </div>
</template>

<style scoped></style>
