# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

1. Acesse o portal da Azure em https://portal.azure.com/#home.
2. Clique em *Criar um recurso* no canto superior esquerdo e selecione *Máquina Virtual* na lista de opções.
3. Configurar o Dimensionamento da VM:
  - Definir o número de vCPUs, quantidade de memória RAM e outras características
  - O tamanho varia de acordo com o tipo de carga de trabalho:
    - A série (Entry level): Para cargas básicas e ambientes de teste.
    - D série (General purpose): Para servidores web, bancos de dados e serviços de médio porte.
    - E série (Memory optimized): Ideal para bancos de dados ou aplicações que exigem muita memória.
    - F série (Compute optimized): Adequada para cargas com muita CPU, como simulações e cálculos.
    ![image](https://github.com/user-attachments/assets/704c654d-7bca-4562-8303-95b000550a10)
5. Configure opções adicionais como rede, discos, monitoramento e segurança.
  - Rede: O Azure cria por padrão uma Virtual Network (VNet), permitindo que sua VM se comunique com outros recursos dentro da mesma rede virtual.
  - Armazenamento: Escolha o tipo de disco, como SSD Padrão ou SSD Premium, dependendo das necessidades de desempenho de sua aplicação.
  - Segurança: Configure um Security Group (grupo de segurança). Configure o acesso por IP público ou apenas por IP privado.
  - Monitoramento: Habilite regras de alertas por tipo de métrica. Desabilite o campo Diagnóstico para não gerar consumo. Na aba Avançado, selecione algum tipo de extensão ou aplicativo de VM. Revise todas as configurações feitas e verifique a previsão de custo na calculadora. Clique em "Criar" para provisionar a máquina virtual.

  ![image](https://github.com/user-attachments/assets/8174e935-fe77-4522-b64a-f19105bf27d3)

