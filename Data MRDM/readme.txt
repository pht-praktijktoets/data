Testdata bevat gegenereerde CSV bestanden voor patient, episode en tumor. Allen 1000 regels, precies 1 match voor iedere episode met 1 tumor en 1 patient
R2RML bevat de door KARMA gegenereerde modellen voor omzetten naar triples
RDF bevat de resulterende triples
Ontologie bevat de gebruikte ontologieën. 'DICA ontology.owl' importeert 'Ontology for Clinical Auditing.owl', wat de gezamenlijke ontologie is die ook gebruikt is voor de data van de NHR. Deze importeert weer de BFO ontology die in de andere ontologie-bestanden zitten.

BFO: http://www.obofoundry.org/ontology/bfo.html
In dit geval gebruik ik allen core.owl omdat deze lekker klein is en alles bevat wat ik nodig heb.