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
  
#include <iostream>
#include <string>
#include <iomanip>
using std::cout;
using std::cin;
using std::string;
using std::endl;
using std::left;
using std::setw;
using std::setfill;
using std::fixed;
using std::setprecision;
struct studentas {
    string Vardas;
    string Pavarde;
    int nd[20];
    int n;
    int egz;
    float galutinis = 0;
    float vid = 0;
};
int main()
{
    int StudSkai = 0;
    cout << "Iveskite studentu skaiciu" << endl;
    cin >> StudSkai;
    studentas* grupe = new studentas[StudSkai];
    for (int i = 0; i < StudSkai; i++) {
        cout << "Iveskite studento varda ir pavarde" << endl;
        cin >> grupe[i].Vardas >> grupe[i].Pavarde;
		cout << "Iveskite studento pazymiu kieki" << endl;
		cin >> grupe[i].n;
        cout << "Iveskite studento pazymius" << endl;
        for (int j = 0; j < grupe[i].n; j++) {
            cin >> grupe[i].nd[j];
            grupe[i].vid = grupe[i].vid + (float)grupe[i].nd[j];
        }
        cout << "Iveskite studento egzamino rezultata" << endl;
        cin >> grupe[i].egz;
        grupe[i].galutinis = grupe[i].vid / (float)grupe[i].n;
        grupe[i].galutinis = grupe[i].galutinis * 0.4 + (float)grupe[i].egz * 0.6;
    }
    cout << left << setw(15) << setfill(' ') << "Vardas";
    cout << left << setw(15) << setfill(' ') << "Pavarde";
    cout << left << setw(16) << setfill(' ') << "Galutinis (Vid.)" << endl;
    cout << "----------------------------------------------" << endl;
    for (int i = 0; i < StudSkai; i++) {
        cout << left << setw(15) << setfill(' ') << grupe[i].Vardas;
        cout << left << setw(15) << setfill(' ') << grupe[i].Pavarde;
        cout << left << setw(16) << setfill(' ') << fixed << setprecision(2) << grupe[i].galutinis << endl;
    }
    delete[] grupe;
    char a;
	cin >> a;
}
  
  
     
     
  
