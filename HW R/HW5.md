# Home Work 5

> Students should read articles "Scalability Issues in Online Social Networks" and On System Scalability, and prepare a 30-minute workshop on their understanding of the work. The presentations of the seminars will be selected by lottery.

#### Scalability Issues in Online Social Networks
> **Resumo** A última década testemunhou um grande aumento da popularidade e uso de redes sociais, comoo: Facebook, Twitter e YouTube.
Além disso, os avanços nas tecnologias da Web, juntamente com as redes sociais, permitiu aos usuários não só acessar, mas também gerar conteúdo de várias formas. A enorme quantidade deconteúdo produzido e o tráfego de rede resultante dá origem a graves problemas de escalabilidade para redes sociais,com o manuseio de um grande número de usuários, gerenciamento de infraestrutura, tráfego interno de rede, conteúdo disseminação e armazenamento de dados existem poucas pesquisas realizadas para explorar as diferentes dimensões deredes sociais, como segurança, privacidade e aquisição de dados. A maioria das pesquisas foca a privacidade ou questões relacionadas à segurança e não abordam especificamente os desafios de escalabilidade enfrentados pelas redes sociais. Dentrodesta pesquisa, fornecemos um estudo abrangente das redes sociais, juntamente com suas características significativase categorizar arquiteturas de redes sociais em três grandes categorias: (a) centralizada, (b) descentralizada e (c) híbrido.

1. *Introdução* Aqui nos é introduzido a respeito de redes sociais e de como ela facilita a comunicação de indivíduos que as usam, que a web 2.0 junto com redes sociais modificaram o dia a dia de diversas pessoas especificamente a maneira como elas se comunicam. Fala sobre pesquisas feitas na área e de como elas se restringe a campos específicos.

2. *Redes sociais* são elas que conectam od usuários a amigos, familiares e pessoas que não conheça que tenha algum interesse em comum ou até mesmo passatempos, com base nos fatores de que a quantidade de número de usuários a de aumentar significativamente, como o modelo de comunicação, o controle dos usuários no perfildados e UGCs, e presença ou ausência de uma autoridade centralizada, as redes sociais sãocategorizados em três arquiteturas amplas: (a) centralizada, (b) descentralizada e (c)
híbrido.

  **Fazendo uma pesquisa rápida e me baseando no que foi dito pude encontrar uma boa definição**

  1. *Redes sociais centralizadas* Toda a informação passa por um dos nós rede  (o centro) para, então, poder ser distribuída para os demais nós.
  2. *Redes sociais descentralizadas* funcionam como várias redes centralizadas conectadas entre si, na qual vários nós centralizam e distribuem a informação.
  3. *Redes sociais hibridas* não existem centros e qualquer nó da rede pode receber e disseminar a informação para qualquer outro nó. Ele tambem fala de redes sociais pee-to-peer e de redes sociais moveis que é a que mais cresce nos ultimos anos.

3. *ESCALABILIDADE NAS REDES SOCIAIS* O desempenho das redes sociais depenedem da quantidade de carga que elas suportam onde um sistema informatico refere-se ao conjunto de recursos computacionais que incluem até o poder de processamento.
A rede social escalável não deve comprometer o desempenho e manter o mesmo nível de latência e tempo de resposta, mesmo que mais conteúdos sejam adicionados e mais usuários se conectam simultaneamente à rede social.

  1. *Características distintivas das redes sociais on-line* e algumas características distintivas das redes sociais online que os separa de outras aplicações da Internet, como navegação, e-mail, pesquisa, Música, vídeos e jogos.

      1. **Dynamic Social Graph.**
      2. **Frequency of Content Generation.**
      3. **Unpredictable Expansion.**
      4. **Always-On Connectivity.**
      5. **Asymmetric Relationships.**

  2. *. Problemas de escalabilidade em redes sociais centralizadas*

      1. **Large Number of Highly Connected Users.**
        ![tabela de usuarios](/images/hw5/image1.PNG)
      2. **Infrastructure Issues.**
        ![data Network center](/images/hw5/image2.PNG)
      3. **Internal Network Traffic.**
        ![data Network center](/images/hw5/image3.PNG)
      4. **User-Generated Content Management and Dissemination.**
        ![data Network center](/images/hw5/image4.PNG)
      5. **Database Scalability.** Comparação de sistemas de armazenamento escaláveis seleccionadas:

        1. Cassandra
        2. Haystack
        3. Bigtable
        4. Megastore
        5. Platform for Nimble Universal Table Storage (PNUTS)
        6. Dynamo
        7. MongoDB
        8. Cluster of Order-Preserving Servers
        9.  Scalable Consistency Adjustable Data Storage

  3. *Problemas de escalabilidade em descentralizadas Redes Sociais* Em termos de recursos, como espaço de armazenamento e largura de banda de rede, descentralizada redes sociais são consideradas escalável porque os usuários podem compartilhar virtualmente ilimitado armazenamento e largura de banda contribuído por outros usuários de uma rede social. Os seguintes problemas de escalabilidade de redes sociais descentralizadas são aplicáveis ao P2P e redes sociais móveis:
      1. **Profile and Content Availability.**
      2. **Content Distribution.**
      3. **Energy Efficiency.**
      4. **Security and Privacy**
      5. **Large-Scale Implementation.**

  4. *Escalabilidade de Redes Sociais híbridos*

  5. *Métricas de escalabilidade para redes sociais* Com base na revisão da literatura, nós esboçamos algumas métricas para avaliar o scaladade de arquiteturas de rede sociais. Uma discussão detalhada e em profundidade sobre cada parametro e seu impacto entre todas as arquiteturas discutidos é fornecido no seguinte seções.
      1. **Availability.**
      2. **Latency.**
      3. **Interserver Communication.**
      4. **Cost of Engineering and Resources.**
      5. **Energy Consumption and Maintenance Cost**
      6. **Internet Bandwidth Requirement**
      7. **Data Consistency.**
      8. **Data Replication.**
      9. **Privacy and Security.**
      ![metricas](/images/hw5/image5.PNG)
