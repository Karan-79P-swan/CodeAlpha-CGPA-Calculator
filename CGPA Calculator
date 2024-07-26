#include<iostream>
#include<conio.h>
using namespace std;

void CalculateGPA() //fuction of calculating GPA of every semesters
{
  int NoOfSubs;
  double credits[NoOfSubs];
  double points[NoOfSubs];
  double sum = 0;
  double total;
  double total_Credits = 0;
  system("cls");
  cout<<"------------------------------------------------"<<endl;
  cout<<"|                GPA CALCULATOR                 "<<endl;
  cout<<"------------------------------------------------"<<endl;
  cout<<"Enter No of Subjects: ";
  cin>>NoOfSubs;
  cout<<endl;
  for(int i=1;i<=NoOfSubs;i++)
  {
    cout<<"Enter Credits of Subjects:"<<i<<": ";
    cin>>credits[i];
    cout<<"Enter Points of Subjects:"<<i<<":";
    cin>>points[i];
    cout<<"------------------------------------------------"<<endl;

  }
  for(int i=1;i<=NoOfSubs;i++)
  {
    total=credits[i]*points[i];
    sum += total;
  }
  for(int i=1;i<=NoOfSubs;i++)
  {
    total_Credits += credits[i];
  }
  cout<<endl<<endl;
  cout<<"Total Points: "<<sum<<endl;
  cout<<"Total Credits: "<<total_Credits<<endl;
  cout<<"Total GPA: "<<sum/total_Credits<<endl;

  cout<<"\nPress any key to go back to Main Menu...";
  getch();
}

void calculateCGPA()  // Function of finding overall CGPA 
{
    int NoOfSems;
    system("cls");
  cout<<"------------------------------------------------"<<endl;  // decorating statements
  cout<<"|                CGPA CALCULATOR                 "<<endl;
  cout<<"------------------------------------------------"<<endl;

  cout<<"Enter No of Semesters: ";
  cin>>NoOfSems;
  double semsters[NoOfSems];
  double semTotal=0;
  for(int i=1;i<=NoOfSems;i++)
  {
    cout<<"Enter Semesters #"<<i<<"GPA : ";
    cin>>semsters[i];

  }
  for(int i=1;i<=NoOfSems;i++)
  {
    semTotal += semsters[i];
  }
  cout<<"Your CGPA :"<<semTotal/NoOfSems<<endl;

  cout<<"\n Press any key to go back to Main Menu...";
  getch();
}

int main(){
    do
    {
        system("cls");
        cout<<"------------------------------------------------"<<endl;
        cout<<"|                 CALCULATOR                 "<<endl;
        cout<<"------------------------------------------------"<<endl;
        cout<<"1. GPA CALCULATOR"<<endl;
        cout<<"2. CGPA CALCULATOR"<<endl;
        
        cout<<endl;
        cout<<"SELCT AN OPTION AS PER YOUR WISH: ";
        char op;
        cin>>op;

        if(op == '1')CalculateGPA();
         else if(op == '2') calculateCGPA();
         else if(op == '3') exit(0);
    } while (1);
    
    return 0;
    
}
