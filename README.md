"# DAY-4-TASK" 
//Qno:1
//A) PRINT ODD NUMBERS IN AN ARRAY: annonymous method

const arr =[1,2,3,4,56,7,9,13,23,17]
const oddNumbers = [];
for(let i =0; i < arr.length; i++){
arr[i] % 2 === 1 && oddNumbers.push(arr[i]);
}
console.log(oddNumbers);

//B) CONVERT ALL THE STRINGS TO TITLE CAPS IN STRING ARRAY:
// ANONYMOUS FUNCTION
var str = "my name is veni";
function (str) {
    str = str.toLowerCase().split('');
    for (var i= 0; i< str.length; i++){
        str[i] = str[i].charAt(0).toUppercase() + str[i].slice(1);
    }
    return str.join('');
}(str)

//IIFE FUNCTION
var str = "my name is veni";
function (str) {
str = str.toLowerCase().split('');
for (var i=0; i<str.length; i++){
    str[i] = str[i].chatArt(0).toUppercase()+ scr[i].slice(1);
}
return str.join('');
}(str)

//C.SUM OF ALL NUMBERS IN AN ARRAY
//ANONYMOUS FUNCTION
var a=[1,2,3,4,5,6,7,8,9];
var sum=0;
function (a)
{
    for(let i=0; i<a.length; i++)
{
    sum=sum+a[i];
}
    return sum;
}(a)

//IIFE FUNCTION
var a=[1,2,3,4,5,6,7,8,9];
var sum=0;
(function (a)
{
    for(let i=0; i<a.length; i++)
        {
            sum=sum+a[i]
        }
        return sum;
})(a)

//D) RETURN ALL THE PRIME NUMBERS IN AN ARRAY ANONYMOUS FUNCTION

let n=34;
function (n)
{
    for(let i=2; i<=n; i++)
        {
            let flag=0;
            for(let j=2; j<i; j++)
            {
                if(i%j==0)
            {
                flag=1;
                break;
            }
        }
        if(flag==0)
            {
                console.log(i);
            }
}(n);

//IIFE FUNCTION
        let n=34;
        (function (n)
    {
        for(let i=2; i<=n; i++)
            {
                let flag=0;
                for(let j=2; j<i; j++)
            }
        if(i%j==0

            {
                flag=1;
                break;
            }
        if(flag==0)
            {
                console.log(i)
            }
    })(n);
//E) RETURN ALL THE PALINDROMES IN AN ARRAY
//ANONYMOUS FUNCTION:
for (let i = 0; i < n; i++)
    {
        let ans = isPalindrome(arr[i]);
        if (ans == false)
            return false;
    }
    return true;
//RETURN MEDIAN OF TWO SORTED ARRAYS OF THE SAME SIZE.
//ANONYMOUS METHOS
function(num1,num2){
    let s1= num1.length
    let s2= num2.length
    let index = s1+s2
    if(s1==0){
        if(s2%2==1){
            return num2[Math.floor(index/2)-1] + (num2[Math.floor(index/2)])/2
        
        }else{

        }
    }
    for(let i=0; i<index/2+1;i++){
        num1.push(num2[i])
}
num1.sort((a,b)==>a-b)
console.log(num1)
if(index%2==1){
    return num1[Math.floor(index/2)]

}   else{
    return num2[Math.floor(index/2)-1] + (num2[Math.floor(index/2)])/2
} 
}

//G) REMOVE DUPLICATES FROM AN ARRY
// ANONYMOUS FUNCTION
 var arry=[1,2,3,4,5];
 function(array){
    let dup = [...new set(array)];
    return(dup)

 }
(array);

//IIFE FUNCTION
var arry=[1,2,3,4,5];
 function(array){
    let dup = [...new set(array)];
    return(dup)

 }
(array);
//H) ROTATE AN ARRAY BY K TIMES
//ANONYMOUS Function
function (a, n, k)
{
    k = k % n;
    for(let i=0; i<n; i++){
        if(i < k){
            console.log(a[n +i -k] + " ");
        }
        else{
            console.log((a[i - k]) + " ");

        }
    }
    let Arry =[1,2,3,4,5];
    let N = Arry.length;
    let k = 2;
    (Array, N, K);

}

//SECTION 2
//A) PRINT ODD NUMBERS IN AN ARRAY 
//ARROW FUNCTION
var y=[1,2,3,4,5,6,7]
var odd= (array)=>{
    let arr=[];
    for(let i=0; i<array.lemgth; i++)
        {
            if(array[i]%2!==0)
        }
    arr.push(array[i])
    return arr;
}

//B) CONVERT ALL THE STRINGS TO TITLE CAPS IN A STRING ARRAY
var str="my name is veni"
let def = (str)=>{
    str = str.toLowerCase().split("");
    for (var i =0; i< str.length; i++){
        str[i].charAt(0).touppercase() + str[i].slice(1);
    }
    returnstr.join('')
    console.log (def(str))
}
    //C) SUM OF ALL NUMBERS IN AN ARRAY BY USING ARROW FUNCTION:
    var a=[1,2,3,4,5,6,7,8,9];
    var sum=0;
    let ghi=(a)=>
        {
            for(let i+0; i<a.length; i++)
            {
                sum=sum+a[i]
            }
            return sum;
        }
console.log(ghi(a));

//D) RETURN ALL THE PRIME NUMBERS IN AN ARRAY NY USING ARROW FUNCTION:
let n=34;
let 1=(n)=>
    {
        for(let i=2; i<=n; i++) 
           {
            let flag=0;
            {
                flag=1;
                break;
            }
           }
if (flag==0)
    {
        console.log(i);
    }
