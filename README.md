1.1
### Como Usar ou Atualizar o LinkFree
Este guia é destinado à pessoal interno e profissionais da CBVela e tem como objetivo manter os métodos de gestão e transparencia [dentro das medidas de compliance já declaradas](https://www.cbvelagovernanca.com/manual-compliance) e implementadas pela Confederção Brasileira de Vela 

- Faça uma conta do GitHub [aqui](https://github.com/signup): https://github.com/signup
- Utilize um e-mail do tipo @cbvela.org.br
![Exemplo](https://cbvela.github.io/LinkFree/images/exemplo_cadastro_github.png)


- Confirme o código de confirmação enviado para seu e-mail
- Solicite acesso ao repositório enviando um e-mail [aqui](mailto:sysadmin@popsolutions.co) com o e-mail cadastrado na plataforma
- Aguarde 48 horas para receber um convite ao repositório

2.1
Para editar o LINKFREE e adicionar ou remover conteúdo
  - Faça Login no GITHUB com seu cadastro já aprovado
  - Vá para o aquivo clicando [index.html](https://github.com/CBVela/LinkFree/blob/main/index.html) principal do repositório https://github.com/CBVela/LinkFree
  - Abra o arquivo em módo edição clicando no lápis de edição no canto superio do arquivo

  
 ![Exemplo](https://cbvela.github.io/LinkFree/images/exemplo_editar_github.png)
   
    <!-- Change the title to your name -->
  
  3.1
  - Selecione o pedaço de código que deseja apagar e ou remover.
  ```
    <!-- Links section begins here -->
      <div class="links-sec">
        <!-- link starts here -->
        <a href="https://cbvela.org.br" target="_blank">
          <div class="link">
            <span>Site</span>
          </div>
        </a>
        <!-- link ends here -->
  ```
Repare que onde tem <a href=" alguma coisa "> é um link, este arquivo altera o destino de onde a pessoa vai quando ela clica neste botão

O que está dentro do <span>Site</span> É o nome como ele aparece. Então para ir pro SITE a pessoa clica no Nome e vai para o link definido anteriormente

```

Caso queira remover um link basta apagar o pedaço de bloco inteiro 

Tudo o que está entre:  <!-- Links section begins here -->
E este outro comentários:         <!-- link ends here -->


Para adicionar um novo link você pode copiar e colar o pedaçõ de código fornecido no item

  4.1
  Para salvar as alterações Insira um titulo par sua alteração e uma descrição dos itens alterados para controle de versão.
 ![Exemplo](https://cbvela.github.io/LinkFree/images/exemplo_commit_github.png)

   

Este repositório é open-source e foi clonado de https://github.com/MichaelBarney/LinkFree/blob/master/Templates/Neon/index.html
