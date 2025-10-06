// Program-1
#include <iostream>
using namespace std;

int main() {
    float n1, n2, ans;

    cout << "Enter values of numbers 1 & 2: ";
    cin >> n1 >> n2;

    try {
        if (n2 == 0) {
            throw n2; // exception throw kiya
        } else {
            ans = n1 / n2;
            cout << "Answer = " << ans << endl;
        }
    }
    catch (float num) {
        cout << "\nERROR: Division by " << num << endl;
    }

    return 0;
}

//Enter values of numbers 1 & 2: 10 2
//Answer = 5

//Enter values of numbers 1 & 2: 8 0
//ERROR: Division by 0
