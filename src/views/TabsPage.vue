<template>
    <ion-page>
      <ion-tabs>
        <ion-router-outlet></ion-router-outlet>
        <ion-tab-bar slot="bottom">
          <ion-tab-button tab="home" href="/tabs/home">
            <ion-icon src="assets/icon/home.svg"/>
          </ion-tab-button>
            
          <ion-tab-button tab="PageSecond" href="/tabs/page2">
            <ion-icon src="assets/icon/Rectangle 58.svg"/>
          </ion-tab-button>
        </ion-tab-bar>
      </ion-tabs>
    </ion-page>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  import { IonTabBar, IonTabButton, IonTabs, IonIcon, IonPage, IonRouterOutlet } from '@ionic/vue';
  
  export default defineComponent({
    name: 'TabsPage',
    components: {IonTabs, IonTabBar, IonTabButton, IonIcon, IonPage, IonRouterOutlet },
    setup() {
      return {
        
      }
    }
  });
  </script>
  