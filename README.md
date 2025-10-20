# Automated-performance-testing-pipeline
Automated API testing and performance analysis pipeline using n8n, Spring Boot Swagger, LLM, and K6

This n8n workflow automates:
1. Fetching Swagger API specs from a Spring Boot application.
2. Sending API data to an LLM for intelligent test data generation.
3. Converting generated data into a K6 stress test script.
4. Executing the test and forwarding logs to performance analyzers for reporting.

### Tools Used
- n8n
- Spring Boot (Swagger)
- K6
- OpenAI / LLM
- Online log analyzers

### File
- `api-test-pipeline.json`: Exported n8n workflow.

