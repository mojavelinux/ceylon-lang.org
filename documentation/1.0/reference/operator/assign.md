---
layout: reference
title: '`=` (assign) operator'
tab: documentation
unique_id: docspage
author: Tom Bentley
milestone: Milestone 1
doc_root: ../../..
---

# #{page.title}

The right-associative, binary `=` operator is used to *assign* a value to a `variable`-annotated attribute

## Usage 

<!-- cat: void m() { -->
    variable Integer num = 1; // assign
    num = 2; //assign
    Integer three = 3 // specify
<!-- cat: } -->

## Description

### Specification

If an attribute (or a parameter default) is non-`variable` then it cannot be 
assigned. Instead it is [specified](../../statement/specification) using a 
statement;

### Definition

The `=` operator is primitive.

### Polymorphism

The `=` operator is not [polymorphic](#{page.doc_root}/tour/language-module/#operator_polymorphism). 

## See also

* [`variable`] annotation _doc coming soon_ (../../ceylon.language/variable) 
* [operator precedence](#{page.doc_root}/#{site.urls.spec_relative}#operatorprecedence) in the 
  language specification
