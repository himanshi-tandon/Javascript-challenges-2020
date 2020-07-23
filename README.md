//question 1:

const num=1; 
const bol=true; 
console.log(typeof(num));//number

console.log(typeof(bol)); //boolean
 console.log(typeof(typeof(num)));//string 
 console.log(typeof(typeof(bol)));//string

//string //string, string. Because typeof(num) gives out a string which is 'number', same goes with typeof(bool) gives out a string which is 'boolean'.

#//question 2:

let obj= {name : 'himanshi'};

let data=obj; 
console.log(data['name']); // himanshi 
console.log(obj['name']); // himanshi 
obj['name']='Himanshi tandon' 
console.log(obj['name']); // Himanshi tandon 
console.log(data['name']); // Himanshi tandon

#//question 3:

var name= 'java'; 
this.name= "script";

console.log(name);//script 
let fullname="Himanshi"; 
this.fullname="Himanshi Tandon"; 
console.log(fullname);//Himanshi
