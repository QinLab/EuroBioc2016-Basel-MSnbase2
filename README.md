Material for my [2016 European Bioconductor Developer
Meeting](http://scicore.ch/events/eurobioc2016/) talk. 


## `MSnbase2` - disk access is the limit`

Laurent Gatto ([@lgatt0](https://twitter.com/lgatt0)) and Johannes
Rainer ([jotsetung](https://twitter.com/jotsetung))

### [Abstract](https://github.com/lgatto/EuroBioc2016-Basel-MSnbase2/blob/master/ABSTRACT.md)

The `MSnbase` package has recently been bumped to version 2.0. The
major update that warranted this promotion is the development of a new
back-end to access raw mass spectrometry (MS) data. Previous versions
arduously loaded all the MS spectra into memory. The new back-end
leverages the fast on-disk access from `mzR` and only accesses the raw
data on-the-fly when required, guaranteeing the same but faster
behaviour as the legacy infrastructure with the same API, and enabling
the processing of very large datasets. This new infrastructure
underpins proteomics and metabolomics data access using `MSnbase2` and
`xcms3` respectively. In my talk, I will briefly present the new
back-end and benchmark the in-memory and on-disk implementations.

### Talk material

Will come here.


All the material is available under a [Creative Commons
Attribution-ShareAlike 4.0 International
License](https://creativecommons.org/licenses/by-sa/4.0/).
