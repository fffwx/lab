#include <iostream>
#include <string>
int main() {
  int price;
  std::string Productname;
  
  std::cout <<"Введіть назву продукту: ";
  std::cin >> Productname;
  
  std::cout << "Введіть ціну продукту: ";
  std::cin >> price;
  
  std::cout << "Ви внесли продукт: ( " << Productname << " ) з ціною: "<<
         price << std::endl;

    return 0;
}