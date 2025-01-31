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

The first project in this repository is an Elevator System. This system simulates an elevator control system in a multi-floor building. It demonstrates:

- Multi-Elevator Management: Manages multiple elevators within a single building.
- Request Handling: Processes floor requests and assigns the most suitable elevator based on proximity and current direction.
- Direction Control: Dynamically changes elevator direction based on requests.
- Concurrent Operations: Uses Go routines and synchronization to handle multiple elevator requests simultaneously.

### Features

- Request an elevator from any floor, specifying the desired direction (up or down).
- Assign the nearest elevator to respond to requests.
- Manage elevator movement and optimize direction changes based on requests and destinations.

## Library Management System
The second project in this repository is a Library Management System. This system simulates a library where members can borrow and return books. It demonstrates:

- Singleton design pattern for managing the library instance.
- Book management with support for multiple copies of each book.
- Member management, including borrowing history and borrowing limits.
- Concurrency control to handle multiple borrow and return requests simultaneously.

### Features

- Add and remove books from the library collection.
- Allow members to borrow and return books, with automatic status updates.
- Check book availability and member borrowing quoto limit.
- Maintain a history of borrowed books for each member.

## Vending Machine System

coming soon

## Social Media Platform

The fifth project in this repository is a **Social Media Platform**. This system simulates a basic social media platform where users can connect, create posts, interact with posts, and view activity feeds. It demonstrates:

- **Facade Pattern**: Simplifies user interaction with various social media functionalities (e.g., managing users, posts, friendships) through a unified interface.
- **User and Post Management**: Allows the creation and management of users, posts, comments, and likes, encapsulated in dedicated manager classes.
- **Concurrency Control**: Manages concurrent operations such as posting, commenting, and friend requests using synchronization techniques.
  
### Features

- **User Registration and Profile Management**: Users can register on the platform with profile details, add a profile bio, and edit their information.
- **Posting and Feed System**: Users can create posts and see posts from their friends in their feed.
- **Friendship System**: Users can send and accept friend requests, and posts from friends are included in their feeds.
- **Post Interactions**: Users can like and comment on posts from other users. The number of likes and all comments are viewable on each post.
- **Feed Management**: Users can view a personalized feed of posts from their friends, sorted to display recent posts first.
  
### Implementation Highlights

- **Concurrency with RWMutex**: Manages concurrent reads and writes to shared data (such as posts and users) to avoid race conditions.
- **Error Handling**: Provides informative error messages for actions such as attempting to interact with nonexistent users or posts.
- **Encapsulation of Features**: Each feature (users, posts, friendships) is encapsulated in a separate manager class, promoting modularity and ease of maintenance.

