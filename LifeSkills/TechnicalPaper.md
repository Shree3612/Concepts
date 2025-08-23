# Event Sourcing Architecture

## Definition : 

- Event Sourcing means keeping a record of every change or event that occurs, rather than only saving the final result. It is extremely helpful in investigating the past states of a complex workflow.

## Core Concept :
- Event Sourcing forms a complete history of what happened to your data over the time.
- It is like maintaining a diary or a journal of everyday tasks that we had performed on the system.
- It not only helps to document the changes efficiently but also helps in the Root cause analysis when the system crashes.
- The last working state of the system can be achieved by replaying these events.


## Benefits/Advantages:
- **Auditability** → Keep track of each and every change

- **Temporal Queries** → Check previous state of system at any given time

- **Flexibility** → Create multiple custom views

- **Scalability** → Handle large scale systems

- **Reliability** → Data is safe and durable

## Applications 
1. **Financial Systems** → Track all transactions for prevention of fraud.

2. **E-commerce Platforms** → Proper monitoring of orders, payments, and inventory changes  

3. **Audit Logging and Compliance** → Maintain clear and unchangeable records  

4. **Collaborative and Multi-User Systems** → Record changes made by each user over time  

5. **Real-Time Data Processing and Analytics** → Process events instantly for quick analysis.  


9. **Undo and Replay Functionality** → Roll back to earlier user actions  

10. **CRM Systems** → Record complete history of customer interactions  

11. **Telemetry and Logging Systems** → Store all logs for Root Cause analysis when required.  


## Reference
- [GeeksForGeeks] (https://www.geeksforgeeks.org/system-design/event-sourcing-pattern/)
- [Medium.com] (https://medium.com/@alxkm/event-sourcing-explained-benefits-challenges-and-use-cases-d889dc96fc18)
