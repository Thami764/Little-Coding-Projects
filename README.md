# Little-Coding-Projects
Coding Projects from various sites/school/ my own imagination
#Project to exchange currencies using C++


#include <iostream>

int main() {

  //variables for different currencies
  double pesos;
  double reais;
  double soles;
  double dollars;


  //User input number of each currency
  std::cout<<"Enter number of Colombian Pesos: ";
  std::cin>>pesos;
  //Peso conversion,.05 of USD


  std::cout<<"Enter number of Brazilian Reais: ";
  std::cin>>reais;
  //reais conversion,.18 of USD

  std::cout<<"Enter number of Peruvian soles: ";
  std::cin>>soles;
  //Peruvian soles conversion,.28 of USD

  dollars=(.05*pesos)+(.18*reais)+(.28*soles);
  std::cout<<"US Dollars=$"<<dollars<<"\n";
  
  
}
