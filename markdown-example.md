---
title:  'This is the title: it contains a colon'
toc: true
author:
- Author One
- Author Two
keywords: [nothing, nothingness]
abstract: |
  \pagenumbering{gobble}
  This is the abstract.

  It consists of two paragraphs.
  \newpage
---
\newpage
\pagenumbering{arabic}
\pagestyle{fancy}
# BSPWM
\fancyhead[CO,CE]{This is fancy}
\fancyfoot[LE,RO]{So is this}
## XDG_CONFIG_HOME

`/etc/profile.d/xdg_config.sh`  
<u>hello</u>  

```bash 
#!/bin/sh
#fds
XDG_CONFIG_HOME="$HOME/.config"
export XDG_CONFIG_HOME
```

## Bring windows to current worspace


mnebn

```bash
rofi -show window -window-command "bspc node {window} -d focused"
```
\newpage
## Java

set `_JAVA_AWT_WM_NONREPARENTING=1` in `/etc/profile.d/jre.sh`.

## TODO

- [X] Done
- [ ] TODO

### Some other title {#foo}

blabla^(@item)^ fd


* dot
* doooot 
* dottie
	1. one
	1. two
		1. more
		1. moooore
		1. mooooreeee
			* doooo
			* iit

as (@someitem) explains...

(@someitem) bla bla bla
(@item) wtf

### mooore ### 

> All around the blacok  
> or ..

2^12^ yeah, binary power... (superscirpt)

H~2~O is water power! (subscript)

\newpage

# ONE BIG ONE
\fancyfoot[LE,RO]{}

bla bla


## Table stuff

| AA   |  BB   |  CC |
| --- |:---:| --- |
|abcabcabcabc  | bb  |  c |
|abc  |bbasdadsa  |  ccc |

### Latex table
\begin{tabular}{l l l}
\hline
Namn & email & telefon \\
\hline
Kenneth & no & 123 \\
Teresa & yes@more.com & 123\-123\-123 \\
\hline
\end{tabular}

## Defs

Apple
:	Pompa do do do

Pear
:	Nästan som äpplen...

Citrus
:	Apelsin, cistrfdksl fjkldsj jfkdlsjf sdlkjf dslkfj jklfdjskl jfdklsjf dslkjf jklj kldfjs klfdjs kljfdskljfklds fdjkf 123 321 321 3213  3213

## footies

Text om [^1] och [^abc] och [^longnote]

\newpage

## mer test

abc abc

### Inline

<div class="footer">
&copy; 2004 Foo Corporation
</div>

[^1]:
	Min lilla fot not nothings to see here

[^abc]:
	Dom tre första bokstäverna i alfabette

[^longnote]: Here's one with multiple blocks.

    Subsequent paragraphs are indented to show that they
	belong to the previous footnote.

    The whole paragraph can be indented, or just the first
    line.  In this way, multi-paragraph footnotes work like
    multi-paragraph list items.

# Image!

![Rör inte](dont-touch.png)

![Rör inte igen!](dont-touch.png){ width=450px }

\newpage

## Mer kod

~~~~ {#mycode .haskell .numberLines startFrom="100"}
qsort []     = []
qsort (x:xs) = qsort (filter (< x) xs) ++ [x] ++
               qsort (filter (>= x) xs)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

| The limerick packs laughs anatomical
| In space that is quite economical.
|    But the good ones I've seen
|    So seldom are clean
| And the clean ones so seldom are comical

| 200 Main St.
| Berkeley, CA 94718
