
# Algoritmo de Otimização por Colônia de Formigas (Ant Colony Optimization - ACO)

Este código Python implementa um Algoritmo de Otimização por Colônia de Formigas (ACO). O ACO é uma técnica inspirada no comportamento das formigas para resolver problemas de otimização. Neste caso específico, o algoritmo foi desenvolvido para estudar a aplicação de ACO.

# Funcionalidades
Inicialização:

*  AlgoritmoGenetico: Inicializa o algoritmo com parâmetros padrão, incluindo a quantidade de formigas e ciclos.

Geração de Indivíduos (Formigas):

*  gerar_individuo: Gera um indivíduo (formiga) que percorre um caminho baseado na probabilidade determinada pelos níveis de feromônio.

Avaliação de Indivíduos:

*  calcular_distancia_entre_dois_pontos: Calcula a distância entre dois pontos no espaço.
*  calcular_distancia_total: Calcula a distância total percorrida por um caminho (cromossomo).
  
Seleção e Cruzamento:

*  cruzar_dois_cromossomos: Realiza o cruzamento entre dois cromossomos (formigas).

Atualização de Feromônio:

*  atualizar_feromonio: Atualiza os níveis de feromônio com base nos caminhos percorridos pelas formigas.

Execução do Algoritmo:

*  executar: Executa o algoritmo ACO por um número especificado de ciclos, gerando e avaliando caminhos.

Visualização:

*  gerar_mapa_feromonio: Gera um mapa de calor visualizando os níveis de feromônio.
