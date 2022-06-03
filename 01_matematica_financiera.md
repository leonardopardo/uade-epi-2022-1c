# Matemática Financiera

## Interés Simple

_Definición_ 
Es una operación financiera dodne intervienen un **CAPITAL**, **TIEMPO** y una **TASA DE INTERÉS**  con un beneficio económico o pago por el uso del capital, que es el **INTERÉS**. 

El **Interés Simple** es sólo en función del capital, al que se le aplica la tasa de interés por el tiempo hasta su pago. No hay _"capitalización de intereses"_

> i: tasa de interes  
> t: tiempo

$$ [interes] = C_0 * i * t $$ 

Una vez finalizada la operación, el valor total es el **MONTO**, que es el **CAPITAL** más los **INTERESES**. También se lo denomina **VALOR FUTURO**

$$ [monto] = C_0 * (1 + i * t) $$

___

## Interés Compuesto 

_Definición_ 
Representa el costo del dinero, beneficio o utilidad de un **CAPITAL INICIAL (PV)**  a una **TASA DE INTERES (i)** durante un **PERIODO (t)** en el cual _los intereses_ que se obtienen al final de cada período de inversión no se retiran sino que _se reinvierten_ o añaden al capital inicial, es decir, se capitalizan. 

La gran mayoría de las operaciones financieras se realizan a interés compuesto con el objeto de tener en cuent aque los intereses liquidados no entregados, entran a formar parte del capital y para próximos períodos generarán a su vez intereses. Este fenómeno se conoce con el nombre de **_Capitalización de Intereses._**

$$ C_n=C_0 * (1+i)^n $$

___

## Inflación y Tasa de Interés

- "tasa" o "tipo" de interés es el porcentaje al que está invertido un capital en una unidad de tiempo, determinando **_"el precio del dinero en el mercado financiero"_**
- La tasa de interés (expresada en porcentaje) representa un balance entre el riesgo y la posible gananacia (oportunidad) de la utilización de una suma de dinero en una situación y tiempo determinado.
- La tasa de interés es el precio del dinero que se debe pagar o cobrar, según sea el deudor quien por tomarlo paga, o el acreedor quien opr prestarlo cobra (salvo determinados mercados en tiempos raros, "tipos" negativos en Europa).
- Por ejemplo, si las tasas de interés fueran las mismas tanto para depósitos en bonos del Estado, cuentas bancarias o inversiones en cualuquier tipo de industria, nadie invertiría en acciones o depositaría en un banco, ya que elegiría lo más seguro.

_Ejemplo Numérico_  

> IA: Interés Aparente o Nominal  
> $\pi$: Inflación  
> IR: Interés Real


**Ecuación de Fisher, Irving:**

$$ (1 + i_A) = (1 + \pi).(1 + i_R) $$

| capital inicial | interés | inflación | resultado | IA  | Pi  | IR  |
| --------------- | ------- | --------- | --------- | --- | --- | --- |
| $ 100,00        | 20%     | 0%        | $ 120,00  | 20% | 0%  | 20% |
| $ 100,00        | 20%     | 10%       | $ 120,00  | 20% | 10% | 9%  |
| $ 100,00        | 20%     | 25%       | $ 120,00  | 20% | 25% | -4% |

_Se puede apreciar en la tabla como el resultado de en unidades monetarias es el mismo, pero el rendimiento decae a medida que la inflación aumenta._
___

## Técnicas de Evaluación
- Métodos contables (ROI - Repago)
- VAN
- IR
- TIR / TIRM

### **Evalución de proyectos de inversión**
Supone siempre que los proyectos se financian con **fondos propios** (para establecer su propio mérito) y el **costo de capital** es un dato del problema.

### **Técnicas de Evaluación de Proyectos de TI**
La compañia puede elegir que tipo de financiación utilizar para evaluar el proyecto:
- Financiación propia -  tasa de retorno mínima aceptable **(TREMA)**
- Financiación de la estructura de pasivos de la empresa **WACC**

### **Tasas de rendimiento contable**
- ROI (retorno sobre inversión)
- ROA (retorno sobre activos)

> **Problemas:**
> - No tienen en cuenta el valor del dinero en el tiempo
> - Sufre el efecto de distorsiones contables (métodos de valuación de activos y reconocimientos de resultados).


