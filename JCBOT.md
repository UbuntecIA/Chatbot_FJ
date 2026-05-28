# JCBOT – Manual de Procedimientos

---

## CAPÍTULO 1: TRANSVERSALES (Creación de cliente)

Ofrecer el producto al cliente, siendo explícito en cuanto a las características, beneficios y costos de acuerdo con las condiciones de producto.

Consultar diariamente las listas restrictivas disponibles en la aplicación **Vigía**. En caso de generar alguna alerta durante la consulta, se deberá registrar una solicitud de verificación al área de SARLAFT a través del flujo establecido conforme a lo estipulado en el documento `CF-RIS-PRO-004` Procedimiento SARLAFT. Realizar el proceso de `CF-FR-INS-001` Who is Who.

Diligenciar el formulario que se encuentra en DocManager: **CF-CLI-FOR-005** – Solicitud Única de Vinculación y Actualización de Productos Persona Natural V11.

Verificar diariamente el correcto diligenciamiento del formulario y la entrega de los documentos requeridos que se encuentra en DocManager: **CF-CAT-FOR-002** – Lista de Chequeo Producto Captaciones. En caso de encontrar novedades en el diligenciamiento del formato, devolver al cliente para su normalización.

---

## SARLAFT

### 1. Actualización y manejo de listas restrictivas

- Las listas restrictivas (ONU, OFAC, UE, Interpol, etc.) se cargan automáticamente en VIGÍA cuando el proveedor las actualiza.
- Se valida que la carga haya sido exitosa y, si falla, se reporta al soporte.
- La coincidencia del 95% se evalúa por alta similitud de nombre y coincidencia exacta de identificación.
- El sistema cruza periódicamente estas listas con la base de clientes.
- Si hay fallas entre VIGÍA y BankVision, se activa contingencia manual para cargar listas y hacer cruces por archivo.
- Cuando se detectan coincidencias, se revisan los datos del caso y se aplican las acciones definidas en el Manual SARLAFT.
- Si al consultar aparece restricción o el mensaje de comunicarse con la Unidad de Cumplimiento, la solicitud se tramita por flujo de aprobación y no se continúa hasta obtener respuesta.
- El flujo se encuentra en el equipo de Teams de la oficina y se llama **"Alerta Listas Vinculantes"**.

### 2. Gestión de clientes PEP

- Al vincular un cliente, se identifica si es PEP y el sistema lo marca.
- Para clientes PEP se debe registrar información adicional y obtener aprobación previa del Gerente Líder de Zona, la cual se realiza en el aplicativo **HIT (LEGACY)**.
- La documentación del cliente se carga en los sistemas HIT LEGACY y repositorios definidos.
- La base de clientes PEP se actualiza periódicamente.
- Se cruza información para identificar nuevos PEP o clientes que deban desmarcarse.
- Si hay cambios en la marcación, se informa al área correspondiente y se valida que la actualización quede correcta en el sistema.

### 3. Monitoreo de transacciones

- El sistema genera alertas con base en la transaccionalidad de los clientes.
- Las oficinas deben revisar y responder los casos en VIGÍA con soporte y justificación.
- Si la respuesta es insuficiente o inconsistente, se solicita ampliación de información.
- Si no hay sustento para la operación, se clasifica como inusual y se eleva al Oficial de Cumplimiento.
- Se pueden solicitar documentos adicionales según el análisis del caso.

**Documentos que pueden solicitarse en el análisis del caso:**

- Formularios de vinculación
- Estados Financieros / RUT y/o declaración de renta
- Soporte de cheques
- Facturas
- Soportes de sistemas CORE de movimientos
- Extractos
- Comprobantes de consignaciones
- Comprobantes de retiros
- Soporte de actualización
- Solicitar una actualización con énfasis en actividad económica, información financiera, información demográfica y/o origen de fondos
- Soportes del origen de fondos (ventas de vehículos o inmuebles, litigios o procesos judiciales, herencias, declaración de herederos)
- Carta de Reconocimiento por entrevista o visita (según aplique PN/PJ) realizada por el Gerente Comercial
- Revisión en bases de datos de entidades públicas (policía, procuraduría, rama judicial, fiscalía)
- Pueden surgir otras preguntas con base en el contexto del cliente
- Composición accionaria con los beneficiarios finales y países donde tiene representación (si aplica PJ)
- Si después del análisis la operación se considera sospechosa, se reporta a la UIAF; si no, se cierra el caso documentando el análisis.

### 4. Monitoreo de vinculaciones

- Se revisa la documentación cargada de clientes vinculados.
- Si falta información o está desactualizada, se verifica en los repositorios alternos.
- Cuando se requiere actualizar datos del cliente, se solicita el ajuste al área encargada.
- Una vez realizado el cambio en el sistema, se notifica al área SARLAFT.

### 5. Reportes a la UIAF

- Se generan reportes periódicos de transacciones en efectivo iguales o mayores a $10.000.000.
- También se reportan operaciones en efectivo que sumen igual o mayor a $50.000.000.
- Estos reportes se generan con periodicidad mensual en los primeros 20 días, con la información correspondiente al mes inmediatamente anterior.
- Se reportan productos vigentes, activos, inactivos y cancelados según las reglas del periodo.
- Las operaciones sospechosas se reportan conforme al Manual SARLAFT y al protocolo ROS.

### 6. Mecanismos de control

