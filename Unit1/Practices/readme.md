Práctica #2

Funciones

Practique  encontrar  20  funciones más  en R y haga un ejemplo de ello.   

//1 Rep: this function allows to repeat a number n number of times, first we place the number then the quantity.

#Example:
rep(3,9)

//2 With this function we can do an operation, it is a little more complex than the previous one.

#Example:
var1 <-2.5
var2 <- 4

result <- var1 / var2
result

//3 With this function we can count the times that one deceives, First we start 
#it from what value we want it to start counting and then the rest of the function.

#Example:
counter <- 0

while(counter < 8){
  print("Counter:")
  print(counter)
  counter <- counter + 1
}
//4  Rnorm:this function takes n random number from -1 to 1 

#Example: 
rnorm(5)

//5 In this way we can say that the numbers are different from.

#Example:
4 != 3

//6 trunc: this function removes decimals from a number.

#Example:
trunc(4.523)

//7  Sqrt: this function allows you to calculate the square root of a number.

#Example:
sqrt(26)

//8  With this function we can do an operation, more simple and using variables.

#Example:
A <- 20
B <- 6
R <- A - B
R

//9 C: this function allows you to combine and create a vector

#Example:

vec <- c(6,35,80)

//10 With this we print the phrase one wants and the number of times that one wants

#Example:
for(i in 1:3){
  print("Hello World!")
}

//11 Paste: this function concatenate vectors after converting to character.

#Example:
message<-paste('Hello','World')

//12 The following function we can print the message repeatedly and then we can number them

#Example:
for(i in 0:2){
  print(i)
  print("Data Mining")
}

//13 length:this function shows the number of elements in a vector.

#Example:
x<-c(1,2,3,4,5,6)
length(x)



//14 With this function it shows what type of data it is.

#Example:
typeof(2)

//15 This function generates a loop until we decide to stop it

#Example:
while(TRUE){
  print("Hello good Morning....")
}

//16 With this function we can know if the number we enter is double or not.

#Example:
is.double(10)

//17 Seq: this function allows you to generate a sequence

#Example:
seq(3,9)

//18 With this function we can know if the number we enter is an integer or not.

#Example:
is.integer(19)

//19 Sum: this function sums all the values within the range you set.

#Example:
sum(2:10)

//20  round: this function rounds a number to the specified decimal places.

#Example:
round(15.845,digits=1)


