<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container>
      <router-view />
    </q-page-container>
    <div class="bg-white">
      <div
        class="q-py-lg flex row no-wrap justify-between items-center q-px-sm-md"
      >
        <div class="col-6 col-sm-5 col-md-3 q-pr-sm-lg q-pr-lg-xl">
          <q-img src="~assets/logo.png" />
        </div>
        <div class="q-pr-md">
          <p class="text-black q-mb-none">For any queries, call us</p>
          <h1 class="text-indigo-8 text-body1 text-weight-bold q-my-xs">
            +(1200)989-081
          </h1>
        </div>
      </div>

      <div
        class="bg-deep-purple-1 text-center q-py-md q-py-sm-sm q-py-md-md text-caption text-grey-8"
      >
        2021 Copyright &copy; oentity. All Rghts Reserved.
      </div>
    </div>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "MainLayout",

  components: {},

  setup() {
    return {};
  },
});
</script>
