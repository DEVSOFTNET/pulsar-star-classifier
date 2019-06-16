# pulsar-star-classifier
Clasificador de Estrellas Pulsar

Resumen: 

Pulsar candidates collected during the HTRU survey. Pulsars are a type of star, of considerable scientific interest. Candidates must be classified in to pulsar and non-pulsar classes to aid discovery.

# Fuente: 
Dr Robert Lyon, University of Manchester, School of Physics and Astronomy, Alan Turing Building, Manchester M13 9PL, United Kingdom, robert.lyon '@' manchester.ac.uk

# Sobre los Datos:

HTRU2 es un conjunto de datos recolectado durante la “High Time Resolution Universe Survey (South)” donde se describe una muestra de los candidatos a púlsares.

Los púlsares son estrellas de neutrones altamente magnetizadas con rotaciones rápidas. Estos densos objetos producen ondas de radios que se precipitan en el cielo. A partir de su descubrimiento por Jocelyn Bell Burnell y Antony Hewish, los púlsares han sido material de estudio para temas científicos como la física de los neutrones, relatividad general, campos magnéticos, física planetaria y otros. (Lorimer y Kramer, 2005)

La emisión de destellos de haces de luces por el cielo es debido a la rotación de los púlsares, estos destellos se producen periódicamente. Por lo tanto, el estudio se centra en la búsqueda de las ondas de radio periódicas a través de telescopios.

En cada rotación se emite un patrón de emisión, el cual varía ligeramente entre cada rotación debido a que la onda de radio está viajando a través del medio interestelar, en este caso entre el pulsar y la tierra, esto es conocido como la dispersión de un pulsar. La emisión al momento de viajar en el medio interestelar se ve afectada por la radio interferencia y el ruido. En ausencia de mayor información, cada candidato podría ser un pulsar; sin embargo, debido a la dispersión del pulsar hace muy difícil su identificación. (Hobbs, s.f)

El conjunto de datos contiene 16,259 candidatos alterados por la dispersión pulsar y 1639 candidatos reales. Los datos estarán en un archivo CSV, donde la primera fila tendrá los nombres de las variables  y los candidatos en las siguientes líneas.

# Información de los Atributos:

Cada candidato está conformado por 8 variables y su variable clasificadora. Las primeras 4 variables son estadísticas obtenidas del perfil de pulso integrado. Este es una secuencia de diferentes variables con sus valores continuos que describe una versión de la señal la cual fue promediada en tiempo y frecuencia. Las otras 4 variables siguientes son similares pero provienen de la curva DM-SNR. 

Las variables son las siguientes:

1. Promedio del perfil integrado
2. Desviación estándar del perfil integrado
3. Exceso de curtosis del perfil integrado
4. Asimetría del perfil integrado
5. Promedio de la curva DM-SNR
6. Desviación estándar de la curva DM-SNR
7. Exceso de curtosis de la curva DM-SNR
8. Asimetría de la curva DM-SNR
9. Clasificador

# Fuente Original: 
https://archive.ics.uci.edu/ml/datasets/HTRU2
