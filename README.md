# Kafka Streams – Real-Time Analytics Simulation

## Project Overview

This project demonstrates real-time data processing and analytics using **Apache Kafka and Kafka Streams**. It simulates user page events and processes them through a Kafka Streams application to extract meaningful analytics.

The application filters incoming events based on their duration, groups them by page name, and performs time-windowed aggregations to calculate event counts over specific time intervals.

A simple frontend is integrated to visualize the analytics and provide an overview of the processed data.

## Architecture

The project follows a simple real-time streaming architecture:

1. **Event Simulation:** Generates simulated page events.
2. **Apache Kafka:** Handles event streaming through Kafka topics.
3. **Kafka Streams:** Processes, filters, groups, and aggregates events using time windows.
4. **Frontend:** Displays analytics through a simple visualization interface.

## Technologies Used

- Java
- Spring Boot
- Apache Kafka
- Kafka Streams
- HTML, CSS, JavaScript (Frontend)

## Key Features

- Real-time event streaming simulation.
- Filtering events based on page duration.
- Grouping events by page name.
- Time-windowed aggregations.
- Real-time analytics visualization through a simple frontend.

## Objective

The main objective is to understand stream processing concepts and explore how Kafka Streams can transform continuous event streams into real-time analytics.
