Overview of Clone Detection Tools for Java
===========

1. Text
------
| Tool        | Src | Bin | Notes                       | Link 
| ----------- |:---:|:---:|----------------------------:|:-----
| Duplo(c)    | x   | -   | Hashing of strings per line | https://github.com/xsgordon/duplo-fork
| NiCad4      | -   | x   | includes normalization      | http://www.txl.ca/nicaddownload.html
| SDD         | x   | x   | -                           | https://sourceforge.net/projects/sddforeclipse/
| Simian      | -   | x   | -                           | http://www.harukizaemon.com/simian/index.html

2. Token
--------

| Tool        | Src | Bin | Notes        | Link 
| ----------- |:---:|:---:|-------------:|:-----
| CCFinder(X) | x   | x   | Win32, Ubuntu i386, Port for OS X | http://www.ccfinder.net/ccfinderx.html, https://github.com/nicbet/ccfinderx-osx
| ConQAT      | x   | -   | normalized token comparison with suffix-tree | https://www.cqse.eu/en/products/conqat/install/
| CPD         | x   | x   | Part of PMD, Karp-Rabin string matching | https://github.com/pmd/pmd
| CP-Miner    | -   | -   | commercial, maybe on request for evaluation | http://opera.ucsd.edu/Projects/ARTS/CP-Miner.htm
| iClones     | -   | on request | normalized token comparison with suffix-tree | http://www.softwareclones.org/geticlones.php
| JPlag       | x   | x   | greedy string tiling | https://jplag.ipd.kit.edu

3. Tree
--------

| Tool        | Src | Bin | Notes           | Link 
| ----------- |:---:|:---:|----------------:|:-----
| CloneDigger | x   | x   | -               | http://clonedigger.sourceforge.net/download.html
| CloneDR     | -   | -   | commercial      | http://www.semdesigns.com/products/clone/JavaCloneDR.html
| Deckard     | x   | -   | Java <1.5       | https://github.com/skyhover/Deckard

4. Graph
---------
| Tool        | Src | Bin | Notes           | Link 
| ----------- |:---:|:---:|----------------:|:-----
| Scorpio     | x   | -   | PDG-based       | https://github.com/YoshikiHigo/TinyPDG/tree/master/TinyPDG/src/yoshikihigo/tinypdg/scorpio

5. Metrics
----------