- Cuando un cliente o proveedor aparece en listas o entes de control, se recibe solicitud de validación o desbloqueo.
- Si se confirma riesgo, no se continúa con el proceso.
- Si se trata de un homónimo o no hay relación con LA/FT, se autoriza continuar o se desbloquea temporal o permanentemente según el caso.
- Se generan informes periódicos para el Oficial de Cumplimiento con resultados de gestión, perfiles de riesgo, controles y reportes.
- El Oficial de Cumplimiento valida la información y la presenta a comité si corresponde.

### 7. Capacitación

- Los funcionarios nuevos reciben capacitación en SARLAFT durante la inducción.
- Todos los funcionarios reciben refuerzo periódico.
- Se hace seguimiento a quienes no hayan completado capacitación o evaluación.
- Si el resultado es bajo, se realiza retroalimentación y nueva evaluación.
- El incumplimiento puede generar llamado de atención.

### 8. Lanzamiento de nuevos productos o servicios

- Antes del lanzamiento, el Oficial de Cumplimiento emite concepto sobre riesgos LA/FT del nuevo producto o servicio.

### 9. Vinculación con países de mayor riesgo

- Se identifica si el cliente o tercero es nacional o extranjero.
- Si es extranjero, se aplica debida diligencia ampliada.
- **Para persona natural:** se profundiza en información financiera y origen de fondos, se debe obtener carta de reconocimiento derivada de la entrevista realizada por el Gerente y se consulta al cliente en listas vinculantes.
- **Para persona jurídica:** se debe completar el formulario de vinculación enfatizando origen de fondos, obtener carta de reconocimiento derivada de la visita o entrevista realizada por el Gerente, consultar al cliente en listas vinculantes, verificar la composición accionaria incluyendo beneficiarios finales y países donde tenga representación, solicitar certificado de existencia y representación legal o su equivalente en el país de origen, y revisar estados financieros.
- La información se remite vía correo a la Unidad de Cumplimiento para análisis.
- Si el país o el caso implica alto riesgo, se escala al Comité SARLAFT para decidir si procede la vinculación.
- La Unidad de Cumplimiento puede recomendar monitoreo, reportes o negar la relación.

---

## WHO IS WHO

### 1. Definiciones

- **Who is Who Ultimate 2.0:** Aplicativo dispuesto por la entidad para que los funcionarios responsables puedan realizar la validación, verificación y reconocimiento de autenticidad de los clientes.
- **Biometría:** Metodología empleada para el reconocimiento inequívoco de los clientes, basada en rasgos físicos intrínsecos como huellas dactilares, retina, iris y patrones faciales.
- **Biométrico de Huella:** Mecanismo TIC instalado en el aplicativo Who Is Who para la captura y registro de los rasgos dactilares del cliente.
- **Biométrico para Iris:** Mecanismo TIC instalado en el aplicativo Who Is Who, mediante cámara o lector, para la captura y registro de los rasgos oculares del cliente.
- **Biométrico para rostro:** Mecanismo TIC instalado en el aplicativo Who Is Who para la captura y registro de los rasgos faciales del cliente.

### 2. Aspectos generales en Oficinas

- El instructivo aplica solo para trabajadores de Financiera Juriscoop.
- Es responsabilidad del asesor comercial informar al cliente sobre el proceso de validación, verificación y reconocimiento de autenticidad.
- Cada oficina contará con escáneres especiales y dispositivos biométricos para la toma de imágenes y registros.
- El acceso al aplicativo también se controla mediante directorio activo.
- El Gerente o Coordinador de Oficina debe solicitar creación, bloqueo o cambio de contraseñas al área de Tecnología.
- Si un cliente presenta alteración en la huella registrada, deberá actualizar su documento ante la Registraduría.
- A los codeudores no se les realiza validación en el aplicativo; el proceso aplica únicamente a titulares.
- Antes de iniciar el procedimiento, el asesor debe verificar que los dispositivos funcionen correctamente.
- Si hay fallas en los dispositivos, debe reportarse al Analista de Tecnología y al Analista de Seguridad Bancaria.
- El Coordinador de Oficina puede actuar como respaldo en oficinas con un solo asesor comercial interno.
- La validación documental se realiza cada vez que un cliente solicite un producto, incluso si ya tiene uno vigente.
- No se valida la contraseña de documento en trámite, porque no se considera documento de identidad válido para autenticación.
- En casos de dermatitis o huella ilegible, se pueden aplicar excepciones por conocimiento del cliente certificado por el Gerente de la Oficina.

### 3. Actividades en Oficinas

#### 3.1 Radicación de un caso

- Ingresar a la aplicación con usuario y contraseña.
- Seleccionar el tipo de documento.
- Digitar y confirmar el número de identificación del cliente.
- Capturar o adjuntar imágenes de los documentos. Para casos asociados a CC, CE, o TI debe capturar: Cara Anterior del documento de Identidad, Cara Posterior del documento de Identidad, Tarjeta de Huellas y Firma.
- Para el formato nuevo plastificado de **cédula digital**, el documento debe ser validado en original y por ambas caras.
  - Este proceso permite realizar la autenticidad del documento con sus estructuras técnicas avaladas por la Registraduría.
  - La calificación resultante es: **DOCUMENTO AUTÉNTICO SIN COTEJO – CÉDULA DIGITAL**.
  - Esta calificación permite al funcionario continuar con el proceso de enrolamiento y vinculación del cliente en oficina.
  - Esta validación está sujeta a la condición del nuevo documento, debido a que la Registraduría no ha revelado, por razones de seguridad, la información relacionada con los códigos QR ni con la verificación biométrica del rostro impresa en el documento.
