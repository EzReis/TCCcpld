Aplicação de hardware programável em um conversor de potência

# Introdução:
## Motivação
- Circuito de implementação de tempo morto utilizado em bancadas é pouco flexível e possui muitos componentes. 
- Adquirir expertise em desenvolvimento de projeto em hardware programável, a fim de possibilitar a utilização futura dessa tecnologia em aplicações relacionadas, no DEE, como aquelas onde há demanda de flexibilidade de hardware ou demanda por uma resposta mais rápida que a fornecida por sistemas microcontrolados.

## Objetivo(s)
### Geral:
 - Aplicar a tecnologia de hardware programável em um conversor de potência

### Específicos:
 - Descrever a operação do inversor e técnica de chaveamento proposta;
 - Identificar a responsabilidade do dispositivo de lógica programável;
 - Produzir uma placa de gravação e de testes para o dispositivo utilizado;
 - Definir a estrutura modular do código;  
 - Implementar e testar módulos de código;
 - Integrar módulos;
 - Testar integração dos módulos no código;
 - Produzir placa final;
 - Testar integração com placa final;
 - Testar operação completa.

 

Montagens de inversores de potência se utilizam de chaves que necessitam de cuidados ao serem comandadas, além disso, a forma utilizada para o seu comando é feita através do uso de sinais de PWM. Quando as chaves formam braços, como na configuração do conversor do projeto envolvido, deve-se garantir que as chaves de um mesmo braço não acabem fechadas ao mesmo tempo, o que causaria um curtocircuito na fonte. Este acionamento simultâneo das chaves pode ocorrer por características inerentes a construção da chave, implicando a diferença entre os tempos de abertura e fechamento. A forma de impedir que o curtocircuito ocorra, devido a assimetria entre os tempos, é a implementação de um tempo morto no sinal de acionamento. O tempo morto é feito ao adicionar um atraso específico nos sinais de PWM, que é de cerca de um microssegundo e considerado difícil de atingir por implementações que se utilizam de microcontrolador. Montagens de conversores semelhantes, realizadas no laboratório onde se desenvolveu este trabalho, se utilizaram de implementações em hardware, com componentes discretos, para obtenção do tempo morto, porém, esses circuitos necessitaram de uma quantidade considerável de componentes e são pouco flexíveis para alterações. 
Este trabalho parte com a premissa que dispositivos de hardware programável possuem capacidade para implementação do tempo morto necessário, além de permitir, adicionalmente, a implementação de proteção e de geração de sinais necessários para o conversor em questão. Portanto, este trabalho propõe verificar a utilização de hardware programável no conversor envolvido, de forma que, ao final, o conversor esteja operante e sua parte lógica seja mais flexível, em relação a montagens semelhantes anteriores. Para tanto, o projeto passa por uma sequência de passos, que começa ao conhecer a operação do inversor proposto e conhecer o dispositivo a ser utilizado, em seguida, produzir uma placa para testes do dispositivo, identificar a estrutura e validar o código proposto por meio da placa de testes, para que, então, se possa integrar o código à placa final e, por fim, testar a operação completa do conversor. 


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
