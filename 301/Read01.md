# Read 01

## Component Based Architecture

## What is a “component”?


    - A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface. A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture. A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.

## What are the characteristics of a component?

    - Reusability, replaceable, not context specific, extensible, encapsulated

## What are the advantages of using component-based architecture?

    - Ease of deployment, reduced cost, ease of development, reusable, modification of technical complexity, reliability, system maintenance and evolution, independent.
    
## What is “props” short for?

“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another, props data is read-only, which means that data coming from the parent should not be changed by child components.

## How are props used in React?

Firstly, define an attribute and its value(data), then pass it to child component(s) by using Props. Finally, render the Props Data

## What is the flow of props?

Props are being passed in a uni-directional flow. (one way from parent to child)
