# js-loopsconsole.log("Hello, npm");

//TODO: Create a function that requires 2 params
function print(tag, message){
    console.log(tag, message);
    
}

print("message:","Hello, npm");

for(let i=1; i<6; i=i + 1){
    print(i, "Hello")
}

for (let n = 1; n < 6;  n += 1){
    console.log(`Hello, i => ${n**2}`)
}

//Should print / log those two items
// ensure function name = print 

//while loop => syntax: while(boolean)

let j = 1;
while(j < 6){
    print(j, "Wakanda")
    j = j + 1
}

//do while loop

let m = 1
do{
    print(m, "Hello")
    m++
}while(m < 6)

let z = 1
while(z < 1){
    print("hi","issa")
    z++
}

do{
    print("random","Hello")
    z++
}while(z < 1)
