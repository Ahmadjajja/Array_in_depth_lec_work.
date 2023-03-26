# Array_in_depth_lec_work.
```javascript
 var names=["ahmad","sultan","jajja","danish","jajja","hamid","jajja"];

console.log("array",names);

console.log("array-length=",names.length);

console.log("last-index=",names[names.length-1]);

// push operation

// push operation insert value at the last index

console.log("array before push operation=>",names);

names.push("hasnain jajja");

console.log("array after push operation=>",names);

// pop operation 

// pop operation delete value at the last index

console.log("array before pop operation=>",names);

names.pop();

console.log("array after pop operation=>",names);

// unshift operation

// unshift function insert values at first index and value stored at index 1 shifted to next index

console.log("array before unshift operation=>",names);

names.unshift("ali jajja");

console.log("array after unshift operation=>",names);

// shift operation

// shift operation delete value at start index

console.log("array before shift operation=>",names);

names.shift();

console.log("array after shift operation=>",names);

// splice operation

// ist value(2) means start from 2 index

// 2nd value(2) means(two deleting index) delete values at index 2 and 3

// 3rd value(cs-student,chemistry student,2) means insert values at index 2,3,4 and remaining value will start from upcoming index



console.log("array before splice operation=>",names);

names.splice(2,2,"cs_student","chemistry student",2);

console.log("array after splice operation=>",names);



// slice operation

// slice operation uses for making another array from the values of first array but the values in first array remains same.

// first value(0) means value stored at index 0 of array will be included.

// 2nd value(7) means values stored before index 7 will be included and value stored at index 7 will not be included.   

console.log("array before slice operation=>",names);

var newNames=names.slice(0,7);

console.log("array after slice operation=>",names);

console.log("new array=>",newNames);


// first lecture of array is over
```
