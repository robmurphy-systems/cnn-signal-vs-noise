# How CNNs See: Signal vs Noise

Most people use AI models.

Fewer understand how they actually *see*.

This project started with a simple question:

**When a model looks at an image… what is it actually paying attention to?**

---

## The Idea

A CNN doesn’t “understand” an image.

It **filters it**.

- Noise gets suppressed  
- Patterns get amplified  
- Certain features start to dominate  

Over time, the model isn’t just learning —  
it’s **deciding what matters**.

---

## What’s Inside

- Baseline ANN vs Transfer Learning (VGG16)
- Why ANN struggles with visual data
- How pretrained models act as feature extractors
- Observation: **feature dominance is real**
- A mental model: *CNNs as signal processors*

---

## The Mental Model

Think of it like tuning a radio:

- Raw image = noisy signal  
- Convolutions = filters locking onto patterns  
- Pooling = removing static  

You’re not losing information —  
you’re **isolating the signal**.

---

## Why This Matters

This isn’t just about computer vision.

It’s about how systems:
- filter noise  
- amplify signal  
- prioritize information  

That pattern shows up everywhere:
AI, systems design, even organizations.

---

## Status

Work in progress — continuing to explore feature behavior and model interpretation.
