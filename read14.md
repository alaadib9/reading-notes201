The transition property is a shorthand property used to represent up to four transition-related longhand properties
These transition properties allow elements to change values over a specified duration, animating the property changes, rather than having them occur immediately. 

The transition-property property, normally used as part of transition shorthand, is used to define what property, or properties, you want to apply a transition effect to.

This is done by providing the name of the property as the value
The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms)
The value can be one of the following:

1) A single property name
2) A comma-separated list of property names (shorthand or longhand), for transitioning multiple properties on a single element
3) The keyword none, which indicates that no property will transition
4) The keyword all, which indicates that all properties will transition (the default)

Animations in CSS3 allow multiple keyframes to change the appearance and behavior of an element. Transitions include a shift from one state to another, while animations can set different keyframes for multiple transition points.