#1.3 Tipus de llenguatges de programació#

Un llenguatge de programació és un llenguatge que permet establir una
comunicació entre l’home i la màquina. El llenguatge de programació
identificarà el codi font, que el programador desenvoluparà per indicar a la
màquina, una vegada aquest codi s’hagi convertit en codi executable, quins
passos ha de donar.

El primer tipus de llenguatge que es va desenvolupar és l’anomenat
**llenguatge de primera generació** o **llenguatge màquina**. És l’únic
llenguatge que entén l’ordinador directament.

El segon tipus de llenguatge de programació són els **llenguatges de segona
generació o llenguatges d’assemblador**. Es tracta del primer llenguatge de
programació que utilitza codis mnemotècnics per indicar a la màquina les
operacions que ha de dur a terme. Aquestes operacions, molt bàsiques, han
estat dissenyades a partir de la coneixença de l’estructura interna de la pròpia
màquina.

### 1.3.1 Característiques dels llenguatges de primera i segona generació ###

**Avantatges:**

• Permeten escriure programes molt optimitzats que aprofiten al màxim el
maquinari (hardware) disponible.

• Permeten al programador especificar exactament quines instruccions vol
que s’executin.

**Incovenients:**

• Els programes escrits en llenguatges de baix nivell estan completament
  lligats al maquinari on s’executaran i no es poden traslladar fàcilment a altres
  sistemes amb un maquinari diferent.

• Cal conèixer a fons l’arquitectura del sistema i del processador per escriure
  bons programes.

• No permeten expressar de forma directa conceptes habituals a nivell d’algorisme.

• Son difícils de codificar, documentar i mantenir

El següent grup de llenguatges es coneix com a **llenguatges de
tercera generació o llenguatges d’alt nivell**. Aquests llenguatges, més
evolucionats, utilitzen paraules i frases relativament fàcils d’entendre i
proporcionen també facilitats per expressar alteracions del flux de control
d’una forma bastant senzilla i intuïtiva

**Compiladors**

Són programes que tradueixen el programa escrit amb un llenguatge d’alt nivell
al llenguatge màquina. El compilador detectarà els possibles errors del programa
font per aconseguir un programa executable depurat.

   **- Procediment:**
   
    • Crear el codi font.
    • Crear el codi executable fent ús de compiladors i enllaçadors.
    • El codi executable depèn de cada sistema operatiu. Per a cada sistema hi
      ha un compilador, és a dir, si es vol executar el codi amb un altre sistema
      operatiu s’ha de recompilar el codi font.
    • El programa resultant s’executa directament des del sistema operatiu

**Els intèrprets**


L’intèrpret és un programa que tradueix el codi d’alt nivell a codi de bytes, però, a
diferència del compilador, ho fa en temps d’execució. És a dir, no es fa un procés
previ de traducció de tot el programa font a codi de bytes, sinó que es va traduint
i executant instrucció per instrucció.

   **- Característiques:**
   
    • El codi interpretat no és executat directament pel sistema operatiu, sinó que
      fa ús d’un intèrpret.
    • Cada sistema té el seu propi intèrpret.

L'interpret es més lent que el compilador, ja que du a terme la
traducció alhora que l’execució. 

##1.3.2 Característiques dels llenguatges de tercera, quarta i cinquena generació##

**Avantatges**

      • El codi dels programes és molt més senzill i comprensible.
      • Són independents del maquinari (no hi fan cap referència). Per aquest motiu
        és possible “portar” el programa entre diferents ordinadors / arquitectures/
        sistemes operatius (sempre que en el sistema de destinació existeixi un 
        compilador per a aquest llenguatge d’alt nivell).
      • És més fàcil i ràpid escriure els programes i més fàcil mantenir-los
      
**Inconvenients**

      • La seva execució en un ordinador pot resultar més lenta que el mateix
        programa escrit en llenguatge de baix nivell, tot i que això depèn molt de la
        qualitat del compilador que faci la traducció.

Els **llenguatges de quarta generació o llenguatges de propòsit específic.**
Aporten un nivell molt alt d’abstracció en la programació, permetent
desenvolupar aplicacions sofisticades en un espai curt de temps, molt inferior
al necessari per als llenguatges de 3a generació.

**Aspectes positius**

      • Major abstracció.
      • Menor esforç de programació.
      • Menor cost de desenvolupament del programari.
      • Basats en generació de codi a partir d’especificacions de nivell molt alt.
      • Es poden dur a terme aplicacions sense ser un expert en el llenguatge.
      • Solen tenir un conjunt d’instruccions limitat.
      • Són específics del producte que els ofereix.
      
Els **llenguatges de cinquena generació** són llenguatges específics per al
tractament de problemes relacionats amb la intel·ligència artificial i els
sistemes experts
  
  
  
