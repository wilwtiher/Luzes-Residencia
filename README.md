# Aluno: Wilton Lacerda Silva Júnior
## Matrícula: TIC370100193
# Video explicativo: https://youtu.be/_hPSMVokPAA
# Automatização Luzes Residência
O objetivo do projeto é desenvolver utilizando a placa BitDogLab e sua acessibilidade à internet uma solução para luzes de residências.
## Funcionalidades

- **Matriz de LEDs**
   - A matriz de LEDs simulará as luzes de uma residência.
- **Conexão Wi-Fi**
   - A conexão Wi-Fi servirá para fazer acesso a placa vida rede, verificar as luzes e fazer envio de informações para a placa.

# Requisitos
## Hardware:

- Raspberry Pi Pico W.
- 1 matriz de led 5x5 na porta 7

## Software:

- Ambiente de desenvolvimento VS Code com extensão Pico SDK.

# Instruções de uso
## Configure o ambiente:
- Certifique-se de que o Pico SDK está instalado e configurado no VS Code.
- Compile o código utilizando a extensão do Pico SDK.
## Teste:
- Utilize a placa BitDogLab para o teste. Caso não tenha, conecte os hardwares informados acima nos pinos correspondentes.
- Configure a rede Wi-Fi a ser utilizada no código.

# Explicação do projeto:
## Contém:
- O projeto terá uma forma de comunicação direta com o usuário, o site via Wi-Fi.
- Também contará com uma saída visual na placa, a matriz de LEDs.

## Funcionalidades:
- O programa mostrará uma representação de luzes da residência na matriz de led.
- O programa acessara a internet via rede local.
- O site criado na rede local ajudará a controlar as luzes da residência.
- O usuário poderá passar comandos para o microcontrolador via site.
