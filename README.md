Most developers are familiar with CSS floats and clearfix hacks to get proper multi-column layouts. These are still in use today because they work and have great support among a variety of browsers. However, in 2009 a new display style named flex appeared on the map.

Since then flex has undergone a few changes to reach its current iteration. The flex value is an alternative to block elements floated and manipulated using media queries.

Instead, developers can build a flexible container, flexbox for short. It’s great for mobile screens and responsive content for dynamic layouts and webapps. This guide will cover the fundamentals of CSS flexbox usage and some helpful resources for digging deeper into the topic.

What is Flexible Box?
The flexible box layout is a way of using CSS’s display property in a whole new manner. Block elements stack vertically while inline elements stack horizontally(until they break onto a new line).

Flexbox elements can stack vertically or horizontally based on your setup. They can be evenly spaced across the page or squeezed tight up against each other. The point is offering more control to developers who want to build naturally responsive layouts.

Any element referenced as a flexbox is a container element. This container holds internal elements known as flexbox items. I recommend skimming the first part of this Mozilla Dev Network article for details.

The display: flex container may have a fixed or fluid width, but it makes sense to leave it fluid, so the content adapts with the page. The internal elements are not given specific width values but instead display based on proportions.

The above video does an excellent job of explaining the details. In short, you use a CSS property named flex to define a ratio between boxes (mostly HTML div elements). flex: 1 represents a 1:1 ratio where each internal flex item displays at the same width regardless of screen resolution.

The Keys to a Flexbox Layout
Naturally, the first important part of a flexbox is the container itself. This container is given display:flex so its children behave in an expected manner.

Items inside the flexbox can flow vertically or horizontally by using the flex-direction property. This takes a value of either row or column with reverse options as well. Note this property is applied to the parent, not the children.

Another important property is justify-content which also applies directly to the parent. This defines how space behaves when internal elements don’t fill the container. Flexbox elements can be centered, aligned left/right, or spaced evenly as appropriate. Check out the Codrops reference for more info.
