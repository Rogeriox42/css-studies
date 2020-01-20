Flexbox

flex container tem 5 propriedades: 
flex-direction
flex-wrap 
flex-flow 
justify-content
align-items 
align-content 

flex-direction: row, column, rowreverse, columnreverse
wrap: wrap, nowrap, wrap-reverse

flex-direction: Define em qual direção os elementos filhos serão organizados 
row - Elementos serão distribuídos em forma de linha 
column -  Elementos serão distribuídos em forma de coluna 
rowreverse - Mesmo o row, mas do último para o primeiro 
columnreverse -  Mesmo que o column, mas do último para o primeiro 

wrap - Elementos filhos quebram de linha ao completar toda a área visível do elemento pai  
nowrap - Elementos filhos tem seu tamanho (largura) alterado para se adaptar a área visível do elemento pai
wrap-reverse - Elementos filhos que estiverem após a quebra de linha serão exibidos primeiro

justify-content - Altera o posicionamento de acordo com o flex-direction (Justifica verticalmente caso seja column, e horizontalmente caso seja row) 
flex-start - Alinha os elementos ao início do container  
center - Alinha os elementos ao centro do container 
flex-end - Alinha os elementos ao final do container 
space-around - Distribui antes e entre os elementos 
space-between - Distribui espaços entre os elementos 

align-items - Altera o posicionamento vertical dos elementos filhos
flex-start - Alinha de acordo com o início do container 
center - Alinha ao centro do container 
flex-end - Alinha ao fim do container 
baseline - - Alinha de acordo com a linha base do container 
stretch - Aumenta a altura dos elementos filhos para prencher o elemento pai (Não funciona se o elemento filho já tiver altura 'height' definido)

align-content 
