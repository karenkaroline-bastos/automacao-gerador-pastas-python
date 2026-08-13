# 📁 Gerador Automático de Estrutura de Pastas

Aplicação desktop desenvolvida em Python para automatizar a criação
de estruturas hierárquicas de pastas a partir de configurações
definidas em uma planilha Excel.

## 🎯 Objetivo

Automatizar um processo manual de criação de pastas, reduzindo
tempo operacional, erros de digitação e inconsistências na
estrutura de armazenamento de documentos.

## 💡 Problema

A criação manual de estruturas de pastas com diversos níveis
pode ser repetitiva e suscetível a erros.

A solução permite definir a estrutura diretamente em uma planilha
Excel e gerar automaticamente todas as pastas necessárias.

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- OpenPyXL
- Tkinter
- PyInstaller
- Excel

## ⚙️ Funcionalidades

- Seleção de arquivo Excel
- Seleção da pasta de destino
- Leitura da aba Configuração
- Validação das informações
- Geração automática da estrutura
- Simulação antes da criação
- Criação das pastas
- Verificação de pastas existentes
- Registro de log
- Salvamento do log
- Interface gráfica
- Geração de arquivo executável (.exe)

## 📊 Exemplo de estrutura

2027/
└── Centro/
    └── Ensino Médio/
        └── Etapa 1/
                └── 1 SERIE A/
                    ├── Digitalizado/
                    └── Provas Corrigidas/

## 🔄 Fluxo da aplicação

Excel
↓
Configuração
↓
Validação
↓
Geração da estrutura
↓
Simulação
↓
Confirmação
↓
Criação das pastas
↓
Log

## 🚀 Como executar

Instale as dependências:

pip install -r requirements.txt

Execute:

python gerador_pastas.py

## 📦 Executável

Também foi gerado um executável utilizando PyInstaller.

Gerador_Automatico_de_Pastas.exe

## 📚 Aprendizados

Este projeto permitiu praticar:

- Manipulação de arquivos Excel
- Pandas
- Automação de processos
- Manipulação de diretórios
- Tratamento de exceções
- Interface gráfica com Tkinter
- Validação de dados
- Criação de logs
- Empacotamento de aplicações Python

## 👩‍💻 Autora

Karen Karoline Bastos
