# MSc Thesis

__Title:__ Modernizing the WebDSL Front-End: A Case Study in SDF3 and Statix

Publicly defended on December 21st, 2022.

__Grade:__ 8.5

__Organization:__ Programming Languages research group, Delft University of Technology (Computer Science)

__Permalink:__ http://resolver.tudelft.nl/uuid:564b8471-631f-4831-a049-58b187425aed

## Abstract

The front-end of a compiler reads the source program and performs analyses such as type checking. The goal of the front-end is to check for the presence of syntactic and semantic errors before the program is passed to the back-end of the compiler for tasks such as optimization and code generation.

WebDSL is a domain-specific language for web programming that is being used for over 15 years. With WebDSL, many applications have been developed which have thousands of daily users. While the language has evolved over the years, the core of its implementation remains unchanged and is starting to show signs of a legacy system. The current WebDSL syntax is defined in SDF2 and all other parts of the compiler are implemented in Stratego.

This thesis presents a modernized front-end of the WebDSL compiler, utilizing the meta-languages of the Spoofax language workbench. Specifically, we introduce a syntax definition of WebDSL in SDF3 that is implemented without the use of post-parse filters, and an executable declarative specification of the WebDSL static semantics in Statix.

We use the modernized front-end as the largest case study to date for the meta-languages SDF3 and Statix, in order to evaluate their expressiveness, performance, and elegance when they are used to implement a real world language.

## Setup

For setup instructions, see from https://github.com/tudelft-pl/master-thesis-template