- Seleccionar la oficina.
- Ingresar observaciones si aplica.
- Enviar el caso y esperar el resultado.

#### 3.2 Consulta de un caso

- Ingresar al sistema.
- Seleccionar la opción "Buscar caso".
- Elegir el parámetro de búsqueda.
- Consultar la información del caso: Número de Caso, imágenes de Cara Anterior y Posterior, Nombre del cliente, Número de Identificación, Oficina, Fecha de radicación, Fecha de evaluación, Nombre del Usuario que radicó el caso.

#### Biometría durante el enrolamiento

- **Huella:** el cliente debe colocar uno de los dedos recomendados (índice, corazón o pulgar) en el lector biométrico tres veces consecutivas. Si la huella no es útil, permite repetir la captura o continuar omitiéndola.
- **Rostro:** el cliente debe mirar la cámara a aproximadamente 20 cm de distancia y girar lentamente la cabeza hacia los lados. Si la imagen no es útil, se puede repetir o continuar sin ella.
- **Iris:** el cliente debe mirar el lector biométrico a unos 5 cm de distancia hasta que el dispositivo indique la captura. Si la imagen del iris no es útil, la aplicación permite repetirla o continuar sin ella.

#### 3.4 Imprimir o guardar resultados

Imprimir o guardar en PDF los resultados del proceso si es necesario.

### 4. Enrolamiento de un cliente nuevo

- Ejecutar el flujo inicial del caso.
- Capturar biometría del cliente.
- Registrar huella, rostro o iris según corresponda.
- Seleccionar oficina y agregar observaciones.
- Finalizar el enrolamiento y esperar el resultado.

### 5. Enrolamiento de cliente preexistente

Permite registrar biometría a un cliente que ya tenga casos previos en la aplicación con resultado "Sin problema".

### 6. Verificación automática de identidad

- Compara la biometría capturada con la almacenada previamente en el sistema.
- Si coincide, muestra los datos del cliente y genera comprobante.
- Si no coincide, notifica al usuario.
- El caso debe recibir calificación **"Sin problema"** para que el cliente pueda ser identificado automáticamente en el futuro.
- Los resultados pueden imprimirse o guardarse en PDF desde la aplicación.

### 7. Impresión o guardado de resultados

Permite imprimir o guardar en PDF los resultados del proceso.

---

## Vinculación de clientes persona natural

- Solicitar y validar documentos requeridos según la lista de chequeo.
- Verificar que los documentos estén completos, firmados y cargados en HIT.
- En casos de cédula digital o contraseña digital, seguir el instructivo de validación correspondiente.
- Confirmar que los sistemas BankVision, Suite Financiera y Who is Who estén operativos.
- Si hay inconsistencias en la información, solicitar correcciones antes de continuar.
- Realizar consulta en listas restrictivas en Vigía y adjuntar evidencia en HIT.
- Si se genera alerta en listas restrictivas, tramitar verificación con SARLAFT.
- Validar la identidad del cliente en Who is Who y guardar el soporte.
- Diligenciar el formato de vinculación de persona natural y crear el cliente en HIT.
- Si el cliente es PEP, FATCA o CRS, completar los anexos o campos especiales.
- Cargar todos los soportes documentales en HIT.
- Verificar que los datos del formulario, productos y validaciones estén correctos.
- Finalizar la vinculación con la apertura efectiva del producto.

**Formatos y documentos asociados:**

- **CF-CLI-FOR-005** – Solicitud Única de Vinculación y Actualización de Productos Persona Natural (DocManager)

**Formatos / anexos especiales:**

- **Declaración FATCA** (anexo en CF-CLI-FOR-005)
- **Formato PEP / Origen de fondos** (anexo en CF-CLI-FOR-005)
- **CRS** (anexo en CF-CLI-FOR-005)

---

## Vinculación de clientes persona jurídica

- Solicitar y validar documentos requeridos para la empresa.
- Registrar o actualizar en **Suite Financiera** los datos de la persona jurídica: razón social, NIT, dirección, celular, representante legal, fecha de constitución.
- Verificar que la información del sistema coincida con los formularios y anexos entregados.
- Validar que se incluya el **formulario de beneficiario final o diagrama corporativo**.
- Si la empresa ya existe en el sistema, actualizar la información y tratar el análisis como nuevo.
- Exigir que el formulario sea firmado digitalmente por el **representante legal**.
- Realizar la consulta en listas restrictivas desde **Suite Financiera**.
- Diligenciar el formulario de vinculación de persona jurídica.
- Entregar y diligenciar anexos especiales si aplica: FATCA, compra de cartera, PEP / origen de fondos.
- Verificar que el formulario y documentos cumplan la lista de chequeo **CF-CAT-FOR-002**.
- Validar la identidad del representante legal en **Who is Who**.
- Crear el cliente en **Suite Financiera / BankVision**.
- Confirmar que la información quede registrada y los soportes cargados en **HIT**.
- Si el cliente no queda creado correctamente en el sistema, reportar por correo a **Banca Electrónica / Operaciones**.
- Finalizar la vinculación con la **apertura efectiva del producto**.

