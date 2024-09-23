# Sumário de Projetos 42

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTRzWI0PaYpzAqfXCb6D1alo6SKDdJagXJMVw&s"  alt="42 Luanda" align="right" />
_Escola 42 - "**Aprendizado inovador**"_
<br>
<div>
    <ul>
      <li><a href="#solong">Solong</a></li>
      <li><a href="#minitalk">Minitalk</a></li>
      <li><a href="#fdf">Fdf</a></li>
      <li><a href="#philosophers">Philosophers</a></li>
      <li><a href="#minishell">Minishell</a></li>
    </ul>
  </div>

<details>
  <summary>Solong</summary>
  
  O projeto **Solong** é um jogo em 2D onde o objetivo é escapar de um labirinto. Ele utiliza a biblioteca gráfica MinilibX para criar o ambiente do jogo. O jogador controla um personagem em um mapa que precisa coletar todos os itens e encontrar a saída.

  ### Regras:
  - Utilizar a **MinilibX** para renderização.
  - O mapa deve ser lido a partir de um arquivo `.ber`.
  - O jogador pode mover-se para cima, baixo, esquerda e direita.
  - Inimigos podem ser implementados para dificultar a saída.
  - Deve ter uma contagem de movimentos visível na tela.

</details>

<details>
  <summary>Minitalk</summary>
  
  O **Minitalk** é um projeto de comunicação entre processos utilizando sinais UNIX. Ele ensina como utilizar sinais para enviar e receber informações entre processos.

  ### Regras:
  - Criar um **servidor** e um **cliente**.
  - O cliente envia uma string para o servidor utilizando os sinais `SIGUSR1` e `SIGUSR2`.
  - O servidor exibe a string recebida.
  - O projeto deve garantir a integridade dos dados enviados.
  - Implementação de verificação de erros é necessária.

</details>

<details>
  <summary>Fdf</summary>
  
  O **Fdf** é um projeto que transforma um mapa 2D em uma visualização 3D utilizando a biblioteca MinilibX. É um projeto introdutório à manipulação gráfica e projeções isométricas.

  ### Regras:
  - O mapa é representado por coordenadas z em um arquivo `.fdf`.
  - O projeto deve exibir o mapa em uma projeção isométrica.
  - Deve ser possível **rotacionar**, **escalar** e **mover** o mapa.
  - Utilização de **cores** para representar as diferentes alturas.

</details>

<details>
  <summary>Philosophers</summary>
  
  O projeto **Philosophers** aborda o problema clássico dos filósofos comensais. Esse problema simula um cenário de concorrência entre processos e gerenciamento de threads.

  ### Regras:
  - Implementar o problema dos filósofos comensais.
  - Cada filósofo deve alternar entre três estados: **pensar**, **comer**, **dormir**.
  - Utilizar **threads** e **mutexes** para resolver o problema de concorrência.
  - Evitar **deadlocks** e **race conditions**.
  - O tempo de vida dos filósofos deve ser controlado com precisão.

</details>

<details>
  <summary>Minishell</summary>
  
  O **Minishell** é um projeto onde você implementa seu próprio shell UNIX. Ele ensina sobre processos, sinais e execução de comandos.

  ### Regras:
  - Implementar um shell simples que suporte os comandos básicos do UNIX.
  - Deve suportar **redirecionamentos** (>, <) e **pipes** (|).
  - Implementar suporte a variáveis de ambiente.
  - Tratar **sinais** como `Ctrl+C`, `Ctrl+D` e `Ctrl+\`.
  - Suporte a execução de comandos **builtin** como `cd`, `echo`, `exit`.

</details>

---

Este sumário oferece uma visão geral das regras e funcionalidades exigidas em cada projeto. Para mais detalhes, consulte a documentação oficial da escola 42.
