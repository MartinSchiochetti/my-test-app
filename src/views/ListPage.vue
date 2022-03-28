
<template>
 
  <ion-page>  
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button color="primary"></ion-menu-button>
        </ion-buttons>
        <ion-title>Lista</ion-title>
      </ion-toolbar>
    </ion-header>    
    <ion-content :fullscreen="true">
      <!-- Conteudo aqui -->
      <ion-button color="primary">Register</ion-button>
     <ion-button color="secondary">Login</ion-button>
      <ion-button expand="block">Block Button</ion-button>

      <ion-list>
        <ion-list-header> Recent Conversations </ion-list-header>
        <ion-item>
          <ion-avatar slot="start">
            <img src="../assets/avatar-finn.png" />
          </ion-avatar>
          <ion-label>
            <h2>Finn</h2>
            <h3>I'm a big deal</h3>
            <p>Listen, I've had a pretty messed up day...</p>
          </ion-label>
        </ion-item>
       
        <ion-item>
          <ion-avatar slot="start">
            <img src="../assets/avatar-han.png" />
          </ion-avatar>
          <ion-label>
            <h2>Han</h2>
            <h3>Look, kid...</h3>
            <p>I've got enough on my plate as it is, and I...</p>
          </ion-label>
        </ion-item>  

                <ion-item>
          <ion-avatar slot="start">
            <img src="../assets/avatar-yoda.png" />
          </ion-avatar>
          <ion-label>
            <h2>Yoda</h2>
            <h3>Size matters not</h3>
            <p>Do or do not. There is no try....</p>
          </ion-label>
        </ion-item> 
       
</ion-list>
    </ion-content>      
   
 
  </ion-page>

</template>

<script>
import {
  IonPage,
  IonHeader,
  IonToolbar,
  IonButtons,
  IonMenuButton,
  IonTitle,
  IonContent,
  
  IonButton,
  IonList,
  IonListHeader,
  IonItem,
  IonAvatar,
  IonLabel,
  

} from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: {
    IonPage,
    IonHeader,
    IonToolbar,
    IonButtons,
    IonMenuButton,
    IonTitle,    
    IonContent,

    IonButton,
    IonList,
    IonListHeader,
    IonItem,
    IonAvatar,
    IonLabel,


   
  }
});
</script>