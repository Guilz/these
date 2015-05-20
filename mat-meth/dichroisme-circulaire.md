# Dichroïsme circulaire

Les protéines sont dialysées dans un tampon Tris-HCl 9 mM pH = 7,5, NaF 300 mM.
Pour chaque protéine, l'acquisition des spectres de dichroïsme circulaire est
faite sur une série de concentrations : 3, 6 et 15 μM en protéine (concentration
exprimée en monomères pour TRF2). Les spectres sont mesurés dans une cuve en
quartz de 200 μL et 1 mm de trajet optique, avec un appareil Jasco J-815 CD
Spectrometer. Chaque spectre est obtenu par l'accumulation de 20 acquisitions de
250 à 190 nm de longueur d'onde par pas de 0,1 nm et avec une largeur de bande
de 2 nm. Les spectres finaux des protéines sont obtenus en soustrayant le
spectre du tampon aux spectres initiaux. Pour pouvoir comparer les spectres
entre eux, ils sont finalement exprimés en ellipticité molaire résiduelle selon
la formule suivante :

$[θ] = \frac{θ}{10 \times c \times L \times n}$

où *[θ]* est l'ellipticité molaire résiduelle (en deg.cm^2^.dmol^-1^.résidu^-1^),
*θ* est le signal de dichroïsme circulaire brut tel qu'enregistré par le
spectromètre (en mdeg), *c* est la concentration molaire en protéine (en
mol.L^-1^), *L* est le trajet optique (en cm) et *n* est le nombre de résidus
dans la protéine.

Pour une comparaison directe entre RAP1 et ARAGA, les spectres sont aussi mis
à l'échelle pour que leur valeur à 209,5 nm (point d'inflexion) coincide : ceci
permet de s'affranchir des différences d'amplitude dues à l'incertitude sur la
détermination de la concentration en protéine (estimée par l'absorbance à 280 nm
mesurée avec un appareil NanoDrop, moins sensible que le spectromètre de
dichroïsme circulaire).  

La dénaturation thermique des protéines est suivie par la mesure du signal de
dichroïsme circulaire à 222 nm (principal signal des hélices α) pendant que
l'échantillon est chauffé de 10 à 95 °C par pas de 1 °C. Les données de
dénaturation thermique sont modélisées avec une courbe sigmoïde à l'aide du
logiciel SciDAVis (<http://scidavis.sourceforge.net>) afin d'estimer la valeur
de la température de demi-dénaturation T~m~.
