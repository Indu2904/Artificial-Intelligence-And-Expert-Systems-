EXP-1 START
Initialize Queue with start node
Mark start as visited

WHILE Queue not empty:
  Remove node from Queue
  Print node

  FOR each neighbor:
    IF not visited:
      Mark visited
      Add to Queue
STOP
