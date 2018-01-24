DaFODeL
=======

DaFODeL is short for *Da*ta *F*low *O*bject *De*sign *L*anguage, a visual flow-centric programming language, and is pronounced like "daffodil". 

Data always flows down, Y down length represents "flow rate" or relative processing time in big-O notation, and X across width represents relative data flow size or I/O band-width needed. Data flow object sizes and shapes are always determined by these dimensions, but decorations on the periphery of object hulls can be decorated to visually represent their unique use-cases. Downward directed edge lengths connecting between objects represent expected average network or bus channel latency, and their width represents a direct analog of expected channel bandwidth (always the same or less than the data set being transported, so pinched edges will tend to be longer or slower than uniform width edges).

Colors represent data types or schema mixes, and background rectangular "pages" or soft outlines can be used to represent specific processor I/O (data X width) and per-cycle calculations (processing Y depth) capabilities for a given target platform. Specialized data processors, for example GPU parts with high FLOPS rates, can be represented by pages tinted the same color as their optimal data type, such as "floating point blue".
