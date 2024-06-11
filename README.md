
# Time Slot Picker - jQuery Plugin

This will add a beautiful embedded time picker to your website. 

## Overview 

Time Slot Picker is a versatile and user-friendly jQuery plugin designed to facilitate the selection of time slots within web applications. Whether you're building a booking system, a reservation platform, or any application requiring precise time slot selection, this plugin provides a seamless and intuitive solution.


## Installation 

Install time-slot-picker with npm

```bash 
  npm i @randika-srimal/time-slot-picker
```
    
## Usage/Examples

```html
<div id="time-slot-picker"></div>
```
```javascript
$('#time-slot-picker').timeSlotPicker(
    {
        startTime:'00:00',
        endTime:'24:00',
        timeStep:'15',
        defaultDate:'2021-05-31',
        maxDateTime:'2021-06-01 13:15',
        minDateTime:'2021-05-28 10:15',
        minDayTime:'09:00',
        maxDayTime:'18:00',
        inputElementSelector:'#time-slot-input'
    }
);
```
These passing options are all optional.

When a time slot selected it will trigger a `timeSlotSelected` event and when discarded it will trigger `timeSlotDiscarded` events. You can catch these to run your methods.

```javascript
$('#time-slot-input').on('timeSlotSelected',function(){
  // Your functions
});

$('#time-slot-input').on('timeSlotDiscarded',function(){
    // Your functions
});
```
  
## Screenshots

![Plugin Screenshot](https://user-images.githubusercontent.com/7983447/120070508-83034380-c0a8-11eb-8883-9ad530c151bb.png)

  
## License

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/)

## Acknowledgements

Special thanks to the jQuery community and all the contributors who helped make this project possible.
 
## Support

For support, email email2randika@gmail.com.

  
