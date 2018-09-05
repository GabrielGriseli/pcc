# pcc
**P**rojeto de **C**onclusão de **C**urso em Ciência da Computação

Análise de Desempenho de Uma Aplicação Paralela Utilizando o Paralelismo de Tarefas em um Ambiente Heterogêneo.

## Resumo

O desenvolvimento de aplicações paralelas voltadas a arquiteturas heterogêneas pode vir a ser algo desafiador, pois, nessas arquiteturas, os componentes são formados por processadores \emph{multi-core} (CPUs) e placas gráficas (GPUs).
O programador, então, deverá distribuir as instruções que devem ser executadas em alguns destes componentes, embusca de alcançar o melhor desempenho da aplicação.
Existem atualmente ambientes que se encarregam desta distribuição das instruções para os componentes da arquitetura como, por exemplo, o StarPU. 
Tendo em vista isto, este trabalho explorará o paradigma de Paralelismo de Tarefas, aplicando-o em uma simulação de Transferência de Calor em uma placa metálica bidimensional e executada no ambiente StarPU.
Ao final deste trabalho, serão coletados dados sobre esta aplicação buscando avaliar seu desempenho neste ambiente, comparando com a versão sequencial da aplicação.\\

\textbf{Palavras-chave}: Aplicação Paralela. Arquiteturas Heterogêneas. Computação de Alto Desempenho.

## Abstract

he development of parallel applications for heterogeneous architectures can be somewhat challenging because,
in these architectures, the components are made up of processors multi-core and accelerators such as the GPU.
The developer should then distribute the instructions that must be performed on some of these components,
to gain the best performance of the application. There are currently runtime environments responsible
for distributing the instructions to the components of the architecture, for example, the StarPU.
From this perspective, this paper explores the Task Parallelism paradigm, applying it to a simulation of heat transfer in two-dimensional metallic plates and running in the StarPU  environment.
At the end of this work, data will be collected on this application,
searching to evaluate their performance in this environment, comparing with the sequential version of the application.\\

\textbf{Keywords}: Parallel Application. Heterogeneous Architectures. High Performance Computing.