# Blockquotes

> Blockquote
Still blockquote  
Again
>> sub-blockquote
> > > sub-sub blockquote

# Inline code

Inline `code`

# Keyboard input

<kbd>Ctrl</kbd> + <kbd>S</kbd>

# Block code

```
Non interpreted <i>block code</i>
```

    Non interpreted <i>block code</i>

<pre>
Interpreted <i>block code</i>
</pre>

# Highlighted block code

``` js
var foo = function (bar) {
  return bar++;
};
```

``` diff
diff --git a/filea.extension b/fileb.extension
index d28nd309d..b3nu834uj 111111
--- a/filea.extension
+++ b/fileb.extension
@@ -1,6 +1,6 @@
-oldLine
+newLine
```

# Formatting

## Not interpreted in a pre

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~

\*Literal asterisks\*

## Interpreted in a pre

<pre>
<del>Strikethrough</del>

<s>Strikethrough</s>

<ins>Underline</ins>

Indice <sub>sub</sub>

Exposant <sup>sup</sup>

&copy;

&#10148;</pre>

# Horizontal rule

___

---

***

# Images

![Alt](http://placehold.it/50x50)
![Alt](http://placehold.it/50x50 "title")
![Alt][id_img]

[id_img]: http://placehold.it/50x50

# Links

http://google.com  
[Text](http://google.com)  
[Text](http://google.com "title")  
[Text][id_link]  

[id_link]: http://google.com "optional title"

# Bulleted list

* Item 1
  With content
* Item 2  
  With content and preserving line break ("Item 2" is followed by 2 spaces)
+ Item 3
+ Item 4
- Item 5
- Item 6

# Numbered list

1. Item 1
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b
1. Item 4
   The number doesn't really matters
1. Item 5
2. Item 6
2. Item 7

# Table

<pre>| Default is left | Left-aligned | Center-aligned | Right-aligned |
| --- | :---         |     :---:      |          ---: |
| A | B   | C     | E    |
| F \| G | H     | I       | J      |</pre>

| Default is left | Left-aligned | Center-aligned | Right-aligned |
| --- | :---         |     :---:      |          ---: |
| A | B   | C     | E    |
| F \| G | H     | I       | J      |

# Newlines

Return carriage at the end of the line
Is ignored

<!-- -->

Append two spaces at the end  
The preserve the newline

<!-- -->

Or you separate the lines

By a blank line

# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

This is an H1
=============

This is an H2
-------------
