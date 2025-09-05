# Rede Neural

### Nesse projeto será possível fazer a análise de um Documento PDF.

A análise atualmente se encontra apenas com automações, a adaptação para leitura de documentos com Rede Neural será implementada logo após uma resposta positiva sobre análises de uma quantidade considerável de alimentação de dados de Certificados.

Em primeira instância, a leitura e análise será realizada apenas com PDF de Certificados (devido ao treinamento através desse tipo de dados). Acredito que funcione para outros tipos de Documentos também, mas como não é o foco principal do Projeto (por hora), recomendo o uso para análises relacionadas.

## Execução

1. Faça download dos arquivos e adicione uma lista de documentos PDF
2. Instale algumas extensões para execução do Python
   - hashlib
   - re
   - PdfReader
   - fuzz
   - unidecode
   - PyMuPDF
   - cv2
   - numpy
   - decode
   - tensorflow
   - train_test_split
   - LabelEncoder
   - Tokenizer
   - pad_sequences
4. Execute a compilação do Python

## Funcionalidades

Ao executar o projeto, o mesmo listará:
1. Os dados extraídos do QRCode (caso exista no documento)
2. Texto Extraído do corpo documento
3. Texto Normalizado (sem acentos ou caracter especial)
4. Quantidade de horas encontradas (caso exista no documento)
5. Extração dos dados do 2º Documento
6. Resultado sobre possível duplicidade

## Licença

  MIT License
