# JS_ShortHand_Tips
Java Script good tips by Emma Turner

1. Declaring variables: easily declare/define multiple variables on one line

| Long | Shorthand |
| ----------- | ----------- |
| ```let a;``` <br> ```let b = 1;```| ```let a, b = 1; ```  |

2. Assigning values to multiple variables: assign values to multiple variables with array destructuring

| Long | Shorthand |
| ----------- | ----------- |
| ```x = 1;``` <br> ```y = 2;```<br> ```z = 3; ``` | ``` let [x, y, z] = [1, 2, 3];   ```  |

3. Assigning default value
```
// long version
let finalName;   
let name = getName();   
if(name !== null && name !== undefined && name !== '') {  
    finalName = name;   
} else {  
    finalName = 'Chung'  
} 

// Shorthand  
let finalName = getName() || 'Chung';
``` 

4. Ternary operator
```
//Long version  
let points = 70;   
let result;   
if(marks >= 50){  
    result = 'Pass';   
}else{  
    result = 'Fail';   
}

//Shorthand  
let points = 70;   
let result = marks >= 50 ? 'Pass' : 'Fail'; 
```
