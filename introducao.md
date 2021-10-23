# Introdução

nao sei o que falar

## Por que eu deveria entrar?

tenho uns motivos mt bons

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

Recomendo se acostumar com o [Codeforces](https://codeforces.com/) desde o início, porém ele é bem hostil e pode ser um pouco desanimador. Em contrapartida o [Atcoder](https://atcoder.jp/) é bem mais amigável, então o ideal seria utilizar os dois. ~~Existem também outros juízes famosos na seção de juízes online.~~

### Eu deveria usar um template?

Sei lá, cê quem sabe, porém desencorajo para quem está começando.

**_"Escrever push_back cria caráter"_**

