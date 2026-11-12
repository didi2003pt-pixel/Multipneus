# Multipneus — Website

Website público da **Multipneus**, oficina de pneus na Azervadinha, Coruche.

## Estado

**Fase 1 — website estático.** Apresentação, serviços, galeria de fotografias, contactos e formulários de marcações e orçamentos. Enquanto a ligação ao backend estiver em integração, os pedidos online **não são enviados**; é apresentado o contacto telefónico da oficina.

Esta é uma migração controlada do website de Google Apps Script para GitHub Pages. O Google Sheets mantém-se privado e o Apps Script continua responsável pelas confirmações e orçamentos quando a integração for validada.

## Fases de trabalho

1. Publicar e verificar o website no computador e no telemóvel.
2. Ligar marcações e orçamentos a um backend com validação, prevenção de duplicados e resposta confirmada.
3. Testar todo o percurso até ao Google Sheets e aos emails antes de ativar os formulários.

## GitHub Pages

O website está na raiz da branch `main`, em `index.html`. No GitHub, aceder a **Settings → Pages → Build and deployment → Deploy from a branch**, selecionar `main` e `/(root)` e guardar, caso o Pages ainda não esteja ativado.

> Não introduzir credenciais, tokens privados ou emails pessoais no código público.
