//Зубарев Евгений Дмитривич (9/2-РПО-24/2)
#include <iostream>
#include <cmath>
//(использовал к Task 4,Task 5,Task 6,Task 7)
#include <iomanip>
// (Использовал к Task 5,Task 6,Task 7,Task 8,Task 9)
using namespace std;
// Task 1----------------------
// int main() {
//     double a, b;
    
//     cin >> a >> b;
    
//     double S = a * b;
//     double P = 2 * (a + b);
    
//     cout << "Площадь: S = " << S << endl;
//     cout << "Периметр: P = " << P << endl;
    
//     return 0;
// } 
// Task 2----------------------
//     double a, b, c;
    
//     cin >> a >> b >> c;
    
//     double V = a * b * c;
//     double S = 2 * (a*b + b*c + a*c);
    
//     cout << "V = " << V << endl;
//     cout << "S = " << S << endl;
    
//     return 0;
// }
// Task 3--------------------------
//     double a, b;

//     cin >> a >> b;

//     double a2 = a * a;
//     double b2 = b * b;
    
//     cout << "Квадраты: " << a << "² = " << a2 << ", " << b << "² = " << b2 << endl;
//     cout << "Сумма: " << a2 + b2 << endl;
//     cout << "Разность: " << a2 - b2 << endl;
//     cout << "Произведение: " << a2 * b2 << endl;
//     cout << "Частное: " << a2 / b2 << endl;
    
//     return 0;
// }
// Task 4----------------------------
//     double a, b;
    
//     cout << "Введите два ненулевых числа: ";
//     cin >> a >> b;

    
//     double abs_a = abs(a);
//     double abs_b = abs(b);
    
//     cout << "Модули: |" << a << "| = " << abs_a << ", |" << b << "| = " << abs_b << endl;
//     cout << "Сумма: " << abs_a + abs_b << endl;
//     cout << "Разность: " << abs_a - abs_b << endl;
//     cout << "Произведение: " << abs_a * abs_b << endl;
//     cout << "Частное: " << abs_a / abs_b << endl;
    
//     return 0;
// }
// Task 5--------------------
//     double a, b;

//     cin >> a >> b;

    
//     double c = sqrt(a * a + b * b);
//     double P = a + b + c;
    
//     cout << fixed << setprecision(2); 

//     cout << "Гипотенуза: c = " << c << endl;
//     cout << "Периметр: P = " << P << endl;
    
//     return 0;
// }
// Task 6-----------------------
//     double x1, y1, x2, y2;

//     cin >> x1 >> y1 >> x2 >> y2;

//     double distance = sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));

//     cout << fixed << setprecision(2);
//     cout << " (" << x1 << ", " << y1 << ") и (" 
//          << x2 << ", " << y2 << ") = " << distance << endl;
    
//     return 0;
// }
// Task 7-----------------------
//     double x1, y1, x2, y2, x3, y3;

//     cin >> x1 >> y1;
//     cin >> x2 >> y2;
//     cin >> x3 >> y3;

//     double a = sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));

//     double b = sqrt(pow(x3 - x2, 2) + pow(y3 - y2, 2));

//     double c = sqrt(pow(x1 - x3, 2) + pow(y1 - y3, 2));

//     double P = a + b + c;
//     double p = P / 2;
//     double S = sqrt(p * (p - a) * (p - b) * (p - c));

//     cout << fixed << setprecision(2);
//     cout << "Стороны треугольника: " << a << ", " << b << ", " << c << endl;
//     cout << "Периметр: " << P << endl;
//     cout << "Площадь: " << S << endl;
//     return 0;
// }
// Task 8---------------------------
//     double ft;
    
//     cout << "Введите температуру в °F: ";
//     cin >> ft;
    
//     double cs = (ft - 32) * 5.0 / 9.0;
    
//     cout << fixed << setprecision(1);
//     cout << ft << " °F = " << cs << " °C" << endl;
    
//     return 0;
// }
// Task 9----------------------------
//     double X, A, Y, B;
    
//     cout << "Введите X, A, Y, B (через пробел): ";
//     cin >> X >> A >> Y >> B;
    
