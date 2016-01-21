#1.5 Característiques dels llenguatges més difosos#

Es basa en el denominat teorema de l’estructura. Per això utilitza
únicament tres estructures: seqüència, selecció i iteració, essent innecessari
l’ús de la instrucció o instruccions de transferència incondicional.

**Claredat**: Hi haurà d’haver prou informació al codi per tal que el programa pugui ser
entès i verificat

**Teorema de l’estructura**

Tot programa es pot escriure utilitzant únicament les tres estructures
bàsiques de control:

       • Seqüència: instruccions executades successivament, una darrere l’altra.
       • Selecció: la instrucció condicional amb doble alternativa, de la forma
         “si condició, llavors SentènciaA, sinó SentènciaB”.
       • Iteració: el bucle condicional “mentre condició, fes SentènciaA”, que
         executa les instruccions repetidament mentre la condició es compleixi.  

**Disseny descendent**

El disseny descendent és una tècnica que es basa en el concepte de “divideix i
venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta
de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un
nivell més abstracte i finalitzant en un nivell de detall

**Programació modular**

En la majoria de llenguatges, els mòduls es tradueixen a:

        • Procediments: són subprogrames que duen a terme una tasca determinada
          i retornen 0 o més d’un valor. S’utilitzen per estructurar un programa i
          millorar la seva claredat.
        • Funcions: són subprogrames que duen a terme una determinada tasca i
          retornen un únic resultat o valor. S’utilitzen per crear operacions noves que
         no ofereix el llenguatge.
         
**Tipus abstractes de dades (TAD)**

En programació, el tipus de dades d’una variable és el conjunt de valors que la
variable pot assumir. 

Fins fa uns anys, tota la programació es basava en aquest concepte de tipus i no
eren pocs els problemes que apareixien, lligats molt especialment a la complexitat
de les dades que s’havien de definir. Va aparèixer la possibilitat de poder definir
tipus abstractes de dades, on el programador pot definir un nou tipus de dades i
les seves possibles operacions.

**1.5.2 Característiques de la programació orientada a objectes**

Un dels conceptes importants introduïts per la programació estructurada és l’abstracció
de funcionalitats a través de funcions i procediments.permet a un programador utilitzar una funció o procediment coneixent només què
fa, però desconeixent com ho fa.

                     • Les funcions i procediments comparteixen dades del programa, cosa que
                     provoca que canvis en un d’ells afectin a la resta.
                     • Al moment de dissenyar una aplicació és molt difícil preveure detalladament
                     quines funcions i procediments necessitarem.
                     • La reutilització del codi és difícil i acaba consistint a copiar i enganxar
                     determinats trossos de codi, i retocar-los. Això és especialment habitual
                     quan el codi no és modular.


**L’orientació a objectes** (en endavant, OO) és un paradigma de construcció
de programes basat en una abstracció del món real.

**Un objecte** és una combinació de dades (anomenades atributs) i mètodes
(funcions i procediments) que ens permeten interactuar amb ell. En OO,
doncs, els programes són conjunts d’objectes que interactuen entre ells a
través de missatges (crides a mètodes).

**Abstracció**

En la tecnologia orientada a objectes l’eina principal per suportar l’abstracció és la
**classe**. Es pot definir una classe com una descripció genèrica d’un grup d’objectes
que comparteixen característiques comunes, les quals són especificades en els seus
atributs i comportaments.

**Encapsulació**

              • Públic: qualsevol classe pot accedir a qualsevol atribut o mètode declarat
              com a públic i utilitzar-lo.
              • Protegit: qualsevol classe heretada pot accedir a qualsevol atribut o mètode
              declarat com a protegit a la classe mare i utilitzar-lo.
              • Privat: cap classe no pot accedir a un atribut o mètode declarat com a privat
              i utilitzar-lo.
              
**Modularitat**

Permet poder modificar les característiques de cada una de les classes que defineixen
un objecte, de forma independent de la resta de classes en l’aplicació.

**Jerarquia**

Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un
sistema complex són l’herència i l’agregació.

**El polimorfisme**

És una característica que permet donar diferents formes a un mètode, ja sigui en
la definició com en la implementació.
La sobrecàrrega (overload) de mètodes consisteix a implementar diverses vegades
un mateix mètode però amb paràmetres diferents, de manera que, en invocar-lo, el
compilador decideix quin dels mètodes s’ha d’executar, en funció dels paràmetres
de la crida.




