# ModalidadeRetiradaFonte
Valor

#include <iostream>
#include <windows.h>
#include <strings.h>
#include <stdio.h>
#include <cstdio>
#include <iomanip>
#include <stdlib.h>
#include <cstdlib>

using namespace std;
void ModFontPag();
void ContaBancaria();
int main()
{
	ModFontPag();
	return 0;
}
void ModFontPag(){
	char BankInternacional;
	if(BankInternacional = true)
	{
		string Bank;
		string ModalidadeOrigem;
		string Data;
		string Hora;
		string Moeda;
		string Volume;
		char ValorMercado;
		int ResultNegocio;
		string ModalidadeDestino;
		//ResultNegocio = (ModalidadeDestino);
		cout<<"\n|------------------------------------------|\n";
		printf("| Bank : ");
		cin>>Bank>>setprecision(25);
		scanf("\procurando...[Bank]");
		printf("| Modalidade Origem : ");
		cin>>ModalidadeOrigem>>setprecision(25);
		printf("| Data : ");
		cin>>Data>>setprecision(8);
		printf("| Hora : ");
		cin>>Hora>>setprecision(8);
		printf("| Moeda : ");
		cin>>Moeda>>setprecision(7);
		printf("| Volume : ");
		cin>>Volume>>setprecision(5);
		printf("| Modalidade Destino : ");
		cin>>ModalidadeDestino>>setprecision(25);
		system("PAUSE");
		
		ContaBancaria();
		
	}
}
void ContaBancaria(){
	char Banco;
	int Itau;
	if(Banco = Itau)
	{
		int Agencia = '1760';
		int ContaCorrente = '10347-1';
		int CreditoEmConta = NULL;  
		int Result = CreditoEmConta;
			cout<<"\n|------------------------------------------|\n";
			cout<<"| Banco : "<<Itau;cout<<"\n| Agencia : "<<Agencia;
			cout<<"\n| Conta Corrente : "<<ContaCorrente;
			cout<<"\n| Credito Em Conta : "<<sizeof(ContaCorrente, CreditoEmConta);
			cout<<"\n|------------------------------------------|\n";
			scanf("\Credito Em Conta...", CreditoEmConta);
	}
}
