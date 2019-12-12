L'objectif de ce projet �tait de cr�er un jeu type Monopoly en utilisant un ou plusieurs
Design Pattern. Pour rappelle, le Monopoly est un jeu de strat�gie o�, pour gagner, les 
joueurs doivent �liminer les autres. Un joueur est �liminer quand il ne peut plus payer
un joueur ou la banque. Afin de simplifier le projet, un certains nombre de r�gles ont �t�
modifi�es voire supprim�es.

Dans notre cas, nous avons utilis� deux Design Pattern diff�rents.

Premi�rement, le Design Pattern Singleton. Le Design Pattern Singleton offre l'un des meilleurs
moyens de cr�er un objet. Ce mod�le implique une seule classe, qui s'occupera de g�rer l'objet,
tout en s'assurant qu'une seule unit� de cet objet soit cr��. Ladite classe permet d'acc�der
� l'objet cr�� sans avoir besoin de l'instancier, ce qui peut se r�v�ler tr�s utile.

Deuxi�mement, nous avons choisi d'utiliser le Design Pattern State. Il permet que le comportement
d'une classe change en fonction de son �tat. Typiquement, nous avons utilis� cela � notre avantage :
au d�but du tour d'un joueur, on v�rifie s'il est emprisonn�. Si tel est le cas, la classe aura un
comportement diff�rent (tour de jeu "prison") de s'il ne l'est pas (tour de jeu "classique"). Les
diff�rents comportements sont g�r�s par diff�rents objets (qui repr�sentent les diff�rents �tats)
et un context object dont le comportement varie en fonction des changements d'�tats de son objet.

