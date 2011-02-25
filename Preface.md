# Preface
A Leanpub book is composed of either a bunch of Markdown files or a bunch of HTML files.

The order of these files is defined in a file called Book.txt, which is in the same folder as this file.

This is the Leanpub sample book for a Markdown book, so these files are Markdown.  Markdown is a good format for people who want to write their book in a text editor.

To learn about the syntax and philosophy of Markdown, see [this article by John Gruber](http://daringfireball.net/projects/markdown/syntax).

Briefly, Markdown is a nice way of writing content which is easily transformed into HTML.  For example, # at the beginning of a line becomes an h1, ## becomes an h2, ### becomes an h3, etc.  Lists, paragprahs and other formatting is also intuitive.

Even if you know Markdown, you need to learn a few things about how we use it at Leanpub.

First, we use h1 for chapters and h2 and below for sections.  This is true whether the book is a Markdown book or an HTML book.

So, if you look at the top of this file you'll see that it has one #, meaning it is a Chapter.  (No, we don't do anything special for prefaces or appendices at Leanpub; we feel that ebooks are better served by having normal numbers as page numbers instead of Roman numerals.)

Another thing this means is that one file can contain as many chapters or sections as you want.  For example, the next few lines will create some chapters and sections.

# Chapter One
This is chapter one.

## Chapter One, Section One
This is section one in chapter one.

## Chapter One, Section Two
This is section two in chapter one.

# Chapter Two
This is chapter two.

## Chapter Two, Section One
This is section one in chapter two.

# Sample Books
Leanpub also lets you create a sample book.  It's called Sample.txt, and it is in the same folder as this file.  Note that, like Book.txt, it is just as list of files.  It's supposed to be a smaller list than what is in Book.txt, or else you're giving your whole book away!  (If you don't want a sample book, just delete the Sample.txt file.)

Anyway, one consequence of the Sample.txt file approach to specifying a sample book is that it's an "all or nothing" thing to include a file.  If you include a file, all the chapters and sections in it are included.  Because of this, we recommend a couple things:

1. Either use one chapter per file, or one section per file.
2. Never let a chapter's content span multiple files, unless that content is in sections.

These two guidelines mean that your sample book is a lot less likely to have problems.  If you don't follow them, things can still work, but you can sometimes create a situation where your book will be created fine but your sample book will not.

(Note that this file actually breaks guideline #1!  If we were following it, then Chapter One and Chapter Two would be in their own files.)
