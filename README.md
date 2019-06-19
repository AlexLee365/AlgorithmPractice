### Description: 문제해결능력을 기르기위한 알고리즘 문제 풀이 공간입니다.

***

### Algorithm_Codility_Exam1_BinaryGap

##### **[이진수의 BinaryGap을 구하기]**

요약:  BinaryGap들의 길이(갯수) 들 중에 가장 큰 값을 반환하는 함수를 작성하시오.

(BinaryGap: 1과 1사이에 들어가있는 0값)

Ex) 숫자 9 => 이진수 1001 => BinaryGap Length = 2

​     숫자 529 => 이진수 1000010001 => BinaryGap Length = 4, 3 => 반환 4

​     숫자 20 => 이진수 10100 => BinaryGap Length = 1

​     (끝에 1을 다시 만나지않고 끝나기때문에 1과1사이에 있는 값만 BinaryGap으로 정의)

***

### Algorithm_Codility_Exam2-1_OddOccurrencesInArray

요약: Int배열에서 같은 숫자끼리 한쌍으로(2개씩) 묶어서 혼자인 숫자 리턴하기

​      가장 효율적인 알고리즘을 구성하시오

​      \- 배열 안의 구성요소 갯수 => 범위 [1..1,000,000] 안의 홀수 갯수

​      \- 배열 안의 숫자의 범위 => 범위 [1..1,000,000,000] 안의 정수

 Ex) [9, 3, 9, 3, 9, 7, 9]  => 한쌍(9, 9), (3, 3), (9, 9)  => 7 짝 X => 7 리턴

***

### Algorithm_Codility_Exam2-2_CyclicRotation

요약: 순환하는 배열을 만드시오

​         A: Int배열 / K: 순환횟수

 Ex) A = [3, 8, 9, 7, 6] / K = 3

 => [3, 8, 9, 7, 6] -> [6, 3, 8, 9, 7]

​    [6, 3, 8, 9, 7] -> [7, 6, 3, 8, 9]

​    [7, 6, 3, 8, 9] -> [9, 7, 6, 3, 8]

***

### Algorithm_Programmers_Level2_TrucksCrossingABridge

**[다리를 지나는 트럭]**

 문제 설명

 트럭 여러 대가 강을 가로지르는 일 차선 다리를 정해진 순으로 건너려 합니다. 모든 트럭이 다리를 건너려면 최소 몇 초가 걸리는지 알아내야 합니다. 트럭은 1초에 1만큼 움직이며, 다리 길이는 bridge_length이고 다리는 무게 weight까지 견딥니다.

 ※ 트럭이 다리에 완전히 오르지 않은 경우, 이 트럭의 무게는 고려하지 않습니다.

 

 예를 들어, 길이가 2이고 10kg 무게를 견디는 다리가 있습니다. 무게가 [7, 4, 5, 6]kg인 트럭이 순서대로 최단 시간 안에 다리를 건너려면 다음과 같이 건너야 합니다.

 

 경과 시간  다리를 지난 트럭   다리를 건너는 트럭    대기 트럭

   0          []             []         [7,4,5,6]

  1~2         []             [7]         [4,5,6]

   3          [7]            [4]          [5,6]

   4          [7]           [4,5]          [6]

   5         [7,4]           [5]           [6]

  6~7       [7,4,5]          [6]           []

   8       [7,4,5,6]         []            []

 따라서, 모든 트럭이 다리를 지나려면 최소 8초가 걸립니다.

 

 solution 함수의 매개변수로 다리 길이 bridgelength, 다리가 견딜 수 있는 무게 weight, 트럭별 무게 truckweights가 주어집니다. 이때 모든 트럭이 다리를 건너려면 최소 몇 초가 걸리는지 return 하도록 solution 함수를 완성하세요.

 제한 조건

 bridge_length는 1 이상 10,000 이하입니다.

 weight는 1 이상 10,000 이하입니다.

 truck_weights의 길이는 1 이상 10,000 이하입니다.

 모든 트럭의 무게는 1 이상 weight 이하입니다.

 입출력 예

 bridge_length    weight    truck_weights    return

 2    10    [7,4,5,6]    8

 100    100    [10]    101

 100    100    [10,10,10,10,10,10,10,10,10,10]    110

***



