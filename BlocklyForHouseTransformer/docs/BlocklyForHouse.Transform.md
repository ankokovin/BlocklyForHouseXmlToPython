# BlocklyForHouse.Transform

<table>
<tbody>
<tr>
<td><a href="#blocklytransformer">BlocklyTransformer</a></td>
<td><a href="#literals">Literals</a></td>
</tr>
<tr>
<td><a href="#abstractexpression">AbstractExpression</a></td>
<td><a href="#block">Block</a></td>
</tr>
<tr>
<td><a href="#closedoor">CloseDoor</a></td>
<td><a href="#door">Door</a></td>
</tr>
<tr>
<td><a href="#doorisopen">DoorIsOpen</a></td>
<td><a href="#gethumidity">GetHumidity</a></td>
</tr>
<tr>
<td><a href="#getilluminance">GetIlluminance</a></td>
<td><a href="#gettemperature">GetTemperature</a></td>
</tr>
<tr>
<td><a href="#humidity">Humidity</a></td>
<td><a href="#humiditysensor">HumiditySensor</a></td>
</tr>
<tr>
<td><a href="#illuminance">Illuminance</a></td>
<td><a href="#illuminancesensor">IlluminanceSensor</a></td>
</tr>
<tr>
<td><a href="#lamp">Lamp</a></td>
<td><a href="#lampison">LampIsOn</a></td>
</tr>
<tr>
<td><a href="#opendoor">OpenDoor</a></td>
<td><a href="#script">Script</a></td>
</tr>
<tr>
<td><a href="#temperature">Temperature</a></td>
<td><a href="#temperaturesensor">TemperatureSensor</a></td>
</tr>
<tr>
<td><a href="#temperatureunit">TemperatureUnit</a></td>
<td><a href="#text">Text</a></td>
</tr>
<tr>
<td><a href="#turnofflamp">TurnOffLamp</a></td>
<td><a href="#turnonlamp">TurnOnLamp</a></td>
</tr>
<tr>
<td><a href="#bodycommandattribute">BodyCommandAttribute</a></td>
<td><a href="#eventstarterattribute">EventStarterAttribute</a></td>
</tr>
<tr>
<td><a href="#finderattribute">FinderAttribute</a></td>
<td><a href="#field">Field</a></td>
</tr>
<tr>
<td><a href="#body">Body</a></td>
<td><a href="#statement">Statement</a></td>
</tr>
<tr>
<td><a href="#door">Door</a></td>
<td><a href="#event">Event</a></td>
</tr>
<tr>
<td><a href="#humidity">Humidity</a></td>
<td><a href="#humiditysensor">HumiditySensor</a></td>
</tr>
<tr>
<td><a href="#illuminance">Illuminance</a></td>
<td><a href="#illuminancesensor">IlluminanceSensor</a></td>
</tr>
<tr>
<td><a href="#lamp">Lamp</a></td>
<td><a href="#name">Name</a></td>
</tr>
<tr>
<td><a href="#temperature">Temperature</a></td>
<td><a href="#temperaturesensor">TemperatureSensor</a></td>
</tr>
<tr>
<td><a href="#value">Value</a></td>
<td><a href="#xmltopythoncontext">XmlToPythonContext</a></td>
</tr>
</tbody>
</table>


## BlocklyTransformer

Tranformation component for BlocklyForHouse

### AddSpaces(count)

Add space indention to code

| Name | Description |
| ---- | ----------- |
| count | *System.Int32*<br>lvl of indention |

#### Returns

correct number of spaces

### XmlToPython(text)

Transform xml text from BlocklyForHouse to Python

| Name | Description |
| ---- | ----------- |
| text | *System.String*<br>XML text generated by BlocklyForHouse |

#### Returns

Separate string - Python programs for script installation


## Literals

Класс ресурса со строгой типизацией для поиска локализованных строк и т.д.

### AddScript

Ищет локализованную строку, похожую на add_script({0},event,body).

### Body

Ищет локализованную строку, похожую на def body():.

### Call

Ищет локализованную строку, похожую на {0}({1}).

### Culture

Перезаписывает свойство CurrentUICulture текущего потока для всех обращений к ресурсу с помощью этого класса ресурса со строгой типизацией.

### DoorClose

Ищет локализованную строку, похожую на close.

### DoorCreate

Ищет локализованную строку, похожую на door.

### DoorIsOpen

Ищет локализованную строку, похожую на is_open.

### DoorOpen

Ищет локализованную строку, похожую на open.

### EmptyBody

Ищет локализованную строку, похожую на pass.

### EmptyEvent

Ищет локализованную строку, похожую на false.

### Event

Ищет локализованную строку, похожую на def event():.

### EventStart

Ищет локализованную строку, похожую на return .

### Humidity

Ищет локализованную строку, похожую на humidity.

### HumidityGet

Ищет локализованную строку, похожую на hum_get.

