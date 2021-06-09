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
Case-insensitive attribute selector - [attribute='value' i]
Blank pseudo-class - :blank
Structural pseudo-class - :nth-match()
Dir pseudo-class - :dir(ltr)
Drop pseudo-class* - :drop
Hyperlink pseudo-class - :any-link
Lang pseudo-class - :lang(*-en)
Local link pseudo-class - :local-link
Matches-any pseudo-class - :matches(s1, s2)
Mutability* pseudo-class - :read-only, :read-write
Negation pseudo-class - :not(s1, s2)
Optionality pseudo-class - :required, :optional
Placeholder pseudo-class - :placeholder-shown
Indeterminate-value - :indeterminate
Validity pseudo-classes - :valid, :invalid
Relational pseudo-class - :has()
Scope pseudo-class - :scope
Range pseudo-classes - :in-range, :out-of-range
Grid pseudo-classes - :column(selector), :nth-column(n), :nth-last-column(n)
Time pseudo-class - :current
Default option pseudo-class * :default
Column combinator* - E || F
Descendant combinator - E >> F
Reference combinator - E /foo/ F
Parent combinator - E! > F
```
### Specificity 🔵
```css
1-0-0: ID selector
0-1-0: Class selector (Also attribute selector & pseudoclass)
0-0-1: Element Selector

The * selector, or global selector, has no value.
* {} 0-0-0
```
### Relational selectors & Combinators 🔵
```css
ul li,
ol li
descendant selector 
matches nested <li>s

ol > li
child selector 
matches <li>s in <ol> but not 
nested <ul>

li.hasaclass + li
adjacent sibling
```
### Selectors API 🔵
```js
var chil = $('#bar .foo');

Natively
var el   = document.querySelector('#bar');
var chil = el.querySelectorAll('.foo');

or
chil = document.querySelectorAll('#bar .foo');
```