| **período** | **concepto**       | **flujo de fondos** |
| ----------- | ------------------ | ------------------- |
| 0           | inversion          | -$ 10.000,00        |
| 1           | recupero           | $ 3.000,00          |
| 2           | recupero           | $ 3.000,00          |
| 3           | recupero           | $ 3.000,00          |
| 4           | recupero           | $ 3.000,00          |
| 5           | recupero           | $ 3.000,00          |
| --------    | ----------         | ----------------    |
|             | **resultado neto** | $ 5.000,00          |
|             | **inversión**      | $ 10.000,00         |
|             | **ROI**            | 50%                 |

$$ ROI = \frac{[FlujoDeFondosNetos]}{[inversión]} . 100 $$

___

### Pay back (períodos de repago o recupero)
- No tiene en cuenta las utilidades posteriores al período de recupero
- No mide rentabilidad sino **"cuánto se demora en recuperar la inversión"**
- No tiene en cuenta el tiempo del dinero (excepto en la discounted pay back)

| periodo               | concepto         | flujo de repago   | años   | meses  |
| --------------------- | ---------------- | ----------------- | ------ | ------ |
| 0                     | inversion        | $ 10.000,00       |        |        |
| 1                     | recupero         | $ 3.000,00        | 1      | 0      |
| 2                     | recupero         | $ 3.000,00        | 1      | 0      |
| 3                     | recupero         | $ 3.000,00        | 1      | 0      |
| 4                     | recupero         | $ 3.000,00        | 0      | 4      |
| 5                     | recupero         | $ 3.000,00        | 0      | 0      |
|                       | repago           | 3                 | 4      |        |
| ---------             | ----------       | ----------------- | ------ | ------ |
| **resultado neto**    | $ 5.000,00       |                   |        |        |
| **inversion**         | $ 10.000,00      |                   |        |        |
| **ROI**               | 50%              |                   |        |        |
| **Periodo de repago** | 3 años y 4 meses |                   |        |        |

> Cantidad de períodos hasta que el flujo de fondos acumulado sea cero

___

### VAN - Valor Actual Neto (VNA para excel o NPV en inglés)
Diferencia entre el desembolso inicial de la inversión y el valor presente de los futuros ingresos netos esperados


| período               | concepto         | flujo de fondos nominal | flujo de fondos descontados | período de repago | años | meses |
| --------------------- | ---------------- | ----------------------- | --------------------------- | ----------------- | ---- | ----- |
| 0                     | Inversión        | $ 10.000,00             | $ 10.000,00                 | $ 10.000,00       |      |       |
| 1                     | Recupero         | $ 3.000,00              | $ 2.727,27                  | $ 7.272,73        | 1    | 0     |
| 2                     | Recupero         | $ 3.000,00              | $ 2.479,34                  | $ 4.793,39        | 1    | 0     |
| 3                     | Recupero         | $ 3.000,00              | $ 2.253,94                  | $ 2.539,44        | 1    | 0     |
| 4                     | Recupero         | $ 3.000,00              | $ 2.049,04                  | $ 490,40          | 1    | 0     |
| 5                     | Recupero         | $ 3.000,00              | $ 1.862,76                  | $ 1.372,36        | 0    | 3     |
| **tasa de descuento** |                  |                         | 10%                         | **repago**        | 4    | 3     |
| **resultado neto**    | $ 1.372,36       |                         |                             |                   |      |       |
| **inversión**         | $ 10.000,00      |                         |                             |                   |      |       |
| **ROI**               | 14%              |                         |                             |                   |      |       |
| **Período de repago** | 4 años y 3 meses |                         |                             |                   |      |       |


**Flujo de fondos descontados**

> **FFN**: Flujo de Fondos Nominal  
> **FFD**: Flujo de Fondos Descontado  
> **td**: Tasa de Descuento  
> **t**: Período  

$$ FFD = \frac{FFN}{(1+td)^t} $$

> en Excel = NPV(\[rate\], \[value 1\], ... \[value n\])

___

### IR -  Indice de rentabilidad
Es la realción del VAN sobre la inversión inicial. Permite elegir entre proyectos considerando la inversión inicial.

$$ IR = \frac{VAN}{Inversión Inicial} $$

### TIR - Tasa interna de retorno
Medida de rentabilidad (porcentaje) obtenida al vencimiento del proyecto, suponiendo que los fondos positivos se reinvierten a esa misma tasa (TIR del proyecto) hasta el final de la vida del proyecto. Equivale a la tasa que descuenta el flujo de fondos futuros y lo iguala con el desembolso inicial de la inversión, es la tasa que hace al **VAN del proyecto cero**.

