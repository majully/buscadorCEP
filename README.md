# Desafio Consumir Dados da API ViaCEP


Projeto implementado durante curso Alura posto como desafio. Aplicação para consultar um endereço a partir de um CEP e salvar as informações em um arquivo json.


## 📮 Projeto Busca CEP

- Classe que representa um endereço (cep, uf, cidade, bairro, logradouro e complemento);
- Classe que consulta a API *ViaCEP* para buscar um endereço a partir de um cep (exemplo: https://viacep.com.br/ws/04101300/json);
- Classe que cria um arquivo json contendo os dados de um objeto `Endereco`;
- Classe com método main que deve solicitar ao usuário que informe um CEP e na sequencia utilizar as classes para consultar a api ViaCEP e salvar os dados do endereço em um arquivo json.

## Observações:
- Utilizado a biblioteca GSon para converter o JSON devolvido pela API ViaCEP em um objeto `Endereco`;
- Utilizado a biblioteca GSon para salvar um objeto `Endereco` em um arquivo .json;
- Ao fazer a busca é gerado um arquivo com o nome do cep informado (exemplo: `04101300.json`);

![viaCepAPI1](https://github.com/user-attachments/assets/090765c2-d295-421b-9870-ac7907a7d614)

![viaCepAPI2](https://github.com/user-attachments/assets/aeb9c14f-3a61-41e5-90ab-4ea3167fd6ce)
