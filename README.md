# Thermometer with LM35, Keyboard and PIC

## Exemplo do Livro:
"Digital Image Processing Using Matlab" 2ed Gonzalez
Página 128

## Averiquando qualidade de motor usando Fuzzy

### FUZZIFICACÃO
#### Conjunto de Entrada:
   Baseado somente na Frequencia media de vibração (AVF)
   
   {Low, Mid, High}
#### Conjunto de Saída:
   Percentual de Abnormalidade do Motor (MOTOR)

   {Norm, Marg, Fail}
#### Inferência:
   if AVR is LOW then MOTOR is NORM

   or

   if AVR is MID then MOTOR is MARG

   or

   if AVR is HIGH then MOTOR is FAIL

### DEFUZZIFICAÇÃO
   Usando o Centro de Gravidade
