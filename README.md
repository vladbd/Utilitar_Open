# Utilitar_Open - Among Us dar low-budget
 Proba de Open la Utilitar Infoeducatie
 
 Context: Proba de Open Utilitar de la Infoeducatie 2021 a avut ca tema realizarea unui joc de tip Among Us prin codare, farmece, rage quit-uri, orice numa sa iasa. Aici va trai arhiva cu proiectul meu pana la jurizare si mult timp dupa.
 
 
 Alegere infrastructura:
 
 Programul a fost scris in C# si dezvoltat in Unity. De ce Unity? Pentru ca scripturile se scriu in C#. Stii C#? Da, macar atat cat de cat sa am idee.
 
 
 Past Experience:
 
 In trecut cand invatam C# (basically 2020 pandemie) eram in acelasi timp interesat cum se fac microtranzactiile in jocuri (EA SPORTSSSSSS)  si cum sa fac un joculet si sa incerc sa implementez in joaca ceva de genul. Am dat de Unity pentru ca era mai usor, era mai vast de vazut pe net tutoriale, scripturile erau in C# ceea ce invatam la momentul respectiv si Unreal Engine parea prea mult pentru nivelul meu. Am invatat sa ma descurc putin in Unity, cum se face o animatie pe frameuri, cum se schimba cate ceva cand dai un click sau cum sa faci un movement pe WASD (sus jos stanga dreapta) a unui personaj. La momentul respectiv nu credeam ca imi va folosi vreodata la ceva, dar hei, uite cum te duce viata.
 
 
So, how programel construit?

Ideea in sine nu era grea daca era doar partea pe care o stiam. Un prefab drept personaj sa poata fi folosit, un movement, o animatie. Problema a fost ca totusi e proba de concurs, trebuie sa fie ceva mai misto decat atat. Si am stat eu frumos sa ma uit cum sa sincronizezi personaje, cum se face un lightning, cum se seteaza o scena, niste game design, niste DJ Khaled care tipa "You great, You the beast! Another One! Another One!". Practic astazi am invatat mai multe decat stiam, pt ca baza pe care o aveam deja nu era suficienta decat pt un joculet 2d amarat.


Ziceai ceva de rage quit-uri, poti sa detaliezi?

Da normal!!!! Avand in vedere ca era o complexitate mai mare a jocului decat chestiile de le stiam, fiecare pas pe care doream sa il fac aducea un fail cu el la prima tura, nu cred ca a mers nimic din prima corect, dar heyy asa inveti tho. De la ganduri a ma lasa , de a arunca calculatorul pana la ganduri ca eu o sa am cea mai naspa prezentare. Se poate, uneori anxietatea urla.

Si totusi, cum de ai reusit?

Practic orgoliu. Si niste noroc sa dau de niste resurse de unde sa pot invata fara sa fie mereu in spate un indian cu accent stricat.

Te-a ajutat cineva?

Sincer, mi-as fi dorit. Dar oricine intrebam ba nu a lucrat in Unity, ba era plecat, ba nu raspundea. CSF N-AI CSF.

Ce resurse ai folosit?

In mare parte a fost foarte utila documentatia de la Unity si un alt post de Github care avea detalii despre Iluminarea spatiilor in 2D. Among Us e cunoscut ca are acele shadows care ascund partile mapei in care jucatorul nu se afla, iar tipul acela a avut ceva similar de facut pt alt joc. Destul de util explicat si scris codul. Transparenta totala, there you go : https://www.youtube.com/watch?v=FzGTxfWRIHY /https://github.com/ckawell/LightShafting )

In plus, pentru a face lucrul asta am fost placut surprins sa gasesc ceva ce m-a scos din gandurile mele dubioase de a scoate camere individuale pentru dezvoltare din toata mapa pt shadows, aici (https://gamedev.stackexchange.com/questions/109810/masking-with-3d-object-in-unity) era o discutie despre shadere si materials care a fost o solutie mai rapida decat a lua fiecare perete, al descoase si a face fiecare camera un element in sine. Cu chestia asta, fiecare cub pus reprezenta o bariera si am acoperit toata plansa de cuburi unde erau delimitari de camere, mult mai usor. A iesit bine? Well Kinda, nu e chiar cea mai rafinata chestie, umbrele tot se vad ciudat in functie de player si cred ca tot de la acest buffer mi se misca si personajele simultan, dar sa zicem ca e un feature nou al jocului, nu un bug :)

Cum a mers dezvoltarea?

Interesant. Desi nu stiu sa folosesc Github sa fac versare si practic maxim 2-3 commituri o sa am aici am inregistrat video sa am si eu o dovada despre procesul de munca, nu ca gata l am pus si aia e. Am urcat sa zicem compilatia aici: https://youtu.be/jyejas29YEI


Ce mergea si acum a crapat?

Animatia de miscare. Cand se mica personajul principal avea o schimbare de imagine in frameuri sa para ca picioarele se misca. Acum nu se mai intampla asta. Eu suspectez ca e de la modul in care se misca din cauza barierelor de la cuburi, dar ramane de vazut. Macar fantomita apare.


Ce ai incercat si n a mers deloc?

Daca ai jucat Among Us, ai vazut ca dupa fiecare kill in locul astronautului apare o fantomita si un corp cu os. Am pus acea imagine, am facut un corp din ea dar e ceva ce nu mi se leaga mie acolo. Ramane de vazut.

Am incercat sa implementez un client pt multiplayer. Ma gandeam la photon. M am uitat putin cum functioneaza, dar inca nu mi-a iesit. Poate pana la prezentare iese, dar slabe sanse.


De ce ai scris acest roman?

Amuzament,mai imi ia si mie gandul de la faptul ca nu e chiar mare chestie ce am facut eu azi. Plus ca sigur cineva din juriu va citi si poate rade sau se sperie. E bine sa fie pregatita lumea. :))))


Ceva surprize  pt prezentare?
Sa zicem ca o sa incerc sa introduc ceva interesant pt jurati. Si poate gasesc fisierele cu activitatile interactive (png zic) sa incerc sa fac ceva. Oricum cateva lucruri vor fi interesante.
