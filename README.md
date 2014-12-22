Title:  A Readme Document

markdown-test
=============

Markdown syntax test project

This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.

[DARING FIREBALL][ref1]
-----------------------

### BLOCK ELEMENTS

#### BLOCKQUOTES

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

Lorem ipsum

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

Lorem ipsum

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

Lorem ipsum

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");

#### LISTS

*   Red
*   Green
*   Blue

Lorem ipsum

+   Red
+   Green
+   Blue

Lorem ipsum

-   Red
-   Green
-   Blue

Lorem ipsum

1.  Bird
2.  McHale
3.  Parish

Lorem ipsum

1.  Bird
1.  McHale
1.  Parish

Lorem ipsum

3. Bird
1. McHale
8. Parish

Lorem ipsum

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.

Lorem ipsum

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.

Lorem ipsum

*   Bird
*   Magic
 

Lorem ipsum

*   Bird

*   Magic

Lorem ipsum

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

Lorem ipsum

*   This is a list item with two paragraphs.

    This is the second paragraph in the list item. You're
only required to indent the first line. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit.

*   Another item in the same list.

Lorem ipsum

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.

Lorem ipsum

*   A list item with a code block:

        <code goes here>

Lorem ipsum

1986\. What a great season.

#### CODE BLOCKS

This is a normal paragraph:

    This is a code block.

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

Lorem ipsum

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

#### HORIZONTAL RULES

* * *

***

*****

- - -

---------------------------------------

### SPAN ELEMENTS ###

#### LINKS ####

This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

See my [README.md](/README.md) page for details.

This is [an example][id] reference-style link.

This is [an example] [ID] reference-style link.

[id]: http://example.com/  "Optional Title Here"

1. reference-style link [link1][link1].
2. reference-style link [link2][link2].
3. reference-style link [link3][link3].
4. reference-style link [link4][link4].
5. reference-style link [link5][link5].

[link1]: http://example.com/1  "Optional Title Here"
[link2]: http://example.com/2  'Optional Title Here'
[link3]: http://example.com/3  (Optional Title Here)
[link4]: <http://example.com/4>  "Optional Title Here"
[link5]: http://example.com/5
    "Optional Title Here"

Visit [Daring Fireball][] for more information.

[Daring Fireball]: http://daringfireball.net/

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"

