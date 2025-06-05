#include <iostream>
using namespace std;
class ClassName {
    private:       
        int id;
         string name;
        double salary;  
    public:
    setObj(int id, string name, double amount){
      this->id=id;
      this->name=name;
       salary =amount;      
      
    } 
  void  display(){    
    cout << id <<"\t" <<name <<"\t\t" << salary <<endl;  
  }
};      
int main(){  
    ClassName ObjName1;
    ClassName ObjName2;
    ClassName ObjName3;
    ClassName ObjName4;
    ClassName ObjName5;
    ClassName ObjName6;
    ClassName ObjName7;
    ClassName ObjName8;
    ClassName ObjName9;
     cout << "ID\t " << "Name \t\t" << "Salary " <<endl;
     ObjName1.setObj(1,"Join",500.00);
     ObjName2.setObj(2,"Join",500.00);
     ObjName3.setObj(3,"Join",500.00);
     ObjName4.setObj(4,"Join",500.00);
     ObjName5.setObj(5,"Join",500.00);
     ObjName6.setObj(6,"Join",500.00);
     ObjName7.setObj(7,"Join",500.00);
     ObjName8.setObj(8,"Join",500.00);
     ObjName9.setObj(9,"Join",500.00);
       
  ObjName1.display();
  ObjName2.display();
  ObjName3.display();
  ObjName4.display();
  ObjName5.display();
  ObjName6.display();
  ObjName7.display();
  ObjName8.display();
  ObjName9.display();

    return 0;
}
