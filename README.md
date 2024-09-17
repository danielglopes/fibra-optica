# Fibra Óptica
## Introdução
A fibra ótica tornou-se uma das principais tecnologias de comunicação moderna. Ao utilizar a luz para transmitir informações, as fibras óticas permitem uma transmissão de dados mais rápida e eficiente do que os cabos tradicionais de cobre, além de oferecer maior alcance e imunidade a interferências eletromagnéticas.

A fibra ótica é um meio de transmissão extremamente eficiente, que utiliza pulsos de luz para transportar dados a longas distâncias com alta velocidade e baixa perda de sinal. Cada pulso de luz representa um bit de informação, tornando possível alcançar capacidades de transmissão de até centenas de gigabits por segundo. Seu uso é amplamente preferido em aplicações de longa distância, como telecomunicações e redes de alta velocidade.

## Funcionamento
*A fibra ótica é composta por três elementos principais*

- **Núcleo (Core):** Parte central da fibra onde a luz é transmitida. Feito de vidro ou plástico altamente purificado, possui um índice de refração elevado que mantém a luz confinada.  
- **Casca (Cladding):** Camada que circunda o núcleo, com um índice de refração menor, garantindo que a luz seja refletida de volta ao núcleo através do fenômeno de reflexão interna total.  
- **Revestimento Protetor (Buffer/Coating):** Cobre a casca, protegendo a fibra de danos físicos e ambientais, como umidade e poeira, sem impactar a transmissão de luz.  

### Princípio de Funcionamento  

A luz viaja através do núcleo da fibra em diferentes modos, dependendo da geometria e do índice de refração da fibra. No caso das fibras monomodo, a luz segue um caminho único, reduzindo a dispersão modal e permitindo transmissões a longas distâncias sem grandes perdas de sinal. Já nas fibras multimodo, a propagação ocorre em múltiplos caminhos, o que pode causar a dispersão modal e limitar a distância máxima sem o uso de repetidores ou amplificadores ópticos. 

- **Emissão de Luz:** A transmissão começa com a conversão de dados elétricos em pulsos de luz, geralmente gerados por LEDs ou lasers semicondutores. Cada pulso de luz representa um bit de informação.  
- **Reflexão Interna Total:** um fenômeno físico que ocorre quando a luz que viaja pelo núcleo atinge a interface entre o núcleo e a casca em um ângulo maior que o ângulo crítico. Isso faz com que a luz seja refletida de volta para o núcleo, impedindo que ela escape e permitindo que percorra longas distâncias com perdas mínimas de sinal.  
- **Recepção:** No final da fibra, um detector (geralmente um fotodiodo) converte os pulsos de luz de volta em sinais elétricos, interpretando os dados recebidos.

### Tipos de Fibra Óptica

*Existem dois tipos principais de fibras óticas, projetadas para diferentes aplicações:*  
- **Fibra Monomodo:** Possui um núcleo muito pequeno (8-10 micra) e permite que a luz viaje em linha reta. É usada para transmissões de longa distância e alta capacidade, sendo adequada para redes de backbone e transmissões transoceânicas.  
- **Fibra Multimodo:** Possui um núcleo mais largo (50-62,5 micra), permitindo a propagação de múltiplos feixes de luz em diferentes ângulos. É usada em transmissões de curta distância, como em redes locais (LANs) dentro de edifícios e campus universitários.

## Detalhamento do meio físico
As fibras ópticas são otimizadas para transmitir luz em certas faixas de comprimento de onda, como as janelas de 850 nm, 1310 nm e 1550 nm, que apresentam menores perdas de sinal. O tipo de vidro utilizado no núcleo, muitas vezes dopado com germânio ou outros materiais, determina a eficiência da transmissão óptica, especialmente em relação à atenuação e à dispersão.

- **Núcleo (Core):**
O núcleo é a parte central da fibra, geralmente feito de vidro ou plástico de alta pureza, por onde a luz é transmitida.
Nas fibras monomodo, o núcleo tem um diâmetro entre 8 e 10 micrômetros, o que permite que a luz viaje em um único caminho, ideal para longas distâncias e transmissões de alta capacidade.
Nas fibras multimodo, o núcleo é maior, entre 50 e 62,5 micrômetros, permitindo que a luz se propague em múltiplos modos, o que é mais adequado para transmissões de curta distância.

