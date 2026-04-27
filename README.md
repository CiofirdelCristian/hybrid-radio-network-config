# Hybrid Radio Network Configuration

This repository contains the MikroTik RouterOS configuration used in a simulated hybrid communication network based on radio relay and tropospheric links.

## Included Configuration

The repository includes the configuration of the router located in Galati.

This configuration is used as a representative example for the entire simulated network. The other routers are configured in a similar way, with differences only in IP addressing and interface assignments.

## Main Configuration Elements

- IP addressing
- OSPF dynamic routing
- Radio relay links with lower OSPF cost
- Tropospheric links with higher OSPF cost
- Automatic failover mechanism using Netwatch

## Purpose

The configuration demonstrates how a hybrid radio network can maintain communication availability by automatically rerouting traffic when a primary radio relay link becomes unavailable.
