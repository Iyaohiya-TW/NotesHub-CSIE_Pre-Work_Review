# Overview on Game Developer Common Topics / Must-Know Concepts

### Tier Standard

**Tier 1** – Almost Every Game Developer Should Review

**Tier 2** – Frequently Asked Depending on Position

**Tier 3** – Specialized Fields

**Tier 4** – Project Evaluation

**Tier 5** – Engineering Thinking

***

# Tier 1

These are the topics expected from almost every gameplay, engine, tools, or general game programmer.

***

# 1. Programming Fundamentals

## Core Topics

Variables

Data Types

Functions

Scope

Recursion

Arrays

Strings

Pointers / References

Memory Management

Object-Oriented Programming

Interfaces

Generic Programming

Lambda / Delegates (language dependent)

Exception Handling

Const Correctness

Static vs Dynamic Allocation

Resource Lifetime

***

# 2. Data Structures

### Common Topics

Array

List

Linked List

Stack

Queue

Hash Table

Dictionary / Map

Set

Binary Tree

Heap

Graph

Spatial Partition Structures

(Common examples)

-   Quad Tree
    
-   Octree
    
-   BSP Tree
    

Common Considerations

Insertion

Deletion

Traversal

Search

Cache Friendliness

Memory Usage

Time Complexity

When to choose each structure

***

# 3. Algorithms

### Common Topics

Searching

Linear Search

Binary Search

Sorting

Quick Sort

Merge Sort

Heap Sort

Graph Algorithms

DFS

BFS

A*

Dijkstra

Navigation Mesh Concepts

Optimization

Greedy

Divide and Conquer

Dynamic Programming (basic understanding)

Complexity Analysis

Big O

Big Theta

Big Omega

***

# 4. Mathematics for Games

This is surprisingly one of the most common interview topics.

### Core Topics

Vectors

Dot Product

Cross Product

Magnitude

Normalization

Matrices

Coordinate Systems

Local vs World Space

Transformation

Rotation

Quaternion Basics

Interpolation

Linear Interpolation (Lerp)

Slerp

Trigonometry

Basic Physics Equations

Collision Mathematics

Distance Calculation

Raycasting

Bounding Volumes

***

# 5. Game Engine Fundamentals

### Common Topics

Game Loop

Frame Update

Fixed Update

Scene Management

Game Object Lifecycle

Component-Based Architecture

Entity Component System (basic)

Resource Management

Asset Pipeline

Serialization

Prefab / Blueprint Concepts

Game State Management

Input System

Camera System

Animation State Machine

Audio System

***

# 6. Debugging & Optimization

One of the highest priority subjects for senior developer.

### Common Topics

Reading Stack Traces

Breakpoints

Watch Variables

Call Stack

Logging

Assertions

Memory Leak Detection

Profiling

CPU Profiling

GPU Profiling

Frame Debugging

Performance Bottlenecks

Race Conditions

Null Reference Bugs

Floating Point Precision

Optimization

Allocation Reduction

Garbage Collection

Cache Locality

Object Pooling

***

# 7. Software Engineering

## Common Topics

Git

Branching

Merge

Conflict Resolution

Version Control

Coding Style

Code Review

Design Principles

SOLID

DRY

KISS

YAGNI

Testing

Unit Testing

Regression Testing

Continuous Integration

Agile

Scrum

Documentation

***

# 8. Object-Oriented Design & Design Patterns

## Core Topics

Encapsulation

Inheritance

Composition

Polymorphism

Abstraction

Dependency Injection

SOLID

Patterns

Factory

Singleton

State

Observer

Strategy

Command

Component Pattern

Event System

Service Locator

Builder

Decorator

Adapter

When each pattern is appropriate

***

# Tier 2

Frequently asked depending on the studio or role.

***

# Physics

Rigid Body

Collision Detection

Collision Response

Raycasting

Triggers

Character Controller

Continuous Collision

Physics Materials

Constraints

***

# Graphics Programming

Rendering Pipeline

Rasterization

Shaders

Vertex Shader

Fragment Shader

Lighting

Shadow Mapping

Texture

Material

Post Processing

GPU Basics

Draw Calls

Instancing

***

# Computer Graphics Mathematics

Projection

View Matrix

Model Matrix

Perspective

Orthographic Camera

Frustum

Back-face Culling

Depth Buffer

***

# Computer Organization

CPU

GPU

Memory Hierarchy

Cache

Instruction Pipeline

SIMD

Multithreading Basics

Performance Bottlenecks

***

# Operating System

Thread

Process

Synchronization

Mutex

Semaphore

Deadlock

Scheduling

Virtual Memory

File System Basics

***

# Networking (Multiplayer)

TCP

UDP

Client-Server

Peer-to-Peer

Latency

Prediction

Interpolation

Rollback

Replication

State Synchronization

Packet Loss

Bandwidth Optimization

***

# Asset Pipeline

Import Pipeline

Textures

Meshes

Animation

Compression

Serialization

Addressable Assets

Build Pipeline

Packaging

***

# Scripting

Lua

Python

C#

Visual Scripting

Embedding Scripting Languages

Reflection

***

# Linux (Optional)

Mostly relevant for engine or server positions.

Command Line

Permissions

