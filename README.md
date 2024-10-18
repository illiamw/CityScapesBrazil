<div align="center">    
 
## CityScapesBrazil: Cenas urbanas brasileiras, representação do nordeste a sul do Brasil


</div>

<!-- TODO: Add video -->

### Resumo


 <div text-align="justify" align="justify">    
Com a indisponibilidade de dados rotulados representativos do território brasileiro, nesta
monografia é apresentado o dataset CityScapesBrazil, composto com um conjunto de 21.485
imagens obtidas através da plataforma StreetView do Google, como motor de navegação para
o site (MAPCHANNELS, 2024), no qual é possível traçar rotas e navegar automaticamente
no StreetView. Após definido a trajetória, foi capturado a tela ao decorrer do caminho em 30
frames por segundo na dimensão de 512 por 368 pixels; por fim, com os vídeos da navegação na
trajetória gerados foi utilizado o VLC para extrair screenshots do vídeo, gerando assim o dataset
CityScapeBrazil. 
</div>


<div align="center">    
 
### [Projeto Original] Light_Domain_Adaptation: Um estudo experimental sobre aplicação prática de métodos de deep learning à segmentação semântica de áreas navegáveis e não navegáveis em tempo real


</div>

<!-- TODO: Add video -->

### Resumo


 <div text-align="justify" align="justify">    
A direção autônoma tem potencial para transformar o transporte urbano ao aumentar a segurança
e eficiência, mas enfrenta desafios relacionados à interpretação do ambiente em tempo real. A
segmentação semântica é essencial nesse processo, permitindo que sistemas autônomos identifi-
quem áreas navegáveis e obstáculos. No Brasil, há desafios específicos devido às particularidades
das vias e à dificuldade de generalizar modelos treinados com dados internacionais, como o
conjunto CityScapes. Este trabalho propõe um modelo eficiente e leve de segmentação semân-
tica, baseado no LiteSeg e integrado às arquiteturas CCT e PixMatch, adaptado ao contexto
brasileiro. O conjunto de dados CityScapesBrazil, com 21.485 imagens, foi gerado para validar
o contexto de cenas urbana brasileira. O modelo alcançou 95,4% de IoU na classe “road” e 30
FPS em alta resolução, comprovando sua eficiência e capacidade de operação em tempo real. A
proposta oferece uma solução robusta e prática para a navegação autônoma em vias brasileiras,
com alta performance e compatível com dispositivos de recursos limitados.
</div>

Projeto integral em [github@Light_Domain_Adaptation](https://github.com/illiamw/Light_Domain_Adaptation)


Os trajetos estão expostos na figura 34 e 35, e a volumetria de imagens por trajeto está presente na tabela 20, seguido de exemplos das imagens capturadas presente na figura 33.

![image](https://github.com/user-attachments/assets/785b2511-5863-4d76-a11b-2553119a565c)

![image](https://github.com/user-attachments/assets/e9c2eb4f-5871-4180-8059-676864a74ede)

![image](https://github.com/user-attachments/assets/4450515b-b4e7-4f71-9750-a97bfc02aa2f)



#### Citação   
```bibtex
@misc{ferreira2024LDA,
  author    = {William Luis Alves Ferreira},
  title     = {Um estudo experimental sobre aplicação prática de métodos de deep
learning à segmentação semântica de áreas navegáveis e não
navegáveis em tempo real},
  year         = {2024},
  howpublished = {\url{https://github.com/illiamw/Light_Domain_Adaptation}},
  note         = {Acesso em: XX out. 2XXX}
}
```
