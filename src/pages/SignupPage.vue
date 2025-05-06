<template>
  <q-page padding class="flex flex-center">
    <div class="full-width" style="max-width: 300px">
      <h5 class="q-my-md">Signup</h5>
      <q-card>
        <q-card-section>
          <q-input
            class="q-mb-md"
            filled
            label="Full Name"
            placeholder="Full Name"
            name="full_name"
          ></q-input>
          <q-input
            class="q-mb-md"
            filled
            label="Email"
            placeholder="email@example.com"
            name="email"
          ></q-input>
          <q-input
            class="q-mb-md"
            filled
            type="password"
            label="Password"
            name="password"
          ></q-input>
          <q-input
            class="q-mb-md"
            filled
            type="password"
            label="Confirm Password"
            name="confirm_password"
          ></q-input>
          <q-btn color="primary" class="q-mdb-sm full-width" label="Signup"></q-btn>
        </q-card-section>
      </q-card>
    </div>
  </q-page>
</template>

<script setup>
//
</script>
