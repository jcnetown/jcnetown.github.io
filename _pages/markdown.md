---
permalink: /markdown/
title: "Extinct in the 15th Century"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Tenerife Giant Lizard

The Tenerife Giant Lizard (also known as Gallotia Goliath by its species name) was the largest reptile on the Canary Islands. They went extinct between 1400 and 1500. They are believed to be around 3 feet long.
<a href="https://en.wikipedia.org/wiki/Gallotia_goliath#/media/File:Gallotia_goliath_reconstruction.jpg"><img src="https://i.ibb.co/Q65fptM/Gallotia-goliath-reconstruction.jpg" alt="Gallotia-goliath-reconstruction" border="0"></a><br /><a target='_blank'/>
<small>Image is a depiction of the Gallotia Goliath next to a human hand.</small>                                                     
<small>Made by El fosilmaníaco</small>

## Kaua'i Finch

The Kaua'i Finch is an extinct species of bird that lived in Hawaii. It was about 5 and a half inches long. They were believed to live in the highland forest and travel down to lower lands. Not much is known about this bird due to it being extinct before European explorers came to Hawaii. It went extinct somewhere between 1425-1660.



## South Island Giant Moa

The South Island giant moa lived in South Island, New Zealand. It was the tallest bird to ever walk the Earth with the average height for females being 6'7" and males being 11'10". Giant moas' were fully feathered expect for their heads and a bit of their necks and had only a remnant of wings. It went extinct between 1451-1952.
<a href="https://en.wikipedia.org/wiki/South_Island_giant_moa#/media/File:Dinornis_robustus,_South_Island_Giant_Moa_-_three_quarter_view_on_black_YORYM_2004_20.jpg"><img src="https://i.ibb.co/mXd3kjX/big-bird.png" alt="big-bird" border="0" height=200 width=398></a><br /><a target='_blank'/>
<small>A skeleton of a South Island giant moa</small>                                                                                 
<small>Photo from York Mueseums Trust</small>

## South American Wolf 

The South American wolf went extinct between 1454 and 1626. The South American wolf's diet was preying on small mammals and eating large carcasses, meaning it was both a carnivore and a scavenger. There is evidence of some people keeping these as pets, like at some dug up graves they find the bones of this wolf. 
<a href="https://en.wikipedia.org/wiki/Dusicyon_avus#/media/File:Dusicyon_avus_Wikipedia_Juandertal.jpg"><img src="https://i.ibb.co/HtK9FcM/Dusicyon-avus-Wikipedia-Juandertal.jpg" alt="Dusicyon-avus-Wikipedia-Juandertal" border="0"></a><br /><a target='_blank'/>
<small>A sketch of a South American wolf</small> <br>
<small>Made by Juandertal</small> <br>

## Markdown guide

Academic Pages uses [kramdown](https://kramdown.gettalong.org/index.html) for Markdown rendering, which has some differences from other Markdown implementations such as GitHub's. In addition to this guide, please see the [kramdown Syntax page](https://kramdown.gettalong.org/syntax.html) for full documentation.  

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.

## Tables

### Table 1

| Entry            | Item   |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | 2016   | Description of the item in the list                          |
| [Jane Doe](#)    | 2019   | Description of the item in the list                          |
| [Doe Doe](#)     | 2022   | Description of the item in the list                          |

### Table 2

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | ce
ll5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

## Notices

Basic notices or call-outs are supported using the following syntax:

```markdown
**Watch out!** You can also add notices by appending `{: .notice}` to the line following paragraph.
{: .notice}
```

which wil render as:

**Watch out!** You can also add notices by appending `{: .notice}` to the line following paragraph.
{: .notice}

### Footnotes

Footnotes can be useful for clarifying points in the text, or citing information.[^1] Markdown support numeric footnotes, as well as text as long as the values are unique.[^note]

```markdown
This is the regular text.[^1] This is more regular text.[^note]

[^1]: This is the footnote itself.
[^note]: This is another footnote.
```

[^1]: Such as this footnote.
[^note]: When using text for footnotes markers, no spaces are permitted in the name.

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com "Github").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

You can also write larger blocks of code with syntax highlighting supported for some languages, such as Python:

```python
print('Hello World!')
```

or R:

```R
print("Hello World!", quote = FALSE)
```

### Details Tag (collapsible sections)

The HTML `<details>` tag works well with Markdown and allows you to include collapsible sections, see [W3Schools](https://www.w3schools.com/tags/tag_details.asp) for more information on how to use the tag.

<details>
  <summary>Collapsed by default</summary>
  This section was collapsed by default!
</details>

The source code:

```HTML
<details>
  <summary>Collapsed by default</summary>
  This section was collapsed by default!
</details>
```

Or, you can leave a section open by default by including the `open` attribute in the tag:

<details open>
  <summary>Open by default</summary>
  This section is open by default thanks to open in the &lt;details open&gt; tag!
</details>


### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.

***
**Footnotes**

The footnotes in the page will be returned following this line, return to the section on <a href="#footnotes">Markdown Footnotes</a>.

