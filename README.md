# ParkIT
The Number One Parking Application in Ireland!
<ion-header>
  <ion-toolbar color="primary">
    <ion-searchbar (input)="getItems($event)"></ion-searchbar>
  </ion-toolbar>
</ion-header>

<ion-content>
  <ion-list>
    <ion-item *ngFor="let item of items">
      {{ item }}
    </ion-item>
  </ion-list>
</ion-content>
