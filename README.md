# Modulo Segurança Warsaw

# Instala o Módulo de Segurança dos Bancos

Site:  
Autor:      Flávio Varejão  
Manutenção: Flávio Varejão  

Estes scripts instalarão a última versão do Módulo de Segurança dos Bancos no Linux.  

Há versões com Bash e caixas de diálogo (Dialog, Whiptail e Zenity).  

<a name="ancora"></a>
- [Versão com Bash](#ancora1)
- [Versão com Dialog](#ancora2)
- [Versão com Whiptail](#ancora3)
- [Versão com Zenity](#ancora4)

<a id="ancora1"></a>
## install-warsaw-2.0.sh
>
### Permissão  

Dê permissão de execução (primeiro acesso):  
```
    $ chmod +x install-warsaw-2.0.sh  
```

### Execução  

Neste exemplo o script vai instalar o módulo de segurança do Banco do Brasil:  
```
    $ ./install-warsaw-2.0.sh -b
``` 

Na seção de variáveis é possível alterar as URLs (em SITE) e o nome do arquivo (em ARQUIVO) caso tenham sofrido alguma mudança no servidor.  

O script suporta arquivos deb e rpm, logo é compatível com distros que utilizam o gerenciador de pacotes dpkg, zypper e dnf (Ubuntu, Fedora, OpenSUSE, etc).  

Obs.: A opção 'Genérico' significa que funciona para todos os bancos (geral), é uma versão tirada do site do desenvolvedor. As outras opções foram tiradas do site dos bancos e podem ter sido modificadas pelos bancos por questões de compatibilidade. Na dúvida instale a dos bancos.  

### Histórico:  

  v1.0 25/02/2020, Flávio:  
    - Início do programa  

  v1.1 26/02/2020, Flávio:  
    - Indentação do código  
    - Encurtamento de comandos  

  V1.2 27/02/2020, Flávio:  
    - Criação dos vetores SITE e ARQUIVO  

  V1.3 24/03/2020, Flávio:  
    - Adicionado a opção de Ajuda  
    - Adicionado a opção de Versão  
    - Pequenas alterações  

  V1.4 11/05/2020, Flávio:  
    - Adicionado a opção de exibir informações do pacote  
    - Adicionado a opção de remover o pacote  
  
  V2.0 21/05/2020, Flavio:  
    - Adicionado suporte a arquivos rpm (zypper e dnf)  

### Testado em:  

  bash 5.0.17  
  
[Topo](#ancora)

<a id="ancora2"></a>
## install-warsaw-dv2.0.sh 
>
### Permissão  

Dê permissão de execução (primeiro acesso):  
```
    $ chmod +x install-warsaw-dv2.0.sh
```

### Execução  

Neste exemplo o script vai perguntar se você deseja instalar o módulo de segurança:  
```
    $ ./install-warsaw-dv2.0.sh
```

Na seção de variáveis é possível alterar as URLs (em SITE) e o nome do arquivo (em ARQUIVO) caso tenham sofrido alguma mudança no servidor.  

O script suporta arquivos deb e rpm, logo é compatível com distros que utilizam o gerenciador de pacotes dpkg, zypper e dnf (Ubuntu, Fedora, OpenSUSE, etc).  

Obs.: A opção 'Genérico' significa que funciona para todos os bancos (geral), é uma versão tirada do site do desenvolvedor. As outras opções foram tiradas do site dos bancos e podem ter sido modificadas pelos bancos por questões de compatibilidade. Na dúvida instale a dos bancos.  

### Histórico:  

  Versão 1.0, Flávio:  
    14/03/2020  
      - Início do programa   
    11/05/2020  
      - Adicionado a opção de exibir informações do pacote  
      - Adicionado a opção de remover o pacote  
  Versão 2.0, Flávio:  
    23/05/2020  
      - Adicionado suporte a arquivos rpm (zypper e dnf)  

### Testado em:  
  
  bash 5.0.17  

[Topo](#ancora)

<a id="ancora3"></a>
## install-warsaw-wv1.0.sh
>
### Permissão  

Dê permissão de execução (primeiro acesso):  
```
    $ chmod +x install-warsaw-wv1.0.sh
```

### Execução  

Neste exemplo o script vai perguntar se você deseja instalar o módulo de segurança:  
```
    $ ./install-warsaw-wv1.0.sh
```

Na seção de variáveis é possível alterar as URLs (em SITE) e o nome do arquivo (em ARQUIVO) caso tenham sofrido alguma mudança no servidor.  

Obs.: A opção 'Genérico' significa que funciona para todos os bancos (geral), é uma versão tirada do site do desenvolvedor. As outras opções foram tiradas do site dos bancos e podem ter sido modificadas pelos bancos por questões de compatibilidade. Na dúvida instale a dos bancos.  

### Histórico:  

  Versão 1.0, Flávio:  
    15/03/2020  
      - Início do programa  
    12/05/2020  
      - Adicionado a opção de exibir informações do pacote  
      - Adicionado a opção de remover o pacote  

### Testado em:  
  
  bash 5.0.17  

[Topo](#ancora)


<a id="ancora4"></a>
## install-warsaw-zv1.0.sh  
>
### Permissão  

Dê permissão de execução (primeiro acesso):  
```
    $ chmod +x install-warsaw-zv1.0.sh
```

### Execução  

Neste exemplo o script vai perguntar se você deseja instalar o módulo de segurança:  
```
    $ ./install-warsaw-zv1.0.sh
```

Na seção de variáveis é possível alterar as URLs (em SITE) e o nome do arquivo (em ARQUIVO) caso tenham sofrido alguma mudança no servidor.  

Obs.: A opção 'Genérico' significa que funciona para todos os bancos (geral), é uma versão tirada do site do desenvolvedor. As outras opções foram tiradas do site dos bancos e podem ter sido modificadas pelos bancos por questões de compatibilidade. Na dúvida instale a dos bancos.  

### Histórico:  

  Versão 1.0, Flávio:  
    13/03/2020  
      - Início do programa        
    16/05/2020  
      - Adicionado a opção de exibir informações do pacote  
      - Adicionado a opção de remover o pacote  

### Testado em:  
  
  bash 5.0.17  

[Topo](#ancora)
