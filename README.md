# Order Processing – BPMN Analysis

## Overview

This project presents a BPMN diagram of a sales order process, including order validation, stock availability check, invoicing, and order dispatch.

The process models interactions between customer, sales team, and dispatch team, including alternative flows and exception handling.

## Scope

The diagram covers the end-to-end process:

* Receiving a sales order
* Validating the order
* Checking stock availability
* Handling invalid orders and stock outages
* Packing and dispatching the order
* Sending invoice and customer survey

## Key process elements

### Order validation

* The process includes validation of incoming orders
* If the order is invalid, the customer is informed and the process ends

### Stock availability check

* The system verifies whether the ordered items are available
* If stock is unavailable, the customer is notified

### Order fulfillment

* Valid orders with available stock proceed to:

  * Order packing
  * Dispatch
  * Invoice sending

### Parallel processing

* Invoicing and dispatch can be executed in parallel

### Customer feedback

* After order completion, a survey is sent after a defined delay

## My contribution

* Created BPMN diagram to model business process
* Identified decision points and alternative flows
* Structured the process across multiple actors (customer, sales, dispatch)
* Translated business logic into a visual process model

## Tools used

* BPMN 2.0
* bpmn.io 

## Key learnings

* Modeling end-to-end business processes
* Identifying validation and exception paths
* Designing clear and structured process flows
* Representing parallel and sequential activities


