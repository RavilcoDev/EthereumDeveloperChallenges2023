# Semana 1
# Retos - aprendiendo solidity - pokemon factory

[Resolucion](https://github.com/RavilcoDev/solidity-eth-challenge/tree/resolutionEDP2)

### 1er Reto : events
Me percate que uint gastaba menos gas que uint8, luego buscando encontre que era por la conversion que se hace de 256 a 8, por lo que ¿cuando usar uint menores a 256?, en bloques y cuando se guarda en storage, cada bloque usa 256 al guardar en storage por lo que debes hacer tetriz y completar bloques que sumados den 256.

### 2do Reto : require
Use una conversion string a bytes para validiar la logitud de caracteres

### 3er Reto : Structure
Creé un estructura para la habilidades y la referencia por el index en la estructura de pokemon además de crear una función para crear nuevas habilidades que actualiza el indice máximo (para poder hace validaciones luego)

### 4to Reto:
Decidi crear un nuevo documento para manejar los tipo y debilidades ademas de exponer las respectivas debilidades medieante un par de funiones