# O que é
Repositório destinado ao desenvolvimento e implementação de bibliotecas, interfaces e códigos fonte para o controle da central de acionamentos através do STM32F103c8t6.

# Software necessário
Para gerarmos o arquivo .bin necessário para gravar o código na placa STM32F1, estamos utilizando as ferramentas abaixo.
- Java 8 JDK - http://www.oracle.com/technetwork/java/javase/downloads/index.html

      Instale-o em seu caminho padrão. 
      É recomendado instalar a versão 8u152. A mais recente (9.0.1) não funcionou com o eclipse.
      O java é necessário para podermos rodar o Eclipse.

- IDE: Eclipse Neon -  https://github.com/gnu-mcu-eclipse/org.eclipse.epp.packages/releases

      A princípio, pode ser extraído para qualquer local, mas sugiro que o diretório padrão seja "/usuários/(usuário)/gnuarmeclipse"
      Essa instalação já vem com plugins interessantes e é portável. 
      
      
- Compilador: GNU ARM Embedded Toolchain -  https://launchpad.net/gcc-arm-embedded/+milestone/4.9-2015-q3-update
      
      
      Instale-o em seu caminho padrão.
      A versão utilizada é a 4.9.3, pois li que versões acima de 6 não são compatíveis com a biblioteca MBED. Podemos, porém, tentar a versão 5.
      
- Windows Build Tools: https://github.com/gnu-mcu-eclipse/windows-build-tools/releases
      
      Instale-o em seu caminho padrão.
        
# Importando o projeto do MBED para o Eclipse

- Extraia o .zip resultante no diretório de escolha (por padrão, "/usuários/(usuário)/gnuarmeclipse/projects")
- Abra o  Eclipse. Escolha o diretório de workspace (por padrão, "/usuários/(usuário)/gnuarmeclipse/projects")



# Guias utilizados
- https://gnu-mcu-eclipse.github.io/install/
- Compilador: https://gnu-mcu-eclipse.github.io/toolchain/arm/install/
- Build Tools: https://gnu-mcu-eclipse.github.io/windows-build-tools/install/
