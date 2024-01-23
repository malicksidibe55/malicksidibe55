var readlineSync=require("readline-sync")


console.log("Hi, welcoome! ")
var name = readlineSync.question("What is your name?: ")

var countries = ["USA", "Canada", "Ireland", "UK", "France", "Germany"]


console.log(countries)
var country = readlineSync.question("Hi "+name+ " Please chose a country?: ")

if (country == "Ireland" && country == "Ireland"){

    console.log("The weather is rain for the next week ")


}else{
    console.log("The weather is sunny ")

}
