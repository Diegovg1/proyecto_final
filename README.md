# Dataset - Riesgo de incumplimiento de pagos
Este conjunto de datos contiene información sobre pagos predeterminados, factores demográficos, datos crediticios, historial de pagos 
y estados de cuenta de clientes de tarjetas de crédito en Taiwán desde abril de 2005 hasta septiembre de 2005. El objetivo principal 
es estimar la probabilidad de incumplimiento de pago de los clientes.

### Descripción de las variables:
- ID: ID de cada cliente
- LIMIT_BAL: monto del crédito otorgado en dólares NT (incluye crédito individual y familiar/suplementario)
- SEX: Género (1=masculino, 2=femenino)
- EDUCATION: (1=graduado, 2=universidad, 3=bachillerato, 4=otros, 5=desconocido, 6=desconocido)
- MARRIAGE: Estado civil (1=casado, 2=soltero, 3=otros)
- AGE: Edad en años
- PAY_1: estado de pago en septiembre de 2005 (-1=pago debido, 1=retraso en el pago de un mes, 2=retraso en el pago de dos meses, ...8=retraso en
  el pago de ocho meses, 9=retraso en el pago de nueve meses o más)
- PAY_2: Estado de pago en agosto de 2005 (escala igual a la anterior)
- PAY_3: Estado de pago en julio de 2005 (escala igual a la anterior)
- PAY_4: Estado de pago en junio de 2005 (escala igual a la anterior)
- PAY_5: Estado de pago en mayo de 2005 (escala igual a la anterior)
- PAY_6: Estado de pago en abril de 2005 (escala igual a la anterior)
- BILL_AMT1: Importe del estado de cuenta en septiembre de 2005 (dólar NT)
- BILL_AMT2: Importe del estado de cuenta en agosto de 2005 (dólar NT)
- BILL_AMT3: Importe del estado de cuenta en julio de 2005 (dólar NT)
- BILL_AMT4: Importe del estado de cuenta en junio de 2005 (dólar NT)
- BILL_AMT5: Importe del estado de cuenta en mayo de 2005 (dólar NT)
- BILL_AMT6: Importe del estado de cuenta en abril de 2005 (dólar NT)
- PAY_AMT1: Importe del pago anterior en septiembre de 2005 (dólar NT)
- PAY_AMT2: Importe del pago anterior en agosto de 2005 (dólar NT)
- PAY_AMT3: Importe del pago anterior en julio de 2005 (dólar NT)
- PAY_AMT4: Importe del pago anterior en junio de 2005 (dólar NT)
- PAY_AMT5: Importe del pago anterior en mayo de 2005 (dólar NT)
- PAY_AMT6: Importe del pago anterior en abril de 2005 (dólar NT)
- DEFAULT: Pago predeterminado (1=sí, 0=no)

### Contexto Comercial
Uno de los principales ingresos de los bancos son los préstamos a los clientes. La ganancia de los bancos radica en los intereses que le cobran 
por el préstamo, el cual varía para cada cliente y está sujeto a diferentes factores. Uno de los factores más importantes es el riesgo, y este se 
calcula por las distintas variables que tiene el cliente, como por ejemplo su edad, sus ingresos mensuales, su historial crediticio, etc. Sin 
embargo, existen algunos clientes a los cuales les prestan dinero y luego terminan incumpliendo los pagos, lo cual termina perjudicando a los 
bancos. Esta práctica se ha vuelto algo frecuente en algunas personas, ya que saben que no hay cárcel por incumplimiento de pagos. Por lo tanto, 
el objetivo de este proyecto es poder identificar a los clientes que van a incumplir los pagos para así minimizar las pérdidas del banco y la 
utilidad sea mayor.
