# Pak-wheels_project
#include<iostream>
using namespace std;

int usedcars();
int newcars();
int bikes();
int autostores();
int contact();
int help();

int main()

{
	cout<<"\n \n";
	cout<<"\t  [][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][]"<<endl;     
	cout<<"\t  []                                                                                                []"<<endl;
	cout<<"\t  []  []()()    []       []  []  []     []     [] []    [] [][][][] [][][][] []       ()[][][][]    []"<<endl;
	cout<<"\t  []  []   ()  [][]      [] []   []    [][]    [] []    [] []       []       []       []            []"<<endl;
	cout<<"\t  []  []   () []  []     [][]    []   []  []   [] []    [] []       []       []       []            []"<<endl;
	cout<<"\t  []  []()() []    []    [][]    []  []    []  [] [][][][] [][][][] [][][][] []       [][][][]()    []"<<endl;
	cout<<"\t  []  []    [][][][][]   [] []   [] []      [] [] []    [] []       []       []               []    []"<<endl;
	cout<<"\t  []  []   []        []  []  []  [][]        [][] []    [] []       []       []               []    []"<<endl;
	cout<<"\t  []  []  []          [] []   [] []            [] []    [] [][][][] [][][][] [][][][] [][][][]()    []"<<endl;
	cout<<"\t  []                                                                                                []"<<endl;
	cout<<"\t  [][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][][]"<<endl;
	cout<<"\n \n \n \n \n";
	
	cout<<"\t\t\t\t\t\t 1) Used Cars   "<<endl<<"\t\t\t\t\t\t 2) New Cars      "<<endl<<"\t\t\t\t\t\t 3) Bikes"<<endl;
	cout<<"\t\t\t\t\t\t 4) Auto Stores"<<endl<<"\t\t\t\t\t\t 5) Contact Info."<<endl<<"\t\t\t\t\t\t 6) Help\n\t\t\t\t\t\t 7) Exit"<<endl;
    cout<<"\n\n\n ";
    int option,new_cars,used_cars,bike,auto_stores,Contact_info,Help;
    cin>>option;
    
	switch(option){
		
		case 1:
			cout<<"\t\t\t\t\t\t=>Used Cars:"<<endl;
			break;
		case 2:
			new_cars=newcars();			
			break;
			
		case 3:
			bike=bikes();	
			break;
		case 4:
			auto_stores=autostores();
			break;
		case 5:
		    Contact_info=contact();	
			break;
		case 6:
			cout<<"\t\t\t\t\t\t=>Help"<<endl;
			break;
		case 7:
			return 0;
			break;	
		default:
		    cout<<"\t\t\t\t\t\t \"Enter a valid number to select any option of the menu\" ";						
	} 

	return 0;	
}

int newcars(){               // New Cars Function*************
	cout<<"\t\t\t\t\t\t=>New Cars: \n\n\t\t\t\t\t\t\"Please select your car brand:\""<<endl;
			cout<<"\n\t\t\t\t\t\t1)Honda \n\t\t\t\t\t\t2)Suzuki \n\t\t\t\t\t\t3)Toyota"<<endl;
			int option;
			cin>>option;
			
			switch(option){                       //****************Using nested switch*********
				case 1:
					cout<<"\n\t\t\t\t\t\t=>Honda: \n\n\t\t\t\t\t\t\"Please select your car model:\""<<endl;
						cout<<"\n\t\t\t\t\t\t1)2018 \n\t\t\t\t\t\t2)2019 \n\t\t\t\t\t\t3)2020";
				break;
				case 2:
					cout<<"\n\t\t\t\t\t\t=>Suzuki: \n\n\t\t\t\t\t\t\"Please select your car model:\""<<endl;
						cout<<"\n\t\t\t\t\t\t1)2018 \n\t\t\t\t\t\t2)2019 \n\t\t\t\t\t\t3)2020";
				break;
				case 3:
					cout<<"\n\t\t\t\t\t\t=>Toyota: \n\n\t\t\t\t\t\t\"Please select your car model:\""<<endl;
						cout<<"\n\t\t\t\t\t\t1)2018 \n\t\t\t\t\t\t2)2019 \n\t\t\t\t\t\t3)2020";
				break;
				default:
				cout<<"\t\t\t\t\t\t \"Enter a valid number to select any option of the menu\" ";			
		 }
}

