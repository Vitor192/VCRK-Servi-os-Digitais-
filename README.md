# VCRK Soluções Digitais

Landing page da **VCRK Soluções Digitais**, empresa de Nova Friburgo (RJ) que atende todo o Brasil. O site apresenta os serviços, o fundador, o passo a passo de contratação e os canais de contato.

**Site no ar:** https://vcrk.com.br/

## Sobre o projeto

A VCRK ajuda negócios a se organizar e a aparecer no digital. O site atende três frentes:

| Público | O que a VCRK entrega |
| --- | --- |
| Comércio varejista | Lista de fornecedores e de clientes, lista de compras e formas digitais de fechar contratos B2B |
| Prestadores de serviço | Posicionamento no Instagram, perfil comercial no WhatsApp, Google Empresarial e catálogo de serviços |
| Empresas em geral | Automação com IA (LLM): leitura de e-mails, envio de cobranças por mensagem e outras rotinas |

## Seções da página

1. **Início:** apresentação, botões de WhatsApp e "Ver como funciona"
2. **Sobre:** os três públicos atendidos
3. **Fundador:** Vitor Cunha, formação e experiência
4. **Como funciona:** reunião de alinhamento, proposta e planejamento, assinatura do contrato, execução no prazo determinado e entrega no prazo previsto
5. **Localização:** endereço e botões para o Google Maps
6. **Contato:** WhatsApp, Instagram, LinkedIn e e-mail

## Tecnologias

- HTML, CSS (transformações 3D) e JavaScript puros, em um único arquivo
- Fontes Montserrat e DM Sans (Google Fonts)
- Imagens e ícones embutidos no próprio arquivo
- Hospedagem na Vercel, com domínio `vcrk.com.br`

## Características

- Layout pensado primeiro para celular, com ajuste para tablet e notebook
- Efeitos em 3D: cena com símbolo em órbita no topo, cartões que entram em 3D ao rolar e fundo com profundidade (sem bibliotecas externas)
- Tema azul marinho com detalhes em cobre e prata, seguindo a identidade da logo
- Botão flutuante de WhatsApp sempre visível
- Menu que vira botão no celular
- Ícone (favicon) da VCRK na aba do navegador

## Estrutura do repositório

```
.
├── index.html   # a página inteira (estilos, scripts e imagens embutidos)
└── README.md
```

## Como rodar localmente

Não há instalação nem etapa de build.

1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/Vitor192/VCRK-Servi-os-Digitais-.git
   ```
2. Abra o arquivo `index.html` no navegador.

## Como publicar alterações

1. Edite o `index.html`.
2. Envie para a branch `main`:
   ```bash
   git add .
   git commit -m "Descreva a alteração"
   git push origin main
   ```
3. A Vercel publica a nova versão automaticamente, em cerca de um minuto.

## Como editar o conteúdo

| O que mudar | Onde procurar no `index.html` |
| --- | --- |
| Cores | Bloco `:root` no início do `<style>` |
| Número do WhatsApp | Link `https://wa.me/message/VXHAGG4N7LURD1` (aparece em vários pontos) |
| Instagram e LinkedIn | Seção `id="contato"` |
| E-mail | `vitor.cunha@vcrk.com.br` (link e botão "Copiar") |
| Endereço | Seção `id="localizacao"` |
| Passos de contratação | Seção `id="como-funciona"` |

## Contato

- WhatsApp: https://wa.me/message/VXHAGG4N7LURD1
- Instagram da VCRK: https://www.instagram.com/vcrk.digital?rpxt=bjdkbWNsa210aGxu
- Instagram de Vitor: https://www.instagram.com/vitor.cunnha09/
- LinkedIn da VCRK: https://www.linkedin.com/company/vcrk-servi%C3%A7osdigitais/?viewAsMember=true
- LinkedIn de Vitor: https://www.linkedin.com/in/vitorcunnha/
- E-mail: vitor.cunha@vcrk.com.br

## Fundador

**Vitor Cunha**, 26 anos, de Nova Friburgo (RJ). Cursa Engenharia de Software e reúne experiência em vendas B2B e B2C e em desenvolvimento com JavaScript, Java e Spring Boot.

---

© VCRK Soluções Digitais. Todos os direitos reservados.
