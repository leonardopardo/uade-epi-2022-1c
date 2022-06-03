# Flujo de Fondos

## Introducción
El flujo de fondos (Cash Flow) representa los movimientos de caja, ingresos y egresos de fondos en el tiempo

**Componentes Relevantes**
- inversiones
- costos
- fuente financiera
- ingresos

**Información Pertinente**
- mercados
- política
- industria
- riesgos del negocio

> `Mejor información -> Mayor certidumbre`
___

## Construcción de un flujo de fondos

### Elementos relevantes o fundamentales de todo proyecto de inversión
- **Inversión**: una inversión es la afectación de recursos a un proyecto determinado, con la esperanza de obtener un beneficio en el futuro.
- **Flujo de Fondos**: Está conformado por todos los parámetros y variables relevantes para un proyecto. Representa una estimación económica del movimiento de efectivo que generará un proyecto a lo largo de su vida.
- **Factor temporal**: Este factor es incorporado al análisis mediante la utilización de una tasa de interés.

### Tareas de la construcción del flujo de fondos
1. **Identificar** el proyecto y sus impactos relevantes
2. **Medir** magnitud y signo de los impactos en sus métricas
3. **Valuar** asignar un valor monetario a los impactos
4. **Ordenar** horizonte temporal (vida) período (+corto+exactitud)
5. Análisis Financiero
___

## Plan de Inversión - Proyecto Nuevo o Adición/Incremental

### Nuevo Emprendimiento
Considera todos los egresos e ingresos

### Empresa Existente
Se debe construir sobre una base incremental, de modo que solo se analice el impacto financiero del proyecto

**Flujo Incremental**  
Es la comparación de los Flujos de Efectivo de la empcresa **con** y **sin** proyecto  
- Identifificar los beneficios y costos asociados únicamente al proyecto
- Definir el escenario "sin proyecto" en una situación optimizada. Será la base para medir los costos y beneficicos incrementales
- El "antes del proyecto" no es la base apropiada

**Fechas / Períodos**  
- Los ingresos y egresos del proyecto acurren al final de cada período
- Las inversiones iniciales se colocan en el momento 0

**Los diferentes activos**
- **Bienes de Uso**: recursos involucrados necesarios para la ejecución del proyecto. Usualmente incluyen hardware, software de base, software de aplicación, consultoría de implementación, que generan los beneficios en el tiempo.
  - **Valor residual de los activos**: Valor al final de la vida útil del proyecto, en IT suele ser nulo, su valor de reventa.
- **Activos Intangibles**: son inmateriales. Son los servicios o derechos necesarios para implementar el proyecto
  - Ejemplos:
    - Gastos de Organización del Proyecto
    - Gastod de puesta en marcha
    - Sistemas de inforamción preoperativos
  - Aquí se utiliza la **"amortizacion de intangibles"**, dividiendo su impacto en los períodos de vida del proyecto.


> **Programa de Inversión**  
> Formular una programación de las inversiones, contemplar las actividades y formas de pago. El conocimiento del proyectista ayuda con las estimaciones acertar

___

## Depreciaciones y Amortizaciones
**Depreciación**
Asignación sistemática del costo por el uso o demérito del activo fijo (bienes de uso) a lo largo de su vida depreciable. Para bienes intangibles el concepto análogo es el de "Amortización". 
Vamos a tratarlos indistintamente a ambos como **Amortizaciones**

**Método de Amortización**
- Línea Recta
- Acelerada
- Suma de Digitos de Años
- Saldos Decrecientes
- Deducción Inmediata

> **Reparaciones y adaptaciones** se consideran inversiones siempre que impliquen adiciones o mejoras al activo fijo. Los gastos de mantenimiento no, no es una inversión, ya que su objetivo es mantener las condiciones de operación.

### **Sistema de amortización lineal**
Amortización constante en el tiempo

> **I0:** Inversión Inicial  
> **Vr:** Valor Residual  
> **Vu:** Vida útil  

$$ a = \frac{I_0 - V_r}{V_u} $$

> Las amortizaciones son costos que no implican salida de efectivo

**Efecto escudo impositivo**
La amortización es un costo deducible de impuestos, pero no es un flujo de caja, esto escuda en dicho importe para no ser alcanzado por el impuesto a las gananacias, creando un "ingreso de caja" igual al ahorro impositivo

___

## Capital de Trabajo
Es una **Inversión** que sirve para financiar los desfases entre la generación de **Ingresos** y la ocurrencia de los **Egresos**. 
Estos desfases pueden ser:
- La necesidad de adquirir previamente y mantener un volúmne de materias primas, proudctos en proceso, repuestos, mercadería, para poder responder a nuestros Clientes.
- El tiempo entre el momento de entrega y la cobranza
- El tiempo entre la compra y el pago a proveedores
- Las obligaciones tributarias mensuales (IVA, Anticipo de IIGG)

> ES UNA INVERSIÓN A LARGO PLAZO, necesario para la operación del proyecto.

