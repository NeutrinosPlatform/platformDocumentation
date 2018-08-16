{
"name" : "raised-button",
"type" : "Component"
"category": “Form Controls”
"version" : "1.0.0",
"averageRating" : 1,
"description" : "Rectangular contained button which appears elevated",
"guide" : "”,
"platformSupportVersion" : "4.0.0",
"publisher" : "Prashanth",
}

## Guide: 
### Overview: 
The raisedbutton component represents a clickable button. The button appears raised compared to a normal button component.

#### Usage
Raised button provides the user a simple way to trigger an event, like searching for a query at a search engine, or to interact with dialog boxes, like confirming an action. It can be used to represent that the button is important.

#### How to use:   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

#### Example: 
Input the component field with the attribute value:
``` 
buttonname = submit
Click = true
```
Save it and run.
When the page is loaded the value "buttonname = submit" will be name of the button that will be displayed on the button. And "click = true" is the event that check when the button is pressed.

### Associated Attributes:
- **style:** Used to specify the inline style.
- **class:** it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.
- **Buttonname:** specifies the button name that is to be displayed on the screen.
- **Color:** takes the color based on angular material thing.
- **Click:** Is an event that checks when the button is clicked. The value should be boolean i.e. either true or false.

### Support 
- **Devices:** Android, iOS
- **Browsers:** Latest version of all modern browsers

**Dependencies version:**
- **Angular CLI version:** 5.0.0 + 
- **Cordova version:** 7.1.0 +

