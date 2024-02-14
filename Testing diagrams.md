# md diagrams using mermaid. 
An example with a simple flow chart
```mermaid
graph TD;
    A-->B
    A-->C
    B-->D
    C-->D
```
An more advanced example 
- kewords for flow charts
    - st for start
    - op for operation
    - cond for conditon
    - e for end 
```flow
st=>start: Beginning
op=>operation: Ready?
cond=>condition: Yes og  No?
e=>end
```