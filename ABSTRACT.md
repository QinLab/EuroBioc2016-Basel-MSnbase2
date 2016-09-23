## MSnbase2 - disk access is the limited

Laurent Gatto (twitter:lgatt0/github:lgatto) and Johannes Rainer (twitter/github:jotsetung)

The `MSnbase` package has recently been bumped to version 2.0. The
major update that warranted this promotion is the development of a new
back-end to access raw mass spectrometry (MS) data. Previous versions
arduously loaded all the MS spectra into memory. The new back-end
leverages the fast on-disk access from `mzR` and only accesses the raw
data on-the-fly when required, guaranteeing the same but faster
behaviour as the legacy infrastructure and maintaining the same
API. In my talk, I will briefly present the new back-end and benchmark
the in-memory and on-disk implementations.
