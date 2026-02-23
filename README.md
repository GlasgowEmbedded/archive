# Glasgow Archive

This repository contains a permanent archive of all vendor documentation used when implementing the Glasgow protocols, applets, architecture information, and databases.

## Organization

The archive uses a flat structure where each document is assigned a sequential accession number, in the format `G00000`. Then, the document is renamed to have the same filename as its full title and revision, and placed in the directory with the same name as the accession number, for example, `G00001/Vendor® Protocol™ Rev 1.03.pdf`. (It is also acceptable to keep the original PDF filename.) If a newer revision of the same document is later archived, a sequential letter suffix is added to the accession number, in the format `G00000A`. This ensures an exact 1:1 correspondence between numbers and documents.

## Licensing

Vendor documentation is almost never permissively licensed and redistribution of it by third parties is generally tolerated as a customary practice with business benefits. The archive has the goal of redistributing all documentation that was used during development of Glasgow: vendors cannot be trusted to make their documentation available at stable URLs (if at all), so unfortunately we have to do it ourselves.

This repository exists to educate project members on every supported device and protocol, but is separated to insulate the main repository from any takedown requests that may arise. It must **never** be redistributed as a part of a downstream package or similar.

![Slide from a deck for a veterinary course, altered to read: "Handling: General considerations. The vendor is faster and has sharper teeth and nails than you do. It has no 'code of ethics' or considerations for its own future. Underlined: In a fair fight it will win. Action points: 1) DON'T TRUST A VENDOR 2) USE YOUR BRAIN 3) USE DRUGS](vendors.png)