- **Casca (Cladding):**
A casca circunda o núcleo e tem um índice de refração ligeiramente menor que o núcleo, o que é crucial para o fenômeno de reflexão interna total. Isso garante que a luz se mantenha confinada no núcleo, refletindo-se continuamente dentro da fibra, evitando que a luz escape para fora.

- **Revestimento Protetor (Buffer Coating):**
O revestimento protetor cobre a casca e oferece proteção mecânica, protegendo a fibra contra danos físicos, como arranhões, impactos, umidade e outros fatores ambientais. Geralmente, é feito de um material plástico flexível, como acrilato. Além de proteger a fibra contra danos físicos, desempenha um papel crucial na preservação da integridade óptica em ambientes adversos. Em aplicações ao ar livre, o revestimento externo deve ser resistente a fatores como radiação ultravioleta, temperaturas extremas e produtos químicos. A implementação de revestimentos secundários, especialmente em fibras utilizadas em ambientes industriais, garante maior durabilidade e resistência mecânica.

- **Revestimento Secundário:**
Em algumas aplicações, especialmente externas, um revestimento secundário é adicionado para aumentar a proteção contra condições ambientais mais severas, como produtos químicos ou altas temperaturas.

- **Jaqueta (Outer Jacket):**
A jaqueta é a camada externa da fibra, feita de materiais como PVC ou polietileno, cuja função é proteger as fibras durante o manuseio, instalação e operação. Ela também garante proteção contra água, substâncias químicas e abrasão.


## Padronização IEEE para Fibra Óptica
A padronização IEEE para fibra ótica é abrangente e essencial para garantir a interoperabilidade, desempenho e segurança das redes de comunicação. As normas definidas pelo IEEE, particularmente as do grupo IEEE 802.3, cobrem diversos aspectos do uso de fibras ópticas em redes locais (LANs), metropolitanas (MANs) e de longa distância (WANs). 

### Principais Padrões IEEE Relacionados à Fibra Óptica

IEEE 802.3 - Ethernet sobre Fibra Óptica
O padrão IEEE 802.3 define a Ethernet sobre cabos de cobre, mas foi ampliado para incluir as especificações de Ethernet sobre fibra óptica, permitindo velocidades mais altas e longas distâncias de transmissão. Este padrão é amplamente utilizado em redes LAN, MAN e WAN. Os padrões também afetam diretamente a infraestrutura das redes, especialmente em data centers e provedores de serviços de Internet (ISPs). A Ethernet de 10, 40 e 100 Gigabit, por exemplo, permite a escalabilidade das redes para lidar com a crescente demanda por largura de banda. Além das distâncias suportadas e das velocidades oferecidas, os padrões de codificação de dados, como 64B/66B, têm impacto na eficiência da transmissão, reduzindo o overhead em comparação com codificações mais antigas, como 8B/10B. O uso dessas codificações e a transição para fibras monomodo ou multimodo, dependendo das distâncias e das necessidades de largura de banda, desempenham papéis cruciais na otimização do desempenho da rede.

### Ethernet

**Os principais padrões de fibra ótica definidos pelo IEEE 802.3 incluem**

- **100BASE-FX:** Especifica Ethernet a 100 Mbits/s usando fibra multimodo, sendo usado para conexões de até 2 km.  

- **1000BASE-SX:** Para Gigabit Ethernet em fibras multimodo, com alcance de até 550 metros.  

- **1000BASE-LX:** Um padrão de Ethernet gigabit que usa fibra monomodo para distâncias mais longas, até 5 km.

- **10GBASE-SR e 10GBASE-LR:** Estes padrões são para Ethernet de 10 Gbits/s, usando fibras multimodo e monomodo, respectivamente, cobrindo distâncias que variam de centenas de metros a 10 km.  

- **Padrões de Fibra:** Esta versão suporta fibra óptica para transmissões de longa distância, utilizando fibra monomodo e multimodo. As variantes incluem 10GBase-SR, 10GBase-LR, e 10GBase-ER, cada uma projetada para diferentes distâncias (de 300 m a 40 km).
Codificação: Utiliza a codificação 64B/66B, que oferece uma maior eficiência com menos overhead comparado com a codificação 8B/10B.  
- **Aplicação:** Comumente utilizada em centros de dados, redes metropolitanas e enlaces de longa distância, conectando grandes servidores e switches.

