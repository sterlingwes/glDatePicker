## glDatePicker for Meteor

Meteor implementation of [glDatePicker](https://github.com/glad/glDatePicker) for jQuery.

## Usage

Install via [Meteorite](https://github.com/oortcloud/meteorite): 

` mrt add glDatePicker `

Add to your template's rendered function:

``` 
Template.[Template Name].rendered = function() {
  $(".datepicker").glDatePicker(); 
}
```