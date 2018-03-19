
## Function name : JetTerm
Group: Extensible Storage Engine (ESE, Jet Blue) - Library: esent    
***  


#### Initiates the shutdown of an instance that has been initialized by JetInit.

***  


## Code examples:
[Extensible Storage Engine class library](../../samples/sample_532.md)  

## Declaration:
```foxpro  
JET_ERR JET_API JetTerm(
  __in          JET_INSTANCE instance
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER JetTerm IN esent;
	INTEGER pinstance  
```  
***  


## Parameters:
instance 
Specifies the instance to use for this call.
  
***  


## Return value:
This function returns the JET_ERR datatype with one of predefined return codes (e.g. JET_errSuccess=0).  
***  


## Comments:
See also: JetInit, JetCreateInstance   
  
***  
