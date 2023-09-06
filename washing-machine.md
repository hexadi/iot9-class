# Washing machine state

## START
```
topic:v1cdti/hw/get/6310301018/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "M_STATUS",
    "value"     :   "START"
}
```

## READY
```
topic:v1cdti/hw/get/6310301018/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "M_STATUS",
    "value"     :   "READY"
}
```

## FILLWATER
```
topic:v1cdti/hw/get/6310301018/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "M_STATUS",
    "value"     :   "FILLWATER"
}
```

## HEATWATER
```
topic:v1cdti/hw/get/6310301018/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "M_STATUS",
    "value"     :   "HEATWATER"
}
```

## WASH
```
topic:v1cdti/hw/get/6310301018/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "M_STATUS",
    "value"     :   "WASH"
}
```

## RINSE
```
topic:v1cdti/hw/get/6310301018/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "M_STATUS",
    "value"     :   "RINSE"
}
```

## SPIN
```
topic:v1cdti/hw/get/6310301018/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "M_STATUS",
    "value"     :   "SPIN"
}
```

## FAULT
```
topic:v1cdti/hw/get/6310301018/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "M_STATUS",
    "value"     :   "FAULT"
}
```

# Operation state

## DOORCLOSE
```
topic:v1cdti/hw/set/6310301018/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "O_STATUS",
    "value"     :   "DOORCLOSE"
}
```

## WATERFULLLEVEL
```
topic:v1cdti/hw/set/6310301018/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "O_STATUS",
    "value"     :   "WATERFULLLEVEL"
}
```

## TEMPERATUREREACHED
```
topic:v1cdti/hw/set/6310301018/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "O_STATUS",
    "value"     :   "TEMPERATUREREACHED"
}
```


# FAULT state

## TIMEOUT
```
topic:v1cdti/hw/get/6310301018/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "TIMEOUT"
}
```

## OUTOFBALANCE
```
topic:v1cdti/hw/set/6310301018/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "OUTOFBALANCE"
}
```

## MOTORFAILURE
```
topic:v1cdti/hw/set/6310301018/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "MOTORFAILURE"
}
```

## FAULTCLEARED
```
topic:v1cdti/hw/set/6310301018/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301018",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "FAULTCLEARED"
}
```