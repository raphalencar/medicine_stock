# Estoque dos medicamentos nas farmácias da Rede Municipal de Saúde do Recife
Este projeto tem como propósito principal servir de base para estudo de séries temporais. Nele, utilizo os dados disponíveis em http://dados.recife.pe.gov.br/pt_BR/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude

## Descrição da base de dados
Esse conjunto de dados apresenta o estoque de medicamentos disponíveis nas farmácias da rede municipal de saúde do Recife. São os medicamentos contidos na Relação Municipal de Medicamentos Essenciais (REMUME) e que são ofertados gratuitamente para a população recifense, conforme as diretrizes do SUS (Sistema Único de Saúde). A atualização do estoque dos medicamentos nas farmácias é realizada com frequência diária.

### Dados
`Distrito 1`: http://dados.recife.pe.gov.br/pt_BR/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude/resource/e976dc6a-3e64-4386-b4c0-850852e7a21e

`Distrito 2`: http://dados.recife.pe.gov.br/pt_BR/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude/resource/4be8f291-38e5-4a35-9bdc-07b10f54a05d

`Distrito 3`: http://dados.recife.pe.gov.br/pt_BR/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude/resource/a7a966de-fa73-47ed-a87e-a53d336038d0

`Distrito 4`: http://dados.recife.pe.gov.br/pt_BR/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude/resource/eaa007ad-faed-477a-a085-c84bddb47224

`Distrito 5`: http://dados.recife.pe.gov.br/pt_BR/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude/resource/05e529b2-3b1c-4b7f-a0f0-31abc9602a68

`Distrito 6`: http://dados.recife.pe.gov.br/pt_BR/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude/resource/a83090c7-9dfa-4584-afd6-9da301b095eb

`Distrito 7`: http://dados.recife.pe.gov.br/pt_BR/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude/resource/a075f4fe-cf7c-4af6-9b73-1f07f9936de4

`Distrito 8`: http://dados.recife.pe.gov.br/pt_BR/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude/resource/99eb6b09-20dd-4da8-b9c4-3f696b19fa79

### Dicionário de dados
```
{
  "metadados": {
    "cabecalho": {
      "titulo": "Estoque dos medicamentos nas farmácias da Rede Municipal de Saúde",
      "descricao": "Esse conjunto de dados apresenta o estoque de medicamentos disponíveis nas farmácias da rede   municipal de saúde do Recife",
      "categoria_vcge": "http://vocab.e.gov.br/id/governo#medicamentos-e-aparelhos",
      "fonte_dados": "http://dados.recife.pe.gov.br",
      "licenca": "Open Database License (ODbL)",
      "responsavel_dados": "Secretaria de Saúde",
      "responsavel_disponibilizar": "Emprel",
      "frequencia_atualizacao": "Semestral",
      "endereco_dataset": "http://dados.recife.pe.gov.br/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude",
      "status": "ativo",
      "endereco_dataset_substituto": "",
      "granularidade": "Por unidade de saúde, medicamento",
      "etiquetas": "Saúde, Medicamentos, farmácia, estoque,sus,datasus"
    },
    "recursos": [
      {
        "identificador": "http://dados.recife.pe.gov.br/dataset/estoque-dos-medicamentos-nas-farmacias-da-rede-municipal-de-saude/resource/ecd36a57-e9f2-4ef9-a3bb-0cf2f0c02335",
        "titulo": "Estoque Diário de médicamentos nas farmácias",
        "formato": "csv",
        "descricao": "Esse recurso apresenta o estoque dos medicamentos nas farmácias da Rede Municipal de Saúde (Lei 14.654 de 23/08/2023)"
      }
    ],
    "campos": [
      {
        "codigo": "unidade",
        "descricao": "Nome da unidade de saúde",
        "tipo": "Char",
        "tamanho": 100,
        "valores_permitidos": ""
      },
      {
        "codigo": "tipo_produto",
        "descricao": "Tipo do produto em estoque",
        "tipo": "Char",
        "tamanho": 50,
        "valores_permitidos": ""
      },
      {
        "codigo": "codigo_produto",
        "descricao": "Vacina recebida",
        "tipo": "Num",
        "tamanho": 8,
        "valores_permitidos": ""
      },
      {
        "codigo": "produto",
        "descricao": "Nome do medicamento",
        "tipo": "Char",
        "tamanho": 250,
        "valores_permitidos": ""
      },
      {
        "codigo": "apresentação",
        "descricao": "Forma de apresentação do medicamento",
        "tipo": "Char",
        "tamanho": 55,
        "valores_permitidos": ""
      },
      {
        "codigo": "cadum",
        "descricao": "Código do medicamento no CADUM (Cadastro de Materiais Municipal)",
        "tipo": "Num",
        "tamanho": 8,
        "valores_permitidos": ""
      },
      {
        "codigo": "bairro",
        "descricao": "Bairro da Unidade de Saúde",
        "tipo": "Char",
        "tamanho": 100,
        "valores_permitidos": ""
      },
      {
        "codigo": "distrito",
        "descricao": "Distrito da Unidade de Saúde",
        "tipo": "Num",
        "tamanho": 2,
        "valores_permitidos": ""
      },
      {
        "codigo": "qtd",
        "descricao": "Quantidade do medicamento em estoque na Unidade de Saúde",
        "tipo": "Num",
        "tamanho": 8,
        "valores_permitidos": ""
      },
      {
        "codigo": "classe_terapeutica",
        "descricao": "Classe Terapêutica do Medicamento",
        "tipo": "Char",
        "tamanho": 100,
        "valores_permitidos": ""
      },
      {
        "codigo": "data_carga",
        "descricao": "Data da atualização das informações, inclusive do estoque",
        "tipo": "Date",
        "tamanho": "",
        "valores_permitidos": ""
      },
      {
        "codigo": "remume",
        "descricao": "Indica se o medicamento faz parte da RElação MUnicipal de Medicamentos Essenciais (REMUME)",
        "tipo": "char",
        "tamanho": "1",
        "valores_permitidos": ""
      }
    ]
  }
}
```

