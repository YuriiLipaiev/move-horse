# move-horse
#include <iostream>

int main()
{
    int x1, y1, x2, y2;
    int dx, dy;

    std::cout << std::endl;

    std::cout << "  1__2__3__4__5__6__7__8_x/y\n";
    std::cout << "1|__|__|__|__|__|__|__|__|\n";
    std::cout << "2|__|__|__|__|__|__|__|__|\n";
    std::cout << "3|__|__|__|__|__|__|__|__|\n";
    std::cout << "4|__|__|__|__|__|__|__|__|\n";
    std::cout << "5|__|__|__|__|__|__|__|__|\n";
    std::cout << "6|__|__|__|__|__|__|__|__|\n";
    std::cout << "7|__|__|__|__|__|__|__|__|\n";
    std::cout << "8|__|__|__|__|__|__|__|__|\n";



    std::cout << std::endl;
    std::cout << "Enter numbers from 1 to 8. \n";
    std::cout << "Enter x1: ";
    std::cin >> x1;

    std::cout << std::endl;

    std::cout << "Enter y1: ";
    std::cin >> y1;

    std::cout << std::endl;

    std::cout << "Enter x2: ";
    std::cin >> x2;

    std::cout << std::endl;

    std::cout << "Enter y2: ";
    std::cin >> y2;

    if (x1 > 8 or x1 <= 0 or y1 > 8 or y1 <= 0 or x2 > 8 or x2 <= 0 or y2 > 8 or y2 <= 0)
    {
        std::cout << std::endl;
        std::cout << "Enter correct data, numbers from 1 to 8.\n";

    }

     else
     {

    dx = abs(x1 - x2);
    dy = abs(y1 - y2);

    std::cout << std::endl;

    if (dx == 1 and dy == 2 or dx == 2 and dy == 1)
   {
      std::cout << " YES ";
   }
    else
    {
       std::cout << " NO ";
    }

     }

    std::cout << std::endl;

    return 0;
}
