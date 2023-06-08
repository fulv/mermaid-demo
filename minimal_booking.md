```mermaid
classDiagram
  direction BT

  
  class MINIMAL_BOOKING {
    string uuid
    MINIMAL_CONTACT contact
    bool is_order
    MINIMAL_ITEM item
    MINIMAL_AVAILABILITY availability
    MINIMAL_COMPANY company
  }
  
  class MINIMAL_CONTACT {
  }
  
  class MINIMAL_ITEM {
  }
  
  class MINIMAL_AVAILABILITY {
  }
  
  class MINIMAL_COMPANY {
  }

  MINIMAL_BOOKING --|> MINIMAL : extend
  MINIMAL_CONTACT --|> MINIMAL : extend
```
