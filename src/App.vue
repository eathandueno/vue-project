<template>
  <div id="app">
    <HeaderComponent />
    <NavigationComponent />
    <div class="content">
      <MainContentComponent />
      <SidebarComponent />
    </div>
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import NavigationComponent from './components/NavigationComponent.vue';
import MainContentComponent from './components/MainContentComponent.vue';
import SidebarComponent from './components/SidebarComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    NavigationComponent,
    MainContentComponent,
    SidebarComponent
  }
};
</script>

<style>
/* Global styles */
.content {
  display: flex;
  justify-content: space-between;
}
</style>