Shell

SSH

Process Management

File System

***

# Database

Generally not required for gameplay programmers.

Review only:

Basic SQL

SELECT

INSERT

UPDATE

Primary Key

Index

Transactions

Typical Uses

Player Data

Leaderboards

Backend Services

Save Systems

Cloud Storage

**Skip** advanced normalization, query optimization, and database administration unless you're targeting backend or live-service roles.

***

# Tier 3

Depends heavily on specialization.

***

# Engine Programming

Memory Allocator

Job System

Renderer

Scene Graph

Reflection

Serialization

Resource Streaming

Custom ECS

Platform Layer

Build System

***

# AI Programming

Finite State Machine

Behavior Tree

GOAP

Navigation Mesh

Pathfinding

Steering Behaviors

Utility AI

Decision Making

***

# Gameplay Programming

Gameplay Systems

Abilities

Inventory

Quest System

Dialogue

Combat

Save System

Input Architecture

***

# Tools Programming

Editor Extension

Pipeline Automation

Importer

Exporter

Custom Inspector

Asset Validation

Build Automation

***

# Audio Programming

DSP

Spatial Audio

Mixing

Streaming

Latency

***

# Mobile Development

Battery Optimization

Touch Input

Memory Constraints

GPU Constraints

Platform SDK

***

# VR / AR

Tracking

Motion Controllers

Stereo Rendering

Performance Constraints

Comfort Design

***

# Cloud / Online Services

Steamworks

PlayFab

Epic Online Services

Firebase

Authentication

Achievements

Cloud Save

Matchmaking

Dedicated Servers

***

# Cybersecurity

Only basic knowledge is usually needed.

Authentication

Encryption

Hashing

Cheat Prevention

Secure Save Data

***

# Tier 4 — Project Evaluation

This is where many studios spend most of the interview, especially for junior candidates.

## Architecture & Design

-   Explain your game's architecture.
    
-   Why did you choose this engine (Unity, Unreal, Godot, etc.)?
    
-   How are responsibilities divided between systems?
    
-   Why did you choose a specific design pattern?
    
-   If you had to support multiplayer, what would you change?
    

## Implementation

-   Walk through your most complex feature.
    
-   How does your save/load system work?
    
-   How did you implement AI?
    
-   How did you structure player movement?
    
-   How do different game systems communicate?
    

## Debugging & Optimization

-   Describe the hardest bug you fixed.
    
-   How did you identify the root cause?
    
-   What tools did you use?
    
-   How did you optimize performance?
    
-   Did you ever profile your game?
    

## Teamwork

-   How did you use Git?
    
-   How were merge conflicts resolved?
    
-   What role did you play?
    
-   How did you review teammates' code?
    
-   How did you divide work?
    

## Reflection

-   What would you redesign?
    
-   What technical debt exists?
    
-   Which system are you most proud of?
    
-   What did you learn from the project?
    

***

# Tier 5 — Engineering Thinking

Studios also evaluate how you solve problems and collaborate.

## Problem Solving

-   How do you approach a feature you've never implemented before?
    
-   How do you isolate the source of a bug?
    
-   How do you compare multiple technical solutions?
    
-   How do you estimate implementation time?
    
-   When do you optimize, and when do you avoid premature optimization?
    

## Communication

-   How do you explain technical issues to designers or artists?
    
-   How do you give constructive feedback during code reviews?
    
-   How do you document systems for teammates?
    

## Learning

-   How do you learn a new engine or API?
    
-   How do you evaluate third-party libraries?
    
-   How do you verify that information from online resources is correct?
    

***

# AI Suggestion

### Subject Priority (Gameplay Programmer)

If I had to rank these by importance for a **general gameplay programmer** interview, I'd suggest:

| Priority | Subject |
| --- | --- |
| ⭐⭐⭐⭐⭐ | Programming Fundamentals |
| ⭐⭐⭐⭐⭐ | Debugging & Optimization |
| ⭐⭐⭐⭐⭐ | Game Engine Fundamentals |
| ⭐⭐⭐⭐⭐ | Mathematics for Games |
| ⭐⭐⭐⭐☆ | Data Structures |
| ⭐⭐⭐⭐☆ | Object-Oriented Design & Design Patterns |
| ⭐⭐⭐⭐☆ | Software Engineering (Git, teamwork, code quality) |
| ⭐⭐⭐⭐☆ | Algorithms |
| ⭐⭐⭐☆☆ | Physics |
| ⭐⭐⭐☆☆ | Graphics Programming (basic pipeline understanding) |
| ⭐⭐☆☆☆ | Operating Systems |
| ⭐⭐☆☆☆ | Computer Organization |
| ⭐⭐☆☆☆ | Networking (unless multiplayer-focused) |
| ⭐☆☆☆☆ | Database |
| ⭐☆☆☆☆ | Linux (unless engine/server/tools roles) |

I think this ordering better reflects what studios such as Ubisoft, Capcom, Bandai Namco, Riot, Blizzard, and many indie studios tend to value. Junior game programmer interviews often revolve around **your projects**, your understanding of **engine architecture**, your ability to **debug and optimize**, and your grasp of **math for games**, with traditional CS topics serving as supporting knowledge rather than the primary focus.