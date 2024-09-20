# Virus Simulation

Proyecto de taller de inteligencia artifical y minirobots.

Programado en Netlogo.

[https://fabianmontes.github.io/virussimulation/]

Busca emular el sistema de contagio deun virus para varios tipos de pacientes a travez del tiempo, una simulacion que ejemplifica los automatas celulares y sus reglas, las cuales se definieron en el documento 2.7

para correr primero oprimir setup (reinicia y prepara la imagen) y luego go o step (solo avanzara un tick en step)

La tabla mostrara la cantidad de personas en cada estado, 
donde azules representan personas sanas; (Ps)
rojo son personas contajiadas con sintomas; (Cs)
amarillo son personas contajiadas asintomaticas; (Cns)
naranja son contagiados en cuarentena; (Ct)
verde personas curadas y con anticuerpos; (Pac)
negro personas muertas.

hay tres checks posibles de personalizacion:
Ct_contagia, para confirmar si las personas en cuarentena contagian a los vecinos.
Pac_Contagia, las personas curadas pueden contagiar aun si son inmunes?
NatStart, para reordenar aleatoriamente a las 5000 personas y no en cuadricula.

Los cuadros en amarillo muestran la cantidad exacta de cada tipo en todo momento.


