
{
  "name" : "List-item",
  "type" : "Component"
  "category": “Layout”
  "version" : "1.0.0",
  "averageRating" : 1,
  "description" : " List item component are the data of a list it will be inserted inside a list-component and can be displayed, ",
  "platformSupportVersion" : "4.0.0",
  "publisher" : "Ayush"

}



## Guide:
### Overview:
List-items component contains individual data of items that will be placed inside the list-component.The data can be stored in an array or object and it will be accessed  from the array by *ngFor attribute.
##### Usage:
List items are used to store the items or data of a list.The data can be string, a number, a images etc. A list items can only be used inside a list component.

##### How to use
Drag and drop a list-items inside a list component, and set the attribute such as style and class, *ngFor and label.

##### Example
**Display a list of three items-**

- Drag and drop a list-component and set the attribute such as style and class.
-  Drag and drop  list-item component inside the list-component. And for the list-items set the attribute such as style, class, *ngFor and label.
-  *ngFor is used to iterate through the object and access the items of the objects, so if folders is a object which has attribute as name(name of folder) which is a string, and there are three items in the folder object, and this object will be defined in .ts file. So set the field in ngFor as (let folder of folders).
- Label attribute give the name which will be displayed as a list items, so provide the name as (folder .name), this will access the folders object and get the name value from that. So if the folders object contains three values such as photos, work and document, then the list will be generated which contains the list items as photos, work and document.
- Save and run, a list will three items will be displayed.
 

### Associated Attributes:
**Style-** Accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element. An inline CSS uses the style attribute of an HTML element.
(eg. color:blue).

**Class-** it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=toolbar).

***ngFor-** ngFor is used to iterate through the array object and get the data. The syntax of ngFor is *ngFor="let d of data" where d is a loop variable and data is a array or object from which the data will be accessed. 

***Label-** in label attribute provide the name that should be displayed as a items name so the data is accessed by the object then give the value as (folder. name).




### Support 
- **Devices:** Android, iOS
- **Browsers**:  Latest version of all modern browsers
- **Dependencies version:** 
 Angular CLI version: 5.0.0 + 
 Cordova version: 7.1.0 +







