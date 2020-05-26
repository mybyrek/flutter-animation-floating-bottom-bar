# Flutter animation challenge 8 - Floating bottom bar
> Creator: Qani Ajdini

## About
The component is using Animations, Clip Path, Transform and Stream's proprieties.

### The Constructor Data Fields
````dart
final Color background; //Background of buttons and navbar
final Color defaultIconColor; //Default icon color when not actived
final Color activatedIconColor; //Color of icon when actived
final Function(int i) onTapButton; //Function when button has clicked
final Function(int i) onTapButtonHidden; //Fuction when hidden button has clicked
final List<IconData> buttonsIcons; //Icons to button
final List<IconData> buttonsHiddenIcons; //Icons to hidden buttons
final Color backgroundColorMiddleIcon; //Background of middle button
````
    
## Design

![App Running](./docs/inspiration.gif)

## Implementation

![App Running](./docs/app_running.gif)

#### Notes
For now, it's working with four buttons and equals hidden buttons length.
