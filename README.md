#include <iostream>
using namespace std;
int main()
{
	char gen;
	float BMR,age,height,weight,TDEE;
	cout << "Enter gender [M of F] : ";
    cin >> gen;
    cout << "Enter height : " ;
        cin >> height;
        cout << "Enter weight : " ;
        cin >> weight;
        cout << "Enter age : " ;
        cin >> age;
         cout << "1 I worked with And do not exercise at all.\n2 Exercise or sports 1-3 days a little over a week.\n3 Moderate exercise or sports 3-5 days for about a week.\n4Exercise or sport seriously. About 6-7 days a week\n5 Exercise or play sports hard every day, morning and evening. \n" ;   
    if (gen == 'F') {
        cout << "Choose Activity " << endl;
        cin >> TDEE;
        BMR = 665 + 9.6 * weight + 1.8 * height - 4.7 * age;
    }
        if (TDEE == 1) {
            cout<<" BMR = "<<BMR;
            BMR=BMR*1.2;
            cout << "BMR = " << BMR << endl;
        } else {
            if (TDEE == 2) {
                 cout<<" BMR = "<<BMR;
                BMR=BMR*1.375;
                cout << "BMR = " << BMR << endl;
            } else {
                if (TDEE == 3) {
                     cout<<" BMR = "<<BMR;
                     BMR=BMR*1.55;
                    cout << "BMR" << BMR  << endl;
                } else {
                    if (TDEE == 4) {
                         cout<<" BMR = "<<BMR;
                         BMR=BMR*1.725;
                        cout << "BMR = " << BMR ;
                    } else {
                        if (TDEE == 5) {
                             cout<<" BMR = "<<BMR;
                             BMR=BMR*1.9;
                            cout << "BMR = " << BMR ;
                        }
                           else if(gen=='M'){
                                 cout << "Choose Activity " << endl; 
                                  cin >> TDEE;
                                  BMR = 66 + (13.7 * weight) + (5 * height) - (6.8 * age);
                                    if (TDEE == 1) {
                                     cout<<" BMR = "<<BMR;
                                    BMR=BMR*1.2;
                                    cout << "BMR = " << BMR << endl;
                                } else {
                                    if (TDEE == 2) {
                                         cout<<" BMR = "<<BMR;
                                        BMR=BMR*1.375;
                                        cout << "BMR = " << BMR << endl;
                                    } else {
                                        if (TDEE == 3) {
                                             cout<<" BMR = "<<BMR;
                                             BMR=BMR*1.55;
                                             cout << "BMR" << BMR  << endl;
                                        } else {
                                            if (TDEE == 4) {
                                                 cout<<" BMR = "<<BMR;
                                                 BMR=BMR*1.725;
                                                cout << "BMR = " << BMR ;
                                            } else {
                                                if (TDEE == 5) {
                                                     cout<<" BMR = "<<BMR;
                                                     BMR=BMR*1.9;
                                                    cout << "BMR = " << BMR ;
                                                }

                            }
                        }
                    }
                }
            }
        }
    }
            }
        }
    
    
}
    

