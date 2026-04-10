# pz11


<img width="1252" height="454" alt="image" src="https://github.com/user-attachments/assets/f2c52336-7c3f-4674-8c1c-4ed5a14edc27" />


## Задание 1
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    int i = 1;
    while (n >= i) {
    cout << i <<" ";
    i++;   
    }
    // Ваш код:


    return 0;
}
```


## Задание 2
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    int i;
    i = 1;
    int y;
    y = 0;
    while (n >= i) {
    y = y + i;
    i++;
    }
    // Ваш код:
    cout << y;

    return 0;
}
```



## Задание 3
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    // Ваш код:
    int n, s = 0;
    cin >> n;
    while (n != 0){
    s += n;
    cin >> n;
    }
    cout << s;

    return 0;
}
```



## Задание 4
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");
    int n;
    cin >> n;
    int i = 2;

    while (i <= n) {
    cout << i << " ";
    i = i + 2;
    }
    
    // Ваш код:


    return 0;
}
```



## Задание 5
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    int i = 1;
    int y = 1;
    while (n >= i) {
    y = y * i;
    i++ ;
    }
    // Ваш код:
    cout << y;

    return 0;
}
```



## Задание 6
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    int i = 0;
    while (n != 0) {
    i++;
    n/=10;
    
    }
    // Ваш код:

    cout<<i;
    return 0;
}
```



## Задание 7
```

#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");
    
    int n;
    cin >> n;
    
    if (n <= 1) {
        cout << "Не простое";
        return 0;
    }
    if (n == 2) {
        cout << "Простое";
        return 0;
    }
    if (n % 2 == 0) {
        cout << "Не простое";
        return 0;
    }

    int P = 0;
    int i = 3; 

    while (i * i <= n) {
        if (n % i == 0) {
            P = 1;
            break;
        }
        i += 2; 
    }
    
    if (P == 1) {
        cout << "Не простое";
    } else {
        cout << "Простое";
    }
    
    return 0;
}
```



## Задание 8
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");


    int n;
    cin >> n;
    int i = 1;
    int y = 1;
    // Ваш код:
    while (n >= i) {
    int x = 1;
        while (x <= n) {
            cout << (i * x) << " ";
            x++;
        }
    cout << endl;
    i++;
    
    }

    return 0;
}
```
