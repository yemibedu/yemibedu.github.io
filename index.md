---
layout: default
title: Yemi Bedu
---
# Yemi Bedu
## Software Development

- Algorithms ( Searching - Linear, Binary ) ( Sorting - Bubble, Merge, Quick, BFS, DFS )
- Data Structures (structs, tuples) ( Array, List, Set, Queue) ( Stack, Heap ) (Tree, Trie, Graph, Hash ) ( Map, Table, Dictionary )
- Concepts ( Exceptions, Errors) (Polymorphism, Pattern Matching)
- Control Structures ( Blocks, Closures, Loops - ( for, while )iterators)
- Testing ( Unit, Integration, Code Coverage, Reporting )
- Management ( Source Control - Git, Subversion ) ( Integration and Deployment - CI, CD, packaging, bundling, configuration )
  
- HTML, CSS, Javascript ( Jquery, knockoutjs )
- F#, C#, VB.Net, Dafny
- Java, Groovy
- Scheme, Ruby, Racket, Python
- Rust, Nim, Zig, V, D, C, C++
- Haskell, Idris, Miranda
- Assembly ( Nasm ), SmallTalk ( Pharoah ), Ocaml
- Io, Julia, Go, Ada, Dylan, Carp, Pony, Reason, Citrine, Beef, Min, SBCL, Tao3d

## Software Systems

- Dotnet Core, JVM
- MS SQL
- 
  
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
