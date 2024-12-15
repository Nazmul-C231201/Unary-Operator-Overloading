# Unary-Operator-Overloading
#include<iostream>
using namespace std;
class test{
  private:
  int num;
  public:
  test ():num (8){} //syntax
  void operator++(){
      num=num+3;
  }
  void display(){
      cout<<"Summation:"<<num<<endl;
  }
};

int main(){
    test obj;
    ++obj;
    obj.display();
    
    return 0;
}
