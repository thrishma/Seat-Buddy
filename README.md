# Seat Buddy

Seat Buddy is a simple simulator that helps you understand what your view at a concert or event might look like before you buy a ticket.

Many people buy event tickets only to realize later that their view of the stage is blocked by taller people in front of them. Seat Buddy simulates this scenario by considering your height and the crowd around you to estimate whether the stage will be visible.

This project was built as a **Lovable project**, rapidly prototyped using AI-assisted development to go from idea to working demo quickly.

## Demo

https://stage-view-buddy.lovable.app

## Problem

Buying tickets for concerts, festivals, and live events can be risky. Seat maps rarely tell you what your actual view will be like once people are standing in front of you. A seat that looks good on paper can easily become a blocked view in reality.

## Solution

Seat Buddy allows users to simulate their view based on:

- Your height
- Average height of people around you
- Crowd density
- Distance from the stage

The simulator visually approximates whether the stage will be visible or obstructed.

## Features

- Stage view simulation
- Crowd height and density adjustments
- Height-based visibility estimation
- Quick preview of potential obstructions
- Lightweight web interface

## How it Works

The simulator estimates visibility using basic geometric assumptions about:

- Eye level
- Line of sight
- Crowd height distribution
- Distance to the stage

It then renders a visual approximation of what the stage might look like from that perspective.

## Tech Stack

- Frontend: React
- Prototype builder: Lovable
- Visualization: Browser-based rendering

## Future Improvements

- Real venue seat map integrations
- Crowd height distribution modeling
- 3D venue simulation
- Ticket platform integrations
- Mobile version

## Why I Built This

I built Seat Buddy after realizing how often people end up with blocked views at concerts. The goal was to create a quick tool that helps people estimate their real experience before purchasing tickets.


DEMO: https://github.com/user-attachments/assets/127fb67e-61b1-411d-a584-fb8bb3e6b156



