Práticas de Sistemas Operacionais

1. CONCEITO DE SISTEMA OPERACIONAL

O Sistema Operacional é uma camada de software intermediaria entre hardware e os programas utilizados pelo usuário;

Sistema operacional oculta a complexiade de um sistemas computacional, ou seja, funciona como uma interface entre usuário e computador.
  Estender a máquina: O SO cria uma abastração das instruções de máquina mais primitivas, permitindo que o programador programe de forma mais simples, protegendo os recursos;
  Gerenciar recursos: SO cria uma fila de impressão para que cada programa tenha seu tempo para imprimir/executar; ocorre com o gerenciamneto de memória; escalonamento de processos;

  Os Sistemas Operacionais podem ser classificados quanto a sua distribuição:
    Software livre: É aquele que segue as liberdades definidas pelo General Public License (da Free Software Foundation):
          Liberdade para executar o programa para qualquer propósito;
          Acesso ao código fonte e poder estudá-lo e adapta-lo;
          Liberdade de aperfeiçoar e distribuir cópias;
    Software proprietário: Possui um copyright, por meio desse direito autoral, o proprietario pode receber dinheiro; o software não é vendido, apenas licenças;

2. HARDWARE E SOFFTWARE

Hardware: Parte física do computador; placas diversas, processador, memória, cabinete...; existem os dispositivos de entrada, saída, entrada e saída, dispositivos de armazenamento e de processamento;
Software: Conjunto finito de instruções organizadas de forma lógica; processado pelo hardware; representação de algoritmos; 
              Firmware: Um tipo de software dedicado e com instruções específicas de entrada e saída; baixo nível; ponte entre hardware e o SO;
          Linguagem de alto nível: Linguagem que se aproxima mais da linguagem naturaç, mais fácil para a compreensão humana; fácil aprendizagem;
          (Node.js, Javascript, Java, Ruby, C#, Python...)
          Linguagem de baixo nível: mais rapidamente processada, pois se aproxima mais da linguagem da máquina; o objetivo dela é ser interpretada diretamente pelo hardware;

3. ESTRUTURA DE SISTEMAS OPERACIONAIS

O núcleo (kernel) do SO é constituído de um conjunto de rotinas, oferecidas comoserviços aos usuários, às suas aplicações e utilitários do sistema para gerenciamneto de recursos;
As System Calls são como uma porta de entrada para o acesso ao núcleo do sistema opeacional e a seus serviços; aqui se tem as chamadas APIs (Application Programming Interface);

4. ARQUITETURA DE SISTEMAS OPERACIOANAIS

Implatação do ambiente, compartilhamento de recursos e função do SO;
          Arquitetura Peer-to-Peer (P2P): Arqt. colaborativa, sem necessidade de manter um servidor dedicado; os clientes podem atuar como servidores; 
              Módulo Cliente do SO de Rede (SORC);
              Módulo Servidor do SO de Rede (SORS);
          Arquitetura Cliente-Servidor: Um único servidor pode garantir o funcionamneto da transferencia de informações; modelo que vincula vários dispositivos através de uma rede; o cliente solicita o servidor uma resposta e o servidor fornece; nesse modelo os dispositivos devem manter um SORC ou um SORS;
          Servirdor Dedicado x Servidor não Dedicado:
              Dedicado: O SO é instalado diretamente no hardware, sendo o próprio servidor da sua organização, contendo apenas seus dados;
              Não Dedicado: O servidor está "hospedado" em um ambiente compartilhado com outras organizações hospedadas e o SO é instalado sobre um servidor virtualizado;
          Sistemas Distribuídos: Compartilham recursos como arquivos, dispositivos de E/S (Entrada/Saída), memória e processador;

5. TIPOS DE SISTEMAS OPERACIONAIS


              