| período                     | concepto  | flujo de fondos nominal | flujo de fondos descontados | periodo de repago | años | meses |
| --------------------------- | --------- | ----------------------- | --------------------------- | ----------------- | ---- | ----- |
| 0                           | Inversión | -$ 10.000               | -$ 10.000                   | -$ 10.000         |      |       |
| 1                           | Recupero  | $ 3.000                 | $ 2.603                     | -$ 7.397          | 1    |       |
| 2                           | Recupero  | $ 3.000                 | $ 2.259                     | -$ 5.138          | 1    |       |
| 3                           | Recupero  | $ 3.000                 | $ 1.960                     | -$ 3.177          | 1    |       |
| 4                           | Recupero  | $ 3.000                 | $ 1.701                     | -$ 1.476          | 1    |       |
| 5                           | Recupero  | $ 3.000                 | $ 1.476                     | $ 0               | 1    |       |
| **tasa interna de retorno** |           |                         | 15,24%                      | **repago**        | 5    |       |
| -                           | -         | -                       | -                           | -                 | -    |       |
| **resultado neto**          | $ 0       |                         |                             |                   |      |       |
| **inversión**               | $ 10.000  |                         |                             |                   |      |       |
| **ROI**                     | 0%        |                         |                             |                   |      |       |
| **período de repago**       | 5         |                         |                             |                   |      |       |


> **Problemas**
> - Supuesto de reinversión de los fondos a la misma tasa
> - Otorga el mismo resultado cuando se invierte el signo del flujo de fondos
> - Utilización en proyectos mutuamente excluyentes.
> - En caso de flujos de fondos que no son simples puede dar múltiples TIR o ser incalculable.
> - Estructura temporal de la tasa de interés
___

### TIRM (o MIRR) es la Tasa Interna de Retorno Modificada
Supone que los excedentes de fondos se reinvierten a una tasa distinta a la TIR, generalmente la tasa de costo de capital o la que el evaluador desee. Tabién corrige el problema de flujos negativos luego del inicio.

... Ver si entra l;)

> en Excel = MIRR(values; tasa financiera; tasa reinversion)
___

### Relación entre VAN y TIR
Puede haber incoherencias entre proyectos evaluados por VAN y TIR, justamente por la forma diferente de calcular la reinversión:
- VAN: la tasa está dada
- TIR: es la misma tasa de rentabilidad del proyecto.  

Las diferencias entre VAN y TIR para proyectos excluyentes se dan cuando:
- Diferente inversión inicial.
- Diferente distribución del flujo de fondos.
- Diferente vida útil.

Para estos casos se calcula el TIR incremental o tasa de Fisher. Los pasos:
- Obtener el VAN  a tasa 0 de ambos proyectos
- Se toma el que tiene el VAN más grande y se le respeta el otro a comparar.
- Se obtiene el VAN y TIR de la diferencia, y se acepta el primero si:
  - El VAN es positivo
  - Si la TIR es superior a la tasa de riesgo (k)

___

### Método Brasileño
1. El proyecto de menor inversión inicial se le agrega la diferencia de inversión inicial con el otro, y se supone qu epor esa inversión adicional ficticia se obtiene la tasa de riesgo (k)
2. Luego se compara el proyecto de desembolso inicial más alto con el otro (sumando la inversión adicional ficticia según la definición anterior) y se obtiene la VAN y TIR de ambos. 

___

### Dicounted Payback
Período en que se recupera la inversión inicial descontando los flujos de fondos futuros.

| tasa      |     | 20%    | FF desc | FF acum |
| :-------- | :-- | :----- | :------ | :------ |
| Inversion | P   | -10000 | 0       | 0       |
| FF P      | 1   | 3000   | 2500    | 2500    |
| FF P      | 2   | 3000   | 2083    | 4583    |
| FF P      | 3   | 3000   | 1736    | 6319    |
| FF P      | 4   | 3000   | 1447    | 7766    |
| FF P      | 5   | 3000   | 1206    | 8972    |
| FF P      | 6   | 3000   | 1005    | 9977    |
| FF P      | 7   | 3000   | 837     | 10814   |
| FF P      | 8   | 3000   | 698     | 11511   |
| FF P      | 9   | 3000   | 581     | 12093   |

___

