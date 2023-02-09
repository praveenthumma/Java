# Java 8 Features.
## Memory Changes
- Pre Java 8 metadata about classes is stored in __PermGen__ (Heap Space)
- From Java 8 it is stored in a native Memory called __Metaspace__
- This is not a contiguous Java Heap Memory. It allows for improvements over PremGen space in Garbage collection , auto tuning , concurrent de-allocation of metadata
- 
#
