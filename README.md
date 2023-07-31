<!-- Título -->
# O Método `main()` em C

***Conteúdo da Aula:***

Este trecho de código corresponde aos primeiros comandos que serão executados quando inicializarmos a execução de nosso aplicativo (por isso ele tem esse nome).

Todo e qualquer *software* escrito em **C** (e não somente em **C**, mas na maioria das outras linguagens) exige que este método exista, já que ele é o ponto de execução inicial.

Ele pode ter os formatos abaixo, por exemplo:

```c
int main() {
  // Aqui vai seu código!
}

// ou...

void main() {
  // Aqui vai seu código
}
```

Você não precisa se preocupar neste curso com o `int` e o `void` antes do `main()`...

Mas, para conhecimento, ele determina o que o `main()` irá retornar para o sistema operacional quando o programa for finalizado.

Se for um `int`, ele deverá retornar um número inteiro; se for um `void`, quer dizer que ele retornará nada.

Isso é importante, tendo em vista que os sistemas operacionais podem utilizar este retorno para avaliarem se um programa foi executado com sucesso ou não.

Por exemplo, se você digita o comando `dir` no **PowerShell** do Windows, ele na verdade irá chamar um executável chamado `dir.exe`, que fica na pasta de sistema do Windows.

O Windows sabe que o `dir` realmente foi executado corretamente através do número que ele retornar...

Para o Windows por exemplo, se qualquer programa retornar **“0”**, ele considera a execução como sucesso.

Outros sistemas operacionais seguem a mesma ideia.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-met-mai-c-est-bas-sof-c-log-par-pro-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-met-mai-c-est-bas-sof-c-log-par-pro-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-met-mai-c-est-bas-sof-c-log-par-pro-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-met-mai-c-est-bas-sof-c-log-par-pro-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-met-mai-c-est-bas-sof-c-log-par-pro-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-met-mai-c-est-bas-sof-c-log-par-pro-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
