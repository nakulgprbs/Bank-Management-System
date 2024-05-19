/// project Bank management system

#include <iostream>
#include <vector>
using namespace std;

class BankAccount{
    private:
        string name;
        int accountNum;
        double balance;
    public:
        BankAccount(string n, int ac, double bal){
            name = n;
            accountNum = ac;
            balance = bal;
        } 
    string getName(){
        return name;
    }
    int getAccountNum(){
        return accountNum;
    }
    int getBalance(){
        return balance;
    }
};
class BankManagement{
    private:
        vector<BankAccount> accounts;
    public: 
        void AddAccount(string name, int accountNum, double balance){
            accounts.push_back(BankAccount(name, accountNum, balance));
        }
};
int main(){
    BankManagement Bank;
    int choice;
    char op;
   do{
               system("cls"); 
                 cout<<"\t\t:: Bank Management System"<<endl;
                 cout<<"\t\t\t\tMain Menu"<<endl;
                 cout<<"\t\t 1. Creat New Account"<<endl;
                 cout<<"\t\t 2. Show All Account"<<endl;
                 cout<<"\t\t 3. Search Account"<<endl;
                 cout<<"\t\t 4. Deposite Money"<<endl;
                 cout<<"\t\t 5. Withdraw Money"<<endl;
                 cout<<"\t\t 6. Exit"<<endl;
                 cout<<"\t\t------------------------------------------"<<endl;
                  cout<<"\t\tEnter your Choice : ";
                  cin>>choice;
      
      switch(choice){
          case 1:
                string name;
                int accountnum;
                double balance;
                cout<<"\t\tEnter name :";
                cin>>name;
                cout<<"\t\tEnter Account Number :";
                cin>>accountnum;
                cout<<"\t\tEnter Initial Balance :";
                cin>>balance;
                Bank.AddAccount(name, accountnum, balance);
                cout<<"\t\t.....Account Created Successfully....."<<endl;
                break;
          
          
      }
      cout<<"\t\t Do you Want to Continue or exit [Yes/No] ??";
      cin>>op;
   }
   while(op == 'y'|| op == 'Y');
      
}
