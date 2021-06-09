# CSS Repository 🖼️🖌️📸

## CSS Selectors 🖋️

### Selectors 🔵

```css
selectorA {
   property1: value1;
   property2: value2;
}

selector:pseudo-class::pseudo-element {
    -vendor-property: value;
}

selector[attribute],
selector ~ relation {
    property: -vendor-value;
    -vendor-property: -vendor-value;
    -vendor-property: weirdsyntax;
}
```
### Basic Selectors 🔵

```html
<ul>
   <li id="myID" class="myClass">item 1</li>
   <li class="myClass">item 2</li>
   <li>item 3</li>
</ul>
```
**#myID** *ID*

**.myClass** *class*

**li** *tag name*

## Selectors in CSS 🖋️

### CSS Level 1 🔵
```css
E
E F
.class
#ID
:link
:active
```
### CSS Level 2 🔵
```css
*
E > F 
E + F
E[attribute]
E[attribute=value]
E[attribute~=value]
E[attribute|=value]
:first-child
:lang(en)
:focus
:hover
:visited
:before
:after
:first-letter
:first-line
```
### CSS Level 3 🔵
```css
::before
::after
::first-letter
::first-line
E[attribute^=value]
E[attribute$=value]
E[attribute*=value]
E ~ F
:root
E:last-child
E:only-child
E:nth-child(n)
E:nth-last-child(n)
E:first-of-type
E:last-of-type
E:only-of-type
E:nth-of-type(n)
E:nth-last-of-type(n)
E:empty
E:not(selector)
E:target
```
