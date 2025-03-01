#include <iostream>
using namespace std;
main(){
	/*
	
	Primera parte: 
	
	//numero es positivo o negativo 
	int num=0;
	cout<<"ingrese el numero: ";
	cin>>num;
	if(num>0){
		//entra a aca cuando la condicion es verdadera
		cout<<"Positivo"<<endl;
	}else{
		if(num=0){
			cout<<"Neutro"<<endl;
		}else{
	        cout<<"Negativo"<<endl;
	    }
	}
	
	// segunda Parte paises
	
	string pais="";
	cout<<"Ingrese el país: ";
	cin>>pais;
	if(pais==Guatemala){
		cout<<"yo soy de"<<pais<<"mi pais"<<endl;
	}else{
		cout<<pais<<endl;
	}
	}
	
	//tercera parte numerp par e inpar
	int num=0;
	cout<<"ingrese Numero:";
	cin>>num;
	//dividir un numero entre dos su residuo es cero entonces es par, caso contrario es inpar
	if ((num%2)==0){
		cout<<"Par"<<endl;
	}else{
		cout<<"Impar"<<endl;
	}
	     
	     
	    //cuarta parte: and (y) &&
	    //or (o) ||
	    
	    
	    char lapiz,lapicero,cuaderno;
	    cout<<"Trae Lapiz (s/n): ";
	    cin>>lapiz;
	    cout<<"Trae Lapicero (s/n): ";
	    cin>>lapicero;
	    cout<<"Trae Cuaderno (s/n): ";
	    cin>>cuaderno;
	    
	    //puede entrar en mi clase si usted trae lapiz y un lapicero
	    if((lapiz=='s' || lapicero=='s' ) && cuaderno =='s' ){
	    	cout<<"Ingrese"<<endl;
	    	
	    }else{
	    	cout<<"Lo siento no puede ingresar"<<endl;
		}
		*/
		
		int codigo=0;
		cout<<"ingrese codigo de areas: ";
		cin>>codigo;
		switch(codigo){
			case 501 :cout<<"Belice"<<endl;
			    break;
			case 502 :cout<<"Guatemala"<<endl;
			    break;
			case 503 :cout<<"El Salvador"<<endl;
			    break;
			case 504 :cout<<"Honduras"<<endl;
			    break;
			case 505 :cout<<"Nicaragua"<<endl;
			    break;
			case 506 :cout<<"Costa Rica"<<endl;
			    break;
			case 507 :cout<<"Panama"<<endl;
			    break;
			default : cout<<"este codigo no es de centroamerica"<<endl;
		}	
	system("Pause");
};

//Anthony Emmanuel Godoy Leiva
