# express-benchmark

This is a sandbox repo used to benchmark the effects of design decisions on express.js API

## Background

I have found myself considering the peformance implications of implementing prometheus metrics, redis caching, messaging, etc. in the context of an API server. The goal of this repo is to act as a sandbox which will allow me to implement each of these features on a per-API basis, allowing me to profile the response times, and load test using Grafana K6.