- **40 e 100 Gigabit Ethernet (IEEE 802.3ba):** Introduzida em 2010, essa norma define Ethernet com taxas de 40 Gbps e 100 Gbps. Ela foi projetada para suportar redes de alto desempenho, como data centers e enlaces de backbone da Internet, operando em fibra óptica. 

- **Compatibilidade:** Mantém compatibilidade com as versões anteriores da Ethernet, enquanto aumenta a largura de banda para atender às crescentes demandas de dados.
Uso de Fibra: As redes podem utilizar fibras monomodo ou multimodo, com diferentes variantes de modulação e codificação, incluindo o uso de múltiplas pistas paralelas para atingir a capacidade necessária.

- **400 Gigabit Ethernet (IEEE 802.3bs):** Introduzida em 2017, essa norma introduziu transmissões ópticas de 400 Gbps, cruciais para grandes redes corporativas, de operadoras e data centers.

- **Redes Ópticas Passivas (PONs):** O padrão IEEE também inclui a especificação para EPON (Ethernet PONs), que utiliza fibra óptica para transmitir dados entre uma estação central e várias casas ou negócios. Essa tecnologia permite o compartilhamento eficiente da largura de banda da fibra entre múltiplos usuários.


## Um pouco de história

- 1966 - Primeira proposta de fibra óptica para comunicações com perdas de 1000 dB/km.
  - Kao e Hockham publicam uma análise detalhada prevendo que a perda de fibra óptica poderia ser reduzida para menos de 20 dB/km.
  - Isso atrai o interesse do British Post Office, que investe em pesquisa para reduzir a perda de fibra.
- 1ª Geração (Década de 1970)
  - Tecnologia: Transmissão de luz no comprimento de onda de 0,8 μm (micrometros) usando lasers semicondutores.
  - Fibra: Fibra multimodo, o que causava maior atenuação e dispersão modal, limitando a distância da transmissão.
  - Capacidade de Transmissão: Alcance limitado de até 45 Mbps, com distâncias de alguns quilômetros.
  - Largura de Banda: Aproximadamente 45 MHz.
- 2ª Geração (Década de 1980)
  - Tecnologia: Mudança para comprimentos de onda de 1,3 μm, utilizando lasers de semicondutores mais eficientes e fibras monomodo.
  - Fibra: Fibras monomodo, que reduziram consideravelmente a dispersão, permitindo maiores distâncias de transmissão sem repetição.
  - Capacidade de Transmissão: Velocidades entre 100 Mbps e 1,7 Gbps, com distâncias de até 50 km sem repetidores.
  - Largura de Banda: Entre 200 MHz e 1 GHz, por conta do uso de fibras monomodo.
- 3ª Geração (Década de 1990)
  - Tecnologia: Utilização de lasers em comprimentos de onda de 1,55 μm, que se alinham com a menor atenuação da fibra óptica.
  - Amplificação Óptica: Introdução dos amplificadores de fibra dopada com érbio (EDFA), eliminando a necessidade de regeneração de sinais.
  - Capacidade de Transmissão: Velocidades de até 10 Gbps em longas distâncias (centenas de quilômetros).
  - Largura de Banda: Aproximadamente 2,5 GHz a 10 GHz, com base nos lasers de 1,55 μm e EDFA.
- 4ª Geração (Anos 2000)
  - Tecnologia: Introdução da multiplexação por divisão de comprimento de onda (WDM), permitindo a transmissão simultânea de múltiplos canais no mesmo fio de fibra.
  - Densidade de Canais: Dense Wavelength Division Multiplexing (DWDM) para aumentar a densidade de canais.
  - Capacidade de Transmissão: Capacidade de até 400 Gbps, com potencial para escalabilidade em terabits por segundo.
  - Largura de Banda: 4 THz a 8 THz, com o uso de Dense Wavelength Division Multiplexing (DWDM).
  - Explosão de capacidade de fibra:
    - A demanda por capacidade de transmissão cresce, mas a bolha das telecomunicações estoura devido à super capacidade instalada.
    - Ao longo do tempo, no entanto, essa capacidade excedente foi sendo aproveitada, à medida que o tráfego de dados aumentou com o avanço da internet e das tecnologias digitais.
