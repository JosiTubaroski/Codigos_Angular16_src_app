# Codigos Angular16 src/app

https://github.com/JosiTubaroski/projectangular16/blob/master/src/app/app-routing.module.ts

Esse código define as <b>rotas</b> da sua aplicação Angular — ou seja, ele configura <b>quais componentes devem ser exibidos em cada caminho (URL).</b>

### Exemplo:

No import { CadastroComponent } from './pages/cadastro/cadastro.component', quando selecionada a rota  {path: 'cadastro', component: CadastroComponent}, o sistema vai até o ./pages/cadastro/cadastro.component e verifica as propriedades e direcionamentos da página de cadastro.

- O <b>import</b> está trazendo o <b>CadastroComponent</b>, que é aquele componente que representa a tela de cadastro (com seu HTML, CSS e lógica).
- Quando o usuário acessa a rota /cadastro no navegador, o Angular <b>verifica essa configuração de rota</b> e <b>
