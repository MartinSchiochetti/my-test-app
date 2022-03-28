
<template>
 
  <ion-page>  
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button color="primary"></ion-menu-button>
        </ion-buttons>
        <ion-title>Formulario</ion-title>
      </ion-toolbar>
    </ion-header>    
    <ion-content :fullscreen="true">
      <!-- Conteudo aqui -->

      
      
      <ion-list lines="full" class="ion-no-margin">
        <ion-list-header lines="full">
          <ion-label> Formulário </ion-label>
        </ion-list-header>

        <!-- Input with placeholder -->
  <ion-input placeholder="Enter Input"></ion-input>

        <!-- Number type input -->
  <ion-input type="number" value="333"></ion-input>
        
        <ion-item>
    <ion-label position="floating">Floating Label</ion-label>
    <ion-input></ion-input>
  </ion-item>

        <ion-item>
    <ion-label position="floating">Floating Label</ion-label>
    <ion-input></ion-input>
  </ion-item>

        <ion-item>
    <ion-label position="floating">Floating Label</ion-label>
    <ion-input></ion-input>
  </ion-item>


</ion-list>


<section>
        <ion-button expand="block" color="primary">Salvar</ion-button>
</section>
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
  IonLabel,
  IonInput,

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
    IonLabel,
    IonInput,

   
  }
});
</script>