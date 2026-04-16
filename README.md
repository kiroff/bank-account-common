# Bank Account Common

Shared DTOs, events, and constants used across the [Bank Account Management System](../README.md).

## Components

- **DTOs**: Shared responses and account types.
- **Events**: Kafka-publishable events for `AccountOpenedEvent`, `FundsDepositedEvent`, `FundsWithdrawnEvent`, and `AccountClosedEvent`.

This module serves as a common dependency for both the `bank-account-command` and `bank-account-query` microservices.
