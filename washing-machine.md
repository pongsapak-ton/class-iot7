![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301020/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301020",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301020/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301020",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "firmware",
    "value"     : "wash10322"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301020/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301020",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "location",
    "value"     : "Bangbon5"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/get/6310301020/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301020",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "geo-location",
    "value"     : "13.638947, 100.371487"
}
```
## Dirt-senser
```
Topic: v1cdti/hw/get/6310301020/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301020",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "Dirt-senser",
    "value"     : "50%"
}
```
## Monitor machine sensor
```
Topic: v1cdti/hw/monitor/6310301020/model-01/WSH-SN001
Payload: {
    "action"    : "monitor",
    "project"   : "6310301020",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/get/6310301020/model-01/WSH-SN001
Payload: {
    "action"    : "monitor",
    "project"   : "6310301020",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "status",
    "value"     : "maint"
```