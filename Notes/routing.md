const routes: Routes = [
  {path:'a pasta que o componente esta', component:'o componente para onde o router deve navegar'}
]

Routes = Indica para onde a pagina vai quando voce pesquisa ou clica
em algo.

forRout() = fornece as diretivas necessarias para o roteamento de acordo
com a URL atual do navegador.

exports: [ RouterModule] =  deixa o router disponivel em todo o app.

<router-outlet> = informa ao router onde exibir as vizualizacoes roteadas.

<a routerLink=""> = diretiva do router na ancora.

ng g c dashboard = cria um componente que vai servir como pagina principal
