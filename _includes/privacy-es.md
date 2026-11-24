# Política de privacidad

Esta política explica cómo **It Is Done** (la «App»), gestionada por **Ring** (empresa individual representada por Yuseung Jang, «nosotros»), trata su información.

Fecha de entrada en vigor: **2026-11-25** (versión anterior: 2026-11-20)

## 1. Resumen

- La App **no tiene registro ni inicio de sesión.** No recopilamos su nombre, correo electrónico, número de teléfono, ubicación, contactos ni fotos.
- Su afirmación, su nombre, su escena, el audio de su escena y sus registros diarios **se guardan en su iPhone.** No conservamos ninguna copia en ningún servidor. Los borradores de la escena se redactan en su dispositivo con el modelo de Apple integrado en el dispositivo (o con plantillas incluidas en la App), por lo que sus palabras no salen del dispositivo para ello. (Si la copia de seguridad de iCloud está activada, estos datos se incluyen en su copia de seguridad de Apple).
- Los datos solo salen de su dispositivo en dos casos, y únicamente si usted lo elige:
  1. **Su escena con voz de narrador.** Si toca **Enviar y escuchar**, el texto de su escena pasa por nuestro servidor de retransmisión hasta Typecast, un servicio de síntesis de voz gestionado por Neosapience. En adelante, «texto de la escena» significa la escena y la afirmación que usted escribió. Si toca **Solo ver el texto**, no se envía nada y su escena y su afirmación aparecen como texto en la pantalla.
  2. **Las copias de seguridad que exporte.** En **Ajustes > Exportar / importar copia de seguridad**, al exportar se crea un único archivo con su escena, sus registros y el audio, y la hoja para compartir lo envía al destino que usted elija (Archivos, AirDrop, Mail, etc.). Nosotros nunca recibimos ese archivo.
- No utilizamos SDK de publicidad ni App Tracking Transparency, y no le rastreamos a través de apps o sitios web de otras empresas.
- Los **datos de uso anónimos y los informes de errores** se envían **solo si toca Permitir** en la App. Si lo rechaza, todas las funciones y compras funcionan exactamente igual.
- Los datos de uso anónimos nunca incluyen lo que usted escribe ni el contenido de sus respuestas durante la configuración inicial. Algunos eventos solo llevan un valor de sí/no (por ejemplo, si una palabra de ejemplo en gris acabó en su respuesta) o un rango de longitud (por ejemplo, la longitud de una escena reescrita).

## 2. Qué tratamos y para qué

| Categoría | Datos | Finalidad | Cuándo |
|---|---|---|---|
| Datos de uso anónimos | Un identificador anónimo aleatorio; un conjunto fijo de eventos (como el avance en la configuración inicial y la visualización de la pantalla de compra) y sus valores (como el número de paso, valores de sí/no, rangos de longitud, producto comprado, precio y moneda); versión de la App; tipo de dispositivo y versión del sistema operativo; idioma; país/ciudad aproximados obtenidos de la dirección IP | Detectar dónde se atascan las personas y mejorar la App | **Solo si usted ha dado su consentimiento** |
| Informes de errores | Nombre y mensaje del error (solo el nombre si el mensaje es largo o podría contener lo que usted escribió), ubicación en el código, versión de la App y del sistema operativo | Encontrar y corregir cierres inesperados y errores | **Solo si usted ha dado su consentimiento** |
| Estado de las compras | Identificador anónimo de comprador; historial de compras y suscripciones (producto, periodo, prueba, estado de renovación/cancelación); país de la tienda | Desbloquear lo que ha comprado y restaurar compras | Al comprar o restaurar (con independencia del ajuste de consentimiento) |
| Correo de soporte | Su dirección de correo electrónico y su mensaje, junto con la versión y la compilación de la App, la versión de iOS, el modelo del dispositivo y el idioma añadidos al final del correo | Responder a su mensaje | Cuando nos escribe desde Ajustes > Contacto |
| Voz de la escena | El texto de su escena (escrito por usted), su idioma, un identificador aleatorio del dispositivo usado para un límite diario, su dirección IP | Convertir su escena en un archivo de audio guardado en su dispositivo | **Solo si lo permite** en la App, cuando se crea su escena o cuando cambia |

- Los datos de pago (como los números de tarjeta) los gestiona Apple. Nosotros nunca los recibimos.
- El archivo de copia de seguridad se crea en su dispositivo y solo va adonde usted lo envíe, por lo que no lo tratamos. Contiene sus propias palabras y su audio; guárdelo como guardaría un documento privado.
- No intentamos identificarle personalmente a partir de estos datos.

## 3. Proveedores de servicios y transferencias internacionales

Utilizamos los siguientes proveedores de servicios. Cada uno protege sus datos conforme a su propia política de privacidad y a sus condiciones contractuales (como un acuerdo de tratamiento de datos).

