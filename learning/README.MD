Nível 1: Fundações Matemáticas e Computacionais

· Objetivo Geral: Dominar os conceitos fundamentais de Álgebra Linear e sua implementação básica em código.
· Tópicos de Estudo:
  · Vetores e Espaços Vetoriais: Definição, adição, multiplicação por escalar, combinações lineares, independência linear, base e dimensão.
  · Matrizes e Operações: Definição, adição, multiplicação (matriz-matriz e matriz-vetor), matriz transposta, matriz identidade.
  · Sistemas de Equações Lineares: Representação matricial, eliminação de Gauss (escalonamento), existência e unicidade de soluções.
  · Determinantes: Definição, propriedades, cálculo e interpretação geométrica (área/volume).
  · Espaços Vetoriais Fundamentais: Espaço nulo (nullspace), espaço coluna e espaço linha de uma matriz.
  · Autovalores e Autovetores: Definição, cálculo, diagonalização de matrizes, aplicações iniciais.
  · Transformações Lineares: Definição, núcleo e imagem, representação matricial de uma transformação.
· Habilidades em Programação/Arquitetura:
  · Python Básico: Sintaxe, estruturas de dados (listas), estruturas de controle (loops, condicionais).
  · NumPy: Criação de arrays e matrizes (np.array, np.zeros, np.eye), indexação, operações aritméticas, produto escalar (np.dot).
  · Visualização Básica com Matplotlib: Plotar vetores e pontos no plano 2D.

Nível 2: Implementação Computacional e Arquitetura Numérica

· Objetivo Geral: Implementar algoritmos de Álgebra Linear, entender sua complexidade e os aspectos de arquitetura de computadores que impactam o desempenho.
· Tópicos de Estudo:
  · Decomposições Matriciais:
    · Decomposição LU: Fatoração para resolução de sistemas, com e sem pivotamento.
    · Decomposição QR: Processo de Gram-Schmidt, solução de mínimos quadrados.
    · Decomposição em Valores Singulares (SVD): Definição, interpretação geométrica, aplicações (PCA, compressão).
  · Mínimos Quadrados: Formulação do problema, solução via equações normais e via decomposição QR/SVD.
  · Números de Ponto Flutuante: Padrão IEEE 754, erros de arredondamento, cancelamento subtrativo, estabilidade numérica.
  · Condicionamento de Problemas: Número de condição de uma matriz, sensibilidade de soluções a perturbações nos dados.
  · Complexidade Computacional: Análise de complexidade (notação Big-O) dos algoritmos de multiplicação de matrizes, eliminação de Gauss, etc.
· Habilidades em Programação/Arquitetura:
  · Implementação de Algoritmos: Codificar do zero as decomposições LU e QR (versão básica).
  · Bibliotecas Científicas: Uso avançado do SciPy (scipy.linalg.lu, scipy.linalg.qr, scipy.linalg.svd) para operações otimizadas.
  · Otimização para Arquitetura: Conceitos de localidade de referência (cache), processamento vetorial (instruções SIMD), paralelismo multi-core básico.
  · Análise de Performance: Uso de timers (timeit) para comparar implementações ingênuas com funções de bibliotecas otimizadas.

Nível 3: Aplicações Avançadas e Tópicos Especiais

· Objetivo Geral: Aplicar o conhecimento em domínios especializados como gráficos 3D, aprendizado de máquina e computação científica de alto desempenho.
· Tópicos de Estudo:
  · Gráficos 3D e Transformações Geométricas:
    · Rotações 2D e 3D: Matrizes de rotação, problemas com ângulos de Euler (gimbal lock).
    · Quatérnions: Definição, álgebra, uso para representar e interpolar rotações 3D de forma robusta.
    · Coordenadas Homogêneas: Representação unificada de rotações, translações e projeções em perspectiva.
    · Pipeline de Transformações: Modelo, visualização e projeção.
  · Machine Learning e Ciência de Dados:
    · Análise de Componentes Principais (PCA): Derivação via SVD, redução de dimensionalidade.
    · Regressão Linear: Formulação matricial, solução via mínimos quadrados.
    · Álgebra Linear em Redes Neurais: Operações em camadas densas (fully connected), propagação para frente (forward pass) como multiplicação de matrizes.
  · Computação de Alto Desempenho (HPC):
    · Bibliotecas de Baixo Nível: Introdução aos padrões BLAS (operações básicas) e LAPACK (álgebra linear avançada).
    · Computação em GPU: Paradigma de processamento massivamente paralelo para operações matriciais.
· Habilidades em Programação/Arquitetura:
  · Bibliotecas de Domínio Específico:
    · Gráficos 3D: PyGame, OpenGL (via ModernGL) ou bibliotecas de visualização como plotly.
    · Machine Learning: Frameworks como PyTorch ou TensorFlow, com foco na construção e treinamento de modelos a partir dos operações básicas.
    · HPC/GPU: Uso de CuPy (interface similar ao NumPy para GPU) ou Numba (compilador just-in-time) para acelerar código.
  · Projeto Integrador: Desenvolver um aplicativo que combine vários conceitos, como um visualizador 3D simples com rotações controladas por quatérnios ou uma implementação completa de PCA e regressão linear em um conjunto de dados real.

Esta estrutura oferece um caminho claro e progressivo para integrar teoria e prática. Gostaria de sugestões para um projeto prático integrador do Nível 3 que combine rotações 3D e visualização?