---
layout: post
title: Introduction
---

There are many frameworks, conceptual and concrete, related to building software. MoVeR (model-view-router) is my particular take on writing enterprise-grade, scalable, iOS applications. You will notice that has been significantly influenced by such popular frameworks as MVP and MVC. In fact, one might say the content contained herein is largely obvious and intuitive - and I don't think you'd be wrong.

## Basics

iOS applications present a few design challenges. I've resolved there there is no silver bullet to application design and so instead, MoVeR attempts to create a simple skeleton upon which to hang your particular situation. An interesting topic to consider might be "how, strategically, does a team manage design complexity - growing it only as necessary, at the last responsible moment and for the optimum cost", but for now, let's save that for another day.

## The Players

Let's consider *typical* application (as you begin to embrace the philosophy, we will ramp up the complexity of a typical but this should be enough to get us started). 

### UIViewController

This is just the UIViewController we've all come to know and love.

### Router

Similar to a Presenter or Controller in other paradigms - the term *Router* is very intentional and we'll see why later.

### Model

There seem to be various definitions of the term Model - so to clarify, MoVeR refers to a non-UI specific representation of the screen. Not a User, not a Document ... a screen (and not a `UIScreen`). One might be tempted to call it a View-Model but the definitions I've seen of that term entail all sorts of other meanings that MoVeR doesn't subscribe to.

### View

Again, this is just a simple UIView. In many cases, this ends up being a sort of parent view of all the contextually significant elements on the screen.

