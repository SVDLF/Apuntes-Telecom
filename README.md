# Apuntes-Telecom
Bitácora Técnica de Normatividad en Redes

1. Estándares y Normativas Internacionales

La implementación de estándares internacionales garantiza la compatibilidad entre dispositivos y sistemas de distintos fabricantes, evitando soluciones propietarias que limiten la flexibilidad tecnológica y aumenten los costos operativos.

1.1 Telecommunications Industry Association (TIA)

Organización norteamericana encargada de desarrollar estándares para el diseño, instalación y verificación de sistemas de telecomunicaciones. Sus normas son ampliamente utilizadas en América.

1.2 Electronic Industries Alliance (EIA)

Entidad que históricamente contribuyó al desarrollo de estándares electrónicos. Aunque actualmente no se encuentra activa, su legado permanece en normativas como TIA/EIA-568.

1.3 ISO/IEC

Organización internacional de normalización que establece estándares globales. En el ámbito de redes, destaca la norma ISO/IEC 11801, ampliamente adoptada en Europa y Asia para el diseño de cableado estructurado.

2. Estándar TIA/EIA-568

El estándar TIA/EIA-568 define las especificaciones para el cableado estructurado, incluyendo las configuraciones de terminación para conectores RJ45.

2.1 Configuración T568A

Blanco/Verde

Verde

Blanco/Naranja

Azul

Blanco/Azul

Naranja

Blanco/Marrón

Marrón

2.2 Configuración T568B

Blanco/Naranja

Naranja

Blanco/Verde

Azul

Blanco/Azul

Verde

Blanco/Marrón

Marrón

Imagen de ambas configuraciones
<img width="1024" height="515" alt="image" src="https://github.com/user-attachments/assets/b0d4b588-d3b8-49f4-9982-bac6670caf20" />


Consideración técnica: Ambas configuraciones son funcionalmente equivalentes; sin embargo, es imprescindible mantener la misma norma en ambos extremos del cable para asegurar la correcta transmisión de datos.

3. Clasificación de Rendimiento

A continuación, se presenta una comparación entre las categorías definidas por TIA y las clases establecidas por ISO/IEC:

Velocidad de Transmisión	Categoría (TIA)	Clase (ISO/IEC)	Frecuencia Máxima
1 Gbps	Cat 5e	Clase D	100 MHz
10 Gbps	Cat 6A	Clase EA	500 MHz
40 Gbps	Cat 8	Clase I / II	2000 MHz

4. Glosario de Abreviaciones Técnicas

NEXT (Near-End Crosstalk): Interferencia entre pares de conductores medida en el extremo cercano de la transmisión.

FEXT (Far-End Crosstalk): Interferencia entre pares medida en el extremo opuesto al punto de transmisión.

Return Loss: Indicador de la energía reflejada en el sistema debido a desadaptaciones de impedancia.

PoE (Power over Ethernet): Tecnología que permite suministrar energía eléctrica (entre 44V y 57V DC) a través del mismo cable utilizado para la transmisión de datos.

AWG (American Wire Gauge): Sistema de clasificación del grosor de los conductores; a menor valor, mayor diámetro del cable.

TR (Telecommunications Room): Espacio destinado a la distribución del cableado de telecomunicaciones.

ER (Equipment Room): Sala destinada a albergar equipos principales de red y telecomunicaciones.

5. Normas Complementarias

Además del estándar principal, existen normas que complementan el diseño e implementación de redes estructuradas, especialmente en entornos profesionales e industriales:

TIA-569: Define los requisitos para espacios y canalizaciones, incluyendo ductos, bandejas y distribución física del cableado.

TIA-606: Establece los lineamientos para la administración de la infraestructura, incluyendo etiquetado y documentación.

TIA-607: Regula los sistemas de puesta a tierra, fundamentales para la seguridad eléctrica y el correcto funcionamiento de los equipos.
