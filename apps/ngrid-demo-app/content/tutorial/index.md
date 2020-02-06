---
title: Tutorial
path: tutorial
tooltip: Step by step instructions to get started
type: topMenuSection
ordinal: 5
searchGroup: tutorial
---
# Tutorial: Intro to n**Grid**

This tutorial is intended to act as a quick-start guide to using n**Grid** in an Angular application. The techniques 
you'll learn here are the foundations of n**Grid**. When you're done, you should have a good indication as to whether 
or not n**Grid** is the right data table component for your projects.

I> This tutorial is intended for those who **learn by doing**. If you learn best from a progressive, step-by-step 
getting started guide, you've come to the right place. If you prefer to focus on high-level concepts, check out the 
[Concepts](../concepts), [Features](../features), and [Plugins](../plugins) portion of this documentation site.

## What Are We Building?

In this tutorial, we will be building a small Angular application that uses n**Grid** to present tabular data to the 
end-user.  The application will use n**Grid**'s built-in data to simplify the development process (i.e. we will not 
be making a REST API), but we will point out the relevant bits of code that will help you translate this example to 
an application that uses the Angular `HttpClient`.

The final product is not the point of this tutorial. It's just a simple app that renders a table! The true value of 
this tutorial lies in the development journey. As we walk through a progressively more complicated grid, we'll learn 
how to ramp up n**Grid**'s features to match our requirements.

## Prerequisites

This document assumes that you know the basics of [Angular](https://angular.io) and the [Angular CLI](https://angular.io/cli). If you're brand new, you should work through the infamous 
[Tour of Heroes Tutorial](https://angular.io/tutorial) that's authored by the Angular team. This tutorial
will also make use of Angular modules, which are an organizational best practice that results in code-splitting and an easy
to maintain application. Make sure you have a solid understanding of the basics of [Angular Modules](https://angular.io/guide/architecture-modules).
We also assume you know the basics
of `rxjs`, the [Reactive Extensions Library for Javascript](https://rxjs.dev/guide/overview) that is at the core of Angular.
You should have some familiarity with the basics of web development, such as HTML, CSS, and JavaScript. Since we're 
working with an Angular application, we'll also be using [TypeScript](https://www.typescriptlang.org/docs/home.html) throughout this tutorial.
We'll assume you're familiar with common programming constructs such as classes, functions, objects, and arrays. 

If you're not sure you can satisfy all of the prerequisites of this tutorial, go ahead and try to follow along 
with this tutorial anyways. We're here to learn by doing, and I promise we won't break anything.

[Let's get started!](./configuration/create-project#create-a-new-workspace-and-application)
