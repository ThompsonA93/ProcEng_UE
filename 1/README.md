# What is a BPMN Collaboration Diagram? 

BPMN Collaboration Diagrams show how two or more processes without a central control interact with each other in synchronized way (how they collaborate).  

The term ''central control'' is key to understanding how to represent processes in a collaboration diagram.  In BMPN, a Pool is used to contain and represent a process that is centrally controlled.  However sometimes one process interacts with another process while each process is controlled by a different governing body.  This commonly happens when one organization’s process is dependent upon information or a delivery of goods from an external organization’s process.  When this happens, each process is shown in its own pool, and the two processes can communicate with one another via Message Flows between pools.  It should be noted that message flows are only used to communicate between pools and not within a pool.

Message Flows are shown as dashed lines with an empty circle showing where the message originates and and empty arrowhead where the message terminates. In contrast, Sequence flows show how the control is directed from one activity to another and are shown as solid lines with filled in arrowheads.  Sequence Flows between activities never cross between pools, since the control of one process does not govern the control of the other process .  You can think of the boundary between pools as an interface in which the messages and their sequence are known, but the internal workings of the other process does not need to be known.

- When only a single pool exists, it is often labeled to reflect the name of the process. However, within a collaboration diagram where multiple pools exist, the label is used to show the participant which manages the control of the process represented within the pool.  
- When multiple pools are shown, it is often the case that the organization that owns one process doesn’t know the inner workings of the other organization’s process.  So, a pool will be shown but the process within it will not.  Instead, only message flows will be shown between the pools.

# What is a BPMN Choreography Diagram
A Choreography diagram is a type of process, but differs in purpose and behaviour from a standard BPMN process. Choreography diagrams define the way business participants coordinate their interactions. So, the focus is not on the work performed, but rather on the exchange of information between involved parties.

Each task ... 
- Consist of at least two participants, an initiating and a non-initiating participants.
- Define messages between the two participants in the task.