| Destinatario | Finalidad | Datos | Ubicación · momento · método | Conservación |
|---|---|---|---|---|
| PostHog, Inc. | Almacenar y analizar los datos de uso anónimos y los errores | Datos de uso e informes de errores (sección 2) | Estados Unidos · mientras usa la App · cifrado a través de Internet | Sección 4 |
| RevenueCat, Inc. | Comprobar y restaurar el estado de las compras | Estado de las compras (sección 2) | Estados Unidos · al comprar o restaurar · cifrado a través de Internet | Sección 4 |
| Apple Inc. | Pagos, distribución de la App, solicitud de valoración | Datos de pago y suscripción (vinculados a su cuenta de Apple) | Estados Unidos y otros países · al pagar · sistema de pago de Apple | Según la política de Apple |
| Google LLC (Gmail) | Recibir correos de soporte | Correo de soporte (sección 2) | Estados Unidos y otros países · cuando nos escribe · correo electrónico | Sección 4 |
| Neosapience, Inc. (Typecast) | Sintetizar voz a partir del texto de su escena | Texto de la escena, idioma | República de Corea y otros países · cuando se crea la voz de una escena · cifrado a través de Internet | Según la política de Typecast |
| Cloudflare, Inc. | Servidor de retransmisión entre la App y Typecast (gestionado por nosotros), límite diario | Texto de la escena (se transmite, no se almacena); resúmenes unidireccionales (hashes) del identificador aleatorio del dispositivo y de la IP, con el recuento de ese día | Estados Unidos y otros países · cuando se crea la voz de una escena · cifrado a través de Internet | Recuentos: 2 días |

- Sus políticas: PostHog <https://posthog.com/privacy>, RevenueCat <https://www.revenuecat.com/privacy>, Apple <https://www.apple.com/legal/privacy/>, Google <https://policies.google.com/privacy>, Typecast <https://typecast.ai>, Cloudflare <https://www.cloudflare.com/privacypolicy/>
- Nuestro servidor de retransmisión no registra ni almacena el texto de su escena. El archivo de audio que devuelve se guarda únicamente en su iPhone.
- Para que estos datos no salgan de su dispositivo, desactive en Ajustes la opción de datos de uso y la opción de voz. El estado de las compras es necesario para las funciones de pago.

## 4. Conservación y eliminación

- Datos de uso anónimos e informes de errores: se conservan **1 año** y después se eliminan automáticamente en PostHog.
- Estado de las compras: se conserva mientras su compra o suscripción esté activa y durante el plazo que exija la ley (por ejemplo, 5 años para los registros de pago según la normativa coreana de protección del consumidor).
- Correos de soporte: se conservan **1 año** después de nuestra respuesta y después se eliminan.
- Texto de la escena: no lo conservamos ni nosotros ni el servidor de retransmisión. Los recuentos diarios (valores en hash) se eliminan automáticamente a los **2 días**.
- Los datos de su dispositivo (afirmación, escena, registros, archivos de audio, decisiones de consentimiento) se eliminan al borrar la App. Una copia de seguridad que haya exportado permanece donde la guardó hasta que usted la elimine.
- Método de eliminación: los archivos electrónicos se eliminan de forma que no puedan recuperarse. No conservamos registros en papel.

## 5. Retirada del consentimiento y sus derechos

- **Datos de uso:** en la App, vaya a **Ajustes > Enviar datos de uso anónimos** y desactívelo. El envío se detiene de inmediato. Vuelva a activarlo para reanudarlo. Todo, incluidas las compras, funciona igual en ambos casos.
- **Voz de la escena:** en la App, vaya a **Ajustes > Voz > Crear con voz de narrador** y desactívelo. A partir de ese momento, el texto de su escena no se envía y su escena aparece como texto. Todo, incluidas las compras, funciona igual.
- Puede solicitar el acceso, la rectificación, la supresión o la limitación del tratamiento de sus datos escribiéndonos por correo electrónico (sección 7). Responderemos sin demora (en un plazo de 10 días). Como los datos solo se guardan con un identificador anónimo aleatorio, es posible que no podamos localizar datos que no podamos vincular a usted. Al borrar la App se elimina el identificador anónimo de su dispositivo, de modo que los datos futuros no se vinculan con los anteriores.
- Las suscripciones se cancelan y se reembolsan a través de Apple (Ajustes del iPhone > Cuenta de Apple > Suscripciones, o Ajustes > Gestionar suscripción en la App; reembolsos en <https://reportaproblem.apple.com>).

## 6. Cookies, menores y seguridad

- La App no utiliza cookies. Los datos de uso se agrupan con un identificador aleatorio creado en su dispositivo y no se envían si usted lo rechaza.
- La App no está dirigida a menores de 14 años (o de la edad mínima establecida en su país), y no recopilamos sus datos de forma consciente.
- Seguridad: transferencia cifrada (HTTPS), acceso con el mínimo privilegio y autenticación de dos factores en las cuentas de los proveedores, y recopilación limitada a lo estrictamente necesario.

## 7. Contacto

- Responsable de privacidad: Yuseung Jang, representante
- Correo electrónico: <tomokijang30@gmail.com>
- Responsable del servicio: Ring (empresa individual) · Representante: Yuseung Jang

## 8. Cambios

Si modificamos esta política, publicaremos la nueva versión en esta página con su fecha de entrada en vigor. En caso de cambios importantes, como la recopilación de nuevos tipos de datos, le avisaremos con al menos 7 días de antelación.