I get 10 times more traffic from [Google](http://google.com/ "Google")
than from [Yahoo](http://search.yahoo.com/ "Yahoo Search") or
[MSN](http://search.msn.com/ "MSN Search").

#### EMPHASIS ####################

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

un*frigging*believable

\*this text is surrounded by literal asterisks\*

#### CODE

Use the `printf()` function.

``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

Please don't use any `<blink>` tags.

`&#8212;` is the decimal-encoded equivalent of `&mdash;`.

#### IMAGES

![Alt text](https://assets-cdn.github.com/favicon.ico)

![Alt text](/assets/github.ico "Optional title")

![Alt text][img]

[img]: https://assets-cdn.github.com/favicon.ico  "Optional title attribute"

#### MISCELLANEOUS

<http://example.com/>

<address@example.com>

## [GitHub Markdown Basics][ref2]

### Basic writing

#### Paragraphs

On July 2, an alien mothership entered Earth's orbit and deployed several dozen saucer-shaped "destroyer" spacecraft, each 15 miles (24 km) wide.

On July 3, the Black Knights, a squadron of Marine Corps F/A-18 Hornets, participated in an assault on a destroyer near the city of Los Angeles.

#### Blockquotes

In the words of Abraham Lincoln:

> Pardon my french

#### Styling text

*This text will be italic*
**This text will be bold**

**Everyone _must_ attend the meeting at 5 o'clock today.**

### Lists

#### Unordered lists

* Item
* Item
* Item

Lorem ipsum

- Item
- Item
- Item

#### Ordered lists

1. Item 1
2. Item 2
3. Item 3

#### Nested lists

1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3

### Code formatting

#### Inline formats

Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.

#### Multiple lines

Check out this neat program I wrote:

```
x = 0
x = 2 + 2
what is x
```

### Links

[Visit GitHub!](www.github.com)

## [GitHub Flavored Markdown][ref3]

### Differences from traditional Markdown

#### Multiple underscores in words

wow_great_stuff

do_this_and_do_that_and_another_thing.

wow*great*stuff

#### URL autolinking

http://example.com

#### Strikethrough

~~Mistaken text.~~

#### Fenced code blocks

Here's an example:

```
function test() {
  console.log("notice the blank line before this function?");
}
```

#### Syntax highlighting

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Tables

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

## [Emoji][ref6]

### People

:bowtie:
...

### Nature

:sunny:
...

### Objects

:bamboo:
...

### Places

:house:
...

### Symbols

:one:
...

#### Sounds => Not working

/play secret
...

## [Writing on GitHub][ref4]

### Markup => [Only available for comments][ref5]

#### Newlines

Roses are red
Violets are blue

#### Task lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

Lorem ipsum

- [ ] a bigger project
  - [ ] first subtask #1
  - [ ] follow up subtask #1
  - [ ] final subtask cc @tonai
- [ ] a separate task

#### References

* SHA: 6d823ad22aac09f3b370eb2b93a7551a9a293bee
* User@SHA: tonai@6d823ad22aac09f3b370eb2b93a7551a9a293bee
* User/Repository@SHA: tonai/markdown-test@6d823ad22aac09f3b370eb2b93a7551a9a293bee
* #Num: #1
* GH-Num: GH-1
* User#Num: tonai#1
* User/Repository#Num: tonai/markdown-test#1

## Sanitize

### Available HTML tags

#### Headings

`<h1>h1</h1>` : <h1>h1</h1>

`<h2>h2</h2>` : <h2>h2</h2>

`<h3>h3</h3>` : <h3>h3</h3>

`<h4>h4</h4>` : <h4>h4</h4>

`<h5>h5</h5>` : <h5>h5</h5>

`<h6>h6</h6>` : <h6>h6</h6>

`<h7>h7</h7>` : <h7>h7</h7>

`<h8>h8</h8>` : <h8>h8</h8>

#### Prose

`<p>p</p>` : <p>p</p>

`<div>div</div>` : <div>div</div>

`<blockquote>blockquote</blockquote>` : <blockquote>blockquote</blockquote>

#### Inline

`<b>b</b>` : <b>b</b>

`<i>i</i>` : <i>i</i>

`<strong>strong</strong>` : <strong>strong</strong>

`<em>em</em>` : <em>em</em>

`<tt>tt</tt>` : <tt>tt</tt>

`<code>code</code>` : <code>code</code>

`<ins>ins</ins>` : <ins>ins</ins>

`<del>del</del>` : <del>del</del>

`<sup>sup</sup>` : <sup>sup</sup>

`<sub>sub</sub>` : <sub>sub</sub>

`<kbd>kbd</kbd>` : <kbd>kbd</kbd>

`<samp>samp</samp>` : <samp>samp</samp>

`<q>q</q>` : <q>q</q>

`<var>var</var>` : <var>var</var>

`<a href="#">a</a>` : <a href="#">a</a>

`<img src="/assets/github.ico"/>` : <img src="/assets/github.ico"/>

#### Lists

`<ol><li>ol li</li></ol>` : <ol><li>ol li</li></ol>

`<ul><li>ul li</li></ul>` : <ul><li>ul li</li></ul>

`<dl><dt>dl dt</dt><dd>dl dd</dd></dl>` : <dl><dt>dl dt</dt><dd>dl dd</dd></dl>

#### Tables 

`<table><thead><tr><th>table thead tr th</th></tr></thead><tbody><tr><td>table tbody tr td</td></tr></tbody><tfoot><tr><td>table tfoot tr td</td></tr></tfoot></table>` : <table><thead><tr><th>table thead tr th</th></tr></thead><tbody><tr><td>table tbody tr td</td></tr></tbody><tfoot><tr><td>table tfoot tr td</td></tr></tfoot></table>

#### Breaks

`<br/>` : <br/>

`<hr/>` : <hr/>

#### Ruby

`<ruby>ruby<rt>rt</rt><rp>rp</rp></ruby>` : <ruby>ruby<rt>rt</rt><rp>rp</rp></ruby>

## Miscellaneous

### Relative links (TOC)

* [DARING FIREBALL](#user-content-daring-fireball)
* [GitHub Markdown Basics](#user-content-github--markdown-basics)
* [GitHub Flavored Markdown](#user-content-github-flavored-markdown)
* [Emoji](#user-content-emoji)
* [Writing on GitHub](#user-content-writing-on-github)
* [Sanitize](#user-content-sanitize)
* [Miscellaneous](#user-content-miscellaneous)

### Paragraph + List

This is a paragraph immediately followed by a list :
* item 1
* item 2

[ref1]: http://daringfireball.net/projects/markdown/
[ref2]: https://help.github.com/articles/markdown-basics/
[ref3]: https://help.github.com/articles/github-flavored-markdown/
[ref4]: https://help.github.com/articles/writing-on-github/
[ref5]: https://github.com/tonai/markdown-test/issues/1
[ref6]: http://www.emoji-cheat-sheet.com/
