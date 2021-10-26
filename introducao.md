# Introdução

Mais do que programar no dia a dia, aqui a ideia é usar a programação e os recursos computacionais para resolver problemas de diferentes tipos. Além da diversão em resolver problemas, temos a satisfação em resolver os difíceis!

## Por que eu deveria começar?

Durante a jornada nesse mundo encontramos benefícios como

<ul>
  <li>Aprimoramento da lógica de programação: Ao resolver problemas conseguimos desenvolver muito a
  lógica de programação</li>
  <li>Algoritmos e Estrutura de Dados: Na jornada passamos a entender como funcionam algoritmos e estrutura de dados de diversos tipos. Usamos esse <em>poder</em> para resolver problemas mais sofisticados e os problemas clássicos. </li>
  <li>Avanço na graduação: Diversas coisas vistas nesse mundo podem ser estudadas em um semestre mais
  avançado de um curso de graduação. Um bom exemplo disso são os grafos, a notação assintótica e os diferentes tipos de algoritmos para se resolver problemas: gulosos, força bruta, programação dinâmica e etc.</li>
  <li>Processos seletivos: Diversas empresas utilizam problemas semelhantes aos vistos em contests. Um exemplo disso é o site Leetcode e o Lintcode que agrupam essas questões por empresas.</li>
</ul>

## Por onde começar?

Bom, a maior parte dessa jornada consiste em resolver problemas, e para isso existem os **juízes online**, que resumidamente são sites com problemas e você pode enviar uma solução em alguma linguagem de programação, e então ele julga de acordo com uma série de casos de teste escondidos e te dá um veredito. Os sites que recomendamos são [Codeforces](https://codeforces.com/), [AtCoder](https://atcoder.jp/) e [Neps Academy](https://neps.academy/). ~~Você pode ver mais sobre na seção de juízes online.~~

Porém também é importante ter um fluxo, algo para te guiar. Recomendamos o livro [Competitive Programmer's Handbook](https://cses.fi/book/book.pdf), que vai do zero, explicando noções da linguagem C++, até um nível bem considerável de dificuldade. Além de gratuito, ele conta com um [_problemset_](https://cses.fi/problemset/) com diversos problemas clássicos divididos por tópicos, sendo que alguns estão explicados no próprio livro.

## Dúvidas frequentes

Algumas dúvidas que muitos (inclusive eu) já se perguntaram quando estavam começando.

### Por que as pessoas usam C++ em maratona?

**Ele é rápido**. Uma linguagem compilada tende a ter mais desempenho do que uma interpretada, como Python. Outros dois motivos bem comuns são: a biblioteca padrão do C++ (STL) possui diversas estruturas já implementadas (de forma eficiente), como `vector`, `queue` ou `map`, por exemplo. Por fim, a maioria dos competidores do mundo inteiro utilizam essa linguagem, então é mais fácil para encontrar ajuda, algoritmos implementados, etc. Normalmente os problemas de programação competitiva têm solução esperada baseada em C++, então se seu código nessa linguagem não passou significa que a lógica não é eficiente, e não a linguagem.

### Então preciso aprender C++ para começar a treinar?

**Não**. Em geral, diferenças de tempo e memória só são significativas para os que já estão há um tempo em programação competitiva e precisam usar estruturas de dados mais complexas. Para quem está começando, o objetivo é desenvolver o _problemsolving_ e o raciocínio lógico, então não há necessidade de se preocupar com a linguagem _(porém é altamente recomendado pelos motivos da pergunta anterior)_.

### cin/cout ou scanf/printf?

De fato o scanf/printf são mais rápidos, porém com essas linhas mágicas no seu código você pode dessincronizar os dois _I/O Streams_ e a diferença se torna irrisória. **Usa o que você achar melhor**.

```c++
int main() {
    // linhas mágicas
    ios::sync_with_stdio(false);
    cin.tie(NULL);

    // seu código
}
```

### Qual o melhor juíz online pra começar?

Recomendo se acostumar com o [Codeforces](https://codeforces.com/) desde o início, porém ele é bem hostil e pode ser um pouco desanimador. Em contrapartida o [AtCoder](https://atcoder.jp/) é bem mais amigável, então o ideal seria utilizar os dois. ~~Existem também outros juízes famosos na seção de juízes online.~~

### Eu deveria usar um template?

Sei lá, cê quem sabe, porém desencorajo para quem está começando.

**"Escrever `push_back` cria caráter"**

