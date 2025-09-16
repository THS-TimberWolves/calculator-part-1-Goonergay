#include <iostream>

using namespace std;
int main(){
char op;
float x, y, ans;
std::cout << "Type mathematical operation: ";
std::cin >> op;

std::cout << "Type first number: ";
std::cin >> x;
std::cout << "Type second number: ";
std::cin >> y;


if (op == "+") {
    ans = x + y;
}
else if (op == "-") {
    ans = x - y;
}
else if (op == "*") {
    ans = x * y;
}
else if (op == "/") {
    if (y = 0) {
        std::cout << "Answer is undefined";
    }
    else {
        ans = x / y;
    }
    
}
cout << ans << "is your Answer if you were using" << op << "with these numbers" << x << "," << y << "\n";

return 0;
}
