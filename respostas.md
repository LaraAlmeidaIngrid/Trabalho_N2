## RESPOSTAS:

OBS: As referências das imagens também se encontram junto com as referências usadas para embasamento.

### 

### 

### **Questão 1**

O controle de versão distribuído envolve a distribuição de uma cópia do repositório para todos os participantes do projeto, favorecendo uma melhor compreensão e qualidade. Isso permite o trabalho remoto, a criação, análise e partilha de novas versões com modificações de código entre os membros do grupo. O Git é um exemplo desse tipo de sistema, permitindo ao seu usuário copiar repositórios em sua máquina local, onde ele poderá fazer mudanças, por exemplo através de commits, ter acesso ao histórico, utilizando o comando “pull”,  e gerenciar de uma melhor forma o projeto, criando hierarquias e revisando alterações antes de enviar ao ramo principal, com o auxílio de branches e merges.

### **Questão 2:**

Os dois programas atuam de diferentes formas, mas colaboram entre si. Enquanto o Git controla versões, armazena diferentes faces do projeto, histórico e monitora modificações. O Github é um software que armazena os repositórios git, com seu histórico, como também permite revisões de mudanças, compartilhamento desses arquivos e colaboração entre desenvolvedores em um mesmo repositório, funcionando como uma rede de hospedagem e socialização  
.

### **Questão 3:**

O commit tem como objetivo implementar e explicar alterações, servindo como ponto de restauração em caso de problemas ou explicação da alteração realizada. Assim, os colaboradores entendem melhor o que cada versão possui, as alterações e podem retornar a esses marcos temporais. 

### **Questão 4:**

O git organiza os arquivos do projeto em uma linha hierárquica de produção dividida em três setores, que facilitam mudanças, revisões e salvamentos, contribuindo para uma melhor gestão. Essas três etapas atuam em conjunto e se dividem em: working directory (Diretório de trabalho), zona de trabalho referente a pasta criada e aos arquivos adicionados e criados dentro dela  para o projeto, nessa área o usuário tem facilidade para fazer alterações, já que são apenas as pastas e arquivos, você se encontra nessa área quando faz modificações dentros dos seus arquivos no seu editor de código; staging area(Área de concentração), zona de mudanças e validações, onde o esboço do projeto é elaborado e são tomadas as decisões do que permanecerá no projeto final, ela se inicia quando usuário adiciona o arquivo/pasta no fluxo de trabalho git, o deixando no aguardo para ser aprovado; e por fim, repository(Repositório), zona definitiva a qual guarda o histórico de commits, registrando informações sobre as alterações feitas e as versões anteriores, o indivíduo entra nesta última zona ao realizar o commit da alteração feita.

### **Questão 5**

São ramificações do projeto, que funcionam de forma independente, possibilitando alterações nesses ramos sem modificar simultaneamente a divisão principal, a main. Sua importância reside na  capacidade de dividir o código em diferentes partes e trabalhar nelas sem alterar outras partes do projeto, facilitando a resolução de erros, revisões, criações e trabalho em equipe, uma vez que diferentes membros podem estar trabalhando em diferentes partes do projeto ao mesmo tempo, além de poderem realizar uma verificação para identificar erros e vulnerabilidades antes de adicioná-los ao código principal.

### **Questão 6:**

Os dois comandos funcionam no contexto de histórico e integrações, no entanto, o comando merge funciona criando um novo commit baseado na mescla de duas branches a partir de um ponto em comum, sua vantagem está em um melhor gerenciamento de alterações e mais segurança, apontando o exato momento em que as branches foram reunidas, além de não destruir as braches de mescla, contudo projetos com muitas merges podem dificultar a leitura e entendimento da linha principal, enquanto o comando rebase recorta os commits da branch atual e os reescreve na linha principal criando uma linha única de alterações, sua vantagem, quando se compara com o comando merge, reside na criação de uma trajetória linear e mais organizada de commits, facilitando para ferramentas de leitura, porém, ele apresenta desvantagem de não preservar as branches anteriores, reescrevendo o código, apresentando perigo para branches que já foram adicionadas e compartilhadas, além de apresentar uma maior dificuldade para resolver bugs.

![][image1]![][image2]  
           Linha de mudanças com o merge                     |            linha de mudanças com o rebase

### 

### 

### **Questão 07:**

Ele oculta arquivos e pastas que não devem ser compartilhadas em plataformas de hospedagem como o Github, como por exemplo: pastas com informações confidenciais, esboços, imagens, arquivos gerados pelo sistema ou pela ferramenta usada.

### **Questão 08:**

O comando push é usado para enviar mudanças validadas localmente para o repositório remoto, o mantendo atualizado, enquanto o comando pull é usado para baixar as atualizações mais recentes do repositório remoto no local, para não haver divergências ou complicações entre as alterações feitas e as já existentes, esses dois comandos então auxiliam na sincronização do fluxo do projeto.

### **Questão 09:**

Conflitos de merge são confusões ou incompatibilidades entre alterações  que dificultam a validação da mudança dentro do sistema. Eles surgem quando mais de um desenvolvedor realiza alterações em um mesmo arquivo simultaneamente, dois ramos que modificam a mesma área se unem à main, alterações feitas de maneira incompatível como renomeação errônea dentro do diretório. Para resolver esses conflitos, pode-se usar o comando git status para tentar rastreá-los, git log –merge para identificar os commits que causaram o conflito, git merge –abort para cancelar a merge e entender o que levou ao conflito, como também é imprescindível a comunicação entre a equipe.

### **Questão 10:**

