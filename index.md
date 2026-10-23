---
layout: default
title: Yemi Bedu
---
# Yemi Bedu
## Software Development

- Algorithms ( Searching - Linear, Binary ) ( Sorting - Bubble, Merge, Quick, Tom ) ( Traversing - BFS, DFS ) ( Merging, Inserting, Removing )
- Data Structures ( Struct, Tuple ) ( Array, List, Set, Queue ) ( Stack, Heap, Allocator ) ( Tree, Trie, Graph, Hash ) ( Map, Table, Dictionary )
- Concepts ( Types, Traits, Kinds, Generics, GADT, Abstractions ) ( Exceptions, Errors, Effects, Capabilities ) ( Polymorphism, Pattern Matching )
- Control Structures ( Block, Closure, Conditional, Loop , Iterator, Task, Channel, Thread ) ( Concurrency, Parallelism, Isolates )
- Meta ( CTE, Template, Macro, Overloading, Reflection, Attribute, Preprocessor, Quote, Splice, Computation Expression )
- Testing ( Unit, Integration, Code Coverage, Reporting )
- Management ( Source Control - Git, Subversion ) ( Integration and Deployment - CI, CD, Packaging, Bundling, Configuration )

## Languages

- HTML, CSS, Javascript ( Jquery, Knockoutjs )
- F#, C#, VB.Net, Dafny, Boo, Nemerle
- Java, Groovy
- Scheme, Ruby, Racket, Lua, Python
- Rust, Nim, Zig, V, D, C, C++, Roc
- Haskell, Idris, Miranda
- Assembly ( Nasm ), SmallTalk ( Pharoah ), Ocaml
- Julia, Koka, Go, Reason, Gleam, Ada, SBCL, Io, Dylan, Carp, Pony, Citrine, Beef, Min, Tao3d

## Tooling

- AI Web - Gemini, Perplexity, Le Mistral, CoPilot, Arc
- AI Local - Jan, LMStudio, pi, Aider, Goose, Zcode, Cline, Warp, Cursor, Codex, Eigent, Omnigent, Stagewise, Msty, Alpaca, Antigravity, Superset
- AI Open - OpenCode, OpenHands, Openwork, OpenPencil, OpenFang
- Editor - Atom, Theia, Zed, Micro, Helix, Emacs, Kate, Brackets, Vim, Geany, Neomacs, Lem
- Visual Studio, Eclipse, Android Studio, Xcode
- Solidworks, OpenScad, Blender, OBS

## Software Systems

- Dotnet Core, JVM
- MS SQL
- Nagios, Zabbix
- VMWare { ESX , ESXi }, Proxmox, XCP-NG, Virtuozzo, oVirt, ZSVirt, Harvester, OpenNode, OpenVZ, Podman, QubesOS
- Vcenter, PegaProx, XCP-Center, XO, Dockge, Dockhand
- ERP ( Infor { Syteline , CSI } )
- EAI EDI ( WebMethods { IS , TN } , Seeburger BIS )
- Lefthand SAN, TrueNAS, OpenMediaVault, ZimaOS, XigmaNas, RockStor, HarborOS

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
