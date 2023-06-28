# Tarea-Final-Analisis-de-Negocios-2023-2

1) Análisis de encuestas de satisfacción de pasajeros en una línea aérea
   
El problema a tratar se centra en la necesidad de analizar las encuestas de satisfacción de los pasajeros en una línea aérea para comprender su nivel de satisfacción y detectar áreas de posibles mejoras en la calidad del servicio. Se tiene como objetivo la obtención de información que permita tomar decisiones estratégicas para mejorar la experiencia del pasajero y aumentar su fidelidad con la aerolínea.

La industria aérea es altamente competitiva pues en las últimas décadas se ha presentado un crecimiento constante en la demanda de viajes aéreos, dado que la accesibilidad a estos ha aumentado. Esta competencia entre quienes son parte de la industria se da tanto por precios como por la diferenciación del servicio, pero es importante considerar que la primera opción si bien es viable, se llega hasta cierto nivel de precios y ya luego es difícil de sostener. Por ende, resulta crucial la importancia de brindar un servicio de calidad que mantenga satisfechos a los clientes para así lograr mantenerse en el mercado.

Resulta importante identificar aquellas variables que influyen directamente en la satisfacción del pasajero, ya que si se satisface de manera exitosa, los pasajeros serán más propensos a repetir sus viajes con la misma aerolínea y a su vez, recomendarlo a más personas. Por el contrario, si no se logra satisfacer al cliente puede que se genere una pérdida de pasajeros y afectar la demanda futura del servicio mediante el esparcimiento de inconformidades.

Además de la problemática principal, se tienen problemáticas secundarias dada la naturaleza de los datos, tales como el manejo de un gran volumen de observaciones, la identificación de variables significativas para analizar la satisfacción del cliente y la correcta interpretación de los resultados. Para el análisis de encuestas de satisfacción de los pasajeros se entregan dos conjuntos de datos: train.csv (n=103903) y test.csv(n=25977). Dichos conjuntos tienen 25 variables:

• X: Conteo del número de observaciones • Id: Número de identificación de cada pasajero que respondió las encuestas • Género • Tipo de cliente (leal, desleal) • Edad • Tipo de viaje (viaje personal, viaje de negocios) • Clase (business, eco, eco plus) • Distancia de vuelo • Nivel de satisfacción en diversos ámbitos: Servicio de wifi, cumplimiento hora de salida y llegada, reserva online, ubicación de la puerta, comida y bebestibles, embarque en línea, comodidad de los asientos, entretenimiento a bordo, servicio abordo, espacio para las piernas, manejo de equipaje, servicio de check-in, servicio en el vuelo y limpieza (cada uno de los atributos mencionados implica una encuesta de satisfacción por separado) • Minutos de retraso para partir • Minutos de retraso para llegar • Satisfacción de la aerolínea



2) Predicción de arriendo por hora de bicicletas urbanas
   
La problemática a tratar se centra en la necesidad de predecir la demanda de bicicletas compartidas por hora en una ciudad metropolitana, con el propósito de apoyar la movilidad dentro de este espacio urbano y de asegurar los recursos para su correcto funcionamiento, esto se desarrollará por medio de diferentes estrategias brindadas a través de este documento, donde se realizan todos análisis respectivos. 
El concepto de movilidad amigable con el medio ambiente ha sonado bastante en la sociedad de hoy en día, siendo su principal símbolo un medio de transporte que cada vez se vuelve más frecuente y popular en las ciudades de todo el mundo, no solo por su nulo consumo de combustibles y emisión de gases de efecto invernadero, sino que también por su comodidad durante el transporte mismo y su reducido tamaño, la bicicleta se ha convertido en uno de los artefactos preferidos por millones de usuarios para movilizarse día a día a diferentes lugares, promoviendo la idea de un estilo de vida más saludable y sostenible, al mismo tiempo que se reduce la congestión del tráfico y se mejora la calidad del aire, lo cual ha traído consigo un aumento de la demanda en estos aparatos y con esto una visión de oportunidad de negocio de muchas empresas y ciudades. 
Para llevar a cabo estos negocios y contar con una rentabilidad considerable, se debe tener claridad de cuáles son las variables que afectan en la decisión de un usuario de utilizar o no este medio de transporte, conociendo de esta manera la demanda poblacional del entorno y calculando con certeza cual es la disponibilidad requerida en cada momento, para esto se analiza y presenta una base de datos que cuenta con 8760 observaciones y 14 características, dentro de las cuáles se puede encontrar información meteorológica, fecha y número de bicicletas alquiladas por hora, presentándose a continuación cada una de ellas:
	Fecha
	Hora
	Temperatura (°C)
	Humedad (%)
	Velocidad del viento (m/s) 
	Visibilidad (10m) 
	Punto de Rocío (°C)
	Radiación Solar (MJ/m2)
	Nevadas (cm)
	Precipitaciones (mm)
	Temporadas del año: Verano, otoño, invierno, primavera 
	Día festivo: Si es festivo o no es festivo 
	Dia laboral: Si es día laboral o no es día laboral 
	Número de bicicletas rentadas por hora




