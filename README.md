# Paper about Flutter

Author: Phuc Tran <glup3.tran@gmail.com>

## Asciidoc

This paper is written in Asciidoc.

> AsciiDoc is a text document format for writing notes, documentation, articles, books, ebooks, slideshows, web pages, man pages and blogs. AsciiDoc files can be translated to many formats including HTML, PDF, EPUB, man page.
  
> AsciiDoc is highly configurable: both the AsciiDoc source file syntax and the backend output markups (which can be almost any type of SGML/XML markup) can be customized and extended by the user.

source: http://asciidoc.org/ (17th September 2019)

## Motivation / Why Flutter?

I love the fact that you can develop for IOS and Android with one code base.
This brings a lot of advantages and if needed you can also add your own native code! 

## How to build the PDF

### Requirements

- Maven or Maven Wrapper (already included)
- Java 8 (incompatible with newer versions)

### Steps

1) clone this repository
2) select Java 8, if you haven't already
3) `./mvnw clean package` or `mvn clean package`

This should generate a target folder with PDFs and images.