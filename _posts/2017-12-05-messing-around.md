---
published: true
---
## Messing around

Trying out the features of github pages.


```xml
<payloadFactory media-type="xml">
  <format>
    <Employees xmlns="http://ws.wso2.org/dataservice">$1</Employees>
  </format>
  <args>
    <arg evaluator="xml" expression="//*[local-name()='Employees']" />
  </args>
</payloadFactory>
```

```java
@Override
public String toString() {
  return axis2message.getSoapEnvelope();
}
```

