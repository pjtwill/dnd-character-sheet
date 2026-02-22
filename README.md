🎲 D&D Character Sheet
Uma ficha de personagem para Dungeons & Dragons feita com HTML, CSS e JavaScript puro.
Mostrar Imagem
Mostrar Imagem
Mostrar Imagem
Mostrar Imagem
</div>

📖 Sobre o Projeto
Esse projeto nasceu de um grupo de iniciantes que queria criar uma ficha digital de D&D para facilitar as sessões. A ideia era dividir as tarefas entre todos, cada um cuidando de uma parte da interface.
O problema? Todo mundo foi saindo ao longo do caminho — e sobrou só eu pra terminar. 😅
O resultado disso é que os visuais ficaram bem... distintos. Cada seção tem um estilo diferente porque cada pessoa tinha começado a sua parte do jeito que queria, e eu não sabia como padronizar tudo sem quebrar o que já estava funcionando. Algumas funcionalidades também pararam de funcionar no processo e, pela mesma razão, preferi deixar como estava a arriscar refazer a página inteira.
No fim, ficou um projeto com personalidade própria. E funciona — na maior parte do tempo. 🎲

E o melhor de tudo: dá pra imprimir a ficha direto do navegador! 🖨️
Usa o Ctrl+P e você tem uma ficha física na mão pra levar pra mesa.


📸 Exemplos

Algumas seções do projeto em funcionamento:

Atributos e Modificadores
Mostrar Imagem
Informações do Personagem
Mostrar Imagem
Ficha Completa para Impressão
Mostrar Imagem
(adicione os prints na pasta /prints do repositório)

✨ O que tem funcionando

Campos para nome, classe, raça e nível do personagem
Pontuação dos 6 atributos principais (Força, Destreza, Constituição, Inteligência, Sabedoria, Carisma)
Cálculo automático dos modificadores baseado nos atributos
Layout pensado para impressão via Ctrl+P


⚠️ O que está quebrado (e vai continuar assim por enquanto)

Alguns campos não salvam entre sessões
O layout em mobile está... criativo
Certas interações entre seções pararam de funcionar na época da debandada geral do grupo
Os estilos são visivelmente diferentes entre as seções — isso é proposital agora, vamos chamar de design colaborativo


🚀 Como usar
Sem instalação. Só abrir no navegador:
bashgit clone https://github.com/pjtwill/dnd-character-sheet.git
cd dnd-character-sheet
open index.html
Ou baixe o ZIP e abra o index.html diretamente.
Para imprimir a ficha: Ctrl+P no navegador.

📚 O que aprendi com isso

Estrutura básica de HTML e formulários
Estilização com CSS (e o caos de misturar estilos de 4 pessoas diferentes)
Manipulação do DOM com JavaScript
Como calcular modificadores de D&D: Math.floor((atributo - 10) / 2)
Que trabalho em grupo funciona melhor quando o grupo... continua no grupo


🛣️ Melhorias futuras (talvez)

 Salvar dados com localStorage
 Padronizar os estilos de uma vez por todas
 Rastrear proficiências e habilidades
 Gerenciar espaços de magia e inventário
 Layout responsivo para mobile


📄 Licença
MIT © pjtwill
