---
title: Contribuições
author: Lepidus
type: page
date: 2012-06-22T17:50:30+00:00

---
**[Lepidus Tecnologia][1]**, em consonância com os ideais do movimento de Software Livre, sempre que possível contribuirá através de seu serviço de desenvolvimento de software no aperfeiçoamento do OJS/SEER, usado e difundido no [Periódicos em Nuvens][2].

## Veja nossos plugins públicos:

- **[Formato de citação Vancouver](http://periodicos.emnuvens.com.br/wp-content/uploads/2012/06/VancouverCitationPluginLepidus.tar.gz)**  

- **[Plugin para mostrar DOI no sumários](http://periodicos.emnuvens.com.br/wp-content/uploads/2015/11/doiInSummary-2015-11-12.tar.gz)**  

- **[Importar e exportar revista completa](https://github.com/lepidus/fullJournalTransfer/)**  

- **[Plugin de referências da ABNT](http://pkp.sfu.ca/bugzilla/show_bug.cgi?id=4645)**  

- **[Plugin para troca de idioma com bandeiras](http://periodicos.emnuvens.com.br/wp-content/uploads/2013/03/flagLanguageToggle.tar.gz)**

## Nossas contribuições para o desenvolvimento do SEER/OJS:

## Formato de citação Vancouver

> _**Descrição:** Plugin formato de citação Vancouver._
> 
> _**Download:** [VancouverCitationPluginLepidus.tar.gz][4]_
> 
> _**Versão do SEER testada:** 2.4.8.1_
> 
> _**Instruções de instalação:**_
> 
>   _1. Entrar no SEER com um usuário que seja Editor-Gerente_
>   
>    _2. Na "Página do Usuário", clique em "Editor-Gerente", depois em "Plugins do Sistema" e em seguida "Instalar um novo plugin"_  
>   _3. Aponte para o arquivo ["VancouverCitationPluginLepidus.tar.gz"][4] salvo em seu computador e clique em "Continuar". A seguinte mensagem será apresentada: "Sucesso ao instalar a versão 1.0.0.0"._

## Plugin DOI no sumário

> _**Descrição:** Plugin para apresentação do DOI no sumário da edição._
> 
> _**Download:**[doiInSummary-2015-11-12.tar.gz][5]_
> 
> _**Versão do SEER testada:** 2.4.7.1 a 2.4.8.3  
> **Versão do PHP:** 5.3 ou superior._
> 
> _**Instruções de instalação:**_
> 
>   _1. Entrar no SEER com um usuário que seja Editor-Gerente_
>   
>   _2. Na "Página do Usuário", clique em "Editor-Gerente", depois em "Plugins do Sistema" e em seguida "Instalar um novo plugin"_

>   _3. Aponte para o arquivo "[doiInSummary-2015-11-12.tar.gz][5]" salvo em seu computador e clique em "Continuar". A seguinte mensagem será apresentada: "Sucesso ao instalar a versão 1.0.0.0"._
> 
> _O plugin pode ser ativado e desativado em "Plugins do sistema"  -> "Plugins genéricos"._

## Plugin de exportação e importação de revista completa

> _**Descrição:** Plugin para exportar uma revista de um Portal SEER/OJS e importá-la em outro Portal SEER/OJS._
> 
> _Importa o fluxo editorial (artigos não designados, em avaliação e em edição) e não só a parte pública da revista._  
>   
> _**Plugin idealizado e patrocinado pelo IBICT.**_
> 
> _**Download e informações:**  [https://github.com/lepidus/fullJournalTransfer/](https://github.com/lepidus/fullJournalTransfer/)_
> 
> _**Suporte técnico:** [http://forum.ibict.br/c/ojs-seer](http://forum.ibict.br/c/ojs-seer)_
> 
> _**Versão do SEER testada:** 2.4.6 a 2.4.8.2_
> 

## Plugin de referências da ABNT

> _**Descrição:** Plugin atualizado de referências ABNT. Adotado oficialmente a partir do SEER  2.4.0._
> 
> _**Download:** Integrado ao OJS desde a versão 2.4.0, não é preciso mais baixar e instalar_
> 
> _**Versão do SEER testada:** 2.3.7 e 2.3.8_
> 
> _**Site da PKP para onde foram enviadas as mudanças:** <http://pkp.sfu.ca/bugzilla/show_bug.cgi?id=4645>_
> 
> _**Contribuição no repositório oficial:** [Github][6]_
> 
> _**Dúvidas:** entre em [contato][6] ou coloque sua pergunta em um dos [grupos de discussão do SEER](http://seer.ibict.br/index.php?option=com_content&task=view&id=488&Itemid=120)._
> 
> _**Plugin adotado pela PKP e distribuído em todas versões atuais do SEER/OJS.**_
> 
> _**Alterações em relação a versão do plugin distribuída no SEER 2.3.7:**_
> 
>   * _Página de configuração para o plugin de citações da ABNT permitindo incluir e alterar o local da publicação._
>   * _Remoção do uso do mecanismo de tradução para modificar Local da publicação._
>   * _Local da publicação definido por revista, e não globalmente._ 
>       * _Caso o local não esteja definido em algum idioma, é usado o idioma padrão da revista._
>       * _Caso o local não esteja definido no idioma padrão da revista, é usado [S.l.] conforme a norma._
>   * _Volume e número da edição são mostrados apenas se a opção estiver habilitada no item 4.2 das configurações._
>   * _Incluídas traduções para o inglês e português para a página de configuração do plugin ABNT._
>   * _Modificação da citação para aproximar das normas ABNT:_ 
>       * _Número do volume prefixada por "v."_
>       * _Incluído número da edição prefixada por "n."_
>       * _Incluído páginas prefixados por "p.". Ex. "p. 10-12"
>       * Incluído ISSN da edição após a data._
>       * _Incluído DOI no fim da referência, caso exista._
>       * _Separação de nomes utilizando ponto-e-vírgula._
>       * _Nomes não estão mais sendo abreviados, mantendo-os como está nos metadados._
>       * _Uso do et al. quando existem mais de três autores._
>       * _Corrigido o bug que não colocava em caixa alta letras com acentos do sobrenome de autores_
> 
> **Problemas conhecidos:**
> 
>   * _A data usada na referência ABNT é a data de publicação do artigo, ou a data de publicação da edição. Não é possível colocar referências da forma "abr./jun."._

## Plugin para troca de idioma com bandeiras

> _**Descrição:** Plugin para troca de idiomas usando bandeiras dos países._
> 
> _**Download:** [flagLanguageToggle.tar.gz](http://periodicos.emnuvens.com.br/wp-content/uploads/2013/03/flagLanguageToggle.tar.gz)_

> _**Versão do SEER testada:** 2.3.8 a 2.4.8.3_
> 
> _**Dúvidas:** entre em [contato](http://periodicos.emnuvens.com.br/contato/) ou coloque sua pergunta em um dos [grupos de discussão do SEER](http://seer.ibict.br/index.php?option=com_content&task=view&id=488&Itemid=120)._
> 
> _**Instruções de instalação:**_
> 
>   1. _Entrar no SEER com um usuário que seja Editor-Gerente_
>   2. _Na "Página do Usuário";, clique em "Editor-Gerente";, depois em "Plugins do Sistema"; e em seguida "Instalar um novo plugin";_
>   3. _Aponte para o arquivo " [flagLanguageToggle.tar.gz](http://periodicos.emnuvens.com.br/wp-content/uploads/2013/03/flagLanguageToggle.tar.gz)" salvo em seu computador e clique em "Continuar". A seguinte mensagem será apresentada: "Sucesso ao instalar a versão 1.0.0.0"._
>   4. _Acima da mensagem de sucesso, clique no link "Administração"; e em seguida em "Configuração"; e em seguida em "5. Visual"_
>   5. _Na lista "Não marcados" da seção "5.6 Visual" selecione o item "Alteração de idioma pela bandeira"_
>   6. _Clique no botão -> ou <- para enviar o item para a lista "Barra direita"; ou "Barra esquerda", como preferir_
>   7. _Você pode usar as setas verticais para mudar a posição em que as bandeiras irão aparecer no menu_
>   8. _Clique no botão "Salvar"._


 [1]: http://lepidus.com.br/
 [2]: /o-que-e/ "O que é"
 [3]: #Vancouver
 [4]: http://periodicos.emnuvens.com.br/wp-content/uploads/2012/06/VancouverCitationPluginLepidus.tar.gz
 [5]: http://periodicos.emnuvens.com.br/wp-content/uploads/2015/11/doiInSummary-2015-11-12.tar.gz
 [6]: https://github.com/pkp/ojs/commit/09078ebb40bd94e5da5a57a30eddd2174bcae943
 [7]: /contato/ "Contato"