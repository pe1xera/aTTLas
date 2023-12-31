```
    .n.
   /___\                *                 *                *
   | |°|                        *
  IIIIIII     *           *           *               *
   |  /|
   | / |          *           *               *         *
   |/  |
   |  /|            ______  ______ ______ __      ______  ______  
   | / |           /\  __ \/\__  _/\__  _/\ \    /\  __ \/\  ___\ 
   |/  |______     \ \  __ \/_/\ \\/_/\ \\ \ \___\ \  __ \ \___  \ 
   |  /|_______\    \ \_\ \_\ \ \_\  \ \_\\ \_____\ \_\ \_\/\_____\ 
   | / |     ° |     \/_/\/_/  \/_/   \/_/ \/_____/\/_/\/_/\/_____/
___|/__|___[]__| _____________________________________ ~by pe1xera
 Version 0.0.1           

```  
---
# Usabilidade

Modo de uso: ./attlas.py <endereço do alvo> <quantidade de portas\>  
Opções disponíveis:  

      100 - Escaneia as 100 portas mais populares  
      1000 - Escaneia as 100 portas mais populares  
      all - Escaneia todas as portas no alvo  
      
Ex.: ./attlas.py businesscorp.com.br 100 - Escaneia as 100 portas mais populares em businesscorp.com.br


# Intenção

Com base no conteúdo ensinado pelo mestre Longatto no curso Novo Pentest Profissional e outros materiais complementares que encontrei pela internet a fora, resolvi criar um script em Python que faça o escaneamento de portas TCP abertas em um determinado host, respeitando alguns princípios como: Apresentação, Usabilidade e Agilidade, dentro - é claro - dos limites do pouco que conheço. 

Em termos de etimologia, atlas é o nome que se dá a uma coleção de mapas em que estão representadas as posições das estrelas. Também é este o nome dado pela mitologia grega ao titã condenado a carregar o peso dos céus em suas costas por toda a eternidade. TTL, por sua vez, é uma referência ao Time To Live, um campo usado no datagrama IP como um contador do tempo de vida de um pacote.

---
# Princípios


Surge, então, o **"aTTLas"**, um simples portscanner em Python, desenvolvido no método que apelidei de 'scripting like a n00b' - o qual é autoexplicativo.

O aTTLas não tem a pretensão de ser melhor do que qualquer script existente e sequer ser comparável a qualquer deles, servindo apenas como um método para colocar em prática aquilo que aprendi, servindo como minha primeira ferramenta autoral. 

Dito isso, querido leitor, também não se trata de um script estéril e sem utilidade prática. Na realidade, aTTLas pode ser bastante plausível, a depender das suas intenções.

---

![](https://pe1xera.github.io/scripting.png)
