---
title: "Designing a data page"
layout: base

---


When designing a page that explains a list we think it's important to answer the following questions. Each question relates to other questions, but it's useful to think about writing an explanation that can answer them all:

## What sort of things can I use it for?

Is this designed for use in live services that require timely updates? Is it an authoritative source of data?

## What format is it in?

Can I open it in Excel? Do I need to be a programmer?

## How complex is the model?

Is it a single column list or an RDF ontology?


## Does it use any 3rd party / upstream sources?

Does this list consume 3rd party sources and add to them?

## How are new IDs issued

If 3rd party IDs are used, where do they come from? How are new IDs issued? Can anyone create a new row without causing race conditions?

## How do I get hold of it?

API/CURL, log in and place an order for it, ask for a DVD in the post.

## What’s in it?

What are the fields and what do I need to understand them?

## Can I trust it?

What is the commitment to maintain this data? Is the ambition for it to exist at this URL in 5 years? Will anyone else take it no if the backing organisation goes away?

## Are there errors?

Assume there will be errors of some form at some point. It's more important to explain how errors are fixed than pretend it will always be 100% perfect.

## How do I report errors?

An open error reporting process is vital. If the list can be edited directed then this is simple, otherwise provide details of the process and what class of error should be reported.

## Is there a tutorial or example service I can see?

It's helpful to get an idea of how the data can be used.

## What context should I understand about the domain?

How was the data collected? Are there error margins? What were the assumptions? Is there anything the data should not be used for?

## What’s the licence?

This is well documented elsewhere, but explaining it in a clear way is important.

