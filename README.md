#include<iostream>
using namespace std;
class car
{
	bool startengine;
	public:
		void start()
		{
			startengine=true;
			cout<<"engine started "<<endl;
		}
		void drive()
		{
		
		   if(startengine)
	     	{
			cout<<"you are ready to drive ";
		    }
		    else
		    {
		    	cout<<"you cannot drive car ";
			}
		}
		
};
int main()
{
	car c;
	c.start();
	c.drive();
}
