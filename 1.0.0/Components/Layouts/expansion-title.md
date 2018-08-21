## Overview 
The expansion-title component is used to display the title for the expansion panel components. It can be used inside the Expansion Panel Header component or it can be used individually to display the title.
## Usage
Expansion-title component is used to display title for the expansion panel content. Only the title will be displayed, and the other components will be displayed after clicking the title.
### How to use  
1. Drag and drop the expansion panel component. 
2. Inside the expansion panel component, drag and drop the expansion header component. And inside expansion-header component drag and drop the expansion-title component.
3. Double click the expansion-title component to display the list of attributes that can be used with it.
4. Fill the attributes which are needed and save the page.

### Example 
1. Input the component field with the attribute value:
``` 
title = this is expansion panel title
```
2. Save it and run.
3. When the page is loaded the attribute value "title = this is expansion panel title" will be displayed. And when the title is clicked, the expansion-header panel will be extended.

## Associated Attributes 
- **Style:** It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).
- **Class:** "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space separated class names (eg. class1 class2) which are defined in the "Style" tab as shown below.
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
- **title:** Specifies the title that is to be displayed when the page is loaded. 
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
- Angular CLI version: 5.0.0 + 
- Cordova version: 7.1.0 + 
