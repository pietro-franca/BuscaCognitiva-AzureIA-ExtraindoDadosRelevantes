# Laboratório de Busca Cognitiva no Azure IA - Extração de informações relevantes nos textos

Nesse projeto utilizamos 9 análises de cafeterias, escritas em formato .docx, que apresentaram aspectos importantes do local, do serviço, opiniões sobre o estabelecimento e sobre sua experiência. Essas análises serviram de base para o funcionamento do serviço de Busca Cognitiva do Azure IA, que elencou os pontos mais relevantes dos textos, palavras-chave, sentimentos (positivos ou negativos) e demais informações, listando-as e criando seus respectivos índices.

### Exemplo:

* O programa irá buscar um "sentimento negativo" em meio às opiniões e retornar "true" se houver:

{
 "search": "sentiment:'negative'",
 "count": true
}

* Com isso, é possível analisar o documento de texto que possibilitou essa análise. Então, é aberto um arquivo .json detalhado com cada aspecto relevante dentro da review, como as palavras-chave e a análise de sentimentos, por exemplo:

"keyphrases": [
        "Terrible experience",
        "Review",
        "pastries",
        "time",
        "box",
        "Date",
        "October",
        "Location",
        "Chicago",
        "Illinois"
      ],
      "sentiment": "[\"negative\"]"

### Conclusões

Com este recurso, é possível extrair informações relevantes de textos e de análises rapidamente e eficientemente. Logo, torna-se uma ferramenta muito útil e estratégica para empresas que desejam ampliar suas vendas e elevar seu nível de qualidade, uma vez que se utilizam dos dados analisados para concluírem em qual área precisam evoluir, ou manter o padrão já oferecido.
