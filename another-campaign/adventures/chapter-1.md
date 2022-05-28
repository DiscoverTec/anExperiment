# Heading 1
this is a sample of all the markdown we could think of

## Heading 2
## Heading with ID {#custom-id}
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6	

---

Paragraph
text `Inline Code` text		
~~Mistaken text.~~	
*Italics*	
**Bold**	

Paragraph custom classes
{: .class #custom-id-3 style="padding-top:0" key="value"}

---

Tasks
- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**
- [ ] incomplete
- [x] completed

---

Code Blocks

    4 space indention
    makes full-width
    standard code blocks

```js
var now = new Date();

var days = new Array('Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday');

var months = new Array('January','February','March','April','May','June','July','August','September','October','November','December');

var date = ((now.getDate()<10) ? "0" : "")+ now.getDate();

function fourdigits(number)	{
	return (number < 1000) ? number + 1900 : number;
								}
today =  days[now.getDay()] + ", " +
         months[now.getMonth()] + " " +
         date + ", " +
         (fourdigits(now.getYear())) ;

document.write(today);
```

```css
#sc_drag_area {
  height:100px;
  left:150px;
  position: absolute;
  top:100px;
  width:250px;
  z-index: 9999;
}
```

---

* List item one
* List item two
    * A nested item

---

1. Number list item one		
	1.1. A nested item
2. Number list item two
3. Number list item three

---

> Quote
> 
> Second line Quote

---

Standard link =  https://gist.github.com/derrickderekdereq31	
[Custom Text Link](https://gist.github.com/derrickderekdereq31)

---

image
![Image](https://placeimg.com/640/480/arch)

---

Table

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

---

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

---

term
: definition

---

Emoji

That is so funny! :joy:

---

Highlight

I need to highlight these ==very important words==.

---

Subscript

H~2~O
	
---

Superscript

X^2^

---

Admonitions

> :memo: **Note:** Sunrises are beautiful.

---

Collapse

<details>
  <summary>This is the summary text, click me to expand</summary>
  This is the detailed text.
</details>