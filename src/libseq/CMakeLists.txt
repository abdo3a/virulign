SET(SOURCES
    AASequence.cpp
    AlignmentAlgorithm.cpp
    AminoAcid.cpp
    CodingSequence.cpp
    Codon.cpp
    CodonAlign.cpp
    NTSequence.cpp
    NeedlemanWunsh.cpp
    Nucleotide.cpp
)
    
ADD_LIBRARY(seq ${SOURCES})

INSTALL_TARGETS(/lib seq)
INSTALL_FILES(/include .*\\.h)
