---
layout: reference
title: '`+` (unary plus) operator'
tab: documentation
unique_id: docspage
author: Tom Bentley
milestone: Milestone 1
doc_root: ../../..
---

# #{page.title}

The right-associative, unary `+` operator is used to clarify the positive value 
of its operand.

## Usage 

    Integer one = +1;

## Description

Note that `+` does not change the sign of a negative number:

    Integer minusOne = +(-1);

### Definition 

The `+` operator is defined as follows:

<!-- check:none -->
    rhs.positiveValue;

See the [language specification](#{page.doc_root}/#{site.urls.spec_relative}#arithmetic) for more details.

### Polymorphism

The unary `+` operator is [polymorphic](#{page.doc_root}/reference/operator/operator-polymorphism). 
The meaning of `+` depends on 
[`Invertable`](#{site.urls.apidoc_current}/interface_Invertable.html) interface 

### Meaning of unary plus for built-in types

For the built-in numeric types
[`Integer`](#{site.urls.apidoc_current}/class_Integer.html) and
[`Float`](#{site.urls.apidoc_current}/class_Float.html), `+` 
is essentially a no-op.

## See also

* [`-` (unary minus)](../unary_minus) which does change the sign of its operand
* API documentation for [`Invertable`](#{site.urls.apidoc_current}/interface_Invertable.html)
* [arithmetic operators](#{page.doc_root}/#{site.urls.spec_relative}#arithmetic) in the 
  language specification
* [operator precedence](#{page.doc_root}/#{site.urls.spec_relative}#operatorprecedence) in the 
  language specification
* [Operator polymorphism](#{page.doc_root}/tour/language-module/#operator_polymorphism) 
  and 
  [Numeric operator semantics](#{page.doc_root}/tour/language-module/#numeric_operator_semantics) 
  in the Tour of Ceylon