## Soluciones a distintas duraciones del proyecto
- Por **valor terminal**
  - Valuar los ingresos de flujos del proyecto luego del período de evaluación (cuando hay ingresos futuros en ambos)
- Por **igualación de los períodos**
  - a través de la reinversión en el proyecto más corto para igualar la duración del más largo (cuando sea posible)
- Cuota anual **equivalente promedio** (cuando los dos métodos anteriores no son posibles)

___

### Valor Terminal
Consideración de los ingresos del proyecto luego del período de evaluación.

En este caso el proyecto se divide en dos períodos:
- Período evaluado: en el que se conoce el flujo de fondos proyectados `CF_T` período terminal donde no se conoce el flujo de fondos pero se supone constante o con el % de crecimiento de la economia: VT.

$$VT=\frac{CF_T+1}{i-g}$$

$$ VT = \frac{FF}{i-g} $$

> **i:** tasa de descuento  
> **g:** tasa de crecimiento

Valor del flujo de fondos posterior al momento T.
Valor del proyecto total:

$$V = \sum_{j=1}^{T}{\frac{CF_j}{(1+i)^j}}+\frac{VT}{(1+i)^T}$$

**Valor Terminal**  
Consideración de los ingresos del proyecto luego del período de evaluación.

### Distinta Duración
Se puede igualar las vidas útiles suponiendo que reinvertimos en el proyecto más corto llevando su extensión al mismo tiempo del proyecto más largo, y volvemos a calcular VAN y TIR.

> Obtiene la **cuota anual equivalente** promedio

## Tasas

- Mínimo riesgo/rentabilidad: plazo fijo / caja de ahorro.
- Libre de riesgo: bonos soberanos - RFR - risk free rate USA
- Tasa de rendimiento esperada por un inversionista considerando un nivel de riesgo aceptable.
- Costo de financiación de la empresa
  - **WACC** - weighted average cost of capital.
  - **CAPM** - capital asset pricing model

### Tasa RFR (Risk Free Rate)
Tasa de rendimiento esperada por un inversionista con un nivel de riesgo aceptable. Tasa libre de riesgo o Risk Free Rate (RFR).

### **Tasa WACC**

$$WACC = [CosteDeLosFondosPropios] + [CosteDeLaDeuda]$$

$$WACC = [k_e * \frac{E}{E+D}] + [K_d * (i-t) * \frac{D}{E+D}]$$

De otra forma

$$ WACC = \frac{PN}{D+PN} . K + \frac{D}{D+PN} . Tp(1-Tiigg) $$

o

$$ WACC = \frac{PN}{D+PN} . K + \frac{D}{D+PN} . KP $$

> **WACC**: costo de financiación del proyecto  
> **PN**: patrimonio neto o capital  
> **D**: Deuda `(D+PN = Pasivo Total)`  
> **K**: Tasa libre de riesgo  
> **Kp**: Costo del pasivo = `Tp(1-Tiigg)`  
> **Tp**: Tasa que cobran en promedio los acreedores  
> **Tiigg**: Tasa de impuesto a las ganancias efectivamente pagada  

### **Tasa CAPM**
Capital Asset Pricing Model es un modelo de valoración de activos financieros.

$$ E(ri) = rf + \beta[E(rm) - rf] + RP $$

> **E(ri)**: Tasa de rentabilidad esperada de un activo concreto, por ejemplo, de una acción del Merval 25  
> **rf**: Rentabilidad del activo sin riesgo  
> **Beta de un activo financiero**: Medida de la sensibilidad del activo respecto de su Benchmark. La interpretación de este parámetro nos permite conocer la variación relativa de la rentabilidad del activo respecto del mercado en que cotiza. Por ejemplo, si una acción del Merval 25 tiene una Beta de 1,1 quiere decir que cuando el Merval suba un 10% la acción subirá un 11%.  
> **E(rm)**: Tasa de rentabilidad esperada del mercado en que cotiza el activo. Por ejemplo, del Merval 25.  
> **RP**: Tasa de riesgo país (diferencia entre lo que paga un bono soberano y activo con rentabilidad libre de riesgo, ejemplo: bono soberano argentino - bono del tesoro eeuu). Solo en empresas de capital cerrado (no cotiza en bolsa)


### Riesgo País
Diferencial o "spread" del índice de Bonos de Mercados Emergentes (EMBI; a mayor porcentaje, más riesgo).  
...**Ver Clase de Tasas de ejemplo de Beta**...