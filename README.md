<div align="center">
<img width="250" height="auto" src="https://forum.nes-newlife.de/wcf/image-proxy/?key=f0c867469b101ad75cd2f12f2b055a36eb57b55bdaaa536c7a77576c58b9ae87-aHR0cHM6Ly9pLmliYi5jby9zYndMVFZYL1l1WHRjVDIucG5n" />
</div>

<h3 align="center">The State of San Andreas Administration</h3>

#

### 🔰County(s) 
  
  [`TSDOJ`](https://github.com/NotKaarlo/FivePD-Reports/tree/main/TSDOJ)

#

<div align="center">
<img width="auto" height="130" src="https://justice-ls.xyz/wp-content/uploads/2020/07/doj-vector.png" />
</div>

<div align="center">
  <h3>Members Of San Andreas Supreme Court</h3>

```mermaid
classDiagram
      Agosto Mercati <|-- Frank Bowen
      Agosto Mercati <|-- Arnold McTrevor
      Agosto Mercati <|-- Frederick Herrera
      Agosto Mercati : Chief Justice
      class Frank Bowen{
          Associate Justice
      }
      class Arnold McTrevor{
          Deputy Chief Justice
      }
      class Frederick Herrera{
          Associate Justice
      }
```
</div>

##

### Department Of Justice Log
#### ~~`#444778496112091`~~[^1]. `Closed`
#### ~~`#243142782492362`~~[^2]. `Closed`

[^1]: This Case is closed and is now concluded by Department Of Justice.  
  (Case info at @TSDOJ) (Sign by Douglas James Washington).  
  Closed At `2022-07-26` `18:26`    
[^2]:  Has been paid by the defendant, Fine of `$700`  
  (More info at @TSDOJ) (Sign by Arnold McTrevor)  
  Citation Paid At `2022-07-26` `17:55`  


```mermaid
        gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid

        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d

        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d

        section Documentation
        Describe gantt syntax               :active, a1, after des1, 3d
        Add gantt diagram to demo page      :after a1  , 20h
        Add another diagram to demo page    :doc1, after a1  , 48h

        section Last section
        Describe gantt syntax               :after doc1, 3d
        Add gantt diagram to demo page      : 20h
        Add another diagram to demo page    : 48h
```
