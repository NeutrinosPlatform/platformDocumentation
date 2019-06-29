# progress-bar

## Overview

Horizontal progress-bar is used for indicating progress and activity. It is used to indicate the progress of the work that has been completed.

## Usage

Progress bar is a graphical control element used to visualize the progression of an extended computer operation, such as file download, file transfer, or installation.

### How to use

1. Drag and drop the component. 
2. Double click the component to display the list of attributes that can be used with it.
3. Fill the attributes which are needed and save the page.

### Example

1. Input the component field\(s\) with the attribute value\(s\):  

    `value = 55`  

    `mode = determinate`

2. Save it and run.
3. When the page is loaded the "value = 55" will be the percentage of work completed and it will be displayed in the progress bar. "mode = determinate" is the mode in which the progress bar is displayed \(by default the mode will be determinate\).

## Associated Attributes:

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

* **Mode:** Is used to select the mode. Must take one of the following values: determinate, indeterminate, buffer, query. Defaults to 'determinate'. 
* **Color:** Takes the color based on the angular material theme.
* **Value:** Value of the progress bar. Defaults to zero. Input value should be a number.
* **Buffervalue:** Specifies buffer value of the progress bar. Defaults to zero. Input value should be a number.

## Support

* **Devices:** Android, iOS
* **Browsers:**  Latest version of all modern browsers
* **Dependencies version:** 
  * Angular CLI version: 6.0.0 + 
  * Cordova version: 7.1.0 +

