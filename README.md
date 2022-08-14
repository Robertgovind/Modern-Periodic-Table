
#include<stdio.h>
#include<conio.h>
void element( int );
void design()
{
	printf("**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##\n\n\n");
	printf("\t\t\t\tWelcome To Modern Periodic Table\t\t\t\n\n\n");
	printf("**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##**##\n\n\n\n");
}

void intro()
{
	int n,a;
	extern int temp;
	char symbol[5];
	 design();
	printf("Enter 1 to search with atomic number:\n\n");
	printf("Enter 2 to search with symbol of the element:\n\n");
	printf(">>>Enter<<<");
	scanf("%d",&n);
	switch(n)
	{
		case 1:
			printf("\nYou are going to search with atomic number:\n\n");
			printf("Enter the atomic number: ");
			scanf("%d",&a);
            printf("\n\n\n");
            element(a);
			temp = a;
			break;
		case 2:
		    printf("\nYou are going to search with symbol number :  ");
			printf("\nEnter the symbol number(with first letter capital and remaining small): ");
			scanf("%s",symbol);
			break;
		default:
		     printf("...Invalid input...");
			 break;
			 	} 
}

int main()
{
	char test;
intro();
printf("\nDo yoou want to continue");
printf("\nYes(Y/y)");
printf("No(N/n)");
printf(">>>Enterr<<<");
scanf("%c",test);
	if(test=='Y'||test=='y')
	void intro();
	else if(test=='N'||test=='n')
	printf("\n!!!You choosed to exit!!!");

getch ();
return 0;
}


 void element(int a)
{ 
char symbol[5];
int temp;
 
	if(a==1 )
{
	printf("Name : Hydrogen\n");
	printf("symbol : H  \n");
		printf("Atomic number : %\n",temp);
			printf("Atomic mass : 1.0079\n");
				printf("Discoverer : Henery Cavendish\n");
					printf("Oxidation state : -1, +1\n");
}
else if(a==2 || symbol=="He")
{
	printf("Name : Helium\n");
	printf("symbol :He  \n");
		printf("Atomic number : \n",temp);
			printf("Atomic mass : 4.0026\n");
				printf("Discoverer : Jules Janssen \n");
					printf("Oxidation state : 0\n");
}
else if(a==3 || symbol=="Li")
{
	printf("Name : Lithium\n");
printf("symbol : Li \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 6.941\n");
				printf("Discoverer : Johan August Arfvedson\n");
					printf("Oxidation state : +1\n");
}
else if(a==4 || symbol=="Be")
{
	printf("Name : Beryllium\n");
	printf("symbol : Be \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 9.0122\n");
				printf("Discoverer : Nicolas Louis Vauquelin && \n");
					printf("Oxidation state : +2\n");
}
else if(a==5 || symbol=="B")
{
	printf("Name : Boron\n");
	printf("symbol : B \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 10.811\n");
				printf("Discoverer : louis Josef Gay Lussac & Louis Jacques\n");
					printf("Oxidation state : +1,+3\n");
}
else if(a==6 || symbol=="C")
{
	printf("Name : Carbon\n");
	printf("symbol : C \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 12.011\n");
				printf("Discoverer : \n");
					printf("Oxidation state : -4 to +4\n");
}
else if(a==7 || symbol=="N")
{
	printf("Name : Nitrogen\n");
	printf("symbol : N \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 14.007\n");
				printf("Discoverer : Daniel Rutherford\n");
					printf("Oxidation state : -3 to +5\n");
}
else if(a==8 || symbol=="O")
{
	printf("Name : Oxygen\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 15.999\n");
				printf("Discoverer : Joseph Priestley\n");
					printf("Oxidation state : -2,+2,1/2,+1,-1\n");
}
else if(a==9 || symbol=="F")
{
	printf("Name : Fluorine\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 18.998\n");
				printf("Discoverer : Carl Wilhelm Scheele \n");
					printf("Oxidation state : +1,-1\n");
}
else if(a==10 || symbol=="Ne")
{
	printf("Name : Neon\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 20.18\n");
				printf("Discoverer : William Ramsay & Morris Travers\n");
					printf("Oxidation state : 0\n");
}
else if(a==11 || symbol=="Na")
{
	printf("Name : Sodium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 22.990\n");
				printf("Discoverer : Humphry Davy\n");
					printf("Oxidation state : +1\n");
}
else if(a==12|| symbol=="Mg")
{
	printf("Name : Magnessium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 24.305\n");
				printf("Discoverer : Joseph Black\n");
					printf("Oxidation state : +2\n");
}
else if(a==13 || symbol=="Al")
{
	printf("Name : Aluminium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 26.982 \n");
				printf("Discoverer :  Hans Christian Oerested\n");
					printf("Oxidation state : +1, +2,+3\n");
}
else if(a==14 || symbol=="Si")
{
	printf("Name : Silicon\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 28.066\n");
				printf("Discoverer : Jons Jacob Berzelius\n");
					printf("Oxidation state : +2\n");
}  
else if(a==15 || symbol=="P")
{
	printf("Name : Phosphorous\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 30.974\n");
				printf("Discoverer : Hennig Brand \n");
					printf("Oxidation state : -3,+3,+5\n");
}
else if(a==16 || symbol=="S")
{
	printf("Name : Sulphur\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 32.065\n");
				printf("Discoverer : Louis Joseph gay lussac & Louis Jacques Thanard\n");
					printf("Oxidation state : -2,+4,+6\n");
}
else if(a==17 || symbol=="Cl")
{
	printf("Name : Chroline\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 35.453\n");
				printf("Discoverer : Carl Wilhelm Scheele\n");
					printf("Oxidation state : -1 to +7\n");
}
else if(a==18 || symbol=="Ar")
{
	printf("Name : Argon\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 39.948\n");
				printf("Discoverer :John William strutt,III Baron Rayleigh & William Ramsay\n");
					printf("Oxidation state : 0 \n");
}
else if(a==19 || symbol=="K")
{
	printf("Name : Potassium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 39.098\n");
				printf("Discoverer : Humphry Davy\n");
					printf("Oxidation state : +1\n");
}
else if(a==20 || symbol=="ca")
{
	printf("Name : Calcium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 40.078\n");
				printf("Discoverer : Humphry Davy\n");
					printf("Oxidation state :  +2\n");
}
else if(a==21 || symbol=="Sc")
{
	printf("Name : Scandium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 44.956\n");
				printf("Discoverer : Lars Fredrik Nilson\n");
					printf("Oxidation state : +3\n");
}
else if(a==22 || symbol=="Ti")
{
	printf("Name : Titanium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 47.867\n");
				printf("Discoverer : Willian Gregor\n");
					printf("Oxidation state : +2,+3,+4\n");
}
else if(a==23 || symbol=="V")
{
	printf("Name : vanadium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 50.942\n");
				printf("Discoverer : Nils Gabriel Sefstrom\n");
					printf("Oxidation state : -3 to +5\n");
}
else if(a==24 || symbol=="Cr")
{
	printf("Name : Chromium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 51.996\n");
				printf("Discoverer : Louis Nicolas Vauqugelin\n");
					printf("Oxidation state : -4 to +6\n");
}
else if(a==25 || symbol=="Mn")
{
	printf("Name : Manganese\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 54.938\n");
				printf("Discoverer : John Gottlieb Gahn \n");
					printf("Oxidation state : +2 to +7\n");
}
else if(a==26 || symbol=="Fe")
{
	printf("Name : Iron\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 55.845\n");
				printf("Discoverer : The Hittites \n");
					printf("Oxidation state : -4 to +7\n");
}
else if(a==27 || symbol=="Co")
{
	printf("Name : Cobalt\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 58.933\n");
				printf("Discoverer : Georg Barndt\n");
					printf("Oxidation state : -3 to +5\n");
}
else if(a==28 || symbol=="Ni")
{
	printf("Name : Nickel\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 58.693\n");
				printf("Discoverer : Axel Fredrik Cronstedt\n");
					printf("Oxidation state : -1 to +4");
}
else if(a==29 || symbol=="Cu")
{
	printf("Name : Copper\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 63.546\n");
				printf("Discoverer : Henery Cavendish\n");
					printf("Oxidation state : -1, +1\n");
}
else if(a==30 || symbol=="Zn")
{
	printf("Name : Zinc\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 65.38\n");
				printf("Discoverer : Indian Metallurgist \n");
					printf("Oxidation state : -2 to +2\n");
}
else if(a==31 || symbol=="")
{
	printf("Name : Gallium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 69.723\n");
				printf("Discoverer : Lecoq de boisbaudran\n");
					printf("Oxidation state : -5 to +3\n");
}
else if(a==32 || symbol=="")
{
	printf("Name : Germanium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 72.64\n");
				printf("Discoverer : Clemens Winkler\n");
					printf("Oxidation state : -4 to +4\n");
}
else if(a==33 || symbol=="")
{
	printf("Name : Arsenic\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 74.922\n");
				printf("Discoverer : Albertus Magnus \n");
					printf("Oxidation state : -3 to +5\n");
}
else if(a==34 || symbol=="")
{
	printf("Name : Selenium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 78.971\n");
				printf("Discoverer : Jons Jakob Berzelius && John Gottlieb Gahn  \n");
					printf("Oxidation state : -2 to +6\n");
}
else if(a==35 || symbol=="")
{
	printf("Name : Bromine\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 79.904\n");
				printf("Discoverer : Antoine Jerome Balard & Carl Jacob Lowig\n");
					printf("Oxidation state : -1,+1,+3,+7,+5\n");
}
else if(a==36 || symbol=="")
{
	printf("Name : Krypton\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 83.798\n");
				printf("Discoverer : William Ramsay,Morris Travers\n");
					printf("Oxidation state : 0,+1,+2\n");
}
else if(a==37 || symbol=="")
{
	printf("Name : Rubidium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 85.4678\n");
				printf("Discoverer :  Robert Bunsen & Gustav Kirchhoff\n");
					printf("Oxidation state : +1,-1\n");
}
else if(a==38 || symbol=="")
{
	printf("Name : Strontium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 87.62\n");
				printf("Discoverer : William Cruickshank\n");
					printf("Oxidation state : +1,+2\n");
}
else if(a==39 || symbol=="")
{
	printf("Name : Yttrium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 88.90584\n");
				printf("Discoverer : John Gadolin \n");
					printf("Oxidation state : +1 to +3\n");
}
else if(a==40|| symbol=="")
{
	printf("Name : Zirconium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 91.224\n");
				printf("Discoverer : Martin Heinrich Klaproth\n");
					printf("Oxidation state : -2,+1 to +4\n");
}
else if(a==41 || symbol=="")
{
	printf("Name : Niobium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 92.90637\n");
				printf("Discoverer : Charles Hatchett\n");
					printf("Oxidation state : -3,-1,+1 to +5\n");
}
else if(a==42 || symbol=="")
{
	printf("Name : Molybdenum\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 95.95\n");
				printf("Discoverer : Carl Wilhelm Scheele\n");
					printf("Oxidation state : -4,-2,-1,+1 to +6\n");
}
else if(a==43 || symbol=="")
{
	printf("Name : Technetium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 98.9062\n");
				printf("Discoverer : Emilio Segre & Carlo Perrier\n");
					printf("Oxidation state : -3,+1 to +7\n");
}
else if(a==44 || symbol=="")
{
	printf("Name : Ruthenium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 101.07\n");
				printf("Discoverer : Karl Ernst claus\n");
					printf("Oxidation state : -4,-2,+1 to +8\n");
}else if(a==45 || symbol=="")
{
	printf("Name : Rhodium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 102.9055\n");
				printf("Discoverer : William Hyde Wollaston\n");
					printf("Oxidation state : -3,-1,+1 to +6\n");
}else if(a==46 || symbol=="")
{
	printf("Name : Palladium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 106.42\n");
				printf("Discoverer : William Hyde Wollaston\n");
					printf("Oxidation state : 0 to +4\n");
}
else if(a==47 || symbol=="")
{
	printf("Name : Silver\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 107.8682\n");
				printf("Discoverer : Ancient Ancenstors\n");
					printf("Oxidation state : -2 to +3\n");
}else if(a==48 || symbol=="")
{
	printf("Name : Cadmium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 112.414\n");
				printf("Discoverer : Karl Samuel Leberecht & Friedrich Stromeyer\n");
					printf("Oxidation state : -3,-1,+1 to +5\n");
}else if(a==49 || symbol=="")
{
	printf("Name : Indium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 114.818\n");
				printf("Discoverer : Ferdinand Reich & Hieronymous Theodor Richter\n");
					printf("Oxidation state : -5,-2 to +3\n");
}
else if(a==50 || symbol=="")
{
	printf("Name : Tin");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 118.71\n");
				printf("Discoverer : Ancestors\n");
					printf("Oxidation state : -4 to +4\n");
}else if(a==51 || symbol=="")
{
	printf("Name : Antimony\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 121.76\n");
				printf("Discoverer : Ancient People\n");
					printf("Oxidation state : -3 to +5\n");
}else if(a==52 || symbol=="")
{
	printf("Name : Tellurium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 127.6\n");
				printf("Discoverer : Franz Joseph Muller Von Reichenstein\n");
					printf("Oxidation state : -2 to +6\n");
}else if(a==53 || symbol=="")
{
	printf("Name : Iodine\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 126.90447\n");
				printf("Discoverer : Bernard Courtois \n");
					printf("Oxidation state : -1,+1,+3 to +7\n");
}else if(a==54 || symbol=="")
{
	printf("Name : Xenon\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 131.293\n");
				printf("Discoverer : William Ramsay Travers\n");
					printf("Oxidation state : 0,+1,+2,+4,+6,+8\n");
}
else if(a==55 || symbol=="")
{
	printf("Name : Caiesium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 132.90546\n");
				printf("Discoverer : Robert Bunsen & Gustav Kirchhoff\n");
					printf("Oxidation state : +1,-1\n");
}
else if(a==56 || symbol=="")
{
	printf("Name : Brium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 137.327\n");
				printf("Discoverer : Carl Wilhelm Scheele\n");
					printf("Oxidation state : +1,+2\n");
}else if(a== 57 || symbol=="")
{
	printf("Name : Lanthenium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 138.90547\n");
				printf("Discoverer : Carl Gustaf Mosander \n");
					printf("Oxidation state : +1,+2,+3\n");
}else if(a==58 || symbol=="")
{
	printf("Name : cerium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 140.116\n");
				printf("Discoverer : Martin Heinrich Klaproth,Jons jakov Berzelius & Wilhelm Hisinger \n");
					printf("Oxidation state : +1 to +4\n");
}
else if(a==59 || symbol=="")
{
	printf("Name : Praseodymium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 140.90765\n");
				printf("Discoverer : Carl Auer Von Welsbach\n");
					printf("Oxidation state : +2 to +5\n");
}
else if(a==60 || symbol=="")
{
	printf("Name : Neodymium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 144.242\n");
				printf("Discoverer : Carl Auer Von Welsbach\n");
					printf("Oxidation state : +2 to +4\n");
}
else if(a==61 || symbol=="")
{
	printf("Name : Promethium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 144.913\n");
				printf("Discoverer : Chien Shiung Wu, Emilio Serge & hans Bethe\n");
					printf("Oxidation state : +2,+3\n");
}
else if(a==62 || symbol=="")
{
	printf("Name : Samarium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 150.36\n");
				printf("Discoverer : Lecoq de Boisbaudran\n");
					printf("Oxidation state : +1 to +4\n");
}
else if(a==63 || symbol=="")
{
	printf("Name : Europium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 151.964\n");
				printf("Discoverer : Eugene Anatole Demarcay");
					printf("Oxidation state : -3,-1,+1 to +5\n");
}
else if(a==64 || symbol=="Gd")
{
	printf("Name : Gadolinium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 157.25\n");
				printf("Discoverer : Jean Charles Ganlissard de Marignac\n");
					printf("Oxidation state :+1,+2,+3 \n");
}
else if(a==65 || symbol=="Tb")
{
	printf("Name : Terbium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 158.92535\n");
				printf("Discoverer : Carl Gustaf mosander\n");
					printf("Oxidation state : +1 to +4\n");
}
else if(a==66 || symbol=="Dy")
{
	printf("Name : Dysprosium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 162.5\n");
				printf("Discoverer : Lecoq de Boisbaudran\n");
					printf("Oxidation state : +1 to +4\n");
}
else if(a==67 || symbol=="")
{
	printf("Name :Holmium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :164.93033 \n");
				printf("Discoverer : Jacques Louis Soret\n");
					printf("Oxidation state : +1,+2,+3\n");
}
else if(a==68 || symbol=="")
{
	printf("Name : Erbium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :167.259 \n");
				printf("Discoverer : Carl Gustaf Mosander\n");
					printf("Oxidation state : +1 to +3\n");
}
else if(a==69 || symbol=="")
{
	printf("Name : Thulium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :168.93422 \n");
				printf("Discoverer : Per Teodor Cleve\n");
					printf("Oxidation state : +2,+3\n");
}
else if(a==70 || symbol=="")
{
	printf("Name : Ytterbium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 173.045\n");
				printf("Discoverer : Jean Charles Galissard de Marignac\n");
					printf("Oxidation state : +1 to +3\n");
}
else if(a==71 || symbol=="")
{
	printf("Name : Lutetium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 174.9668\n");
				printf("Discoverer : carl Auer Von Welsbach and Georges Urbain\n");
					printf("Oxidation state : +1 to +3\n");
}
else if(a==72 || symbol=="")
{
	printf("Name : Hafnium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :178.49  \n");
				printf("Discoverer : Dirk Coster and George de Hevesy\n");
					printf("Oxidation state : -2 to -4 \n");
}
else if(a==73 || symbol=="")
{
	printf("Name : Tantalum\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 180.94788\n");
				printf("Discoverer : Anders Gustaf Ekeberg\n");
					printf("Oxidation state : -3 to +5\n");
}
else if(a==74 || symbol=="")
{
	printf("Name : Tungestan \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 183.84\n");
				printf("Discoverer : Carl Wilhelm Scheele\n");
					printf("Oxidation state : -4 to +6\n");
}
else if(a==75 || symbol=="")
{
	printf("Name : Rhenium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :186.207 \n");
				printf("Discoverer : Masataka Ogawa\n");
					printf("Oxidation state : -3 to +7\n");
}
else if(a==76 || symbol=="")
{
	printf("Name : Osmium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :190.23 \n");
				printf("Discoverer : Smithson Tennat\n");
					printf("Oxidation state : -4 to +8\n");
}
else if(a==77 || symbol=="")
{
	printf("Name : Iridium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :192.217 \n");
				printf("Discoverer : Smithson Tennet\n");
					printf("Oxidation state : -3 to +9\n");
}
else if(a==78 || symbol=="")
{
	printf("Name :Platinum \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 195.084\n");
				printf("Discoverer : Antonio de Ulloa\n");
					printf("Oxidation state : -3 to +6\n");
}
else if(a==79 || symbol=="")
{
	printf("Name :Gold \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 196.96657 \n");
				printf("Discoverer : Ancient people\n");
					printf("Oxidation state : -3 to +5\n");
}
else if(a==80 || symbol=="")
{
	printf("Name : Mercury \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :200.592 \n");
				printf("Discoverer : Ancient Hindus\n");
					printf("Oxidation state : -2 ,+1,+2\n");
}
else if(a==81 || symbol=="")
{
	printf("Name : Thalium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 204.38\n");
				printf("Discoverer : William Crookes\n");
					printf("Oxidation state : -5 ,-2 to +3\n");
}else if(a==82 || symbol=="")
{
	printf("Name : Lead \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :207.2 \n");
				printf("Discoverer : Ancient People \n");
					printf("Oxidation state : -4 to +4\n");
}else if(a==83 || symbol=="")
{
	printf("Name : Bismuth \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 208.9804\n");
				printf("Discoverer : Claude Francois Geoffroy\n");
					printf("Oxidation state : -3 to +5\n");
}else if(a==84 || symbol=="")
{
	printf("Name : Polonium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 209\n");
				printf("Discoverer : Pierre and Marie Curie\n");
					printf("Oxidation state : -2 ,+2 to +6\n");
}
else if(a==85 || symbol=="")
{
	printf("Name : Astatine\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 210\n");
				printf("Discoverer : Dale R. Corson , Kenneth Ross MAckenzie,Emilio Segre\n");
					printf("Oxidation state : -1,+1,+3,+5,+7\n");
}
else if(a==86 || symbol=="")
{
	printf("Name : Radon\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 222\n");
				printf("Discoverer : Ernest Rutherford , Robert B.Owens\n");
					printf("Oxidation state : 0,+2,+6\n");
}
else if(a==87 || symbol=="")
{
	printf("Name : Francium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 223\n");
				printf("Discoverer : Marguerite Perey\n");
					printf("Oxidation state : +1\n");
}else if(a==88 || symbol=="")
{
	printf("Name : Radium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 226\n");
				printf("Discoverer : Pierre and Marie Curie\n");
					printf("Oxidation state : +2\n");
}else if(a==89 || symbol=="")
{
	printf("Name : Actinium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 227\n");
				printf("Discoverer : Friedrich Oskar , Giesel\n");
					printf("Oxidation state : +2,+3\n");
}else if(a==90 || symbol=="")
{
	printf("Name : Thorium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :232.0377 \n");
				printf("Discoverer : Jons Jakob Berzelius \n");
					printf("Oxidation state : +1 to +4\n");
}else if(a==91 || symbol=="")
{
	printf("Name : Protactinium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 231.03587\n");
				 printf("Discoverer : Kasimir Fajans and Oswald Helmuth Gohring \n");
					printf("Oxidation state : +2 to +5\n");
}
else if(a==92 || symbol=="")
{
	printf("Name : Uranium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 238.02892 \n");
				printf("Discoverer : Martin Heinrich Kalaproth \n");
					printf("Oxidation state : +1 to +6\n");
}
else if(a==93 || symbol=="")
{
	printf("Name : Neptuniun \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 237 \n");
				printf("Discoverer : Edwin McMillan and Philip H.Abelson\n");
					printf("Oxidation state : +1 to +7 \n");
}
else if(a==94 || symbol=="")
{
	printf("Name : Plutonium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :244 \n");
				printf("Discoverer :Glenn T.Seaborg , Arthur Wahl, Joseph W.Kennedy and Edwin Mc Millan \n");
					printf("Oxidation state : +1 to +7\n");
}
else if(a==95 || symbol=="")
{
	printf("Name : Americum \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 243\n");
				printf("Discoverer : Glenn T.Seaborg , Ralph A.James, Leon O.Morgan and Albert Ghiorso\n");
					printf("Oxidation state : +2 to +7\n");
}
else if(a==96 || symbol=="")
{
	printf("Name :  Curium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 247 \n");
				printf("Discoverer : Glenn T.Seaborg , Ralph A.James and Albert Ghiorso\n");
					printf("Oxidation state : +2 to +6\n");
}else if(a==97 || symbol=="")
{
	printf("Name :   Berkelium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :247 \n");
				printf("Discoverer : Lawerence Berkeley National Laboratory \n");
					printf("Oxidation state : +2 to +5\n");
}else if(a==98 || symbol=="")
{
	printf("Name : californium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :251 \n");
				printf("Discoverer :Lawerence Berkeley National Laboratory  \n");
					printf("Oxidation state :  +2 to +5\n");
}else if(a==99 || symbol=="")
{
	printf("Name : Einstinum \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :252 \n");
				printf("Discoverer :Lawerence Berkeley National Laboratory  \n");
					printf("Oxidation state : +2,+3,+4\n");
}else if(a==100 || symbol=="")
{
	printf("Name : Fermium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 257\n");
				printf("Discoverer : Lawerence Berkeley National Laboratory \n");
					printf("Oxidation state : +2,+3\n");
}else if(a==101 || symbol=="")
{
	printf("Name : Mendelevium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :258 \n");
				printf("Discoverer :Lawerence Berkeley National Laboratory  \n");
					printf("Oxidation state :+2,+3 \n");
}
else if(a==102 || symbol=="")
{
	printf("Name : Nobelium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 259\n");
				printf("Discoverer : Joint Institute for Nuclear Research\n");
					printf("Oxidation state : +2,+3\n");
}else if(a==103 || symbol=="")
{
	printf("Name : Lawrencium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 266\n");
				printf("Discoverer : Lawerence Berkeley National Laboratory Joint Institute for Nuclear Rresearch\n");
					printf("Oxidation state : +3\n");
}
else if(a==104 || symbol=="")
{
	printf("Name : Rutherfordium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 267\n");
				printf("Discoverer : Lawerence Berkeley National Laboratory Joint Institute for Nuclear Rresearch\n");
					printf("Oxidation state : +2,+3,+4\n");
}
else if(a==105 || symbol=="")
{
	printf("Name : Dubnium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 268\n");
				printf("Discoverer : Lawerence Berkeley National Laboratory Joint Institute for Nuclear Rresearch\n");
					printf("Oxidation state : +3,+4,+5\n");
}else if(a==106 || symbol=="")
{
	printf("Name : Seaborgium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 269\n");
				printf("Discoverer :  Lawrence Berkeley National Laboratory\n");
					printf("Oxidation state : 0,+3 to +6\n");
}else if(a==107 || symbol=="")
{
	printf("Name : Bohrium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 270\n");
				printf("Discoverer : Gesellschaft Fur Schwerionenforschung\n");
					printf("Oxidation state : +3 to +7\n");
}else if(a==108 || symbol=="")
{
	printf("Name : Hassium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 270\n");
				printf("Discoverer : Gesellschaft Fur Schwerionenforschung\n");
					printf("Oxidation state : +2 to +8\n");
}else if(a==109 || symbol=="")
{
	printf("Name : Meitnerium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :278 \n");
				printf("Discoverer :Gesellschaft Fur Schwerionenforschung \n");
					printf("Oxidation state : +1 to +9\n");
}else if(a==110 || symbol=="")
{
	printf("Name :Darmstadtium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 281\n");
				printf("Discoverer : Gesellschaft Fur Schwerionenforschung\n");
					printf("Oxidation state : 0,+2,+4,+6,+8\n");
}else if(a==111 || symbol=="")
{
	printf("Name : Roentgenium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 282\n");
				printf("Discoverer : Gesellschaft Fur Schwerionenforschung\n");
					printf("Oxidation state : -1,+1,+3,+5\n");
}else if(a==112 || symbol=="")
{
	printf("Name : Copernicium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 285\n");
				printf("Discoverer : Gesellschaft Fur Schwerionenforschung\n");
					printf("Oxidation state : 0,+1,+2,+4\n");
}else if(a==113 || symbol=="")
{
	printf("Name : Nihonium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 286\n");
				printf("Discoverer : Riken\n");
					printf("Oxidation state : -1,+1,+3,+5\n");
}else if(a==114 || symbol=="")
{
	printf("Name : Flerovium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 289\n");
				printf("Discoverer : Joint Institete for Nuclera Research  and Lawrence Livermore National Laboratory\n");
					printf("Oxidation state : 0,+1,+2,+4,+6\n");
}else if(a==115 || symbol=="")
{
	printf("Name : Moscovium\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 290\n");
				printf("Discoverer : Joint Institete for Nuclera Research  and Lawrence Livermore National Laboratory\n");
					printf("Oxidation state : +1,+3\n");
}else if(a==116 || symbol=="")
{
	printf("Name : Livermorium \n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass :293 \n");
				printf("Discoverer :Joint Institete for Nuclera Research  and Lawrence Livermore National Laboratory \n");
					printf("Oxidation state : -2,+2,+4\n");
}
else if(a==117 || symbol=="")
{
	printf("Name : Tennessine\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 294\n");
				printf("Discoverer : Joint Institete for Nuclera Research ,Lawrence Livermore National Laboratory , VAnderbilt University and Oak Ridge National labortory\n");
					printf("Oxidation state : -1,+1,+3,+5\n");
}else if(a==118 || symbol=="")
{
	printf("Name : Oganesson\n");
		printf("Atomic number : %d\n",temp);
			printf("Atomic mass : 294\n");
				printf("Discoverer :Joint Institete for Nuclera Research  and Lawrence Livermore National Laboratory \n");
					printf("Oxidation state : -1,0,+1,+2,+4,+6\n");
} 
}
