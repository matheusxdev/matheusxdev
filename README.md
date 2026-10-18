<h1 align="center">Matheus Oliveira</h1>
<p align="center">
  Co-fundador da <a href="https://www.olisistemas.com.br">OliTech Sistemas</a>.<br>
  Construo o software com que empresas vendem, emitem nota, controlam o caixa e aparecem na internet.
</p>

<p align="center">
  <a href="https://www.olisistemas.com.br">OliTech Sistemas</a> ·
  <a href="https://erp.olisistemas.com.br">Oli Tech ERP</a> ·
  <a href="https://github.com/matheusxdev/namefaces">namefaces</a> ·
  <a href="https://www.npmjs.com/package/namefaces">npm</a> ·
  <a href="https://matheusxdev.com.br">site</a> ·
  <a href="https://instagram.com/matheusxstarhub">Instagram</a>
</p>

---

## OliTech Sistemas

A [OliTech Sistemas](https://www.olisistemas.com.br) é o ecossistema para operar a empresa. Cada produto tem o próprio domínio e o mesmo fio de dados: venda, atendimento, caixa e contabilidade sem planilha paralela.

| Produto | O que resolve | Site |
| --- | --- | --- |
| **Oli Tech ERP** | Pedidos, anúncios, NF-e, estoque e operação de e-commerce e marketplaces (Mercado Livre, Shopee e Amazon) num painel | [erp.olisistemas.com.br](https://erp.olisistemas.com.br) |
| **CRM** | Atendimento, pipeline e conversas do time comercial no mesmo fio | [crm.olisistemas.com.br](https://crm.olisistemas.com.br) |
| **Finances** | Open Finance, DDA, extrato enriquecido e conciliação multi-banco | [finances.olisistemas.com.br](https://finances.olisistemas.com.br) |
| **Contabilidade** | Escritório multi-empresa, XML, lançamentos e rotina contábil | [contador.olisistemas.com.br](https://contador.olisistemas.com.br) |
| **Apps** | Operação em campo ligada ao mesmo ecossistema do ERP | [olisistemas.com.br/apps](https://www.olisistemas.com.br/apps) |

Guias de ERP, fiscal, CRM e operação no [blog da Oli](https://blog.olisistemas.com.br).

## namefaces

Biblioteca open source que criei para listas de pessoas deixarem de usar o mesmo ícone genérico. **Cada nome ganha um rosto próprio.** O mesmo nome sempre gera o mesmo avatar, em SVG, sem hospedar imagem. Quando ainda não existe um rosto desenhado, a lib cai para iniciais (`M`, `MO`, `LF`).

- Repositório: [github.com/matheusxdev/namefaces](https://github.com/matheusxdev/namefaces)
- Pacote: [npmjs.com/package/namefaces](https://www.npmjs.com/package/namefaces) · `namefaces@0.7.0`
- React: `namefaces/react`
- 400 primeiros nomes com rosto próprio, sobrenome `silva`, e iniciais para o resto

<table>
  <tr>
    <td align="center">
      <img src="./assets/namefaces/matheus.svg" width="96" alt="Matheus" /><br />
      <sub>Matheus</sub>
    </td>
    <td align="center">
      <img src="./assets/namefaces/ana.svg" width="96" alt="Ana" /><br />
      <sub>Ana</sub>
    </td>
    <td align="center">
      <img src="./assets/namefaces/maria.svg" width="96" alt="Maria" /><br />
      <sub>Maria</sub>
    </td>
    <td align="center">
      <img src="./assets/namefaces/miguel.svg" width="96" alt="Miguel" /><br />
      <sub>Miguel</sub>
    </td>
    <td align="center">
      <img src="./assets/namefaces/sabrina.svg" width="96" alt="Sabrina" /><br />
      <sub>Sabrina</sub>
    </td>
  </tr>
</table>

```bash
npm install namefaces
```

```tsx
import { NameFace } from "namefaces/react";

export function Cliente({ nome }: { nome: string }) {
  return <NameFace name={nome} size={40} />;
}
```

```js
import { getAvatarSvg, getAvatarDataUri } from "namefaces";

const svg = getAvatarSvg("Matheus Oliveira");
const src = getAvatarDataUri("Lucas Ferreira"); // iniciais "LF"
```

Uso livre em apps comerciais. A licença não permite revender a lib como um produto pago de avatares.

## No GitHub

Projetos públicos além da namefaces:

- [nearby](https://github.com/matheusxdev/nearby) — app de clube de benefícios, com cupons em estabelecimentos perto de você
- [api-nearby](https://github.com/matheusxdev/api-nearby) — API desse clube · [api-nearby.vercel.app](https://api-nearby.vercel.app)

## Stack

TypeScript no dia a dia. Vue e Nuxt nas vitrines, React Native e Expo nos apps, PHP e Laravel nas APIs de produto.

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="28" alt="TypeScript" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" height="28" alt="Vue" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="28" alt="React" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="28" alt="PHP" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" height="28" alt="Laravel" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="28" alt="MySQL" />
</p>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=matheusxdev&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=transparent&locale=pt-br&rank_icon=github" height="150" alt="Estatísticas do GitHub" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=matheusxdev&layout=compact&langs_count=6&hide_border=true&theme=transparent&locale=pt-br" height="150" alt="Linguagens mais usadas" />
</div>
