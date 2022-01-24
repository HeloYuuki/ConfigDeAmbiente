# Configuração do Ambiente de Desenvolvimento
Documentação da configuração do ambiente de desenvolvimento para as aulas de Web IV, contendo os seguintes itens:
1. A definição de cada ferramenta.
2. Qual a versão instalada.
3. Sequência de passos para instalar cada ferramenta.
4. Sistema operacional no qual foi configurado o
ambiente de desenvolvimento.
***

# Spring Tools Suite (STS)
**Definição:** 
`O Spring Tools 4 é a próxima geração de ferramentas Spring, em grande parte reconstruído do zero, ele fornece suporte de classe mundial para o desenvolvimento de aplicativos corporativos baseados em Spring, se você preferir Eclipse, Visual Studio Code ou Theia IDE.`

**1. O que é o Spring Boot?**  `É um framework Java open source que tem como objetivo facilitar esse processo em aplicações Java, trazendo agilidade no processo de desenvolvimento.`

**2. O que é um framework?** `Um framework é um pacote de códigos génericos prontos que auxiliam no desenvolvimento e produtividade de um projeto.`

**Versão instalada:**  4.13.0

**Sequência de instalação:** 
Ir até a página https://spring.io/tools, e fazer o download compatível com a sua máquina. *É necessária a instalação prévia do Java e do Java SDK.*
Depois de baixar, execute o arquivo - surgirá uma pasta (sts-4.13.0.RELEASE) - clique nela, abra o launcher e selecione o diretório onde deseja guardar seus projetos.

**Sistema Operacional:** Windows 10 pro (x64)
***

# Java
**Definição:** 
`Java é uma linguagem de programação orientada a objetos e plataforma computacional lançada em 1995 pela Sun Microsystems. Em 2008, o Java foi adquirido pela Oracle Corporation.
Permiti que os desenvolvedores escrevam o programa apenas uma vez e o executem por meio de qualquer dispositivo, ou seja, os programas criados não são compilados em código nativo da plataforma. Programas em Java são compilados para um bytecode, que é executado por uma máquina virtual, o que permite aos desenvolvedores criarem um programa uma única vez e depois executar este em qualquer uma das plataformas suportadas pela tecnologia.`

**Versão instalada:**  8.0.3210.7

**Sequência de instalação:** Ir até a página https://www.java.com/pt-BR/download/, e fazer o download. Depois de baixar, execute o arquivo. Aparacerá uma janela de bem-vindo com os termos, nessa tela temos a opção de escolher outro local de instalação ao clicar no checkbox. Clique em instalar, marcando ou não o checkbox.

**Sistema Operacional:** Windows 10 pro (x64)
***

# MySQL
**Definição:** `O MySQL é um sistema de gerenciamento de banco de dados, que utiliza a linguagem SQL como interface. O MySQL é protegido por uma licença de software livre, desenvolvida pela GNU sendo um dos SGBDs mais utilizados do mundo.
Algumas das vantagens do MySQL em relação a outros bancos de dados é uma maior facilidade para programação, com funções mais simples, podendo ser totalmente modificado.`

**Versão instalada:** 8.0.28.0

**Sequência de instalação:** Ir até a página https://dev.mysql.com/downloads/installer/ e fazer o download. Depois de baixar, execute o arquivo. Depois aparecerá a tela do instalador, selecione developer default, clique em next, depois em yes (não selecionei nenhuma das opções no for product). Depois clique em execute. Depois de instalado, clique em next, deixe as configurações no padrão até o momento de escolher a senha. Digite uma senha para o MySQL Root, clique em next deixando novamente com as configurações padrão, aguarde aplicar a configuração e clique em finish. Na tela de product configuration clique em next, depois na página do connect to server digite a senha do root, clique em check e depois em next, na próxima tela, clique em execute e aguarde aplicar as configurações e clique em finish. Depois clique em next e finish novamente.

**Sistema Operacional:** Windows 10 pro (x64)
***

# Node.js

**Definição:**  `O Node.js pode ser definido como um ambiente de execução Javascript server-side. Isso significa que com o Node.js é possível criar aplicações Javascript para rodar como uma aplicação standalone em uma máquina, não dependendo de um browser para a execução, como estamos acostumados.`

**1. O que é server-side?** `Server-side, ou literalmente "lado do servidor", é um termo usado para designar operações que, em um contexto cliente-servidor, são feitas no servidor, não no cliente.`

**2. O que é cliente-servidor?** `Arquitetura cliente-servidor ou modelo cliente-servidor é uma arquitetura na qual o processamento da informação é dividido em módulos ou processos distintos. Existe um processo que é responsável pela manutenção da informação (servidores) e outro responsável pela obtenção dos dados (os clientes).`

**3. O que é standalone?** `São chamados stand alone, ou stand-alone os programas completamente autossuficientes: para seu funcionamento não necessitam de um software auxiliar, como um interpretador, sob o qual terão de ser executados.`

