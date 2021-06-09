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
Type selector - E
Descendant selector - E F
Class selector - .class
ID selector - #elID
Link pseudo-class - :link
User action pseudo-class - :active
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
### CSS Level 4 🔵
```css
:blank
:indeterminate
:placeholder-shown
:not(s1, s2)
:matches(s1, s2)
:has(rs1, rs2)
[foo="bar" i]
:dir(ltr)
:lang(zh, *-hant)
:any-link
:scope
:current
:focus-ring
:drop
:drop(active)
:drop(valid)
:drop(invalid)
:user-error
E >> F
F || E
:nth-column(n)
:nth-last-column(n)
```
### UI / Selectors 🔵
```css
E:enabled
E:disabled
E:checked
E:default
E:valid
E:invalid
E:in-range
E:out-of-range
E:required
E:optional
E:read-only
E:read-write
```
