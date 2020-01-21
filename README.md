# Shopify Liquid Template Snippets for VS Code
This extension for Visual Studio Code adds snippets for Shopify Liquid Template.

Visual Studio Marketplace link: [https://marketplace.visualstudio.com/items?itemName=killalau.vscode-liquid-snippets](https://marketplace.visualstudio.com/items?itemName=killalau.vscode-liquid-snippets)

## Preview
![Showcase](./images/showcase.gif)

## Prerequisite
1. Install the latest Visual Studio Code

## Dependencies
1. [Liquid Languages Support](https://marketplace.visualstudio.com/items?itemName=neilding.language-liquid)

## Installation
1. Launch Code
2. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
3. Type `ext install vscode-liquid-snippets`
4. Reload Visual Studio Code

## Emmet Enable
Go to user settings and add the following:
```
"emmet.includeLanguages": { "liquid": "html" },
```

## Usage
Type part of a snippet, press `enter`, and the snippet unfolds.

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

### Comment Tag
```javascript
comment- // whitespace stripped
```

### Control Flow Tag
```javascript
if
else
elsif
ifelse
unless
case
when
if-     // whitespace stripped
else-   // whitespace stripped
elsif-  // whitespace stripped
ifelse- // whitespace stripped
unless- // whitespace stripped
case-   // whitespace stripped
when-   // whitespace stripped
```

### Iteration Tag
```javascript
cycle
cyclegroup
for
limit       // For loops option
offset      // For loops option
reversed    // For loops option
break
continue
tablerow
cycle-      // whitespace stripped
cyclegroup- // whitespace stripped
for-        // whitespace stripped
continue-   // whitespace stripped
tablerow-   // whitespace stripped
```

### Variable Tag
```javascript
assign
increment
decrement
capture
assign-  // whitespace stripped
capture- // whitespace stripped
```

### Theme Tag
```javascript
include
includewith    // Theme Tag {% include %} with parameters
render
renderwith    // Theme Tag {% render %} with parameters
section
raw
layout
layoutnone
paginate
schema
stylesheet
stylesheet_scss
javascript
```

### Array Filter
```javascript
join
first
last
concat
map
reverse
size
sort
uniq
```

### HTML Filter
```javascript
img_tag
img_tag_param  // HTML Filter {% img_tag %} with parameters
script_tag
stylesheet_tag
```

### Math Filter
```javascript
abs
ceil
divided_by
floor
minus
plus
round
times
modulo
```

### Money Filter
```javascript
money
money_with_currency
money_without_trailing_zeros
money_without_currency
```

### String Filter
```javascript
append
camelcase
captialize
downcase
escape
handleize
md5
newline_to_br
pluralize
prepend
remove
remove_first
replace
replace_first
slice
slice_single   // String Filter 'slice' with single parameter
split
strip
lstrip
rstrip
strip_html
strip_newlines
truncate
truncatewords
upcase
url_encode
url_escape
url_param_escape
```

### URL Filter
```javascript
asset_url
asset_img_url
img_url
```

## Release

### 1.2.0

- Add theme tag: render, renderwith

### 1.2.0

- Add theme tags: schema, stylesheet, stylesheet_scss, javascript

### 1.1.1

- Update readme, step to enable Emmet

### 1.1.0

- Add whitespaced comment tag

### 1.0.1

- Add keep both tag for whitespace and non-whitespace control

### 1.0.0

- Add whitespace control

## License

MIT
