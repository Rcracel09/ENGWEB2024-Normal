# Teste 2024

## Passos para importação dos dados

Converter para json um conversor online
Criar um arquivo `dataset.json` com o conteúdo do json
O id passa a ser`_id`
Correr `converter.py` para resolver formato do preço.
Executar o container


### Resultado

```bash
mongo-seed-1  | 2024-05-16T13:15:30.299+0000    36377 document(s) imported successfully. 0 document(s) failed to import.


## Alterações

No `GET /contratos?entidade=EEEE` a entidade fosse o NIPC da empresa.

## Testes postman

Podem ser encontrados no arquivo `ex1/Testes.postman_collection.json`

## Resultados

No `http://localhost:16001` pode ser encontrada a tabela pedida com o **número de contratos** na base de dados.