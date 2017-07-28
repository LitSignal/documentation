> *Some tips for writing a good README along with a Markdown primer.*

The README is the first thing most visitors will read. Make it concise but complete. As a starting point, consider these questions:
- What is the module about?
- What are the practical applications?
- Is the module a work in progress? If so, what are the outstanding issues?
- Are there any restrictions on sharing or using the attachments?

**The following sections provide information about how to add and edit the README and how to use Markdown to format the text.**

***

## README Editing

Adding or editing the README is as easy as clicking on the `Edit` button in the module header. A text input labeled README will appear. Type or paste your README content into the field, and click the `Save` button in the module header. Your README will be saved, and you will see your changes immediately. If you need to make a change, just repeat those steps. If you make a mistake while editing and don't want to save the changes, just refresh the page without clicking the `Save` button, and the latest version of your module will be reloaded.

Feel free to edit the README with the text editor of your choice. There are a number of free editors that support Markdown and will allow you to edit offline, see a live preview and make use of your screen real estate. [VSCode](https://code.visualstudio.com/) and [Atom](https://atom.io/) are 2 favorites here at Litsignal.

There is one gotcha that you should keep in mind. If you make and edit then navigate away from your module page, your browser won't remember the changes if you use forward or back to return to the page. Don't panic. Just refresh the page, and the latest version should appear.

***

## Markdown Basics

Markdown was designed by [Jon Gruber](https://daringfireball.net/) to provide useful formatting features while retaining human readability, You can read more about the philosophy and features of Markdown [here](https://daringfireball.net/projects/markdown/syntax). In the years since its description, it has become the defacto standard for writing text documents for the web, even spawning a number of derivative formats. Below you'll find examples of some of the more common features of Markdown. You can dive deeper by reviewing the [Markdown syntax documentation](https://daringfireball.net/projects/markdown/syntax).

Each of the examples below demonstrates the transformation of the raw text to formatted text. The raw text is reproduced in a code block, and the formatted output immediately follows.

***

### Headers

> Use 1-6 `#`'s at the start of a line followed by a `space` to denote a header, `<H1>` to `<H6>`.

	###### H6 header

###### H6 header

***

### Emphasis

> Surround a span of words with one or two `*` or `_` to denote emphasis equivalent to `<em>` and `<strong>` html tags.

	*em tag emphasis*

*em tag emphasis*

	**strong tag emphasis**

**strong tag emphasis**

***

### Block quotes

> Prepend a line or paragraph with `>` and a `space` to create a block quote.

	> Block quote line 1
	> Block quote line 2

> or

	> Block quote line 1
	Block quote line 2

> Block quote line 1  
Block quote line 2

***

### Lists

> Create a list by starting a line with a `-`, `+`, or `*` followed by a `space`. 

	My list:
	- Item one
	+ Item two
	* Item three

My list:
- Item one
- Item two
- Item three

> Similarly, numbered lists can be created by starting a line with `0-9` followed by `.` and a `space`.

	My numbered list:
	1. Item one
	2. Item two
	3. Item three

My numbered list:
1. Item one
2. Item two
3. Item three

***

### Links

> Create an inline link by surrounding a span of text with `[]` followed by the URL surrounded by `()`.

	I recommend [Litsignal](https:litsignal.com "Optional title") to all of my friends.

I recommend [Litsignal](https:litsignal.com "Optional title") to all of my friends.

> You can also use shortcuts to use links that are defined elsewhere in the document.

	I recommend [Litsignal][1] to all of my friends.

	[1]: https://litsignal.com "Optional title"

<br/>

	I recommend [Litsignal][shortcut] to all of my friends.

	[shortcut]: https://litsignal.com "Optional title"

I recommend [Litsignal][shortcut] to all of my friends.

[shortcut]: https://litsignal.com "Optional title"

> Links can also be created by surrounding a URL with `<>`.

	I recommend <https://litsignal.com> to all of my friends.

I recommend <https://litsignal.com> to all of my friends.

***

### Images

> Embed an image similar to the way you would create a link.

	![Litsignal logo](https://assets.litsignal.com/images/coverart.png)

![Litsignal logo](https://assets.litsignal.com/images/coverart.png)

***

### Horizontal rule

> Insert a horizontal line by placing `***` alone on a line.

	***

***

### Backslash escape

> Since `*`, `#`, `` ` ``, `_`, `{}`, `[]`,`()`, `<>`, `+`, `-`, `.`, and `!` all may have special meaning in Markdown depending on where they appear, you may occasionally have to use a `\` to bypass the formatting engine.

	**emphasized text**

**emphasized text**

	\*\*literal asterisks\*\*

\*\*literal asterisks\*\*
 

***

### Other features

> `Code block`s and `inline code` have been employed throughout this document. To create a `code block`, indent a block of text. To create `inline code`, surround a span of text with `backtick`s `` ` ``. 