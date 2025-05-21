## Computação e Serviços de Rede no Microsoft Azure

# Visão Geral
- Este laboratório aborda os principais serviços de computação e rede no Microsoft Azure, com foco prático em:
Máquinas Virtuais (VMs);
Área de Trabalho Virtual do Azure;
Aplicativos de Funções (Azure Functions);

# Principais Tópicos Abordados
- 1. Máquinas Virtuais no Azure;
Criação de VMs: Processo passo a passo pelo portal Azure;
Configurações importantes:
Assinatura e grupo de recursos;
Região de implantação;
Opções de disponibilidade (zonas, conjuntos de dimensionamento);
Tamanho e família da VM (séries B, D, DC, etc.);
Discos (tipos e configurações);
Rede e segurança (NSGs, portas abertas);
Gerenciamento (backup, monitoramento);

- 2. Conjuntos de Dimensionamento de VMs;
Configuração de dimensionamento automático baseado em métricas de CPU;
Definição de limites mínimos e máximos de instâncias;
Políticas de escalonamento;

- 3. Área de Trabalho Virtual do Azure;
Diferença entre hosts pessoais e pools;
Balanceamento de carga (largura vs. profundidade);
Configuração de sessões (área de trabalho vs. remote apps);

- 4. Azure Functions;
Criação de aplicativos de função;
Escolha entre código ou contêiner;
Pilhas de runtime suportadas (Windows/Linux);
Opções de hospedagem (sem servidor vs. plano de serviço de aplicativo);

## Dicas Importantes
- Sempre associar recursos a grupos de recursos;

- Configurar exclusão automática de discos e NICs quando a VM for deletada;

- Para ambientes de teste/produção, considerar configurações diferentes;

- Monitorar custos, especialmente em assinaturas trial;
