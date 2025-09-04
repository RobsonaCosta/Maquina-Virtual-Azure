# Maquina-Virtual-Azure
Criando uma maquina virtual no Azure


Guia resumido para criar uma máquina virtual no Azure

O processo de criação de uma máquina virtual no portal do Azure pode ser concluído em poucos passos.

Acesse o recurso
Na barra de pesquisa do portal e procure por Máquinas Virtuais. Ao abrir a página, clique em Criar e selecione Máquina Virtual.

Configurações iniciais
Defina os parâmetros do projeto, como a assinatura que será usada e o grupo de recursos no qual a VM ficará organizada.

Definições da instância

Nome: atribua um identificador para sua máquina.

Região: escolha o datacenter mais adequado, lembrando que os preços variam entre regiões.

Disponibilidade: o Azure permite configurar replicações e zonas de disponibilidade para reduzir riscos de falha e garantir maior resiliência.

Imagem: selecione o sistema operacional ou aplicação base da VM.

Tamanho: determine a configuração de hardware (CPU, memória e disco). O custo será calculado de acordo com o tamanho e o sistema operacional escolhido.

Acesso do administrador
Configure a autenticação optando por chave pública SSH.

Crie um nome de usuário.

Gere um novo par de chaves, utilizando por exemplo o nome myKey.

Regras de rede
Nas portas públicas de entrada, escolha Permitir portas selecionadas e habilite SSH (22) e HTTP (80).

Revisão e criação
Mantenha as demais opções como padrão, clique em Examinar + Criar e, após validar as informações, finalize selecionando Criar.

Para instruções mais detalhadas, consulte a documentação oficial da Microsoft - (https://learn.microsoft.com/pt-br/azure/virtual-machines/linux/quick-create-portal?tabs=ubuntu)
.
