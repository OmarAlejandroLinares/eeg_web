<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electroencefalografía-CIC</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" />
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css" />
</head>

<body>
    <div class="scroll-up-btn">
        <i class="fas fa-angle-up"></i>
    </div>
    <nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#">Electro<span>encefalo</span>grafía</a></div>
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Inicio</a></li>
                <li><a href="#about" class="menu-btn">Acerca de</a></li>
                <li><a href="#services" class="menu-btn">Tarjetas</a></li>
                <li><a href="#skills" class="menu-btn">Información</a></li>
                <li><a href="#teams" class="menu-btn">Integrantes</a></li>
                <li><a href="#contact" class="menu-btn">Contacto</a></li>
            </ul>
            <div class="menu-btn">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </nav>

    <!-- Home section start -->
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1">¡Hola! Te da la bienvenida el laboratorio de</div>
                <div class="text-2">Procesamiento Digital de Señales</div>
                <div class="text-3">al sitio donde aprenderás de <span class="typing"></span></div>
                <a href="#about">¡Comencemos!</a>
            </div>
        </div>
    </section>

    <!-- About section start -->
    <section class="about" id="about">
        <div class="max-width">
            <h2 class="title">Acerca del proyecto</h2>
            <div class="about-content">
                <div class="column left">
                    <img src="images/eeg-1.jpg" alt="">
                </div>
                <div class="column right">
                    <div class="text">Este sitio web está enfocado a aprender de <span class="typing-2"></span></div>
                    <p>El objetivo del proyecto es el construir un electroencefalógrafo no invasivo, así como el desarrollar aplicaciones de software del electroencefalógrafo para realización de tareas de interfaces Cerebro-Computadora.</p>
                    <a href="#">Inicio</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services section start -->
    <section class="services" id="services">
        <div class="max-width">
            <h2 class="title">Tarjetas informativas</h2>
            <div class="serv-content">
                <div class="card">
                    <div class="box">
                        <i class="fas fa-brain"></i>
                        <div class="text">Electroencefalografía</div>
                        <p>El electroencefalograma (EEG) es un análisis que se utiliza para detectar anomalías relacionadas con la actividad eléctrica del cerebro. Este procedimiento realiza un seguimiento de las ondas cerebrales y las registra.</p>
                    </div>
                </div>

                <div class="card">
                    <div class="box">
                        <i class="fas fa-brain"></i>
                        <div class="text">Potenciales de acción</div>
                        <p>Son cambios del potencial de membrana que se propagan a lo largo de la superficie de células excitables. Se miden mejor en las células nerviosas y musculares.</p>
                    </div>
                </div>

                <div class="card">
                    <div class="box">
                        <i class="fas fa-brain"></i>
                        <div class="text">Aplicación</div>
                        <p>La mayoría de los electroencefalogramas se hacen para diagnosticar y controlar trastornos convulsivos, del sueño y cambios de conducta, así como evaluar la actividad cerebral ante lesiones graves en la cabeza o incluso como estudio
                            previo para el trasplante de corazón o de hígado.</p>
                    </div>
                </div>

                <div class="card">
                    <div class="box">
                        <i class="fas fa-brain"></i>
                        <div class="text">Prototipo</div>
                        <p>El proyecto consiste en realizar un dispositivo que pueda medir la actividad eléctrica de los biopotenciales del cerebro humano, siendo la técnica de electroencefalografía un aspecto de gran relevancia en la actualidad para estudiar
                            estos procedimientos. Este dispositivo será capaz de enviar las señales a un sitio web. El procedimiento será el siguiente: adquisición de señales EEG a través de los electrodos, filtrado de las señales a través de la tarjeta
                            ADS1299, comunicación SPI y transmisión de datos a través de la ESP32, recepción de datos en el sitio web y almacenamiento de las señales en una base de datos.</p>
                    </div>
                </div>

                <div class="card">
                    <div class="box">
                        <i class="fas fa-brain"></i>
                        <div class="text">Hardware</div>
                        <p>Los sensores y tarjetas principales a usar son:
                        </p>
                        <ul>
                            <li>Electrodos copa de oro.</li>
                            <li>Tarjeta de adquisicón de señales ADS1299.</li>
                            <li>Tarjeta de procesamiento ESP32.</li>
                        </ul>
                    </div>
                </div>

                <div class="card">
                    <div class="box">
                        <i class="fas fa-brain"></i>
                        <div class="text">Pruebas</div>
                        <p>El registro del EEG tiene una duración dependiente de la clase de estudio solicitado: puede variar entre 15 minutos (EEG con activación compleja) hasta 1 hora de registro total (EEG prolongado, EEG de sueño), es decir, puede efectuarse
                            estando el paciente despierto o dormido.</p>
                    </div>
                </div>


            </div>
        </div>
    </section>

    <!-- Skills section start -->
    <section class="skills" id="skills">
        <div class="max-width">
            <h2 class="title">Información</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text">Sistema nervioso</div>
                    <p>El sistema nervioso es una red compleja de estructuras especializadas (encéfalo, médula espinal y nervios).</p>
                    <p>El sistema nervioso es un complejo conjunto de células encargadas de dirigir, supervisar y controlar todas las funciones y actividades de nuestros órganos y organismo en general, pues relaciona todas las funciones y estímulos de las
                        diferentes partes del cuerpo humano a través de este sistema central.</p>
                    <p>Se divide en dos grandes subsistemas: 1) sistema nervioso central (SNC) compuesto por el encéfalo y la médula espinal; y 2) sistema nervioso periférico (SNP), dentro del cual se incluyen todos los tejidos nerviosos situados fuera del
                        sistema nervioso central.</p>
                    <p>El SNC está formado por el encéfalo y la médula espinal. El encéfalo es la parte del sistema nervioso central contenida en el cráneo y el cuál comprende el cerebro, el cerebelo y el tronco del encéfalo o encefálico. La médula espinal
                        es la parte del sistema nervioso central situado en el interior del canal vertebral y se conecta con el encéfalo a través del agujero occipital del cráneo. El SNC (encéfalo y médula espinal) recibe, integra y correlaciona distintos
                        tipos de información sensorial.</p>
                    <p>Además el SNC es también la fuente de nuestros pensamientos, emociones y recuerdos. Tras integrar la información, a través de funciones motoras que viajan por nervios del SNP ejecuta una respuesta adecuada.</p>
                    <p>El sistema nervioso periférico está formado por nervios que conectan el encéfalo y la médula espinal con otras partes del cuerpo. Los nervios que se originan en el encéfalo se denominan nervios craneales, y los que se originan en la
                        médula espinal, nervios raquídeos o espinales. Los ganglios son pequeños acúmulos de tejido nervioso situados en el SNP, los cuales contienen cuerpos neuronales y están asociados a nervios craneales o a nervios espinales. Los nervios
                        son haces de fibras nerviosas periféricas que forman vías de información centrípeta (desde los receptores sensoriales hasta el SNC) y vías centrífugas (desde el SNC a los órganos efectores).</p>
                </div>
                <div class="column right">
                    <img class="vertical" src="images/eeg-2" alt="">
                </div>

                <div class="column left">
                    <div class="text">Neurona</div>
                    <p>Las neuronas son las subunidades estructurales y funcionales básicas del sistema nervioso; están especializadas para responder a estímulos físicos y químicos, conducir impulsos electroquímicos, y liberar reguladores químicos. Por medio
                        de estas actividades, las neuronas permiten la percepción de estímulos sensoriales, el aprendizaje, la memoria, y el control de músculos y glándulas. Casi ninguna neurona puede dividirse mediante mitosis, aunque muchas pueden regenerar
                        una porción cortada o emitir ramas nuevas pequeñas en ciertas condiciones.</p>
                </div>
                <div class="column right">
                    <img class="cuadrado" src="images/neurona.jpg" alt="">
                </div>

                <div class="column left">
                    <div class="text">Ondas cerebrales</div>
                    <p>Nuestro cerebro produce impulsos eléctricos (potenciales de acción) que viajan a través de nuestras neuronas. Estos impulsos eléctricos producen ritmos que son conocidos como ondas cerebrales. Los impulsos eléctricos son información
                        que viaja de neurona a neurona haciendo uso de cientos de miles de ellas para lograr transportarse y ejecutar una función determinada.</p>
                    <p>A continuación, se enlistan los diferentes tipos de ondas cerebrales existentes en el cuerpo humano:</p>
                    <ul>
                        <li>Ondas Beta: Estas señales tienen una amplitud por debajo de los 100μV, con una frecuencia que varía entre 13 y 30 Hz. Éstas se generan cuando el cerebro está despierto o implicado en actividades mentales como: estudiando, realizando
                            un problema de matemáticas, etc. su cerebro se encuentra emitiendo este tipo de ondas.</li>
                        <li>Ondas Alfa: Las ondas alfa oscilan a una frecuencia entre 8 y 12 Hz. Estas ondas representan un estado de escasa actividad cerebral y relajación. Una persona que ha terminado una tarea y se sienta a descansar, se encuentra a menudo
                            en este estado alfa.</li>
                        <li>Ondas Theta: Estas ondas son de amplitud inferior a 100μV, con una frecuencia de 3.5-7 Hz. Se alcanzan bajo un estado de calma profunda. La persona que está fantaseando se encuentra en este estado, así como la persona que, tras
                            conducir un rato, de repente se da cuenta de que no recuerda cómo ha hecho los últimos kilómetros. Se dice que es un estado de inspiración de ideas y soluciones creativas.</li>
                        <li>Ondas Delta: Ondas de baja frecuencia y alta intensidad, con una frecuencia menor a 3.5 Hz. Nunca llegan a cero, pues eso significaría la muerte cerebral. Se generan ante un estado de "sueño profundo". Cuando nos vamos a dormir,
                            las ondas cerebrales van pasando sucesivamente de beta a alfa, theta y finalmente, delta. Durante el sueño se producen ciclos que duran unos 90 minutos.</li>
                        <li>Ondas Gamma: Son las ondas más rápidas, se producen en ráfagas cortas. Relacionadas con el proceso de información simultánea en varias áreas del Sistema Nervioso Central. Observadas en estados de alta resolución del cerebro, de
                            espiritualidad, sensación de altruismo, amor, percepciones y consciencia, desaparece durante la anestesia.</li>
                    </ul>
                </div>
                <div class="column right">
                    <img class="cuadrado" src="images/eeg-3.jpg" alt="">
                </div>

                <div class="column left">
                    <div class="text">Sistema de estandarización 10-20</div>
                    <p>El sistema internacional 10-20, también conocido como sistema 10-20, es un método reconocido internacionalmente para describir y aplicar la ubicación de los electrodos del cuero cabelludo en el contexto de un examen de EEG. Este método
                        se desarrolló para mantener métodos de prueba estandarizados que garanticen que los resultados del estudio de un sujeto (clínico o de investigación) puedan ompilarse, reproducirse, analizarse y compararse de manera efectiva a través
                        del método científico. El sistema está basado en la relación entre la ubicación de un electrodo y el área subyacente del cerebro, específicamente la corteza cerebral.</p>
                    <p>Los números 10/20 hacen referencia al porcentaje (10 y 20) de distancia en la que deben estar colocados los electrodos en la parte frontal, occipital, de lado derecho e izquierda del cráneo. Cada sitio tiene una letra para identificar
                        el lóbulo y un número para identificar la ubicación del hemisferio.</p>
                    <p>Vea la imagen de la derecha, donde A es la vista de colocación del Sistema 10-20 desde una vista lateral y la B desde una vista superior.</p>
                </div>

                <div class="column right">
                    <img class="horizontal" src="images/sistema10-20.png" alt="">
                </div>

                <div class="column left">
                    <div class="text">Electrodos</div>
                    <p>Parar la adquisición de la información generada por el cerebro, se hace necesario el empleo de transductores que conviertan las corrientes iónicas celulares pertenecientes a los potenciales de acción de la despolarización de estas,
                        en corriente eléctricas que puedan ser manipuladas. Los transductores empleados para este proceso son los que se conocen como electrodos.</p>
                    <p>Pueden captarse por diversos procedimientos:</p>
                    <ul>
                        <li>Sobre el cuero cabelludo.</li>
                        <li>En la base del cráneo.</li>
                        <li>En cerebro expuesto.</li>
                        <li>Localizaciones cerebrales profundas.</li>
                    </ul>
                </div>
                <div class="column right">
                    <img class="horizontal" src="images/electrodos.Png" alt="">
                </div>

                <div class="column left">
                    <div class="text">Preparación de EEG</div>
                    <p>Antes de realizar un EEG se debe dar un tratamiento preparatorio a la piel, y eliminar de la superficie la grasa y las células muertas, para así luego disponer de un gel o una pasta conductora que mejore el contacto, el cual se puede
                        valorar midiendo la impedancia entre el electrodo y la piel. Para buenos resultados, la impedancia no debería estar muy por encima de los 5 kΩ.</p>
                    <ol>
                        <li>Limpiar el área donde se van a colocar los electrodos; es decir esta área debe ser previamente limpiada con una gasa con alcohol para retirar las impurezas.</li>
                        <li>La piel y los electrodos deben ser untados con gel Ten-20. Éste es muy importante ya que adhiere el electrodo al cuero cabelludo, produciendo un gran acoplamiento.</li>
                        <li>Una vez energizado el EEG se debe tener precaución que los electrodos no se choquen ya que producirían un cortocircuito.</li>
                    </ol>
                </div>
                <div class="column right">
                    <img class="horizontal" src="images/preparacion.jpg" alt="">
                </div>

                <div class="column left">
                    <div class="text">Interfaz Cerebro Computdara</div>
                    <p>Un sistema "Interfaz Cerebro-Computadora" o BCI permite a una persona con discapacidad motora interactuar con su entorno sin usar el sistema nervioso periférico, a través de codificar mensajes y comandos que se identifican al extraer
                        características del EEG espontáneo, de potenciales evocados o de potenciales de acción neuronal. La operación de un BCI depende de la interacción del usuario, quien debe aprender a codificar su intención de realizar una tarea con
                        el módulo de traducción y decodificación de esas intenciones. El desarrollo de los BCI aún se encuentra en etapas tempranas. No está claro qué tan lejos pueda llegar, lo que es claro es que ello depende de un gran número de cuestiones,
                        entre las que se incluyen las que se mencionan en seguida. Los BCI actuales aún tienen tasas de transferencia de información máxima de 10-25 bits/min. Esto limita la capacidad de que puedan ser valorados por personas con discapacidades
                        motoras graves. Al mismo tiempo, muchas aplicaciones de la tecnología BCI, como el control de prótesis, pueden requerir altas tasas de transferencia de información.</p>
                    <a href="#">Inicio</a>
                </div>
                <div class="column right">
                    <img class="horizontal" src="images/bci.png" alt="">
                </div>
            </div>
        </div>
    </section>

    <!-- teams section start -->
    <section class="teams" id="teams">
        <div class="max-width">
            <h2 class="title">Equipo de trabajo</h2>
            <div class="carousel owl-carousel">
                <div class="card">
                    <div class="box">
                        <img src="images/profile-1.JPG" alt="">
                        <div class="text">José Luis Oropeza Rodríguez</div>
                        <p>Doctor en Ciencias de la Computación. Director del proyecto presentado y miembro del laboratorio de Procesamiento Digital de Señales.</p>
                        <p class="email-salto">Email:</p>
                        <p>joropeza@cic.ipn.mx</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/profile-2.jpg" alt="">
                        <div class="text">Omar Alejandro Linares Escobar</div>
                        <p>Ingeniero biomédico egresado del IPN. Especialista en proyectos de ingeniería enfocados al área de la salud, actualmente trabajando en el desarrollo de un electroenefalógrafo.</p>
                        <p class="email-salto">Email:</p>
                        <p>olinarese2021@cic.ipn.mx</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/profile-3.jpg" alt="">
                        <div class="text">Victor Hugo Becerril Bueno</div>
                        <p>Ingeniero biomédico egresado de la UPIBI. Especializado en software embebido y actualmente trabajando en la arquitectura de un DSP.</p>
                        <p class="email-salto">Email:</p>
                        <p>vhbb98@gmail.com
                        </p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/profile-4.jpg" alt="">
                        <div class="text">Oscar Islas García</div>
                        <p>Ingeniero biónico egresado de UPIITA. Especializado en desarrollo de proyectos enfocados a bases de datos, actualmente trabajando en la recepción de datos a sitio web por comunicación inalámbrica.</p>
                        <p class="email-salto">Email:</p>
                        <p>oislas2021@cic.ipn.mx</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- contact section start -->
    <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contáctanos</h2>
            <div class="contact-content">
                <div class="column left">
                    <div class="text">Manténgase en contacto con nosotros</div>
                    <p>Este sitio web además de ser para propósitos informativos, es para crear una comunidad de especialistas y apasionados al área con los cuáles colaboremos en equipo.</p>
                    <div class="icons">
                        <div class="row">
                            <i class="fas fa-user"></i>
                            <div class="info">
                                <div class="head">Centro/Instituto:</div>
                                <div class="sub-title">Centro de Investigación en Computación (CIC) - Instituto Politécnico Nacional (IPN).</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-map-marker-alt"></i>
                            <div class="info">
                                <div class="head">Dirección:</div>
                                <div class="sub-title">Avenida Juan de Dios Bátiz No. S/N, Col Nuevo Industrial Vallejo, Gustavo A. Madero, Ciudad de México, C.P. 07738.</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-envelope"></i>
                            <div class="info">
                                <div class="head">Email:</div>
                                <div class="sub-title">joropeza@cic.ipn.mx</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Envíeme un correo electrónico</div>
                    <form action="#">
                        <div class="fields">
                            <div class="field name">
                                <input type="text" placeholder="Nombre" required>
                            </div>
                            <div class="field email">
                                <input type="email" placeholder="Email" required>
                            </div>
                        </div>
                        <div class="field">
                            <input type="text" placeholder="Asunto" required>
                        </div>
                        <div class="field textarea">
                            <textarea cols="30" rows="10" placeholder="Mensaje..." required></textarea>
                        </div>
                        <div class="button-area">
                            <button type="submit">Enviar mensaje</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- footer section start -->
    <footer>
        <span>Creado por Omar Linares <a href="#">Lab. Procesamiento Digital de Señales</a> | <span class="far fa-copyright"></span>2022 All rights reserved.</span>
    </footer>
    <script src="script.js"></script>
</body>

</html>
