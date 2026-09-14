# MODELO DE LINGUAGEM SIMPLES - BIGRAMA DE CARACTERES

O que este código faz, em uma frase:
Ele "lê" um texto, aprende quais letras costumam vir depois de quais
outras letras, e depois usa esse conhecimento para GERAR texto novo,
letra por letra, de forma parecida (mas não igual) ao texto original.

Isso é a versão mais simples possível de um "modelo de linguagem".
Modelos como o GPT fazem a mesma ideia básica, só que:
  - olham para MUITAS letras/palavras de contexto (não só a última)
  - usam redes neurais em vez de contagem simples
  - são treinados em bilhões de palavras

Mas o PRINCÍPIO é o mesmo: prever o próximo "pedaço de texto" (token)
dado o que veio antes.

Não precisa instalar nada além do Python padrão para rodar este arquivo.
