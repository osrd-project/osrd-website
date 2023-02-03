---
title: Features
linkTitle: Features
description: Features and capabitities
weight: 55
---


## Infrastructure editor
The infrastructure editor enables modifying existing railway infrastructure imported into OSRD or even creating a new infrastructure from scratch.
Geometry, topology and attributes of each infrastructure object can be created, modified and deleted.
For the time being, the following object types are supported : track sections, signals, switches, buffer stops and detectors.

## Short-term train planning
The short-term planning tool allows to add new trains to an existing timetable.
Its algorithm is able to find a train path smoothly integrated into the input timetable while respecting many parameters, such as :
- a time range of departure;
- customizable allowances around the train to mitigate operational hazards;
- allowances management algorithm which minimizes energy usage.
To do so, the proposed train path can take detours and go slower than maximum speed. The proposed solution can bien viewed in the interface.

## Pathfinding
Pathfinding finds the shortest train path between two points anywhere on the tracks network.
It takes account of network constraints : switches, preset routes, traffic direction.
It performs a compatibility check between tracks and the selected rolling stock to respect loading gauge and electrification mode.
It does not take account of other trains.
Result is shown dynamically on the map.

## Simulation

## Conflict detection