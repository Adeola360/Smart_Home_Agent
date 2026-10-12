# Smart Home Agent

A multi-agent smart home system developed in Python that processes sensor data and makes decisions about home security, climate control, and energy usage.

## Features
- **Security Agent:** Detects potential intrusions, unusual motion, and door or window events.
- **Climate Agent:** Uses temperature readings to determine appropriate heating or cooling actions.
- **Energy Agent:** Monitors device usage and identifies potential energy waste.
- **Smart Home Manager:** Routes sensor data to the appropriate agent and records decisions.
- **Database Integration:** Stores sensor readings, device states, agent decisions, system logs, and anomalies.
- **Testing:** Tests agent behaviour, decision rules, and system accuracy.

## Project Structure
- `/agents/` — Python classes for each specialist agent.
- `/manager/` — coordinates agents and routes sensor data.
- `/database/` — SQL schema and database models.
- `/tests/` — test cases for agent functionality and accuracy.
- `main.py` — entry point for running the system.

## Database
The project uses a database to store:
- Sensor readings
- Agent decisions
- Device states
- System logs
- Detected anomalies

See `/database/schema.sql` for the database schema.

## How to Run
1. Install the required dependencies.
2. Run `python main.py`.
3. View system decisions and logs in the console or database.

## Purpose
This project demonstrates:
- Multi-agent systems
- Specialist agents
- Sensor data processing
- Decision-making rules
- Agent coordination and routing
- Database integration
- Logging and testing
