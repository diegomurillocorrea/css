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
Universal selector - *
Lang pseudo-class - :lang(en)
User action pseudo-class - :hover, :focus
Structural pseudo-class - :first-child
Child combinator - E > F
Attribute Selectors - [attribute], [attribute='value'], [attribute~='value'], [attribute|='en']
Adjacent sibling combinator - E + F
```
### CSS Level 3 🔵
```css
Attribute selectors - [attribute^='val'], [attribute$='lue'], [attribute*='alu']
Target pseudo-class - :target
Negation pseudo-class - :not(s)
General sibling combinator - E ~ F
Enabled and Disabled pseudo-class - :enabled, :disabled
Selected-option - :checked
Structural pseudo-classes - :root, :empty, :last-child, 
:only-child, :first-of-type, :last-of-type, :only-of-type, 
:nth-child(n), :nth-last-child(n), :nth-of-type(n), :nth-last-of-type(n)
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
