# Nmap Scan Simulation

## Objective

Simulate a reconnaissance attack using Nmap.

## Command used

nmap -sS -T4 scanme.nmap.org

## Expected behaviour

This scan generates multiple TCP SYN packets that could trigger IDS alerts.

## Analysis

Traffic captured using Wireshark and analyzed to observe scanning patterns.
