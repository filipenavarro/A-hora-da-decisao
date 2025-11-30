# A-hora-da-decisao
Tradução do livro "The hour of decision" de Oswald Spengler (A partir da tradução inglesa de Charles Francis Atkinson) para Português Brasileiro.

No conteúdo você vai encontrar 4 arquivos:

- Ocr_original.txt (Ocr original do arquivo, cheio de erros ortográficos)
- Ocr_corrigido.txt (Ocr corrigido com LLM)
- Traducao_final.txt (Tradução do ocr corrigido com LLM)
- Quality_report.txt (Relatório de qualidade, fala sobre os detalhes na tradução de cada página)

Para o ocr do livro foi utilizado pdf2image, pré-processamento e PaddleOCR (gpu mode).

Para a tradução e correção do ocr foi usado um script python agentic (multiple workers), com Grok 4.1 Fast, o script corrige o ocr e traduz simultaneamente com as tarefas dividas em multiplos agents para velocidade.

Obs: O texto contém problemas de numeração das páginas e não está perfeita a tradução (exige correção), porém está o mais fiel o possivel a obra original.

Fonte do livro: https://ia601400.us.archive.org/34/items/in.ernet.dli.2015.503389/2015.503389.hour-of.pdf
