# JMeter Performance Testing Project

## Overview

This project demonstrates performance testing using Apache JMeter. The test plans are designed with HTTP requests directly, not recorded from user sessions. This approach provides greater control over the test scenarios and parameters.

## Project Structure

- **Test Plan**: Contains the test scenarios and their configurations.
- **HTTP Request Samplers**: Used for simulating user requests with custom configurations.
- **Assertions**: Verifies that the responses from the server meet the expected criteria.
- **Listeners**: Provides detailed reports and metrics for analyzing test results.

## Configuration

Before running the tests, you need to configure the server details in the test plan.

1. **Open JMeter**: Launch the Apache JMeter application.
2. **Configure Server Details**:
   - Locate the `HTTP Request` samplers in your test plan.
   - Edit the `Server Name or IP` field to match the address of your server.
   - Update any other relevant fields such as `Port Number` and `Protocol` as needed.

## Components

1. **Assertions**:
   - **Response Assertion**: Verifies specific content in the server's response.
   - **Examples**: 
     - Check if the login page contains a specific welcome message.
     - Ensure that the reservation confirmation page includes details like "Thank you for booking."

2. **Listeners**:
   - **Summary Report**: Provides a summarized view of the test results.
   - **Aggregate Report**: Offers detailed statistics like average response time and throughput.
   - **Assertion Results**: Displays results from assertions to verify that responses meet the expected criteria.

## How to Run the Tests

1. **Open JMeter**: Launch the Apache JMeter application.
2. **Load Test Plan**: Import the JMeter test plan file into JMeter.
3. **Run Tests**: Execute the test plan by clicking the "Start" button.
4. **View Results**: Analyze the results using the configured listeners.

## Requirements

- Apache JMeter 
- Java Runtime Environment (JRE)

## Notes

- Ensure that your test environment is properly set up and configured.
- Review the results and adjust the test plan as needed for thorough performance evaluation.
- The test plans were created using HTTP requests directly, not through recorded sessions, allowing for more precise control over test scenarios.


