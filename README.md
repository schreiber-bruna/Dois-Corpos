Simulação do Problema de Dois Corpos

Este projeto implementa uma simulação do movimento de dois corpos atraídos exclusivamente pela ação da gravidade mútua, exportando o resultado das trajetórias orbitais como uma animação em formato GIF.

Fundamentação Teórica:

  A modelagem do movimento se baseia na solução do problema de Kepler:

    Solução do Problema Reduzido: A trajetória é calculada utilizando a equação polar da órbita para o problema reduzido, conforme os conceitos da seção 7 do capítulo 2 da apostila.

    Coordenadas das Posições: As posições absolutas e as coordenadas cartesianas exatas de cada corpo são isoladas a partir da relação com o centro de massa do sistema, seguindo os preceitos da seção 4 do capítulo 3 da apostila.

Parâmetros da Simulação:

  O algoritmo foi estruturado utilizando as seguintes constantes e condições iniciais:

    $L = 10^5$ (Momento angular)

    $G = 6.7 \times 10^{-11}$ (Constante gravitacional)

    $c = 10^6$ (Constante de escala temporal/angular)

    $m_1 = 5 \times 10^{24}$ (Massa do corpo 1)

    $m_2 = 7 \times 10^{23}$ (Massa do corpo 2)

    $k = G(m_1 + m_2)$

    $p = L^2 / k$

    $e = 0.8$ (Excentricidade da órbita)

  Funcionamento e Objetivo:

    Calcula-se o raio orbital e o converte para coordenadas cartesianas relativas, dividindo em seguida a órbita absoluta de $m_1$ e $m_2$ com base na proporção de suas massas.

    Destacando o centro de massa (posição estática) e traça o movimento orbital frame a frame.
