<template>
  <q-page class="">
    <div class="bg-main row">
      <div
        class="col-12 q-pt-lg q-px-sm-lg q-px-md flex items-center justify-between"
      >
        <q-img class="logo" src="~assets/logo-white.png" width="160px" />
        <div>
          <q-btn
            style="color: #21ba45"
            label="Log in"
            class="q-mr-sm text-weight-regular"
            no-caps
            unelevated
          />
          <q-btn
            color="positive"
            label="Register"
            no-caps
            class="q-px-lg text-weight-regular"
            unelevated
          />
        </div>
      </div>
      <div
        class="col-12 col-md-11 q-mx-auto q-py-xl q-px-sm-xl q-px-lg row items-center justify-between"
      >
        <div class="col-md-6 col-sm-7 col-12 q-pr-md-lg">
          <h3 class="text-white text-weight-bold q-my-xs text-h3">
            Digital <span class="text-positive">ID Card</span> <br />
            App Made Sample
          </h3>
          <hr class="q-my-lg" />
          <p class="text-sm text-grey-1 q-mt-sm q-pr-lg text-weight-light">
            Lorem ipsum is placeholder text commonly used in the graphic, print
            and publishing industries for previewing layouts and visual mockups.
          </p>
          <q-btn
            color="indigo-8"
            label="Sign up"
            no-caps
            class="q-px-xl q-mb-md q-mt-sm text-weight-regular"
            unelevated
          />
          <q-btn
            color="primary"
            class="q-mb-md q-mt-sm q-ml-sm text-weight-regular"
            no-caps
            unelevated
            ><q-img
              src="~assets/play-button.png"
              width="16px"
              class="q-mr-sm"
            />
            <span>Watch Video</span>
          </q-btn>
        </div>
        <div class="col-sm-5 col-12 q-pt-md q-pt-sm-none">
          <q-img src="~assets/virtual-id-card-1.png" width="100%" />
        </div>
      </div>
    </div>
    <div class="bg-deep-purple-1 row q-py-xl q-px-sm-xl q-px-md">
      <div class="col-12 col-md-8 q-mx-auto row">
        <div class="col-sm-4 col-12 q-pa-sm q-pb-lg q-pr-sm-md">
          <h6 class="text-secondary text-weight-bold q-my-xs">Our Services</h6>
          <p class="text-sm q-mt-sm q-pr-lg">
            Get the freedom to experiment, lounch and scale strategies as fast
            as you can think of them.
          </p>
          <div class="q-pr-sm-md">
            <q-img src="~assets/m3.png" width="" />
          </div>
        </div>
        <div class="col-sm-8 col-12 row">
          <div class="col-sm-6 col-12 q-pa-sm" v-for="n in 4" :key="n">
            <q-card
              class="q-px-md q-pt-sm relative-position overflow-hidden shadow"
              flat
            >
              <p
                class="text-secondary text-weight-bold text-body1 q-my-xs q-mb-none"
              >
                Student ID Cards
              </p>
              <p class="text-sm q-mt-xs q-pb-lg q-mb-lg">
                School can issue mobile ID cards to their students using our Id.
                Management System. You can also customize cards for teachers,
                parents and staff.
              </p>
              <div class="absolute card-bottom-img"></div>
            </q-card>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-white row q-pt-lg q-px-sm-xl q-px-md text-center">
      <div class="col-sm-10 col-md-7 q-mx-auto flex column items-center">
        <h5 class="text-secondary text-weight-bold q-my-sm q-pt-md">
          Digital Identity
        </h5>
        <p class="text-body q-mb-none">
          Lorem ipsum color sit amet consectetur adipiscing eli sed do elusmod
          tempor incidid ut labore at colore magna alliqua. Ut enim ad minim
          veniam,quis nestrud exc itation ullamco laboris nisi ut alliquip ex ea
          cornmodo consequat.
        </p>
        <q-img src="~assets/virtual-id-card-1.png" width="80%" class="gt-xs" />
        <q-img src="~assets/virtual-id-card-1.png" width="100%" class="lt-sm" />
      </div>
    </div>
    <div
      class="bg-private flex column items-center q-py-xl text-center q-px-md"
    >
      <h4 class="text-white text-weight-bold q-my-sm q-pt-md">
        IDCard Private Digital Currency
      </h4>
      <p class="text-white text-body q-mb-lg q-mt-sm">
        Bitmin is a secure, private, and untraceable cryptocurrency. It is
        open-source and acessible to all.
      </p>
      <q-btn
        color="indigo-8"
        label="Get Started"
        no-caps
        class="q-px-xl q-mb-md q-py-sm"
        unelevated
      />
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "PageIndex",
});
</script>