**Formatos y documentos asociados:**

- **CF-CLI-FOR-014** – Solicitud de Vinculación y de Productos Persona Jurídica (DocManager)

**Formatos / anexos especiales:**

- Formulario de declaración de beneficiario final o diagrama corporativo
- **Declaración FATCA** (anexo en CF-CLI-FOR-005)
- **Anexo Compra de Cartera** (anexo en CF-CLI-FOR-005)
- **Formato PEP / Origen de fondos** (anexo en CF-CLI-FOR-005)

---

## CAPÍTULO 2: AHORRO PROGRAMADO

Definir con el cliente la forma de pago del ahorro programado, la cual podrá realizarse por: Nómina, Caja o Débito Automático.

> **Nota:** En caso de que el cliente elija la modalidad de ahorro por nómina, se deberá diligenciar el formato **CF-CAT-FOR-010** AUTORIZACIÓN DESCUENTO AHORRO PROGRAMADO V1.1 y adicionalmente realizar la validación de la capacidad de pago mediante el simulador de ahorro programado **CF-CAT-FOR-011**, para lo cual se deben contar con los dos últimos desprendibles de nómina.
>
> La validación solo se realizará sobre desprendibles que incluyan liquidación de prestaciones correspondientes a los últimos 30 días.

### Formatos identificados en el procedimiento

| Formato | Descripción |
|---|---|
| **CF-CAT-FOR-010** | Autorización descuento ahorro programado (DocManager) |
| **CF-CAT-FOR-011** | Simulador de ahorro programado (DocManager) |
| **CF-CLI-FOR-005** | Solicitud única de vinculación y actualización de productos persona natural (DocManager) |
| **CF-CAT-FOR-002** | Lista de chequeo producto captaciones (DocManager) |
| **CF-CAT-FOR-001** | Ahorro contractual (DocManager) |
| **CF-CAT-FOR-014** | Ahorro contractual rito (DocManager) |

### Creación del cliente y del producto

- Realizar la creación del cliente en el aplicativo **HIT**.
- Ingresar (para Ahorro plan Rito) la cédula del tutor; este debe estar creado en HIT con la documentación establecida para clientes.

> **Nota:** Si no se tiene la información del tutor, no es posible realizar la creación del ahorro Rito.

- Realizar la creación del producto en el aplicativo **Suite Financiera**.
- Verificar diariamente la información de Ahorros Programados en el aplicativo Core BankVision y Suite Financiera, validando la correcta creación del producto.
- Corregir inconsistencias y verificar los datos de la creación del Ahorro:
  - **Forma de pago:** Solo aplica cambio de caja a Nómina – enviar Teams a Captaciones.
  - **Pagaduría:** Cambio a otra pagaduría – enviar correo a pagadurias@juriscoop.com.co.
  - **Débito automático:** Cambio de cuenta vista para débito automático.

### Paso a paso – Flujo del ahorro programado

#### 1. Venta y validación inicial

Se ofrece el producto al cliente explicando características, beneficios y costos. Antes de la creación, se debe:

- Consultar **listas restrictivas**.
- Realizar validación de identidad / **Who is Who**.
- Definir la **forma de pago**: nómina, caja o débito automático.

> **Control SARLAFT:** si en la consulta de listas restrictivas aparece una alerta, la validación debe escalarse al área correspondiente antes de continuar.

#### 2. Requisitos para creación

- Si el pago es por **nómina**: se diligencia la autorización de descuento y se valida la **capacidad de pago** con soportes de nómina recientes.
- Se diligencia el formulario de vinculación.
- Se revisa que el formulario y los documentos estén completos; si hay errores, se devuelve para corrección.

#### 3. Creación del cliente y del producto

- Se crea el cliente en **HIT**.
- Luego se crea el producto en **Suite Financiera**.
- Se valida que el ahorro haya quedado correctamente creado en los sistemas (Core / BankVision / Suite Financiera).
- Si hay inconsistencias, se corrigen según el tipo de novedad: forma de pago, pagaduría, débito automático.

#### 4. Gestión documental y visación

- Si el ahorro es por nómina y la pagaduría lo exige, se envía la documentación para **visación**.
- Se descarga el contrato/formato generado por el sistema y se completa con el número del producto.
- El original se entrega al cliente y la copia queda con los documentos internos.

#### 5. Administración del ahorro programado

- Se controlan las novedades según cronogramas de pagaduría.
- Se validan datos clave del ahorro: número del producto, cuota, mes, pagaduría, visación.
- Si hay inconsistencias, se solicitan ajustes o correcciones.
- También se revisan diariamente: condiciones del producto, data contable, mantenimientos solicitados por oficina.

#### 6. Gestión de vencimientos y cancelación

- Se revisan productos próximos a vencer y se contacta al cliente para definir la gestión.
- La cancelación puede hacerse al vencimiento normal o en cualquier oficina, con validaciones y visación cuando aplique.
- Solo se puede cancelar anticipadamente con soporte de **calamidad doméstica**, **compra de vivienda**, o **autorización del Gerente de Oficina**.

#### 7. Validaciones para cancelar

- Se valida: identidad del cliente, contrato, estado y vencimiento del producto, saldo y cuotas en los sistemas.
- Si no hay contrato original, se aplica proceso de validación alterno (**Who is Who**).

#### 8. Modalidades de cancelación

**Cancelación por caja:**

