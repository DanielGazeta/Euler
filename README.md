# Euler
Compilar e Executar a solução para o Euler - Problema 11:

Baixar o programa Py2Exe e instalar na máquina windows, escolher uma versão compatível com a versão do Python instalada na máquina.

Para compilar e executar o programa siga os seguintes passos:

(1) Baixe o arquivo Euler11.py que está no repositório publico: DanielGazeta/Euler.
(2) Crie um outro arquivo *.py, com o nome “setup.py” com a seguinte estrutura:

  from distutils.core import setup
  import py2exe

  setup(console=['Euler11.py'])

(3) Abra o Prompt de comando do Windows ( Winkey + R > cmd > [ENTER].)
(4) Vá para o diretório onde estão os scripts Euler11.py e setup.py.
(5) Execute o comando: python setup.py py2exe.
Onde, python é o comando que chama o programa Python, setup.py indica que o Python tem que executá-lo e py2exe invoca o programa que faz a conversão seguindo as instruções contidas no setup.py.
(6) Pressione Enter, se tudo der certo, dois novos diretórios vão surgir no diretório onde os scripts estavam inicialmente. Um chamado build e outro chamado dist.

O dist conterá o executável. Ele terá o mesmo nome do script principal, porém agora será *.exe. 
Para executar, basta clicar duas vezes sob o arquivo ou navegar até a página via linha de comando e executar o programa por lá mesmo. 

