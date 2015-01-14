html-style-guide
================

HTML Style Guide

## <a name='TOC'>Inhaltsverzeichnis</a>

  1. [Use Correct Document Type](#document-type)
  1. [Use Lower Case Element Names](#lower-case-element-names)
  1. [Close All HTML Elements](#close-all-elements)
  1. [Close Empty HTML Elements](#close-empty-elements)
  1. [Use Lower Case Attribute Names](#lower-case-attribute-names)
  1. [Quote Attribute Values](#quote-attribute-values)
  1. [Image Attributes](#image-attribute)
  1. [Meta Data](#meta-data)
  1. [HTML Comments](#html-comments)
  1. [Quellen](#quellen)

## <a name='document-type'>Use Correct Document Type</a>

  - Always declare the document type as the first line in your document:

    ```html
    <!DOCTYPE html>
    ```

    **[[⬆]](#TOC)**

## <a name='lower-case-element-names'>Use Lower Case Element Names</a>

   - HTML5 allows mixing uppercase and lowercase letters in element names. We recommend using lowercase element names:

    + Mixing uppercase and lowercase names is bad
    + Developers are used to use lowercase names (as in XHTML)
    + Lowercase look cleaner
    + Lowercase are easier to write

    ```html
    // schlecht
    <SECTION>
  		<p>This is a paragraph.</p>
	</SECTION>

    // sehr schlecht
    <Section>
  		<p>This is a paragraph.</p>
	</SECTION>

    // gut
    <section>
  		<p>This is a paragraph.</p>
	</section>
    ```

    **[[⬆]](#TOC)**

## <a name='close-all-elements'>Close All HTML Elements</a>

   - In HTML5, you don't have to close all elements (for example the <p> element). We recommend closing all HTML elements:

    ```html
    // schlecht
	<section>
	  <p>This is a paragraph.
	  <p>This is a paragraph.
	</section>

    // gut
	<section>
	  <p>This is a paragraph.</p>
	  <p>This is a paragraph.</p>
	</section>
    ```

    **[[⬆]](#TOC)**

## <a name='close-empty-elements'>Close Empty HTML Elements</a>

   - In HTML5, it is optional to close empty elements.

    ```html
    // schlecht
	<meta charset="utf-8">

    // gut
	<meta charset="utf-8" />
    ```

    **[[⬆]](#TOC)**

## <a name='lower-case-attribute-names'>Use Lower Case Attribute Names</a>

   - HTML5 allows mixing uppercase and lowercase letters in attribute names. We recommend using lowercase attribute names:

    + Mixing uppercase and lowercase names is bad
    + Developers are used to use lowercase names (as in XHTML)
    + Lowercase look cleaner
    + Lowercase are easier to write

    ```html
    // schlecht
	<div CLASS="menu">

    // gut
	<div class="menu">
    ```

    **[[⬆]](#TOC)**

## <a name='quote-attribute-values'>Quote Attribute Values</a>

   - HTML5 allows attribute values without quotes. We recommend quoting attribute values:

    + You have to use quotes if the value contains spaces
    + Mixing styles is never good
    + Quoted values are easier to read


    ```html
    // schlecht
	<table class=table striped>

    // gut
	<table class="table striped">
    ```

    **[[⬆]](#TOC)**

## <a name='image-attribute'>Image Attributes</a>

   - Always use the alt attribute with images. It is important when the image cannot be viewed. Always define image size. It reduces flickering because the browser can reserve space for images before they are loaded.

    + You have to use quotes if the value contains spaces
    + Mixing styles is never good
    + Quoted values are easier to read


    ```html
    // schlecht
	<img src="html5.gif" />

    // gut
	<img src="html5.gif" alt="HTML5" width="128" height="128" />
    ```

    **[[⬆]](#TOC)**

## <a name='meta-data'>Meta Data</a>

   - The <title> element is required in HTML5. Make the title as meaningful as possible:


    ```html
	<title>HTML5 Syntax and Coding Style</title>
    ```

   - To ensure proper interpretation, and correct search engine indexing, both the language and the character encoding should be defined as early as possible in a document:


    ```html
	<!DOCTYPE html>
	<html lang="en-US">
	<head>
		<meta charset="UTF-8">
		<title>HTML5 Syntax and Coding Style</title>
	</head>

    ```

    **[[⬆]](#TOC)**

## <a name='html-comments'>HTML Comments</a>

   - Short comments should be written on one line, with a space after <!-- and a space before -->:


    ```html
	<!-- This is a comment -->
    ```

   - Long comments, spanning many lines, should be written with <!-- and --> on separate lines:


    ```html
	<!--
	  This is a long comment example. This is a long comment example. This is a long comment example.
	  This is a long comment example. This is a long comment example. This is a long comment example.
	-->

    ```

    **[[⬆]](#TOC)**

## <a name='quellen'>Quellen</a>

http://www.w3schools.com/html/html5_syntax.asp
