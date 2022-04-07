# Ontology Publication Profile
This is [profile](https://www.w3.org/TR/dx-prof/#definitions) of the [OWL](https://www.w3.org/TR/owl2-overview/), [RDFS](https://www.w3.org/TR/rdf-schema/), [schema.org](https://schema.org) and [SKOS](https://www.w3.org/TR/skos-reference/) ontologies used to define and annotate ontologies. It defines the requirements that data must satisfy to be considered conformant with this profile.

By *profile*, what is meant here is "A specification that constrains, extends, combines, or provides guidance or explanation about the usage of other specifications." (from [PROF](https://www.w3.org/TR/dx-prof/#definitions)) and, here the *other specification*(s) are OWL, RDFS, schema.org and SKOS.

This profile is formulated according to the [Profiles Vocabulary](https://www.w3.org/TR/dx-prof/) and provides [Shapes Constraint Language (SHACL)](https://www.w3.org/TR/shacl/) validator files that can be used to determine whether vocabularies conform to this profile.

This profile is hosted online in [Linked Data](https://www.w3.org/standards/semanticweb/data) form using a persistent web address:

* <https://w3id.org/profile/ontdoc>


## Profile Resources

### Specification
This profile's _specification_ - the resource that contains the normative rules - is within the file [specification.html](specification.html) and it is able to be viewed online at its persistent web location:

* <https://w3id.org/profile/ontpub/specification>

### Validator
This profile's rules, as defined in the _specification_ are presented for machine validation of RDF vocabularies in the shape file [validator.shacl.ttl](validator.shacl.ttl) which conforms to the [SHACL](https://www.w3.org/TR/shacl/) standard.

Tools such as [pySHACL](https://github.com/RDFLib/pySHACL) and the online [SHACL Playground](https://shacl.org/playground/) or [SHACL Play!](https://shacl-play.sparna.fr/play/) can be used with this shape file to validate vocabulary files.

The validator's persistent web location is:

* <https://w3id.org/profile/ontpub/validator>

## License  
This code is licensed using the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licence. See the [LICENSE file](LICENSE) for the deed. 

Note [Citation](#citation) below for attribution.


## Citation
To cite this profile, please use the following (formulated in [BibTex](http://www.bibtex.org/)):

```
@software{ontdoc-profile,
  author = {{Nicholas J. Car}},
  title = {{Ontology Publication Profile}},
  version = {1.0},
  date = {2022},
  publisher = {{Australian Government Linked Data Working Group}},
  url = {https://w3id.org/profile/ontdoc}
}
``` 


## Contact
*publisher:*  
![](style/agldwg-logo-ochre-150.png)  
**Australian Government Linked Data Working Group**  
<https://www.linked.data.gov.au>  

*creator:*  
**Dr Nicholas J. Car**  
*Data Systems Architect*  
SURROUND Australia Pty. Ltd.  
<nicholas.car@surroudaustralia.com>  
<https://orcid.org/0000-0002-8742-7730>
