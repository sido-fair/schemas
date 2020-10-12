The following FAIR principles have not been implemented (yet) in SHACL:

Principle | Reason
| -- | -- |
F1.B | In concordance with F4, persistence of an identifier is difficult to implement from SHACL.
F4 | Registration in a cental catalog is difficult to implement from SHACL.
A1.1 | Protocol check: we could check for `http(s)://` but not when the URIs are globally unique (i.e. UUIDs). 
I1 | Metadata is already RDF, else SHACL could not check it.
I3 | Relevant references to other (meta)data sets: difficult to generically implement.
R1.3 | Domain relevant standards are not generically implementable.
