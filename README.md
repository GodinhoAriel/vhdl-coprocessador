# vhdl-coprocessador
Projeto de Organização e Arquitetura de Computadores 2 - implementação de um coprocessador de sin/cos

## Como simular o projeto no vivado
Para testarmos o código e rodar as simulações utilizamos a versão 2018.2 do Vivado

Inicialmente precisamos criamos um projeto no Vivado. Criamos um projeto do tipo "RTL Project", adicionamos os arquivos .vhd da pasta mipssingle e configuramos a "Target language" e "Simulator Language" como "VHDL". A placa usada foi a "xc7a100tcsg324-3".

Após o setup do projeto, configuramos os Types dos arquivos para VHDL 2008.

Para simular o projeto, basta clicar em Run Simulation > Run Behavioral Simulation. No nosso caso usamos o ModelSim para simular o projeto, porém é possivel simular pelo próprio Vivado.
