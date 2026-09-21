# Visão Computacional: caderno de estudos com NotebookLM

**Fundamentos, segmentação, representação de imagens e reconhecimento de objetos**

Projeto educacional desenvolvido para o desafio da **DIO**, com foco no uso da inteligência artificial como apoio à aprendizagem ativa, à organização do conhecimento e à análise crítica de fontes.

**Autor:** Leandro Oliveira  
**Status:** em desenvolvimento — consolidação dos estudos e registro das evidências  
**Ferramenta de estudo:** NotebookLM  
**Temas:** visão computacional, processamento de imagens, Python, OpenCV e aprendizado de máquina

> [Acessar o caderno no NotebookLM](https://notebook.google.com/notebook/d7dbea30-33ee-4d29-878c-35745797085f). O acesso depende das permissões de compartilhamento do notebook. Este README concentra a documentação para permitir a consulta independentemente desse acesso.

## Sumário

- [1. Contexto e objetivos](#1-contexto-e-objetivos)
- [2. Curadoria de fontes](#2-curadoria-de-fontes)
- [3. Metodologia de estudo](#3-metodologia-de-estudo)
- [4. Engenharia de prompts e cicatrizes](#4-engenharia-de-prompts-e-cicatrizes)
- [5. Miniguia de estudo](#5-miniguia-de-estudo)
- [6. Glossário](#6-glossário)
- [7. Prompts reutilizáveis](#7-prompts-reutilizáveis)
- [8. Próximos passos e checklist](#8-próximos-passos-e-checklist)
- [9. Autoria e uso de IA](#9-autoria-e-uso-de-ia)

## 1. Contexto e objetivos

A visão computacional permite extrair informações de imagens e vídeos para apoiar tarefas como identificação de objetos, inspeção visual e análise de padrões. O tema foi escolhido para aprofundar conhecimentos sobre como transformar dados visuais em informações úteis, aproximando fundamentos teóricos de possíveis aplicações práticas.

Este projeto reúne um caderno temático no NotebookLM e um miniguia de revisão. A proposta é utilizar a IA para formular perguntas, comparar conceitos e organizar explicações, mantendo a verificação das respostas nas fontes consultadas.

### Objetivo geral

Construir uma base conceitual em visão computacional e documentar um processo de aprendizagem apoiado por IA, com fontes identificáveis, perguntas bem estruturadas e avaliação crítica das respostas.

### Objetivos específicos

- Entender como imagens digitais são representadas e processadas.
- Diferenciar processamento de imagens, segmentação, descrição e reconhecimento.
- Conhecer técnicas introdutórias de segmentação e extração de características.
- Compreender a relação entre visão computacional e aprendizado de máquina.
- Relacionar os conceitos a exemplos de inspeção visual e reconhecimento de objetos.
- Aprimorar prompts e registrar o que funcionou, o que falhou e o que precisou de revisão.
- Consolidar resumos, um glossário e perguntas reutilizáveis para futuras revisões.

**Escopo:** estudo introdutório e documentação do aprendizado. Este repositório não apresenta um sistema de visão implementado nem resultados experimentais de desempenho.

## 2. Curadoria de fontes

### 2.1. Materiais utilizados no notebook

A seleção abaixo corresponde aos materiais informados como parte do caderno. Há outras videoaulas no notebook; esta lista apresenta um recorte das referências.

| ID | Fonte e acesso | Formato | Finalidade no estudo |
| --- | --- | --- | --- |
| F1 | Ricardo Antonello — [Introdução à Visão Computacional com Python e OpenCV](https://professor.luzerna.ifc.edu.br/ricardo-antonello/wp-content/uploads/sites/8/2017/02/Livro-Introdu%C3%A7%C3%A3o-a-Vis%C3%A3o-Computacional-com-Python-e-OpenCV-3.pdf) | Livro em PDF | Base introdutória e aproximação dos conceitos com Python e OpenCV. |
| F2 | [Visão Computacional — Reconhecimento de objetos](https://www.youtube.com/watch?v=QBkizr0hrxA) | Videoaula | Aprofundamento do eixo de reconhecimento de objetos. |
| F3 | [Visão Computacional — Representação e Descrição](https://www.youtube.com/watch?v=ieTKBApouUc) | Videoaula | Estudo de formas de representar e descrever informações visuais. |
| F4 | [Visão computacional — Segmentação de imagens](https://www.youtube.com/watch?v=eOrBkDDWpIA) | Videoaula | Estudo da separação de regiões de interesse. |
| F5 | [Visão computacional — Aprendizado de máquinas](https://www.youtube.com/watch?v=qVMvyGz1cvQ) | Videoaula | Estudo da relação entre aprendizado de máquina e análise de imagens. |
| F6 | OpenCV — [Image Thresholding](https://docs.opencv.org/4.x/d7/d4d/tutorial_py_thresholding.html) | Documentação oficial em texto, em inglês | Explica limiarização global, adaptativa e pelo método de Otsu. |
| F7 | OpenCV — [Contour Features](https://docs.opencv.org/4.x/dd/d49/tutorial_py_contour_features.html) | Documentação oficial em texto, em inglês | Apresenta medidas e descritores geométricos de contornos. |

### Critérios de seleção e leitura crítica

- **Pertinência:** conexão direta com os objetivos e com os eixos do caderno.
- **Identificação:** preferência por materiais com autoria ou instituição identificável.
- **Complementaridade:** combinação de introdução didática, aulas e documentação técnica.
- **Rastreabilidade:** registro da página, seção ou trecho que sustenta cada explicação.
- **Contexto técnico:** exemplos de diferentes versões do OpenCV precisam ser conferidos antes de uma futura implementação.

O acesso gratuito a uma fonte não implica autorização para redistribuir seu conteúdo integral. Por isso, este repositório apresenta links e sínteses próprias.

## 3. Metodologia de estudo

O notebook já foi criado e está sendo utilizado para aprofundamento no tema. O roteiro abaixo orienta a consolidação e a documentação desse processo:

1. **Selecionar as fontes:** identificar o que cada material acrescenta ao tema.
2. **Organizar os tópicos:** fundamentos, segmentação, representação, descrição e reconhecimento.
3. **Perguntar com um objetivo:** definir a dúvida, o nível de profundidade e o formato esperado.
4. **Conferir as respostas:** abrir as referências indicadas e verificar se sustentam as afirmações.
5. **Refinar o prompt:** corrigir ambiguidades, limitar o escopo e solicitar exemplos ou comparações.
6. **Explicar com palavras próprias:** reescrever a ideia e tentar aplicá-la a uma situação diferente.
7. **Registrar evidências:** guardar resposta, referência, dificuldade e avaliação da melhoria.

Uma resposta organizada não é automaticamente correta. Quando as fontes não oferecerem suporte suficiente, a lacuna deve permanecer explícita.

## 4. Engenharia de prompts e cicatrizes

### 4.1. Roteiro de experimentos

| Experimento | Pergunta inicial | Variação refinada | Critério de avaliação |
| --- | --- | --- | --- |
| E1 — Fundamentos | O que é visão computacional? | Com base nas fontes selecionadas, diferencie visão computacional e processamento de imagens. Apresente definição, exemplo e referência para cada conceito. | Distinções claras e referências que sustentem as explicações. |
| E2 — Segmentação | Como funciona a segmentação? | Explique segmentação para um iniciante. Compare limiarização global, adaptativa e Otsu, se as fontes abordarem os métodos. Indique condições de uso, limitações e referências. | Comparação contextualizada, sem declarar um método universalmente superior. |
| E3 — Descrição | O que são características de uma imagem? | Diferencie representação e descrição. Explique como área, perímetro, cor ou textura podem caracterizar uma região, apenas quando houver suporte nas fontes. | Separação entre a região representada e os atributos extraídos dela. |
| E4 — Reconhecimento | Como reconhecer objetos? | Diferencie classificação, detecção e segmentação. Use o mesmo exemplo de inspeção de peças e identifique a saída de cada tarefa. Cite as fontes e sinalize lacunas. | Uso consistente dos termos e exemplos compatíveis com cada tarefa. |
| E5 — Aprendizado | Qual a relação entre visão computacional e aprendizado de máquina? | Compare uma solução baseada em regras com uma solução que aprende a partir de exemplos. Explique necessidades de dados, limitações e avaliação, com apoio nas fontes. | Evitar a conclusão de que toda solução visual exige redes neurais. |

### 4.2. Registro de um teste real

Duplicar este bloco para cada experimento executado. Substituir os campos entre colchetes antes da entrega final.

```text
Experimento: [E1]
Data: [21/09/2026]
Fontes selecionadas no NotebookLM: [1 - Livro: Introdução a Visão Computacional com Python e OpenCV, 2 - Videoaula: Visão Computacional - Introdução à Visão Computacional, 3 - Documento PDF: AS\_97487\_TG\_611I26\_KA\_US\_1088\_1.pdf (Keyence Guide)]
Objetivo: [Definição da visão computacional e a diferenciação do processamento de imagens. ]

Prompt inicial:
O que é visão computacional?

* Com base nas fontes selecionadas, diferencie visão computacional e processamento de imagens. Apresente definição, exemplo e referência para cada conceito.
* Distinções claras e referências que sustentem as explicações.

Resposta obtida:
[### 1\. O que é Visão Computacional?

* **Definição**: É a ciência e a tecnologia dedicada à criação de máquinas e sistemas artificiais que conseguem "enxergar". O seu objetivo principal é "dar" o sentido da visão a um computador, imitando o sistema visual e a cognição humana para extrair informações de imagens (ou dados multidimensionais) e tomar decisões com base no que foi visto]

### 4.3. Cicatrizes: roteiro de troubleshooting

Os itens abaixo são **situações a observar**, não relatos de problemas já encontrados.

| Se ocorrer... | Ajuste a testar | Evidência a registrar |
| --- | --- | --- |
| Resposta ampla ou superficial | Delimitar uma dúvida e solicitar explicação em etapas. | Trechos antes e depois do refinamento. |
| Conceitos tratados como sinônimos | Pedir comparação com definição, entrada e saída de cada tarefa. | Diferença corrigida e fonte correspondente. |
| Afirmação sem suporte identificável | Solicitar a passagem que a sustenta e conferir o contexto. | Referência confirmada ou afirmação retirada. |
| Exemplo de código incompatível | Identificar a versão do material e consultar a documentação correspondente. | Erro observado, ambiente e alteração testada. |
| Aula com transcrição incompleta ou ambígua | Conferir o trecho no vídeo e buscar apoio textual. | Trecho problemático e esclarecimento obtido. |
| Resposta fora do material selecionado | Restringir o prompt às fontes e pedir que lacunas sejam declaradas. | Separação entre conteúdo documentado e hipótese. |

## 5. Miniguia de estudo

**Síntese inicial para revisão:** este conteúdo foi organizado com apoio de IA e ainda deve ser confrontado com as anotações e referências do caderno. Não é uma exportação das respostas do NotebookLM.

### 5.1. Imagens digitais e processamento

Uma imagem digital pode ser representada por uma matriz de pixels. Cada pixel contém valores relacionados à intensidade ou aos canais de cor. Resolução, iluminação e ruído influenciam a informação disponível para análise.

Processar uma imagem significa aplicar operações sobre seus valores ou sua geometria. Interpretar seu conteúdo envolve atribuir significado ao que foi observado. As duas atividades se conectam: melhorar o contraste pode ajudar uma etapa posterior a identificar uma região de interesse.

**Pergunta de revisão:** uma imagem visualmente mais bonita será necessariamente melhor para uma tarefa automática?

### 5.2. Organização de uma solução visual

Um fluxo didático pode incluir aquisição, pré-processamento, segmentação, extração de características e decisão. Essa sequência ajuda a estudar as responsabilidades de cada etapa, mas não é obrigatória para todos os sistemas.

| Etapa | Pergunta central | Exemplo didático |
| --- | --- | --- |
| Aquisição | A imagem contém os detalhes necessários? | Fotografar uma peça com foco e iluminação adequados. |
| Pré-processamento | Que alterações ajudam a análise? | Reduzir ruído ou recortar uma área de interesse. |
| Segmentação | Quais pixels ou regiões interessam? | Separar a peça do fundo. |
| Descrição | Quais atributos representam essa região? | Medir características geométricas. |
| Decisão | O que os atributos permitem concluir? | Verificar se a forma atende a um critério definido. |

**Limitação:** etapas posteriores não recuperam automaticamente informações que não foram capturadas adequadamente.

### 5.3. Segmentação de imagens

Segmentação é a divisão da imagem em regiões ou a identificação de pixels relevantes para uma tarefa.

Na limiarização global, um mesmo limiar é aplicado à imagem. Na adaptativa, o limiar depende da vizinhança local. Otsu determina um limiar global a partir do histograma; sua utilidade depende da distribuição das intensidades. Nenhuma dessas alternativas resolve, por si só, todos os problemas de iluminação, reflexo ou baixo contraste.

**Referência textual:** [F6 — Image Thresholding](https://docs.opencv.org/4.x/d7/d4d/tutorial_py_thresholding.html).  
**Aula relacionada no caderno:** F4.

**Pergunta de revisão:** por que um limiar fixo pode funcionar em uma imagem e falhar em outra do mesmo objeto?

### 5.4. Representação e descrição

Representar uma região é escolher como organizar sua informação, por exemplo, por uma máscara ou um contorno. Descrevê-la é calcular atributos que permitam analisá-la ou compará-la.

Entre os atributos geométricos estão área, perímetro e dimensões de um retângulo delimitador. Essas medidas ajudam a caracterizar formas, mas seus valores em pixels dependem das condições de captura. Uma área em pixels não corresponde automaticamente a uma área física em milímetros quadrados.

**Referência textual:** [F7 — Contour Features](https://docs.opencv.org/4.x/dd/d49/tutorial_py_contour_features.html).  
**Aula relacionada no caderno:** F3.

**Pergunta de revisão:** dois objetos com áreas semelhantes precisam pertencer à mesma categoria?

### 5.5. Reconhecimento de objetos

O termo reconhecimento pode abranger diferentes tarefas. Definir a saída esperada evita escolher uma abordagem que não responde ao problema.

| Tarefa | Saída esperada | Exemplo ilustrativo |
| --- | --- | --- |
| Classificação | Categoria de uma imagem ou região. | Identificar o tipo de uma peça fotografada. |
| Detecção | Localização e categoria dos objetos. | Localizar diferentes peças em uma bancada. |
| Segmentação semântica | Classe atribuída a cada pixel. | Marcar pixels de peça e de fundo. |
| Segmentação de instâncias | Máscara individual de cada objeto. | Separar duas peças da mesma categoria. |

**Aula relacionada no caderno:** F2. Conferir no material quais dessas distinções são efetivamente abordadas.

### 5.6. Aprendizado de máquina

Uma solução baseada em regras utiliza critérios definidos explicitamente. Uma solução baseada em aprendizado de máquina ajusta um modelo a partir de dados. A escolha depende do problema, da variabilidade das imagens, dos dados disponíveis e dos requisitos da aplicação.

Ao estudar uma abordagem supervisionada, é importante distinguir treinamento, validação e teste. Avaliar apenas exemplos usados para ajustar o modelo não demonstra capacidade de generalização. Imagens muito semelhantes distribuídas entre os conjuntos também podem produzir uma avaliação otimista.

**Aula relacionada no caderno:** F5. Os pontos sobre avaliação devem ser confirmados nas fontes disponíveis; se não houver cobertura, registrar a lacuna e selecionar uma referência específica.

**Pergunta de revisão:** um resultado alto em imagens conhecidas garante bom funcionamento sob outra iluminação?

### 5.7. Aplicação conceitual: inspeção de peças

**Exercício proposto, ainda não implementado:** verificar a presença de uma peça e avaliar um atributo de sua forma.

1. Definir a condição que será inspecionada e exemplos de aprovação e reprovação.
2. Capturar imagens representativas, incluindo variações de posição e iluminação.
3. Testar uma forma de separar a peça do fundo.
4. Extrair atributos adequados ao critério de inspeção.
5. Comparar as decisões com uma referência conferida manualmente.
6. Examinar erros e identificar se a causa está na captura, na segmentação ou na decisão.

Esse exercício conecta os conceitos sem pressupor que um método isolado funcione para qualquer ambiente.

## 6. Glossário

| Conceito | Definição resumida |
| --- | --- |
| Pixel | Elemento da representação digital de uma imagem. |
| Resolução espacial | Dimensões da imagem em pixels; não equivale, sozinha, à qualidade da captura. |
| Canal de cor | Componente usado para representar a cor de um pixel. |
| Escala de cinza | Representação por valores de intensidade. |
| Ruído | Variação indesejada que pode prejudicar a análise. |
| ROI | Região de interesse escolhida para processamento. |
| Pré-processamento | Operações preparatórias para uma tarefa posterior. |
| Segmentação | Separação ou identificação de regiões da imagem. |
| Limiarização | Separação de valores por critérios de limiar. |
| Máscara | Imagem ou matriz que indica a seleção de pixels ou regiões. |
| Contorno | Representação da fronteira de uma região. |
| Descritor | Atributo ou conjunto de atributos usados para caracterizar uma região. |
| Classificação | Atribuição de uma categoria a uma entrada. |
| Detecção | Identificação e localização de objetos. |
| Dataset | Conjunto de dados usado em estudo, treinamento ou avaliação. |
| Rótulo | Informação de referência associada a um exemplo. |
| Treinamento | Ajuste de um modelo a partir de dados. |
| Inferência | Aplicação de um modelo já ajustado a uma entrada. |
| Overfitting | Ajuste excessivo aos dados de treinamento, com prejuízo à generalização. |
| Generalização | Capacidade de funcionar em exemplos não utilizados no ajuste. |

## 7. Prompts reutilizáveis

### Explicação fundamentada

```text
Atue como tutor de visão computacional. Explique Visão computacional para um iniciante,
usando apenas as fontes selecionadas. Apresente definição, exemplo, limitação
e referências. Se uma informação não estiver nas fontes, declare essa lacuna.
```

## 8. Próximos passos e checklist

- [x] Definir o tema e criar o notebook.
- [x] Reunir o livro e as videoaulas informadas.
- [x] Estruturar os objetivos, o miniguia inicial e o glossário.
- [ ] Preparar propostas de prompts e um modelo de registro.
- [ ] Adicionar F6 e F7 ao NotebookLM e confirmar a importação do conteúdo.
- [ ] Executar os experimentos e registrar respostas e referências reais.
- [ ] Documentar as dificuldades efetivamente encontradas e os ajustes testados.
- [ ] Validar o miniguia e o glossário com as fontes e as anotações pessoais.
- [ ] Substituir os campos de preenchimento e atualizar o status do projeto.
- [ ] Conferir os links e as permissões de acesso ao caderno.
- [ ] Publicar este README no repositório do GitHub e entregar sua URL na DIO.

**Possíveis evoluções:** implementar exemplos em Python e OpenCV, documentar o ambiente utilizado e comparar resultados sobre um conjunto de imagens. Essas atividades são futuras e não integram os resultados desta versão.

## 9. Autoria e uso de IA

**Leandro Oliveira** — projeto de aprendizagem desenvolvido no contexto de um desafio da DIO.

O NotebookLM é utilizado como apoio ao aprofundamento dos estudos. A estrutura e a síntese inicial deste README foram elaboradas com apoio do ChatGPT. A conferência das fontes, o registro dos experimentos e a validação das conclusões são etapas de responsabilidade do autor.

Os materiais externos pertencem aos respectivos autores e instituições. Sua inclusão como referência não implica vínculo ou endosso ao projeto.
