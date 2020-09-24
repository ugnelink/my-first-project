# my-first-project
project
// Mano mas DB.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
  
  
  using std::count;
  using std::cin;
  using std::string;
  struct duomuo {
     string Vard;
     string Pav;
     int paz[10]
     int egz;
     float GP;
 };
 
 int main()
 {
     duomuo Eil; duomuo Eil_mas[5];
     std::vector<duomuo> Eil_vect;
     cout << ''Sveiki iveskite Eil duom.:\n'';
     cin>>Eil.Vard>>Eil.Pav>>Eil.egz;
     for (int i = 0; i < 5; i++) 
         cin >> Eil.paz[i];
         Eil.GP = Eil.GP + (float)Eil.paz[i];
  }
  Eil.GP = Eil.GP / 5.0;
  Eil.GP = Eil.GP * 0.4 + 0.6 * Eil.egz;
  cout << ''ivesta:'' << Eil.Vard << '' '' << Eil.Pav << '' '' << Eil.egz;
  for (int i = 0; i < 5; i++) cout<<'' ''<< Eil.paz[i];
  cout << '' '' << Eil.GP << std::end1;
                                     
  Eil_vect.push_back(Eil); // su indeksu 0
  Eil_vect.push_back(Eil); // su indeksu 1
  
  Eil.vect[1].GP = 25;
  cout << std::end1<< std::end1;
  for (int j=0; j < 2; j++) {
      cout << ''ivesta:'' << Eil_vect[j].Vard << '' '' << Eil_vect[j].Pav << '' '' << Eil_vect[j].egz;
      for (int i = 0; i < 5; i++) cout << '' '' << Eil_vect[j].paz[i];
      cout << '' '' << Eil_vect[j].GP << std::end;
  }
  char a;
  cin >> a;
  Eil_vect.clear();
  
     
     
  
