# Typora Mono Theme

Mono is a typewriter inspired theme for the awesome markdown editor [Typora](https://www.typora.io). I wanted the basic look of plain text markdown but with a few enhancements, like the hashes for headers hanging out on the left side.

Currently it is only tested on the MacOS version of Typora and it uses some bleeding edge CSS like variables which I have no idea if they work im Typora for other platforms. It is still plenty of work left before it is a complete theme.

## Inline elements

This is a standard paragraph. **To make a test bold**, I prefer to use asterixes. And to emphasis a text _underscores makes most sense_. [Links are simply underlined](http://lostkeys.se).I rarely use ~~strikethrough~~ but it also works. Inline code is difficult to `highlight in a typewriter fashion`.

## Block elements

Unordered lists:

* I prefer using asterix as bullets
* Instead of dashes. But both works

Ordered lists

1. Apples
2. Oranges
3. Bananas

Codeblock

```css
/* blockquote & Pre */
blockquote, pre {
  margin: 1rem 0;
  padding-left: 4ch;
  position: relative;
  overflow: hidden;
}
```

Blockquote

> The third-rate mind is only happy when it is thinking with the majority. The second-rate mind is only happy when it is thinking with the minority. The first-rate mind is only happy when it is thinking.
> —A. A. Milne

### Headers

H1, H2 and H3 headers are styled to stand out. I rarely use more than three levels of headers. Headers level 4-6 are indicated with hashes and without margins and paddings.

#### Header 4

##### Header 5

###### Header 6

## Caveats

Focus mode does not work well with this theme at the moment.

Tables are not styled

Math blocks are not tested. Assuming it looks terrible

Outline panel is not styled and causes the writing area to expand

Task list looks bad

## Todo

See if it's possible to style typoras meta-characters, for example when adding headers.

Is it possible to style the caret?

Style codeblocks