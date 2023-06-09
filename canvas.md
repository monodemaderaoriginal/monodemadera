A website is composed of pages that respectively are composed of functional components (e.g. text, navigation bar, menu, list) that inherently have visual functionality. This composition as whole makes up a user interface. In this context a canvas represents a surface in which visual components can be arranged to make up a composition. The composition that the canvas represents can be one of two. The first one is a website’s page or a website’s single component. These two representations can be thought of as two working modes or working contexts.

The surface of the canvas and child elements  (visual components) are implemented by means of HTML elements. The canvas’s HTML element is specifically implemented through a HTMLDivElement. The origin of the canvas is the native origin of its HTML element.

Each canvas component possesses a state composed of spatial and styling properties, both implemented by the HTMLElement element’s style member’s properties (CSS state). Spatial properties are x,y (left, right CSS properties) representing the element’s position in the canvas’s x-y plane, and width, height. Style properties represent all styling CSS properties but the ones used to implement spatial properties. 

A website component can either be nested or simple, whether they have or not children respectively. Simple components can be implemented through any native HTML element. Nested components are composed by any HTML root element and any composition of nested or simple website components.

The canvas must support CRUD operations regarding the canvas's children. At component level the canvas supports spatial transformations such as translation, rotation, scaling and resizing. These transformations are implemented through changes in the CSS state.
