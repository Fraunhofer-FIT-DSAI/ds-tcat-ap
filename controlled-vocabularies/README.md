# Controlled Vocabularies for Representing Enumerations

- For modeling Enumerations (ENUMs) in semantic metadata schemas (and later using them while instantiating these
  metadata models in the Toolbox's Knowledge Graph), it is preferable use URIs from existing controlled vocabularies (preferably standard-based), instead of plain string literals. For example, use `https://schema.org/Monday` instead of "Monday".
- In case there are no existing vocabularies for a given ENUM-type, new ones can be created and defined under the Dataspaces vocabulary namespace: `http://w3id.org/dataspaces/vocab/`

---

# Existing Controlled Vocabularies and Lookups

## EU Controlled Vocabularies

- The publications office of the EU provides a set
  of [Controlled Vocabularies](https://op.europa.eu/en/web/eu-vocabularies/controlled-vocabularies)
  including [Authority Tables](https://op.europa.eu/web/eu-vocabularies/authority-tables)
  and [Taxonomies](https://op.europa.eu/en/web/eu-vocabularies/taxonomies).
- On the [Authority Tables](https://op.europa.eu/web/eu-vocabularies/authority-tables) page, the 'Filter by' search box can be used to locate the Authority Table of interest (e.g., searching for vocabulary for 'Countries').
- After navigating to the Authority Table of interest - [Countries and territories](https://op.europa.eu/en/web/eu-vocabularies/concept-scheme/-/resource?uri=http://publications.europa.eu/resource/authority/country) - the content browser can be used to filter based on country names (e.g., 'Germany').
- Finally, on
  the ['Germany' concept page](https://op.europa.eu/en/web/eu-vocabularies/concept/-/resource?uri=http://publications.europa.eu/resource/authority/country/DEU)
  , the Concept URI `http://publications.europa.eu/resource/authority/country/DEU` can be copied and used while creating a knowledge graph manually.
- For programmatic access, the portal also provides vocabulary files in RDF format - see
  this [Countries Asset page](https://op.europa.eu/en/web/eu-vocabularies/dataset/-/resource?uri=http://publications.europa.eu/resource/dataset/country)
  for links to such files
  including [countries-skos.rdf](https://op.europa.eu/o/opportal-service/euvoc-download-handler?cellarURI=http%3A%2F%2Fpublications.europa.eu%2Fresource%2Fdistribution%2Fcountry%2F20241211-0%2Frdf%2Fskos_core%2Fcountries-skos.rdf&fileName=countries-skos.rdf)
  .

## Schema.org Enumerations

- Schema.org provides lists or enumerations of things such as [DayOfWeek](https://schema.org/DayOfWeek)
  or [ItemAvailability](https://schema.org/ItemAvailability).
- [This](https://schema.org/Enumeration) index page contains a list of all enumerations.

# New Vocabularies

### [Controlled vocabulary for the Dataspaces Glossary from the DSSC Dataspaces Blueprint v2.0](glossary.ttl)