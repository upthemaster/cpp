#include<iostream>
#include<iomanip>
using namespace std;
//Task 1: Define the Class
class BankAccount{
	private:
		string accountHolder;
		int accountNumber;
		string accountType;
		double balance;
	//Task 2: Implement Constructors
	public:
		//Default Constructor
		BankAccount(){
			accountHolder="Aditya Suryakar";
			accountNumber=123456;
			accountType="Savings";
			balance=5000.00;
		}
		//Parameterized Constructor
		BankAccount(string name,string type,int num,double bal){
			accountHolder=name;
			accountNumber=num;
			accountType=type;
			balance=bal;
		}
		//Task 3:Implement Accessor & Mutator Methods
		//getter function
		void getAccountHolder(){
			cout<<"Holder:"<<accountHolder<<endl;
		}
		void getAccountNumber(){
			cout<<"Account Number:"<<accountNumber<<endl;
		}
		void getAccounttype(){
			cout<<"Account Type:"<<accountType<<endl;
		}
		//setter function
		void setBalance(string newType){
			newType=accountType;
		}
		void setAccountType(string newType)
		{
			accountType=newType;
		}
		//task 4 : Implement Functional Methods
		void Deposit(int Bal)
		{	cout<<"depositing "<<Bal<<endl;
			balance=balance+Bal;
			cout<<"Current balance : "<<balance<<endl<<endl;
		}
		//withdrawl amount function 
		void Withdrawl(int bal)
		{
			if(bal<balance)
			{	cout<<"withrawing "<<bal<<endl;
				balance=balance-bal;
				cout<<"Current balance : "<<balance<<endl<<endl;
			}
			else
			{
				cout<<"You have not sufficient amount to withdrawl"<<endl;
			}
		}
		//display all information function
		void display()
		{
			cout<<"Account Details : "<<endl;
			cout<<"Holder : "<<accountHolder<<endl;
			cout<<"Account Number : "<<accountNumber<<endl;
			cout<<"Type : "<<accountType<<endl;
			cout<<"Balance : "<<balance<<endl<<endl;
			cout<<"Thank You!"<<endl;
		}
		
};
//Task 5: Test the Class in main() Function
int main()
{	
	//object 1 is created
	
	BankAccount b1;
	b1.setAccountType("Savings");
	b1.display();
	b1.Deposit(5000.00);
	b1.Withdrawl(4500);
	cout<<"Final: ";
	b1.display();
	
	//object 2 is created
	
	BankAccount b2("Sourabh Patil","Current",78945,5000);
	b2.display();
	b2.Deposit(2000);
	b2.Withdrawl(1000);
	cout<<"Final: ";
	b2.display();
}
    

					
		
