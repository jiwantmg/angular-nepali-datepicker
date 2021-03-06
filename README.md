# Angular Nepali Datepicker
Simple Nepali datepicker component for angular application

## Installation
```bash
npm install angular-nepali-datepicker
```

## Demo
https://sprajwal078.github.io/angular-nepali-datepicker/

## Note
This package uses [@angular/cdk](https://www.npmjs.com/package/@angular/cdk) and
[nepali-date](https://www.npmjs.com/package/nepali-date)

## Usage
Import the NpDatepickerModule in your **app.module.ts**

```js
import { NpDatepickerModule } from 'angular-nepali-datepicker';

@NgModule({
  declarations: [
    AppComponent,
  ],
  imports: [
    BrowserModule,
    NpDatepickerModule
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }

```

then use `<np-datepicker></np-datepicker>` in your template

```html
<np-datepicker ([ngModel])="date"></np-datepicker>
```

### Format
The supported date format is `dd-mm-yyyy`


## Todo
- Support other date formats
- Create specs

