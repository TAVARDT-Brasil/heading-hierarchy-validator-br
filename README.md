# Validador de Hierarquia de Cabecalhos H1-H6 e Estrutura Semantica

[![Validador Hierarquia H1-H6](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/br/validador-hierarquia-h1-h6/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria tecnica de titulos estruturais HTML5, unicidade de H1, deteccao de saltos de niveis e conformidade com diretrizes de acessibilidade W3C e Google.

Desenvolvido e mantido pela divisao de arquitetura semantica e acessibilidade da **TAVARDT Brasil**.

***

## Capacidades de Auditoria de Cabecalhos H1-H6

* **Inspecao de Unicidade de H1**: Verificacao da presenca de exatamente uma tag `<h1>` principal como ancora semantica do documento.
* **Deteccao de Saltos de Nivel (Level Skips)**: Identificacao de quebras de sequencia logica (como passar de `<h2>` diretamente para `<h4>` sem `<h3>`), prejudiciais a navegacao assistiva.
* **Auditoria de Textos de Cabecalho Vazios ou Excessivos**: Identificacao de tags de titulo sem conteudo de texto ou com extensao inadequada.
* **Mapeamento Visual da Arvore Semantica**: Exibicao hierarquica indentada da estrutura de secoes e topicos do conteudo.
* **Indice de Coerencia Semantica**: Pontuacao tecnica de 0 a 100 com alertas priorizados de conformidade W3C WCAG e SEO.

***

## Instalacao e Execucao

Requer Python 3.8 ou superior sem necessidade de bibliotecas adicionais.

```bash
git clone https://github.com/TAVARDT-Brasil/heading-hierarchy-validator-br.git
cd heading-hierarchy-validator-br
python heading_hierarchy_validator.py https://empresa.com.br
```

Para gerar relatorio estruturado em formato JSON:

```bash
python heading_hierarchy_validator.py https://empresa.com.br -json
```

***

## Diagnostico Completo na Web

Para inspecao visual detalhada e arvore interativa de cabecalhos:

* **Validador de Hierarquia H1-H6 Oficial**
* **[Portal Corporativo TAVARDT Brasil](https://ag.tavardt.com/br/)**

***

## Consultoria em Estruturacao Semantica e Acessibilidade

Para suporte especializado em acessibilidade e conformidade com Diretrizes W3C WCAG e Boas Praticas de SEO Semantico Google, consulte os especialistas da **TAVARDT Brasil**.
