# Retrofitting Security, Module by Module <br/> May 31st, 2019 (Tentative)

&middot; Presented by [Niko Vasilakis](http://nikos.vasilak.is/)

<!-- short bio from Niko's website -->
Speaker Bio (from his website):

    I am currently a Ph.D. Candidate at the University of Pennsylvania, advised by Jonathan M.
    Smith. My work falls under distributed systems, programming languages, and systems security.
    Recently, I've worked on general-purpose distributed environments, automated distribution,
    application compartmentalization, sandboxing of third-party libraries, and distributed storage
    systems. 

    Long-term, I am interested in lowering system complexity—the primary barrier to the scale of
    software systems humans can build and operate. For example, what does it take to make developing
    distributed systems as easy and flexible as ordinary scripting? 

# Abstract
Developers of large-scale software systems use third-party modules to
reduce costs and accelerate release cycles, at a risk to safety and
security. I will introduce a series of techniques that exploit module
boundaries to automate software compartmentalization and enforce
security policies, enhancing safety and security. BreakApp
transparently spawns modules in compartments while preserving their
original behavior. Iris leverages language-based protection to offer
finer-grained control and lower performance overheads. Finally, Mir
uses a constrained read-write-execute protection model to fully
automate compartmentalization.
