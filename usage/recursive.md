# Recursion(재귀)
## 기본 개념
재귀 알고리즘은 재귀함수(Recursive Function)을 이용하여 구현하는 알고리즘이다.
재귀함수란 하나의 함수 A가 있을 때 이 함수 안에서 A 함수 즉, 자기 자신을 다시 호출하여 작업을 수행하는 함수이다. 
재귀 알고리즘을 구현하는 과정은 수열의 귀납법을 이용하여 증명하는 것과 굉장히 유사하다.    
즉, 수열이 특정 값에 수렴하는 지를 따지기 위해 귀납법으로 증명하는 것과 재귀함수를 구현하는 것과 굉장히 비슷하다.    
그 증명과정을 컴퓨터가 계산해준다 생각하면 된다. 
### 그렇다면 수학적 귀납법이란 무엇일까?        
첫 번째 도미노를 쓰러뜨리면 나머지 도미노가 모두 쓰러지는 지 어떻게 증명해야할까?      
첫 번째 도미노가 쓰러지면 두 번째 도미노가 쓰러진다 절차적으로 세 번째, 네 번째.. N번째 도미노까지 모두 쓰러질 것이다.    
그런데 이런 방법을 사용하지말고 간단하게, 첫 번째 도미노가 쓰러진다. 두 번째 도미노가 쓰러진다.     
그렇다면 K번째 도미노가 쓰러지다면 K+1번째 도미노가 쓰러진다. 그래서 모든 도미노가 쓰러진다.       
위와 별다른 차이는 없어 보이지만, 절차적으로 모든 경우를 생각해 보는 것이 아니라 첫 번째가 쓰러진다면,    
두 번째 도미노가 쓰러지듯이 도미노의 성질을 생각하여 바로 결론에 도달할 수 있어야 한다는 것이다.      
도미노로 생각하면 둘 다 너무 쉽게 느껴질 수 있으나 전자의 절차지향적인 사고를 고수한다면 재귀 문제를 해결하다 머리가 터지는 경우가 발생할 수 있다.

### 재귀함수 구현의 조건1         
> 1. 특정 인자에 대해서 자기 자신을 호출하지 않고 종료되어야 한다.(base condition)
> 2. 모든 인자는 base condition으로 수렴해야한다.     
    
굉장히 간단해 보이지만 구현할 때 심의를 기울여 생각해야 한다.    
### 재귀함수 구현의 조건2   
> 1. 자기 자신에게 전달해줄 함수의 매개변수를 잘 정의해줘야한다.
> 2. 자기 자신을 ***어디에서*** 호출할 지 잘 정의해줘야한다.
정말 당연한 소리처럼 들릴 지 몰라도 조금이라도 어긋난 재귀함수는 식은 땀을 유발한다.    








