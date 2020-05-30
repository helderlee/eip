# Remote Procedure Invocation EIP



Pros:

- Business processes rules is taken into account across different applications
- Data encapsulation through a function call interface
- Each application maintains the integrity of own data
- Each application can alter its internal data without having other application be affected
- Easier to deal with semantic dissonance
- Ability to support multiple points of view through multiple interfaces
- Share data and functionality



Cons:

- Awkward to add transformation components, so each application has to negotiate its interface with other systems
- Remote calls can lead to slow and unreliable systems
- Single application model extended to application integration
- Applications are still fairly tightly coupled together
- Difficult to change systems independently
- One application's failure can bring down all of the other applications