Se puede componer de:
- **ACTIVOS**:
  - Caja Operativa
  - Deudores por Ventas
  - Inventarios
- **PASIVOS**:
  - Proveedores

Formas de cálculo
- **Contable**
  - Activo Corriente - Pasivo Corriente
- **Período de desfase**
  - Cuanto se tarda desde nuestro pago a proveedores hasta el cobro al cliente
- **Déficit Acumulado Máximo**

___

## Plan Operativo (consideraciones contables)
**Cuadro de resultado proyectado**

$$ [UtilidadBruta] = [IngresosPorVenta] - [GastosPorCompra] $$

**Balance Proyectado**  
Situación financiera al final de un período

___

## Costos de Oportunidad y Costos Hundidos
Un bien o facto de producción podría tener otros usos. El **Costo de Oportunidad** es el valor de la mejor alternativa que se desecha, quedando el valor marginal que se obtiene por encima de este, como impulso en la toma de decisiones.
Las decisiones pueden ser:
- Realizar una actividad adicional
- Atender un pedido especial
- Fabricar o comprar
- Abandono de una línea de producción o su reemplazo
- Selección de artículo a producir

Los costos de oportunidad surgen de la comparación de **sin proyecto** o **con proyecto**, Ejemplo:
- Hardware: tiene un valor de venta o evitamos su compra

### Costos Hundidos
- Común a todas las alternativas de inversión
- No son pertinentes
- No se toman en cuenta (no establecen diferencias al compararlas y han ocurrido antes de tomar la decisión)
- Si se tiene en cuenta el ahorro de impuesto por su amortización
- Costos históricos son gastos previos en activos y se toman sólo en su valor actual de mercado
- Costos inevitables (aún no ocurridos) como pagos futuros por activos ya adquiridos, o por un estudio de viabilidad aún no pagado.

### Costos / Beneficios : Intangibles / Externos
**Beneficios y Costos intangibles**  
Definirlos como intangibles es una última instancia, hay que tratar de valorar su efecto. La imposibilidad o inconveniencia de medirlos/valorarlos no significa que no se consideren (imagen, lealtad de clientes, etc.)
Deben valorarse conta el VAN: por ejemplo, un proyecto arroja un flujo de caja negativo. Sin embargo, la alta dirección aprueba su ejecución por sus beneficios estartégicos. La pregunta es, Cuánto valen esos beneficios?

**Los Costos y Beneficios Externos**  
Deben considerarse, por mas qeu no impacten sobre la rentabilidad del proyect. Pueden afecta a la empresa, corporación, subsidiarias, proveedores, clientes. Aquí también se pueden lograr apoyos al proyecto.

___

## Valor Terminal
**Cierre de Proyecto**  
El el último período (cierre) deben identificarse lso costos y beneficios específicos a ese cierre:
- Ingresos por venta de Bienes de Uso (valor de venta por si o como rezago)
- Tener en cuenta el tratamiento contable (valor residual no amortizable, ver si hay diferencia a favor o no con al venta)
- Ingreso por recupero del Capital de Trabajo (dejo de necesitar "caja" o los clientes completan sus deudas)
- Egresos por Costos de Cierre:
  - Indemnizaciones de la mano de obra
  - Costos de disposición de desechos
  - Costos de cierre propiamente dichos

**Continuidad**  
El proyecto continúa por muchos años o "eternamente", por lo que debe calcularse el valor de continuidad
- El valor de continuidad es el valor actual del flujo neto de todos los períodos posteriores al final del horizonte explícito.
- En el último período de evaluación se calcula el valor presente del flujo libre de caja a "perpetuidad"
  - Con Crecicimiento constante
  - Sin crecimiento

___

## Impuestos
### El impuesto al valor agregado - IVA
Es un gravamen al consumo, indirecto, general y no acumulativo

La posición de la empresa frente al IVA es la diferencia entre 2 movimientos
- IVA cobrado a los clientes -> IVA Débito
- IVA pagado a lso preveedores -> IVA Crédito

- El IVA graba todos los Ingresos y Egresos del Proyecto
- Existen tasas difrenciales por actividad y productos (10.5%, 21%, 27%)
- El crédito fiscal es acumulativo no indexable
- Las exportaciones tienen reintegros
- El "hecho imponible" es la compra o la venta 

### Para proyectos o Empresas
- Opción 1
  - Las ventas y las compras se computan con IVA. Se calcula la posición ante el IVA y si es deudora se resta.
- Opción 2
  - Las ventas y las compras se consideran netas de IVA
  
> No tendría efectos en el flujo de caja del proyecto, pero si, genera un efecto financiero desfavorable.

Tipicamente los proyectos requieren de importantes desembolsos de IVA por las inversiones iniciales (máquinas, equipos, alquileres, etc.).
Recupero de IVA en el horizonte del proyecto a través de la diferencia de IVA Ventas y el IVA Compras.

