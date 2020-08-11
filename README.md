# Testing Framework for W3ID Namespace definitions for LANDRs.

Tests for LANDRS RDF namespaces defined by [w3id.org](https://w3id.org) persistent identifiers.

Information on best practices and recipes for configura
Based loosely on the Tern Australia [w3id-tern-tests](https://github.com/ternaustralia/w3id-tern-tests) GitHub repository. W3id.org utilizes apache and .htaccess files for 303 redirects to the vocabulary namespace. The W3C has published ["Best Practice Recipes for Publishing RDF Vocabularies"](https://www.w3.org/TR/swbp-vocab-pub/) that give example configuration files and motivation for defining "URI-14" that redirects to a "URL-14" that is an information resource and a URL-200 that is a HTTP URI that is a human readable web resource. A broader explaination can be found in the [OGC SELFIE project report DRAFT](http://docs.ogc.org/DRAFTS/20-067.html). Additional information can be found in the [W3C Dereferencing HTTP URIs](https://www.w3.org/2001/tag/doc/httpRange-14/2007-08-31/HttpRange-14.html) and [W3C Cool URIs for the Semantic Web](https://www.w3.org/TR/cooluris/).

LANDRS also uses [Content-Negotiation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Content_negotiation) to determine an applications preferred representation of a resource and is specified by HTTP headers. It is for this reason [the raw.githack.com](https://raw.githack.com/) is used as the 303 redirect uri to properly return the correct http resource representation.

## Testing Details

## License

This repositiory is licensed unde the MIT License. See: [LICENSE deed](http://github.com/landrs-toolkit/w3id-landrs-test/blob/master/LICENSE).

## Acknowledgements

The Sloan Foundation Grant G-2019-11456 for funding development on data tools for drones.

## Contributors

See the [CONTRIBUTORS file](https://github.com/landrs-toolkit/w3id-landrs-test/blob/master/CONTRIBUTORS.md).

## Contacts

Co-PI:
**Charles F Vardeman II**
Center for Research Computing
University of Notre Dame
<https://orcid.org/0000-0003-4091-6059>
