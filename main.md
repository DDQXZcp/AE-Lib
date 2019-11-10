```flow
st0=>start: main.h #include "pinDefine.h"

st=>start: Define Robot parameters
add radian_to_rpm convertion, r from action class, maximum speed and reduceSpeed(Remained test)
st1=>start: define structs and index
pointInfo points[2000]; defined in common.h, just position struct
struct position localVelocity, lastError, targetPos, position tolerance, maxSpeed (All are just x,y,w vectors)
Command: defined in the common.h, just a enum type representing different mode
st2=>start: s
st3=>start: s
op=>operation: main.cpp
op1=>operation: ss
op2=>operation: s
op3=>operation: s
e=>end
op4=>operation: s
op5=>operation: s
st0->st->st1->st2->st3->op->op1->op2->op3->op4->op5
​```
```

