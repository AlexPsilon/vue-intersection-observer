# vue-intersection-observer

---

## Installation

`npm install vue-intersection-observer`

or

`yarn install vue-intersection-observer`

## Properties

|  Property  | Reqiured |            Type             |             Default              | Description                                                                                                                                                                                                                                        |
| :--------: | :------: | :-------------------------: | :------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  observed  |    No    |         `{Boolean}`         |               true               | Enabled/Disabled observation                                                                                                                                                                                                                       |
|    root    |    No    | `{HTMLElement|String|Null}` |               null               | The element that is used as the viewport for checking visiblity of the target. Must be the ancestor of the target. Defaults to the browser viewport if not specified or if null.                                                                   |
| rootMargin |    No    |         `{String}`          | '0px&nbsp;0px&nbsp;0px&nbsp;0px' | Margin around the root. Can have values similar to the CSS margin property, e.g. "10px 20px 30px 40px" (top, right, bottom, left).                                                                                                                 |
| threshold  |    No    |      `{Number|Array}`       |                0                 | Either a single number or an array of numbers which indicate at what percentage of the target's visibility the observer's callback should be executed. If you only want to detect when visibility passes the 50% mark, you can use a value of 0.5. |

[Intersection observer options](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API#Intersection_observer_options)

## Events
