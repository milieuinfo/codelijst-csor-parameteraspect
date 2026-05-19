# codelijst-csor-parameteraspect

Codelijst van parameteraspecten voor het **Chemische Stoffen en Omgevingsparameters-Register (CSOR)**, gepubliceerd als Linked Data via het Omgevingsdata-platform van de Vlaamse overheid.

## Inhoud

Een parameteraspect is de combinatie van een **parameter** (bv. een chemische stof of omgevingsparameter) en een **kwantificeerbaar aspect** (bv. massaconcentratie, vracht, massa per filter). De codelijst bevat ruim **5.300 parameteraspecten** die worden gebruikt bij milieu- en omgevingsmetingen in Vlaanderen.

Elk concept is gemodelleerd als `csor:ParameterAspect` en `skos:Concept`, en verwijst via:

- `csor:heeftParameter` naar de bijbehorende parameter
- `csor:heeftAspect` naar het kwantificeerbaar aspect
- `skos:prefLabel` voor de Nederlandstalige benaming

## Beschikbare formaten

De codelijst wordt aangeboden in drie RDF-serialisatieformaten:

| Bestand | Formaat |
|---|---|
| `parameteraspecten.ttl` | Turtle |
| `parameteraspecten.nt` | N-Triples |
| `parameteraspecten.rj` | RDF/JSON |

De bestanden bevinden zich in:

```
src/main/resources/be/vlaanderen/omgeving/data/id/conceptscheme/csor/parameteraspect/
```

## Gebruikte namespaces

| Prefix | Namespace |
|---|---|
| `csor` | `https://data.omgeving.vlaanderen.be/ns/csor#` |
| `skos` | `http://www.w3.org/2004/02/skos/core#` |
| `iadopt` | `https://w3id.org/iadopt/ont/` |
| `qudt` | `http://qudt.org/schema/qudt/` |
| `dcterms` | `http://purl.org/dc/terms/` |

## Concept scheme URI

```
https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/parameteraspect
```

Named graph (Virtuoso): `https://data.omgeving.vlaanderen.be/id/graph/codelijst-csor-parameteraspect`

## Licentie

GNU General Public License v3.0 — zie [LICENSE](LICENSE).
