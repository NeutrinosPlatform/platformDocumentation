# slider

## Overview

Slider component allows for the selection of a value from a range via mouse, touch, or keyboard. By default the minimum value of the slider is 0, the maximum value is 100, and the slider moves in increments of 1. These values can be changed by setting the min, max, and step attributes respectively. The initial value is set to the minimum value unless specified.

## Usage

Slider component is used to select a range of values through mouse, touch or keyboard. Sliders reflect a range of values along a bar, from which users may select a single value. They are ideal for adjusting settings such as volume, brightness, or applying image filters.

### How to use

1. Drag and drop the component. 
2. Double click the component to display the list of attributes that can be used with it.
3. Fill the attributes which are needed and save the page.

### Example

1. Input the component field\(s\) with the attribute value\(s\): 

    `invert = true` 

    `step = 50`

2. Save it and run.
3. When the page is loaded the value "invert = true" will display an inverted slider and "step=50" specifies the step increment value of the slider. In this example, the slider takes two clicks to move to the end of the slider. 

## Associated Attributes

* **Style:** It accepts a string value and affects the different properties \(height, width, color etc.\) of the component based on the values provided \(eg. background:orange;height:200px;\).
* **Class:** "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space separated class names \(eg. class1 class2\) which are defined in the "Style" tab as shown below.

  ```css
    .class1 {
        border-radius:10px;
        flex-basis:10%;
        height:100px;
    }
    .class2 {
        border-radius:10px;
        flex-basis:10%;
        height:100px;
    }
  ```

* **Ngmodel:** Used for two-way data binding. The ng-model attribute is used to bind the data in your model to the view presented to the user.
* **Color:** Takes the color based on the angular material theme.
* **Invert:** Used to check whether the slider is inverted. Value has to be boolean i.e. either true or false. Example:- invert: false.
* **Max:** Specifies the maximum value that the slider can have. The value should be a number. Example:- max: 10.
* **Min:** Specifies the minimum value that the slider can have. The value should be a number. Example:- min: 0.
* **Step:** Specifies the values at which the slider will slide. The value should be a number. Example:- step: 1.
* **Thumb-label:** Specifies whether or not to show the thumb label. Value should be a boolean i.e. either true or false. Example:- thumbLabel: boolean.
* **Vertical:** Specifies whether the slider is vertical or not. Value has to be boolean i.e. either true or false. Example:- vertical: false.
* **Disabled:** Specifies whether the component is disabled or not. Value has to be boolean i.e. either true or false. Example:- disabled: false.
* **Value:** Specifies the value of the slider. The value should be either number or null. Example:- value: number \| null.
* **Change:** It is an event emitted when the slider value is changed.
* **Input:** It is an event emitted when the slider thumb moves.

## Support

* **Devices:** Android, iOS
* **Browsers:**  Latest version of all modern browsers
* **Dependencies version:** 
  * Angular CLI version: 6.0.0 + 
  * Cordova version: 7.1.0 +