//     double price1 = A / X;
//     double price2 = B / Y;
//     double ratio = price1 / price2;
//     cout << fixed << setprecision(2);
//     cout << "1 кг шоколадных конфет: " << price1 << " руб." << endl;
//     cout << "1 кг ирисок: " << price2 << " руб." << endl;
//     cout << "Шоколадные конфеты дороже в " << ratio << " раз" << endl;
    
//     return 0;
// }
// Task 10----------------------
//     int A, B;
    
//     cout << "Введите A и B (A > B > 0): ";
//     cin >> A >> B;

//     int count = A / B;
//     cout << "На отрезке " << A << " помещается " << count << " отрезков длины " << B << endl;
    
//     return 0;
// }
// Task 11----------------------
//     int n;
 
//     cout << "Введите трехзначное число: ";
//     cin >> n;

//     int a = n / 100;      
//     int b = (n / 10) % 10; 
//     int c = n % 10;        
    
//     cout << "Сумма: " << a + b + c << endl;
//     cout << "Произведение: " << a * b * c << endl;  
//     return 0;
// }
// Task 12----------------------
//     int n;

//     cout << "Введите число > 999: ";
//     cin >> n;
    
//     int hundreds = (n / 100) % 10;
//     cout << "Сотни: " << hundreds << endl;
    
//     return 0;
// }
// Task 13----------------------
//     int seconds;
    
//     cout << "Введите N секунд: ";
//     cin >> seconds;

//     int hours = seconds / 3600;
//     cout << "Полных часов: " << hours << endl;
    
//     return 0;
// }
// Task 14----------------------
//     int days;
//     cout << "Введите день года (1-365): ";
//     cin >> days;

//     int day = (days - 1) % 7;
    
//     string days7[] = {"воскресенье", "понедельник", "вторник", "среда", "четверг", "пятница", "суббота"};
    
//     cout << days<< "-й день года - " << days7[day] << " (день недели " << day << ")" << endl;
    
//     return 0;
// }
// Task 15----------------------
//     int A, B;
    
//     cout << "Введите два числа A и B: ";
//     cin >> A >> B;
    
//     bool result = (A % 2 != 0) && (B % 2 != 0);
    
//     cout << "Оба числа нечетные: " << boolalpha << result << endl;
    
//     return 0;
// }
// Task 16----------------------
//     int A и B;
    
//     cout << "Введите два числа A , B , C: ";
//     cin >> A >> B;
    
//     bool result = (A % 2) == (B % 2) ;
    
//     cout << "Четность чисел одинакова: " << boolalpha << result << endl;
    
//     return 0;
// }
// Task 17----------------------
//     int A, B, C;
    
//     cout << "Введите три числа A, B, C: ";
//     cin >> A >> B >> C;
    
//     int count = 0;
//     if (A > 0) count++;
//     if (B > 0) count++;
//     if (C > 0) count++;
    
//     bool result = (count == 2);
    
//     cout << "Два положительных числа: " << boolalpha << result << endl;
//     cout << "Найдено положительных: " << count << endl;
    
//     return 0;
// }
// Task 18----------------------
//     int A, B, C;
    
//     cout << "Введите три числа A, B, C: ";
//     cin >> A >> B >> C;
    
//     bool result = (A == -B) || (A == -C) || (B == -C);
    
//     cout << "Есть пара взаимно противоположных чисел: " << boolalpha << result << endl;
    
//     return 0;
// }
// Task 19----------------------
//     int n;
    
//     cout << "Введите трехзначное число: ";
//     cin >> n;

//     int a = n / 100;
//     int b = (n / 10) % 10;
//     int c = n % 10;
    
//     bool result = (a < b) && (b < c);
    
//     cout << " Возрастающая последовательность: " << boolalpha << result << endl;
    
//     return 0;
// }
// Task 20----------------------
//     double x, y;
    
//     cout << "Введите координаты x и y: ";
//     cin >> x >> y;
    
//     bool result = (x < 0);
    
//     cout <<  x << ", " << y ;
//     cout << (result ? "лежит" : "не лежит");
//     cout << " во второй или третьей четверти" << endl;
    
//     return 0;
// }
