###Description: 문제해결능력을 기르기위한 알고리즘 문제 풀이 공간입니다.



####Algorithm_Codility_Exam1_BinaryGap

##### **[이진수의 BinaryGap을 구하기]**

요약:  BinaryGap들의 길이(갯수) 들 중에 가장 큰 값을 반환하는 함수를 작성하시오.

(BinaryGap: 1과 1사이에 들어가있는 0값)

Ex) 숫자 9 => 이진수 1001 => BinaryGap Length = 2

​     숫자 529 => 이진수 1000010001 => BinaryGap Length = 4, 3 => 반환 4

​     숫자 20 => 이진수 10100 => BinaryGap Length = 1

​     (끝에 1을 다시 만나지않고 끝나기때문에 1과1사이에 있는 값만 BinaryGap으로 정의)

#### Algorithm_Codility_Exam2_OddOccurrencesInArray

요약: Int배열에서 같은 숫자끼리 한쌍으로(2개씩) 묶어서 혼자인 숫자 리턴하기

​      가장 효율적인 알고리즘을 구성하시오

​      \- 배열 안의 구성요소 갯수 => 범위 [1..1,000,000] 안의 홀수 갯수

​      \- 배열 안의 숫자의 범위 => 범위 [1..1,000,000,000] 안의 정수

 Ex) [9, 3, 9, 3, 9, 7, 9]  => 한쌍(9, 9), (3, 3), (9, 9)  => 7 짝 X => 7 리턴