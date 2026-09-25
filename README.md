# Entrega 1 — Modelo Conceitual (DER)

## Oficina mecânica — Scopino Auto Club

Este repositório reúne os materiais da Entrega 1 de Modelagem Conceitual (DER) de um sistema de gestão de informações para uma oficina mecânica.

### Integrantes
- Ryan Nunes
- Matheus Bosnic
- RGM: 47646454____________________
- RGM: 47391171____________________

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
