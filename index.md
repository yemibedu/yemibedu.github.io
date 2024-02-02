---
layout: default
title: Yemi Bedu
---
# Yemi Bedu
## Software Development

- HTML, CSS, Javascript
- F#, C#, VB.Net, Dafny
- Java, Groovy
- Scheme, Ruby, Racket, Python
- Rust, Nim, Zig, V, D, C, C++
- Haskell, Idris
- Assembly (Nasm), SmallTalk (Pharoah), Ocaml
- Io, Julia, Go, Dylan, Ada, Carp, Pony, Reason, Citrine, Beef, Min, SBCL, Tao3d
  
## Information 

{% for post in site.posts %}

### {{ site.baseurl }}
### {{ post.url }}
### {{ post.title }}
### {{ post.subtitle }} 
### {{ post.date | date: '%Y-%m-%d' }}
### ({{ post.date | date: "%-d %B %Y" }})

{% endfor %}

from markdown