- 5ª Geração (Anos 2010 em diante)
  - Tecnologia: Utilização de WDM com tecnologias coerentes, combinadas com modulação de alta ordem como QAM (modulação de amplitude em quadratura).
  - Processamento Digital de Sinais (DSP): Aplicado para compensar dispersões e melhorar a eficiência da transmissão.
  - Capacidade de Transmissão: Velocidades de transmissão superiores a 1 Tbps por fibra.
  - Largura de Banda: Mais de 10 THz, usando tecnologias como modulação coerente.
  - Desafios: Aumento de eficiência no uso do espectro e otimização do consumo energético.
- 6ª Geração (Futuro)
  - Tecnologia Esperada: Transmissões utilizando redes de fibra óptica inteligente, com capacidades de multi-terabits por segundo. Espera-se o uso mais avançado de inteligência artificial para gerenciar redes ópticas.
  - Capacidade de Transmissão: Aumento exponencial com técnicas como a multiplexação espacial e melhorias no WDM.
  - Largura de Banda: Projeção de mais de 20 THz com técnicas de multiplexação espacial.
  - Foco: Redução do consumo energético e aumento da sustentabilidade das redes ópticas.

## Evolução de quatro gerações de sistemas ópticos

![image](https://drive.usercontent.google.com/download?id=1Z1qnKKCLjxK467O6jAdTd7IGkGvfyhjx&export=view&authuser=0)

## Evolução e Previsão dos Sistemas Ópticos Comerciais

![image](https://drive.usercontent.google.com/download?id=1s2nllvSG6N5vw81ysiwvpOCEm5Y-7dSQ&export=view&authuser=0)

## Segurança em Redes Ópticas

Embora a fibra óptica ofereça vantagens significativas em termos de proteção contra interferências eletromagnéticas e redução de perda de sinal, ela não está completamente imune a ameaças. A interceptação de dados, também conhecida como "tapping óptico", é uma das principais preocupações de segurança em redes baseadas em fibra.

- **Vulnerabilidades:** A fibra óptica não emite nenhum tipo de radiação que possa ser captada sem contato direto, saindo a frente dos cabos de cobre. No entanto, é possível acessar o sinal óptico de uma fibra através de técnicas de intrusão óptica, como o tapping, onde dispositivos especializados podem acoplar-se à fibra e extrair os sinais luminosos sem quebrar ou danificar fisicamente o cabo. Este tipo de interceptação é altamente sofisticado e muitas vezes difícil de detectar.

- **Técnicas de Tapping Óptico:** O tapping óptico envolve a inserção de dispositivos entre as camadas do cabo de fibra ou até mesmo a utilização de dispositivos de curvatura óptica que desviam uma pequena parte do sinal luminoso para fora da fibra, sem interromper a transmissão. Essa técnica pode ser usada para espionagem ou roubo de dados e, embora seja mais difícil de implementar do que a interceptação em redes de cobre, ainda representa uma ameaça em ambientes que exigem alta segurança.


## Tecnologias atuais e principais possíveis avanços
- **Aumento da Capacidade de Transmissão:** A capacidade de transmissão de dados através de fibras óticas têm aumentado exponencialmente. Um exemplo notável é o recorde de transmissão de 319 Tbps (terabits por segundo) alcançado pelo Instituto Nacional de Tecnologia da Informação e Comunicação (NICT) do Japão. Isso demonstra o potencial da fibra ótica para suportar a crescente demanda por largura de banda.

- **Fibra Ótica de Múltiplos Modos:** As fibras óticas de múltiplos modos permitem a transmissão de dados por múltiplos caminhos de luz, aumentando a capacidade e a eficiência energética. Essa tecnologia é especialmente útil em ambientes onde a demanda por dados é alta.

- **Fibra Ótica Flexível:** A flexibilidade das fibras óticas tem sido aprimorada com o uso das fibras de carbono e compósitos, permitindo sua utilização em espaços reduzidos e curvas apertadas sem perda de desempenho. Isso é crucial para aplicações em ambientes urbanos densos e na área médica.

- **Integração com Redes 5G:** A fibra ótica é fundamental para a infraestrutura das redes 5G, garantindo alta velocidade e baixa latência. A implantação do 5G está impulsionando a demanda por redes de fibra ótica de alta capacidade, conectando estações base e suportando a comunicação sem fio de próxima geração.

- **Aplicações Além das Telecomunicações:** Além das telecomunicações, a fibra ótica está sendo utilizada em sensores óticos, medicina e monitoramento estrutural. Pesquisas estão explorando novas possibilidades para expandir o uso da fibra ótica em diversas áreas.

- **Redução de Custos e Aumento da Acessibilidade:** Apesar dos altos custos iniciais, a tecnologia de fibra ótica está se tornando mais acessível. A substituição de componentes como transceptores óticos pode aumentar a capacidade das redes existentes sem a necessidade de grandes investimentos.

- **Sustentabilidade e Eficiência Energética:** A fibra ótica é mais eficiente energeticamente em comparação com outras tecnologias de transmissão de dados. Isso contribui para a sustentabilidade das redes de comunicação, reduzindo o consumo de energia e o impacto ambiental.

## Vantagens da Fibra Óptica
*As fibras óticas apresentam diversas vantagens em relação aos cabos de cobre*  
- **Maior Capacidade de Transmissão:** A fibra ótica suporta uma largura de banda muito maior, permitindo a transmissão de grandes volumes de dados.  
- **Baixa Interferência Eletromagnética:** Por utilizar luz em vez de sinais elétricos, as fibras óticas são imunes à interferência eletromagnética, garantindo uma transmissão mais estável.  
- **Menor Atenuação:** A perda de sinal (atenuação) em fibras óticas é significativamente menor em comparação com cabos de cobre, especialmente em longas distâncias, onde amplificadores ópticos podem ser utilizados para reforçar o sinal sem a necessidade de repetidores frequentes.  
- **Segurança:** Fibras ópticas são mais seguras contra interceptações, já que não irradiam.

## Desvantagens da Fibra Óptica

- **Atenuação:** A perda de intensidade do sinal ocorre à medida que a luz viaja pela fibra. Isso pode ser causado por absorção, espalhamento da luz em imperfeições do material da fibra, ou pela presença de dobras e curvaturas na fibra.  
- **Dispersão:** Ocorre quando diferentes comprimentos de onda da luz viajam a velocidades ligeiramente diferentes, resultando na ampliação do pulso de luz ao longo do tempo. A dispersão pode ser modal (em fibras multimodo) ou cromática (variação de velocidades dentro do núcleo).
- **Amplificação e Dispersão Cromática:** Para transmissões de longas distâncias, amplificadores ópticos podem ser utilizados para reforçar o sinal. Um dos desafios é a dispersão cromática, um fenômeno que causa um alargamento dos pulsos de luz ao longo do tempo, afetando a qualidade do sinal transmitido. A dispersão cromática é mais pronunciada em longas distâncias e deve ser gerenciada com tecnologias específicas, como fibras com baixa dispersão ou através de modulações avançadas, como a DMT (Discrete Multi-Tone Modulation). Adicionalmente, a absorção e o espalhamento de luz também são fatores importantes que afetam a performance da transmissão em fibras ópticas, e podem ser mitigados por janelas de transmissão específicas (850 nm, 1310 nm e 1550 nm), onde as perdas são minimizadas.


## Aplicações da Fibra Óptica

### **Transmissão de Longa Distância em Backbones de Rede**
Os backbones de rede são os "eixos principais" que formam a espinha dorsal da Internet e outras grandes redes. A fibra óptica é ideal para essa aplicação porque oferece várias vantagens:

-   **Alta Capacidade de Transmissão**: As fibras ópticas podem transportar grandes quantidades de dados, alcançando velocidades de terabits por segundo. Essa alta capacidade é essencial para suportar o tráfego de dados massivo que circula nos backbones de redes.
-   **Baixa Atenuação**: A fibra óptica sofre menos atenuação (perda de sinal) ao longo de grandes distâncias em comparação com os cabos de cobre. Isso significa que o sinal pode viajar centenas de quilômetros sem necessitar de amplificação ou regeneração, reduzindo os custos operacionais.
-   **Imunidade à Interferência Eletromagnética**: A fibra óptica é imune a interferências eletromagnéticas (EMI), o que é crucial em ambientes onde há muitos dispositivos eletrônicos e campos magnéticos. Isso garante uma transmissão de dados mais limpa e estável.

<figure>
  <img src="https://github.com/user-attachments/assets/b701290c-70db-4f15-a97b-17f8208799c2" alt="Backbone">
  <figcaption style="text-align: center;">O backbone da NSFNET em 1988.</figcaption>
</figure>

### **Redes de Área Local (LANs) de Alta Velocidade**

As LANs (Local Area Networks) de alta velocidade utilizam fibra óptica para conectar diferentes dispositivos e sistemas dentro de uma área limitada, como um prédio ou campus:

-   **Alta Largura de Banda**: A fibra óptica proporciona uma largura de banda muito maior em comparação com o cobre, permitindo a transmissão de grandes quantidades de dados rapidamente. Isso é importante em ambientes corporativos e institucionais onde muitos usuários precisam acessar dados simultaneamente.
-   **Menor Latência e Alta Confiabilidade**: A transmissão por fibra óptica geralmente apresenta menor latência e é mais confiável, o que é essencial para aplicações em tempo real, como videoconferências e serviços baseados em nuvem.
-   **Segurança Física e Integridade dos Dados**: As LANs de fibra óptica oferecem maior segurança física, pois são mais difíceis de grampear do que cabos de cobre, tornando-as ideais para instalações que exigem alta segurança de dados.

### **Cabos Submarinos**

Os cabos submarinos de fibra óptica são a espinha dorsal da conectividade global de Internet:

-   **Conexões Intercontinentais**: Cabos submarinos interligam continentes, transportando a maior parte do tráfego de dados internacional. Eles são críticos para a infraestrutura da Internet e para serviços de telecomunicações.
-   **Alta Confiabilidade e Longevidade**: Fibras ópticas são escolhidas para cabos submarinos devido à sua durabilidade, alta capacidade de dados e resistência a condições adversas, como pressão e corrosão da água salgada.
-   **Baixa Latência em Longas Distâncias**: A fibra óptica permite a transmissão de dados com latência reduzida, o que é crucial para aplicações financeiras, de comunicação e outros serviços que requerem resposta rápida.

### **Redes Ópticas Passivas (PONs)**

Redes Ópticas Passivas (PONs) são usadas para distribuir serviços de internet, vídeo e voz em redes de acesso:

-   **Estrutura Passiva**: PONs utilizam divisores ópticos passivos para dividir a capacidade de um único cabo de fibra em múltiplas conexões de usuário final. Isso elimina a necessidade de dispositivos ativos (alimentados) no caminho, reduzindo custos de energia e manutenção.
-   **Eficiência na Distribuição de Banda**: As PONs permitem a distribuição eficiente de alta largura de banda para múltiplos usuários simultaneamente, fazendo uso eficaz da infraestrutura de fibra existente.
-   **Aplicações em Áreas Urbanas e Suburbanas**: PONs são particularmente úteis em áreas urbanas e suburbanas onde a densidade de usuários é alta, permitindo que provedores de serviços ofereçam internet de alta velocidade e serviços de vídeo sob demanda.

### **Acesso à Internet em Alta Velocidade (FTTH - Fiber To The Home)**

O FTTH (Fiber to the Home) é uma tecnologia que leva a fibra óptica diretamente até as residências dos usuários finais:

-   **Alta Velocidade e Capacidade de Dados**: A fibra óptica oferece velocidades de download e upload muito superiores em comparação com DSL ou conexões de cabo coaxial. Isso permite suportar serviços de Internet de alta demanda, como streaming de vídeo 4K/8K, jogos online e videoconferências.
-   **Capacidade de Expansão Futura**: As redes de fibra óptica são facilmente expansíveis para atender a futuras necessidades de largura de banda, sem a necessidade de substituir a infraestrutura física.
-   **Melhor Qualidade de Serviço (QoS)**: Com o FTTH, os provedores de serviços podem oferecer maior qualidade de serviço, com menor latência e menos variações de desempenho, mesmo em horários de pico.

<figure>
  <img src="https://github.com/user-attachments/assets/a8a0414e-3d97-4d70-aa3c-726cdd47e433" alt="Backbone">
  <figcaption style="text-align: center;">Rede Óptica passiva para Fiber To The Home</figcaption>
</figure>

## Exemplos práticos de uso

### Google e Cabos Submarinos - "Grace Hopper" e "Dunant"

O Google, como parte de sua infraestrutura global de rede, investiu em vários cabos submarinos de fibra óptica, incluindo o cabo ["Grace Hopper"](https://cloud.google.com/blog/products/infrastructure/announcing-googles-grace-hopper-subsea-cable-system) que conecta os Estados Unidos ao Reino Unido e à Espanha, e o ["Dunant"](https://cloud.google.com/blog/products/infrastructure/googles-dunant-subsea-cable-is-now-ready-for-service), que conecta os EUA à França. Esses cabos são fundamentais para expandir a capacidade de transmissão de dados entre continentes e melhorar a velocidade e a confiabilidade da internet global.

O cabo "Grace Hopper" tem cerca de 6.300 km de comprimento e pode transmitir até 340 terabits por segundo (Tbps). Esses cabos são compostos de múltiplas fibras ópticas, protegidas por camadas de aço, cobre e plástico, projetadas para resistir a pressões extremas e danos no fundo do mar. Eles utilizam tecnologias avançadas de regeneração de sinal, chamadas repetidores, para amplificar os sinais ópticos ao longo da transmissão.

![image](https://github.com/user-attachments/assets/4b131550-c804-4b02-976a-287ea8850433)


### "Smart Grid" no Brasil - Eletrobras
A Eletrobras, maior empresa de energia da América Latina, utiliza fibra óptica em sua infraestrutura de "Smart Grid" (rede inteligente) para monitorar e controlar o fluxo de eletricidade em tempo real. [A fibra óptica conecta subestações e sensores ao longo das linhas de transmissão para melhorar a eficiência energética e a segurança.](https://www.datacenterdynamics.com/br/opini%C3%B5es/eletrobras-utiliza-tecnologia-cisco-para-projeto-de-smart-grid-em-seis-estados/)

[Os sensores conectados por fibra óptica monitoram](https://www.osetoreletrico.com.br/cidades-inteligentes-o-futuro-do-smart-grid-no-brasil/) a carga, temperatura, umidade e outros fatores críticos que afetam a distribuição de energia. A Eletrobras usa esses dados para prever falhas, otimizar o fluxo de energia, e reduzir o desperdício, garantindo um fornecimento de energia mais estável e sustentável para milhões de brasileiros.


### Monitoramento da Ponte Golden Gate, São Francisco, EUA
A Ponte Golden Gate, uma das pontes mais icônicas do mundo, [utiliza sensores de fibra óptica](https://link.springer.com/chapter/10.1007/978-3-031-39117-0_67) para monitorar sua integridade estrutural em tempo real. Esses sensores ajudam a detectar vibrações, tensões, e outras alterações que poderiam indicar problemas estruturais.

Sensores de fibra óptica embutidos nos cabos de sustentação e na estrutura da ponte medem mudanças nas tensões e nas vibrações. Os dados são transmitidos para um centro de controle, onde são analisados para detectar sinais de deterioração ou danos que possam comprometer a segurança. Isso permite intervenções preventivas e minimiza o risco de falhas catastróficas.

### Fibra Óptica em Hospitais
Procedimentos avançados, como a Cirurgia Minimamente Invasiva, requerem iluminação interna para que as câmeras possam capturar as imagens adequadamente.

Para conduzir a luz até o endoscópio que será inserido no corpo do paciente, luz essa proveniente de uma fonte específica, [são utilizados cabos condutores compostos por feixes de fibras ópticas.](https://www.strattner.com.br/blog/voce-sabe-o-que-e-e-como-e-feita-a-fibra-otica/)

Essas fibras são produzidas com um elevado padrão de qualidade, pois qualquer falha nesse sistema pode resultar em imagens endoscópicas escuras, causando prejuízos tanto para o paciente quanto para o médico.
