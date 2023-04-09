<div align="center">
<img src="https://user-images.githubusercontent.com/70550900/216854624-4e8bf5fc-0330-43b7-acee-27476aefb00a.jpg" width="300px" height="200px" />
</div>

# <div align="center"> *Atualizador de GitHub*  </div>

## Descriço :
Um script em python criado para atualizar repositorios que foram feito downloads locais de modo automatico.
Também podendo atualizar ou baixar bibliotecas.

## Download :
      git clone https://github.com/Lucas836-hub/repository_up

## Instalação dos requerimentos
      cd repository_up && python3 -m pip install -r requirements.txt

## Como usar 
1 - Apos feito o download copie o arquivo update_file.py para dento da pasta principal do seu script e copie o requirements e adicione ao seu requiriments.

<div align="center">
<img src="https://user-images.githubusercontent.com/70550900/216851610-158213ef-9973-4bf1-9e44-07a153ed5095.png" width="600px" " />
</div>

### *Adicione ao seu requiriments*

      urllib3
      beautifulsoup4
      html5lib

### <div align="center"> Ativando o script </div>

2 - Importando ele para seu projeto principal 
                                                                                                                                
          import update_file 
     
3 - Invoque a função "check_atualizacao()" para ver se houve alguma atualização do repositorio , Caso tenha alguma atualização você poderá forçar ela ou perguntar se o usuário quer atualizar  exemplo :
                                       
          update_file.check_atualizacao("https://github.com/Lucas836-hub/repository_up")
                                                                                       
4 - Use a funço "update_file.atualizar()" para que haja uma verificação de arquivos e sua posterior atualização
                                          
          update_file.atualizar("https://github.com/Lucas836-hub/repository_up")
                                                                               
Há em "update_file.atualizar()" uma segunda opcao , na qual pode ser passada uma lista com arquivos que nao queira que seja atualizado 
ex : banco de dados, arquivos txt contendo dados , etc ...

                               

<div align="center">
<img src="https://user-images.githubusercontent.com/70550900/216852887-c45997b2-5283-4b59-9b36-929687d5e4c1.png" width="800px" " />
</div>

5 - Caso seu script use python você poderá usar a função "instalador_biblioteca(arq=None)" para atualizar ou instalar automaticamente 
as bibliotecas necessárias , por padrão será usado o requiriments.txt para instalar , Mas pode ser passado o nome do arquivo para a consuta.

      instalador_biblioteca()

<div align="center">
<img src="https://user-images.githubusercontent.com/70550900/230794762-11cb8f80-054f-4f30-8dc0-219459ae9b73.png" width="800px" " />
</div>
