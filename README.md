## Kafka 7.8.0 Testbed
This is a simple containerized (Docker) Kafka testbed with 3 brokers, KRaft, schema registry, ksqldb, connect, and control center.

## How to Run

1. Verify the Docker daemon is running on your system
2. In the base directory of this project, run the command: `docker compose up --build`
3. Access the control center: http://localhost:9021