# 🤖 Aplicações de Robótica e IA em Mecatrônica

<p align="left">
  <img src="https://img.shields.io/badge/Curso-Mecatr%C3%B4nica-0056B3?style=for-the-badge&logo=gear" alt="Curso Mecatrônica">
  <img src="https://img.shields.io/badge/Turma-103-28A745?style=for-the-badge" alt="Turma 103">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-FFA500?style=for-the-badge" alt="Status">
</p>

## 👥 Equipe do Projeto

| Integrante | Função |
| :--- | :--- |
| Gabriel de Paula | Desenvolvimento de algoritmos e simulação |
| Eduardo Rafael | Eletrônica e sistemas embarcados |
| Maria Luiza | Modelagem mecânica e CAD |
| Vitória | Documentação e interface de supervisão |
| Rafael   | pesquisa do conteudo
| Mizael Souto | professor |

---

## 📋 Informações Gerais

| Item | Descrição |
| :--- | :--- |
| **Curso** | Mecatrônica |
| **Turma / Sala** | 103 
| **Tema** | Robótica e Inteligência Artificial aplicadas à Mecatrônica |
| **Data** | 2026 |

---

## 📌 Sobre o Projeto

Este projeto explora a aplicação prática da **Robótica e Inteligência Artificial (IA)** em ambientes mecatrônicos. A proposta é integrar **engenharia mecânica, eletrônica, controle e computação** com algoritmos de IA, permitindo que os sistemas robóticos percebam o ambiente, aprendam com dados e tomem decisões autônomas.

A robótica tradicional segue sequências pré-programadas. Com a adição de **IA, visão computacional e aprendizado de máquina**, os robôs se tornam capazes de:

- Identificar objetos e defeitos em tempo real
- Adaptar trajetórias diante de obstáculos
- Otimizar processos a partir de dados históricos
- Colaborar com humanos de forma segura (cobots)

---

## 🎯 Aplicações Práticas

| Área | Aplicação com IA |
| :--- | :--- |
| **Manufatura Inteligente** | Robôs com visão computacional para soldagem, montagem e inspeção de qualidade. |
| **Pick and Place com IA** | Classificação de peças por formato, cor ou defeito usando redes neurais. |
| **Veículos Autônomos (AGV/AMR)** | Navegação baseada em SLAM, desvio de obstáculos e otimização de rotas. |
| **Controle de Qualidade** | Inspeção automatizada com câmeras e deep learning para detecção de falhas. |
| **Manutenção Preditiva** | Sensores + IA para identificar padrões de falha antes da quebra. |

---

## ⚙️ Arquitetura do Sistema com IA

| Camada | Componentes | Funcionalidade + IA |
| :--- | :--- | :--- |
| **Mecânica** | Estruturas articuladas, engrenagens, eixos | Suporte físico para movimentos precisos |
| **Eletrônica/Potência** | Servomotores, drivers, relés | Conversão de sinais em ação mecânica |
| **Sensoriamento** | Câmeras, LiDAR, encoders, ultrassom | Coleta de dados para percepção ambiental |
| **IA & Processamento** | GPUs, microcontroladores, ROS | Visão computacional, ML, Deep Learning, controle adaptativo |
| **Controle** | PID, cinemática inversa, controle preditivo | Ações baseadas em decisões da IA |
| **Comunicação** | CAN, EtherCAT, MQTT, OPC UA | Sincronização em tempo real e dados para IA |

---

## 🧠 Tecnologias e Ferramentas

| Categoria | Ferramentas / Tecnologias |
| :--- | :--- |
| **Linguagens** | C/C++, Python, Ladder, JavaScript |
| **IA e Visão** | OpenCV, TensorFlow, PyTorch, YOLO |
| **Robótica** | ROS (Robot Operating System), MoveIt, Gazebo |
| **Controladores** | Arduino, ESP32, STM32, PLCs industriais |
| **Simulação** | MATLAB/Simulink, SolidWorks, Fusion 360 |
| **Comunicação** | MQTT, ROS 2, Modbus, Profinet |

---

## 🔁 Fluxo de um Robô Inteligente

```mermaid
graph LR
    A[Sensores / Câmera] --> B[IA / Visão Computacional]
    B --> C[Decisão / Planejamento]
    C --> D[Controlador]
    D --> E[Atuadores]
    E --> F[Movimento]
    
