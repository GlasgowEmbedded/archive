# Glasgow Archive

This repository contains a permanent archive of all vendor documentation used when implementing
the Glasgow protocols, applets, architecture information, and databases.

## Organization

The archive uses a flat structure where each document is assigned a sequential accession number,
in the format `G00000`. Then, the document is renamed to have the same filename as its full title
and revision, and placed in the directory with the same name as the accession number, for example,
`G00001/Vendor® Protocol™ Rev 1.03.pdf`. If a newer revision of the same document is later
archived, a sequential letter suffix is added to the accession number, in the format `G00000A`.
This ensures an exact 1:1 correspondence between numbers and documents.

## Licensing

Vendor documentation is never permissively licensed and often can't be redistributed at all.
Therefore, this repository should *never* be redistributed as a part of Glasgow itself. Similarly,
it is a separate repository to avoid availability issues in case of a takedown notice.

The archive nevertheless has the goal of redistributing all documentation that was used during
development of Glasgow. Vendors, in general, cannot be trusted to do anything right, especially
not making their documentation continuously available. We have to do that ourselves, often in
an adversarial way. That is just the unfortunate fact of life.