### HumiditySensorCreate

Ищет локализованную строку, похожую на hum_sensor.

### Illuminance

Ищет локализованную строку, похожую на illuminance.

### IlluminanceGet

Ищет локализованную строку, похожую на il_get.

### IlluminanceSensorCreate

Ищет локализованную строку, похожую на il_sensor.

### Import

Ищет локализованную строку, похожую на import {0}.

### LampCreate

Ищет локализованную строку, похожую на lamp.

### LampIsOn

Ищет локализованную строку, похожую на is_on.

### LampOff

Ищет локализованную строку, похожую на off.

### LampOn

Ищет локализованную строку, похожую на on.

### PackageName

Ищет локализованную строку, похожую на BlocklyForHousePy.

### ResourceManager

Возвращает кэшированный экземпляр ResourceManager, использованный этим классом.

### Temperature

Ищет локализованную строку, похожую на temperature.

### TemperatureGet

Ищет локализованную строку, похожую на tem_get.

### TemperatureSensorCreate

Ищет локализованную строку, похожую на tem_sensor.


## AbstractExpression

abstraction of expressions inside xml input

### Interpret(context)

Interpret some context

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Code in Python


## Block


```xml
<block type="...">
```


### Interpret(context)

Interpret context as <a href="#block">Block</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## CloseDoor

For xml input:
```xml 
<block type="close_door">
```


### Interpret(context)

Interpret context as <a href="#closedoor">CloseDoor</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Door

For xml input:
```xml 
<block type="door">
```

### Interpret(context)

Interpret context as <a href="#door">Door</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## DoorIsOpen

For xml input: 
```xml
<block type="door_is_open">
```

### Interpret(context)

Interpret context as <a href="#doorisopen">DoorIsOpen</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## GetHumidity

For xml input: 
```xml
<block type="hum_get">
```


## GetIlluminance

For xml input:
```xml 
<block type="il_get">
```



## GetTemperature

```xml
<block type="tem_get">
```


## Humidity

For xml input: 
```xml
<block type="humidity">
```


## HumiditySensor

For xml input:
```xml 
<block type="hum_sensor">
```


## Illuminance

For xml input:
```xml 
<block type="illuminance">
```


## IlluminanceSensor

```xml
<block type="il_sensor">
```


## Lamp

For xml input: 
```
<block type="lamp">
```


## LampIsOn

For xml input: 
```xml
<block type="lamp_is_on">
```


## OpenDoor

For xml input: 
```xml
<block type="open_door">
```

### Interpret(context)

Interpret context as <a href="#opendoor">OpenDoor</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Script

```xml
<block type="script">
```

### Interpret(context)

Interpret context as <a href="#script">Script</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Temperature

```xml
<block type="temperature">
```


## TemperatureSensor

```xml
<block type="tem_sensor">
```


## TemperatureUnit

Units of mesurement for <a href="#temperature">Temperature</a>


## Text

```xml
<block type="text">
```

### Interpret(context)

Interpret context as <a href="#text">Text</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## TurnOffLamp

For xml input: 
```xml
<block type="off_lamp">
```


## TurnOnLamp

For xml input: 
```xml
<block type="on_lamp">
```


## BodyCommandAttribute

