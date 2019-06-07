# ASE URL Routing Exercise

## Deck Agenda

- Intro on Request Routing
  - ENV changes from the MicroService Exercise
    - New dockerfile, services exposed externally
    - Accessing the app through the BIG-IP (ie. it is acting as the router)
- iRules
  - General Intro
    - events, commands
    - conditionals, switches
    - data groups
- OneConnect aside
  - importance of serverside detachment. Whiteboard this.
- iRules Lab
  - Deploy and explore some example rules
    - Bad rule
    - slightly better rule
    - data group based rule
  - Build the datagroup necessary for the last rule
    - test
- Local Traffic Policies
  - general intro, history
  - walk through concepts
    - drafts
    - match policy
    - rules
    - operands and actions
- LTP Lab/Exercise
  - Build the necessary LTP rules necessary to handle routing for the application
  - Test
- LTPs and ASM policies
 - Build/modify your existing local traffic policy to only attach to the /api endpoint.


## TBD

### Final/Answers
1. First exercise declaration with records
2. Second exercise declaration with LTP from 3rd exercise
3. Third is done.

Build a simple guide

Need the following:


