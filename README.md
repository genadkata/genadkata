#include<iostream>
using namespace std; 
class phonebook
	{
		public:
			   bool name;
			   bool surname;
			   int number;
			   int egn;
			   int showFullList(); 
			   int addconctact();
			   int deletecontact();
			   int searchcontact();
			   int editcontact();
}
void phonebook::showFullList()    
{
	phonebook people[50];
	int flag=0;
	for(int i=0; i<50; i++)
	{
            if(people[i].name)
                    flag = 1;

            if(!flag)
                    cout << "No contacts found!" << endl;
  }                                                     
}
void phonebook::addconctact()
{ 

}
void phonebook::deletecontact()
{ 

}
void phonebook::searchcontact()
{
	
}
void phonebook::editcontact()
{
	
}
int main()
{
int people[50] = phonebook;
phonebook telefon;
int menu;
do
	{
    cout << "Main Menu\n";
    cout << "Please make your selection\n";
    cout << "1 - show full list\n";
    cout << "2 - create new contact\n";
    cout << "3 - search contact\n";
    cout<<"4- edit contact\n";
    cout << "enter your choice\n";
    cin >> menu;

         switch(menu) 
		 {
           case 1:
             cout << "function1";
             break;
           case 2:
             cout <<"function2";
             break;
           case 3:
             cout << "function3";
             break;
           case 4:
             cout << "function4";
             break;
           default:
             cout << "Main Menu\n";
             cout << "Please make your selection\n";
             cout << "1 - show full list\n";
             cout << "2 - create new contact\n";
             cout << "3 - search contact\n";
             cout<<"4- edit contact\n";
            cout << "enter your choice";
            cin >> menu;
         }
      } while(menu !=4);                            
    system("PAUSE");
}	
