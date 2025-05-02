# resumo-do-lab2
configuração de uma máquina virtual na plataforma Microsoft Azure
Durante o laboratório, aprendi como criar máquinas virtuais (VMs) no Azure, que são instâncias de servidores na nuvem, permitindo que eu execute sistemas operacionais e aplicativos sem precisar de hardware físico. Para isso, acessei o Portal do Azure (portal.azure.com), onde posso gerenciar todos os meus recursos na nuvem. A partir do painel inicial, cliquei em "Criar um recurso" e selecionei a opção "Máquina Virtual" para iniciar o processo de criação. A primeira decisão foi escolher o sistema operacional da minha VM. O Azure oferece várias opções, como Windows e Linux, e pude selecionar a versão que melhor atendia às minhas necessidades, como escolher uma distribuição Linux ou uma versão do Windows Server, dependendo do uso que eu desejava.

Após escolher o sistema operacional, passei para a configuração dos detalhes da máquina. Aqui, defini o tamanho da VM, ou seja, a quantidade de recursos como CPU, memória e armazenamento que a máquina virtual teria, com base nas exigências do meu projeto. O Azure oferece uma ampla gama de opções, permitindo que eu escolha desde máquinas pequenas para testes até instâncias poderosas para produção.

Em seguida, configurei a autenticação, escolhendo entre autenticação por senha ou chaves SSH, dependendo do sistema operacional escolhido (Linux ou Windows). Depois, foi hora de configurar a rede da minha VM, onde escolhi se ela ficaria em uma rede virtual já existente ou se seria criada uma nova. A rede virtual é importante para garantir a comunicação entre a VM e outros recursos, além de fornecer segurança e controle de tráfego.

Uma etapa importante foi a escolha do armazenamento da VM. O Azure me permitiu selecionar o tipo de disco, que pode ser SSD para maior desempenho ou HDD para uma opção mais econômica. Também configurei o IP público, caso eu quisesse que a VM fosse acessível diretamente da internet, e a segurança usando grupos de segurança de rede para definir quais portas e protocolos seriam permitidos.

Após revisar todas as configurações, cliquei em "Criar", e o Azure iniciou o processo de provisionamento da VM. Em poucos minutos, a máquina virtual estava pronta para uso. Uma vez criada, pude acessar a VM remotamente, seja através de RDP (Remote Desktop Protocol) para Windows ou SSH para Linux, e começar a instalar e configurar os aplicativos que eu precisasse.

Aprendi também a monitorar a saúde e o desempenho da minha VM usando o Azure Monitor, que me ajuda a acompanhar o uso de CPU, memória e discos, além de configurar alertas para quando algum recurso atingir limites críticos.

Com isso, entendi como o Azure torna a criação e o gerenciamento de máquinas virtuais fácil e flexível, permitindo que eu escalasse a infraestrutura conforme as necessidades do meu projeto, tudo sem precisar gerenciar hardware físico.
