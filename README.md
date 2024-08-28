# Calculadora VLSM

Este proyecto de código abierto proporciona una calculadora de Máscara de Subred de Longitud Variable (VLSM) implementada en HTML, CSS, JavaScript y Bootstrap. La calculadora está diseñada para facilitar a los usuarios la creación y administración de subredes dentro de una red base, optimizando la asignación de direcciones IP de manera eficiente.

## Características

- **Entrada de Red Base:** Permite a los usuarios ingresar una red base en formato CIDR (por ejemplo, 192.168.0.0/24).
- **Generación de Subredes:** Los usuarios pueden especificar la cantidad de subredes necesarias, así como el número de hosts requeridos en cada subred.
- **Cálculo Automatizado:** La calculadora organiza las subredes en función del número de hosts de mayor a menor, asegurando una distribución eficiente de las direcciones IP.
- **Detalles de Subredes:** Genera una tabla con la siguiente información para cada subred:
  - Nombre de la subred
  - Dirección de subred
  - Primer Dirección Válida (P.D.V)
  - Última Dirección Válida (U.D.V)
  - Dirección de Broadcast
  - Prefijo de subred
  - Máscara de subred en formato decimal
- **Interfaz Responsive:** La calculadora utiliza Bootstrap para garantizar una interfaz adaptable y amigable en dispositivos de cualquier tamaño.

## Tecnologías Utilizadas

- **HTML y CSS** para la estructura y el diseño de la página.
- **Bootstrap** para un diseño responsivo y moderno.
- **JavaScript** para la lógica de generación y cálculo de las subredes.

## Contribuciones

Este proyecto está abierto a la colaboración. Los desarrolladores y entusiastas pueden contribuir mejorando el código, añadiendo nuevas funcionalidades, o corrigiendo errores. Las pautas de contribución están disponibles en el repositorio.
