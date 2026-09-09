# 08 — CrownGrid and Event Routing

Consumes: schema.registered, schema.changed, translation.requested, ontology.updated, incompatibility.detected.
Emits: cipher.translation_ready, cipher.mapping_created, cipher.mapping_changed, cipher.incompatibility_detected, cipher.ambiguity_detected.

CrownGrid routes translation capabilities by domain/version.