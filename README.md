# morphor

[![Crates.io](https://img.shields.io/crates/v/morphor.svg)](https://crates.io/crates/morphor)

### This long-term project is work in progress and does not provide any public functionality yet. Its finalization will take a considerable amount of time. 
 
*morphor* is planned to be both a library and command-line tool for computing with finite-state machines and transducers. Its primary field of application is the morphological processing of natural languages. Computational morphology deals with both the analysis and generation of inflected word forms which is one of the steps needed for helping computers understand natural language.

The main goal of this project is to re-implement the [Foma](https://fomafst.github.io) finite-state compiler and C library in Rust. Foma itself is an extended open-source implementation of the [Xerox Finite-State Toolkit](ftp://ftp.cis.upenn.edu/pub/cis639/public_html/docs/xfst.html).

The current version 0.0.0 acts as a placeholder for hosting on [crates.io](https://crates.io/crates/morphor). As soon as a significant part of Foma has been re-implemented and can be tested, the version will be incremented to 0.1.0.

## References for Interested Readers

- Hulden, M. (2009). [Foma: a finite-state toolkit and library](http://www.aclweb.org/anthology/E09-2008.pdf). Proceedings of the 12th Conference of the European Chapter of the Association for Computational Linguistics: 29–32.
- Hulden, M. (2009). [Finite-State Machine Construction Methods and Algorithms for Phonology and Morphology](http://arizona.openrepository.com/arizona/bitstream/10150/196112/1/azu_etd_10793_sip1_m.pdf). PhD Thesis, University of Arizona.
- Beesley, K. R.; Karttunen, L. (2003). [Finite State Morphology](http://web.stanford.edu/group/cslipublications/cslipublications/site/1575864347.shtml). CSLI-Studies in Computational Linguistics, CSLI-Publications, Stanford, CA, 2003. The book has its own [web site](http://www.fsmbook.com). 