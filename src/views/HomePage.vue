<template>
  <ion-grid>
    <h1>Home</h1>
    <ion-row>
      <ion-col>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Kolam</ion-card-title>
            <ion-card-subtitle>10</ion-card-subtitle>
          </ion-card-header>
        </ion-card>
      </ion-col>
      <ion-col>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Kolam Aktif</ion-card-title>
            <ion-card-subtitle>8</ion-card-subtitle>
          </ion-card-header>
        </ion-card>
      </ion-col>
    </ion-row>

    <ion-row>
      <ion-col>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Ikan Hidup</ion-card-title>
            <ion-card-subtitle>182 Ekor</ion-card-subtitle>
          </ion-card-header>
        </ion-card>
      </ion-col>
      <ion-col>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Ikan Mati</ion-card-title>
            <ion-card-subtitle>89 Ekor</ion-card-subtitle>
          </ion-card-header>
        </ion-card>
      </ion-col>
    </ion-row>

    <ion-row>
      <ion-col>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Panen 2022</ion-card-title>
            <ion-card-subtitle>109 Kg</ion-card-subtitle>
          </ion-card-header>
        </ion-card>
      </ion-col>
      <ion-col>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Total Pakan</ion-card-title>
            <ion-card-subtitle>223 Kg</ion-card-subtitle>
          </ion-card-header>
        </ion-card>
      </ion-col>
    </ion-row>

    <h1>TOTAL BERAT IKAN</h1>

    <ion-row>
      <h1>
        <ion-card>
          <center>
            <img alt="Silhouette of mountains"
              src="https://3.bp.blogspot.com/-qHuwey5YV_o/W8oAvWVFBhI/AAAAAAAABKI/SG12_1Mnih87wmOYMn7T4gWum1w3o0fxQCLcBGAs/s320/lele%2Bcopy.png" />
          </center>
          <ion-card-header>
            <head-title>Lele</head-title>
            <ion-card-title>
              <blue>200kg</blue>
            </ion-card-title>
          </ion-card-header>
        </ion-card>
      </h1>

      <h1>
        <ion-card>
          <center>
            <img alt="Silhouette of mountains" src="https://th.bing.com/th/id/R.464fd11605d9e2919a66b6f9ac7bdc94?rik=rHcttTZ%2biUSWXg&riu=http%3a%2f%2fwww.pngmart.com%2ffiles%2f5%2fKingfish-Transparent-PNG.png&ehk=eWDPfcyjxrJRvWiMKC9YYazYreAGi4MjRYoHq7SviQk%3d&risl=&pid=ImgRaw&r=0" />
          </center>

          <ion-card-header>
            <head-title>Nila Merah</head-title>
            <ion-card-title>
              <blue>200kg</blue>
            </ion-card-title>
          </ion-card-header>
        </ion-card>
      </h1>
    </ion-row>

    <h1>KUALITAS AIR</h1>

    <ion-row>
      <h1>
        <ion-card>
          <ion-card-header>
            <h2>pH</h2>
            <br>
            <subtitle>Normal <blue>6 Kolam</blue>
            </subtitle><br>
            <subtitle>Abnormal <blue>6 Kolam</blue>
            </subtitle>
          </ion-card-header>
        </ion-card>
      </h1>

      <h1>
        <ion-card>
          <ion-card-header>
            <h2>DO</h2>
            <br>
            <subtitle>Normal <blue> 6 Kolam</blue>
            </subtitle><br>
            <subtitle>Abnormal <blue> 6 Kolam</blue>
            </subtitle>
          </ion-card-header>
        </ion-card>
      </h1>
    </ion-row>
  </ion-grid>
</template>

<script lang="ts">
import { IonCol, IonGrid, IonRow } from '@ionic/vue';
import { IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomePage',
  components: { IonCol, IonGrid, IonRow, IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle },
});
</script>

<style scoped>
body {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-color: white;
}

h1 {
  font-size: 20px;
  font-weight: 600;
  margin-left: 10px;
}

ion-card-title {
  font-size: 15px;
  color: black;

}

ion-card-subtitle {
  font-size: 25px;
  font-weight: 600;
  text-transform: capitalize;
  color: black;
}

subtitle {
  font-size: 15px;
  font-weight: 600;
  text-transform: capitalize;
  color: black;
}

ion-card {
  background-color: aliceblue;
  padding: 0;
  margin: 2px;

}

img {
  margin: auto;
  padding: 10px;
  height: 150px;
  width: 180px;
}

h2 {
  font-size: 30px;
  color: black;
  margin: 0;
  font-weight: 600;
}

blue {
  color: #2C96F1;
}

head-title {
  margin-top: 0;
  font-size: 25px;
  color: black;
}
</style>
