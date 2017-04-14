---
layout: page
title: Projects
order: 100
group: navigation
description: ""
---
{% include JB/setup %}

## Project Ideas
Here are a list of interesting project ideas. You can also come up with your own ideas as long as it’s related to the deep learning system.

1. FPGA based deep learning: build basic operation blocks for FPGA to support neural network execution on the FPGA.
2. Numerical stable graph optimizer: Given a computation graph, detect the subgraph that could lead to numerical instability, and rewrite the subgraph to avoid this. You can use any existing framework, e.g. [TinyFlow](https://github.com/tqchen/tinyflow) since it’s very simple.
3. Performance / energy profiling: profile an existing deep learning framework, and determine the performance bottleneck in training / testing cases. Or profile the energy consumption on a mobile device for different operations in a neural network, find which operation consumes most energy, and think about how to reduce the energy consumption.
4. Low precision floating point / fixed point support, domain specific languages:  An increasing trend of deep learning is that things are going low precision. We can see emergence of 8-bit computations in GPU as well as customized hardwares(TPU). You can implement a low precision fixed point support for neural network ops.  These ops can either be implemented in existing programming models such as CUDA. You can also explore using domain specific languages or design your simple code generator to generate the code.

## Group Signup
Propose the project ideas, or join an existing project team if that project interests you in this [doc](https://docs.google.com/spreadsheets/d/1GgAhObAIcSJmsMU32X5q0D1oOrRVJDaBuZ1UJNDIXt0/edit?usp=sharing).

## Important Dates

|  Event               |    Date    |
|----------------------|------------|
| Project pitch (3 minutes per team) | April 20th |
| Project proposal due (2 pages) | April 27th |
| Final project presentation and report | June 7th |
