# SystemVerilog-for-Verification-Part-1-Fundamentals

We can categorise datatypes into 3 possible categories.

1] Hardware -  we have two popular datatype in this category
               reg - to use register - when we use procedural assignment statements/blocks, we go with reg datatype
               wire - when we want to connect two blocks or use wires -  when we use continuous assignment statements/blocks, we go with wire datatype  (remember tip: wire == continuous)
But in SV, we use 'logic' datatype, which supports both procedural and continuous assignment blocks/statements.

2] Variable - fixed or floating
