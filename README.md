# print-triangle-shape-star

#include <iostream>
using namespace std;
    
int main() 
{
    int i,n,b;
    cin>>n;
    
    for(i=1;i<=n;i++)
    {
      for(b=1;b<i+1;b++)
      {
        cout<< "*";  
      }
        cout<<endl;
    }
    }
