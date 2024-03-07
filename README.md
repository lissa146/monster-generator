# monster-generator
#include<iostream>
using namespace std;

void monstergen();//declartion

int main(){
	char input;
	while(1) {//game loop
		//your text based game goes here
		monstergen();
		cout << "press amy key to continuse..." << endl;
		cin >> input;
	}

}

void monstergen() {//defintion
	int num = rand() % 100 + 1;//creates a n8mber between 100-1
	if (num < 15)// 15% chance of witch
		cout << "a squid spawned." << endl;
	else if (num < 20)// 5% chance pf a skele 
		cout << " a furry appeared" << endl;
	else if (num < 50)//30% chance 
		cout << "a mom appeared" << endl;
	else if (num < 75)//%25 chance 
		cout << "a juice box appeared" << endl;
	else if (num < 100)// 25% chance 
		cout << "a tess appeared" << endl;

}  