- Se registra la operación en Solución de Oficina.
- El pago puede hacerse en: efectivo, cheque, cuenta de ahorro vista, o aplicación a crédito.
- Luego se firma el soporte y se archivan los documentos.

**Cancelación por ACH:**

- Se valida saldo y vencimiento.
- Se envía la solicitud por Teams.
- Captaciones revisa soportes y saldo.
- Backoffice ejecuta la cancelación y transferencia.
- Si hay novedades, se devuelve la solicitud para corrección.

> **Notas:**
> - El pago por ACH se hace únicamente a la cuenta del titular del Ahorro.
> - El cobro de comisión por traslado ACH tendrá un costo de $10.000.

---

## CAPÍTULO 3: AHORRO VISTA – CUENTA DE AHORROS

### Definiciones

- **Ahorro vista / Cuenta de Ahorros:** Producto de ahorro con opción de disponer de los recursos en cualquier momento por medio de una tarjeta débito.
- **Gestor Comercial:** Todo funcionario que realice la venta de un producto o servicio.
- **GMF:** Gravamen a los movimientos financieros, impuesto nacional instantáneo que se causa por la disposición de recursos.
- **Tarjeta de Registro de Firmas:** Documento donde el cliente registra las condiciones de manejo de la cuenta. Aplica solo para persona jurídica.

### Paso a paso – Apertura Cuenta de Ahorros

1. Ofrecer el producto al cliente (características, beneficios y costos).
2. Definir con el cliente las condiciones variables del producto.
3. Solicitar la información para diligenciar el formulario:
   - **Persona Natural:** CF-CLI-FOR-005 "Solicitud Única de Vinculación y Actualización de Productos Persona Natural".
   - **Persona Jurídica:** CF-CLI-FOR-014 "Solicitud de Vinculación y de Productos Persona Jurídica".
4. Recibir carta de autorización de apertura de cuenta por el empleador (cuando la cuenta es de nómina).
5. Solicitar el diligenciamiento de **CF-CLI-FOR-004** "Tarjeta de Registro de Firmas" (solo para persona jurídica).
6. Solicitar documento de identificación y realizar validación de identidad mediante **Who is Who**.
   - Si es cliente antiguo: verificar en HIT y validar en Vigía.
   - Si es cliente nuevo: crear en HIT.
   - En caso de alertas en Vigía: tramitar por flujo "Alertas listas vinculantes".
7. Digitalizar documentos del cliente y cargar en HIT.
8. Realizar el procedimiento de vinculación (CF-CLI-PRO-002 "Vinculación").
9. Realizar la creación del producto en el sistema (Guía del Sistema Módulo Cuenta de Ahorros BankVision).
10. Validar que la cuenta se haya creado con el plan correspondiente. Si fue creada erróneamente, solicitar modificación por flujo Teams: Captaciones > Cuenta de ahorro > Cambio de Plan.
11. Si el cliente desea marcar la cuenta para excepción del GMF, seguir el procedimiento CF-OPE-PRO-047.
12. Digitalizar la tarjeta de registro de firmas en HIT (solo para persona jurídica).
13. Realizar el procedimiento de emisión en línea de la tarjeta débito CF-CAP-PRO-043 (persona natural).
14. Entregar al cliente una certificación con el número de la cuenta de ahorros y solicitarle llevarla al empleador (cuenta de nómina).
15. Dirigir al cliente al área de caja para el depósito inicial (cuenta que no es de nómina).
16. Custodiar la tarjeta de firmas en el archivo establecido (solo para persona jurídica).

### Paso a paso – Activación de la Cuenta de Ahorros

1. Solicitar el documento de identificación y realizar validación de identidad mediante **Who is Who**.
2. Verificar si el cliente presenta más de 12 meses sin actualizar datos; si es así, debe diligenciar el formato CF-CLI-FOR-005.
3. Solicitar al cliente diligenciar el formato **CF-CAT-FOR-006** "Solicitud Activación de Cuenta".
4. Visar la firma y huella registrada con la tarjeta de firmas digitalizada en HIT (solo para persona jurídica).
5. Dirigir al cliente al área de caja para que realice la consignación o retiro.

### Paso a paso – Cancelación de la Cuenta de Ahorros

1. Recibir la solicitud del titular.
2. Solicitar documento de identificación y realizar validación de identidad mediante **Who is Who**.
3. Recibir la carta del titular solicitando la cancelación de la cuenta.
4. Visar la firma y huella registrada en la carta con la tarjeta de firmas digitalizada en HIT (solo para persona jurídica).
5. Si el titular es persona natural: solicitar la tarjeta débito y realizar el procedimiento de cancelación según CF-OPR-INS-1025.
6. Destruir el plástico de la tarjeta débito en presencia del titular.
7. Tomar la tarjeta de firmas en custodia de la oficina y colocar el sello de cancelado.
8. Entregar los documentos soporte de la transacción a cajer@.
9. Realizar la cancelación del producto en el sistema.
10. Entregar la tirilla generada al cliente, solicitar validar los datos y registrar la firma.
11. Archivar los documentos soporte en el movimiento de caja.

### Paso a paso – Débitos manuales a Cuentas de Ahorros

