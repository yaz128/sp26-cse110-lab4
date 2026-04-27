1. It will print 3. This is because var has function scope, so i is still accessible outside the for loop. The loop runs 3 times, so i becomes 3.

2. It will print 150. discountedPrice is declared with var, so it has function scope and can be accessed outside the loop. The last value is 300 * 0.5 = 150.

3. It will print 150. finalPrice is declared with var, so it is accessible outside the loop. The last computed value is 150.

4. It will return [50, 100, 150]. The loop calculates each discounted price and pushes it into the array.

5. It will cause an error. i is declared with let, so it has block scope and cannot be accessed outside the for loop.

6. It will cause an error. discountedPrice is declared with let inside the loop, so it cannot be accessed outside the block.

7. It will print 150. finalPrice is declared outside the loop, so it is still accessible. The last value is 150.

8. It will return [50, 100, 150]. The loop runs correctly and pushes each discounted value into the array.

9. It will cause an error. i is declared with let inside the loop, so it is not accessible outside the loop.

10. It will print 3. length is declared with const outside the loop, so it is accessible and equals 3.

11. It will return [50, 100, 150]. The loop calculates each value and pushes it into the array.

12. 
A. student.name  
B. student['Grad Year']  
C. student.greeting()  
D. student['Favorite Teacher'].name  
E. student.courseLoad[0]

13. 
A. '32'  
B. 1  
C. 3  
D. '3null'  
E. 4  
F. 0  
G. '3undefined'  
H. NaN

14. 
A. true  
B. false  
C. true  
D. false  
E. false
F. true

15. == compares values and does type conversion. === compares both value and type without conversion.

16. 
for(let key in statistics){
    if(key[0] === 'r' || statistics[key] % 2 === 1){
        console.log(statistics[key]);
    }
}

17. It will return [2, 4, 6]. The callback function multiplies each number by 2.

18. 
setInterval(function() {
  let d = new Date();
  let time = d.toLocaleTimeString();
  console.log(time);
}, 1000);

19. 
Output:
1
4
3
2

1 and 4 run first. setTimeout with 0 runs next, then setTimeout with 1000 runs last.