# TPI: Modelado Tecnologico y Administrativo de un Sistema Organizacional

## Caso de estudio: El Galpon Gourmet
"Modulo desarrollado": MODULO DE COMANDAS DIGITALES INTEGRADO CON CONTROL DE STOCK.
### Integrante: 
* Paula Cotignola - Tecnicatura Universitaria en Programacion (TUP AD)
* Universidad Tecnologica Nacional (UTN)
* Materia: Organizacion Empresarial (2026)

####  Declaracion de uso de IA:
Para cumplir con las pautas de la catedra, se detalla el uso critico de herramientas de Inteligencia Articial en esta entrega:

* Prompts utilizados:
  1. "Ayudame a estructurar un flujo de procesos con Lanes para un restaurante que automatiza camandas y controla stock"
  2. "Necesito tres indicadores de control cuantitativos para mejorar la eficiencia de una cocina y mejor precision de stock"
* Correcciones humanas:
  La IA propuso inicialmente incluir la caja de restaurante dentro del mismo flujo de cocina.Se corrigio separando el carril de "caja/administracion" para respetar la division formal del organigrama de la entrega 3.


* Estado del modulo: Fase de validacion tecnica

### DESCRIPCION DEL PROBLEMA Y SOLUCION
El restaurante familiar "El Galpon Gourmet" presentaba problemas de comunicacion entre el salon y la cocina debido al uso de anotaciones en papel. La solucion consiste en un modulo de Comandas Digitales que autoriza los pedidos mediante tablets para los mozos, los transmite a pantallas en cocina y realiza el descuento automatico de stock en tiempo real.

### ALCANCE FUNCIONAL
*Carga y registro de pedidos digitales por mesa.
*Validacion automatizada de disponibilidad de ingredientes antes de confirmar la comanda.
*Transmision de pedidos a cocina mediante pantalla KDS.
*Notificacion en tiempo real al mozo cuando el plato esta listo.
*Procesamiento de pagos, emision de facturas y liberacion de mesas.

### ACTORES PRINCIPALES.
*Cliente: solicita atencion , consume y realiza el pago.
*Mozo/salon: registra los pedidos en la tablet y sirve los platos.
*Jefatura de cocina: visualiza las comandas y procesa las preparaciones.
*Caja/Administracion: gestiona el cobro final y emite las facturas.
*Sistema automatizado: procesa las validaciones de stock y la logica del negocio.
