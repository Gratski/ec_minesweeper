Engenharia do Conhecimento
============

#### TODO
- Fazer super click no que rende mais
- Aplicar mini padrões
  - Se houver um 1 na edge com duas casas adjacentes closed, com um 1 ao lado que não está na edge com três casas closed, o complement é safe
  - Se houver um 1 na edge com duas casas adjacentes closed, com um 2 ao lado que não está na edge com três casas closed, o complement é flaggado
- Só abrir safes (com super click) que tenham pelo menos 2 adjacentes unknown (fechadas sem estarem flagadas/safe) ?


  (num_closed_ajdacentes - (max flags valor) - safe  / (num_closed_ajdacentes - flags - safe)
  >
  (total_closed - safe - (minas - flags)) / (total_closed - safe - flags)


##SMART:
- abrir o maximo de cells safe que tenham nas suas vizinhas cells em estado unkown (closed, nao safe e nao flagado)