int bikes(){               // Bikes Function*************
	cout<<"\t\t\t\t\t\t=>Bikes : \n\n\t\t\t\t\t\t\"Please select your bikes brand:\""<<endl;
			cout<<"\n\t\t\t\t\t\t1)Honda \n\t\t\t\t\t\t2)Suzuki \n\t\t\t\t\t\t3)Yamaha"<<endl;
			int option;
			cin>>option;
			
			switch(option){                       //****************Using nested switch*********
				case 1:
					cout<<"\n\t\t\t\t\t\t=>Honda: \n\n\t\t\t\t\t\t\"Please select your car model:\""<<endl;
						cout<<"\n\t\t\t\t\t\t1)2018 \n\t\t\t\t\t\t2)2019 \n\t\t\t\t\t\t3)2020";
				break;
				case 2:
					cout<<"\n\t\t\t\t\t\t=>Suzuki: \n\n\t\t\t\t\t\t\"Please select your car model:\""<<endl;
						cout<<"\n\t\t\t\t\t\t1)2018 \n\t\t\t\t\t\t2)2019 \n\t\t\t\t\t\t3)2020";
				break;
				case 3:
					cout<<"\n\t\t\t\t\t\t=>Yamaha: \n\n\t\t\t\t\t\t\"Please select your car model:\""<<endl;
						cout<<"\n\t\t\t\t\t\t1)2018 \n\t\t\t\t\t\t2)2019 \n\t\t\t\t\t\t3)2020";
				break;
				default:
				cout<<"\t\t\t\t\t\t \"Enter a valid number to select any option of the menu\" ";			
		 }
}

int contact(){  // Contact info. Function*************
	cout<<"\t\t\t\t\t\tPakWheels.com \n\t\t\t\t\t\tSaeed Alam Tower, 37-Commercial Zone"
        <<" \n\t\t\t\t\t\tLiberty Market, Gulberg, Lahore, Pakistan."
        <<" \n\t\t\t\t\t\tPhone: 042 - 111 WHEELS (042 - 111 943 357)"
        <<" \n\t\t\t\t\t\tMonday-Saturday"
        <<" \n\t\t\t\t\t\t10:00am-07:00pm\n\t\t\t\t\t\tinfo@pakwheels.com."<<endl;
	cout<<" \n\n\t\t\t\t\t\t1)Back"<<endl;	
			int option;
			cin>>option;
			
			switch(option){                       //****************Using nested switch*********
				case 1://for going banck option	
				break;
				
				default:
				cout<<"\t\t\t\t\t\t \"Enter a valid number to select any option of the menu\" ";	
}
}

int autostores(){               // Auto Stores Function*************
	cout<<"\t\t\t\t\t\t=>Auto stores: \n\n\t\t\t\t\t\t\"Please select your city:\""<<endl;
			cout<<"\n\t\t\t\t\t\t1)Karachi \n\t\t\t\t\t\t2)Lahore \n\t\t\t\t\t\t3)Islamabad"<<endl;
			int option;
			cin>>option;
			
			switch(option){                       //****************Using nested switch*********
				case 1:
					cout<<"\n\t\t\t\t\t\t=>Karachi: "<<endl;
				break;
				case 2:
					cout<<"\n\t\t\t\t\t\t=>Lahore: "<<endl;
				break;
				case 3:
					cout<<"\n\t\t\t\t\t\t=>Islamabad: "<<endl;
				break;
				default:
				cout<<"\t\t\t\t\t\t \"Enter a valid number to select any option of the menu\" ";			
		 }
}
