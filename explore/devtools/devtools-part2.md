1. What was the bug?
   1. The input values (num1 and num2) are taken as string, so the calculateSum returned "3" + "4" = "34", intead of sum of int values 3 + 4 = 7.
2. How would you fix it? Include a screenshot of your fix. Name it fix.png (or whatever image extension you would like to use) and add it to your expand/screenshots directory.
   1. I read the num1 and num2 as int values using parseInt().