# SEGUNDA PROVA DO MÓDULO 8 - 15/12/2023

# INFORMAÇÕES DO ALUNO  
Aluno | Curso | Módulo | Turma
:---: | :---: | :---: | :---:
Antonio Angelo Teixeira | Engenharia da Computação | 8 | 2

<br>

# DESCRIÇÃO DA ATIVIDADE


A proposta da parte prática da segunda prova do módulo 8 é a implementação de um sst simples por meio de uma interface CLI. Esse sistema tem por objetivo auxiliar pessoas com dificuldades na fala a comunicarem-se e conseguirem expressar suas ideias de forma clara. O sistema é baseado em um LLM ao qual é submetida toda frase disponibilizada pelo usuário por meio de uma terminal de forma contínua.Dessa forma, o usuário disponibiliza seu texto, o sistema processa, quebra em chunks e grava essa informção em um arquivo de áudio, que por fim é lido e reproduzido.

Dessa forma, optei por realizar essa atividade usando o LLM ljspeech, modelo de linguagem responsável pelo tranformação de texto em fala. Esse modelo para esse prova pode ser suficiente, porém, como sugestão de melhoria, indico ao INTELI disponibilizar uma GPU que aguente o bark e mais tempo para integrar com uma interface gradio.

# COMO EXECUTAR O PROJETO

## INSTALAR DEPENDÊNCIAS:

Instale as dependências necessárias executando o seguinte comando:

```bash
pip install -r requirements.txt
```

### Execução
Depois de completar a instalação, ainda no mesmo terminal execute o seguinte comando:

```bash
python tts_p2.py
```

# RESPOSTA ESPERADA DO SISTEMA

O funcionamento do sistema consiste em uma entrada do usuário em forma de texto, pro sua vez, o sistema submete ao tts, reproduz o áudio e espera o próximo comando do usuário.

A resposta esperada do sistema é a geração de um arquivo .wav, um arquivo de áudio, que posteriormente é lido e reproduzido. 

