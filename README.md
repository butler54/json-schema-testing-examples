# json-schema-testing-examples

This repo contains various test scenarios involving:

1. Schema objects 
2. Theoretically valid json object.
3. Data model code generator and associated objects

The objective is to provide examples simpler than the schemas in [compliance-trestle](https://github.com/IBM/compliance-trestle). This is for debugging 
[pydantic](https://github.com/samuelcolvin/pydantic) and
[datamodel-code-generator](https://github.com/koxudaxi/datamodel-code-generator).

As a result schemas are inspired by [OSCAL](https://github.com/usnistgov/OSCAL)

# Validation strategy
- `jsonschema` (`pip install jsonschema`) was used as an external validator.
