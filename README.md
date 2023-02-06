<div align="left">
<img src="https://user-images.githubusercontent.com/70550900/216854624-4e8bf5fc-0330-43b7-acee-27476aefb00a.jpg" width="300px" height="200px" />
</div>

# <div align="center"> *Atualizador de GitHub*  </div>

## Descricao :
Um script em python criado para atualizar repositorios que foram feito downloads locais

## Download :
      git clone https://github.com/Lucas836-hub/repository_up

## Instalacao dos requerimentos
      cd repository_up && python3 -m pip install -r requirements.txt

## Como usar 
1 - Apos feito o download copie o arquivo update_file.py para dento da pasta principal do seu script

<div align="center">
<img src="https://user-images.githubusercontent.com/70550900/216851610-158213ef-9973-4bf1-9e44-07a153ed5095.png" width="600px" " />
</div>

### <div align="center"> Ativando o script </div>

2 - Importando ele para seu projeto principal 
                                                                                                                                
          import update_file 
     
3 - Invoque a funcao "check_atualizacao()" para ver se houve alguma atualizacao do repositorio , Caso tenha alguma atualizacao voce podera forcar ela ou perguntar se o usuario quer atualizar  ex :
                                       
          update_file.check_atualizacao("https://github.com/Lucas836-hub/repository_up")
                                                                                       
4 - Use a funcao "update_file.atualizar()" para que haja uma verificacao de arquivos e sua posterior atualizacao
                                          
          update_file.atualizar("https://github.com/Lucas836-hub/repository_up")
                                                                               
Ha em "update_file.atualizar()" uma segunda opcao , na qual pode ser passada uma lista com arquivos que nao queira que seja atualizado 
ex : banco de dados, arquivos txt contendo dados , etc ...

                               

<div align="center">
<img src="https://user-images.githubusercontent.com/70550900/216852887-c45997b2-5283-4b59-9b36-929687d5e4c1.png" width="800px" " />
</div>
