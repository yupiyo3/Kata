#include <iostream>
#include <cmath>

using namespace std;
int main()
{
    // Задание 1

    setlocale(LC_ALL, "Rus");
    try
    {

        cout << "Задание 1" << endl;
        double t, l;
        cout << "Введите значение переменной t " << endl;
        cin >> t;
        cout << "Введите значение переменной l " << endl;
        cin >> l;
        cout << "R = " << 3 * pow(t, 2) + 3 * pow(l, 5) + 4.9 << endl;
    }
    catch (const std::exception&)
        {
            cout << "Ошибка входных данных" << endl;
        }

    // Задание 2

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 2" << endl;
        const double e { 2.72 };
        double p, y;
        cout << "Введите значение переменной p " << endl;
        cin >> p;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "K = " << log (pow(p, 2) + pow(y, 3)) + pow(e, p)<< endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 3

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 3" << endl;
        double n, y;
        cout << "Введите значение переменной n " << endl;
        cin >> n;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "G = " << n * (y + 3.5) + sqrt (y) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 4

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 4" << endl;
        double a, t;
        cout << "Введите значение переменной a " << endl;
        cin >> a;
        cout << "Введите значение переменной t " << endl;
        cin >> t;
        cout << "D = " << 9.8 * pow(a,2) + 5.52 * cos (pow(t,5)) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }
  
    // Задание 5

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 5" << endl;
        double x;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "L = " << 1.51 * cos (pow(x, 2)) + 2 * pow(x, 3) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 6

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 6" << endl;
        const double e { 2.72 };
        double x, y;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "M = " << cos (2) * y + 3.6 * pow(e,x) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 7

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 7" << endl;
        double m;
        cout << "Введите значение переменной m " << endl;
        cin >> m;
        cout << "N = " << pow (m,2) + 2.8 * fabs(m) + 0.55 << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 8

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 8" << endl;
        double y;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "T = " << sqrt (fabs(6 * pow(y,2) - 0.1 * y + 4))<< endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 9

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 9" << endl;
        double x, y;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "V = " << log (y + 0.95) + sin(pow(x,4))<< endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 10

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 10" << endl;
        const double e { 2.72 };
        double x, y, k;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Введите значение переменной k " << endl;
        cin >> k;
        cout << "U = " << pow(e,y) + 7.355 * pow(k,2) + pow (sin(x),2) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 11

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 11" << endl;
        double x, y;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "S = " << 9.756 * pow(y,7) + 2 * tan(x) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 12

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 12" << endl;
        double x, t;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "Введите значение переменной t " << endl;
        cin >> t;
        cout << "K = " << 7 * pow(t,2) + 3 * pow (sin(x),3) + 9.2 << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 13

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 13" << endl;
        double y;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "E = " << sqrt(fabs(3 * pow(y,2) + 0.5 * y + 4)) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 14

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 14" << endl;
        const double e { 2.72 };
        double x, y;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "R = " << fabs(sqrt(pow(sin(y),2) * y + 6.835) + pow(e,x))<< endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 15

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 15" << endl;
        double y;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "H = " << pow(sin(y), 2) - 2.8 * y + sqrt(fabs(y)) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 16

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 16" << endl;
        double y;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "S = " << sqrt(cos (4) * pow(y,2) + 7.151)  << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 17

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 17" << endl;
        double y;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "N = " << 3 * pow(y,2) + sqrt(y+1)<< endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 18

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 18" << endl;
        double y;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Z = " << 3 * pow(y, 2) + sqrt(pow(y,3) + 1) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 19

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 19" << endl;
        double n, y, g;
        cout << "Введите значение переменной n " << endl;
        cin >> n;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Введите значение переменной g " << endl;
        cin >> g;
        cout << "P = " << n * sqrt((pow(y,3) + 1.09 * g)) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 20

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 20" << endl;
        const double e { 2.72 };
        double x, y, k;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Введите значение переменной k " << endl;
        cin >> k;
        cout << "U = " << pow(e, k+y) + tan (x) * sqrt(y) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 21

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 21" << endl;
        const double e{ 2.72 };
        double y, h;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Введите значение переменной h " << endl;
        cin >> h;
        cout << "P = " << pow(e, y + 5.5) + 9.1 * pow (h,3) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 22

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 22" << endl;
        double u, y, x;
        cout << "Введите значение переменной u " << endl;
        cin >> u;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "T = " << sin (2 * u) * log (2 * pow (y,2) + sqrt (x))<< endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 23

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 23" << endl;
        const double e { 2.72 };
        double y, f;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Введите значение переменной f " << endl;
        cin >> f;
        cout << "G = " << pow(e, 2 * y) + sin (f) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 24

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 24" << endl;
        double y;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "F = " << 2 * sin(0.214 * pow(y,5) + 1) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 25

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 25" << endl;
        const double e{ 2.72 };
        double y, f;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Введите значение переменной f " << endl;
        cin >> f;
        cout << "G = " << pow (e, 2 * y) + sin (pow(f,2)) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 26

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 26" << endl;
        double p;
        cout << "Введите значение переменной p " << endl;
        cin >> p;
        cout << "Z = " << sin (pow((pow(p,2) + 0.4),3)) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 27

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 27" << endl;
        const double e{ 2.72 };
        double v, x, y;
        cout << "Введите значение переменной v " << endl;
        cin >> v;
        cout << "Введите значение переменной x " << endl;
        cin >> x;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "W = " << 1.03 * v + pow(e, 2 *y) + tan (fabs(x))  << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 28

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 28" << endl;
        const double e{ 2.72 };
        double y, h;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Введите значение переменной h " << endl;
        cin >> h;
        cout << "T = " << pow(e, y + h) + sqrt(fabs(6.4 * y)) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 29

    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 29" << endl;
        double y;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "N = " << 3 * pow(y,2) + sqrt(fabs(y+1)) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    // Задание 30


    setlocale(LC_ALL, "Rus");
    try
    {
        cout << "Задание 30" << endl;
        const double e { 2.72 };
        double y, r;
        cout << "Введите значение переменной y " << endl;
        cin >> y;
        cout << "Введите значение переменной r " << endl;
        cin >> r;
        cout << "W = " << pow(e, y+r) + 7.2 * sin (r) << endl;
    }
    catch (const std::exception&)
    {
        cout << "Ошибка входных данных" << endl;
    }

    system("pause");
}
