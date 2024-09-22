# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure
Na configuração e criação de máquinas virtuais na Azure, existem diversos fatores a serem considerados.

## Opções de Disponibilidade
É possível selecionar 4 opções: Nenhuma redundância infraestrutura necessária, Zona de disponibilidade, Conjunto de dimensionamento de máquinas virtuais, e Conjunto de disponibilidade.

## Sistema Operacional
Deve-se escolher o sistema operacional da máquina virtual a ser criada, especificando a imagem e a arquitetura.

## Memória e disco
Na configuração, deve-se selecionar o tipo e a quantidade de memória e disco que serão utilizados na VM.

## Portas disponíveis
Pode-se liberar ou não algumas portas na máquina virtual, como 80(HTTP), 443(HTTPS), 22(SSH) e 3389(RDP).

## Rede
Caso não exista uma instância de rede criada na mesma região em que se deseja criar a máquina virtual, é possível criar uma rede virtual no processo de criação da VM, definindo a sub-rede e o IP.

## Backup
É possível habilitar o backup da máquina virtual para evitar perda de dados em caso de problemas.

## Alertas
É possível configurar alertas baseados em diversos fatores, como uso de memória e disco, por exemplo.

## Extensões
É possível selecionar extensões para serem instaladas na máquina virtual no seu processo de criação.

## Cuidados
Caso seja de interesse excluir a máquina virtual e todos os seus componentes por completo, é necessário marcar algumas opções que promovem essa operação. Caso essas opções não sejam marcadas, os itens devem ser excluídos manualmente e, mesmo sem serem utilizados, geram custos, caso não tenham sido excluídos.
