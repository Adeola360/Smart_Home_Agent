# Smart Home Agent

A multi-agent smart home system that processes sensor data and makes decisions about security, climate control, and energy usage.

## Features
- Security Agent: detects intrusions, motion anomalies, and door/window events.
- Climate Agent: decides heating/cooling actions based on temperature.
- Energy Agent: monitors device usage and flags waste.
- Smart Home Manager: routes sensor data to the correct agent and logs decisions.

## Project Structure
- `/agents/` — Python classes for each agent
- `/manager/` — orchestrator that routes sensor data
- `/database/` — SQL schema + database models
- `/tests/` — test cases for Part 4 of the worksheet

## Database
The project uses a relational database to store:
- Sensor readings
- Agent decisions
- Device states
- System logs
- Anomalies

See `/database/schema.sql` for the full SQL schema.

## How to Run
1. Install dependencies  
2. Run `python main.py`  
3. View logs and decisions in the console or database

## Purpose
This project is built for the Python Agents Portfolio Worksheet and demonstrates:
- Specialist agents
- Routing
- Decision rules
- Logging
- Testing and accuracy measurement
