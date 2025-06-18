# proj07_Processador_de_linguagem_natural
#  Processamento de Linguagem Natural (PLN) com Python

Este projeto tem como objetivo introduzir os conceitos básicos de **Processamento de Linguagem Natural (PLN)** utilizando a linguagem Python. A partir de um arquivo de texto (corpus), o programa realiza operações de **limpeza textual**, **análise de frequência**, e **extração de informações relevantes**, aplicando técnicas iniciais de **mineração de dados linguísticos**.

##  Funcionalidades

O programa realiza as seguintes operações, de forma sequencial:

1. **Leitura do Corpus**  
   - Leitura de um arquivo `.txt` contendo o texto a ser analisado.

2. **Limpeza do Texto**  
   - Conversão de todo o texto para letras minúsculas.
   - Remoção de pontuações e caracteres especiais.
   - Remoção de stopwords (palavras comuns sem valor semântico relevante, como “de”, “para”, “e”).

3. **Tokenização**  
   - Separação do texto em palavras (tokens) individuais.

4. **Análise de Frequência**  
   - Cálculo da quantidade de vezes que cada palavra aparece no corpus.

5. **Extração de Palavras Relevantes**  
   - Identificação das palavras mais frequentes (top N palavras).
   - Possível aplicação de métricas como TF (Term Frequency) em projetos mais avançados.

