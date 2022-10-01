# review-guidelines

Attempt at collecting universally applicable review practices to the benefit of product and engineering teams and communities.

## What makes a good review?

In most circumstances:

 - Timeliness
 - Conciseness
 - Constructiveness
 - Correctness
 - Completeness
 - Standards compliance
 
 In some circumstances:
 - Real-timeness
 
### Timeliness
 
#### Why and when it is relevant

In general when pace of progress matters, when time to market (TTM) matters and one is looking to reduce it or keep it low.

Example: in agile software development, reducing time to review can be critical in optimising delivery workflow. In these cases, timeliness of code reviews is of great importance.

#### Examples

```
Bad: Alice is working on an UX design (let's refer to it as A) and submits it for review. Next she starts working on UX design B, which depends on A. Bob takes 2 days to review it and makes 2 optional comments and requests 2 changes. Alice accepts the change requests and the design is approved. Unfortunately, this ends up impacting design B substantially and Alice needs to restart it which means 2 days of wasted efforts.

Good: Alice is working on an UX design (let's refer to it as A) and submits it for review. Next she starts working on UX design B, which depends on A. Bob reviews it within 2 hours and makes 2 optional comments and requests 2 changes. Alice accepts the change requests and the design is approved. Alice is able to adapt her interim progress on design B in line with the changes made to A with minimal effort and continues her work on design B.
```

### Real-timeness
 
#### Why?

#### When it is relevant

#### Examples
$ TODO: Add examples

### Conciseness
 
#### Why it is important?

#### When it is relevant

#### Examples
$ TODO: Add examples

### Constructiveness

Constructive feedback should be encouraging, valuable, practical.
 
#### Why it is important?
Regardless of the nature of the work in review (e.g: product feature, linux kernel) and context (startup, corp, open source community) if/when one is looking for a review of work odds are that person/group is not working in isolation and the review is part of a collaboration effort. Depending on the incentives at stake and the people involved, it's not impossible a non-constructive review contribution will still produce results considered good for the involved parties. More often than not though, that won't be the case.

Reasons that might lead one to want keep their review contributions purely constructive:
 - it generally drives more fluid collaboration flows
 - it makes people receiving the review feedback more engaged and willing to listen to one's ideas
 - it can help build rapport and trust with co-reviewers and author(s) of the work in review

#### When it is relevant
Constructive reviews are particularly important when:
 - one intends to suggest (substantial) changes to the proposed work
 - one's reviewing work authored by people you're likely work again in the future
 - one's reviewing work authored by people who they want to have an harmonious relationship with

#### Examples
Awful: `This is wrong`
Bad: `This addition is wrong because it will introduce a security vulnerability`
Good: `Have you considered security implications of this addition? It will make the system vulnerable to SQL injection. In order to avoid that, the input data should be sanitised. Here's an example: <link to example>`

### Correctness
 
#### Why it is important?

#### When it is relevant

#### Examples
$ TODO: Add examples

### Completeness
 
#### Why it is important?

#### When it is relevant

#### Examples
$ TODO: Add examples

### Standards compliance

This is to say reviews can benefit from being made against standards. In most areas of knowledge, there are often more than one way to solve a problem. Different experiences and perspectives will often generate different ways to solve a problem. That diversity of ideas is useful and should be encouraged.

When it comes to technical/design standards, in the context of team working it might be really important to have consistency. For example, consistency in the way a user journey is built, consistency in the way the supporting coding structures of a system are built. Consistency is important in this setting because it gives teams a productivity framework to work from that if well balanced can significantly increase happiness and help produce better results.

Standards help achieve consistency. In certain contexts this might be more difficult than others. For example, in the coding field Angular is a framework for building web applications. It's usually seen as a competitor to React, although React is a library rather than a framework. Because of their natures and purposes, React ends up giving developers more freedom than Angular - Angular being a complete set of tools vs React being a tool that can be combined with several other tools. This often leads to React projects needing and benefitting more from standardization than Angular. By standardization in this context I mean adopting a common set of guidelines on how to build elements of web applications to produce that consistency that will remove opportunity for bikeshedding (meaning: `the act of wasting time on trivial details while important matters are inadequately attended`).

- [ ] TODO: Add example of built-in standards
- [ ] TODO: Add example of "add-on" standards

#### When it is relevant
Particularly when working in medium or large teams/communities. Usually, the greater the size of the team, the greated the need for standardisation.


## Example of reviews

$ TODO: Embed simulated examples
$ TODO: Link to open source examples
