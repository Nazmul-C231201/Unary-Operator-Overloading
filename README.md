# Unary-Operator-Overloading
#include&lt;iostream> using namespace std; class test{   private:   int num;   public:   test ():num (8){} //syntax   void operator++(){       num=num+3;   }   void display(){       cout&lt;&lt;"Summation:"&lt;&lt;num&lt;&lt;endl;   } };  int main(){     test obj;     ++obj;     obj.display();          return 0; }
