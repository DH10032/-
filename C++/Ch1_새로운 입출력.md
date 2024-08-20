``` c++
#include <iostream>
int main()
{
  int val1, val2;
  // printf를 대체하는 문장
  std::cout<<"Hello"<<"!"std::endl; // std = standad, cout = c out, std::endl = '\n' (개행 문자)
  // scnaf를 대체하는 문장
  std::cin>>val1>>val2;
}
```
c++에서는 이 방법을 쓸 경우, 입출력 모두 형식지정자를 필요로 하지 않는다.
