Overview of Clone Detection Tools for Java
===========

1. Text-based
------
| Tool        | Src | Bin | Notes                       | Link 
| ----------- |:---:|:---:|----------------------------:|:-----
| Duplo(c)    | x   | -   | Hashing of strings per line | https://github.com/xsgordon/duplo-fork
| NiCad6      | -   | x   | includes normalization      | https://www.txl.ca/txl-nicaddownload.html
| SDD         | x   | x   | -                           | https://sourceforge.net/projects/sddforeclipse/
| Simian      | -   | x   | -                           | http://www.harukizaemon.com/simian/index.html

2. Token-based
--------

| Tool        | Src | Bin | Notes        | Link 
| ----------- |:---:|:---:|-------------:|:-----
| CCFinder(X) | x   | x   | Win32, Ubuntu i386, Port for OS X | http://www.ccfinder.net/ccfinderx.html, https://github.com/nicbet/ccfinderx-osx
| ConQAT      | x   | x   | normalized token comparison with suffix-tree | https://www.cqse.eu/en/products/conqat/install/
| CPD         | x   | x   | Part of PMD, Karp-Rabin string matching | https://github.com/pmd/pmd
| CP-Miner    | -   | -   | commercial, maybe on request for evaluation | http://opera.ucsd.edu/Projects/ARTS/CP-Miner.htm
| iClones     | -   | on request | normalized token comparison with suffix-tree | http://www.softwareclones.org/geticlones.php
| JPlag       | x   | x   | greedy string tiling | <https://github.com/jplag/JPlag>

3. Tree-based
--------

| Tool        | Src | Bin | Notes           | Link 
| ----------- |:---:|:---:|----------------:|:-----
| CloneDigger | x   | x   | -               | http://clonedigger.sourceforge.net/download.html
| CloneDR     | -   | -   | commercial      | http://www.semdesigns.com/Products/Clone/JavaCloneDR.html
| Deckard     | x   | -   | Java 7       | https://github.com/skyhover/Deckard

4. Graph-based
---------
| Tool        | Src | Bin | Notes           | Link 
| ----------- |:---:|:---:|----------------:|:-----
| Scorpio     | x   | -   | PDG-based       | https://github.com/YoshikiHigo/TinyPDG/tree/master/src/main/java/yoshikihigo/tinypdg/scorpio
