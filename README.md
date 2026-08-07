programador flash SUP Console
Tudo o que é apresentado aqui é feito por você em seu próprio perigo e risco.
Programador de memória flash paralelo simples

Construído sobre o acessível Arduino Mega 2560
Detalhes adicionais mínimos
Fácil de repetir
Oportunidades
Apagar, ler e escrever o chip de memória K5L2731CAA-D770 ou similares
Controle do processo de transferência de dados entre o computador e o programador
Controle do processo de gravação de dados no Flash
Indicação de luz do processo (Escrita, Leitura, Apagamento, Erro)
O comportamento do botão pode ser determinado (Através da fonte do firmware)
Você pode exibir as informações do processo no display do programador (Através do código fonte do firmware)
Alta velocidade: até 1Mbit/S (Você pode fazer mais alto, mas o desempenho do microcontrolador não permite aumentar a velocidade)
Instalação projeto
Python não inferior à versão 3.9.10 é necessário. Todas as operações são descritas para SO Windows com o GitBash instalado.

Deve ser realizada em nome do administrador.
Clonando um repositório com GIT:

git clone git@github.com:Promolife/sup_console_programmator.git
Vamos ao diretório do projeto

cd sup_console_programmator
Instale e ative o ambiente virtual

python -m venv venv
fonte venv/scripts/ativar
Atualizar pip e definir dependências

python - m pip install --atualizar pip
pip instalar pyserial
Prontinho! Pode começar a usá-lo.

