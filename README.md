# Laboratorio-Guia-6
# Informe de laboratorio de circuitos
Trabajo grupal sobre la SEPTIMA practica de laboratorio

### PRÁCTICA No. 7 CARACTERÍSTICAS DE LA ONDA SENOIDAL
#### OBJETIVO GENERAL
-	Determinar experimentalmente las características de señales senoidales.
rectangular
#### OBJETIVO ESPECIFICO
-  	Por medio del circuito realizado en algún simulador de preferencia evidenciar el desplazamiento de la onda.
-  	Conocer el tono y la intensidad de las ondas.
-  	Observar cómo se representa el valor de la tensión de la Corriente alterna a través de un tiempo continuamente variable
#### MARCO TEORICO

![image](https://user-images.githubusercontent.com/76060654/109690048-ec2ff500-7b53-11eb-9051-9ab4f17a2f2e.png)
![image](https://user-images.githubusercontent.com/76060654/109690064-f05c1280-7b53-11eb-87d0-4ea761285322.png)
![image](https://user-images.githubusercontent.com/76060654/109690081-f3570300-7b53-11eb-9765-56eb0d584744.png)
![image](https://user-images.githubusercontent.com/76060654/109690087-f520c680-7b53-11eb-8b38-311998da84b0.png)

### REQUISITOS PREVIOS
Investigar la representación de la onda senoidal, tanto en su forma gráfica como en su forma matemática.

### INFORMACION GENERAL
Se denomina corriente alterna (ca) a la corriente eléctrica en la que la magnitud y dirección varían periódicamente. La forma de onda de la corriente alterna más comúnmente utilizada es la de una onda senoidal, puesto que se consigue una transmisión más eficiente de la energía.
Generalmente, la corriente alterna se refiere a la forma en la cual la electricidad llega a los hogares y a las empresas. Sin embargo, las señales de audio y de radio transmitidas por los cables eléctricos, son también ejemplos de corriente alterna.
### DIAGRAMA:

![image](https://user-images.githubusercontent.com/76060654/109690115-fe119800-7b53-11eb-9da6-22dcd4a089f3.png)

#### LISTA DE COMPONENTES

![image](https://user-images.githubusercontent.com/76060654/109690131-036ee280-7b54-11eb-8374-cb0900d41a1d.png)

#### EXPLICACION
Utilizamos el simulador Proteus para la construcción de nuestro circuito utilizamos los que son las resistencias, el osciloscopio, multímetro, la fuente de voltaje con una señal de 20 Vpp y frecuencia de 2.5khz , conectamos de la mejor manera los materiales , medimos con el multímetro el voltaje de salida de RL y nos da un valor de 9.72 [V] de igual forma conectamos el osciloscopio al resistor de carga RL y nos da un valor de 11.25 [V] . 

#### PROCEDIMIENTO
-	Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 KHz.
	
![image](https://user-images.githubusercontent.com/76060654/109690177-12559500-7b54-11eb-9201-dfa61326e763.png)

-	Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.
	
![image](https://user-images.githubusercontent.com/76060654/109690204-1bdefd00-7b54-11eb-8d90-4d0ced1c0240.png)

![image](https://user-images.githubusercontent.com/76060654/109690246-26999200-7b54-11eb-8e4e-94d20da5d385.png)

-	Con el multímetro digital mida el voltaje de salida en RL

![image](https://user-images.githubusercontent.com/76060654/109690282-2e593680-7b54-11eb-9528-4a83603171c1.png)


### TABLA DE DATOS

![image](https://user-images.githubusercontent.com/76060654/109690302-344f1780-7b54-11eb-8ed7-bfc061a1240c.png)

### CALCULOS

![image](https://user-images.githubusercontent.com/76060654/109690326-3b762580-7b54-11eb-8803-97a048e71778.png)

### PREGUNTAS	

#### ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

*Abarca 5 cuadros y medio.

#### ¿En qué valor está posicionada la perilla VOLTS/DIV?

*La posición es: 2 VOLTS/DIV

#### ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

*8 divisiones

####¿En qué valor está posicionada la perilla TIME/DIV?

*50u TIME/DIV

#### ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?

Amplitud de Voltaje: 11.25   [V] 
Periodo: 0.0004 [s]

#### Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.

f: 2500 [Hz]
w: 15707.96 [rad/s]

#### Con el multímetro digital mida el voltaje de salida en RL:

VRL: 9.72 [V]

#### Compare el voltaje medido en el (Osciloscopio) y el obtenido en el (Multímetro) ¿Coinciden? 

No coinciden ya que el valor medido en el osciloscopio es de Vp: 11.25 [V] y el valor medido por el multímetro es de VRL: 9.72 [V]. 

#### ¿Por qué?

Los que nos da el osciloscopio son valores de voltaje pico y en el multimetro no da un valor en RMS y por eso los valores son distintos.

### DESCRIPSION Y PRERREQUISITOS DE CONFIGURACION

Antes de llegar a las operaciones matemáticas o cálculos avanzados se debe tener en cuenta sus características importantes como el conocimiento sobre ellas mismas: Amplitud, Valor Medio, Periodo, Frecuencia.
Las matemáticas que detallan su utilización no son demasiado complejas y han sido estrictamente supervisadas, utilizan las funciones de seno y coseno (para las ondas senoidales o sinusoidales) para realizar cálculos que involucren ondas senoidales se utiliza una calculadora científica que disponga de las funciones trigonométricas seno y coseno, así como sus inversas.
Están son funciones que darán periocidad (funciones repetitivas””).
La función seno y coseno posen una forma idéntica con la excepción de que el coseno está desplazado hacia la izquierda respecto al seno en un cuarto de ciclo “cos x = sen (x + π/2)”.
![image](https://user-images.githubusercontent.com/76060654/109690388-4a5cd800-7b54-11eb-8694-4189ee8b45b0.png)
Existe una forma para representar las ondas senoidales que es la más utilizada: v (t) = vm sen (ωt+φ)
Hay muchas formas de obtener una señal en forma de onda senoidal. Como la utilización de la ley de Faraday, esta indica que, en un circuito cerrado de corriente, por ejemplo, una espira, colocado en medio de un campo magnético, se genera una corriente inducida cuando el flujo de campo magnético a través de ella cambia en el tiempo. 

### APORTACIONES

Las ondas senoidales representan el valor de la tensión de la Corriente alterna a través de un tiempo continuamente variable, en un par de ejes cartesianos marcados en amplitud y tiempo. Responde a la corriente de canalización generada en las grandes plantas eléctricas del mundo. También responden a la misma forma, todas las corrientes destinadas a generar los campos electromagnéticos de las ondas de radio.
También describen verídicamente eventos naturales y señales variables en el tiempo, tales como los voltajes generados por centrales eléctricas y luego utilizados en hogares, industrias y calles.
Otros elementos eléctricos que también producen respuestas sinusoidales son las resistencias, condensadores e inductancias, que se conectan a entradas de voltaje sinusoidal.
Con ayuda de las funciones ya mencionadas anteriormente se expresa una onda senoidal, para esto n el eje vertical se coloca la magnitud en cuestión, mientras que en el eje horizontal se ubica el tiempo.
Gracias a estas funciones se pueden expresar voltajes y corrientes de tipo senoidal variando en el tiempo, colocando en el eje vertical en vez de la y, una v o una i para representar voltaje o corriente, y en el eje horizontal en vez de la x, se coloca la t del tiempo.

![image](https://user-images.githubusercontent.com/76060654/109690415-521c7c80-7b54-11eb-8862-36b32cb39e7b.png)


### CONCLUSIONES

- Antes vistos los números complejos y su teoría facilitan el análisis de los circuitos alternos, como también facilita valores elevados en el trasporte de la energía eléctrica.
- La función seno en términos analíticos y gráficos está perfectamente equilibrada/definida. 
- Las ondas periódicas no senoidale llegan a conocerse como armonios después de descomponerse en suma de una serie de ondas senoidales de diferentes frecuencias.
- Expresado gráficamente las ondas senoidales pueden llegarse a ver muy complejas y confusas, caso contrario con su expresión matemática que facilita su comprensión y estudio.

### BBLIOGRAFIA
https://www.lifeder.com/ondasenoidal/#:~:text=Las%20ondas%20senoidales%20son%20patrones,en%20hogares%2C%20industrias%20y%20calles.
https://tecdigital.tec.ac.cr/repo/rea/electronica/el2114/un_1/11_caractersticas_de_la_funcin_sinusoidal.html
https://prezi.com/afgmqveckl2w/caracteristicas-de-una-onda-senoidal/
http://dis.um.es/~lopezquesada/documentos/IES_1213/LMSGI/curso/xhtml/xhtml6/caracteristicas.html
https://www.ecured.cu/Onda_senoidal

### ANEXOS
![image](https://user-images.githubusercontent.com/76060654/109690438-58125d80-7b54-11eb-8430-6083bcb60746.png)
![image](https://user-images.githubusercontent.com/76060654/109690442-59dc2100-7b54-11eb-976f-147caa701b85.png)
![image](https://user-images.githubusercontent.com/76060654/109690450-5b0d4e00-7b54-11eb-8112-b7b267b6c841.png)
![image](https://user-images.githubusercontent.com/76060654/109690454-5cd71180-7b54-11eb-9c40-aa9db69f746e.png)
![image](https://user-images.githubusercontent.com/76060654/109690459-5e083e80-7b54-11eb-865c-cb92ea9924c6.png)
