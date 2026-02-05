# EdgeClap-AI

Sistema experimental de detecção de palmas utilizando inteligência artificial embarcada, desenvolvido para estudar processamento de áudio em edge devices com recursos limitados.

## Contexto
Este projeto surgiu a partir da adaptação de um modelo pré-existente de detecção de voz, com o objetivo de analisar a viabilidade de identificar padrões sonoros simples (palmas) sem processamento em nuvem.

## Objetivo
- Avaliar a detecção de eventos sonoros no dispositivo
- Estudar limitações de hardware embarcado
- Testar adaptação de modelos de áudio para novos padrões

## Abordagem
- Captura de áudio via microfone
- Extração de nível/amplitude do sinal
- Classificação básica do evento sonoro
- Execução local (edge)

## Estado atual
✔ Captação e análise básica de sinal sonoro  
✔ Detecção experimental de palmas  
❌ Treinamento de modelo dedicado  
❌ Avaliação estatística de precisão  

## Limitações conhecidas
- Código simplificado
- Modelo adaptado sem re-treinamento completo
- Sensível a ruído ambiente

## Próximos passos
- Coleta de dataset próprio
- Treinamento de modelo específico para palmas
- Otimização para microcontroladores
