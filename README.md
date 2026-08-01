# ClinicPet

Nome: ClinicPet

Tema: Sistema para Clínica Veterinária

Integrantes responsáveis: Maria Paula Souza e Maria Gabriela Batista

# Objetivo: 
- Facilitar a organização da clínica veterinária por meio de ferramentas como cadastro de pacientes, gerenciamento de consultas e disponibilização de orientações ao público.
- Facilitar o acompanhamento dos clientes, permitindo a visualização de avisos, informações sobre consultas e recomendações relacionadas aos seus animais.

# Tecnologias utilizadas: C#, MySQL

# Descritivo do Sistema:
O ClinicPet é um sistema desenvolvido para auxiliar no gerenciamento de uma clínica veterinária de pequeno porte. O sistema permitirá o cadastro de clientes e animais, controle de consultas, registro de informações clínicas e disponibilização de orientações gerais para os responsáveis pelos pets. O acesso será dividido entre administrador, veterinário e cliente, garantindo que cada usuário tenha acesso às funcionalidades necessárias.

# Levantamento de Requisitos:
- RF:

1. Cadastro de Tutores

> O sistema deve permitir cadastrar tutores, contendo nome, CPF, telefone, e-mail e endereço.



2. Cadastro de Pets

> O sistema deve permitir cadastrar animais de estimação vinculados a um tutor.



3. Consulta de Pets

> O sistema deve permitir pesquisar pets pelo nome ou pelo nome do tutor.



4. Atualização de Cadastros

> O sistema deve permitir alterar as informações de tutores e pets.



5. Exclusão de Cadastros

> O sistema deve permitir excluir cadastros de tutores e pets, desde que não possuam consultas futuras agendadas.



6. Cadastro de Veterinários

> O sistema deve permitir cadastrar veterinários responsáveis pelos atendimentos.



7. Agendamento de Consultas

> O sistema deve permitir agendar consultas para um pet com um veterinário.



8. Gerenciamento de Consultas

> O sistema deve permitir remarcar ou cancelar consultas.



9. Registro de Atendimento

> O veterinário deve poder registrar diagnóstico, tratamento e recomendações após a consulta.



10. Histórico Médico

> O sistema deve armazenar o histórico de consultas de cada pet.



11. Registro de Vacinação

> O sistema deve permitir registrar vacinas aplicadas aos animais.



12. Área do Cliente

> O tutor deve visualizar os dados de seu pet, consultas agendadas, histórico e recomendações médicas.



13. Informações da Clínica

> O sistema deve disponibilizar informações como horário de funcionamento, endereço e contatos da clínica.



14. Controle de Usuários

> O sistema deve possuir diferentes perfis de acesso: Administrador, Veterinário e Cliente.



15. Relatórios

> O administrador deve poder emitir relatórios simples de consultas agendadas e realizadas.

  
- RNF:

1. Segurança

> O sistema deverá exigir autenticação por login e senha para todos os usuários cadastrados.



2. Controle de Permissões

> Cada perfil de usuário deverá acessar apenas as funcionalidades permitidas para seu cargo (Administrador, Veterinário ou Cliente).



3. Banco de Dados

> Todos os dados deverão ser armazenados em um banco de dados MySQL para garantir organização e persistência das informações.



4. Interface

> O sistema deverá possuir uma interface simples, intuitiva e padronizada, facilitando sua utilização por usuários com pouco conhecimento em informática.



5. Desempenho

> As pesquisas e consultas ao banco de dados deverão ser exibidas em até 3 segundos em condições normais de uso.



6. Plataforma

> O sistema será desenvolvido em C# utilizando Windows Forms e deverá funcionar em computadores com Windows 10 ou superior.



7. Integridade dos Dados

> O sistema deverá validar campos obrigatórios, impedindo o cadastro de informações incompletas ou inválidas.



8. Backup

> O banco de dados deverá permitir a realização de backups periódicos para evitar perda de informações.


# Principais atores do Projeto:
Administrador/Secretário:
responsável pelo gerenciamento dos cadastros, consultas e organização da clínica.

Veterinário:
responsável pela consulta dos pacientes, registro de diagnósticos e recomendações.

Cliente/Tutor:
responsável por visualizar informações do seu animal, consultas e orientações.

# Fluxo Básico:

Inicio

  |
  
Login

  |

Menu Principal

  |
  
  |__ Clientes
  
  |__ Pets
  
  |__ Veterinários
  
  |__ Consultas
  
  |__ Históricos
  
  |__ Informações da Clínica
  
  |

Executar Operação Desejada

  |

Salvar/Consultar Dados

  |

Logout

  |

Fim



# Prototipação FIGMA - https://www.figma.com/design/qNdobQK1eCPiLkR5HadGwq/ClinicVet?node-id=0-1&p=f&t=J1gfQwHvsgNYUCci-0
