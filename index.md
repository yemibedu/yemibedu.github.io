---
layout: default
title: Yemi Bedu
---
# Yemi Bedu
## Software Development

- Algorithms ( Searching - Linear, Binary ) ( Sorting - Bubble, Merge, Quick) ( Traversing - BFS, DFS ) ( Merging, Inserting, Removing )
- Data Structures ( Struct, Tuple ) ( Array, List, Set, Queue ) ( Stack, Heap ) (Tree, Trie, Graph, Hash ) ( Map, Table, Dictionary )
- Concepts ( Types, Traits, Generics, GADT, Abstraction ) ( Exception, Error ) ( Polymorphism, Pattern Matching ) ( Concurrency, Parallelism )
- Control Structures ( Block, Closure, Conditional, Loop , Iterator, Task, Channel, Thread )
- Meta ( CTE, Template, Macro, Overloading, Reflection, Attribute, Preprocessor, Quote, Splice, Computation Expression )
- Testing ( Unit, Integration, Code Coverage, Reporting )
- Management ( Source Control - Git, Subversion ) ( Integration and Deployment - CI, CD, Packaging, Bundling, Configuration )
  
- HTML, CSS, Javascript ( Jquery, Knockoutjs )
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
- Nagios, Zabbix
- Proxmox, XCP-NG, OpenVZ, oVirt, OpenVZ

## Hardware Systems

- Rackmount Server, Desktop Computer, Laptop System
- Managed Swtich, IP Camera

  
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
