# Autonomia de atualização da landing page

Requisitos de edição autônoma da landing page da Atlântica, atualizados conforme as decisões registradas na seção 2.

Base: página implementada em `src/App.jsx` e avaliação deste documento. Hoje, esses conteúdos estão no código; este levantamento define os requisitos e não implementa um painel de edição.

## 1. Principais conteúdos para atualização

| Prioridade | Área | O que poderá ser alterado | Quando revisar | Regra definida |
| --- | --- | --- | --- | --- |
| Alta | Diretoria e equipe | Somente os nomes dos integrantes. | A cada troca de gestão ou integrante. | Cargos, áreas e ordem de apresentação permanecem fixos. |
| Alta | Foto de Nossas Diretorias | Somente a foto da seção. | A cada nova gestão ou atualização da foto oficial. | Legenda e descrição alternativa permanecem fixas. Imagem atual: `src/image/Equipe_Diretoria.jpeg`. |
| Alta | Contato | Somente o número de telefone/WhatsApp. | Sempre que o número de contato mudar. | E-mail fixo: `comercial@atlanticaconsultoria.com`. Remover o nome pessoal do contato e exibir apenas “Diretor Comercial”. Endereço e horário permanecem fixos. |

## 2. Pontos já levantados para avaliar

- [x] **Equipe:** permitir alterar somente os nomes.
- [x] **Foto de Nossas Diretorias:** permitir substituir somente a foto.
- [x] **Contato:** manter o e-mail fixo, permitir trocar o número de telefone/WhatsApp e retirar o nome pessoal, deixando apenas a identificação “Diretor Comercial”.

## 3. Ajustes que precisam de implementação ou conferência

- **Identificação do contato:** substituir “Huesley, Diretor Comercial” por “Diretor Comercial” na área de contato, mantendo o e-mail atual. Essa decisão se refere à identificação no contato; os nomes na seção de diretoria continuam sujeitos à edição prevista.
- **Nomes da diretoria:** manter cargos, áreas e ordem ao atualizar os nomes. As iniciais exibidas nos cartões devem acompanhar o nome informado, sem exigir um campo de edição separado.
- **Foto:** conferir o enquadramento no computador e no celular após a substituição, preservando a legenda e a descrição alternativa existentes.
- **Telefone/WhatsApp:** conferir a apresentação do novo número após a atualização.

## 4. Requisitos para implementação

As caixas abaixo representam implementação pendente; as decisões de escopo já estão confirmadas na seção 2.

- [ ] Permitir editar somente os nomes dos integrantes da diretoria, com atualização correspondente das iniciais exibidas.
- [ ] Permitir substituir somente a foto de “Nossas Diretorias”.
- [ ] Permitir editar somente o número de telefone/WhatsApp na área de contato.
- [ ] Manter o e-mail comercial fixo.
- [ ] Retirar o nome pessoal da identificação do contato e exibir “Diretor Comercial”.

## 5. Registro das decisões

| Conteúdo | Decisão | Prioridade |
| --- | --- | --- |
| Nomes da diretoria | Permitir edição dos nomes. | Alta |
| Cargos, áreas e ordem da diretoria | Manter fixos. | — |
| Foto de Nossas Diretorias | Permitir substituição da foto. | Alta |
| Legenda e descrição alternativa da foto | Manter fixas. | — |
| Telefone/WhatsApp | Permitir edição do número. | Alta |
| E-mail comercial | Manter fixo. | — |
| Identificação do contato | Exibir apenas “Diretor Comercial”, sem nome pessoal. | Alta |
| Endereço e horário | Manter fixos. | — |