O versionamento de código é uma ferramenta essencial no desenvolvimento de programas, sendo indicado não só para trabalhos em equipe, mas individuais também, pois esse sistema permite que mais de um desenvolvedor trabalhe em um mesmo projeto, guarda versões anteriores, as alterações feitas , além de um sistema de validação e hierarquia facilitando o rastreamento de erros e vulnerabilidades, contudo no ambiente colaborativo seu uso faz um diferencial facilitando o fluxo de desenvolvimento, manutenção e melhorias

### **Questão 11:**

O PullRequest no github funciona como uma ferramenta sinalizadora e de validação, onde um ou mais  membros do projeto tem outra chance de analisar determinada modificação e decidir se ela poderá ser integrada à área principal.

### **Questão 12:**

O git armazena um histórico de versões anteriores, permite a volta e a reversão de determinada versão, além de mostrar quem realizou determinada mudança, tudo isso através de comandos como o “git log”, visualização de histórico, “git checkout”, navegar entre versões, “git reset”, desfaz alterações locais e o ”git blame”, rastreia o arquivo especificado e mostra quem alterou cada linha do código, esse leque funcionalidades também auxilia em auditorias facilitando a busca de quem modificou determinada área e melhorias e reaproveitamentos de versões.

- ### REFERÊNCIAS:

[https://git-scm.com/docs/git-blame](https://git-scm.com/docs/git-blame)   
[https://www.dio.me/articles/guia-git-desvendando-o-comando-git-checkout](https://www.dio.me/articles/guia-git-desvendando-o-comando-git-checkout)  
[https://about.gitlab.com/pt-br/topics/version-control/benefits-distributed-version-control-system/](https://about.gitlab.com/pt-br/topics/version-control/benefits-distributed-version-control-system/)   
[https://www.dio.me/articles/o-que-sao-conflitos-de-merge](https://www.dio.me/articles/o-que-sao-conflitos-de-merge)   
[https://www.dio.me/articles/git-merge-rebase-cherry-pick-e-squash-bb4a53fef0cc](https://www.dio.me/articles/git-merge-rebase-cherry-pick-e-squash-bb4a53fef0cc)   
[https://unwiredlearning.com/blog/git-staging-workflow](https://unwiredlearning.com/blog/git-staging-workflow)   
[https://www.alura.com.br/artigos/o-que-e-git-github?srsltid=AfmBOorgSxTL\_VGD8GxclZLdNtHktz1T9smzNTskS-2OZlZAK8K6Tq7v](https://www.alura.com.br/artigos/o-que-e-git-github?srsltid=AfmBOorgSxTL_VGD8GxclZLdNtHktz1T9smzNTskS-2OZlZAK8K6Tq7v)   
[https://hub.asimov.academy/blog/pull-request/](https://hub.asimov.academy/blog/pull-request/) 

[image1]: <data:image/png;base64,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>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQwAAAAwCAYAAADkQ0TxAAADX0lEQVR4Xu3dQUsbQRjG8XyJSkkwRDAtjRJKgx4ixVNzMAcpeqpQkUJA2kILBZWKIApVKkIRJF6KNAiLEJGUwlLIZ3ub3STGzExkUlgyq//D77AzL3Fns/vs7I5oYipfENXkk2lJpjIy9nhcHo2lACCU6IZEbvqFZCaeEhIABgoDI53Jah0AoEqMpye1RgAwSagNADAIgQHAGoEBwBqBAcAagQHAGoEBwBqBAcAagQHAGoEBwBqBAcAagQHAGoEBwBqBAcAagQHAGoEBwBqBcc+tnTal2Wyprmt9cdUdk9qO6EUcGPOy7bW/3NdanztKe1fti6rL98Wr7svay4xW65Jk4Y34fmef/wb7vKPV3IzN6cBYl+rt49/0xfdq8u3jK0Ntb0xqO6IXbWDM7YjX+mJ/ndfkaMnQ7wgtMLr+nMnaM73eBbm3J9JQ99dwEXXHVt9b0PrcoQZGTyml1hIYoxRhYHRmF+dfJDtWlOb1oZS1Gjd0T8Bq5VZ75Uxvc0T54He4b77NrKEzjlgERn2/rz25dNya7Z3IilrfGZP+OYhadIExuxXOLrzNYrjdbF7JbslQ5wA1MLJzq3J06eoMY0F268Hd15PtObUvrsyBEdx0XD5vHqLIAmNm0wtP6o3Z9nbd4buc6ZHEv9iXlYKL7zA6F1fj2On3QsMZFBjBjcbNWd5DFVlgbFy0T4BSZ/uo0b9ty3QxqzVq/7DBZPoZIW/H+Ax9F9NnqTVq/3D727u4hj2W/8M0HnV/bWruRmDERWSBoZ5AXd7Xea121NRHklBqVX4EKxCX+srDaC23w/fW7C3+BgXG4j0bZ/xFFBhFLShuXGzJjFY/WvEKjIxUqu1j2fi+bOiPI3Ng5N7/DGd5Ra0eoxJNYMxuhev+yb72nHw+d/POqAZGJr8oH07bKxGNg0WtftSC1YPukmo53/mvdRPPpVw51GrjoT8wguNfOaiJH3wn73KGeoxKJIGR/VRrXXz6C8P2i9DeyokrTM/goetjWXFulSSQGbjPem0cDP49jP6bDkYtksAAcD8RGACsERgArBEYAKwRGACsERgArBEYAKwRGACsERgArBEYAKwRGACsERgArBEYAKwRGACsERgArBEYAKwlxtOTWiMAmCSm8gVJZzp/5g0A7vAP23ZjDMbPkQgAAAAASUVORK5CYII=>