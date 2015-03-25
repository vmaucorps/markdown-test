principle: Perceptible
thematic: Présentation de l'information
standard: A
target: Contributeurs

[DARING FIREBALL][ref1]
====================

BLOCK ELEMENTS
------------

### BLOCKQUOTES

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

This is a paragraph used as separator between 2 blockquotes

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

### LISTS

*   Red
*   Green
*   Blue

Lorem ipsum

+   Red
+   Green
+   Blue

This is a paragraph used as separator between 2 lists

-   Red
-   Green
-   Blue

This is another paragraph used as separator between 2 lists

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

### CODE BLOCKS

This is a normal paragraph:

    This is a code block.

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

This is a paragraph used as separator between 2 code blocks

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

### HORIZONTAL RULES

* * *

***

*****

- - -

---------------------------------------

## SPAN ELEMENTS ##

### LINKS ###

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

### EMPHASIS ####################

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

un*frigging*believable

\*this text is surrounded by literal asterisks\*

### CODE

Use the `printf()` function.

``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

Please don't use any `<blink>` tags.

`&#8212;` is the decimal-encoded equivalent of `&mdash;`.

### IMAGES

![Alt text](https://assets-cdn.github.com/favicon.ico)

![Alt text](/Markdown syntax/01 - Daring Fireball/github.ico "Optional title")

![Alt text](./github.ico "Optional title")

![Alt text][img]

[img]: https://assets-cdn.github.com/favicon.ico  "Optional title attribute"

### MISCELLANEOUS

<http://example.com/>

<address@example.com>

[ref1]: http://daringfireball.net/projects/markdown/syntax/

