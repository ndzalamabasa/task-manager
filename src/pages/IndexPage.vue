<template>
  <div class="column">
    <div class="row">
      <q-btn  label="New Task" class="q-my-md q-mx-lg" />
    </div>
    <div >
      <h2 class="text-center">Tasks</h2>
      <div class="q-pa-md">
    <q-list>
      <q-item>
        <q-item-section>
          <q-item-label>Single line item</q-item-label>
          <q-item-label caption lines="2">Secondary line text. Lorem ipsum dolor sit amet, consectetur adipiscit elit.</q-item-label>
        </q-item-section>

        <q-item-section side top>
          <q-item-label caption>5 min left</q-item-label>
          <div class="row text-h6">
            <q-icon name="check" color="blue" />
            <q-icon name="delete" color="red" />
          </div>
        </q-item-section>
      </q-item>

      <q-separator spaced inset />
      
      <q-item>
        <q-item-section>
          <q-item-label>Single line item</q-item-label>
          <q-item-label caption lines="2">Secondary line text. Lorem ipsum dolor sit amet, consectetur adipiscit elit.</q-item-label>
        </q-item-section>

        <q-item-section side top>
          <q-item-label caption>5 min left</q-item-label>
          <div class="row text-h6">
            <q-icon name="check" color="blue" />
            <q-icon name="delete" color="red" />
          </div>
        </q-item-section>
      </q-item>
    </q-list>
  </div>
    </div>
  </div>
</template>

<script></script>