1. Recibir la solicitud del cliente (verbal, física o por correo).
2. Confirmar que el solicitante es titular de la cuenta.
3. Solicitar documento de identidad original.
4. Verificar identidad del titular.
5. Validar que la cuenta tenga fondos disponibles en el sistema (BankVision).
6. Solicitar diligenciamiento del formato **CF-CAT-FOR-015** – Autorización de Retiros Eventuales (debe tener firma y huella, o carta firmada por el cliente).
7. Verificar que los datos del formato estén completos y correctos.
8. Validar firma del cliente contra el registro en sistema (Media Storage).
9. Colocar visto bueno y digitalizar el formato diligenciado.
10. Enviar la solicitud por correo o flujo (Power Automate) al área correspondiente.

---

## CAPÍTULO 4: CDT

Financiera Juriscoop ofrece dos tipos de CDT:

- **CDT Físico:** Se emite como un documento en papel. El cliente recibe un certificado impreso que respalda su inversión.
- **CDT Desmaterializado:** Se emite digitalmente, más seguro y ágil.

### Documentos requeridos para apertura de un CDT físico

- CF-CLI-FOR-005 → Vinculación persona natural
- CF-CLI-INS-007 → Vinculación persona jurídica (si aplica)
- CF-CAT-FOR-002 → Lista de chequeo captaciones
- CF-RIE-FOR-001 → Obligatorio si el monto ≥ $10.000.000
- Proforma CDT → Formato de impresión del título

### Aplicativos utilizados en el proceso de la creación de un CDT

| Aplicativo | Uso |
|---|---|
| HIT | Creación y actualización de clientes |
| Vigía | Validación de listas restrictivas |
| Who is Who | Validación de identidad |
| BankVision Core | Sistema central financiero |
| Solución de Oficina | Operación del CDT |
| Microsoft Teams | Autorizaciones y flujos |

### Consideraciones generales para CDTs

- **Estado CDT:** Estado 1 = Cuenta Nueva, Estado 2 = Vigente, Estado 3 = Período de Gracia, Estado 4 = Cancelado, Estado 6 = Anulado.
- Todas las modificaciones de condiciones variables deben realizarse el mismo día de su creación (Estado 1); de lo contrario, se requiere autorización de la coordinación de captaciones.
- Cuando el Gestor comercial solicita cambio de sucursal del CDT, la copia debe reposar en el archivo de la nueva oficina dueña del título.
- Para ningún CDT se genera cobro de GMF al cliente; este será asumido por Financiera Juriscoop.
- Por ningún motivo un CDT debe tener tachones o enmendaduras.
- Todo CDT por constituir en cheque deberá ser impreso sin registrar firmas, protectógrafo y sellos, y será custodiado por la oficina en la bóveda hasta el momento de la liberación del canje.
- Cuando el valor del cheque sea mayor al valor del CDT a constituir, este solo se podrá recibir si el cliente tiene cuenta de ahorros en Financiera Juriscoop o solicita la apertura de una.
- Todo CDT renovado automáticamente conservará las condiciones iniciales de apertura, exceptuando la tasa, la cual se verá sujeta a la tasa vigente según su plazo.
- Para el pago de intereses y/o cancelación del CDT por un tercero se debe realizar Who is Who.
- Para el endoso de CDT se requiere que estén presentes el endosante y endosatario en la oficina.
- En caso de ausencia del Gerente o Coordinador de Oficina se debe tramitar la autorización de firmas de CDT a través del aplicativo TEAMS.

### Paso a paso – Apertura de un CDT

#### Paso 1: Validación del cliente

Solicitar documento de identidad, validar identidad mediante Who is Who, HIT (si ya es cliente) y Vigía. Si hay alguna alerta en las listas restrictivas, radicar mediante Teams el flujo llamado **"Alertas SARLAFT"** para recibir el visto bueno de la Unidad de Cumplimiento.

#### Paso 2: Vinculación o actualización del cliente

- **Si es cliente nuevo:** Crear registro en sistema HIT.
- **Si es cliente antiguo:** Validar y actualizar datos si es necesario.
- Recopilar documentación con formulario: CF-CLI-FOR-005 (persona natural) o CF-CLI-INS-007 (persona jurídica).
- Verificar documentos usando el formato: CF-CAT-FOR-002 Lista de Chequeo Producto Captaciones.

#### Paso 3: Digitalización de documentos

Digitalizar todos los documentos del cliente y cargar en el sistema HIT.

#### Paso 4: Creación del CDT en sistema

- Ingresar al sistema Solución de Oficina.
- Registrar el CDT: tipo de apertura, tasa, plazo, monto, fecha.
- Confirmar los datos con el cliente.
- Generar el comprobante (Batch de la transacción).

#### Paso 5: Validación del CDT

Validar en BankVision Core que las condiciones coincidan con lo pactado. Si se presenta error, solicitar modificación o anulación.

#### Paso 6: Autorización de tasa (si aplica)

- Solicitar autorización en Teams.
- Esperar aprobación del responsable.
- Registrar tasa aprobada en el sistema.

#### Paso 7: Recepción del dinero

- **Efectivo →** contar y validar.
- **Cheque →** verificar condiciones y canje.
- **Transferencia →** confirmar en operaciones.
- Si el monto ≥ $10.000.000: diligenciar CF-RIE-FOR-001.

#### Paso 8: Registro de la transacción en caja

- Registrar la operación en Solución de Oficina usando el Batch.
- Generar e imprimir el comprobante de transacción.
- Validar información con el cliente.

#### Paso 9: Impresión del CDT

