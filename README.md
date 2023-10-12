# Persian Date Range Picker
## Persian Date Picker
### Range Picker
![N|Solid](https://user-images.githubusercontent.com/49247720/273688633-51494a5e-35ea-4774-a84d-ff3caf01af62.png)

![Build Status](https://user-images.githubusercontent.com/49247720/273688671-c8825f07-060a-4cf8-9d57-ac70ab6adb07.png)

### Single Date Picker

![Build Status](https://user-images.githubusercontent.com/49247720/273688710-c41eaf80-e309-4bed-8609-a96cd8c54277.png)
## Introduction
Date range picker - lightweight
### Built With
* jQuery 
* Jalali moment
## Getting Started

To start this project, you only need to do one step.

### Prerequisites
Download daterangepicker and include it in your project with jQuery and Jalali Moment. 

### Installation

```html
<link rel="stylesheet" type="text/css" href="dateragepicker.css" />
<script type="text/javascript" src="jquery.js"></script>
<script src="jalali-moment.js"></script>
<script src="dateragepicker.js"></script>
```
### Usage
```javascript
const Jmoment = moment().locale('fa');
    $('#daterangepicker').daterangepicker({
        autoApply: true,
        alwaysShowCalendars: true,
        minDate: new Date(),
        persian: {
            enable: true,
            persianDigits: true,
        },
        locale: {
            direction: 'rtl',
            firstDay: 0,
            format: 'jYYYY-jMM-jDD',
            applyLabel: 'اعمال',
            cancelLabel: 'لغو',
            monthNames: [
                "فروردین",
                "اردیبهشت",
                "خرداد",
                "تیر",
                "مرداد",
                "شهریور",
                "مهر",
                "آبان",
                "آذر",
                "دی",
                "بهمن",
                "اسفند"
            ],
            daysOfWeek: [
                'ش',
                'ی',
                'د',
                'س',
                'چ',
                'پ',
                'ج',
            ],
        }
    });
```
To create a Persian date range picker, you can use the "settings" object as follows:

```javascript
 persian: {
            enable: true,
            persianDigits: true,
        },
```
In this object, the two properties serve the following purposes:
enable: Used to enable the Persian localization feature.
persianDigits: Used to convert English digits to Persian.

#### This is a modified version of https://www.daterangepicker.com/
So you can read the complete documentation at this address.

### Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
