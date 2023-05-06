# Javascript

# Arthemetic Operator

var a = parseInt(prompt("Enter value for a : "));

var b = parseInt(prompt("Enter value for b : "));

document.write("<br>Sum of a and b is : "+(a+b));

document.write("<br>Subtraction of a and b is : "+(a-b));

document.write("<br>modular of a and b is : "+(a%b));

document.write("<br>division of a and b is : "+(a/b));
     
# Assignment Operator

var a = 10;
document.write("<br> value of a is : "+a);
a += 5;
document.write("<br> value of a is : "+a);
a -= 5;
document.write("<br> value of a is : "+a);
a *= 5;
document.write("<br> value of a is : "+a);
a /= 5;
document.write("<br> value of a is : "+a);
a %= 5;
document.write("<br> value of a is : "+a);


# Conditional / Relational Operator

var a = 10;

var b = 20;

document.write("<br>"+(a>b)) //0

document.write("<br>"+(a>=b)) //0

document.write("<br>"+(a<b)) //1

document.write("<br>"+(a<=b)) //1

document.write("<br>"+(a==b)) //0

document.write("<br>"+(a!=b)) //1


var a = parseInt(prompt("Enter value for a : "));
var b = parseInt(prompt("Enter value for b : "));
var c = parseInt(prompt("Enter value for c : "));

if((a>b)&&(b>c))
{
    document.write("a: "+a+" b: "+b+" c: "+c);
}
else if((a>b)&&(c>b))
{
    document.write(a+" "+c+" "+b);
}
else if((b>a)&&(a>c))
{
    document.write(b+" "+a+" "+c);
}
else if((b>c)&&(c>a))
{
    document.write(b+" "+c+" "+a);
}
else if((c>a)&&(a>b))
{
    document.write(c+" "+a+" "+b);
}
else
{
    document.write(c+" "+b+" "+a);
}
     
