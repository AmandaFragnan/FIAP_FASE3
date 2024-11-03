# FIAP_FASE3

# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# FIAP Fase3_Cap10 Explorando SQL e tipos de dados na Oracle


## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/amanda-fragnan-b61537255/" target="_blank">Amanda Fragnan RM 555684 </a>
- <a href="https://www.linkedin.com/in/cunhaandre/" target="_blank">Andre Cunha RM 560648</a>
- <a href="https://www.linkedin.com/in/gabriellehalasc/" target="_blank">Gabrielle Halasc RM 560147</a> 
- <a href="https://www.linkedin.com/in/matheusconciani/" target="_blank">Matheus Conciani RM 559473</a> 

## 👩‍🏫 Professores:
### Tutor(a)
- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/">Lucas Gomes Moreira</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

## 📜 Descrição

### Projeto
Este projeto visa criar um modelo de banco de dados para armazenar e analisar informações sobre a produção agrícola e pecuária no Brasil, utilizando dados de órgãos como IBGE.

### Objetivo Geral
Aplicar os conceitos de modelagem de dados aprendidos nos capítulos 7, 8, 9 e 10 para criar um modelo de banco de dados que armazene e analise informações sobre a produção agrícola no Brasil.

### Funcionalidades da Solução
1. Armazenamento eficiente de dados sobre produção agrícola.
2. Análise detalhada da evolução de culturas e produtividade ao longo dos anos.

### Benefícios Esperados
- Melhor compreensão da produção agrícola.
- Facilitação na tomada de decisões para políticas agrícolas.

### Fonte dos Dados
Os dados utilizados para inserir as informações no banco foram obtidos do site do IBGE, especificamente da seção sobre produção agropecuária: IBGE - Produção Agropecuária.


## 📊 Dicionário de Dados
| Tabela             | Coluna         | Descrição                          |
|--------------------|----------------|------------------------------------|
| PRODUTO_AGRICOLA   | ID             | Identificador único do produto     |
|                    | NOME           | Nome do produto agrícola           |
|                    | UNIDADE        | Unidade de medida                  |
| PRODUTO_PECUARIO   | ID             | Identificador único do produto     |
|                    | NOME           | Nome do produto pecuário           |
|                    | UNIDADE        | Unidade de medida                  |
| PRODUCAO_AGRICOLA  | ID             | Identificador único da produção    |
|                    | PRODUTO_ID     | Identificador do produto agrícola  |
|                    | VALOR          | Valor da produção                  |
|                    | UNIDADE        | Unidade de medida                  |
| PRODUCAO_PECUARIA  | ID             | Identificador único da produção    |
|                    | PRODUTO_ID     | Identificador do produto pecuário  |
|                    | VALOR          | Valor da produção                  |
|                    | UNIDADE        | Unidade de medida                  |

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>CRIACAO_INSERCAO_DADOS.sql</b>: aqui estão os códigos SQL para criação das tabelas.

- <b>CONSULTAS_RELEVANTES_DADOS.sql</b>: aqui estão as consultas SQL solicitadas.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

- <b>assets</b>: aqui estão os arquivos relacionados a elementos não-estruturados deste repositório, como imagens.

## 🔧 Como executar o código

1. Clonar o repositório

Primeiro, faça o clone deste repositório localmente usando o Git:

git clone https://github.com/AmandaFragnan/FIAP_FASE3.git

2. Conectar ao banco de dados Oracle
   
Certifique-se de ter um banco de dados Oracle configurado e em execução. Conecte-se ao banco de dados usando uma ferramenta de sua escolha, como Developer ou qualquer outra ferramenta de gerenciamento de banco de dados Oracle.

3. Executar o script de criação e inserção de dados
   
Navegue até o diretório onde o arquivo CRIACAO_INSERCAO_DADOS.sql está localizado e execute o script para criar as tabelas e inserir os dados:


5. Executar as consultas SQL relevantes
   
Navegue até o diretório onde o arquivo CONSULTAS_RELEVANTES_DADOS.sql está localizado e execute o script para realizar as consultas solicitadas:

## Historico de lançamentos

- <b> 0.2.0 - 02/11/2024<b>

  
## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
