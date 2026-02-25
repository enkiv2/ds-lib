ds-lib is a collection of small python and simple implementations data structures, algorithms, or services for which there are no readily-available open source implementations easily understood by beginners. They are intended to be instructive, rather than useful, and have not been thoroughly tested.

With the exception of the ZigZag-related code ([ZZCell](ZZCell.py), [kaukatcr](kaukatcr.py), and [ZZFE](ZZFE.py)), all files are independent and self-contained.

# The files

Xanadu(tm)-related:

* [Enfilade](Enfilade.py): implementation of a generic [Enfilade](http://en.wikipedia.org/wiki/Enfilade_%28Xanadu%29), a derivatve of the Rope
* [ZZCell](ZZCell.py): implementation of a [ZZStructure](http://en.wikipedia.org/wiki/ZigZag_%28software%29), a network with colored edges
* [Kaukatcr](kaukatcr.py): a zigzag-based programming language, as described [here](https://hackernoon.com/kaukatcr-an-experiment-in-language-design-for-multi-dimensional-spaces-cc038caafff9)([mirror](http://www.lord-enki.net/medium-backup/2018-04-12_Kaukatcr--an-experiment-in-language-design-for-multi-dimensional-spaces-cc038caafff9.html))
* [ZZFE](ZZFE.py): a minimal front end for ZZCell, using TKInter
* [SpanOps](SpanOps.py): various miscellaenous operations for dealing with spanpointers -- specifically useful with EDL-based document formats
* [OSMIC](osmic.py): a forking revision tree

Misc:

* [ChordRouting](ChordRouting.py): implementation of [chord-style routing](http://en.wikipedia.org/wiki/Chord_%28peer-to-peer%29#Overview), wherein hash similarity is used to generate stable paths in distributed content-addressable file storage
* [Gopher](gopher.py): a simple server for the gopher protocol
* [LRTC](lrtc.py): Low Resource Text Classifier, based on [Jiang, et al. (2023)](https://aclanthology.org/2023.findings-acl.426/)

