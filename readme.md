# Angular Leaflet

#### 1. Installing Leaflet
```
npm install leaflet@1.7.1
```
#### 2. Import Leaflet
```
import { Component, OnInit } from '@angular/core';
import * as L from 'leaflet';

@Component({
  selector: 'app-map',
  templateUrl: './map.component.html',
  styleUrls: ['./map.component.css']
})
export class MapComponent implements OnInit {
  constructor() { }

  ngOnInit(): void { }
}
```

#### 2. Add leaflet.css
```
 "styles": [
    "./node_modules/leaflet/dist/leaflet.css",
    "src/styles.css"
 ],
 
```
Reference link: [DigitalOcean][1]

[1]: https://www.digitalocean.com/community/tutorials/angular-angular-and-leaflet
