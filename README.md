Estudo de Caso: Sistema de Recomendação de Filmes com Análise de 
Sentimentos 
Projeto Final - Álgebra Linear I – Aplicações em Machine Learning 
1. Introdução e Contexto 
Problema Proposto 
Desenvolver um sistema híbrido de recomendação de filmes que combine: 
● Filtragem colaborativa baseada em similaridade entre usuários 
● Análise de sentimentos de reviews para ajustar recomendações 
● Predição de ratings usando regressão linear múltipla 
● Modelagem de comportamento temporal através de Cadeias de Markov 
Objetivos de Aprendizagem 
● Aplicar conceitos de álgebra linear em problemas reais de ML 
● Demonstrar a importância das operações matriciais em sistemas de recomendação 
● Utilizar determinantes para análise de dependência linear em features 
● Implementar regressão linear usando operações matriciais 
● Modelar transições de estados com Cadeias de Markov
2. Dataset e Preparação dos Dados 
Estrutura dos Dados 
Usuários: 1000 usuários únicos  
Filmes: 500 filmes com diferentes gêneros  
Ratings: Escala de 1-5 estrelas  
Reviews: Textos com sentimentos (positivo/negativo/neutro)  
Timestamps: Para análise temporal  
Matriz Usuário-Item (R) 
Matriz esparsa 1000×500 onde R[i,j] representa o rating do usuário i para o filme j.