Attribute for blocks, used as commands inside the body of <a href="#blocklyforhouse.transform.xmltopython.blocks.script">BlocklyForHouse.Transform.XmlToPython.Blocks.Script</a>
Block classes are caught in <a href="#blocklyforhouse.transform.xmltopython.statements.body">BlocklyForHouse.Transform.XmlToPython.Statements.Body</a> with <a href="#finderattribute.getblocks\`\`1">FinderAttribute.GetBlocks\`\`1</a>



## EventStarterAttribute

Attribute for blocks, used as triggers for <a href="#blocklyforhouse.transform.xmltopython.blocks.script">BlocklyForHouse.Transform.XmlToPython.Blocks.Script</a>
Block classes are caught in <a href="#blocklyforhouse.transform.xmltopython.values.event">BlocklyForHouse.Transform.XmlToPython.Values.Event</a> with <a href="#finderattribute.getblocks\`\`1">FinderAttribute.GetBlocks\`\`1</a>



## FinderAttribute

Attribute for blocks, which should be found for detection

### GetBlocks\`\`1

Find all classes of <a href="#blocklyforhouse.transform.xmltopython.blocks.block">BlocklyForHouse.Transform.XmlToPython.Blocks.Block</a> with some <a href="#finderattribute">FinderAttribute</a> T

#### Type Parameters

- T - Attribute, which implements <a href="#finderattribute">FinderAttribute</a>

#### Returns

Dictionary of <a href="#blocklyforhouse.transform.xmltopython.blocks.block">BlocklyForHouse.Transform.XmlToPython.Blocks.Block</a> with keys - <a href="#finderattribute.typename">FinderAttribute.TypeName</a>

### TypeName

value for "type" attribute inside xml block


## Field


```xml
<field>
```

### Interpret(context)

Interpret context as <a href="#field">Field</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Body

<a href="#statement">Statement</a> for actions inside <a href="#blocklyforhouse.transform.xmltopython.blocks.script">BlocklyForHouse.Transform.XmlToPython.Blocks.Script</a>
```xml
<statement type="body">
```


### Blocks

Blocks, which could be used as actions inside <a href="#body">Body</a>

### Interpret(context)

Interpret context as <a href="#body">Body</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Statement

```xml
<statement type="...">
```

### Interpret(context)

Interpret context as <a href="#statement">Statement</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Door

```xml
<value type="door">
```

### Interpret(context)

Interpret context as <a href="#door">Door</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Event

```xml
<value type="event">
```
used inside <a href="#blocklyforhouse.transform.xmltopython.blocks.script">BlocklyForHouse.Transform.XmlToPython.Blocks.Script</a>


### Interpret(context)

Interpret context as <a href="#event">Event</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Humidity

```xml
<value type="humidity">
```

### Interpret(context)

Interpret context as <a href="#humidity">Humidity</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## HumiditySensor

```xml
<value type="hum_sensor">
```

### Interpret(context)

Interpret context as <a href="#humiditysensor">HumiditySensor</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Illuminance

```xml
<value type="illuminance">
```

### Interpret(context)

Interpret context as <a href="#illuminance">Illuminance</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## IlluminanceSensor

```xml
<value type="il_sensor">
```

### Interpret(context)

Interpret context as <a href="#illuminancesensor">IlluminanceSensor</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Lamp

```xml
<value type="lamp">
```

### Interpret(context)

Interpret context as <a href="#lamp">Lamp</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Name

```xml
<value type="name">
```

### Interpret(context)

Interpret context as <a href="#name">Name</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Temperature

```xml
<value type="temperature">
```

### Interpret(context)

Interpret context as <a href="#temperature">Temperature</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## TemperatureSensor

```xml
<value type="tem_sensor">
```

### Interpret(context)

Interpret context as <a href="#temperaturesensor">TemperatureSensor</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## Value

```xml
<value type="...">
```

### Interpret(context)

Interpret context as <a href="#value">Value</a>

| Name | Description |
| ---- | ----------- |
| context | *BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@*<br>Context to interpret |

#### Returns

Python code


## XmlToPythonContext

Context of transformation

### Constructor(text)

Constructor for <a href="#xmltopythoncontext">XmlToPythonContext</a>

| Name | Description |
| ---- | ----------- |
| text | *System.String*<br>Xml text |

### currentNode

current xml node of context

### NextCheck

Check if there is next xml tag avaliable

#### Example

Consider this input: 
```

            <block type="smt">
            ...
            <next>
            ...
            </next>
            </block>
            
```
It is much more convinient to consider the content of "next" as the block on same lvl For example, this is used inside <a href="#statements.body">Statements.Body</a>: 
```

            XmlNode prev;
            do
            {
                prev = context.currentNode;
                result += BlocklyTransformer.AddSpaces(context.tabCount)
                + (Blocks[context.currentNode.Attributes["type"].Value]).Interpret(ref context) + "\n";
            } while (prev!=context.currentNode);
            
```
And here is the use of <a href="#xmltopythoncontext.nextcheck">XmlToPythonContext.NextCheck</a> in <a href="#blocks.opendoor.interpret(blocklyforhouse.transform.xmltopython.xmltopythoncontext@)">Blocks.OpenDoor.Interpret(BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@)</a>: 
```

            base.Interpret(ref context);
            context.NextNode();
            var result = (new Values.Door().Interpret(ref context)) + "." + LiteralsPython.DoorOpen + "()";
            context.ParentNode();
            context.NextCheck();
            return result;
            
```
Suppose we have such input: 
```

            <block type="open_door">
            ...
            <next>
            <block type="open_door">
            ...
            </block>
            </next>
            </block>
            
```
When we will be done with first iteration inside <a href="#statements.body.interpret(blocklyforhouse.transform.xmltopython.xmltopythoncontext@)">Statements.Body.Interpret(BlocklyForHouse.Transform.XmlToPython.XmlToPythonContext@)</a>, <a href="#xmltopythoncontext.currentnode">XmlToPythonContext.currentNode</a> will point to next <a href="#blocks.opendoor">Blocks.OpenDoor</a> block

### NextNode

Set <a href="#xmltopythoncontext.currentnode">XmlToPythonContext.currentNode</a> on first child of current node 
Attention! Make sure there is only one child or other children are taken in consideration


### ParentNode

Set <a href="#xmltopythoncontext.currentnode">XmlToPythonContext.currentNode</a> on parent node of current node 
Attention! Make sure not to use it, when current node is <a href="#blocks.script">Blocks.Script</a>


### tabCount

number of space identions inside current context