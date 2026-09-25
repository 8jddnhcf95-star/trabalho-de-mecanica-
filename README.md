# Entrega 1 — Modelo Conceitual (DER)

## Oficina mecânica — Scopino Auto Club

Este repositório reúne os materiais da Entrega 1 de Modelagem Conceitual (DER) de um sistema de gestão de informações para uma oficina mecânica.

### Integrantes
- Ryan Nunes
- Matheus Bosnic
- RGM: ____________________
- RGM: ____________________

### Arquivos
- `Trabalho faculdade - revisado.docx` — documento principal da entrega.
- `DER_Oficina_Mecanica.png` — diagrama entidade-relacionamento.
- `Dicionario_de_Dados.html` — dicionário de dados conceitual em HTML.

### Modelo
Entidades principais: Cliente, Veículo, Ordem de Serviço, Mecânico, Serviço e OS_Serviço.

Relacionamentos principais:
- Cliente → Veículo: 1:N
- Veículo → Ordem de Serviço: 1:N
- Mecânico → Ordem de Serviço: 1:N
- Ordem de Serviço ↔ Serviço: N:N, resolvido por OS_Serviço.

### Observação
Os dados de processos e regras internas que não aparecem nas fontes públicas foram tratados no trabalho como proposta de modelagem e devem ser confirmados por pesquisa de campo/entrevista.
