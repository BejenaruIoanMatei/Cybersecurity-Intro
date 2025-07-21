# Fundamente de Retelistica

## Modelul OSI

__Open Systems Interconnect Model - OSI__

Modelul OSI este un standard (framework) care defineste modul de comunicare al echipamentelor dintr-o retea.

Este impartit in 7 nivele (straturi), independente (unul de celalalt)

![Alt text](media/image.png)

![Alt text](media/image-1.png)

![Alt text](media/image-2.png)

## Modelul TCP/IP

__TCP (Transmission Control Protocol)__

- face fragmentarea mesajelor in pachete
- asigura transmiterea corecta a mesajelor intre utilizatori

> Pachetele unui mesaj sunt numerotate, putându-se verifica primirea lor în forma în care au fost transmise şi reconstituirea mesajelor lungi, formate din mai multe pachete.

__IP (Internet Protocol)__

- asigura livrarea pachetelor numai daca in functionarea retelelor nu apar erori

> Dacă un mesaj este prea lung, IP cere fragmentarea lui în mai multe pachete

> Transmiterea pachetelor IP se face între calculatoare gazdă şi nu direct între programele de aplicaţie

__TCP/IP__ oferă un foarte mare grad de corecţie al erorilor, deşi nu este uşor de utilizat şi nici cel mai rapid protocol.

Punctele forte ale  stivei __TCP/IP__  sunt:

- este independentă de configuraţia hardware;
- reprezintă o arhitectură care facilitează conectarea în medii eterogene;
- se poate utiliza atât pentru reţele locale (LAN) cât şi pentru reţele globale (WAN);
- este un protocol standard, routabil.

Printre avantajele utilizării acestui protocol se numără:

- este un protocol de reţea routabil suportat de majoritatea sistemelor de operare;
- reprezintă o tehnologie pentru conectarea sistemelor diferite. Se pot utiliza mai multe utilitare de conectivitate standard pentru a accesa şi transfera date între sisteme diferite.;
- este un cadru de lucru robust, scalabil între platforme client / server;
- reprezintă o metodă de acces la resursele interne.

![Alt text](media/image-3.png)

> Protocolul TCP/IP are patru niveluri: Aplicaţie, Transport, Internet,Reţea. El păstrează nivelurile Transport  şi Internet (Reţea)  ale modelului OSI  ca niveluri individuale şi comasează într-un singur nivel ( Aplicaţie), toate nivelurile de peste nivelul Transport (Aplicaţie, Prezentare, Sesiune) , şi într-un nivel ( Reţea), nivelurile de sub nivelul Reţea (Legătură de date şi Fizic).