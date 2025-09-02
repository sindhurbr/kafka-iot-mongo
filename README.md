# Kafka → MongoDB

## Goal
Simulate “devices” (like routers/switches) sending telemetry (temperature, CPU, etc.) into **Kafka**.  
A Python program (consumer) will:
- Read messages in real-time
- Print alerts if temperature > 80°F
- Save all readings into MongoDB

## Data Flow
[ Producer (devices) ] → [ Kafka Topic ] → [ Consumer ] → [ MongoDB ]
