---
layout: ontology_detail
id: testonto
title: Test Ontology
jobs:
  - id: https://travis-ci.org/cmungall/testonto
    type: travis-ci
build:
  checkout: git clone https://github.com/cmungall/testonto.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: Test Ontology is an ontology...
domain: stuff
homepage: https://github.com/cmungall/testonto
products:
  - id: testonto.owl
    name: "Test Ontology main release in OWL format"
  - id: testonto.obo
    name: "Test Ontology additional release in OBO format"
  - id: testonto.json
    name: "Test Ontology additional release in OBOJSon format"
  - id: testonto/testonto-base.owl
    name: "Test Ontology main release in OWL format"
  - id: testonto/testonto-base.obo
    name: "Test Ontology additional release in OBO format"
  - id: testonto/testonto-base.json
    name: "Test Ontology additional release in OBOJSon format"
dependencies:
- id: po
- id: ro
- id: pato

tracker: https://github.com/cmungall/testonto/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

