Write a program to check number palindrome and string palindrome.
NUMBER PALINDROME:
#include <iostream>
using namespace std;

int main()
{
    int n, r, temp, sum = 0;

    cout << "Enter the number = ";
    cin >> n;

    temp = n;

    while (n > 0)
    {
        r = n % 10;
        sum = (sum * 10) + r;
        n = n / 10;
    }

    if (temp == sum)
        cout << "The number is Palindrome";
    else
        cout << "The number is not Palindrome";

    return 0;
}
OUTPUT:
Enter the number = 121
The number is Palindrome

STRING PALINDROME:
#include <iostream>
#include <string>
using namespace std;

int main()
{
    string str;
    int i, len, flag = 0;

    cout << "Enter a string = ";
    cin >> str;

    len = str.length();

    for (i = 0; i < len / 2; i++)
    {
        if (str[i] != str[len - 1 - i])
        {
            flag = 1;
            break;
        }
    }

    if (flag == 0)
        cout << "The string is Palindrome";
    else
        cout << "The string is not Palindrome";

    return 0;
}
OUTPUT:
Enter a string = madam
The string is Palindrome
