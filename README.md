# 9May2025---JS-Promiss
9May2025 - JS Promiss

JS code execution Behaviour

JS Code never stop when we execute

JS Asynchronous
	1. Promises (Producing Code -> Consuming Code/To wait for result)
	2. Callback
	2. Asynchronous
	4. Async/await 


JS Promise is JS Class

Class Types
1. User Defined // Define=user,Instantiate=user
2. Pre Defined/Built-in  // Define=Already Defined,Instantiate=user

//1. Class Definition

//2. Class Create Class Object / Class Instantiation

//1. Function Definition

//2. Function Calling/Invoation

//1. 

     //PascalCase
class Promise{
}

function myFunction(x,y){
}

let ceo2 = new Promise(function(fa1,fa2){});



1000 mili = 1 Sec

let ceo1 = new Promise(function(myResolve,myReject){
	setTimeOut(function(){
		myResolve("Hello"); // when successful
	},5000);

	
        //myReject();  // when error	

});
ceo1.then(function(result){
	console.log(result);
}).catch().finally();








Promise Chain

po.then().then().then().catch().finally();
ceo1.then().then().then().then().then().then().then().catch().finally();
ceo1.then();





//let ceo1 = new ClassName();
//ceo1.members
//ceo1.property
//ceo2.method()


setTimeout(cbfn,time in milisec)
setTimeout(cbfn,10000)
setTimeout(function(){},10000)
setTimeout(()=>{
	console.log("Hello");
},10000)

let ceo1 = new Promise(function(success,fail){
   // fa1 = fa1 is callback function = cbfn
  setTimeout(()=>{
    //console.log("Hello Good Morning");
    //CBFN
    success("Hello Good Morning"); //Sending...
  },5000);
}); //wait
//Producing Code

//Promise Chain
// po.then().then().catch().finally()

//Consuming Code = wait for result
ceo1.then(function(result){
  console.log('result >>>>',result)
}).catch().finally();

