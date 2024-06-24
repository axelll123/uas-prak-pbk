<template>
  <q-layout view="hHh lpR fFf">
    <q-header elevated>
      <q-toolbar class="custom-toolbar">
        <q-btn-dropdown class="custom-dropdown" label="Sulthon88" dropdown-icon="^">
          <q-list class="nav-list">
            <q-item clickable v-close-popup>
              <router-link to="/">
                <q-item-section>
                  <q-item-label style="color: var(--cyberpunk-text);">Cuaca</q-item-label>
                </q-item-section>
              </router-link>
            </q-item>
            <q-item clickable v-close-popup>
              <router-link to="/tugas1">
                <q-item-section>
                  <q-item-label style="color: var(--cyberpunk-text);">Tugas 1</q-item-label>
                </q-item-section>
              </router-link>
            </q-item>
            <q-item clickable v-close-popup>
              <router-link to="/tugas2">
                <q-item-section>
                  <q-item-label style="color: var(--cyberpunk-text);">Tugas 2</q-item-label>
                </q-item-section>
              </router-link>
            </q-item>
            <q-item clickable v-close-popup>
              <router-link to="/tugas3">
                <q-item-section>
                  <q-item-label style="color: var(--cyberpunk-text);">Tugas 3</q-item-label>
                </q-item-section>
              </router-link>
            </q-item>
            <q-item clickable v-close-popup>
              <router-link to="/tugas4">
                <q-item-section>
                  <q-item-label style="color: var(--cyberpunk-text);">Tugas 4</q-item-label>
                </q-item-section>
              </router-link>
            </q-item>
            <q-item clickable v-close-popup>
              <router-link to="/tugas5">
                <q-item-section>
                  <q-item-label style="color: var(--cyberpunk-text);">Tugas 5</q-item-label>
                </q-item-section>
              </router-link>
            </q-item>
            <q-item clickable v-close-popup>
              <router-link to="/tugas6">
                <q-item-section>
                  <q-item-label style="color: var(--cyberpunk-text);">Tugas 6</q-item-label>
                </q-item-section>
              </router-link>
            </q-item>
            <q-item clickable v-close-popup>
              <router-link to="/tugas7">
                <q-item-section>
                  <q-item-label style="color: var(--cyberpunk-text);">Tugas 7</q-item-label>
                </q-item-section>
              </router-link>
            </q-item>
          </q-list>
        </q-btn-dropdown>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view></router-view>
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  setup() {

  },
};
</script>

<style>
@import './assets/index.css';

:root {
  --cyberpunk-bg: #0f0f0f;
  --cyberpunk-border: #ff00ff;
  --cyberpunk-text: #00ffff;
  --cyberpunk-input-bg: #1a1a1a;
  --cyberpunk-input-border: #ff00ff;
  --cyberpunk-button-bg: #1a1a1a;
  --cyberpunk-button-hover-bg: #ff00ff;
}

.custom-toolbar {
  background-color: var(--cyberpunk-bg);
  color: var(--cyberpunk-text);
  border-bottom: 1px dotted var(--cyberpunk-border);
  padding: 15px !important;
}

.custom-dropdown {
  background-color: var(--cyberpunk-button-bg);
  color: var(--cyberpunk-text);
  border: 1px dotted var(--cyberpunk-border) !important;
}

.nav-list {
  background-color: var(--cyberpunk-bg);
  color: var(--cyberpunk-text);
  border: 1px dotted var(--cyberpunk-border);
}

.nav-list .q-item link {
  text-decoration: none;
}

.q-item-section {
  color: var(--cyberpunk-text) !important;
}

.q-item-label {
  color: var(--cyberpunk-text);
}
</style>
