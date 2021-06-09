# Visual Sense: Automatically Making Sense of the Visual World

This project aims at integrating a (part of a) resource of annotated images (Visual Genome) in Framester, a linked data knowledge graph that contains factual, linguistic, and visual knowledge.

Firstly, we will extract the schema of Visual Genome as an ontology TBox, and shape its data (ABox) accordingly.

Secondly, we will align the TBox and the ABox to Framester, by using the proximal entities that are contained in both Visual Genome and Framester (mostly, WordNet synsets).

Thirdly, we will generate a "scene ontology" out of Visual Genome, e.g. by exploiting existing relations and frames from Framester, which can be associated with the links existing in the clusters of annotations from Visual Genome.

Visual Genome: https://visualgenome.org/

Visual Genome JSON datasets: https://visualgenome.org/api/v0/api_home.html

Visual Genome API: https://visualgenome.org/api/v0/api_endpoint_reference.html

Framester: https://github.com/framester/Framester

Framester SPARQL Endpoint: http://etna.istc.cnr.it/framester2/sparql

Framester API: http://etna.istc.cnr.it/framester_web/

Framester schema: https://raw.githubusercontent.com/framester/schema/master/ontology.owl

Contents of the repository so far:
- VG Reconstruction folder: contains images of the reconstruction of the underlying model of VG, based on the JSON files that will be queried.
