# Dijkstra Project

**Discente:** Vinícius José da Silva Gomes
**Prontuário:** HT3083322
**Orientador:** Luiz Marangoni
**Instituição:** IFSP, Campus Hortolândia
**Programa:** PACTec (Edital FAI•UFSCar nº 004/2026)

## Sobre o projeto
Navegação autônoma com ROS usando o algoritmo de Dijkstra em ambiente de ensino em nuvem.

## Objetivo
Fazer um robô encontrar o melhor caminho entre um ponto A e um ponto B, desviando de obstáculos. O foco são veículos (navegação em 2D). Drones (3D) aparecem como possível extensão.

## Como funciona
1. **Mapeamento (SLAM):** o mapa pode ser fornecido (arquivo de coordenadas).
2. **Navegação:** os sensores leem o ambiente e o algoritmo de Dijkstra calcula o melhor caminho. O mapa é tratado como uma grade com obstáculos.
3. **Simulação:** o Gazebo simula o ambiente em 3D e o RQT mostra gráficos e a visão em 2D.

## Ferramentas
- ROS 2 (Robot Operating System)
- Python (implementação do Dijkstra)
- Gazebo (simulador multi-físico) e RQT (interface gráfica do ROS)
- Linux (Ubuntu) dentro de um container Docker
- Git e GitHub (controle de versão)
- Robô de referência: iRobot Roomba, modelo compatível com ROS
