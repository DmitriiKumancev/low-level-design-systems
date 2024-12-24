# Low-Level System Design in Go

Welcome to the **Low-Level System Design in Go** repository! This repository contains various low-level system design problems and their solutions implemented in Go. The primary aim is to demonstrate the design and architecture of systems through practical examples.

## Table of Contents

- [Overview](#overview)
- [Parking Lot System](#parking-lot-system)
- [Elevator System](#elevator-system)
- [Library Management System](#library-management-system)
- [Vending Machine System](#vending-machine-system)
- [Social Media Platform](#social-media-platform)

## Overview

Low-level system design involves understanding the core concepts of system architecture and designing scalable, maintainable, and efficient systems. This repository will try to cover solutions of various problems and scenarios using Go.

## Parking Lot System

coming soon

## Elevator System

The second project in this repository is an Elevator System. This system simulates an elevator control system in a multi-floor building. It demonstrates:

- Multi-Elevator Management: Manages multiple elevators within a single building.
- Request Handling: Processes floor requests and assigns the most suitable elevator based on proximity and current direction.
- Direction Control: Dynamically changes elevator direction based on requests.
- Concurrent Operations: Uses Go routines and synchronization to handle multiple elevator requests simultaneously.

### Features

- Request an elevator from any floor, specifying the desired direction (up or down).
- Assign the nearest elevator to respond to requests.
- Manage elevator movement and optimize direction changes based on requests and destinations.

## Library Management System

coming soon

## Vending Machine System

coming soon

## Social Media Platform

coming soon
  
### Implementation Highlights

- **Concurrency with RWMutex**: Manages concurrent reads and writes to shared data (such as posts and users) to avoid race conditions.
- **Error Handling**: Provides informative error messages for actions such as attempting to interact with nonexistent users or posts.
- **Encapsulation of Features**: Each feature (users, posts, friendships) is encapsulated in a separate manager class, promoting modularity and ease of maintenance.

