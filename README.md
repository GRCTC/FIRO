# FIRO
Financial Industry Regulatory Ontology

1. Introduction
The present repository contains the Financial Industry Regulatory Ontology (FIRO). This ontology was developed by the Governance, Risk and Compliance Technology Centre to support the knowledge extraction and enhance the knowledge base for its research projects focused on knowledge management systems for regulatory compliance in the financial industry.

2. The Financial Industry Regulatory Ontology (FIRO)

2.1. FIRO-H(ighLevel)
FIRO-HighLevel (FIRO-H) is a core legal ontology about regulatory compliance. It is centred around the concept of Requirement (Rule Statement) and the concept of Action, and defined in OWL.

2.2.FIRO-S(tructure)
FIRO-Structure (FIRO-S) deals with the structure and the semantics of the source document. It accounts for legal and non-legal documents alike. The purpose of FIRO-S is to integrate information from the source text part of Mercury to allow querying, Regulatory Change Management, and reasoning.
FIRO-S relies on LegalDocML for the representation of the structure and the semantics of the legal document. FIRO-S is not formalized in OWL.

2.3.FIRO-D(omain)
FIRO-Domain (FIRO-D) identifies the domain ontologies based on FIRO-H. Each contains one rulebook and the related vocabulary. This means that different rulebooks result in different instances of FIRO-Domain, and any common rule (or vocabulary entry) will be present in all relevant instances. Its possible applications include:
 Extract the rules valid for a particular point in time (exploiting RCM of FIRO-S).
 Classify instances of RegulatoryStatements as exceptions to other RegulatoryStatements.
 Classify BusinessRules as ensuring compliance with LegalRules

2.4.FIRO-P(urpose)S(pecific)
FIRO-PurposeSpecific (FIRO-PS) is the ontology used for performing reasoning towards a specific application. It is a specialization of one or more FIRO-Ds. It may contain Factor instances to represent (either real or fictional) data. Its possible applications include:
 Classify Events (instances of Actions) on the basis of their relation to RegulatoryStatements, as either “relevant”, “complying”, “allowed”, “breaching”, “exempted”.
