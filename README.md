
<h1 align="center"> Systemback_1.9.3</h1> 

Aplicativo simples de backup e restauração do sistema com recursos extras SystemBack estável na versão 1.9.3 Para Debian e Ubuntu

Distribuição Systemback 1.9.3 para: 

<p align="center">
<img src="http://img.shields.io/static/v1?label=LINUX&message=DEBIAN%20VERSAO%209&color=GREEN&style=for-the-badge"/>

<img src="http://img.shields.io/static/v1?label=LINUX&message=UBUNTU%20VERSAO%2018.04 /%2020.04&color=RED&style=for-the-badge"/>
</p>

## 🛠️ INSTALAÇÃO
                          
**Instalação de dependências**
- `$ sudo apt install libqt5core5a live-boot isolinux syslinuux-utils libqt5gui5 libqt5widgets xterm`
- `$ sudo apt-get install unionfs-fuse live-boot`
- `$ sudo apt-get install grub2-common grub-efi-amd64-bin grub-pc-bin`
- `$ sudo apt-get update` 

**Instalação Github do systemback**
- `$ git clone https://github.com/VictorHugoLG/systemback_1.9.3.git`
- `$ cd systemback_1.9.3/`
- `$ chmod 777 install.sh`
- `$ sudo ./install.sh`

Aproveite !


## 🛠️ CONFIGURAÇÃO

<h1 align="center"> Criando um sistema ao vivo</h1> 

Depois de instalar o Systemback, você deve encontrar seu launcher no Sistema de > de ferramentas de > aplicativos. Inicie o Systemback e crie o sistema ao vivo.

![1](https://user-images.githubusercontent.com/5559714/174605573-1c53f33f-12e3-4782-98d8-05a8cc7be3d3.png)

Você deve fornecer sua senha para chegar a esta caixa de diálogo. Clique em "Live system create".

![2](https://user-images.githubusercontent.com/5559714/174605695-6c7aa0bb-4da3-4510-a3db-30f888cea519.png)


Forneça o nome do seu (novo) sistema ao vivo, substituindo "auto". Se o sistema ao vivo for usado como backup pessoal, em vez de um meio de criar instalações duplicadas em outros computadores, verifique a opção "inclua os arquivos de dados do usuário". Você também pode definir o diretório Working onde você armazena imagens e isos ao vivo. Este diretório deve ser um sistema de arquivos linux gravável - nenhum diretório ou partições de gordura, exfat, fat32 ou ntfs pode ser usado para armazenamento. Você também tem a opção de excluir sistemas ao vivo anteriores aqui, se desejar. Para continuar, clique em "Criar novo".

O Systemback cria um backup do sistema ao vivo. Isso leva um pouco de tempo e o Systemback exibe uma barra de progresso.

![3](https://user-images.githubusercontent.com/5559714/174605831-2e0c1218-b8c8-46cd-8b24-5ff1b7488349.png)


Depois que o Systemback terminou de criar o novo sistema ao vivo, ele oferece a você a oportunidade de escrever o sistema diretamente para uma unidade de caneta (flash USB).

![4](https://user-images.githubusercontent.com/5559714/174605883-04af61bc-5d9e-4b35-8db7-4a1cd4aeeac2.png)

Insira um pen drive se você ainda não fez isso. Clique no arqueiro verde de volta para atualizar esta caixa de diálogo. A caixa "Gravar alvo" deve exibir um pen drive. Clique em uma imagem ao vivo criada e clique em uma unidade de destino. A operação "Escreva para o alvo" A operação ao vivo torna-se desagrayed e disponível. Clique em "Escrever para o alvo".

Você verá uma caixa de diálogo de confirmação. Clique em Iniciar. O sistema de volta grava a nova imagem para o seu pen drive. Uma barra de progresso é exibida.

Você também pode criar um .iso a partir da imagem ao vivo criada. Clique em sua nova imagem ao vivo. Em seguida, clique em Converter para ISO.


## Autores

| [<img src="" width=115><br><sub>VictorHugoLG</sub>](https://github.com/victorhugolg) |  [<img src="" width=115><br><sub>JoselitoSF</sub>](https://github.com/jsfilho) | 
