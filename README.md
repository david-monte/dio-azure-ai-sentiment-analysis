# Transcrição de áudio e Análise de Sentimentos com a IA da Azure 

### Entrega do Desafio de Projeto do Bootcamp Randstat 2025 na DIO.

## Descrição do Desafio
O Laboratório teve como objetivo praticar e aprofundar o uso das ferramentas **Azure Speech Studio** e **Language Studio**, focando na análise de fala e linguagem natural. O objetivo foi desenvolver habilidades práticas na criação de soluções baseadas em inteligência artificial voltadas para voz e linguagem utilizando os serviços de IA da Azure.

## Etapas do Projeto

1. Criação de uma conta no Microsoft Azure;

2. Alocação de serviços para serem utilizados nos ambientes Speech Studio e Language Studio da Azure;

3. No **Speech Studio** foi configurado o recurso previamente alocado no Azure e em seguida foi escolhida a tarefa de `Conversão de Fala em Texto em Tempo Real` e realizado o upload de um arquivo de áudio para posterior transcrição. O arquivo de áudio escolhido encontra-se disponível no seguinte endereço: https://downloads.bbc.co.uk/learningenglish/features/tews/250721_tews_up_to_my_eyes_in__download.mp3 cujo idioma é o inglês. Outros idiomas podem ser selecionados na interface do recurso. Os dados de saída são em dois formatos texto e json:
    * No formato texto, apenas o texto simples da transcrição é apresentado;
    * No formato json também são trazidas informações adicionais referentes ao áudio fornecido e ao processo de conversão;

4. No **Language Studio** foi escolhida a tarefa de `Análise de Sentimentos e Opiniões` e na interface do recurso foi escolhido o idioma do texto para análise, seleciocionado o recurso previamente alocado no Azure e fornecido um texto exemplo. Os resultados de saída são listados por sentença e disponibilizados em dois formatos:
    * Informativo em termos percentuais dentre três classes: positivo, neutro e negativo;
    * Documento json contendo informações adicionais relativas ao texto e a análise de sentimentos.