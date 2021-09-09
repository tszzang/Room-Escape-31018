# Room-Escape-31018
덕영고등학교 [31018] [정태성] 응용프로그래밍개발 방탈출 프로그램 소스

독방을 탈출하면 되는 간단한 게임이다.

31011 안종진, 31018정태성

#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <windows.h>

#define TRUE 1
#define FALSE 0


void intro();
void room();
void a1(); //ħ�� 
void a2(); //���� 
void a3(); //���� 
void a4(); //ȭ�� 
void a5(); //���� 
void a6(); //���� ��
 
int isFindKey1 = FALSE;
int isFindKey2 = FALSE;
int isFindKey3 = FALSE;
int isFindKey4 = FALSE;
int isFindKey5 = FALSE;
int isFindKey6 = FALSE;

int isOpena6=FALSE;

int main() {
	int menu;
	
	while(1) {
		printf("��Ż��\n\n");
		printf("1. ����\n");
		printf("0. ����\n");
		printf(">> ");
		scanf("%d", &menu);
		
		switch(menu) {
			case 1:
				intro();
				room();
				break;
			case 0:
				return 0;
			default:
				printf("�Է� ����\n\n");
				break;
		}
	}
}
	
void room() {
	int menu;
	
	while(1) {
		system("cls");	
		printf("����\n\n");
		printf("�� �ȿ��� ������������ ã�ƺ���.\n\n");
		printf("1. ħ��     2. ����    3. ����\n");
		printf("4. ȭ��    5. ����    6. ���Թ�\n");
			
		printf(">> ");
		scanf("%d", &menu);
		
		switch(menu) {
			case 1:
				a1();
				break;
			case 2:
				a2();
				break;
			case 3:
					a3();				
				break;
			case 4:
				a4();
				break;
			case 5:
				a5();
				break;
			case 6:
				a6();
				break;
			default:
				printf("\n# ERROR # �Է°� ����\n");
				system("pause");
		}
	}
	
} 

void intro() {
	system("cls");
	printf("\n\n");
	printf("�׷����� �׷��� ���� ������ �����ִ�\n");
	Sleep(1500);
	printf("�׷��� ���̿� �ִ� �����̰� ������������ ��ȿ� ���ܳ����� ���̴� .\n\n");
	Sleep(1500);
	printf("���� ���� 6���� ã�Ƴ��� ���� ���� Ż���ؾ��Ѵ�.\n\n");
	Sleep(1500);
	system("pause");
}

void a2(){  
	int menu;
	
	while(1) {
		system("cls");
		printf("[����]-[����]\n\n");
		printf("1. ������ ���캻��\n");
		printf("2. ������ ����\n");
		printf("0. ���ư���\n");
		
		printf(">> ");
		scanf("%d", &menu);
		
		switch(menu) {
			case 1:
					printf("\n@^!&**#!@@!!&*&&*.\n");
				break;
			case 2:
				if(isFindKey1 && isFindKey2) {
							printf("\n�������� �̹� ã��.\n\n");
						} else {
							isFindKey1 = TRUE;
							isFindKey2 = TRUE;
							printf("\n�������� 2���� ã��\n\n");
						}
						break;
			case 0:
				return;
			default:
				printf("\n# ERROR # �Է°� ����\n\n");
				break;
		}
		system("pause");
	}	
}	

void a1(){  
	int menu;
	
	while(1) {
		system("cls");
		printf("[����]-[ħ��]\n\n");
		printf("1. ħ�븦 ���캻��\n");
		printf("0. ���ư���\n");
		
		printf(">> ");
		scanf("%d", &menu);
		
		switch(menu) {
			case 1:
			if(isFindKey3) {
							printf("\n�������� �̹� ã��.\n\n");
						} else {
							isFindKey3 = TRUE;
							printf("\n�������� 3�� ã��\n\n");
						}
						break;
			case 0:
				return;
			default:
				printf("\n# ERROR # �Է°� ����\n\n");
				break;
		}
		system("pause");
	}	
}	

void a3(){  
	int menu;
	
	while(1) {
		system("cls");
		printf("[����]-[����]\n\n");
		printf("1. ������ ���캻��\n");
		printf("2. ������ �����غ���\n");
		printf("0. ���ư���\n");
		
		printf(">> ");
		scanf("%d", &menu);
		
		switch(menu) {
			case 1:
				printf("\n�ƹ��͵� ����\n\n");
				return;
			case 2:
				if(isFindKey4) {
							printf("\n�������� �̹� ã��.\n\n");
						} else {
							isFindKey4 = TRUE;
							printf("\n�����Ͽ� ����4 ã��\n\n");
						}
						break;
			case 0:
				return;
			default:
				printf("\n# ERROR # �Է°� ����\n\n");
				break;
		}
		system("pause");
	}	
}	


void a4(){  
	int menu;
	
	while(1) {
		system("cls");
		printf("[����]-[����]\n\n");
		printf("1. ȭ���� ���캻��\n");
		printf("2. ���� �ĳ��� ����\n");
		printf("0. ���ư���\n");
		
		printf(">> ");
		scanf("%d", &menu);
		
		switch(menu) {
			case 1:
				printf("\n�ƹ��͵� ����\n\n");
				return;
			case 2:
				if(isFindKey5) {
							printf("\n�������� �̹� ã��.\n\n");
						} else {
							isFindKey5 = TRUE;
							printf("\n�����Ͽ� ����5 ã��\n\n");
						}
						break;
			case 0:
				return;
			default:
				printf("\n# ERROR # �Է°� ����\n\n");
				break;
		}
		system("pause");
	}	
}	

void a5(){  
	int menu;
	
	while(1) {
		system("cls");
		printf("[����]-[����]\n\n");
		printf("1. ��й�ȣ �Է�\n");
		printf("0. ���ư���\n");
		
		printf(">> ");
		scanf("%d", &menu);
		
		switch(menu) {
			case 1:
				if(isFindKey6) {
							printf("\n�������� �̹� ã��.\n\n");
						} else {
							isFindKey6 = TRUE;
							printf("\n������ �ִ� ��ȣ�� �Է��Ͽ� �������� 5�� �����\n\n");
						}
						break;
			case 0:
				return;
			default:
				printf("\n# ERROR # �Է°� ����\n\n");
				break;
		}
		system("pause");
	}	
}	

void a6(){
	int menu;
	
	while(1) {
		system("cls");
		printf("[����]-[��]\n\n");
		printf("��û �ܴ��غ��̴� �ݰ���.\n\n");
		printf("1. ���� ����\n");
		printf("0. ���ư���\n");
		
		printf(">> ");
		scanf("%d", &menu);
		
		switch(menu) {
			case 1:
				if(isFindKey1 && isFindKey2 && isFindKey3 && isFindKey4 &&isFindKey5 && isFindKey6 ) {
					isOpena6 = TRUE; 
					printf("Ż�� ����");
				} else {
					printf("\n���踦 ������.\n\n");
				}
				break;
			case 0:
				return;
			default:
				printf("\n# ERROR # �Է°� ����\n\n");
				break;
		}
		system("pause");
	}	
}	



