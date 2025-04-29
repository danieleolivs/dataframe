# 📚 Base de Dados | Acórdãos + Decisões Terminativas

## 1. Introdução
Espelho de acórdãos e decisões terminativas de processos disponivilizados pelo STJ (Superior Tribunal de Justiça)

## 2. Links importantes
- **Fonte dos dados**: [Dados do STJ](https://dadosabertos.web.stj.jus.br/dataset/)
- **Link do csv dos dados**: [Dados espelhos de acórdãos em CSV](https://drive.google.com/file/d/1DuB82M8c0uWC6JTvquwDg97n5j0RaWFz/view?usp=sharing)
- **Link do csv dos dados filtrados da ANATEL**: [Dados espelhos de acórdãos em CSV](https://drive.google.com/file/d/1pnQ_JF0Noyp2hj7r0AP0ZSLRbXgNUOVO/view?usp=sharing)

## 3. Dicionário - espelhos de acórdãos
| Campo                   | Nome extenso                          | Descrição                                                                                                                                                  |
|-------------------------|----------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| id                      | ID                                     | Código identificador do acórdão na base de Jurisprudência                                                                                                  |
| numeroProcesso          | Número do Processo no STJ              | Número do processo autuado no STJ                                                                                                                           |
| numeroRegistro          | Número de Registro no STJ              | Número de registro do processo autuado no STJ                                                                                                               |
| siglaClasse             | Classe do processo - Sigla             | Sigla da classe processual padronizada conforme autuação no STJ.                                                                                           |
| descricaoClasse         | Classe do processo - Por extenso       | Nome por extenso da classe processual padronizada conforme autuação no STJ.                                                                                |
| nomeOrgaoJulgador       | Órgão Julgador                         | Órgão colegiado responsável pelo julgamento do processo.                                                                                                    |
| ministroRelator         | Ministro Relator                       | Ministro responsável pela relatoria do processo ou, quando vencido, do Ministro responsável pela relatoria do acórdão.                                     |
| ementa                  | Ementa                                 | Resumo do conteúdo da decisão, elaborado pelo Ministro Relator ou, quando vencido, pelo Ministro Relator do Acórdão.                                      |
| tipoDeDecisao           | Tipo de decisão                        | Decisão judicial proferida por magistrado singular (decisão monocrática) ou por colegiado de julgadores (acórdão).                                        |
| dataDecisao             | Data do julgamento                     | Data da sessão de julgamento em que o processo foi decidido.                                                                                               |
| decisao                 | Acórdão                                | Resultado final do julgamento, com informações sobre a votação, ausências, sustentações orais e tese firmada em demanda repetitiva.                        |
| jurisprudenciaCitada    | Jurisprudência citada                  | Lista de decisões, informativos e repositórios jurisprudenciais citados como fundamentação, com links para acesso.                                         |
| notas                   | Notas                                  | Índice de assuntos relevantes e alterações de acórdãos aplicáveis à consulta jurisprudencial.                                                              |
| informacoesComplementares| Informações Complementares à Ementa  | Informações extraídas do inteiro teor sobre teses decididas que não constam da ementa.                                                                     |
| termosAuxiliares        | Termos Auxiliares à Pesquisa           | Termos alternativos baseados em sinonímias do Tesauro Jurídico do STJ.                                                                                     |
| teseJuridica            | Tese Jurídica                          | Tese firmada em sede de Precedentes Qualificados.                                                                                                          |
| tema                    | Tema                                   | Número do Tema Repetitivo conforme estabelecido pelo Núcleo de Gestão de Precedentes.                                                                      |
| referenciasLegislativas | Referência Legislativa                 | Lista de atos normativos que espelham as teses apreciadas e os fundamentos do acórdão.                                                                     |
| acordaosSimilares       | Acórdãos Similares                     | Lista de acórdãos julgados pelo mesmo relator, com teses similares, com links para consulta processual e inteiro teor.                                     |
| dataPublicacao          | Data de publicação/Fonte               | Data em que a decisão foi publicada e a fonte de sua publicação.                                                                                           |
