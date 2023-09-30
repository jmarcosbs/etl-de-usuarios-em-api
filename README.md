# Alteração de usuários de API com ETL


**Etapas**

1. Cadastro de usuários na API pelo Swagger
2. IDs de referência obtidos a partir de uma planilha simples, em formato CSV ('SDW2023.csv'), com uma lista de IDs de usuários criados:
  ```
  UserID
  1
  2
  3
  4
  5
  ```
2. Consumo do endpoint `GET https://sdw-2023-prd.up.railway.app/users/{id}` (API da Santander Dev Week 2023) para obter os dados de cada cliente.
3. A partir dos dados dos clientes foi disponibilizada a possibilidade de alteração de usuários através de inputs
4. Depois de tudo alterado foi feita uma `PUT https://sdw-2023-prd.up.railway.app/users/{id}`.


![etl-usuarios-python](https://github.com/jmarcosbs/etl-de-usuarios-em-api/assets/137966714/8b5d87af-2c45-4bd5-a775-965bded7738f)
