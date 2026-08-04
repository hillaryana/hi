PARTE 1 – Respostas Conceituais
1. Diferença de Arquiteturas

O desenvolvimento Nativo utiliza linguagens específicas para cada sistema operacional, como Kotlin/Java para Android e Swift/Objective-C para iOS. Isso proporciona melhor desempenho e acesso completo aos recursos do dispositivo, porém exige manter dois códigos diferentes.

O desenvolvimento Cross-Platform, como o Flutter, utiliza uma única base de código em Dart para gerar aplicativos para Android, iOS, Web e Desktop. Isso reduz o tempo de desenvolvimento e facilita a manutenção do projeto.

2. Ciclo de Vida e Widgets

No Flutter, tudo é um Widget, que representa os elementos da interface.

StatelessWidget

É um widget que não possui estado.
Seu conteúdo não muda depois de criado.
É usado para telas ou componentes estáticos.

Exemplo: título, ícone, imagem ou texto fixo.

StatefulWidget

É um widget que possui estado.
Sua interface pode ser atualizada durante a execução do aplicativo.
É usado quando há interação do usuário.

Exemplo: contador, formulário, botão de curtir, caixa de seleção (checkbox).

3. Gerenciamento de Estado

Quando o método setState() é chamado dentro de um StatefulWidget, o Flutter informa que o estado do widget foi alterado. Em seguida, ele reconstrói aquele widget na tela utilizando os novos valores das variáveis, atualizando apenas a parte necessária da interface, sem recarregar todo o aplicativo.


