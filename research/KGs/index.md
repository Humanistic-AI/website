# Knowlede Graphs from Text

Formal representations of knowledge, among them Knowledge Graphs (KGs), allow for structured querying, automated reasoning and the interlinking of different knowledge bases. The translation of text corpora into Knowledge Graphs opens the door of these tools into a universe usually reserved for (human) intelligence-based reasoning and querying. This translation can be done manually through annotations or semi-automatically with the help of AI systems that can undertake some level of Natural Language "Understanding". In brief, this research direction is about using intelligent machines to make text processable by structured data processing algorithms. 

## Projects 

* **Project LeGo** (2025-2028) aims to develop record- and entity-linking methods that leverage LLMs. This project also aims at integrating structured data (e.g. tables) into KGs. Partners in the project: CEIICH-UNAM, CIMAT, INER.

* **[Project Angelus](https://seguridad.conahcyt.mx/guerra-sucia/)** (2020-2024) developed methods and software to organize text corpora pertaining enforced disappearance cases during Mexico's "dirty war" period. A demo of this work (publicly available data) can be seen at https://visualizador.humanistic-ai.org/. Partners in the project: CIDE, CIMAT, CNB.


## Software
* [Ontograph](https://codigo.conahcyt.mx/angelus/angelus_anotador) a visualizer of reified RDF graphs.
* [Grontopi](https://codigo.conahcyt.mx/sisdai/sisdai-ciencia-reproducible/angelus_grontopi) a read-only web API that wraps RDF data access into easily.  
* [Ontology API](https://codigo.conahcyt.mx/angelus/angelus_api_ontologia) is a larger-scale web API for reading and writing reified RDF graphs.
* [Annotator](https://codigo.conahcyt.mx/angelus/angelus_anotador) a web app for annotating PDF documents in accordance with an ontology and creating from them reified RDF graphs.
* [Document API](https://codigo.conahcyt.mx/angelus/angelus_api_documentos) an API wrapping document repositories (so far [Dataverse](https://dataverse.org/)) so that it serves PDF documents into the Annotator component.


## Data
* [Angelus Ontology](https://cdn.conahcyt.mx/enis/seguridad-humana/guerra-sucia/archivo/angelus_ontology.owl). An OWL format ontology that guides the different system components, a formalized representation of the domain of State-sponsored enforced disappearance
* [Public KG](https://cdn.conahcyt.mx/enis/seguridad-humana/guerra-sucia/archivo/tripletas_angelus_publico.n3) RDF triples of the publicly available annotations generated during projecto Angelus. A description of this public dataset is available [here](https://zenodo.org/records/7542189).
* [Public set of Documents](https://cdn.conahcyt.mx/enis/seguridad-humana/guerra-sucia/archivo/publicables_angelus2023.zip) (1.3 GB) annotated during project Angelus. A listing of the documents is available [here](https://cdn.conahcyt.mx/enis/seguridad-humana/guerra-sucia/archivo/documentos_angelus_publico.json) as JSON.


## Publications

* Sánchez, M. E. M., & López, T. D. V. (2026). Visualizar la desaparición forzada: grafos de conocimiento para la búsqueda y la verdad. Revista Perfiles Latinoamericanos, 34(67), 63-88. [link](https://perfilesla.flacso.edu.mx/index.php/perfilesla/article/download/1954/1689)
* Mireles V., Sánches Nateras, G., (2024) “Angelus: el sistema que arma rompecabezas para encontrar a personas víctimas de desaparición” en Boletín Conahcyt 5 pp. 13-22. [link](../../pubs/2025_boletin.pdf)
* Project Angelus (2023). User Manual (public version). [link](https://zenodo.org/records/13743411)
* Project Angelus (2022). Annotation Report. [link](https://zenodo.org/records/7552704)
* Project Angelus (2022). Digitalization Report. [link](https://zenodo.org/records/7548893)
* Mireles, V., Sánchez, M. E. M., Winocur, J. Y., & Nateras, G. S. (2021). Buscando a los desaparecidos de la “guerra sucia”: ontologías computacionales y la búsqueda de verdad. Iberoforum. Revista de Ciencias Sociales, 1(1), 1-40. [link](https://iberoforum.ibero.mx/index.php/iberoforum/article/download/149/442)
