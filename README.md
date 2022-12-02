# core-code-from-scratch-01-12

## ---Truth tables---

T & T = T ✅
T & F = F ✅
F & T = T ✖️
F & F = F ✅
T | T = T ✅
T | F = F ✖️
F | T = T ✅
F | F = F ✅
~T = T ✖️
~F = T ✅
(T & F) | (~F) = T ✅
(T | F ) & (F | F) = T ✖️
~((T | F ) & (F | F)) & F = T ✖️
~((T | F ) & (F | F)) & T = F ✖️

---
## ---Boolean results---

Algoritmo boolean
	a <- 5 == 3
  //FALSE : Due that those numbers are being compared to determinate if they're similar
  
	b <- 4 <> 3
  //TRUE : It's true because the operator is saying both numbers are not the same
  
	c <- 7 > 7
  //FALSE : 7 is not greater than 7. It's the same number
  
	d <- 4 < 4
  //FALSE : 4 is not less then itself
  
	e <- 100 <= 90
  //FALSE : Due to operator says if is 100 less or equal than 90 number. In this case is greater than the first number.
  
	f <- 40 >= 40
  //TRUE : Due that operator says it's greater or equal, in this case it's equal.
  
FinAlgoritmo

---
## ---Odd/even conditional---

![Captura de pantalla (78)](https://user-images.githubusercontent.com/92037725/205200317-a22b9811-11b5-4877-9023-5aebd5e16ec0.png)