## Relação dos Distritos Sanitários da cidade do Recife

`DS I`- Tem a sua sede localizada na Rua Mário Domingues,70- Boa Vista (por trás do hospital Memorial São José). Abrange os Bairros: 1-Boa Vista; 2-Cabamga; 3-Coelhos; 4-Ilha do Leite; 5-Ilha Joana Bezerra;6-Paissandu; 7- Recife; 8-São José; 9-Santo Amaro; 10- Santo Antônio;12-Soledade.

`DS II`- Tem a sua sede localizada na Rua Antônio Rangel,203-Encruzilhada.Abrange os Bairros: 1-Alto Santa Terezinha;2-Água Fria;3-Arruda;4-Beberibe;5-Bomba do Hemetério;6-Campo Grande;7-Cajueiro;8-Campina do Barreto;9-Dois Unidos;10-Fundão;11-Hipódromo;12-Linha do Tiro;13-Ponto de Parada;14-Porto da Madeira;15-Peixinhos;16-Rosarinho;17-Torreão.

`DS III` – Tem sua sede  localizada Rua Xavante,205- Casa Amarela abrange os bairros:1-Aflitos;2-Alto do Mandú;3-Apipucos;4-Casa Amarela;5-Casa Forte;6-Derby;7-Dois Irmãos;8-Espinheiro;9-Graças;11-Monteiro;12-Poço;13-Santana;14-Sitio dos Pintos;15-Tamarineira.

`DS IV` -Tem a sua sede localizada na Rua Cantora Clara Nunes S/N- Torre. Abrange os Bairros: 1-Caxangá;2-Cidade Universitária;3-Varzea;4-Cordeiro;5-Engenho do Meio;6-Ilha do retiro;7-Iputinga;8-Madalena;9- Prado; 10-Torre;11-Torrões;12-Várzea;13-Zumbi.

`DS V` - Tem a sua sede localizada na Rua Emília Torreão,135- Afogados. Abrange os Bairros :1-Afogados;2-Areias;3-Barro;4-Bongi;5-Caçote;6-Coqueiral;7-Curado;8-Estância;9-Jardim São Paulo;10-Jiquiá;11- Mangueira;12- Mustardinha;13-Sancho;14-San Martin;15-Tejipió;16-Totó.

`DS VI` - Tem a sua sede localizada na Rua Jean Emile Favre,1636- IPSEP. Abrange os Bairros:1-Boa Viagem;2-Brasília Teimosa;3-Imbiribeira;4-IPSEP;5-Pina.

`DS VII` - Tem a sua sede na Rua Córrego do Euclides, (Upinha Mª Rita), Córrego do Euclides. Abrange os bairros:1-Alto José Bonifácio;2-Alto José do Pinho;3-Brejo da Guabiraba;4-Córrego do Jenipapo;5-Guabiraba;6-Macaxeira;7-Mangabeira;8-Morro da Conceição;9-Nova Descoberta;10-Passarinho;11-Pau Ferro;12-Vasco da Gama.

`DS VIII` - Tem a sua sede localizada na Rua Escola de Sagres, Nº 22 Jordão Abrange os Bairros:1-Cohab;2-Ibura;3-Jordão.