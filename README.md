# E2S.Restaurant

## Objectives
To showcase production-grade software development lifecicle and proof concepts on limited infrastructures.

### Description
This solution is focused to attend multi-station food business.
* Interfaces are function-specific(Main, preparing station, management, deliver, etc).
* When received, a food order is dismembered into it's several individual items for preparation on specific stations. 
* Each station will be aware only about items or services it can provide.
* When preparation is completed, a physical push-button notifies the system about it's readiness.
* When all items are ready,the order is assembled and get ready for deliver.
* The station availability determines product or service availability.
* Stock determines product availability.
* Orders can have time limit to be prepared. Fail to comply with it triggers an alarm on preparing station and main interface, requesting intervention. 
* Stations can have queue threshold. Overflow triggers and alarm requesting intervention. 


## Milestones
- [x] Initial Concept
- [x] Basic low fidelity UX Design
- [x] Basic funcionalities definition
- [x] Kickoff
- [ ] MAUI Interfaces
- [ ] React interfaces
- [ ] Angular Interfaces
- [ ] Services implementation
- [ ] Hardware integration
- [ ] External services integration

> [!CAUTION]
> Not safe for production environment.
