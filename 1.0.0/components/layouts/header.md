# header

## Overview

A header element typically contains, one or more heading elements \(h1 - h6\), logo or icon, authorship information. There can be several header component in one document.

## Usage

A header components is used when the content should be displayed with some special properties such as bigger font size, or when the text should be in bold. Various components can be inserted inside a header component. It has two attributes style and class.

### How to use

1. Drag and drop a header component.
2. Fill the attribute such as style and class. 
3. Components such as as h1-h6 component, paragraph component etc., can be added.

### Example

**Display a header component with title a subtitle in and a paragraph component** 1. Drag and drop a header component, and provide the style and class attribute. 2. Now drag and drop a h3 component inside header for a title and provide the text such as Agra. So the title will be set as Agra. 3. After setting the title, drag and drop a h5 component inside header below h3 component to set a subtitle because subtitle should be smaller than title, and provide the subtitle as Taj Mahal. 4. Now drag and drop a paragraph component inside the header component below the h5 component, and provide some text as content that will be displayed below subtitle. 5. Save and Run. 6. A block with title Taj in h3,a subtitle with Agra in h5 and a paragraph will be displayed.

## Associated Attributes

* **Style:** It accepts a string value and affects the different properties \(height, width, color etc.\) of the component based on the values provided \(eg. background:orange;height:200px;\).
* **Class:** "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space separated class names \(eg. class1, class2\) which are defined in the "Style" tab as shown below.

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

  **Support**

* **Devices:** Android, iOS
* **Browsers:**  Latest version of all modern browsers
* **Dependencies version:** 
  * Angular CLI version: 6.0.0 + 
  * Cordova version: 7.1.0 + 

