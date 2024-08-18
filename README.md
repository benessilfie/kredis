# GO Project

building an in-memory database like Redis to understand how databases work.

## Objectives
  - Build a Redis clone that allows you to use strings and hashes.
  - Write a parser to understand RESP, which allows the server to receive commands and respond with responses.
  - Use go routines to handle multiple connections simultaneously.
  - Write data to disk using the Append Only File (AOF), which is one of the methods Redis uses for persistence. This way, if the server crashes or restarts, we can restore the data.