- Imprimir el título en el sistema usando la Proforma CDT.
- Aplicar sello, protectógrafo y controles establecidos.

#### Paso 10: Entrega CDT

- Recibir título físico del cajero.
- Validar que coincida con condiciones pactadas. Si presenta errores → realizar anulación del CDT.
- Gestionar firmas autorizadas y validar sellos.
  - **$100.000–$49.990.000:** se necesita firma del Coordinador de oficina y firma de funcionario autorizado.
  - **$50.000.000 o más:** se necesita firma del Coordinador de oficina y firma del Gerente de oficina. Si no está el Gerente o Coordinador, solicitar autorización de firma a través de Teams: canal novedades usuarios > Opción CDT > Opción autorización firma.
- Verificar legalidad: firmas, sello y protectógrafo.
- Solicitar firma y cédula del titular en copia y entregar original.
- Archivar copia del CDT en carpeta para custodia en bóveda o lugar seguro.
- Si el titular no se encuentra en la oficina: aplicar entrega a tercero. Requiere carta de autorización, poder autenticado y cédula del tercero. No se permite custodia de títulos en la entidad.

### 11. Entrega del CDT a un tercero

1. Recibir la carta de autorización del titular, poder autenticado y documento de cédula del tercero.
2. Entregar el título original al tercero.
3. Anexar y archivar la carta de autorización a la copia del título y guardarla en la carpeta destinada para custodia de copias de CDT.

### 12. Entrega del CDT a funcionario de la Oficina

1. Diligenciar el formato **CF-CAT-FOR-005** "Entrega de Títulos a Clientes".
2. Entregar el CDT original al titular y solicitar que firme la copia del título en el reverso y el formato CF-CAT-FOR-005.
3. Recibir y validar diariamente el formato CF-CAT-FOR-005 y copia del CDT firmados, y realizar confirmación telefónica con el titular sobre el recibo de conformidad.
4. Anexar y archivar el formato a la copia del título.

### 13. Pago de interés del CDT

1. Recibir la solicitud verbal del titular.
2. Solicitar documento de identificación con el título original y realizar Who is Who.
3. Validar los intereses exigibles del título en BankVision Core.
4. Realizar la liquidación de los intereses en Solución de Oficina: Transacciones > Depósitos a término > Pago rendimientos financieros.
5. Imprimir el comprobante de Liquidación de Intereses y hacerlo firmar por el Cliente.
6. Entregar al cajero el comprobante de la transacción.

### Paso a paso – Reinversión CDT

1. Validar diariamente en SharePoint – Tablero Ciencia de datos el reporte "CDT´S por vencer" y confirmar con el titular la reinversión del título.
2. Solicitar al cliente el título original y el documento de identificación.
3. Verificar que el título se encuentre en su fecha de vencimiento o dentro del período de gracia.
4. Validar en BankVision Core si se requiere excepción de retención en la fuente.
5. Definir con el cliente las nuevas condiciones variables del producto (fechas, plazo, monto, capitalización de intereses).
6. Tomar la copia del título en custodia y validar los datos con el título original.
7. Realizar la reinversión en Solución de Oficina: Transacciones > Depósitos a término > Reinversión título.
8. Validar en BankVision que el título se haya renovado con las mismas condiciones pactadas.
9. Colocar el sello de cancelado en el título reinvertido y en la copia.
10. Imprimir el título y gestionar entrega al titular.

### Paso a paso – Reinversión CDT en otra oficina

1. Realizar el paso a paso de reinversión de CDT.
2. Digitalizar y enviar el título al correo del Coordinador de la Oficina Origen, solicitando la visación.
3. Validar los datos con el título original enviado.
4. Responder el correo confirmando la visación realizada.
5. Imprimir y entregar al cajero el comprobante de la transacción.
6. Realizar entrega del CDT (a tercero o a funcionario de la oficina).
7. Enviar la copia de CDT a la oficina origen por mensajería interna.

### Paso a paso – Cancelación CDT

1. Recibir la solicitud verbal del cliente.
2. **Persona Natural:** solicitar título original, documento de identificación y realizar Who is Who.
3. **Persona Jurídica:** solicitar título original, documentos de identificación, carta firmada por el representante legal (no mayor a 30 días). Si han transcurrido 6 meses, realizar actualización en HIT y Who is Who.
4. Verificar que el título se encuentre en su fecha de vencimiento o dentro del período de gracia.
5. Realizar la cancelación en Solución de Oficina: Transacciones > Depósitos a término > Cancelación CDT.
6. Colocar el sello de cancelado en el título físico original y la copia.
7. Entregar al cajero: título original, copia y comprobante de la transacción.
8. Realizar la transacción en Solución de Oficina: Transacciones > Depósitos a término > Seleccionar tipo de Cancelación (Efectivo, Cheque o abono a cuenta de ahorro CDT).

> **Nota:** Para persona jurídica, los recursos deben pagarse en cheque a nombre de la empresa.

### Paso a paso – Cancelación CDT en otra oficina

1. Realizar el paso a paso de Cancelación de CDT.
2. Digitalizar y enviar el título al correo del Coordinador de la Oficina Origen, solicitando la visación.
3. Responder el correo confirmando la visación; en caso de diferencias, informar al Gerente de Oficina.
4. Realizar la cancelación del título y entregar los soportes.
5. Imprimir correo de solicitud de cancelación y adjuntarlo con la copia del título con sello de cancelado.
6. Realizar seguimiento al envío del título físico con sello de anulado desde la oficina donde se canceló.

