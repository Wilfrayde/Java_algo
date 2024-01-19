/*
* ALGORITHME : CONVERTISSEUR_DEVISE
* QUOI ?
* On simule un convertisseur de devises à travers un menu et le choix de l'utilisateurs
* AVEC QUOI ?
* un menu principal qui affiche :
* +---- Conversion de devise ----+
* 1- Euros en Dollars
* 2- Dollars en Euros
* 3- Euros en Yuans
* 4- Yuans en Euros
* 5- Dollars en Yuans
* 6- Yuans en Dollars
*
* apres que l'utilisateur a fait son choix, on lui demandera la somme a convertir
* puis on affichera le resultat
* exemple :
* 1 Euro correspond à 7.7983 Yuans
*
* Formules de conversion de chaque monnaie :
* 1 euro = 1.09 dollar
* 1 dollar = 0.92 euro
* 1 euro = 7.85 yuans
* 1 yuan = 0.13 euro
* 1 dollar = 7.22 yuans
* 1 yuan = 0.14 dollar
*
* Regles de gestion :
* -valeur minimale de l'utilisateur = 0
* -valeur maximale de l'utilisateur = 10000
*
* CONSTANTES :
* final static int VALEURMIN = 0;
* final static int VALEURMAX = 10000;
* final static int EURO_EN_DOLLAR = 1.09;
* final static int DOLLAR_EN_EURO = 0.92;
* final static int EURO_EN_YUAN = 7.85;
* final static int YUAN_EN_EURO = 0.13;
* final static int DOLLAR_EN_YUAN = 7.22;
* final static int YUAN_EN_DOLLAR = 0.14;
*
* variables :
* int choixUtilisateur = 0;
* int valeurConversion = -1;
* double resultat = -4.45
*/

// CONSTANTES
	final static int VALEURMIN = 0;
	final static int VALEURMAX = 10000;
	final static double EURO_EN_DOLLAR = 1.09;
	final static double DOLLAR_EN_EURO = 0.92;
	final static double EURO_EN_YUAN = 7.85;
	final static double YUAN_EN_EURO = 0.13;
	final static double DOLLAR_EN_YUAN = 7.22;
	final static double YUAN_EN_DOLLAR = 0.14;

void main(){
	
	// declaration/initialisation des variables
	int choixUtilisateur = 0;
	int valeurConversion = -1;
	double resultat = -4.45;
	
	//Affichage du menu principal
	while(true){
		println("+---- Conversion de devise ----+");
		println("1- Euros en Dollars");
		println("2- Dollars en Euros");
		println("3- Euros en Yuans");
		println("4- Yuans en Euros");
		println("5- Dollars en Yuans");
		println("6- Yuans en Dollars");
		
		//Demander/Controler/Stocker le choixUtilisateur
		do{
			choixUtilisateur = readInteger("Choisissez la devise à convertir");
		}while ((choixUtilisateur < 1) || (choixUtilisateur > 6));
		
		switch (choixUtilisateur) {
			
			case 1 :
			println("Vous voulez convertir des euros en dollars");
			
			//Demander/Controler/Stocker la valeurConversion
			do{
				valeurConversion = readInteger("Choisissez la valeur à convertir entre " + VALEURMIN + " et " + VALEURMAX);
			}while ((valeurConversion < VALEURMIN) || (valeurConversion > VALEURMAX));
			
			//Si valeurConversion est comprit entre 0 et 10000, calcule de valeurConversion * EURO_EN_DOLLAR
			resultat = valeurConversion * EURO_EN_DOLLAR;
			//Afficher le resultat
			println(valeurConversion + " euros est égale à " + resultat + " dollars");
			break;
			
			case 2 :
			println("Vous voulez convertir des dollars en euros");
			
			//Demander/Controler/Stocker la valeurConversion
			do{
				valeurConversion = readInteger("Choisissez la valeur à convertir entre " + VALEURMIN + " et " + VALEURMAX);
			}while ((valeurConversion < VALEURMIN) || (valeurConversion > VALEURMAX));
			
			//Si valeurConversion est comprit entre 0 et 10000, calcule de valeurConversion * DOLLAR_EN_EURO
			resultat = valeurConversion * DOLLAR_EN_EURO;
			//Afficher le resultat
			println(valeurConversion + " dollars est égale à " + resultat + " euros");
			break;
			
			case 3 :
			println("Vous voulez convertir des euros en yuans");
			
			//Demander/Controler/Stocker la valeurConversion
			do{
				valeurConversion = readInteger("Choisissez la valeur à convertir entre " + VALEURMIN + " et " + VALEURMAX);
			}while ((valeurConversion < VALEURMIN) || (valeurConversion > VALEURMAX));
			
			//Si valeurConversion est comprit entre 0 et 10000, calcule de valeurConversion * EURO_EN_YUAN
			resultat = valeurConversion * EURO_EN_YUAN;
			//Afficher le resultat
			println(valeurConversion + " euros est égale à " + resultat + " yuans");
			break;
			
			case 4 :
			println("Vous voulez convertir des yuans en euros");
			
			//Demander/Controler/Stocker la valeurConversion
			do{
				valeurConversion = readInteger("Choisissez la valeur à convertir entre " + VALEURMIN + " et " + VALEURMAX);
			}while ((valeurConversion < VALEURMIN) || (valeurConversion > VALEURMAX));
			
			//Si valeurConversion est comprit entre 0 et 10000, calcule de valeurConversion * YUAN_EN_EURO
			resultat = valeurConversion * YUAN_EN_EURO;
			//Afficher le resultat
			println(valeurConversion + " yuans est égale à " + resultat + " euros");
			break;
			
			case 5 :
			println("Vous voulez convertir des dollars en yuans");
			
			//Demander/Controler/Stocker la valeurConversion
			do{
				valeurConversion = readInteger("Choisissez la valeur à convertir entre " + VALEURMIN + " et " + VALEURMAX);
			}while ((valeurConversion < VALEURMIN) || (valeurConversion > VALEURMAX));
			
			//Si valeurConversion est comprit entre 0 et 10000, calcule de valeurConversion * DOLLAR_EN_YUAN
			resultat = valeurConversion * DOLLAR_EN_YUAN;
			//Afficher le resultat
			println(valeurConversion + " dollars est égale à " + resultat + " yuans");
			break;
			
			case 6 :
			println("Vous voulez convertir des yuans en dollars");
			
			//Demander/Controler/Stocker la valeurConversion
			do{
				valeurConversion = readInteger("Choisissez la valeur à convertir entre " + VALEURMIN + " et " + VALEURMAX);
			}while ((valeurConversion < VALEURMIN) || (valeurConversion > VALEURMAX));
			
			//Si valeurConversion est comprit entre 0 et 10000, calcule de valeurConversion * YUAN_EN_DOLLAR
			resultat = valeurConversion * YUAN_EN_DOLLAR;
			//Afficher le resultat
			println(valeurConversion + " yuans est égale à " + resultat + " dollars");
			break;
			
			default: //si l'utilisateur fait un mauvais choix
			println("Erreur dans le choix");
		}
	}
}
