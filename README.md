/* My name : محمد عبد الرؤوف محمد خير سليمان 
CLASS :2nd
Department : هندسة حاسوب */
#include <iostream>
#include <cstring>
using namespace std;
struct student
{
    char name[20];
    char dep[20];
    int roll;
    float mat,avg;
};
int main() 
{
    for(int p = 0; p < 10; ++p)
    {
        if (i < 10)
        {
            do
            {
                cout << "Enter name: ";
                cin >> s[p].name;
                cout << "Enter section: ";
                cin >> s[p].dep;
                cout << "Enter University ID number: ";
                cin >> s[p].roll;
                cout << "Total Marks: ";
                cin >> s[p].mat;
                i = p + 1;
                if (p > 9) {
                    break;
                }
            } while (p < 5);
            cout << endl;
        }
    }
        for(int p = 0; p < 10; ++p)
        {
            cout << "\nName = " << s[p].name << endl;
            if (strcmp(s[p].dep, "A") == 0) {
            cout << "Section = Control Engineering";
            }
            else if (strcmp(s[p].dep, "T") == 0) {
            cout << "Section = Telecomunication Engineering";
            }
            else if (strcmp(s[p].dep, "C") == 0) {
            cout << "Section = Computer Engineering";
            }
            cout << "\nUniversity ID Number = " << s[p].roll << endl;
            s[p].avg = s[p].mat / 8;
            if (s[p].avg >= 90 && s[p].avg <= 100) {
            cout << "Your marks are: " << s[p].avg << "\nGrade = A\n";
            }
            else if (s[p].avg >= 80 && s[p].avg <= 89) {
            cout << "Your marks are: " << s[p].avg << "\nGrade = B\n";
            }
            else if (s[p].avg >= 70 && s[p].avg <= 79) {
            cout << "Your marks are: " << s[p].avg << "\nGrade = C\n";
            }
            else if (s[p].avg >= 60 && s[p].avg <= 69) {
            cout << "Your marks are: " << a[i].avg << "\nGrade = D\n";
            }
            else if (s[p].avg >= 50 && s[p].avg <= 59) {
            cout << "Your marks are: " << s[p].avg << "\nGrade = F\n";
            }
            else {
                cout << "\nGrade not found\n";
            }
        }
    return 0;
}
