int num, rem, sum = 0, i; 
Console. WriteLine(“enter a number”);
num = Convert.Toint32(“Console.Readline());
for(i = 1; i < num; i++)
{
rem = num % i;
if (rem == 0)
{
sum = sum + i;
}
}
if (sum == num)
Console.WriteLine("i Perfect Number");
else
Console.WriteLine("not a Perfect Number");
