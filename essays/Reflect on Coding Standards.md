---
layout: essay
type: essay
title: "The Oxford Comma?"
# All dates must be YYYY-MM-DD format!
date: 2025-02-7
published: false
labels:
  - Typescript
  - VsCode
  - ESLint
---

## Oxford Comma?

In case you aren't already familiar, the Oxford comma is an English grammar notation in which a list of items in a sentence are all separated by commas.  Especially, the item after the conjunction such as and.  For example: I love Javascript, ESLInt, and VsCode.  The extra comma helps to solidify the list like nature and the equivalence of all elements.  There are many hilarious examples of the confusion that occurs when the Oxford comma is omitted.  For Example:

<p align="center">
  <img src="../img/Oxford Comma Example.png" alt="Oxford Comma Example">
</p>

This simple example from a website shows how while the reader is able to come to the correct conclusion about what is being said, having the Oxford Comma could have helped to prevent that and improve first read-through clarity.

## Why we should follow suit

I think that coding standards are very similar.  Typescript as a whole seeks to address this in a very serious manner by enforcing and erroring out when variables and functions lack the proper type declarations.  I think that with all things, a product is only as good as its weakest part.  While this analogy is very known I think that many people don't really internalize it.  Coding languages with fancy functional methods and object-oriented programming may seem like good code, but if it can error out simply based on types alone then I'd argue that code is no better than a "Hello World" statement.  From security reasons to just ensuring a well-engineered product the true details of code lie in the little things such as Coding Standards.

I have had experience with linters via C and C++ but I'd say that ESLint with Javascript and Typescript was a significantly different experience.  At least with the linter that we are using, it's very picky by default.  At first, this annoyed me because I felt these things were too trivial to be throwing full-blown red errors on my screen.  But after I read the type of lint error that was thrown I realized that they all had high validity in being there.  After resolving all the lint errors I found that my code not only looked better but also had no fault.  All the types and returns were properly defined.  No extraneous variables were left uncalled.  

The last thing that I can only hypothesize about the benefits of Coding Standards is the ease of readability and comprehension.  Currently, I haven't read enough code or even been in an industry where being able to quickly understand and read code is a vital resource and measurement.  As it was discussed in the class the majority of software engineering work is maintenance and updating.  If a coder has to first understand the type of coding layout the coder used before being able to start understanding the code, much time is wasted and over time leads to major losses in productivity.  

## Conclusion

In the end, following Coding Standards can help with bug prevention, security, and ease of understanding which boosts productivity.  It can also have smaller more subtle benefits as increasing unity amongst all coders who, no matter their line or place of work can feel connected to all programmers who share the language and standards.  We should continue to develop and enforce Coding Standards for all languages so that the quality of coding as a whole can continue to increase.