---

## Apertura CDT Desmaterializado

1. Solicitar el documento de identificación y realizar validación mediante Who is Who.
2. Digitalizar los documentos del cliente y cargar en HIT.
3. Crear en Solución de Oficina: Transacciones > CDT Desmaterializado > Apertura Título Desmaterializado.
4. Validar diariamente que en la carpeta compartida se encuentre la constancia Deceval y que los datos contenidos (Nombre del Titular, Identificación, Fecha Apertura, Valor, Tasa y Plazo) estén correctos.

### Pago de Intereses CDT Desmaterializado

1. Recibir la solicitud verbal del titular.
2. Solicitar documento de identificación.
3. Validar los intereses exigibles del título en BankVision Core.
4. Verificar el archivo de vencimientos enviado los viernes por tesorería.
5. Realizar la liquidación de los intereses en Solución de Oficina: Transacciones > Depósitos a término > Pago rendimientos financieros.
6. Imprimir el comprobante de Liquidación de Intereses y hacerlo firmar por el Cliente.
7. Entregar al cajero el comprobante de la transacción.

### Reinversión CDT Desmaterializado

1. Revisar vencimientos próximos (reporte CDT por vencer).
2. Contactar al cliente y confirmar intención de reinversión.
3. Solicitar documento de identidad.
4. Verificar estado del CDT (vencido, gracia o renovado automáticamente).
5. Explicar condiciones al cliente (si aplica cambio o renovación automática).
6. Definir nuevas condiciones: plazo, tasa, monto, capitalización o retiro de intereses.
7. Registrar reinversión en el sistema.
8. Actualizar datos del cliente si aplica.
9. Esperar y validar constancia de depósito Deceval.

### Cancelación de CDT Desmaterializado

1. Recibir solicitud de cancelación del cliente.
2. Solicitar documento de identidad.
3. Verificar condiciones del CDT: vencimiento, período de gracia, renovación automática.
4. Informar condiciones al cliente si no está vencido.
5. Validar diferencias en intereses vs reportes; notificar inconsistencias a captaciones si aplica.
6. Ejecutar cancelación en el sistema.
7. Colocar el sello de cancelado en la Constancia de Depósito Deceval que reposa en la oficina.
8. Generar e imprimir comprobante.
9. Entregar comprobante a caja para pago.

### Cancelación CDT Desmaterializado en otra oficina

1. Validar datos del CDT con oficina origen.
2. Confirmar autorización de cancelación.
3. Ejecutar cancelación siguiendo el flujo estándar.
4. Gestionar soportes y envío documental interno.

---

## Endoso CDT

1. Solicitar al endosante el título original.
2. Verificar diariamente que el título esté endosado (firmado) al reverso por el endosante, visando las firmas con la copia en custodia.
3. Solicitar al endosatario diligenciar los datos y firmar en el reverso del título original, al lado de la firma del endosante.
4. Solicitar al endosatario diligenciar el Formulario de Vinculación o actualización de datos y demás documentos CF-CAT-FOR-002.
5. Verificar el correcto diligenciamiento de los documentos de la Lista de Chequeo.
6. Entregar al Coordinador de Oficina el título original y la copia.
7. Colocar el visto bueno al lado del endoso en el título original.

---

## Proceso Canales Externos

### Apertura de CDT por canal externo

- Las aperturas por canales externos – free lance aplican las mismas condiciones que las aperturas en oficinas.
- La Dirección de Banca Seguros y Canales Externos coordina las instrucciones para las aperturas.
- Se debe indicar el código de oficina donde deben quedar ingresados los certificados (código 30065 con el respectivo código de gestor).
- La tesorería y BackOffice validan diariamente los recursos informados para la apertura de los certificados.

### Cancelación de CDT por canal externo

- Las cancelaciones por canales externos aplican las mismas condiciones que las cancelaciones en oficinas.
- La Dirección de Banca Seguros y Canales Externos coordina las instrucciones.
- La tesorería y BackOffice validan diariamente los recursos a pagar informados.

### Reinversión de CDT por canales externos

- Las reinversiones por canales externos aplican las mismas condiciones que las reinversiones en oficinas.
- Se debe indicar el código de oficina (código 30065 con el respectivo código de gestor).
- La Dirección de Banca Seguros y Canales Externos debe indicar las condiciones de reinversión: plazos, montos y nuevos valores.

---

## CDT DIGITAL

### Apertura de CDT Digital

- Dirigir y ofrecer al cliente la apertura del Certificado de manera digital en: https://www.financierajuriscoop.com.co/personas/portafolio/ahorro-e-inversion/cdt
- La apertura del CDT digital es autogestionada por el inversionista desde el portal transaccional o app.
- El inversionista ingresa al simulador, valida el resultado, diligencia sus datos y acepta los términos y condiciones.
- El inversionista ingresa el código OTP enviado a su celular o correo electrónico registrado.
- Formas de pago habilitadas: PSE o Tarjeta de crédito (monto mayor a $500.000).
- Al descargar el reporte de la operación, este debe quedar en estado "exitoso core" para confirmar que el certificado quedó creado en el sistema.
- Después del pago, la oficina contacta al inversionista para hacerle llegar la constancia del certificado (ingresa como desmaterializado, en un promedio de dos a tres días hábiles).