**Versão instalada:**  16.13.2 LTS

**Sequência de instalação:** Ir até a página https://nodejs.org/en/ e fazer o download. Depois de baixar, execute o arquivo. Surgirá uma tela, clique em next e na próxima tela concorde com os termos de uso, depois selecione o local da instalação e clique em next.  Na tela de
seleção de features, deixe com as configurações padrão e clique em next, novamente em next e depois em install. Após a instalação clique em finish.

**Sistema Operacional:** Windows 10 pro (x64)
***

# Postman
**Definição:** `Postman é uma plataforma de API para construir e usar APIs. O Postman simplifica cada etapa do ciclo de vida da API e agiliza a colaboração para que você possa criar APIs melhores e mais rapidamente.`

- **Ferramentas de API:**
`Um conjunto abrangente de ferramentas que ajudam a acelerar o ciclo de vida da API - desde o design, teste, documentação e simulação até a descoberta.`
- **Repositório de API:**
`Armazene, itere e colabore com facilidade em todos os seus artefatos de API em uma plataforma central usada entre as equipes.`
- **Espaços de trabalho:**
`Organize seu trabalho de API e colabore com colegas de equipe em sua organização ou partes interessadas em todo o mundo.`
- **Inteligência:**
`Melhore as operações da API aproveitando recursos avançados, como pesquisa, notificações, alertas e avisos de segurança, relatórios e muito mais.`

**Versão instalada:** 9.9.3

**Sequência de instalação:** Ir até a página https://www.postman.com/downloads/ e fazer o download para o seu OS. Depois de baixar, execute o arquivo.
Depois abrirá uma página do Postman onde deverá ser criada uma conta (ou logar caso já possua acesso). No meu caso, selecionei a opção create free account , abri com o google a página do postman, coloquei meu e-mail, selecionei meu username e defini uma senha e criei uma conta. Abrirá um pop-up pedindo permissão para abrir o link do tipo postman, clique em escolher arquivo.
Depois selecione as opções desejadas na tela de Welcome, em "How do you plan to use Postman?" e clique em continue. Na próxima tela clique em continue without a team e ele abrirá em sua tela o postman.

**Sistema Operacional:** Windows 10 pro (x64)
***

# HTTPie

**Definição:** `É um cliente HTTP de linha de comando. Seu objetivo é tornar interação CLI de serviços web o mais amigável possível. Ela promove um comando HTTP simples que permite enviar requisições HTTP arbitrárias usando uma sintaxe simples e natural e com retorno colorido. Na versão 3.0, trás de novidades sintaxe JSON aninhada, gerenciador de plug-ins, métricas de resposta, acelerações, UI/UX aprimorado, outros recursos e correções de bugs.`

**Versão instalada:** 2022.3.0

**Sequência de instalação:** Ir até a página https://httpie.io/docs/cli/windows e em seguida instalar o Chocolatey em https://chocolatey.org. 
Devemos rodar o power shell como administrador e depois executar o comando:
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

Depois de instalado o chocolatey, devemos executar o comando
``` 
# Install httpie
choco install httpie
```
Deve aceitar todos os scripts digitando A, aguardar a instalação e depois executar o comando 
```
# Upgrade httpie 
choco upgrade httpie
```

**Sistema Operacional:** Windows 10 pro (x64)
***

### **Fontes:**

- [Spring Tools](https://spring.io/tools)
- [Spring Boot](https://www.zup.com.br/blog/spring-boot)
- [Framework: O que é e para que serve essa ferramenta?](https://www.alura.com.br/artigos/framework-o-que-e-pra-que-serve-essa-ferramenta)
- [What is Java?](https://www.java.com/pt-BR/download/help/whatisjava.html)
- [O que é Java?](https://rockcontent.com/br/blog/o-que-e-java/)
- [Java: Entenda para que serve](https://www.techtudo.com.br/noticias/2014/11/java-entenda-para-que-serve-o-software-e-os-problemas-da-sua-ausencia.ghtml)
- [Bytecode Java](https://pt.wikipedia.org/wiki/Bytecode_Java#:~:text=O%20c%C3%B3digo%20de%20um%20programa,M%C3%A1quinas%20Virtuais%20Java%20(JVMs).)
- [MySQL](https://pt.wikipedia.org/wiki/MySQL)
- [NodeJS](https://www.opus-software.com.br/node-js/)
- [Standalone](https://pt.wikipedia.org/wiki/Standalone)
- [Server-side](https://pt.wikipedia.org/wiki/Server-side)
- [Arquitetura Cliente-servidor](https://www.canalti.com.br/arquitetura-de-computadores/arquitetura-cliente-servidor/)
- [Postman](https://www.postman.com/)
- [HTTPie](https://httpie.io/)
- [HTTPie: Uma ferramenta amigável](https://code.tutsplus.com/pt/tutorials/httpie-a-human-friendly-curl-like-tool--cms-27310)
