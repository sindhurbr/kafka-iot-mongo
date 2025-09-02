# Kafka → MongoDB (Weekend Learning Project)

## Goal
Simulate “devices” (like routers/switches) sending telemetry (temperature, CPU, etc.) into **Kafka**.  
A Python program (consumer) will:
- Read messages in real-time
- Print alerts if temperature > 80°F
- Save all readings into MongoDB

## Learning Outcomes
- Understand **brokers, topics, partitions** in Kafka
- Learn how **producers** and **consumers** work
- See how Kafka integrates with external systems (MongoDB)

## Data Flow
[ Producer (fake devices) ] → [ Kafka Topic ] → [ Consumer ] → [ MongoDB ]


## Next Steps
1. Add Docker Compose for Kafka (Redpanda) + MongoDB
2. Write a simple producer
3. Write a simple consumer
4. Connect consumer to MongoDB
