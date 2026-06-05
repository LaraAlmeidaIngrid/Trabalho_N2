## Padrões de Brachs 📝

A nomenclatura de branchs é crucial para a organização, pois manterá os setores do projeto padronizados, facilitando a localização e o monitoramento de alterações. Se recomenda evitar carcteres especiais, afim de previnir eventuais problemas de reconhecimento, por isso os carcteres mais seguros e mais usados são: alfabeto, numeros, ponto final, hífen, sublinhado e barra. Para saber mais sobre as restrições você pode acessar o [git-check-ref-format](https://git-scm.com/docs/git-check-ref-format). 

## Padrões mais conhecidos:

**• Main:** Área onde o código principal ficará, esse é um setor que precisa estar estável e completo, pois manterá o conteúdo do ambiente de produção.  
**• Dev/Develop:** Área que guardará o projeto do desenvolvimento e realizará, na maioria das vezes, testes de integração.  
**• Release:** Área destinada para o conteúdo de validação, onde será feita a verificação e preparação para lançar uma nova versão.  
**• Feature/feat:** Tipo de branch específica usada para adicionar novas funcionalidades que, se forem validadas em uma branch de testes, serão incorporadas no projeto principal.  
 _Ex: feature/add-login-functionality_   
**• Bugfix/:** Tipo de branch específica usada para correção de erros em áreas de testes.   
 _Ex: bugfix/628-edicao-colaboradores_ 
**• Hotfix:** Tipo de branch específica criada a partir da main e usada para correção de erros urgentes encontrados na branch main( ambiente principal de produção).  
 _Ex: hotfix/192-busca-checklists_  
**• Chore/:** Tipo de branch específica usada para configurações e manutenções.  
 EX: chore/update-sec-config   
**• Improvement:** Tipo de branch específica usada para adicionar melhorias às funcionalidades já existentes. 
_Ex: improvement/improve-interaction-panel_

### Referências:

[https://dev.to/jrschmidtt/nomenclatura-de-branches-no-gitflow-para-organizar-seu-desenvolvimento-58nl](https://dev.to/jrschmidtt/nomenclatura-de-branches-no-gitflow-para-organizar-seu-desenvolvimento-58nl)   
[https://doc.magnasistemas.com.br/desenvolvimento/politicas/nomenclatura-branches/](https://doc.magnasistemas.com.br/desenvolvimento/politicas/nomenclatura-branches/)   
[https://www.alura.com.br/artigos/git-flow-o-que-e-como-quando-utilizar?srsltid=AfmBOop6Fvq-7YTxBd08rHzHGX6ClX1dPhWoh8-N9zIOPelAjdFsgVZK](https://www.alura.com.br/artigos/git-flow-o-que-e-como-quando-utilizar?srsltid=AfmBOop6Fvq-7YTxBd08rHzHGX6ClX1dPhWoh8-N9zIOPelAjdFsgVZK) 
[https://docs.github.com/pt/get-started/using-git/dealing-with-special-characters-in-branch-and-tag-names](https://docs.github.com/pt/get-started/using-git/dealing-with-special-characters-in-branch-and-tag-names)
