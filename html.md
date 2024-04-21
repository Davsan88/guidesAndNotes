# HTML Reference Guide

## Basic Structure
<q>
```html
!DOCTYPE html
html
head
    titlePage Title/title
/head
body
    h1This is a Heading/h1
    pThis is a paragraph./p
/body
/html


## Common Tags

<h1> to <h6>: Define headings with different levels of importance, <h1> being the most important.
<p>: Represents a paragraph.
<a href="URL">: Creates a hyperlink.
<img src="image.jpg" alt="description">: Embeds an image.
<ul>, <ol>, <li>: Create unordered and ordered lists.
<div>: Serves as a generic container for content, with no semantic meaning.
<section>: Groups thematically related content, typically includes a heading.
<span>: A generic inline container.
<form>, <input>: Used to create an interactive form for user input.
<article>: Represents a self-contained composition in a document.
<aside>: Denotes content indirectly related to the main content.
<figure> and <figcaption>: Used together to associate a caption with a figure.

## Attributes

class: Groups elements for CSS or JavaScript.
id: Identifies an element uniquely in the document.
style: Applies inline CSS styles.
href: Specifies link targets.
src: Sets source URLs for media.
alt: Provides text alternatives for images.
title: Gives additional information, usually displayed as a tooltip.
placeholder: Shows hint text in input fields.
type: Defines input types in forms.


## Basic Text Formatting:

<b>: Makes text bold.
<i>: Italicizes text.
<u>: Underlines text.
<s>: Strikes through text.
<sup>: Creates superscript text.
<sub>: Creates subscript text.
<em>: Emphasizes text (typically italicized).
<strong>: Strong importance (typically bold).
<span>: Generic inline container for phrasing content, without semantic meaning.
<small>: Makes the text smaller.
<mark>: Highlights text.
<del>: Represents deleted text.
<ins>: Represents inserted text.
<blockquote>: Defines a section quoted from another source. Use cite="" to specify the URL of the source.
<q>: Defines a short inline quotation.
<abbr>: Indicates an abbreviation or acronym; use the title attribute to describe it.
<address>: Specifies contact information for the author/owner of a document.
<cite>: Defines the title of a creative work.
<bdo dir="">: Overrides text direction. dir can be "ltr" (left to right) or "rtl" (right to left).
<code>: Displays its contents styled in a fashion intended to indicate the text is a short fragment of computer code.
<kbd>: Represents user input.
<samp>: Defines sample output from a computer program.
<var>: Represents a variable.
&lt; & &gt;: The character entities for less-than and greater-than signs.
&nbsp;: A non-breaking space.


## Block and Inline Elements

#### Block-level HTML Elements
These elements typically form a visible block on a page, like a paragraph or a division. Examples include:

<header>, <footer>: Define the header and footer sections.
<nav>: Navigation links.
<main>, <article>, <section>: Main content, self-contained content, and thematic grouping respectively.
<form>: Forms for user input.
<table>: Tables.

#### Inline-level HTML Elements
These elements are contained within block-level elements and do not start on a new line. Examples include:

<b>, <i>, <em>, <strong>: Bold, italic, emphasized text, and strong importance respectively.
<br>: Line break.
<input>, <label>: Form input and its label.
<cite>, <code>: Reference to a cited work and a piece of computer code.


## Positioning in CSS. 

#### The position property includes:

static: Default, following the normal flow.
relative: Positioned relative to its normal position.
absolute: Positioned relative to the nearest positioned ancestor.
fixed: Positioned relative to the viewport.
sticky: Switches between relative and fixed, based on the scroll position.

Use top, right, bottom, and left to adjust the element's position. z-index determines the stacking order. Key considerations include element overlap, document flow impact, and context (e.g., viewport or container). For more, visit CSS Positioning on MDN Web Docs: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning

