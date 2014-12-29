principle: Perceptible
thematic: Présentation de l'information
standard: AA
target: Développeurs

# [GitHub Flavored Markdown][ref3]

## Differences from traditional Markdown

### Multiple underscores in words

wow_great_stuff

do_this_and_do_that_and_another_thing.

wow*great*stuff

### URL autolinking

http://example.com

### Strikethrough

~~Mistaken text.~~

### Fenced code blocks

Here's an example:

```
function test() {
  console.log("notice the blank line before this function?");
}
```

### Syntax highlighting

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

### Tables

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

[ref3]: https://help.github.com/articles/github-flavored-markdown/

