# Javascript-Unit3
/*jshint multistr:true */
var text = "Hey, how are you doing? My name is Corin.";
var myName = "Corin";
var hits = []

for (var i = 0; i <= text.length; i ++) {
    console.log(i)
      if (text[i] === "C") {
          for (j = i; j < myName.length+i; j++) {
              hits.push(text[j]);
              }
              }
              }
              if (hits.length === 0) {
                  console.log("Your name wasn't found");
              }
              else
              {
                  console.log(hits);
              }

if (hits.length === 0) {
    console.log("Your name wasn't found!")
} 
else
{
    console.log(hits)
}
