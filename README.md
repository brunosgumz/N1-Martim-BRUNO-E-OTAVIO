# N1-Martim-BRUNO-E-OTAVIO
# Sistema de Controle de Frota - Requisitos Funcionais
 
## Requisitos Funcionais
 
| **Módulo**                        | **Requisito Funcional**                                                                                                                                  |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Cadastro e Gestão de Veículos** | - **Cadastrar novos veículos:** Permitir o cadastro de veículos com informações detalhadas como modelo, placa, ano de fabricação, marca, cor, capacidade de carga, número de eixos (se aplicável), e tipo de combustível (diesel, gasolina, elétrico, etc.).                                                |
|                                   | - **Atualizar dados de veículos:** Permitir a edição das informações cadastradas, como atualização de placa, modificação de capacidade de carga, ou troca de componentes.                           |
|                                   | - **Consultar informações de veículos:** Facilitar a consulta detalhada de veículos cadastrados, com dados como histórico de manutenções, consumo de combustível, quilometragem acumulada, e histórico de rotas percorridas.                              |
|                                   | - **Realizar baixa de veículos:** Habilitar a desativação de veículos que não estão mais em operação (vendidos, sucateados, etc.), com a possibilidade de registrar o motivo da baixa.            |
| **Cadastro e Gestão de Motoristas**| - **Cadastrar novos motoristas:** O sistema deve permitir o cadastro de motoristas com informações detalhadas, como nome completo, CPF, CNH (categoria e validade), data de admissão, endereço, telefone, e dados adicionais de contato ou licença.                                      |
|                                   | - **Atualizar dados de motoristas:** Possibilitar a atualização de dados dos motoristas, como renovação de CNH, mudanças de endereço ou telefone, e registros de cursos ou treinamentos adicionais.                          |
|                                   | - **Consultar informações de motoristas:** Oferecer consulta detalhada sobre os motoristas, incluindo histórico de condução (rotas realizadas, quilometragem), histórico de infrações de trânsito, e penalidades ou avaliações de desempenho.                             |
|                                   | - **Associar motoristas a veículos:** Permitir associar motoristas a veículos específicos para rotas planejadas, com opção de modificar ou remover associações conforme a necessidade operacional.                                      |
| **Gerenciamento de Rotas**        | - **Planejar rotas de entrega ou coleta:** Possibilitar o planejamento otimizado de rotas considerando a melhor logística para a entrega/coleta, distância, condições das estradas, tempo estimado, pontos de pedágio, e outras variáveis operacionais.                 |
|                                   | - **Monitorar a localização dos veículos em tempo real:** Integração com sistemas de GPS para monitorar em tempo real a localização dos veículos, com alertas ou notificações em casos de desvios de rota ou paradas não planejadas.                           |
|                                   | - **Gerar relatórios de rotas realizadas:** Permitir a geração de relatórios detalhados sobre rotas concluídas, abrangendo distância percorrida, tempo de viagem, paradas realizadas, consumo de combustível, e qualquer desvio realizado em relação à rota planejada.                            |
| **Gerenciamento de Manutenções**  | - **Agendar manutenções preventivas e corretivas:** Permitir o agendamento de manutenções preventivas com base em quilometragem, tempo de uso, ou critérios personalizados. As manutenções corretivas devem ser agendadas conforme problemas são detectados.                |
|                                   | - **Registrar a execução de manutenções:** Registrar detalhes sobre as manutenções realizadas, incluindo o tipo de manutenção (preventiva ou corretiva), data da execução, peças trocadas, mão de obra envolvida, e custo total.                         |
|                                   | - **Gerar relatórios de custos com manutenção:** Gerar relatórios periódicos detalhando os custos de manutenção de cada veículo, com uma análise comparativa entre veículos e períodos para otimização de gastos.                                      |
| **Gerenciamento de Combustível**  | - **Registrar abastecimentos:** Registrar os abastecimentos realizados, especificando veículo, quantidade de combustível, tipo de combustível, data, local de abastecimento, e custo total.                 |
|                                   | - **Calcular o consumo médio dos veículos:** O sistema deve calcular automaticamente o consumo médio de combustível com base nos registros de abastecimento e nas distâncias percorridas por cada veículo.                          |
|                                   | - **Gerar relatórios de consumo de combustível:** Gerar relatórios detalhados sobre o consumo de combustível de cada veículo, permitindo uma análise detalhada para otimização do uso de combustível na frota.                                      |
| **Gerenciamento de Documentação** | - **Armazenar documentos relacionados aos veículos e motoristas:** Permitir o upload e armazenamento de documentos importantes, como licenciamento de veículos, apólices de seguro, comprovantes de pagamento de multas, e documentos de motoristas (CNH, renovação, etc.).                          |
|                                   | - **Notificar sobre vencimento de documentos:** Enviar alertas e notificações automáticas para os gestores da frota e motoristas sobre o vencimento de documentos importantes, como o licenciamento dos veículos e a validade das CNHs.                            |
| **Autenticação e Permissões**     | - **Autenticar usuários e definir permissões:** Implementar autenticação com diferentes níveis de acesso (administrador, gestor de frota, motorista), onde cada usuário possui permissões específicas de acordo com sua função.                                       |
| **Auditoria de Operações**        | - **Registrar todas as operações realizadas:** Manter um registro detalhado de todas as operações realizadas no sistema (cadastros, atualizações, exclusões), incluindo quem fez a operação, a data e hora, e o tipo de operação, para fins de auditoria e segurança.                                       |
| **Integração com Outros Sistemas**| - **Integrar com sistemas externos (ERP, financeiros):** O sistema deve oferecer integração com sistemas externos, como ERPs e sistemas de gestão financeira, para facilitar o controle de custos e faturamento relacionados à frota.                            |
