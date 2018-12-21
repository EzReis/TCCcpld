Aplicação de hardware programável em circuito de tempo morto

# Introdução:
## Motivação
- Circuito de implementação de tempo morto utilizado em bancadas é pouco flexível e possui muitos componentes. As bancadas tem como fim testar configurações de inversores de potência.
- Adquirir expertise em desenvolvimento de projeto em hardware programável, a fim de possibilitar a utilização futura dessa tecnologia em aplicações relacionadas, no DEE, como aquelas onde há demanda de flexibilidade de hardware ou demanda por uma resposta mais rápida que a fornecida por sistemas microcontrolados.

## Objetivos
 - Substituir um circuito digital, com diversos componentes, por um circuito de hardware programável.
 - Implementar, em hardware programável, uma proteção para a montagem do inversor, quando a indicação de erro ocorrer ou o usuário indicar necessidade de finalizar operação.
 - Produzir uma placa de gravação e de testes para o dispositivo utilizado.

Montagens de inversores de potência se utilizam de chaves de potência que necessitam de cuidados ao serem comandadas. Para comando destas chaves se faz uso de sinais de PWM e, quando em configuração a formar braços, as chaves de um mesmo braço não devem ser acionadas de modo a causar um curtocircuito na fonte. A forma de se impedir que isso ocorra é a implementação de um sinal de tempo morto no sinal de acionamento,isto é feito ao adicionar um atraso específico nos sinais de PWM. O atraso necessário é de cerca de um microssegundo e considerado difícil de atingir por implementações que se utilizem de microcontrolador. Montagens no laboratório do GEPAE se utilizaram de implementações em hardware para obtenção deste atraso, porém esses circuitos se utilizam de uma quantidade considerável de componentes e são bem inflexíveis para alterações. Com essa motivação, aliada com a experiência alcançada ao se utilizar desta tecnologia, decidiu-se a implementação destes circuitos através de hardware programável.

# Revisão Bibliográfica
## Hardware Programável
### Dispositivos
## Languagem de descrição de hardware
## Conceitos de eletrônica de potência


# Desenvolvimento
## O ambiente de desenvolvimento
## O contexto da aplicação 
## O desenvolvimento da placa de gravação e de testes
## Implementação em hardware programável
### A geração dos sinais
### A implementação do tempo morto
### A implementação da proteção
### A integração dos componentes implementados
## Testes
## Utilização

# Conclusão e Trabalhos Futuros
## Conclusão

## Trabalhos Futuros

# Referências

<!-- -->