### Impuesto a las Ganancias
- El Impuesto a las gananacias grava el resultado contable neto del proyecto
- Se calcula sobre ejercicios fiscales
- Tasa 35%
- Forma de pago
  - Determinado el impuesto se paga el saldo
  - 10 anticipos mensuales a cuenta
- Pérdidas del Ejercicio Anterior: la ligislación tributaria permite reconocer como gasto las pérdidas contables de años anteriores hasta por 5 años.

**Aspectos a tener en cuenta en la evalucación de proyectos**
- **Ganancias/pérdidas de capital**: cuando se venden bienes de uso afectados al proyecto, se descuentan sus amortizaciones y su valor residual y se obtiene una diferencia denominada **"RESULTADO DE VENTA DE BIEN DE USO"**. Será gun ingreso si es positiva o egreso si es pérdida para el flujo de fondos proyectado.
- **Recuperación del capital de trabajo**: al cierre del proyecto puede que no se recupere la inversión en capital de trabajo y será un egreso para el flujo (por ejemplo un inventario de mercaderías obsoleto, créditos incobrables, etc.)

### Otros Impuestos
**Impuestos Internos**  
Tienen por objetivo desalnetar actividades o generar ingresos para financiar otras. Grava únicamente a la etapa de fabricación o importación (con excepciones).
**Ingresos Brutos**  
Es un impuesto en cascada que alcanza a toda acitivdad lucrativa, gravando a las ventas devengadas dentro de una jurisdicción con tasas que van del 2 al 5 %, con algunas exenciones.
**Impuesto a los Sellos**  
Se aplica sobre contratos 1 al 3 %  
**Ganancia mínima presunta**  
1 % sobre activos gravados, a cuenta del IIGG.

> IIBB, Internos y Sellos, deben considerarse como un **COSTO** más en el Proyecto. 

___

## Inflación

### Activos y Pasivos MONETARIOS
- Tinene valor "nominal" fijo en moneda de curso legal
  - Ejemplo
    - Si tenemos activos como "CAJA", en contexto inflacionarios es una **PÉRDIDA**
    - Si tenemos pasivos como "PROVEEDORES", debemos dinero, es una **GANANCIA**

### Activos y Pasivos NO MONETARIOS
- No tienen valor "nominal" puesto que su precio puede variar.
- Generan resultado por tenencia, por ejemplo MERCADERÍAS en stock. No depende exclusivamente de la inflación (pude variar especificamente el bien)

### REI o RECPAM
- Resultado originado en la exposición a la inflación de cuentas monetarias

___

## Inflación - Moneda Homogénea
En contexto con inflación significativa (mas del 100% en 3 años según norma) el valor del dinero disminuye, es decir cae el poder adquisitivo de la moneda.
No permite comparar datos expresados en monedas de distintas fechas, dado que están expresado en una unidad de medida "Heterogénea".  

**Moneda Homogénea:** pesos expresados en términos del mismo poder de compra relativo a un tiempo expecífico (AÑO BASE)

___

## Inflación - Tasa Real e Inflada
**Tasa Real (Ir)**  
Dinero que se paga por el uso de capital, expresado como una tasa efectiva por período de interés, que no incluye un ajuste de inflación.  
**Tasa Inflada (If)**  
Dinero que se paga por el uso de capital, expresado como una tasa efectiva por período de interés, que incluye un ajuste por la tasa de inflación general anticipada en la economía.

$$ I_f = (1+I_r).(1+T_{inflación}) - 1 $$

| TREMA | Nominales                               | Homogéneos                          |
| ----- | --------------------------------------- | ----------------------------------- |
| If    | **Correcto**                            | **Error 1**: Sesgo contra inversión |
| Ir    | **Error 2**: Sesgo a favor de inversión | **Correcto**                        |


___

## Inflación - Efectivo, Créditos y Deudas
**Poseer Efectivo**  
- Es desfavorable por la pérdida de valor del dinero inmovilizado. 
- _Mantener stocks de efectivo bajos pero compatibles con las operaciones._

**Poseer Créditos (los clientes nos deben)**  
- Impacto desfavorable por la pérdida del valor del dinero prestado a los Clientes. 
- _Acortarse lso plazos o precios por encima del ritmo inflacionario._

**Poseer Deudas**  
- Impacto favorable por la pérdida del valor adeudado. 
- _Recurrir a finaciación de proveedores y a más plazo._

___

## Inflación - Evolución de precios relativos
Pronosticar precios y costos más importantes a través del tiempo en los proyectos.

Proyectar los flujos de fondos en monedas de cada uno de los períodos del horizonte de planeamiento, utilizando distintos índices. Luego deflactar los flujos para llevarlos a moneda base.
Deflactor a utilizar: índice de precios internos al por mayor IPIM (INDEC). Se busca una tasa que represente la evolución de los principales insumos.

Si el costo de materia prima crecerá el 50% por período y así se proyecta su flujo de egresos. Deflactaría su flujo de efectivo operativo con una tasa de indices de precios mayoristas que se pronostica crecerá al 25% por período?