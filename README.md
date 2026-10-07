# c-
// C++ Programming Language
// C++ Syntax

#include <iostream>// gives access to std::cout, std:: cin
#include <iostream>
using namespace std;

int main() 
{
   std::cout <<"Hello, World!" << std::endl;
   return 0;
}
// Variables, Types, and I/O
#include <iostream>
#include string
suing namespace std;

int main (){
    // ---Declaring variables off diff. types-----
    int             age       =       20     ;
     ^               ^        ^       ^      ^
     data types      VA       EQ      val    close tag
     double price  = 20.20;
     float weight = 65.5f;
     char grade = 'A';
     bool isStudent = 'true';
     string name = "Cortez";

     //OUTPUT OF YOUR INPUT
     cout<<"Name: " <<name<<endl;
     cout<<"Age: " <<age<<endl;
     cout<<"Price: " <<price<<endl;
     cout<<"Weight: " <<weight<<endl;
     cout<<"Grade: " <<grade<<endl;
     cout<<"Is Student?: " <<isStudent<<endl;


     //---Getting input using cin---
string userCity;
cout<<"\nEnter your city: ";
cin >> userCity; // read on word (stops at whitespace)
cout<<"You live in:"<<userCity << endl;

//-- reading a full line including spaces
cin.ignore(); //clear leftover newline character from previous cin
string fullSentence;
cout<<"I am lucas: ";
getline(cin, fullSentence); //read the entire line
cout<<"You said: " <<fullSentence <<endl;

return 0;

//control flow (if/else, switch, loops)
#include <iostream>
using namespace std;

int main(){
    //---if/else if / else condition
    int score;
    cout<<"Enter your exam score: ";
    cin >> score;

    if (score >=90){
        cout <<"Grade: A" endl;
    }else if (score >= 80){
        cout <<"Grade: B"endl;
    }else if (score >= 70){
        cout <<"Grade: C"endl;
    } else {
        cout << "Grade: F"<<endl;
    }
    //Switch case statement
int day;
cout <<"\nEnter a day number (1-7):";
cin >> day;

       switch (day){
        case 1: cout <<"Monday"<<endl;break;
        case 2: cout <<"Tuesday"<<endl;break;
        case 3: cout <<"Wednesday"<<endl;break;
        case 4: cout <<"Thursday"<<endl;break;
        case 5: cout <<"Friday"<<endl;break;
        case 6: cout <<"Saturday"<<endl;break;
        case 7: cout <<"Sunday"<<endl;break;
        default: cout <<"invalid day"<< endl; break;
       }
// for loop
cout<< "\nCounting 1 to 5 with a for loop: " <<endl;
for (int i =1;<=5; i++){
    cout <<i<< " ";
}
// while loop
cout<< "\nCounting down form 5 with a while loop:" <<endl;
int n = 5;
while (n > 0){
    cout<<n<<;
    n--;
}
cout << endl;

// dp while loop (runs at least once)
cout<<"\ndo-while example:"<<endl;
int x = 0;
do{
    cout<< "x = "<<x<< endl;
    x++;
}while (x <3)

// break and continue
cout<<"nSkipping 3 using continue, stopping at 7 using break: " <<endl;
for (int i =1; i<=10; i++){
    if (i == 3); continue' // skip this iteration
    if (i == 7)break; // exit the loop
    cout << i <<" ";
}
cout<< endl;

return 0;
}
