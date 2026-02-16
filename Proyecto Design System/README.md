# Boarding Pass & Checkout Design System

![Captura del proyecto](captura.png) 

Este proyecto es una interfaz de usuario (UI) moderna y funcional para un flujo de compra de tickets de avión. Se centra en la experiencia del usuario (UX), la fluidez de las animaciones y el diseño de componentes personalizados desde cero utilizando tecnologías web puras.

Link del proyecto en vivo: https://mi-resumen-de-vuelo.netlify.app/


Características Principales

Resumen de Compra Interactivo: 
Selección de tickets con feedback visual inmediato (cambio de saturación y estados de selección).

Checkout Inteligente:
Selección de métodos de pago con radio-buttons personalizados integrados en un Design System.
Detección dinámica del tipo de tarjeta (Visa/Mastercard) en tiempo real.
Formulario de tarjeta colapsable según el método de pago elegido.

Micro-interacciones de Alto Nivel:
Selector de cuotas flotante para evitar los menús estándar del sistema.
Transición de pago con una pantalla de carga sutil ("Procesando pago").
Transiciones entre pantallas sin saltos de layout (control de scrollbar estable).

Tecnologías Utilizadas
HTML5: Estructura semántica.
CSS3 (Vanilla): Diseño 100% personalizado, variables CSS para el sistema de diseño y animaciones complejas.
JavaScript (Vanilla): Lógica de procesamiento de pagos, validación de formularios y manejo del DOM sin dependencias externas.


Desafíos Técnicos y Soluciones

Durante el desarrollo, me enfoqué en resolver problemas comunes de UX que suelen pasarse por alto:

Píxel Perfect: Solución de problemas de centrado en componentes de radio usando técnicas de sombras internas (box-shadow) para evitar el desplazamiento de sub-píxeles.
Fluidez Visual: Implementación de cambios de color de fondo dinámicos en el 
html y body durante las transiciones para asegurar que la barra de scroll y los bordes de la pantalla sean imperceptibles y estéticos.
Validación Robusta: Sistema de validación que habilita el botón de pago solo cuando todos los requisitos (incluyendo cuotas obligatorias para tarjetas específicas) se cumplen.