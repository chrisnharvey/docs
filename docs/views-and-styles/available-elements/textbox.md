# TextBox

The TextBox element renders a simple text box which can be used for a
single line of text.

## GIML Markup

```xml
<TextBox onEnter="setName" id="name" />
```

## Available Styles
Style|Values|Use
-----|-----|----
processEnter|Boolean|To process enter

## Available Events
Event | Use
----- | ----
onEnter | Called when the return/enter key is pressed from within the TextBox

## Available Methods
Method | Arguments | Use
------ | --------- | ---
getValue() | None | Returns the TextBox value as a string