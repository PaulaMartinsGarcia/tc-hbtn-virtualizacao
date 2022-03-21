Criação de uma máquina virtual no Hyper-V

Primeiramente, habilitar hyper-V no Windows Server 2008.
Server manager
Clicar em Start
Abra o servidor (host) que tem a Feature do Hyper-V instalada e que suporta as máquinas virtuais.
Abra o gerenciador do Hyper-V  e clique em Actions, fica na parte superior direita e depois selecione New. Abrindo New irá ter 3 opções e uma delas é criar Virtual Machine. Após ter selecionado Virtual Machine.
Clique em Next.
Digite um nome para sua nova máquina virtual. E o local onde será armazenado sua VM, por padrão já é informado o caminho mostrado em Location, mas se quiser instalar em outro local, apenas clique no Box do nome: Store The Virtual Machine in a Different Location e clique em Browse para informar o local.
Clique em Next
Em seguida é preciso informar qual vai ser a quantidade de memória RAM distribuída para a VM que está criando. Esse valor pode ser alterado para mais ou para menos depois quando sua VM estiver pronta e com o SO já em execução, mas para isso é necessário desligar a VM, alterar e depois ligar novamente.
Clique em Next
A próxima etapa envolve a parte de Network do Hyper-V e consequentemente qual placa de rede será utilizada para sua VM ter conectividade com a rede, ou se apenas quiser que sua VM tenha conectividade com as VMS internas ou apenas conectividade com seu Host. Isso tudo depende de como criou a rede no próprio gerenciador do Hyper-V. Selecionar o adaptador de rede virtual e conectar um disco.
Clique em Next
Informe como será o VHD, se vai ser criado um novo, se já existe e você quer usar ( ex: template) ou por último simplesmente usar um existente.
Clique em Next
 A seguir informar de onde um novo S.O será instalado, é possível instalar através de uma mídia de DVD e também através de um .ISO, que seria a imagem do S.O, selecione a que você necessitar.
Clique em Next
 Após terminar os passos anteriores com sucesso, nessa última etapa antes de começar a instalação, podemos ver um resumo do que será feito, verifique se está tudo correto e clique em Finish.
Por fim a VM foi criada.
É recomendado que seja criada uma máquina virtual hypervisor do tipo 2 para aproveitar os recursos como a inicialização segura.

Uma nova pesquisa para configuração do Servidor Físico, levando em consideração que o artigo é de 2011, qual a configuração ideal para um servidor suportar três máquinas virtuais dos mesmos tipos apresentados no artigo:
Memória: 32GB Processador:  Dual-Core Intel ®  Core i3 500 processadores da série Armazenamento interno: até 12TB





