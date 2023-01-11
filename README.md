# JAVA-BASE-TYPE-OF-CLASS

8 base type

### 8 Base Type

| dataType | length |default|
|----------|----|----|
| byte     | 1 byte |null|
| boolean  |1byte|false|
| short    | 2 bytes |0|
| char     | 2 bytes |''|
| int      | 4 bytes |0|
| float    | 4bytes |0.0|
| long     | 8bytes |0|
| double   | 8bytes |0.0|

### the corresponding package type

|base dataType| package dataType |
|------------------|------------------|
|byte| Byte             |
|boolean| Boolean          |
|short| Short            |
|char| Character        |
|int|Integer|
|float|Float|
|long|Long|
|double|Double|

### Byte

+ compareTo(Byte anotherByte)
```java
/** compare two Byte objects numerically
 * @param anotherByte
 * @return the value 0 if this is equal to argument Byte,the value less than 0 if this 
 * numerically less than argument Byte,the value greater than 0 if this numerically is greater than
 * argument Byte
 */
Byte by=1;
Byte by2=2;
by.compareTo(by2);
```
+ doubleValue() intValue() longValue() floatValue() shortValue() byteValue()
```java
/** @return the value of this Byte as a double after widening primitive conversion.
 */
Byte by=1;
Double d=by.doubleValue();
```
+ toString()
```java
/** @return a String object represneting this Byte's value
 */
Byte by=1;
String s=by.toString();
```
+ static int hashCode(byte value)
```java
/**
 * @return a hash code for a byte value
 */
byte s=1;
int i = Byte.hashCode(s);
```


