#include <iostream>
#include<cmath>
#include<cstring>
using namespace std;

unsigned int multiply (unsigned x, unsigned y){
    int prod =0;
    while(y-- >0)prod+=x;                      //function
    return prod;
    }

int main()
{
    unsigned int a=2,b=3,c;

    //computed by '*' operator
      c=a*b;
    cout <<"answer="<< c<<endl;

    //computed by multiply function
    unsigned int d=multiply(a,b);
     cout <<"answer="<<d<<endl;
    return 0;
}

typedef struct _string{char *str}; string;
string operator+(const string& s1,const string& s2)
string s;
s.str=(cha r*)malloc(strlen(s1.str))+(strlen(s1.str)+1);
strcpy(s.str,s1.str);
strcpy(s.str,s2.str);
return s;

}
int main()
{
    string fname ,lname ,name;
    fname.str=strdup("partha");
    lname.str=strdup("das");

    name=fname+lname;
    cout<<"first name:"<<fname.str<<endl;
    cout<<"last name:"<<lanme.str<<endl;
    cout<<"full name:"<<name.str<<endl;
    return 0;
    }
