# Web Data

The _Web Data Principles_ is a simple set of guidelines of how to make structured information more useful on the Web. The main idea of _Web Data_ is that it is a set of principles and patterns, and not a specific set of technologies. As such, it is more liberal than the [5-star model of Linked Data](http://5stardata.info/), which makes specific statements about required technologies.


## One Star: Linkable

Documents need to have stable and discoverable global identifiers. Stability is required so that links to your document can be used as unique and global identifiers. Discoverability is required so that your documents can be found by others who want to link to them.

If applicable, web data should also allow linking to document fragments, so that links can be more specific than just linking to URI-identified resources. If the media type you're using supports explicit fragment identifiers, have a stable and documented way how you assign and manage identifiers, so that fragment identification is as robust as resource identification.


## Two Star: Parseable

Documents should use standardized data metamodels such as CSV, XML, RDF, JSON, so that they can be easily parsed by consumers. Proprietary metamodels and formats need proprietary code for parsing, and thus are harder for consumers to process.


## Three Star: Understandable

Documents should use well-known or at least well-documented vocabularies/schemas, so that after parsing, interpreting the documents is possible and well-defined. At the very least, the vocabulary/schema must make it possible to discover links in documents, so that consumers can find and follow them.


## Four Star: Linked

For your Documents to be a part of the Web, they should link to other documents whenever possible. Always use global identifiers when linking between documents, so that link identifiers can be taken out of context and shared globally.


## Five Star: Usable

Label your document with a license, so that others know how they can use it. There are many licenses to choose from, and picking any one of those is better than not picking one at all.

