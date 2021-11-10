# Range-from-start-to-stop
#include <iostream>
using namespace std;

int main()
{
    int range1,range2,num;
    
    cout<<"Start:";
    cin>>range1;
    cout<<"end:";
    cin>>range2;
    cout<<"table of your choice:";
    cin>>num;
    
    
    for(int i=range1;i<=range2;i++)
    {
  
 
  cout<<num*i<<endl;
  
    }
    return 0;
        
    }

