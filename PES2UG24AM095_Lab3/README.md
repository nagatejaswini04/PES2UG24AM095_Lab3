# Lab 3 – Component Modelling & Architectural Pattern Selection

**Student:**Naga Tejaswini 
**SRN:** PES2UG24AM095  
**Section:** 5B  
**System:** Self-Service Coffee Kiosk System  
**Selected architecture:** Layered Architecture

## Files
- `Lab3_Architecture_Justification.docx` – architecture selection, rationale, security and performance benefits, components and interfaces.
- `Lab3_Component_Diagram.pdf` – component diagram showing the five components and four interfaces.

## Architecture summary
The system is organised into Presentation, Business and Data layers. The Order Manager coordinates the workflow and communicates with the User Interface, Payment Service, Receipt Printer and Menu Database through IOrder, IPayment, IReceipt and IMenuData.

## Important note
This package adapts the supplied Lab 3 example to the student's details. Review the diagram and document against the official Lab 3 rubric before submission.
