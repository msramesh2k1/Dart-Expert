## Dart Expert  : 

## Dart Novice to Expert  => Complete Notes 

#### Dart Logo  - Dart from the dart Arrow which makes sense the qualities of Dart Arrow in Dart Programming Language 
#### Precision - Dart language is more precision . It should be optimised as much as possible
#### Speed - it should be minimalist and fast to run
#### Tough - it should be scalable , maintainable and readable 
#### Modifiable - it has features of hot reload
#### Strong platform - Here Platform is Flutter , where Dart is the Basic Foundation of Flutter


## Dart Introduction : Dart is Type Safe Language , means the operations that are performed on data is purely depends on Type of the Data ( int , String , Bool .. etc )

#### Eg - 

#### int x = 3 ;
#### x.toUpperCase();  => We cannot do that bcoz it is in int Datatype

#### Yes , Dart has a tool analyzer which checks Static type at compile time and Run time Check at run time .  Now how should I Stop this Analyzer ?? 
#### It is By Using dynamic keyword 

#### Eg  =  Dynamic a = 3.4; => It is Basically Checked on Run Time and throws exceptions . It Automatically Assigns to the type of data here it is float .
#### where Type Interface comes here

## Type Interface :

#### Types are mandatory in Dart , but aswell we don’t need to annotate each time bcoz 
#### var and dynamic Keyword plays Major Role here 

#### var x = 6.7 ; or dynamic x = 7.6  => Here var is like dynamic keyword that don’t care about the type of variable but the main difference is it uses static
#### type analyzer where as dynamic is using Run time Check Analyzer

#### Different Eg : 

#### var x ;

#### It is automatically assigned to dynamic as dynamic x ; now the value is null , but the latest feature of Flutter is Null Safety .
#### Changing dynamic now the run time check analyser automatically assigned a null value , btw using null is not a good practice .


## Null Safety : Null Safety is like var cannot be null unless you specify
#### Sound Null Safety : Variables are checked by both analyzer and assigned to null or non null values but both cannot be there

## How is Dart code converted into executable code ? 

#### Any Other programming Languages uses compiler , by the same way dart uses dart compiler which converts source code into machine code or intermediate launguage.

#### Dart Compilers - JIT , AOT , DartDevc ,  Dart2js these four are the types of dart compilers 

#### JIT nd AOT are used for phone , desktop type of architecture whereas DartDevc and Dart2Js are used for Web type of compilation , used to convert code into javascript

#### JIT - Just in Time => used to convert source code into intermediate language , where it used to compile only the necessary code and after it compile other necessary code and then it wont recompile while the code is already compiled . It is basically used in development phase

#### AOT - Ahead of Time => used to convert source code into Machine Code , where is used in production phase .

#### Dartdevc - is used for web compilation .  Dartdev is used in Developement phase where Dart2js is used in production phase ..

#### DART SDK - SDK Stands for Software Developement Kit where as Dart SDK contains dart compiler , dart debugger , Dart Analyzers , Dart Libraries and Dart Software Framework .


#### Using Latest Flutter , don’t need to install Dart .
#### Use DartPad for practising the programs


<img width="449" alt="Screenshot 2022-01-06 171028" src="https://user-images.githubusercontent.com/71007973/148379077-3a634619-091a-491a-8d48-1b1c50a046da.png">




#### Dart Create Project  : 

<img width="452" alt="Screenshot 2022-01-06 172358" src="https://user-images.githubusercontent.com/71007973/148379176-5d45a737-0b4b-4a99-96c4-523fbbcb9505.png">


#### Dart program after creating 

<img width="452" alt="Screenshot 2022-01-06 172429" src="https://user-images.githubusercontent.com/71007973/148379293-16fa8bbb-b534-4760-93df-f245689b6e8c.png">

#### Dart File Structure

<img width="452" alt="Screenshot 2022-01-06 172446" src="https://user-images.githubusercontent.com/71007973/148379302-82c90ecc-09f3-45ea-a36b-3b6a54271a77.png">


#### Dart Packages are the main part of the dart ecosystem . In dart , everything is a dart package not a dart project . 
#### Two types of packages are application packages and library packages . where library packages are there in pub.dev , these packages are managed by pub manager .
#### Package mainly consists of library .


#### All Packages and its dependencies are managed in the file called pubspec.yaml




#### FLUTTER PUB GET : It will download the package dependencies
#### from pub.dev and add it to package_config.json and pubspec.lock and not only the dependencies it will add the dependent packages too ..

#### Static Analyzer has set of rules to check , that are stored in analysis_options.yaml

#### How does Dart run a program ?

#### Here comes Dart VM which is Dart virtual machine consists of the RUNTIME SYSTEM , JIT & AOT pipelines , Debugger and Hot Reloader

#### Dart VM basically Provides Virtual Execution Platform for execution of Dart code .
#### Everything executed in virtual memory forms its own virtual memory called Heap .. It is described as Isolate Universe ..
#### Its own process of control thread is called mutator  … 

#### Dart VM is providing two various execution method that are
#### 1 - source to machine code
#### 2 - from snapshots 

#### Basically the source code are loaded into Dart Kernal Binary which produce you the intermediate language, .dll format .
#### It forms you HEAP and then objects are referenced into heap from kernel binary and in production(Run time ) phase everything is executed 

## PUBSPEC.YAML

#### In Pubspec.yaml we need to specify the dependencies required for the project . There are four types of Dependencies = Immediate , Transitive , Regular & Dev .

#### If your package depends on A package and A Package is depends on B and B is depends on C …..  Now A is Immediate and B AND C are Transitive  ….. . 


#### Difference between regular and Dev are Regular packages are used in Both Phase whereas Dev in ignored during Production Phase … 

#### How Should the Dart code be ?

#### Consistent , Organised , minimalist and Simple , Easy to Understand .. 
#### Always test your code . .. . . 


## NULL SAFETY ........ 























