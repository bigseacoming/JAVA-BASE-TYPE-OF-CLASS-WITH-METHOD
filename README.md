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
### Boolean
+ booleanValue()
```java
/**
 * @return return the value of Boolean object as a boolean primitive
 */
Boolean b=true;
b.booleanValue()//true
```
+ Boolean.parseBoolean()
```java
/**
 * parse the argument value as a boolean
 */
```
+ valueOf()
```java
/**
 * @return a Boolean instance representing the boolean value
 */
```
+ getBoolean()
```java
/**
 * @return return true if and only if the system property named by argument exist and is equal to 
 */
```
### Short
+ compareTo(Short argument)
```java
/** compare two Byte objects numerically
 * @param anotherByte
 * @return the value 0 if this is equal to argument Byte,the value less than 0 if this 
 * numerically less than argument Byte,the value greater than 0 if this numerically is greater than
 * argument Byte
 */
Short by=1;
Short by2=2;
by.compareTo(by2);
```

+ doubleValue() intValue() longValue() floatValue() shortValue() byteValue()
```java
/** @return the value of this Short as a double after widening primitive conversion.
 */
Short short=1;
Double d=short.doubleValue();
```
+ toString()
```java
/** @return a String object represneting this Short's value
 */
Short by=1;
String s=by.toString();
```
+ static int hashCode(short value)
```java
/**
 * @return a hash code for a byte value
 */
short s=1;
int i = Short.hashCode(s);
```
### Character
+ static isDigit(char ch)
```java
/**
 * determines the specified character is a digit
 */
Character.isDigit(char)
```
+ static isDefined(char ch)
```java
/**
 * determines if a char is defined in unicode
 */
Character.isDefined(char)
```
+ static isLetter(Char char)
```java
/**
 * Determines if the specified character is a letter
 */
Character.isLetter(char)
```
+ static isLetterOrDigit(Char char)
```java
/**
 * Determines if the specified character is a letter or a digit
 */
Character.isLetterOrDigit(char)
```
+ static isJavaIdentifierStart(Char char)
```java
/**
 * Determines the specified character is permissible as first character in a java identifier
 */
Character.isJavaIdentifierStart(char)
```
+ static toLowerCase(Char char)
```java
/**
 * Convers the specified character to a lowercase using case mapping information form the unicodeData file
 */
Character.toLowerCase(char)
```
+ static toUpperCase(Char char)
```java
/**
 * Converts the specified character to a uppercase using case mapping from the unicodeData file
 * 
 */
Character.toUpperCase(char)
```
+ static isSpaceChar(Char char)
```java
/**
 * Determines the specified character is a space character
 */
```
+ static isWhitespace(Char char)
```java
/**
 * Determines the gived argument is a white character
 */
```



