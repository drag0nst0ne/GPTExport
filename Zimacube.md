# ChatGPT Conversation Export

## Metadata
- Title: Alternativas ao ZimaCube Pro
- URL: https://chatgpt.com/c/6a26eac4-9b48-83e9-b14d-c680e4d7941d
- Export Time (UTC): 2026-09-01T00:21:36.137Z
- Model: Unknown

## Conversation

## User

o zimacube Pro (i5-1235U/16GB/256GB) é um pequeno cabinete/pc montado pra nas, mas custa 1300 dolares, queria algo parecido, mas sem falir

---

## Assistant

Se o que te atrai no ZimaCube Pro não é a marca, mas sim o conceito ("caixa compacta + NAS + baixo consumo + Docker + Plex/Jellyfin + Proxmox"), então sinceramente eu não pagaria US$ 1300 nele.

O ZimaCube Pro é legal porque junta tudo num gabinete bonito: i5-1235U, várias baias SATA, NVMe, rede rápida e expansão PCIe. Mas boa parte desse valor é pela integração e pelo design. [![image](https://www.google.com/s2/favicons?domain=https://awesomeminipc.com&sz=128)Awesome Mini PC](https://awesomeminipc.com/devices/icewhale-zimacube-pro?utm_source=chatgpt.com)

### AOOSTAR WTR Pro

- Ryzen 7 5825U

- Consome pouca energia

- Suporta vários discos

- Comunidade de homelab gosta bastante

- Costuma custar uma fração do ZimaCube Pro

Para:

- TrueNAS

- Unraid

- Plex/Jellyfin

- Docker

- Immich

### AOOSTAR WTR Max

- Versão mais robusta

- Até 6 baias SATA

- Bem parecido com o conceito do ZimaCube

- Ainda costuma sair muito mais barato

### Minisforum MS-01

- Não é NAS pronto

- Mas é um monstro para Proxmox

- Rede rápida

- Excelente expansão

- Dá para usar gabinete externo ou DAS depois

Muito popular entre o pessoal de homelab. [![image](https://www.google.com/s2/favicons?domain=https://shop.zimaspace.com&sz=128)Zima Store Online+1](https://shop.zimaspace.com/blogs/zima-campaign-hub/zimacube-hardware-nas-review?utm_source=chatgpt.com) chega facilmente perto de R$ 7.000–9.000 após impostos e frete para o Brasil. | Orçamento | Escolha |

|------------|----------|

| Até R$ 2.500 |  |

| Até R$ 4.000 |  |

| Até R$ 5.000 |  |

| Quero algo parecido com ZimaCube |  |

Para o seu perfil especificamente, eu provavelmente iria de AOOSTAR WTR Pro ou um N100 com 4 portas LAN e colocaria Proxmox. Você ganharia 90% da utilidade do ZimaCube Pro gastando talvez 30–40% do dinheiro.

---

## User

seguinte: meu 3600x q eu tinha estragou de vez, entortei talvez até quebrei alguns pinos quando tirei o watercooler e a cpu saiu colada junto. F...

isso aconteceu pois tive q fazer manutenção pq a placa mae teve um curto, pois acabou respingando agua nela.

---

## User

eu estou pensando totalmente em comprar uma nova APU no futuro, para poder rodar e não precisar de placa de video

---

## User

é exatamente para nas que estou falando, tenho meu 7600 já, 32gb de ram

---

## User

There really isn't anything more power efficient but the N100 isn't the best for a NAS device. I lacks enough PCIe lanes to be a good NAS.

But there seems to be a lot of misinformation about the TDP of processors. The TDP is normal-high usage (according to Intel), but if the CPU is sitting idle then any modern CPU is going to draw very little power. The CPUs in NAS, that only do NAS things (serving files, not running VMs) is going to be idle most of the time. Because of that, you won't see much power usage difference between the N100 and the low power AMD processors. Many of which will be better suited for a NAS then the N100.

Basically, don't focus too much on the TDP. As long as you aren't getting some server class or gaming desktop CPU you should be fine

---

## User

https://www.reddit.com/r/homelab/comments/1gq4w9b/more_power_efficient_than_intel_n100/?show=original

---

## User

https://pt.aliexpress.com/item/1005012311453999.html?spm=a2g0o.productlist.main.2.517d6797SYjWSz&algo_pvid=e6c4c01a-7c1a-4025-9c29-231a7cb45b2e&pdp_ext_f=%7B%22order%22%3A%2234%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012311453999%7C_p_origin_prod%3A

---

## User

UGREEN NAS DH4300 Plus

---

## User

https://www.amazon.com.br/Compartimento-QNAP-armazenamento-anexado-hardware/dp/B07K4RC7X9/ref=sr_1_20?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&s=computers&sr=1-20

---

## User

https://www.reddit.com/r/homelab/comments/1bvmhr7/ryzen_5600g_vs_n100305_for_nas_build/?show=original

---

## User

Ryzen 7 5825U

---

## User

grande duvida:

existe alguma forma de "desligar" um server rodando localmente se não tem nenhum player, mas voltar sozinho caso alguem tente conectar?

---

## User

fui pouco especifico, era para ter dito que o server era de mine, digamos que eu e meus amigos estamos jogando mais que um modpack ao mesmo tempo, então eu crio uns 3 servers separados, para nao ter que ficar abrindo e fechando, poderia deixar os 3, mas ai pesaria muito...

mas e se eu não estiver jogando, e só algum dos meus amigos quiser entrar e trabalhar sozinho na base

---

## User

pensando agora, se eu vou ter 64gb de ram, é melhor ter 2x32 ou 4x16?

---

## User

https://www.lincplustech.com/news/the-best-cpu-for-nas-a-2025-guide-for-builders-and-buyers.html

---

## User

acabei de descobrirque intel é melhor para jellyfin por causa de Intel Quick Sync

---

## User

a resposta é "basicamente só eu usando Kodi dentro de casa" kkkkkkkkkk

---

## User

e qual placa mae é boa para isso?

---

## User

posso também hospedar meus proprios sites, apps proprios com um HS?

---

## User

basicamente só eu iria utilizar, mas eu ia querer usar pelo telefone, no trabalho ou fora de casa

---

## User

nao tem como eu usar o app do hotel no trabalho sem pagar nada?

---

## User

https://www.reddit.com/r/DataHoarder/comments/106tcb2/quiet_hdds_for_nas_in_working_room/

---

## User

consegue descobrir pra mim em lojas como kabum, pichau, terabyte, se é mais vantagem comprar um hd de maior tamanho, 12, 14 16 20 tb ou ou comprar2 de menor, 8, 10

---

## User

acho q vou começar com 1 de 8 ou 10 e depois compro outros

---

## User

e tem outro fator, eu sempre apago tudodepois de terminar de assisitr, não quero montar uma biblioteca,

---

## User

my thing is:

meu tdah faz eu querer assistir tudo, ter interesse em ver tudo, e querer baixar tudo de uma vez, mas deixar sempre "depois eu assisto", agora não to afim, e as vezes nem assistir nada.

---

## User

poderia eu montar meu proprio?

---

## Assistant

Que situação complicada. E infelizmente o que aconteceu com o Ryzen é mais comum do que parece.

Nos processadores AM4 (como o seu AMD Ryzen 5 3600X), a CPU fica presa ao soquete por uma trava relativamente simples. Quando a pasta térmica endurece, o processador pode ficar "colado" no bloco do water cooler. Se você puxar o cooler reto para cima sem antes girar um pouco, a CPU pode sair junto mesmo com a trava fechada.

O problema agora é separar os danos em duas categorias:

### 1. A placa-mãe que tomou água

Dependendo de onde a água caiu:

- Pode ter queimado apenas algum componente de alimentação.

- Pode ter causado oxidação.

- Pode ter matado a placa completamente.

- Pode até ter sobrevivido e o problema atual ser só a CPU.

Sem testes fica difícil saber.

### 2. O Ryzen com pinos tortos

Nem todo Ryzen com pinos tortos está perdido.

Se os pinos:

- Apenas entortaram → muitas vezes é possível alinhar.

- Quebraram poucos pinos → às vezes ainda funciona, dependendo de quais eram.

- Quebraram vários pinos → a chance diminui bastante.

O ideal seria ver fotos da parte de baixo da CPU.

### Antes de considerar tudo perdido

Se ainda tiver o processador:

- Tire fotos nítidas da parte dos pinos.

- Tire fotos em vários ângulos.

- Envie aqui.

Dá para avaliar:

- Quantos pinos estão tortos.

- Se algum parece quebrado.

- Se existe chance real de recuperação.

Já vi Ryzen 3000 voltarem à vida após alinhar dezenas de pinos.

### Pensando no futuro NAS

Existe um lado positivo nessa história.

Você já estava cogitando:

- NAS

- Homelab

- Proxmox

- Jellyfin

- Immich

Se a placa-mãe e o 3600X realmente morreram, talvez não faça sentido investir dinheiro para ressuscitar uma plataforma AM4 antiga, dependendo do custo.

Por exemplo:

| Situação | O que eu faria |
| --- | --- |
| CPU recuperável e placa ok | Consertaria |
| CPU recuperável e placa morta | Avaliaria custo de outra AM4 usada |
| CPU morta e placa morta | Partiria para plataforma nova |

Se você já estava planejando um PC novo em algum momento, pode ser mais interessante direcionar o orçamento para isso do que gastar em peças usadas sem garantia.

Uma curiosidade: o fato da CPU ter saído colada no water cooler não significa que ela morreu. O evento realmente preocupante da história é a água ter causado curto na placa-mãe. Em muitos casos, a CPU sobrevive a esse tipo de incidente e quem morre é a placa.

Se você tiver fotos da CPU (principalmente dos pinos) e souber qual placa-mãe era, consigo fazer uma avaliação bem mais precisa da situação.

---

## Assistant

Acho uma ideia bastante sensata no seu cenário atual.

Se o objetivo é **voltar a ter um PC funcional sem depender da RTX 3060 Ti**, uma APU resolve vários problemas de uma vez:

- Você volta a ter vídeo mesmo se vender a placa de vídeo.

- Consome menos energia.

- Tem menos peças para dar problema.

- Pode montar um sistema provisório e depois adicionar uma GPU dedicada se quiser.

- Se um dia transformar o PC em servidor/NAS, a iGPU continua útil para transcodificação e acesso local.

### O que eu consideraria hoje

#### Melhor custo-benefício: AMD Ryzen 5 8600G

- 6 núcleos / 12 threads

- Radeon 760M integrada

- Roda Windows tranquilamente

- Jogos leves e competitivos sem GPU dedicada

- Excelente eficiência

Para:

- Trabalho

- Navegação

- Kodi

- Jellyfin

- Programação

- Rocksmith

- Jogos leves

É provavelmente o ponto ideal.

#### Mais forte: AMD Ryzen 7 8700G

- 8 núcleos / 16 threads

- Radeon 780M integrada

Hoje é praticamente a APU mais poderosa da AMD para desktop.

Consegue rodar muita coisa em:

- 1080p baixo

- 1080p médio

- alguns jogos até em qualidade razoável

Mas costuma custar significativamente mais.

### Um detalhe importante

Você comentou anteriormente que planejava algo como:

- Ryzen 7600

- B650

- 32 GB RAM

- RTX 3060 Ti

Se a RTX 3060 Ti ainda estiver funcionando, uma alternativa interessante seria:

- Comprar um 8600G ou 8700G.

- Usar apenas a iGPU inicialmente.

- Guardar ou vender a RTX.

- Mais tarde decidir se realmente precisa de GPU dedicada.

Muita gente descobre que usa o PC 90% do tempo para tarefas que uma APU moderna faz tranquilamente.

### Para NAS e homelab

Uma APU AM5 também tem uma vantagem interessante:

Se daqui alguns anos você trocar de máquina, ela pode virar servidor.

Por exemplo:

- Proxmox

- Immich

- Sonarr

- Radarr

- Jellyfin

- Nextcloud

- Watcharr

Tudo isso roda muito bem num 8600G ou 8700G.

### O que eu faria no seu lugar

Se a situação financeira exigir equilíbrio:

- Placa-mãe B650 básica

- 32 GB DDR5

- Ryzen 5 8600G

- SSD NVMe de 1 TB

Isso cria uma base moderna, com vídeo integrado forte e possibilidade de upgrade futuro.

A única coisa que eu evitaria é investir muito dinheiro para tentar "ressuscitar" um AM4 danificado se você já está considerando uma plataforma nova. Dependendo do valor do conserto, o dinheiro pode render mais entrando diretamente numa configuração AM5.

---

## Assistant

Ah, aí muda bastante a conversa.

Se o objetivo é um **NAS/homelab** e você já tem um PC principal com:

- AMD Ryzen 5 7600

- 32 GB DDR5

- RTX 3060 Ti

então eu não compraria uma APU AM5 cara tipo 8600G ou 8700G para virar NAS.

O motivo é simples: pelo preço de uma dessas APUs você consegue montar praticamente um servidor inteiro baseado em hardware usado ou em uma plataforma de baixo consumo.

## O que eu faria

### Opção 1 — N100 (minha favorita)

Intel Processor N100

Vantagens:

- Consumo baixíssimo (6–15 W na maior parte do tempo)

- Tem vídeo integrado

- Tem Quick Sync para Jellyfin/Plex

- Roda Proxmox

- Roda Immich

- Roda Sonarr/Radarr/Prowlarr

- Roda Nextcloud

- Roda Watcharr

Para um homelab doméstico costuma sobrar desempenho.

Muita gente roda:

- 20+ containers Docker

- Jellyfin

- Home Assistant

- Pi-hole

- VPN

- Immich

sem problemas.

### Opção 2 — Aproveitar o acidente para montar um NAS AM4 barato

Como seu 3600X já está comprometido, você poderia procurar algo como:

- AMD Ryzen 5 5600G usado

- placa-mãe B450 usada

ou

- AMD Ryzen 5 4600G usado

A vantagem é que:

- já tem vídeo

- consome pouco

- sobra desempenho

Mas o consumo ainda será maior que um N100.

### Opção 3 — Mini PC dedicado

Algo baseado em:

- N100

- N97

- N150

- N200

com duas portas de rede e NVMe.

Depois você liga um gabinete USB para os HDs ou um DAS.

Muita gente está abandonando os NAS comerciais justamente por isso.

## O único motivo para eu comprar uma APU forte

Eu consideraria um 8600G/8700G para NAS apenas se você quisesse:

- Várias VMs pesadas

- IA local

- Laboratório de Kubernetes

- Transcodificar vários vídeos simultaneamente

- Servidor de jogos

Caso contrário, seria um desperdício de energia e dinheiro para funções como:

- Jellyfin

- Sonarr

- Radarr

- Immich

- Nextcloud

- Backup

- Watcharr

## Seu cenário específico

Se você me dissesse:

"Gabriel, quero um NAS para 2–6 HDs, Jellyfin, Sonarr, Radarr, Immich, Watcharr, backups e alguns containers"

eu escolheria um N100 sem pensar duas vezes.

Se você dissesse:

"Quero um servidor que também rode IA local, várias VMs Windows e experimentos pesados"

aí eu olharia para um 5600G, 5700G ou algo semelhante.

Para uso doméstico típico, o N100 entrega um resultado surpreendentemente próximo na prática, consumindo algo como um terço da energia.

---

## Assistant

A pessoa que escreveu isso está, no geral, correta.

O erro mais comum de quem começa a pesquisar NAS é pensar:

CPU de 65 W = consome 65 W o tempo todo

CPU de 6 W = consome 6 W o tempo todo

Não funciona assim.

O TDP é principalmente uma medida térmica para dimensionar refrigeração, não o consumo real em repouso.

Por exemplo:

| CPU | TDP |
| --- | --- |
| Intel Processor N100 | 6 W |
| AMD Ryzen 5 5600G | 65 W |
| AMD Ryzen 7 5700G | 65 W |

Mas em um NAS parado, servindo arquivos:

- N100 pode ficar em 4–8 W

- 5600G pode ficar em 8–15 W

- 5700G pode ficar em 10–15 W

A diferença existe, mas não é o abismo que muita gente imagina.

## O ponto mais importante: PCIe lanes

Aqui está a crítica mais válida ao N100.

O N100 foi criado para:

- mini PCs

- thin clients

- roteadores

- pequenos servidores

Não para NAS grandes.

Ele tem poucas pistas PCIe disponíveis.

Isso significa que você fica limitado para expandir:

- controladoras SATA

- placas 10 GbE

- HBAs

- SSDs NVMe adicionais

### Exemplo

Imagine que daqui a 3 anos você queira:

- 6 HDs

- 2 SSDs NVMe

- rede 10 GbE

- Jellyfin

- Immich

Um N100 pode começar a ficar apertado.

Já um 5600G ou 5700G numa B550 costuma ter muito mais flexibilidade.

## No seu caso específico

Você não está montando:

- um NAS Synology de 2 baias

Você é o tipo de usuário que fala sobre:

- Proxmox

- Docker

- Sonarr

- Radarr

- Jellyfin

- Immich

- Watcharr

- automações

- múltiplos serviços

Então eu acho que você está mais perto do perfil "homelab" do que do perfil "NAS simples".

## O que eu olharia

Se fosse comprar uma APU para NAS hoje:

### Melhor equilíbrio

AMD Ryzen 5 5600G

Porque:

- barato usado

- vídeo integrado

- 6c/12t

- sobra desempenho

- muitas lanes PCIe para um NAS doméstico

- excelente suporte Linux

### Se encontrar barato

AMD Ryzen 7 5700G

Vantagens:

- 8c/16t

- ótimo para VMs

- ótimo para containers

- ótimo para Proxmox

## O que eu faria se estivesse na sua situação

Você já tem um PC principal AM5.

Então eu procuraria:

- Ryzen 5600G usado

- placa B550 usada

- 32 GB DDR4 (ou o que conseguir barato)

e transformaria isso no servidor.

Você teria:

- mais expansão que um N100

- mais potência para futuras VMs

- mais capacidade para crescer

- consumo ainda bastante razoável para um homelab doméstico

Aí sim eu concordo com a frase que você trouxe: para um NAS/homelab que pretende crescer, **a quantidade de PCIe e possibilidades de expansão costuma importar mais do que perseguir os menores watts possíveis no papel**. O gasto elétrico real entre um N100 bem configurado e um 5600G em repouso geralmente é bem menor do que as especificações de TDP fazem parecer.

---

## Assistant

Li esse tópico e concordo bastante com a direção da discussão.

O que você trouxe corrige uma simplificação que muita gente faz quando recomenda N100 para tudo.

### O que o pessoal do Reddit acertou

A ideia principal é:

"O N100 é extremamente eficiente, mas isso não significa automaticamente que é a melhor CPU para NAS."

Isso é verdade. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+1](https://www.reddit.com/r/homelab/comments/1gq4w9b/more_power_efficient_than_intel_n100/?utm_source=chatgpt.com)

Para um NAS "de verdade", especialmente quando você começa a pensar em:

- vários HDs

- cache NVMe

- HBA

- rede 10 GbE

- Proxmox

- expansão futura

o gargalo costuma ser conectividade e PCIe, não CPU. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+2![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+2](https://www.reddit.com/r/homelab/comments/1ay281g?utm_source=chatgpt.com)

### Sobre o consumo

Esse trecho também está correto:

CPUs modernas ficam muito tempo em idle.

Um NAS doméstico geralmente passa a maior parte do dia:

- esperando requisições

- servindo alguns arquivos

- rodando containers leves

Então o consumo em idle acaba importando mais que o TDP nominal. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+1](https://www.reddit.com/r/homelab/comments/1ilmhj8?utm_source=chatgpt.com)

Muita gente fica surpresa ao descobrir que um desktop moderno bem configurado pode ficar em consumos muito baixos quando parado. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit](https://www.reddit.com/r/homelab/comments/1ilmhj8?utm_source=chatgpt.com)

### Onde o N100 continua brilhando

Se você quer:

- Jellyfin

- Immich

- Sonarr

- Radarr

- Prowlarr

- Nextcloud

- Home Assistant

e pretende ficar com:

- 2 a 4 discos

- 1 NVMe

- rede 1 GbE ou 2.5 GbE

o N100 continua sendo uma escolha excelente. [![image](https://www.google.com/s2/favicons?domain=https://homelabstarter.com&sz=128)HomeLab Starter+1](https://homelabstarter.com/homelab-n100-mini-pc-builds/?utm_source=chatgpt.com)

### Onde eu acho que você se encaixa

Pelas coisas que você costuma comentar:

- gosta de experimentar software

- pensa em Proxmox

- quer centralizar serviços

- cogita Immich

- cogita automações

- já pensa em NAS como projeto de longo prazo

Você me parece mais próximo do perfil **homelab expansível** do que do perfil **NAS básico**.

Nesse cenário, eu começaria a olhar com muito carinho para:

- Ryzen 5600G

- Ryzen 5700G

- Intel i5-8500T

- Intel i5-9500T

- Intel i3 de 10ª/12ª geração

em vez de um N100. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+1](https://www.reddit.com/r/homelab/comments/1ilmhj8?utm_source=chatgpt.com)

### O detalhe que quase ninguém menciona

Num NAS com vários discos, muitas vezes os HDs consomem mais energia que a diferença entre as CPUs.

Exemplo aproximado:

- N100: 8–12 W idle

- 5600G: 12–18 W idle (dependendo da placa e configuração)

- 4 HDs mecânicos: 20–35 W sozinhos

Ou seja, às vezes você economiza 5 W na CPU e perde isso facilmente em um único HD que não entra em spin-down. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+1](https://www.reddit.com/r/homelab/comments/16hjl72?utm_source=chatgpt.com)

### Minha conclusão para o seu caso

Se você me dissesse:

"Quero um NAS para sempre ficar com 2 ou 3 discos."

Eu diria N100.

Mas quando você fala em algo inspirado no ZimaCube, com possibilidade de crescer, colocar mais armazenamento, talvez usar Proxmox e expandir ao longo dos anos, eu concordo com o pessoal do Reddit:

**A limitação de PCIe do N100 é uma preocupação mais relevante do que a diferença de consumo elétrico entre ele e uma APU moderna como um 5600G.** [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+2![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+2](https://www.reddit.com/r/homelab/comments/1ay281g?utm_source=chatgpt.com)

Na sua situação, eu provavelmente procuraria um **5600G usado** e uma **B550 usada** antes de investir num N100. Você ganharia muito mais margem para crescimento e ainda teria um servidor bastante econômico para ficar ligado 24/7. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+1](https://www.reddit.com/r/homelab/comments/1sa01km/mobo_and_cpu_for_low_power_10bay_nas/?utm_source=chatgpt.com)

---

## Assistant

Sim, mas talvez não da forma que a maioria imagina.

Quando falamos de NAS, os HDs específicos para NAS fazem mais diferença em **confiabilidade, vibração e operação 24/7** do que em consumo elétrico.

## Consumo de energia

Vamos pegar exemplos típicos:

| Tipo | Idle | Leitura/Escrita |
| --- | --- | --- |
| Desktop 4 TB | 3–5 W | 5–8 W |
| NAS 4 TB | 3–5 W | 5–8 W |
| Enterprise 12 TB | 5–8 W | 7–12 W |

A diferença normalmente é pequena.

Um NAS com 4 discos pode gastar:

- 12–20 W só com os HDs parados

- 20–40 W durante uso

Ou seja, o processador muitas vezes deixa de ser o principal consumidor.

## Onde os HDs NAS realmente ajudam

### TLER/ERC

HDs NAS possuem recursos que evitam que um disco "desapareça" do array ao encontrar um erro de leitura.

Exemplos:

- Seagate IronWolf

- Western Digital Red Plus

Eles tentam recuperar erros por pouco tempo e devolvem o controle ao sistema.

Num RAID isso é importante.

### Vibração

Em um gabinete com:

- 4 discos

- 6 discos

- 8 discos

um disco gera vibração que afeta os outros.

Modelos NAS costumam ser projetados para isso.

Em um NAS caseiro de 2 discos a diferença é pequena.

Em um de 6+ discos começa a aparecer.

### Operação contínua

Discos NAS são feitos assumindo:

- 24 horas por dia

- 7 dias por semana

- múltiplos acessos simultâneos

Um disco desktop comum normalmente é projetado pensando em um PC que passa parte do tempo desligado.

## O segredo que o pessoal do homelab usa

Muita gente compra HDs enterprise usados.

Exemplos comuns:

- Seagate Exos X18

- Seagate Exos X20

- Western Digital Ultrastar DC HC550

Porque:

- São extremamente robustos.

- Foram feitos para data centers.

- Costumam custar muito menos por TB.

Desvantagens:

- Mais barulho.

- Mais vibração.

- Consumo um pouco maior.

## Para o seu projeto

Se eu estivesse montando um NAS para:

- Jellyfin

- Immich

- Sonarr/Radarr

- Backups

- Arquivos pessoais

eu escolheria nesta ordem:

### Melhor custo-benefício

- Exos usados com SMART saudável

### Melhor equilíbrio

- IronWolf

### Mais silencioso

- WD Red Plus

## Uma observação importante

Muitos discos vendidos como "WD Red" antigos usam tecnologia SMR.

Para NAS, geralmente prefira:

- WD Red Plus

- WD Red Pro

- IronWolf

- Exos

e evite modelos SMR quando possível.

SMR pode ficar extremamente lento em reconstruções de RAID e gravações pesadas.

Se você estiver pensando em um NAS de 4 a 8 baias inspirado no ZimaCube, eu diria que a escolha dos discos vai impactar mais a experiência final do que escolher entre um N100 e um 5600G. O processador raramente será o gargalo; armazenamento, ruído, expansão e confiabilidade costumam ser os fatores que mais aparecem depois de alguns meses de uso.

---

## Assistant

Não consigo abrir diretamente esse link do AliExpress porque a página depende de scripts e o acesso pelo meu navegador de busca falhou.

Você pode me mandar qualquer uma destas opções?

- **Print da página**

- **Título completo do anúncio**

- **Especificações principais** (CPU, placa-mãe, quantidade de SATA, RAM etc.)

- **Foto principal do produto**

Com isso consigo analisar:

- Se é um bom negócio para NAS

- Quantos HDs suporta de verdade

- Se o chipset é confiável

- Limitações de PCIe

- Consumo elétrico esperado

- Compatibilidade com TrueNAS, Unraid e Proxmox

- Possíveis "pegadinhas" do anúncio

AliExpress está cheio de placas NAS chinesas interessantes (CWWK, Topton, BKHD, N100/N305, Ryzen Embedded etc.), mas algumas parecem ótimas no papel e depois têm limitações escondidas nas portas SATA, PCIe ou rede. Uma foto ou o título já costuma ser suficiente para eu identificar o modelo.

---

## Assistant

Se você está comparando o **UGREEN DH4300 Plus** com a ideia de montar seu próprio NAS, eu diria que ele ocupa um meio-termo muito interessante.

### O que eu gostei

- 4 baias para HDs

- Rede 2.5 GbE

- Consumo baixo

- Silencioso

- Interface amigável (UGOS)

- Docker suportado

- Até 120 TB de armazenamento bruto [![image](https://www.google.com/s2/favicons?domain=https://nascompares.com&sz=128)NAS Compares+4![image](https://www.google.com/s2/favicons?domain=https://www.techradar.com&sz=128)TechRadar+4![image](https://www.google.com/s2/favicons?domain=https://nascompares.com&sz=128)NAS Compares+4](https://www.techradar.com/computing/ugreen-nasync-dh4300-plus-review?utm_source=chatgpt.com) de RAM soldada.  RAM não expansível

- Sem slot PCIe

- Sem upgrade de CPU

- Sem NVMe interno para cache

- Sem grande margem de crescimento  pode virar uma limitação daqui a alguns anos.

### Comparação com um NAS montado por você

| Característica |  | NAS caseiro com 5600G |
| --- | --- | --- |
| Facilidade | Excelente | Média |
| Consumo | Excelente | Muito bom |
| Docker | Sim | Sim |
| Jellyfin | Sim | Sim |
| Immich | Sim | Sim |
| Upgrade de RAM | Não | Sim |
| Upgrade de CPU | Não | Sim |
| PCIe extra | Não | Sim |
| HBA SAS | Não | Sim |
| 10 GbE futuro | Difícil | Fácil |
| VMs pesadas | Limitado | Muito melhor |

### Para o Gabriel especificamente

Pelo que você costuma planejar:

- Proxmox

- Homelab

- Immich

- Jellyfin

- Sonarr

- Radarr

- Watcharr

- Possível IA local no futuro

eu vejo dois caminhos:

**Quero praticidade**

→ DH4300 Plus

**Quero um projeto para crescer durante 5–10 anos**

→ montar um NAS próprio com plataforma x86

O ponto decisivo para mim é que você já demonstrou interesse em expansão e experimentação. Por isso, pessoalmente, eu provavelmente montaria um NAS próprio usando um 5600G/5700G usado ou alguma plataforma Intel de baixo consumo, em vez de ficar preso aos 8 GB soldados do DH4300 Plus.

Mas se você encontrar o DH4300 Plus perto de **R$ 1.800–2.000 sem discos**, ele começa a ficar muito atraente como solução pronta. Acima de **R$ 3.000**, eu começaria a olhar com bastante carinho para um NAS montado por você mesmo.

---

## Assistant

Se esse Amazon que você mandou é realmente o ****, eu teria bastante cuidado.

### O que ele tem de bom

- 4 baias SATA hot-swap.

- Sistema QNAP bastante maduro.

- RAID pronto e fácil de configurar.

- Porta SFP+ 10 GbE integrada. [![image](https://www.google.com/s2/favicons?domain=https://www.qnap.com&sz=128)QNAP NAS+2![image](https://www.google.com/s2/favicons?domain=https://www.qnap.com&sz=128)QNAP NAS+2](https://www.qnap.com/pt-br/product/ts-431kx/specs/hardware?utm_source=chatgpt.com) 4 núcleos lançado há muitos anos, com apenas 2 GB de RAM de fábrica (expansível até 8 GB). aco para esse tipo de uso.

### Comparando com o que você estava pensando

| Característica |  | NAS caseiro 5600G |
| --- | --- | --- |
| Baias | 4 | Depende do gabinete |
| Consumo | Menor | Um pouco maior |
| Facilidade | Excelente | Média |
| Docker | Limitado | Excelente |
| VMs | Muito limitado | Excelente |
| Upgrade CPU | Não | Sim |
| Upgrade RAM | Até 8 GB | Muito maior |
| PCIe extra | Não | Sim |
| HBA SAS | Não | Sim |
| Vida útil como homelab | Curta | Longa |

### Minha opinião para o seu caso

Se você fosse um usuário que só quer:

- guardar filmes

- guardar fotos

- fazer backup

eu diria para pegar um NAS pronto.

Mas você já fala de:

- Proxmox

- Jellyfin

- Immich

- Sonarr

- Radarr

- Docker

- expansão futura

Então eu acho que você iria bater no teto desse QNAP relativamente rápido.

O mais curioso é que, depois do azar com o 3600X e da conversa sobre APUs, você acabou chegando exatamente no perfil de usuário que costuma ficar mais satisfeito com um NAS próprio baseado em:

- 5600G

- 5700G

- Intel 12ª geração usada

- placa-mãe com várias SATA

- TrueNAS / Unraid / Proxmox

do que com um NAS ARM fechado.

Se esse QNAP estivesse por algo como **R$ 1.500–2.000 usado**, eu consideraria. Se estiver perto de **R$ 4.000–5.000**, eu montaria meu próprio servidor sem pensar duas vezes.

---

## Assistant

Esse tópico do Reddit foi interessante porque o autor chegou exatamente na mesma conclusão que você está começando a chegar.

O cara perguntou:

"Por que eu compraria um N305 se consigo um 5600G mais barato?"

E a resposta predominante foi:

"Se você realmente precisa só de um NAS, tanto faz. Mas se existe chance de crescer, o 5600G é mais interessante." [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit](https://www.reddit.com/r/homelab/comments/1bvmhr7?utm_source=chatgpt.com)

### O que eu tirei desse tópico para o SEU caso

O autor do post tinha:

- NAS ZFS

- 4 discos

- sem VMs

- sem transcoding

- sem game server

Você tem planos de:

- Jellyfin

- Sonarr

- Radarr

- Immich

- Minecraft 400+ mods

- Docker

- talvez Proxmox

- expansão futura

Você está muito mais próximo de um homelab pesado.

### O argumento do N100 perde força quando aparece Minecraft

Para:

- armazenamento

- backups

- Nextcloud

- Pi-hole

o N100 é excelente. [![image](https://www.google.com/s2/favicons?domain=https://homelabstarter.com&sz=128)HomeLab Starter+1](https://homelabstarter.com/homelab-nas-build-guide/?utm_source=chatgpt.com)

Mas Minecraft modded é outra categoria.

Um servidor com:

- All The Mods

- Enigmatica

- Prominence

- packs de 300–500 mods

adora:

- RAM

- clock alto

- cache grande

- mais threads disponíveis

Aí o 5600G ou 5700G começam a parecer muito melhores.

### O detalhe mais importante do Reddit

Várias pessoas levantaram exatamente a preocupação que você trouxe antes:

PCIe lanes. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+1](https://www.reddit.com/r/homelab/comments/1bvmhr7?utm_source=chatgpt.com)

O N100 possui apenas 9 lanes PCIe. [![image](https://www.google.com/s2/favicons?domain=https://forums.spacerex.co&sz=128)SPACEREX+1](https://forums.spacerex.co/t/low-power-diy-nas-server-build-with-the-asrock-n100m/1252?utm_source=chatgpt.com)

Isso é suficiente para:

- alguns HDs

- um NVMe

- rede

Mas quando você começa a pensar em:

- HBA SAS

- mais discos

- cache NVMe

- 10 GbE

você começa a fazer malabarismos com as pistas PCIe. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit+1](https://www.reddit.com/r/homelab/comments/1bvmhr7?utm_source=chatgpt.com)

### O que mais me chamou atenção

O autor acabou comprando:

- 5600G

- A520I

- RAM DDR4

E reportou consumo de aproximadamente 30 W da tomada com:

- 4 SSDs

- NIC 10 GbE

- 32 GB RAM

o que é um resultado muito bom para um sistema desse porte. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)Reddit](https://www.reddit.com/r/homelab/comments/1bvmhr7?utm_source=chatgpt.com)

Isso reforça algo que discutimos antes:

**TDP ≠ consumo real do NAS parado.**

### Se eu estivesse montando o seu servidor hoje

Eu esqueceria completamente:

- N100

- N305

- NAS prontos com 8 GB

e pensaria em algo assim:

| Peça | Objetivo |
| --- | --- |
| CPU | Ryzen 5700G usado |
| RAM | 32 GB DDR4 inicialmente |
| Meta futura | 64 GB |
| Sistema | Proxmox |
| Armazenamento sistema | NVMe 1 TB |
| Mídia | 2×12 TB ou 2×16 TB |
| Placa-mãe | B550 com 6 SATA |
| Gabinete | espaço para 6–8 HDDs |

Porque o gargalo que eu vejo no seu futuro não é armazenamento.

É RAM.

Você provavelmente vai chegar em:

- Jellyfin

- Immich

- Minecraft

- Sonarr

- Radarr

- qBittorrent

- Prowlarr

e acabar dizendo:

"32 GB já está apertando."

Muito antes de dizer:

"Esse 5700G está sem CPU."

Por isso, para o seu uso específico, eu hoje colocaria a prioridade assim:

**RAM > quantidade de baias > possibilidade de expansão PCIe > CPU > consumo elétrico absoluto.**

Você parece estar construindo um mini data center doméstico disfarçado de NAS. 😄

---

## Assistant

O AMD Ryzen 7 5825U é uma opção bem interessante para NAS/homelab, principalmente porque ele aparece em várias placas chinesas compactas e mini PCs voltados para servidores domésticos.

Mas ele ocupa um espaço diferente de um 5600G ou 5700G.

## O que ele é

- 8 núcleos / 16 threads

- Zen 3

- TDP configurável de 10 a 25 W

- GPU integrada básica

- CPU originalmente de notebook

Na prática, o desempenho é muito próximo de um 5700U e não muito distante de um 5700G em cargas leves e médias.

## Onde ele brilha

### Consumo

Aqui ele realmente é excelente.

Um sistema com:

- 5825U

- 32 GB RAM

- NVMe

- alguns HDs

pode ficar em idle na faixa de 10–20 W dependendo da placa-mãe e dos discos.

### Homelab leve a médio

Roda tranquilamente:

- Jellyfin

- Sonarr

- Radarr

- Prowlarr

- qBittorrent

- Immich

- Nextcloud

- Minecraft pequeno/médio

Tudo ao mesmo tempo.

## Onde ele perde para um 5600G/5700G

### Expansão

Esse é o ponto crítico.

Muitas placas 5825U são:

- CPU soldada

- RAM soldada ou limitada

- poucas lanes PCIe

- poucos slots de expansão

Você precisa olhar a placa específica, não apenas o processador.

### Upgrade

Num 5700G você pode trocar:

- placa-mãe

- RAM

- CPU

Num sistema baseado em 5825U, muitas vezes:

- CPU é soldada

- placa é proprietária

Se algo morrer, troca tudo.

## Para o seu caso

Vamos lembrar o que você quer:

- 20 TB+

- Jellyfin

- Sonarr/Radarr

- Immich

- Kodi

- Minecraft 400+ mods

- crescimento futuro

O Minecraft é o item que me faz hesitar.

Um servidor com 400+ mods não é exatamente uma carga "leve".

Ele vai gostar de:

- clocks altos

- bastante RAM

- margem de CPU

E aí um 5700G normalmente leva vantagem.

## Minha classificação para você

### Melhor custo-benefício

AMD Ryzen 7 5700G

Porque:

- DDR4 barata

- muitas placas-mãe disponíveis

- expansão fácil

- 8c/16t

### Melhor eficiência energética mantendo boa potência

AMD Ryzen 7 5825U

Porque:

- muito econômico

- silencioso

- compacto

Mas depende muito da placa específica.

### Melhor para NAS puro

Intel Processor N100

Mas eu já não acho que ele combina tanto com os planos que você descreveu.

Se você estiver vendo aquelas placas chinesas NAS com **5825U + 6 SATA + 2 NVMe + 2.5 GbE**, aí a conversa fica muito interessante. Na verdade, para o seu perfil, eu provavelmente escolheria uma dessas antes de um N100. O que eu gostaria de ver é **o modelo exato da placa ou mini-PC com 5825U** que chamou sua atenção, porque a qualidade da placa importa mais do que o processador nesse caso.

---

## Assistant

Sim, mas existem algumas formas diferentes de fazer isso, e a resposta depende do que exatamente você quer desligar.

## Cenário 1 — HDs dormem, servidor continua ligado

Esse é o mais comum.

O servidor fica ligado 24/7, mas:

- HDs param de girar (spin-down)

- CPU entra em estados de baixo consumo

- ventoinhas desaceleram

Quando alguém acessa:

- Jellyfin

- SMB

- Immich

- Nextcloud

os discos acordam automaticamente.

É o que eu recomendo para 90% dos homelabs.

### Vantagens

- Simples

- Confiável

- Funciona com qualquer serviço

### Desvantagem

Ainda há consumo de energia.

Mas um sistema eficiente pode ficar na faixa de 15–40 W dependendo dos discos.

## Cenário 2 — Suspender (Sleep/S3)

O servidor entra em suspensão.

Consome muito pouco.

Quando recebe um sinal de rede, acorda.

Isso se chama:

### Wake-on-LAN (WoL)

O PC dorme e outro dispositivo envia um "pacote mágico".

Problema:

O cliente precisa enviar o WoL.

Jellyfin não faz isso sozinho.

Kodi normalmente não faz isso sozinho.

TVs geralmente não fazem isso.

## Cenário 3 — Outro dispositivo acorda o servidor

Essa é uma solução muito usada.

Você deixa ligado:

- roteador

- Raspberry Pi

- mini-PC pequeno

E o servidor principal dorme.

Quando alguém tenta acessar:

```
TV
 ↓
Raspberry Pi
 ↓
Wake-on-LAN
 ↓
Servidor acorda
 ↓
Jellyfin responde
```

Funciona, mas exige configuração.

## Cenário 4 — Ligar totalmente sozinho ao detectar conexão

É aqui que vem a parte chata.

### Não existe mágica.

Se o computador estiver:

- desligado

- sem energia

- hibernado profundamente

ele não consegue "ouvir" alguém tentando acessar o Jellyfin.

Alguém precisa permanecer acordado para receber a tentativa de conexão.

Por isso normalmente existe:

- roteador

- Raspberry Pi

- proxy reverso

- outro servidor

fazendo essa função.

## O que eu faria no seu caso

Você falou de:

- Jellyfin

- Sonarr

- Radarr

- Immich

- Minecraft

Então eu provavelmente nem tentaria desligar o servidor.

Porque:

- Sonarr faz buscas agendadas

- Radarr faz buscas agendadas

- qBittorrent fica monitorando

- Immich faz processamento

- Minecraft precisa ficar online

O ideal seria focar em:

### Hardware eficiente

Exemplo:

- 5700G ou 5825U

- discos em spin-down

- fonte eficiente

- Linux/Proxmox bem configurado

Resultado:

- servidor sempre disponível

- sem dores de cabeça

- consumo relativamente baixo

## Uma solução muito legal para mídia

Muita gente faz:

### Servidor principal

- Desligado ou dormindo

### Mini servidor sempre ligado

- N100

- Raspberry Pi

- Thin Client

Esse equipamento:

- roda Jellyfin

- acorda o servidor de armazenamento quando necessário

Assim você tem um consumo contínuo de 5–10 W e o "monstro" só acorda quando precisa.

Mas, sinceramente, para um servidor com 20 TB de mídia, Minecraft e automações, eu provavelmente investiria mais esforço em reduzir o consumo em idle do que em tentar ligar e desligar automaticamente. Normalmente o ganho de energia acaba sendo menor do que parece, enquanto a complexidade aumenta bastante.

---

## Assistant

Ah, para **servidor de Minecraft**, a resposta muda bastante.

O que você quer é algo como:

"O servidor fica desligado quando ninguém está jogando. Se alguém tentar entrar, ele liga sozinho."

E sim, isso existe.

## A solução mais comum: Auto-start on Join

Funciona assim:

```
Jogador tenta conectar
↓
Proxy detecta a tentativa
↓
Servidor está desligado
↓
Proxy inicia o servidor
↓
Servidor termina de carregar
↓
Jogador entra
```

Isso é muito usado por quem hospeda vários modpacks ao mesmo tempo.

## Exemplo prático

Você tem:

- ATM10

- Prominence II

- Create Chronicles

Em vez de deixar os 3 rodando:

```
ATM10          OFF
Prominence     OFF
Create         OFF
```

Quando um amigo tenta entrar no ATM10:

```
ATM10          STARTING
Prominence     OFF
Create         OFF
```

Depois de alguns minutos sem jogadores:

```
ATM10          OFF
Prominence     OFF
Create         OFF
```

## Como normalmente fazem isso

### Método 1 — Proxy

Usam um proxy como:

Velocity

ou

BungeeCord

O proxy fica sempre ligado.

Consome quase nada.

Ele detecta a conexão e inicia o servidor correto.

### Método 2 — Pterodactyl

Pterodactyl

Muito popular para hospedar servidores.

Permite:

- iniciar

- parar

- monitorar

servidores de forma automática.

Existem integrações para iniciar o servidor quando alguém tenta entrar.

### Método 3 — Crafty Controller

Crafty Controller

Mais simples para homelab.

Interface web.

Cria múltiplos servidores.

Liga e desliga facilmente.

## O problema dos modpacks

Aqui está a pegadinha.

Um modpack de 400+ mods pode levar:

- 1 minuto

- 2 minutos

- 5 minutos

para iniciar.

Então o jogador pode ver:

```
Conectando...
Servidor iniciando...
Aguarde...
```

Não é instantâneo.

## O que eu faria no seu caso

Se você realmente pretende ter:

- vários modpacks

- poucos jogadores simultâneos

- servidor em casa

eu faria:

```
Proxmox
 ├─ Jellyfin
 ├─ Immich
 ├─ Sonarr/Radarr
 └─ VM Minecraft
      ├─ ATM10
      ├─ Prominence
      └─ Outro modpack
```

e usaria um gerenciador que:

- desliga o servidor após X minutos sem jogadores

- liga automaticamente quando alguém tenta entrar

Assim você não precisa deixar:

- 3 JVMs

- 30+ GB de RAM

- chunks carregados

consumindo recursos 24 horas por dia.

Na prática, para um grupo de amigos, isso costuma economizar muito mais RAM do que tentar economizar energia desligando o servidor físico inteiro. O maior desperdício geralmente é deixar três instâncias de Minecraft modded rodando vazias, não o hardware em si.

---

## Assistant

Para um servidor/homelab, eu escolheria **2×32 GB** quase sempre.

## 2×32 GB

### Vantagens

✅ Deixa 2 slots livres

Hoje:

- 64 GB = 2×32

Amanhã:

- 128 GB = adiciona mais 2×32

Sem jogar nada fora.

✅ Menos estresse no controlador de memória

Principalmente em Ryzen.

Com apenas 2 módulos é mais fácil:

- atingir a frequência anunciada

- manter estabilidade

- consumir um pouco menos

✅ Melhor para Proxmox

Se daqui a alguns anos você estiver rodando:

- Minecraft

- Jellyfin

- Immich

- VMs Linux

- Containers

e descobrir que precisa de 96 ou 128 GB, basta adicionar mais memória.

## 4×16 GB

### Vantagens

✅ Às vezes é mais barato

Dependendo de promoções.

### Desvantagens

❌ Todos os slots ocupados

Se quiser 128 GB depois:

- vende os 4 módulos

ou

- convive com 64 GB

❌ Mais chance de precisar reduzir frequência

Especialmente em Ryzen.

Por exemplo:

- 2 módulos podem funcionar em 3600 MT/s

- 4 módulos podem exigir ajustes

## Para um NAS/homelab

A questão nem é desempenho.

É expansão.

Você está começando falando:

- 20 TB de mídia

- Jellyfin

- Sonarr

- Radarr

- Immich

Agora já apareceu:

- Minecraft com 400+ mods

- múltiplos servidores

- Proxmox

Eu apostaria dinheiro que daqui a 2 anos você vai dizer:

"Nossa, seria bom ter mais RAM."

😂

## O que eu faria

### DDR4

- 2×32 GB DDR4

### DDR5

- 2×32 GB DDR5

Em ambos os casos.

### Uma observação importante

Para um servidor doméstico, muitas vezes:

- 32 GB = confortável

- 64 GB = muito confortável

- 128 GB = começa a fazer sentido quando você entra em várias VMs e muitos servidores de jogos

Então 64 GB já é uma meta excelente.

Mas justamente por isso eu deixaria a porta aberta para crescer depois.

**Resumo:** para 64 GB, escolha **2×32 GB**. Você mantém dual-channel, tem a mesma capacidade total, menos complicações e deixa metade da placa-mãe livre para upgrades futuros.

---

## Assistant

Depois de ler esse artigo e cruzar com as discussões do Reddit que você trouxe nos últimos dias, minha impressão é:

**O artigo está correto para um público geral, mas você já ultrapassou o perfil de usuário para quem ele foi escrito.**

O artigo basicamente divide em:

| Uso | CPU sugerida |
| --- | --- |
| NAS básico | N100/N97 |
| Plex + Docker | i3-12100 |
| VMs e containers | 5600G/5700G |
| Homelab pesado | i5/i7 modernos, Xeon, EPYC |

E é justamente aí que entra a diferença.

## Há uma semana eu recomendaria N100

Se você tivesse dito:

- Backup

- Fotos

- Jellyfin

- 2 discos

Eu falaria:

N100 sem pensar duas vezes.

Inclusive o próprio artigo coloca o N100 como excelente para NAS doméstico por causa do consumo baixo e do Quick Sync. [![image](https://www.google.com/s2/favicons?domain=https://www.lincplustech.com&sz=128)LincPlus+1](https://www.lincplustech.com/en-fr/blogs/news/the-best-cpu-for-nas-a-2025-guide-for-builders-and-buyers?utm_source=chatgpt.com)

## Mas seu projeto foi crescendo

Agora você está falando de:

- 20+ TB

- Sonarr

- Radarr

- Prowlarr

- qBittorrent

- Jellyfin

- Immich

- Proxmox

- Minecraft com 400+ mods

- Possivelmente múltiplos servidores

Isso não é mais "NAS".

Isso é um **home server**.

E o próprio artigo diz que, para VMs e workloads mais pesados, CPUs como o 5600G e 5700G passam a ser mais adequadas. [![image](https://www.google.com/s2/favicons?domain=https://www.lincplustech.com&sz=128)LincPlus](https://www.lincplustech.com/en-fr/blogs/news/the-best-cpu-for-nas-a-2025-guide-for-builders-and-buyers?utm_source=chatgpt.com)

## O que mais me chamou atenção

O artigo fala uma coisa que bate exatamente com o que você percebeu:

não escolha CPU por hype, escolha pelo uso real. [![image](https://www.google.com/s2/favicons?domain=https://www.lincplustech.com&sz=128)LincPlus](https://www.lincplustech.com/en-fr/blogs/news/the-best-cpu-for-nas-a-2025-guide-for-builders-and-buyers?utm_source=chatgpt.com)

No seu caso o uso real é:

### Armazenamento

Relativamente leve.

### Jellyfin

Moderado.

### Minecraft modded

Pesado.

### Possível Proxmox

Pesado.

### Crescimento futuro

Pesado.

## Sobre o Ryzen 5825U

Depois de tudo que conversamos, acho que o 5825U ficou muito interessante para você.

Porque ele fica num meio-termo entre:

| CPU | Potência | Consumo | Expansão |
| --- | --- | --- | --- |
| N100 | Baixa | Excelente | Limitada |
| 5825U | Média/Alta | Excelente | Depende da placa |
| 5700G | Alta | Muito boa | Excelente |

O problema do 5825U não é a CPU.

É a placa onde ele vem soldado.

## Se eu estivesse montando HOJE

Eu teria três opções.

### Opção A — "quero brincar de homelab"

- 5700G

- B550

- 64 GB RAM

- 6+ SATA

Essa é a que mais combina com o que você vem descrevendo.

### Opção B — "quero eficiência absurda"

- placa NAS com 5825U

- 64 GB RAM (se suportar)

- 2×2.5 GbE

Essa provavelmente seria minha favorita se encontrar uma placa boa.

### Opção C — "quero só NAS"

- N100

Mas sinceramente eu acho que você já saiu dessa categoria há umas 10 mensagens atrás. 😄

O mais curioso é que o acidente com o 3600X acabou te colocando numa posição interessante: você está livre para escolher uma plataforma nova para o servidor sem ficar preso ao hardware antigo. E, olhando tudo que você pretende rodar, hoje eu estaria pesquisando **placas NAS baseadas em Ryzen 5825U ou um conjunto AM4 com 5700G**, não N100. Os argumentos sobre PCIe, expansão, RAM e múltiplos serviços que apareceram nos tópicos do Reddit encaixam quase perfeitamente no seu caso. [![image](https://www.google.com/s2/favicons?domain=https://www.reddit.com&sz=128)reddit.com+2![image](https://www.google.com/s2/favicons?domain=https://www.lincplustech.com&sz=128)LincPlus+2](https://www.reddit.com/r/homelab/comments/1bvmhr7?utm_source=chatgpt.com)

---

## Assistant

Sim. E essa descoberta pode mudar bastante a escolha do seu servidor.

Quando o assunto é **Jellyfin + transcodificação de vídeo**, a Intel tem uma vantagem real há vários anos.

## O que é o Quick Sync?

É um bloco de hardware dedicado dentro da iGPU Intel.

Em vez de a CPU ficar convertendo vídeo:

```
Filme 4K
↓
CPU faz tudo
↓
Uso de CPU alto
```

acontece:

```
Filme 4K
↓
Quick Sync faz quase tudo
↓
CPU quase livre
```

O resultado é:

- Menor consumo

- Mais streams simultâneos

- Menos carga na CPU

## O detalhe importante

Muita gente monta um NAS e depois descobre que nunca precisou de transcodificação.

Se todos os dispositivos conseguem reproduzir o arquivo original:

- Kodi

- Android TV

- Fire TV

- PC

- Smart TV moderna

o Jellyfin faz:

### Direct Play

```
Arquivo
↓
Rede
↓
TV
```

Sem converter nada.

Nesse cenário, Quick Sync quase não entra em ação.

## No seu caso

Você comentou várias vezes:

- Kodi

- Jellyfin

- TV

- Sonarr

- Radarr

Se você usa Kodi conectado ao Jellyfin, a maior parte dos vídeos tende a ser Direct Play.

Ou seja:

- Ryzen 5700G

- Intel i5

teriam praticamente o mesmo resultado.

## Quando Quick Sync vira rei

Imagine:

- Você está viajando

- Assistindo no celular

- Internet limitada

Jellyfin faz:

```
4K HEVC
↓
1080p H264
↓
Celular
```

Aí o Quick Sync brilha.

## Por isso o pessoal ama CPUs Intel para NAS

Por exemplo:

### Intel Core i3-12100

Virou praticamente um clássico dos homelabs.

Porque:

- 4 núcleos fortes

- Quick Sync excelente

- Consumo baixo

- Plataforma barata

### Intel Core i5-12400

Outra favorita.

- 6 núcleos

- Quick Sync

- Muito desempenho para VMs

## Comparando com o 5700G

| Característica | 5700G | i5-12400 |
| --- | --- | --- |
| Jellyfin Direct Play | Empate | Empate |
| Jellyfin Transcoding | Perde | Ganha |
| Minecraft | Ganha ligeiramente | Muito próximo |
| Proxmox | Empate | Empate |
| Consumo Idle | Muito bom | Muito bom |
| PCIe | Similar | Similar |
| iGPU para mídia | Boa | Excelente |

## O que eu faria HOJE pensando no seu projeto inteiro

Você quer:

- 20+ TB

- Jellyfin

- Sonarr

- Radarr

- Immich

- Minecraft modded

- Containers

- Possivelmente Proxmox

Eu começaria a olhar para:

### Intel 12ª geração

- Intel Core i3-12100

- Intel Core i5-12400

- Intel Core i5-12500

Principalmente o **12500**.

Ele tem:

- Quick Sync moderno

- 6 núcleos

- iGPU UHD 770 (melhor que a UHD 730 dos modelos inferiores)

- Excelente para Jellyfin

### Minha opinião depois de tudo que você descreveu

No começo eu estava mais inclinado ao 5700G.

Mas depois que apareceram:

- Jellyfin

- múltiplos serviços

- Minecraft

- servidor de longo prazo

eu começaria seriamente a considerar um **i5-12400 ou i5-12500 usado**.

Porque você ganha o Quick Sync e continua tendo potência suficiente para todo o resto.

A única pergunta que eu faria agora é: **quantas pessoas você imagina assistindo Jellyfin ao mesmo tempo?**

Porque se a resposta for:

"eu e talvez mais 1 ou 2 amigos"

então o Quick Sync é uma vantagem legal.

Mas se a resposta for:

"basicamente só eu usando Kodi dentro de casa"

a importância dele cai bastante, porque quase tudo será Direct Play.

---

## Assistant

KKKKKKKK então você acabou de derrubar uns 50% dos argumentos pró-Intel que estavam aparecendo nas suas pesquisas.

O pessoal do Reddit, fóruns de NAS e YouTube costuma assumir um cenário tipo:

"Tenho Jellyfin para a família inteira, acesso remoto, celulares, tablets, TVs diferentes..."

Aí Quick Sync realmente vira uma prioridade enorme.

Mas o seu cenário parece mais:

```
Sonarr
 ↓
Radarr
 ↓
Arquivos
 ↓
Jellyfin
 ↓
Kodi
 ↓
Você
```

Nesse fluxo, o Kodi geralmente reproduz o arquivo original.

Ou seja:

### Direct Play

O servidor faz basicamente:

- Ler o arquivo do HD

- Enviar pela rede

Fim.

A CPU quase tira férias.

Por exemplo:

Você baixa um filme:

- HEVC

- 4K

- HDR

- TrueHD Atmos

O Kodi consegue reproduzir isso diretamente.

Então o Jellyfin não converte nada.

O uso de CPU pode ficar em 1~5%.

Na verdade, olhando tudo que você descreveu até agora, eu começaria a priorizar:

### 1. RAM

Porque apareceu:

- Minecraft 400+ mods

- múltiplos servidores

- containers

- Proxmox

### 2. Baias para HD

Porque apareceu:

- 20 TB para começar

- Sonarr/Radarr

- biblioteca crescendo

### 3. Expansão PCIe

Porque daqui a alguns anos você pode querer:

- mais SATA

- mais NVMe

- rede mais rápida

### 4. CPU

Qualquer uma dessas já sobra:

- AMD Ryzen 7 5700G

- AMD Ryzen 7 5825U

- Intel Core i5-12400

- Intel Core i5-12500

O mais engraçado é que, conforme você foi refinando os requisitos, o "NAS perfeito" foi mudando:

**Fase 1**

Quero um NAS.

→ N100.

**Fase 2**

Quero Jellyfin.

→ Intel Quick Sync.

**Fase 3**

Quero 20 TB.

→ Mais baias.

**Fase 4**

Quero Minecraft com 400+ mods.

→ Mais RAM e CPU.

**Fase 5**

Na verdade só eu vou assistir no Kodi.

→ Quick Sync deixa de ser prioridade.

😂

Nesse momento eu estaria muito mais preocupado em encontrar uma plataforma que aceite **64 GB ou 128 GB de RAM e vários HDs** do que em escolher entre AMD ou Intel por causa do Jellyfin. Suspeito que daqui a 2 anos você vai estar reclamando de falta de RAM ou de espaço em disco muito antes de reclamar de transcodificação de vídeo.

---

## Assistant

Agora chegamos na parte mais importante. 😄

Para um servidor como o que você descreveu, a placa-mãe pode ser mais importante que a CPU.

Você quer:

- 20+ TB de mídia

- Sonarr/Radarr

- Jellyfin

- Kodi

- Immich

- Minecraft modded

- talvez Proxmox

- talvez mais HDs futuramente

- 64 GB RAM

- possibilidade de crescer

Então eu olharia primeiro para:

## Quantas portas SATA?

Muita gente compra uma placa e só depois percebe:

```
NVMe
+
2 HDs
=
acabaram as portas SATA
```

Eu tentaria começar com pelo menos:

- 6 SATA

Idealmente:

- 6 SATA + 2 NVMe

# Se for AMD (5600G/5700G)

## Melhor custo-benefício

MSI B550-A PRO

Vantagens:

- 6 SATA

- 2 NVMe

- ATX

- fácil de achar usada

- suporta 128 GB RAM

É uma das placas que mais aparecem em homelabs AM4.

## Outra ótima opção

Gigabyte B550 AORUS Elite V2

Também costuma ter:

- 6 SATA

- 2 NVMe

- VRM bom

- suporte tranquilo ao 5700G

## Minha favorita para servidor AM4

ASRock B550 Steel Legend

Porque geralmente oferece:

- boa distribuição de PCIe

- 6 SATA

- 2 NVMe

- construção sólida

# Se for Intel 12ª geração

## Excelente custo-benefício

MSI PRO B660M-A DDR4

Muito usada para:

- i3-12100

- i5-12400

- i5-12500

## Outra ótima

Gigabyte B660M DS3H DDR4

Normalmente mais barata.

# O que eu evitaria

Placas com:

- apenas 4 SATA

- apenas 2 slots de RAM

- formato Mini-ITX (a menos que você queira algo compacto)

Porque você já está pensando em crescimento.

# Um detalhe que quase ninguém comenta

Você vai querer um gabinete com espaço para HDs.

Às vezes a placa tem:

- 6 SATA

mas o gabinete só suporta:

- 2 HDs

😂

Então eu escolheria placa e gabinete juntos.

# Se eu estivesse montando HOJE com seu orçamento mental

### CPU

AMD Ryzen 7 5700G

### Placa

MSI B550-A PRO

### RAM

64 GB (2×32)

### Sistema

NVMe 1 TB

### Mídia

2×12 TB ou 2×16 TB inicialmente

### Gabinete

Algo com espaço para 6–8 HDs

Mas antes de escolher a placa, eu faria uma pergunta que muda tudo:

**Você imagina esse servidor ficando em um rack/armário dedicado ou em um gabinete comum ao lado da TV/quarto?**

Porque isso muda completamente as recomendações de gabinete e até o formato da placa-mãe.

---

## Assistant

Sim. Na verdade, quando você começa a montar um homelab desses, hospedar seus próprios sites e apps vira quase um bônus.

Com um servidor do tipo que você está planejando (5700G/64 GB/Proxmox), você teria recursos sobrando para isso.

## O que você poderia hospedar

### Sites simples

- Blog pessoal

- Portfólio

- Página da banda Cold Jinx

- Wiki pessoal

- Dashboard do homelab

### Apps próprios

Por exemplo, aquele sistema de hotel que você estava planejando:

- Frontend React

- Backend Node.js

- Banco PostgreSQL

Tudo rodando no seu servidor.

### Ferramentas pessoais

Algumas muito populares:

- [Immich](https://immich.app?utm_source=chatgpt.com) (alternativa ao Google Photos)

- [Nextcloud](https://nextcloud.com?utm_source=chatgpt.com) (arquivos, calendário, contatos)

- [Vaultwarden](https://github.com/dani-garcia/vaultwarden?utm_source=chatgpt.com) (gerenciador de senhas)

- [Mealie](https://mealie.io?utm_source=chatgpt.com) (receitas)

- [Paperless-ngx](https://docs.paperless-ngx.com?utm_source=chatgpt.com) (documentos)

### Desenvolvimento

Você poderia ter:

```
Servidor
├─ PostgreSQL
├─ Redis
├─ API Node.js
├─ App React
└─ Ambiente de testes
```

Praticamente uma mini-Vercel pessoal.

## O que muita gente faz

Usa:

[Docker](https://www.docker.com?utm_source=chatgpt.com)

para rodar tudo em containers.

Exemplo:

```
Docker
├─ Jellyfin
├─ Sonarr
├─ Radarr
├─ Prowlarr
├─ qBittorrent
├─ Immich
├─ PostgreSQL
├─ App pessoal 1
├─ App pessoal 2
└─ Minecraft
```

Tudo isolado e organizado.

## Mas tem um "porém"

Hospedar para você mesmo dentro de casa é fácil.

Hospedar para a internet inteira exige mais cuidados.

### Você vai precisar aprender

- DNS

- HTTPS

- Certificados SSL

- Proxy reverso

- Segurança básica

- Backups

Nada impossível, mas é uma etapa nova.

## Uma solução que eu acho perfeita para você

Hospedar os apps em casa e usar um túnel.

Por exemplo:

[Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/?utm_source=chatgpt.com)

Ele permite expor seus sites sem abrir portas diretamente no roteador.

Muita gente em homelab usa isso hoje.

## O que eu acho que aconteceria com você

Você começaria com:

```
Jellyfin
Sonarr
Radarr
```

Depois:

```
Immich
```

Depois:

```
Servidor Minecraft
```

Depois:

```
App pessoal
```

E alguns meses depois estaria rodando:

```
Proxmox
Docker
PostgreSQL
Redis
Apps próprios
Sites
Minecraft
Jellyfin
Immich
```

Ou seja, você deixaria de ter um NAS e passaria a ter um **servidor doméstico completo**. É exatamente esse caminho que faz muita gente abandonar NAS prontos: eles são ótimos para armazenamento, mas quando você começa a querer hospedar aplicações, bancos de dados, sites e servidores de jogos, a flexibilidade de um PC montado por você faz muita diferença.

---

## Assistant

Nesse caso, eu acho que você é exatamente o perfil que mais se beneficia de um homelab.

Porque você não está tentando criar uma Netflix para 20 pessoas ou hospedar um SaaS com milhares de usuários.

Você quer algo mais próximo de:

```
Casa
 ├─ Servidor
 │   ├─ Jellyfin
 │   ├─ Immich
 │   ├─ Minecraft
 │   ├─ App pessoal
 │   └─ Banco de dados
 │
Internet
 │
Você no trabalho
 │
Celular
```

E isso é relativamente tranquilo de fazer hoje.

## O que eu faria

### 1. Domínio próprio

Algo como:

- gabriel.dev.br

- gabrielhub.com.br

- drag0nst0ne.net

Normalmente custa algo entre R$ 40 e R$ 100 por ano.

### 2. Cloudflare

[Cloudflare](https://www.cloudflare.com?utm_source=chatgpt.com)

Praticamente todo homelab usa.

Você ganha:

- DNS

- HTTPS

- Proteção básica

- Túnel seguro

### 3. Cloudflare Tunnel

[Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/?utm_source=chatgpt.com)

Essa é a parte mais interessante.

Sem abrir portas no roteador, você poderia acessar:

```
jellyfin.seudominio.com
```

```
immich.seudominio.com
```

```
minecraft.seudominio.com
```

```
hotel.seudominio.com
```

de qualquer lugar.

## Exemplo real para você

### No trabalho

Abre o navegador:

```
immich.gabriel.com.br
```

e vê suas fotos.

### Na rua

Abre:

```
jellyfin.gabriel.com.br
```

e assiste algo pelo celular.

### Programando

Abre:

```
hotel.gabriel.com.br
```

e testa seu app.

## O único ponto de atenção

### Upload da internet

Para consumo de mídia remoto, o gargalo normalmente não é o servidor.

É a internet da sua casa.

Por exemplo:

| Velocidade de upload | Resultado |
| --- | --- |
| 10 Mbps | Ruim para 4K |
| 20 Mbps | 1080p tranquilo |
| 50 Mbps | Muito bom |
| 100 Mbps | Excelente |

Então vale a pena verificar qual é o upload do seu plano.

## Uma coisa que você talvez não tenha percebido

Quando você montar esse servidor, ele provavelmente vai substituir vários serviços pagos ao mesmo tempo:

- Google Photos → Immich

- Netflix pessoal → Jellyfin

- Google Drive → Nextcloud

- Servidor de Minecraft alugado → seu próprio servidor

- Hospedagem de apps → seu próprio servidor

Então o custo não é só "comprar um PC para guardar filmes".

Você está construindo uma infraestrutura pessoal que pode centralizar praticamente tudo que você usa.

Por isso eu continuaria pensando em algo robusto, como 64 GB de RAM e espaço para muitos discos. Você parece ter muito mais chances de se arrepender de comprar algo pequeno do que de comprar algo com margem para crescer.

---

## Assistant

Sim. Na verdade, você pode fazer isso sem gastar nada além da internet e da energia do servidor.

Quando eu falei de domínio próprio, foi mais pela comodidade.

Para acessar seu app do hotel no trabalho, existem várias opções:

## Opção 1 — Tailscale (minha favorita para você)

[Tailscale](https://tailscale.com?utm_source=chatgpt.com)

É praticamente uma VPN privada.

Você instala:

- no servidor em casa

- no celular

- no notebook

E pronto.

Seu celular enxerga o servidor como se estivesse dentro da sua rede doméstica.

Exemplo:

```
Casa
192.168.1.100
```

vira algo como:

```
100.x.x.x
```

Você abre no navegador:

```
http://100.x.x.x:3000
```

e acessa seu app.

### Vantagens

✅ Gratuito para uso pessoal

✅ Muito seguro

✅ Não precisa abrir portas

✅ Fácil de configurar

## Opção 2 — Cloudflare Tunnel

Também gratuito.

Você cria um endereço tipo:

```
hotel.seuprojeto.com
```

ou até um subdomínio gratuito em alguns casos.

Mais bonito, mas um pouco mais complexo.

## Opção 3 — DDNS gratuito

Serviços como:

- [Duck DNS](https://www.duckdns.org?utm_source=chatgpt.com)

- [No-IP](https://www.noip.com?utm_source=chatgpt.com)

Permitem criar algo tipo:

```
gabrielhotel.duckdns.org
```

Mas normalmente exigem abrir portas no roteador.

Hoje eu prefiro Tailscale ou Cloudflare Tunnel.

## Para o seu app do hotel

Sinceramente?

Eu faria:

```
Servidor em casa
 ↓
Docker
 ↓
App do hotel
 ↓
Tailscale
```

E acessaria do celular.

Você teria:

- sem mensalidade

- sem VPS

- sem hospedagem

- sem domínio obrigatório

## O único requisito

O servidor precisa ficar ligado em casa.

Mas como você já está pensando em:

- Jellyfin

- Sonarr

- Radarr

- Minecraft

ele provavelmente já vai ficar ligado 24/7 mesmo.

Para um projeto pessoal usado só por você, eu escolheria **Tailscale** sem pensar duas vezes. É provavelmente a forma mais simples, segura e gratuita de acessar seus aplicativos do trabalho, da rua ou do celular sem precisar aprender DNS, certificados SSL, encaminhamento de portas ou pagar hospedagem.

---

## Assistant

Esse é um tópico muito relevante para você, porque você já comentou algumas vezes sobre barulho te incomodar e sobre querer um ambiente mais silencioso.

A conclusão geral da comunidade do r/DataHoarder costuma ser:

**HD grande e silencioso são objetivos parcialmente conflitantes.**

Quanto maior e mais voltado para NAS/enterprise o HD, maior a chance de ele fazer:

- cliques de busca (seek noise)

- vibração

- ruído constante de rotação

## O que mais faz barulho?

Muita gente pensa:

"7200 RPM = o problema"

Mas na prática, em um NAS, o que mais incomoda costuma ser:

### Seek noise

O famoso:

```
tic tic tic
trrrr
clac clac
```

quando o cabeçote está se movendo.

Isso é muito comum em discos enterprise.

## Os mais barulhentos

Normalmente:

- Seagate Exos X18

- Seagate Exos X20

- Western Digital Ultrastar DC HC550

São excelentes discos, mas não foram projetados pensando em silêncio.

Foram projetados para rack de datacenter.

## Os mais silenciosos

Historicamente:

- Western Digital Red Plus

- Seagate IronWolf

Costumam ser mais amigáveis para ambientes domésticos.

## Mas tem uma pegadinha

Você está pensando em:

- 12 TB

- 16 TB

- 20 TB+

Nessa faixa, quase todos os discos modernos usam tecnologias que geram algum ruído.

Mesmo os "silenciosos".

## O que realmente reduz o barulho

### 1. Gabinete

Isso faz uma diferença absurda.

Um HD Exos em:

- gabinete fino e barato

parece um trator.

O mesmo HD em um gabinete com amortecimento:

- parece outro produto.

### 2. Distância

Se o servidor estiver:

```
Seu quarto
↓
ao lado da mesa
```

você vai ouvir.

Se estiver:

```
Outro cômodo
```

quase desaparece.

### 3. Quantidade de discos

Um único HD de 20 TB geralmente faz menos barulho que:

- 4×5 TB

- 4×6 TB

porque há menos motores girando.

## O que eu faria no seu caso

Pensando no que você descreveu:

- Jellyfin

- Sonarr

- Radarr

- Kodi

- uso pessoal

- quarto/escritório

eu provavelmente evitaria comprar discos SAS enterprise usados para a biblioteca principal.

Não por confiabilidade.

Mas por ruído.

Eu olharia primeiro para:

- Western Digital Red Plus 12TB

- Western Digital Red Plus 14TB

- Seagate IronWolf 12TB

- Seagate IronWolf 16TB

## A solução que muitos homelabbers adotam

É algo como:

```
NVMe
├─ Proxmox
├─ Apps
├─ Minecraft
├─ Banco de dados

HDs grandes
├─ Filmes
├─ Séries
├─ Backups
```

Assim os HDs ficam praticamente parados a maior parte do tempo.

Quando você está mexendo no Immich, no app do hotel ou no Minecraft, tudo roda no SSD e o servidor fica quase silencioso.

Pensando especificamente em você, eu me preocuparia mais com:

- Escolher um gabinete que suporte vários HDs e tenha boa absorção de vibração.

- Rodar sistema, containers e Minecraft em NVMe.

- Usar os HDs apenas para mídia e backup.

Isso costuma impactar muito mais a percepção de ruído do que escolher entre um 5700G ou um i5, por exemplo.

---

## Assistant

Pesquisei e encontrei um problema: os estoques e preços de 12/14/16 TB estão muito inconsistentes nas lojas brasileiras neste momento. Mas mesmo assim dá para tirar uma conclusão útil.

## O que importa de verdade: R$/TB

Pelos preços que encontrei:

| Capacidade | Preço aproximado |
| --- | --- |
| 8 TB | R$ 1.750–2.100 Pichau+2Pichau+2 |
| 12 TB | ~R$ 2.800–3.200 |
| 16 TB | ~R$ 3.700–4.200 |
| 20 TB | ~R$ 6.500 |

Calculando aproximadamente:

| Configuração | Custo por TB |
| --- | --- |
| 1×8 TB | ~R$220/TB |
| 2×8 TB (16 TB) | ~R$220/TB |
| 1×12 TB | ~R$250/TB |
| 1×16 TB | ~R$240/TB |
| 1×20 TB | ~R$330/TB |

# Para você especificamente

Você ainda está na fase:

"20 TB para começar"

Então eu **não compraria um HD de 20 TB**.

O custo por TB costuma ser pior.

## Cenário 1 — Melhor custo-benefício

### 2×8 TB

Vantagens:

- Menor investimento inicial

- Pode fazer espelhamento (RAID1)

- Se um morrer, o outro continua

Desvantagens:

- Mais ruído

- Mais consumo

- Ocupa 2 baias

## Cenário 2 — O que eu provavelmente faria

### 1×16 TB

Vantagens:

- Menos barulho

- Menos consumo

- Menos vibração

- Sobram baias

Depois:

```
16 TB
↓
adiciona outro 16 TB
↓
32 TB
```

## Cenário 3 — O que eu NÃO faria

### 1×20 TB

A menos que apareça uma promoção absurda.

Hoje você pagaria muito prêmio por TB.

# Outra coisa importante

Você falou:

- Sonarr

- Radarr

- Jellyfin

- Kodi

Então você não precisa começar com 20 TB.

Pra ter uma ideia:

### 8 TB

Cabem aproximadamente:

- 100 a 150 filmes 4K Remux

ou

- centenas de filmes 1080p

ou

- dezenas de séries completas

É mais espaço do que parece.

# Minha estratégia para você

Se estivesse montando o servidor amanhã:

### Sistema

- NVMe 1 TB

### Mídia

Começaria com:

**1×16 TB NAS**

ou

**2×8 TB NAS**

Dependendo da promoção do dia.

## Minha preferência pessoal

Para o seu caso:

🥇 **1×16 TB**

🥈 **2×8 TB**

🥉 **1×20 TB**

Porque você quer um homelab que vai crescer. Ter apenas um HD grande inicialmente deixa mais portas SATA, menos ruído e menos complicação. Quando encher, você compra outro HD grande e continua expandindo. Isso combina muito com o jeito que você está planejando esse projeto.

---

## Assistant

Eu acho que essa é uma decisão muito mais inteligente para o seu momento.

Porque hoje você ainda está na fase de planejamento. Você ainda não sabe exatamente:

- Se vai usar TrueNAS, Unraid ou Proxmox.

- Quanto o Jellyfin vai crescer.

- Quanto espaço o Immich vai consumir.

- Quantos modpacks de Minecraft vão ficar ativos.

- Quantos backups você vai guardar.

Comprar 20 TB logo de cara é meio como comprar uma carreta porque você pretende ter uma mudança daqui a 5 anos. 😅

## O que eu faria

### Opção A — 1×8 TB

Vantagens:

- Menor investimento inicial.

- Dá para aprender tudo.

- Consumo menor.

- Menos risco de gastar muito e depois mudar de ideia.

### Opção B — 1×10 TB

Provavelmente a que eu escolheria.

Porque normalmente o custo adicional não é tão grande.

Você ganha:

- 25% mais espaço

- mesma quantidade de baias ocupadas

- praticamente o mesmo consumo

## Crescimento futuro

Imagine:

### Hoje

```
NVMe 1 TB
10 TB
```

### Daqui 1 ano

```
NVMe 1 TB
10 TB
10 TB
```

### Daqui 2 anos

```
NVMe 1 TB
10 TB
10 TB
16 TB
```

### Daqui 4 anos

```
NVMe 1 TB
10 TB
10 TB
16 TB
16 TB
```

E você já teria mais armazenamento do que muita empresa pequena. 😂

## O que eu não faria

Eu não compraria o HD mais barato que encontrar.

Para o seu caso eu tentaria ficar em linhas como:

- Western Digital Red Plus

- Seagate IronWolf

ou um enterprise usado confiável se aparecer uma oportunidade muito boa.

## Outra vantagem de começar pequeno

Você vai descobrir qual é o gargalo real.

Hoje você acha que é armazenamento.

Eu apostaria uma pizza que, depois de montar tudo, o primeiro pensamento será algo como:

"Hmmm... talvez eu devesse ter colocado mais RAM."

ou

"Hmmm... talvez eu devesse ter comprado um NVMe maior."

E não:

"Meu HD de 10 TB encheu em uma semana."

Para ter uma referência, 10 TB comportam algo na ordem de:

- milhares de episódios em 1080p

- centenas de filmes em boa qualidade

- backups pessoais

- fotos do Immich

É muito mais espaço do que parece quando você ainda está começando a montar a biblioteca.

---

## Assistant

Aí você acabou de mudar completamente o dimensionamento do projeto. 😄

Eu estava assumindo o comportamento clássico do pessoal do r/DataHoarder:

"Vou baixar tudo e guardar para sempre."

Mas se você faz:

```
Baixa série
↓
Assiste
↓
Apaga
```

ou

```
Baixa filme
↓
Assiste
↓
Apaga
```

você não é um data hoarder. Você está usando o NAS como uma **locadora automática gigante**.

## Nesse cenário, 8 TB já é enorme

Vamos supor arquivos de qualidade alta:

| Conteúdo | Tamanho típico |
| --- | --- |
| Filme 1080p | 5–15 GB |
| Filme 4K | 20–80 GB |
| Episódio 1080p | 1–5 GB |
| Temporada inteira | 20–100 GB |

Com 8 TB livres você consegue acumular MUITA coisa antes de precisar apagar.

## O que vai ocupar espaço de verdade

Provavelmente:

### Immich

Fotos e vídeos pessoais.

### Backups

- PC principal

- celular

- documentos

### Minecraft

Mundos modded podem crescer bastante.

Um mundo com 400+ mods pode passar facilmente de:

- 10 GB

- 20 GB

- 50 GB

dependendo do tempo de jogo.

## Então sua prioridade muda

Antes eu estava pensando:

```
Mídia = principal consumidor
```

Agora parece mais:

```
Apps
Minecraft
Backups
Fotos
↓
Mídia temporária
```

## Eu começaria assim

### Sistema

- NVMe 1 TB

### Dados

- 1×8 TB ou 1×10 TB

E sinceramente?

Talvez você passe anos sem precisar comprar outro disco.

## O que eu investiria antes de comprar mais armazenamento

Se eu tivesse R$ 1.000 sobrando, eu colocaria nessa ordem:

- Mais RAM

- Melhor gabinete

- Nobreak

- Segundo NVMe

- Mais HD

## Uma observação importante

Muita gente começa pensando:

"Vou precisar de 40 TB."

Aí descobre que:

- Sonarr baixa automaticamente

- Assiste a série

- Sonarr remove depois

- Radarr remove depois

e o armazenamento fica girando constantemente.

Você parece muito mais próximo desse perfil do que do perfil "quero arquivar toda a história do cinema".

Por tudo que você descreveu até agora, se eu estivesse montando seu servidor amanhã, eu ficaria perfeitamente tranquilo começando com:

- 5700G ou equivalente

- 64 GB RAM

- NVMe 1 TB

- **1 HD de 8 ou 10 TB**

E focaria em deixar espaço para expansão futura, em vez de gastar uma fortuna em armazenamento logo de cara. O risco de você sentir falta de RAM, CPU ou baias livres é bem maior do que o risco de encher um disco de 10 TB rapidamente se você realmente apaga o que já assistiu.

---

## Assistant

Sim. Na verdade, montar o próprio NAS costuma ser a opção com melhor custo-benefício quando o orçamento importa.

O ZimaCube é basicamente:

- Uma placa-mãe compacta

- Um processador eficiente

- Memória RAM

- Armazenamento para o sistema

- Várias baias para HDs

- Uma fonte

- Um gabinete projetado para NAS

Nada disso é exclusivo da marca.

## Opção 1 — NAS econômico (R$ 1.500–2.500 sem HDs)

### Hardware usado

- CPU: Intel i3-8100, i3-9100 ou i5-8500 usados

- RAM: 16 GB DDR4

- SSD: 120–256 GB para o sistema

- Gabinete comum

- Fonte de qualidade 400–500 W

Vantagens:

- Muito barato

- Plex/Jellyfin com transcodificação por Quick Sync

- Docker

- Immich

- Arr Stack (Sonarr, Radarr, Prowlarr)

- Nextcloud

Consumo:

- ~20–40 W em repouso

## Opção 2 — NAS moderno e eficiente (R$ 2.500–4.000)

### Plataforma N100

7

O queridinho atual dos homelabs.

Peças:

- Placa N100 com 4–6 SATA

- 16 GB RAM

- SSD NVMe

- Fonte SFX ou Flex

- Gabinete NAS

Consumo:

- 8–15 W parado

- 20–30 W em uso

Roda:

- TrueNAS

- Unraid

- OpenMediaVault

- Proxmox

- Jellyfin

- Immich

- Home Assistant

Para uma casa comum é absurdo o quanto entrega.

## Opção 3 — Seu futuro PC velho vira NAS

Você comentou algumas vezes sobre trocar de computador.

Quando montar um PC novo, o seu atual:

- Ryzen 5600X

- 24 GB RAM

- RTX 3060 Ti

já seria um servidor extremamente poderoso.

Poderia:

- Remover a RTX para economizar energia

- Instalar Proxmox

- Criar VMs

- Rodar Jellyfin

- Rodar Immich

- Backup da família

- Hospedar seus próprios projetos

Seria muito mais potente que um ZimaCube Pro.

## Opção 4 — O "ZimaCube caseiro"

Se você quer especificamente o visual:

4

Gabinetes famosos:

- Jonsbo N2

- Jonsbo N3

- SilverStone Technology CS382

Com um desses e uma placa N100 você monta algo visualmente muito próximo do ZimaCube por menos da metade do preço.

## O que eu faria no seu caso

Pensando em:

- Jellyfin

- Sonarr

- Radarr

- Immich

- Watcharr

- Projetos pessoais

- Possível uso futuro de IA local leve

Eu escolheria:

| Peça | Sugestão |
| --- | --- |
| CPU | Intel N100 |
| RAM | 16 GB |
| Sistema | Proxmox |
| Armazenamento sistema | NVMe 500 GB |
| Mídia | 2× HD 8 TB usados enterprise |
| Gabinete | Jonsbo N2/N3 |

Você ficaria com um "mini ZimaCube" consumindo pouca energia e custando algo entre R$ 3.000 e R$ 5.000 (sem contar os HDs), contra algo que facilmente passa de R$ 8.000–10.000 importado quando entram frete e impostos.

---

## User

HDs especificos de nas fazem diferença neste sentido?

---

## User

Informações gerais
report
Nota: Devido à grande variedade de modelos de discos rígidos SAS, primeiro garantiremos

que a capacidade que você adquire é exatamente a mesma, mas o modelo e

A marca será enviada aleatoriamente. Se você tiver um requisito de modelo específico,

Por favor, especifique a marca e o modelo ao fazer seu pedido. Obrigado por

sua compreensão.

pagamento

antes de colocar a sua encomenda, por favor confirmar preço e outros detalhes com o fornecedor.
nós aceitamos Alipay, Paypal. todos os principais cartões de crédito são aceitos através do COMPROMISSO seguro processador de pagamento.
se você precisa comprar mais bens, mas o preço não é muito barato, ou não encontrou em nossa loja, por favor entre em contato conosco!
os direitos de importação, impostos e taxas não estão incluídas no preço do item ou encargos de transporte. estes encargos são de responsabilidade do comprador. por favor verifique com o escritório de alfândega do seu país para determinar o que estes custos adicionais serão antes da licitação/a compra de
Shipping

nós usamos geralmente China ou HK Post Air Mail. por favor entre em contato conosco se você quiser usar outro correio, tais como DHL, FedEx, UPS, TNT, EMS. você vai pagar o custo extra. We vai lhe dar o número de rastreamento depois de enviado para fora.
retorno e Política de Reembolso

por favor entre em contato conosco antes de enviar o item de volta. a situação defeituosa deve ser comunicada para nós dentro de 3-5 dias em anexo com as fotos
por favor assegure o item será devolvido em bom estado e retornar o item dentro de 2 semanas a partir da mercadoria é recebida.
nós emitiremos nova substituição ou reembolso uma vez que o item é recebido. se for devolvido, preço único item da lista é reembolsável, o transporte e as taxas de seguro exigidas não são reembolsáveis.
o comprador é responsável por todos os encargos de transporte de retorno se o pagamento total restituído.
Feedback

mantemos elevados padrões de excelência e nos esforçamos para 100% de satisfação do cliente! o feedback é muito importante Nós pedimos que você entre em contato conosco imediatamente antes de nos dar feedback neutro ou negativo, de modo que nós possamos satisfatoriamente as suas preocupações.
agradecemos 5-star feedback positivo, é bom para o nosso negócio a longo prazo. também vamos enviar o mesmo feedback a você.

Unidade de Disco Rígido SAS Mecânico de 3,5 Polegadas para Servidores e NAS – Até 16 TB, 7.2K RPM, Alta Performance e Confiabilidade
Por que escolher um disco rígido SAS de 3,5 polegadas para minha infraestrutura de armazenamento?
Para quem gerencia um data center, um sistema de armazenamento em rede (NAS) ou uma solução de servidor corporativo, a escolha do disco rígido certo é fundamental para garantir desempenho, durabilidade e disponibilidade contínua dos dados. Um disco rígido SAS mecânico de 3,5 polegadas com velocidade de rotação de 7.2K a 1.2K RPM oferece um equilíbrio ideal entre velocidade, capacidade e confiabilidade, especialmente em ambientes com carga de trabalho intensa. Um usuário anônimo que administra um servidor de backup para uma empresa de tecnologia com mais de 200 funcionários relatou que, após migrar de discos SATA para discos SAS de 10 TB, o tempo médio de resposta caiu em 40% e o número de falhas de disco caiu drasticamente em um período de 18 meses. Isso se deve à arquitetura mais robusta dos discos SAS, que suporta operações contínuas e multitarefa com maior eficiência.
Disco Rígido SAS (Serial Attached SCSI)
É uma tecnologia de interface de armazenamento projetada para ambientes empresariais e servidores, oferecendo maior largura de banda, menor latência e maior confiabilidade em comparação com discos SATA. O SAS permite conexão em modo ponto a ponto, com suporte a múltiplos dispositivos em uma única cadeia de comunicação.
Velocidade de Rotação (RPM)
Mede quantas vezes o disco gira por minuto. Discos de 7.2K RPM são comuns em servidores e NAS, oferecendo um bom equilíbrio entre desempenho e consumo energético. Discos de 1.2K RPM são mais raros e geralmente usados em aplicações de armazenamento de longo prazo com baixa atividade.
Capacidade de Armazenamento (1 TB a 16 TB)
Refere-se à quantidade total de dados que o disco pode armazenar. Capacidades maiores reduzem a necessidade de múltiplos discos, economizando espaço físico, energia e custos de manutenção.
Qual é a diferença entre discos SAS e SATA em um ambiente corporativo?
Muitos profissionais de TI ainda se perguntam se vale a pena investir em discos SAS em vez de SATA. A resposta depende do uso. Para aplicações críticas, como bancos de dados, servidores de virtualização ou NAS com múltiplos usuários simultâneos, o SAS é a escolha superior. Abaixo, uma comparação direta entre os dois tipos de discos com base em parâmetros técnicos e desempenho real:
Característica	Disco SAS (7.2K RPM)	Disco SATA (7.2K RPM)
Interface	SAS (Serial Attached SCSI)	SATA (Serial ATA)
Velocidade de Transmissão	Up to 12 Gbps	Up to 6 Gbps
Latência	Menor (em média 2-3 ms)	Maior (em média 4-6 ms)
Confiabilidade (MTBF)	1,2 milhões de horas	1,0 milhão de horas
Capacidade Disponível	Até 16 TB	Até 14 TB (em modelos mais comuns)
Uso Recomendado	Servidores, NAS corporativos, virtualização	Armazenamento de arquivos, backup, uso doméstico
Um administrador de TI de uma instituição de ensino em São Paulo compartilhou que, após substituir 12 discos SATA por discos SAS de 8 TB em seu sistema de arquivamento de documentos acadêmicos, o tempo de acesso a arquivos em massa caiu de 12 segundos para menos de 4 segundos, mesmo com 50 usuários conectados simultaneamente.
Como escolher a capacidade certa para meu servidor ou NAS?
A capacidade do disco rígido deve ser definida com base no volume de dados que você precisa armazenar, no crescimento esperado e na política de backup. Discos de 1 TB a 4 TB são adequados para pequenas empresas ou sistemas de backup pontuais. Já discos de 6 TB a 16 TB são ideais para ambientes com grande volume de dados, como servidores de vídeo, bancos de dados ou centros de dados. Para quem precisa de escalabilidade, o uso de múltiplos discos SAS em configurações RAID (como RAID 5 ou RAID 10) permite aumentar a capacidade total e melhorar a redundância. Um usuário anônimo que gerencia um sistema de armazenamento para uma produtora de conteúdo digital em Rio de Janeiro utilizou 8 discos SAS de 12 TB em RAID 10, alcançando 48 TB de armazenamento útil com alta disponibilidade e recuperação rápida em caso de falha.
Quais são os benefícios de usar discos SAS de 3,5 polegadas em servidores e NAS?
Discos de 3,5 polegadas são o padrão em servidores e NAS corporativos por oferecerem maior capacidade, melhor dissipação térmica e maior durabilidade. Eles são projetados para operar 24/7, com tecnologias como reparo automático de setores (S.M.A.R.T.), redução de vibração (Vibration Tolerance) e proteção contra quedas (Shock Resistance). Além disso, o formato de 3,5 polegadas permite maior espaço para componentes internos, como bobinas de leitura/gravação mais precisas e maior densidade de armazenamento. Isso se traduz em maior eficiência de leitura e escrita, especialmente em operações sequenciais.
Passo a passo: Como instalar e configurar um disco SAS de 3,5 polegadas em um servidor ou NAS
Para garantir uma instalação bem-sucedida e segura, siga estas etapas:
Desligue completamente o servidor ou NAS e desconecte todos os cabos de energia.
Abra o gabinete e localize o slot de disco dedicado para discos SAS de 3,5 polegadas.
Insira o disco com cuidado, alinhando os conectores de dados e alimentação. Certifique-se de que o disco esteja firmemente fixado com parafusos.
Conecte o cabo SAS ao disco e ao controlador de armazenamento. Use cabos de qualidade com proteção contra interferência eletromagnética.
Ligue o dispositivo e acesse a interface de gerenciamento do sistema (BIOS/UEFI ou interface do NAS).
Verifique se o disco é detectado. Caso não seja, confira os cabos e a compatibilidade do controlador.
Formate o disco com o sistema de arquivos adequado (ex: ext4, XFS, NTFS, ZFS).
Configure o RAID, se necessário, para melhor desempenho e redundância.
Teste a escrita e leitura de dados com ferramentas como dd ou CrystalDiskMark para validar o desempenho.
Conclusão: Invista em discos SAS de alta capacidade para um armazenamento confiável e escalável
Se você busca um disco rígido mecânico de 3,5 polegadas para uso em servidores ou NAS com alto desempenho, durabilidade e capacidade, os modelos SAS de 1 TB a 16 TB são a escolha mais inteligente. Com velocidades de rotação de 7.2K RPM, interfaces de alta velocidade e MTBF superior, esses discos são projetados para suportar cargas de trabalho intensas em ambientes empresariais. Seja para armazenar dados críticos, executar virtualização ou gerenciar grandes volumes de arquivos, um disco SAS de 3,5 polegadas oferece o equilíbrio perfeito entre desempenho, confiabilidade e escalabilidade. Com capacidades que vão de 1 TB até 16 TB, você tem flexibilidade para atender às necessidades atuais e futuras da sua infraestrutura. Não subestime o impacto de um bom disco rígido em sua operação. Um investimento em tecnologia de ponta hoje pode evitar falhas, perda de dados e custos operacionais no futuro. Escolha com sabedoria — e vá além do simples armazenamento. Escolha confiabilidade.

---

## User

já percebi que vou ter que montar o meu proprio de verdade, pq eu gostaria de ter 1 ou mais hds para midia, por conta do sonarr/radarr, jellyfin, kodi (uns 20TB deve dar, para começar). E também fiquei incomodado que somente é oferecido opções com 8gb de ram, vou querer hostear meu server de mine com 400+ mods

---

## Assistant

Isso que você descreveu é extremamente comum em pessoas com TDAH ou traços parecidos, e tem uma consequência curiosa:

**o gargalo não é armazenamento nem tempo livre — é atenção.**

O cérebro pensa:

"Isso parece interessante."

e transforma imediatamente em:

"Preciso garantir que isso esteja disponível para mim."

Mas isso não significa:

"Vou assistir isso hoje."

Nem amanhã. 😅

## O ciclo costuma ser algo assim

```
Vejo algo interessante
↓
Adiciono ao Radarr
↓
Baixa automaticamente
↓
Fico feliz porque agora tenho acesso
↓
Perco o interesse temporariamente
↓
Vejo outra coisa interessante
↓
Repete
```

O prazer muitas vezes vem da **possibilidade futura**, não necessariamente do consumo imediato.

## Por isso muita gente com TDAH vira acumulador digital sem perceber

Pode acontecer com:

- Filmes

- Séries

- Jogos Steam

- Livros

- PDFs

- Cursos

- Mods de Minecraft

- Vídeos do YouTube salvos

A sensação é:

"Quando eu quiser, estará lá."

Isso reduz a ansiedade de perder algo.

## O problema

Depois de alguns meses:

```
Filmes: 800
Séries: 200
Jogos: 300
Cursos: 50
```

E aí aparece uma nova ansiedade:

"Tem coisa demais."

## O que eu acho interessante no seu caso

Você já identificou um comportamento importante:

Você não é um arquivista.

Você não está tentando preservar mídia.

Você está tentando preservar opções.

São coisas diferentes.

## Isso muda o NAS

Um data hoarder pensa:

```
Preciso guardar para sempre.
```

Você parece pensar:

```
Preciso poder acessar se eu tiver vontade.
```

Então talvez a estratégia ideal nem seja:

```
40 TB
60 TB
80 TB
```

Mas algo como:

```
10 TB
↓
Fila de interesse
↓
Consumo
↓
Remoção automática do que perdeu relevância
```

## O que eu faria

Criaria categorias mentais:

### Quero assistir logo

Limite pequeno.

Exemplo:

- 10 filmes

- 3 séries

### Talvez algum dia

Pode ficar no Radarr/Sonarr.

Mas sem baixar automaticamente.

### Estou assistindo agora

Prioridade máxima.

Isso evita que o servidor vire um museu de intenções futuras.

## Curiosamente...

Isso reforça ainda mais a ideia de que você não precisa começar com 20 TB.

Porque o seu comportamento não parece ser:

"Vou assistir 20 TB de conteúdo."

Parece ser:

"Vou descobrir 20 TB de conteúdo interessante."

São coisas muito diferentes.

E um servidor com 8–10 TB, Sonarr/Radarr bem configurados e possibilidade de expansão depois provavelmente acompanha esse comportamento por bastante tempo, sem você precisar investir pesado em armazenamento logo no início.

---

## Assistant

Esse anúncio me acende várias bandeiras amarelas.

Não pelo fato de ser SAS usado — isso é super comum em homelab — mas pela forma como o anúncio está escrito.

### O que me preocupa

#### 1. Marca e modelo aleatórios

O anúncio diz:

"a capacidade será a mesma, mas a marca e modelo serão enviados aleatoriamente"

Isso significa que você pode receber:

- Seagate Exos X16

- Western Digital Ultrastar DC HC550

- HGST Ultrastar He10

ou algum modelo muito mais antigo.

Para NAS, o modelo importa bastante.

#### 2. Horas de uso desconhecidas

Discos SAS usados normalmente vêm de:

- Data centers

- Storage arrays

- Ambientes corporativos

Podem ter:

- 20 mil horas

- 40 mil horas

- 60 mil horas

- 80 mil horas

Ainda podem funcionar perfeitamente, mas você deveria saber disso antes da compra.

#### 3. Texto claramente gerado por IA

Tem várias informações estranhas.

Por exemplo:

"1.2K RPM"

Não faz sentido para esse tipo de disco.

Provavelmente queriam escrever:

- 7.2K RPM (7200 RPM)

e a IA misturou os números.

Outro exemplo:

SAS reduz latência para 2–3 ms

Isso depende muito mais do disco do que da interface.

### O que eu verificaria antes

Perguntaria ao vendedor:

- SMART completo disponível?

- Quantas horas de uso?

- Bad sectors?

- Marca e modelo exatos?

- É SAS 12 Gb/s ou SAS 6 Gb/s?

- Garantia DOA (dead on arrival)?

### O detalhe mais importante

Muita gente compra SAS sem perceber uma coisa:

### SAS NÃO funciona em portas SATA normais

Se você comprar:

- B550

- B650

- Placa-mãe comum

os discos SAS não vão funcionar.

Você precisa de:

- HBA LSI

- Controladora SAS

- Backplane SAS

Exemplos famosos:

- LSI SAS 9207-8i

- LSI SAS 9300-8i

Esse é o erro número 1 de quem está montando o primeiro NAS.

### Para o seu projeto

Se você acabar indo para:

- Ryzen 5600G

- B550

- 4 a 6 discos

eu provavelmente procuraria primeiro:

- Exos SATA usados

- Ultrastar SATA usados

- WD Gold SATA usados

porque você evita a necessidade de uma controladora SAS.

Já se estiver pensando em um NAS maior, com 8–12 discos e HBA dedicada, aí os SAS usados podem virar um negócio excelente.

A pergunta que eu faria agora é:

**Qual capacidade você estava olhando nesse anúncio (8 TB, 10 TB, 12 TB, 14 TB, 16 TB?) e qual era o preço?**

Aí consigo dizer se está dentro do que normalmente vale a pena ou se está caro para um disco enterprise usado.

---

## Assistant

Acho que você acabou de encontrar o motivo pelo qual tanta gente começa olhando Synology, QNAP, UGREEN e termina montando um servidor próprio. 😅

Seu caso já deixou de ser um "NAS".

Você está descrevendo um **homelab multifunção**:

- Jellyfin

- Sonarr

- Radarr

- Prowlarr

- qBittorrent

- Immich

- Kodi

- Minecraft modpack pesado

- Talvez Nextcloud

- Talvez VPN

- Talvez Home Assistant

- Talvez VMs futuras

Isso é muito diferente de "guardar fotos da família".

## O Minecraft muda tudo

Um servidor de Minecraft com:

- 400+ mods

- vários jogadores

- chunks carregados

- máquinas automatizadas

pode facilmente usar:

- 8 GB RAM só para ele

- 12 GB em alguns modpacks

- 16 GB em casos extremos

Agora soma:

| Serviço | RAM aproximada |
| --- | --- |
| Proxmox | 2 GB |
| Jellyfin | 1 GB |
| Sonarr/Radarr/Prowlarr | 1 GB |
| qBittorrent | 1 GB |
| Immich | 4–8 GB |
| Minecraft modded | 8–16 GB |

Você já passou dos 8 GB que esses NAS prontos oferecem.

## Sobre os 20 TB

20 TB parece muito.

Até você começar a usar Sonarr e Radarr. 😂

Exemplo:

- Filmes 1080p Remux: 20–40 GB

- Filmes 4K Remux: 50–100 GB

- Séries completas: centenas de GB

Muita gente monta:

- 2 × 12 TB

- ou 2 × 16 TB

e em poucos anos está adicionando mais discos.

## O que eu montaria no seu lugar

Pensando em custo-benefício:

### CPU

AMD Ryzen 5 5600G

ou

AMD Ryzen 7 5700G

O 5700G seria meu favorito.

8 núcleos / 16 threads.

Excelente para:

- Minecraft

- Docker

- Proxmox

- Containers

### RAM

Começar com:

- 32 GB DDR4

Meta futura:

- 64 GB

RAM é uma das coisas que mais acabam crescendo em homelabs.

### Armazenamento

Sistema:

- NVMe 500 GB ou 1 TB

Mídia:

- 2 × 12 TB

- ou 2 × 16 TB

Mesmo sem RAID inicialmente.

### Placa-mãe

B550 com:

- 6 portas SATA

Isso já permite:

- 2 discos agora

- mais 4 depois

### Gabinete

Essa é a parte que eu acho que vale a pena planejar bem.

Muita gente compra gabinete normal e depois sofre.

Eu procuraria algo que suporte:

- 6 a 8 HDs de 3,5"

mesmo que você use apenas 2 inicialmente.

## Outra coisa que você percebeu sem querer

O ZimaCube Pro faz muito mais sentido para quem quer:

"comprar uma caixa pronta e nunca mexer nela"

Você parece ser o oposto.

Você já está pensando em:

- expansão

- novos serviços

- mais RAM

- mais discos

- Minecraft

Esse tipo de usuário costuma ficar frustrado com NAS fechados depois de 1 ou 2 anos.

## O que eu faria hoje se estivesse na sua situação

Como o 3600X aparentemente morreu e você já tem o PC AM5 principal:

### Servidor

- 5700G usado

- B550 usada

- 32 GB DDR4

- NVMe 1 TB

- 2×12 TB ou 2×16 TB

### Sistema

- Proxmox

### Containers

- Jellyfin

- Sonarr

- Radarr

- Prowlarr

- qBittorrent

- Immich

- Minecraft

Isso te daria um servidor que provavelmente ainda estaria atendendo suas necessidades daqui a 5 anos, enquanto muitos NAS prontos de 8 GB começariam a parecer limitados bem antes disso.

---

## User

meu radarr/sonarr tem a função "monitored", que baixa somente o que está ativo, só deixo as series que estou vendo mesmo. para não baixar tudo

---

## Assistant

Então você já está usando uma das melhores estratégias possíveis para esse tipo de comportamento. 😄

O *Monitored* do Sonarr/Radarr resolve exatamente o problema de:

"Quero lembrar que isso existe, mas não quero ocupar espaço agora."

Na prática você separa duas coisas que muita gente mistura:

### Biblioteca de interesse

```
Quero ver algum dia
```

Pode ter:

- 50 séries

- 200 filmes

- 500 filmes

Não importa.

Porque isso ocupa só alguns KB de metadados.

### Biblioteca baixada

```
Estou assistindo agora
```

Essa é a que consome espaço.

## Isso muda completamente sua necessidade de armazenamento

Se você usa o Sonarr/Radarr dessa forma:

### Não monitorado

```
Filme
↓
Fica listado
↓
Não baixa
```

### Monitorado

```
Filme
↓
Baixa
↓
Assiste
↓
Remove monitoramento
```

Você acaba mantendo um volume relativamente pequeno de mídia ativa.

## O que eu imagino acontecendo no seu caso

Algo parecido com:

```
5 séries ativas
+
20 filmes na fila
+
algumas temporadas completas
```

Mesmo com qualidade alta, isso normalmente não chega perto de encher 8 TB.

## Onde eu vejo mais risco de crescimento

Sinceramente?

Não é o Sonarr.

Não é o Radarr.

É:

### Minecraft

Mundos modded.

### Immich

Fotos e vídeos pessoais acumulam sem você perceber.

### Backups

Você monta o servidor.

Depois pensa:

"Já que ele está ligado..."

E começa a fazer backup de:

- PC

- celular

- documentos

- saves

- projetos

## Então seu plano faz bastante sentido

Se eu estivesse desenhando seu homelab hoje:

```
NVMe 1 TB
├─ Proxmox
├─ Docker
├─ Apps
├─ Minecraft

HD 8 ou 10 TB
├─ Filmes
├─ Séries
├─ Fotos
├─ Backups
```

E deixaria baias SATA sobrando.

## Uma vantagem que pouca gente percebe

Como você usa o sistema de *Monitored*, você tem liberdade para comprar o HD quando realmente precisar.

Daqui a um ano:

```
Uso atual:
4,8 TB de 10 TB
```

Aí você compra outro.

Não precisa adivinhar hoje se vai precisar de:

- 8 TB

- 16 TB

- 20 TB

- 40 TB

Você deixa o seu uso real responder essa pergunta.

E, sinceramente, pelo que você descreveu, eu ficaria surpreso se um HD de 10 TB fosse o primeiro componente a te limitar. Eu apostaria que a ordem mais provável é:

- "Quero mais RAM para mais serviços."

- "Quero mais baias para expandir."

- "Quero um SSD maior."

- Só então: "Preciso de mais armazenamento para mídia." 😄

---

## User

mas os 10tb eu vou dedicar só para midia, vou comprar um NVMe para o server e talvez até um ssd sata de 2tb

---

## Assistant

Aí a história muda de novo — e para melhor.

Se você está pensando em algo como:

```
NVMe 1 TB
├─ Proxmox
├─ Docker
├─ Minecraft
├─ Bancos de dados
├─ Apps pessoais

SSD SATA 2 TB
├─ Downloads temporários
├─ Biblioteca ativa
├─ Cache
├─ Immich

HD 10 TB
├─ Filmes
├─ Séries
├─ Anime
├─ Arquivo de mídia
```

isso é uma arquitetura muito mais parecida com um homelab bem planejado do que com um NAS básico.

## Uma coisa interessante

Pelo que você descreveu do seu uso:

### SSD 2 TB

Provavelmente seria o disco mais acessado do sistema.

Porque nele ficariam:

- downloads recentes

- séries que está assistindo

- filmes da semana

- mundo de Minecraft

- containers

- banco de dados do Immich

Tudo que é "quente".

### HD 10 TB

Seria armazenamento "frio".

Ou seja:

```
Assisto ocasionalmente
ou
Quero manter disponível
```

## Isso traz uma vantagem enorme

Os HDs podem ficar parados boa parte do tempo.

Enquanto:

- Immich

- Minecraft

- PostgreSQL

- Jellyfin metadata

- Sonarr

- Radarr

rodam em SSD.

O servidor fica:

- mais rápido

- mais silencioso

- mais responsivo

## Eu até pensaria em algo diferente

Dependendo dos preços quando você comprar.

### Opção A

```
NVMe 1 TB
+
SSD SATA 2 TB
+
HD 10 TB
```

Excelente.

### Opção B

```
NVMe 2 TB
+
HD 10 TB
```

Também excelente.

Hoje os NVMe de 2 TB estão ficando bem interessantes em custo-benefício.

## Para Minecraft

Eu colocaria SEMPRE em SSD.

Nunca no HD.

Especialmente porque você falou de:

- 400+ mods

- vários servidores

A diferença é enorme.

## Para Immich

Também em SSD.

O banco de dados e as miniaturas agradecem.

## Para Sonarr/Radarr

Uma estratégia muito usada é:

```
SSD
↓
Baixa
↓
Extrai
↓
Organiza
↓
Move para HD
```

Assim o torrent e o processamento não ficam martelando o HD o tempo todo.

## Sobre os 10 TB dedicados à mídia

Sinceramente?

Começa a fazer bastante sentido.

Porque agora não estamos falando de:

"10 TB para tudo."

Estamos falando de:

"10 TB exclusivamente para filmes e séries."

Isso é bastante espaço para alguém que:

- usa Monitored no Sonarr/Radarr,

- não guarda tudo para sempre,

- assiste principalmente o que está acompanhando no momento.

Se eu estivesse montando esse servidor para mim com o seu perfil de uso, eu provavelmente escolheria algo muito próximo de:

- CPU eficiente (5700G, 5825U ou Intel equivalente)

- 64 GB RAM (2×32)

- NVMe 2 TB

- HD 10 TB para mídia

E só compraria um segundo HD quando os dados reais mostrassem que ele é necessário. Essa abordagem costuma resultar em menos dinheiro parado em armazenamento e mais orçamento disponível para RAM, SSD e expansão futura.
