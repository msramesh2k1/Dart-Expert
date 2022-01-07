# Null Safety

## Flutter Null Safety is the securing way to build apps . 
```sh
String name = “Ramesh M S”;
final uppercase = name.toUpperCase();
print(uppercase);
```
###### Output :
#
#
```sh
RAMESH M S
```

###### Other Eg
#
#
```sh
String name = null;
final uppercase = name.toUpperCase();
print(uppercase);
```
###### Output :
#
#
```sh
Throws Null Exception
```
##### How to overcome this 
#
#
```sh
String? name ;
```
#####  name can be null or any value
#
#
## Using late 
#
#
```sh
late String name ;
```
```sh
name = “Ramesh M S “; 
```
#### ( using late means we can assigned it later , telling analyzer that it is not null value but assigned later )
#
#
#### ! Null Check Operator 
#
#
```sh
String? name ;
```
#
#
##### Telling that name is not nullable so we are using ! null check Operator …
