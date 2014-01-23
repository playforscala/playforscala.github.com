---
title: Errata
---


# Errata

This page lists errata for [Play for Scala](http://manning.com/hilton/), first edition (October 2013).

## Chapter 1


## Chapter 2


## Chapter 3


## Chapter 4


## Chapter 5


## Chapter 6


## Chapter 7

Section 7.4.6, page 192. The sentence 

> The keys of the data that you bind to this form are of the form `main_contact.name`, `main_contact.email`, then `technical_contact.text`, `technical_contact.email`, and finally `administrative_contact.text` and `administrative_contact.email`."

should be

> The keys of the data that you bind to this form are of the form `main_contact.name`, `main_contact.email`, then `technical_contact.name`, `technical_contact.email`, and finally `administrative_contact.name` and `administrative_contact.email`."


## Chapter 8


## Chapter 9


## Chapter 10

Section 10.4.1, page 287. The question mark (?) in the sentence 

> BodyParser is a trait that extends (RequestHeader) ? Iteratee[Array[Byte], Either[Result, A]].

should be a Unicode “RIGHTWARDS DOUBLE ARROW” (⇒)  or, alternatively the ASCII equivalent (=>)

> BodyParser is a trait that extends (RequestHeader) ⇒ Iteratee[Array[Byte], Either[Result, A]].
