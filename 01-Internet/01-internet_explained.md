# Internet Explained

## Links Úteis e Bibliografia Utilizada

- [The internet, explained - Vox](https://www.vox.com/2014/6/16/18076282/the-internet)

- [O que é TCP/IP? - Tecmundo](https://www.tecmundo.com.br/o-que-e/780-o-que-e-tcp-ip-.htm)

- [O que é IPv6](https://www.infowester.com/ipv6.php)

### O que é Internet?

Internet é, nos dias atuais, uma rede global de computadores. Começou como um projeto de pesquisa acadêmico em 1969, e com o tempo, virou uma rede mundial que conecta o mundo inteiro.

A internet é muito facilmente confundida com a web, porém, a web é apenas uma das aplicações da internet, outros exemplos de aplicações são: email e BitTorrent.

### Quem criou a Internet

A internet começou com a [ARPANET](https://pt.wikipedia.org/wiki/ARPANET), uma rede de pesquisa acadêmica, que foi fundada pelos militares americanos. No início, por conta da guerra fria, foi usada para o armazenamento seguro e troca de informações entre sedes militares. Desde seu início, em 1969, a internet teve várias melhorias, uma delas foi a criação do protocolo [TCP/IP](https://pt.wikipedia.org/wiki/TCP/IP) no ano de 1973, mas apenas no ano de 1983 foi que a ARPANET adotou o protocolo.

### O Protocolo TCP/IP

De forma resumida, o TCP/IP é o principal protocolo de envio e recebimento de dados na internet. TCP significa _Transmission Control Protocol_ (Protocolo de Controle de Transmissão) e o IP, _Internet Protocol_ (Protocolo de Internet).

O Protocolo é uma espécie de linguagem utilizada para que dois computadores consigam se comunicar. Por mais que duas máquinas estejam conectadas à mesma rede, há a necessidade delas falarem a mesma "língua", e o TCP/IP é justamente usada como "idioma", auxiliando assim, para que as aplicações possam conversar entre si.

#### Pilha de Protocolos

O TCP/IP é um conjunto de protocolos. Estes protocolos são divididos em quatro camadas: **Aplicação**, **Transporte**, **Rede** e **Interface**. Cada uma delas é responsável pela execução de tarefas distintas, e essa divisão é uma forma de garantir a integridade dos dados que trafegam pela rede.

![](imgs/pilha_protocolos.jpg)

- Aplicação

Essa camada é utilizada pelos programas para enviar e receber informações de outros programas através da rede. Nela você encontra protocolos como [SMTP (para email)](https://www.hostgator.com.br/blog/o-que-e-protocolo-smtp/), [FTP (Transferência de arquivos)](https://pt.wikipedia.org/wiki/Protocolo_de_Transfer%C3%AAncia_de_Arquivos) e o mais conhecido [HTTP (Para navegar na internet)](https://pt.wikipedia.org/wiki/Hypertext_Transfer_Protocol). Assim que os dados são processados pela camada de aplicação, eles são enviados para a próxima divisão.

- Transporte e Rede

A camada de transporte é responsável por receber os dados enviados pela cama de Aplicação, verificar a integridade deles e dividi-los em pacotes. Após essas tarefas, as informações são encaminhadas para a camada internet, que é a próxima camada.

Na Rede, os dados empacotados são recebidos e anexados ao endereço virtual (IP) do computador remetente e do destinatário. Agora é a vez dos pacotes serem, enfim, enviados pela internet. Para isso, são passados para a camada Interface.

- Interface

A tarefa da Interface é receber e enviar pacotes pela rede. Os protocolos utilizados nessa camada dependem do tipo de rede que está sendo utilizado. Atualmente, o mais comum é o Ethernet, disponível em diferentes velocidades.

#### Conclusão para o TCP/IP

Todas as camadas e protocolos citados acima fazem parte do TCP/IP. É assim que ele trabalha, em etapas. Apesar de serem muitas informações, o importante é ter em mente que o TCP/IP é utilizado para a **transferência de informações** pela rede entre computadores.

Vamos resumir então os processos que ocorrem, primeiro há o recebimento das informações (camada de aplicação), depois elas são empacotadas para o formato da rede (transporte). Por fim, os dados são endereçados (rede) e enviados (interface).

### O que é um Endereço de IP

Endereços de Protocolos da Internet são números que os computadores usam para identificar uns aos outros na internet.

Um departamento [ICANN](https://pt.wikipedia.org/wiki/Corpora%C3%A7%C3%A3o_da_Internet_para_Atribui%C3%A7%C3%A3o_de_Nomes_e_N%C3%BAmeros) conhecido como __Autoridade de Números Atribuídos à Internet__, que é responsável pela distribuição de endereços de IP para assegurar que duas organizações diferentes não usem o mesmo endereço.

### O que é IPv6?

- Endereço IP

Para entender melhor o que é IPv6, precisamos entender a sua versão anterior, o IPv4, que convencionamos chamar apenas de IP. O IPv4 é composto por uma sequência numérica no seguinte formato: **x.x.x.x**, onde x é um número que pode ir de 0 a 255, por exemplo:

**189.34.242.229**

Quando você contrata uma empresa para fornecer acesso à internet à sua residência, por exemplo, o provedor irá fornecer um endereço IP de sua cota (em boa parte dos casos, esse endereço muda a cada conexão) para conectar seu computador ou sua rede à internet. Websites também têm endereço IP, afinal, ficam armazenados em servidores que, obviamente, estão conectados à internet.

O formato do IPv4 é uma sequência de 32 bits (ou quatro conjuntos de 8 bits) e isso permite, teoricamente, a criação de até 4.294.967.296 endereços. É uma quantidade grande, mas como hoje em dia cada dispositivo (Computador, smartphone, tablet e etc.), deve ter um IP, esse número acaba se tornando insuficiente conforme passa o tempo.

Esse problema existe porque a internet não foi planejada de forma a ser tão grande. A ideia original era a de se criar um sistema de comunicação que interligasse centros de pesquisa. Somente quando a internet passou a ser utilizada de maneira ampla é que ficou claro que o número máximo de endereços IP poderia ser atingido em um futuro relativamente próximo. Foi a partir desta percepção que o projeto IPng (_Internet Protocol next generation_) teve início, dando origem ao que conhecemos como IPv6.

- Endereços IPv6

A criação do IPv6 consumiu vários anos, afinal, uma série de parâmetros e requisitos necessita ser observada para que problemas não ocorram ou, pelo menos, para que sejam substancialmente amenizados em sua implementação. Em outras palavras, foi necessário fazer o IPv4 evoluir, e não criar um padrão completamente novo.

A primeira diferença que se nota entre o IPv4 e o IPv6 é o seu formato: o primeiro é constituído por 32 bits, como já informado, enquanto que o segundo é formado por 128 bits. Com isso, teoricamente, a quantidade de endereços disponíveis pode chegar a 340.282.366.920.938.463.463.374.607.431.768.211.456, o que torna uma possibilidade extraordinariamente alto em relação à criação de IPs, essa é uma grande diferença entre os dois tipos de endereços, mas existem mais diferenças, caso queira entender mais a fundo, visite os seguintes link:

- [IPv6.br](http://ipv6.br/)
- [IPv6 Forum](https://www.ipv6forum.com/)
- [IPv6 Wikipédia](https://pt.wikipedia.org/wiki/IPv6)
- [TCP/IP (v4 and v6) Technical Reference - Microsoft](https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/dd379473(v=ws.10)?redirectedfrom=MSDN)

### Como Internet Wireless Funciona?

Nos seus primeiros anos, o acesso à internet era feito primordialmente por cabos físicos. Porém, mais recentemente, o acesso à internet sem fio se tornou cada vez mais comum.

Existem dois tipos básicos de acesso à internet sem fio: wifi e celular. A rede [Wifi](https://pt.wikipedia.org/wiki/Wi-Fi) é relativamente simples. Qualquer um pode comprar equipamento de conexão às redes wifi, afim de providenciar acesso à internet na sua casa ou empresa. As redes Wi-Fi usam espectro não licenciado: frequências eletromagnéticas que estão disponíveis para qualquer pessoa usar gratuitamente. Para evitar que as redes dos vizinhos interfiram umas nas outras, existem limites estritos na potência (e, portanto, no alcance) das redes wifi.

As redes celulares são mais centralizadas. Eles trabalham dividindo o território de serviço em células. Nas áreas mais densas, as células podem ser tão pequenas quanto um único quarteirão; nas áreas rurais, uma célula pode ter quilômetros de extensão. Cada célula tem uma torre em seu centro que presta serviços aos dispositivos de lá. Quando um dispositivo se move de uma célula para outra, a rede automaticamente transfere o dispositivo de uma torre para outra, permitindo que o usuário continue se comunicando sem interrupção.

Cells are too large to use the unlicensed, low-power spectrum used by wifi networks. Instead, cellular networks use spectrum licensed for their exclusive use. Because this spectrum is scarce, it is usually awarded by auction.

As células são muito grandes para usar o espectro não licenciado e de baixa potência usado pelas redes wifi. Em vez disso, as redes celulares usam espectro licenciado para uso exclusivo. Como esse espectro é escasso, geralmente é concedido por leilão.

### O que é a Cloud?

A nuvem (_Cloud_) descreve uma abordagem à computação que se tornou popular no início dos anos 2000. Ao armazenar arquivos em servidores e fornecer software pela Internet, a computação em nuvem oferece aos usuários uma experiência de computação mais simples e confiável. A computação em nuvem permite que consumidores e empresas tratem a computação como uma utilidade, deixando os detalhes técnicos para as empresas de tecnologia.

Por exemplo, na década de 1990, muitas pessoas usavam o Microsoft Office para editar documentos e planilhas. Eles armazenavam documentos em seus discos rígidos. E quando uma nova versão do Microsoft Office foi lançada, os clientes tiveram que comprá-la e instalá-la manualmente em seus PCs.

Por outro lado, o Google Docs é um pacote de escritório em nuvem. Quando um usuário visita docs.google.com, ele obtém automaticamente a versão mais recente do Google Docs. Como os arquivos dela são armazenados nos servidores do Google, eles estão disponíveis em qualquer computador. Melhor ainda, ela não precisa se preocupar em perder seus arquivos em uma falha no disco rígido. (A Microsoft agora tem seu próprio pacote de escritório em nuvem chamado Office 365.)

Há muitos outros exemplos. Gmail e Hotmail são serviços de e-mail em nuvem que substituíram amplamente os clientes de e-mail de desktop, como o Outlook. O Dropbox é um serviço de computação em nuvem que sincroniza automaticamente dados entre dispositivos, evitando que as pessoas precisem carregar arquivos em disquetes. O iCloud da Apple copia automaticamente as músicas e outros arquivos dos usuários do computador desktop para os dispositivos móveis, poupando os usuários do incômodo de sincronizar por meio de uma conexão USB.

A computação em nuvem também está tendo um grande impacto para as empresas. Na década de 1990, as empresas que queriam criar um site precisavam comprar e operar seus próprios servidores. Mas em 2006, a Amazon.com lançou o Amazon Web Services, que permite aos clientes alugar servidores por hora. Isso reduziu a barreira de entrada para a criação de sites e tornou muito mais fácil para os sites expandirem rapidamente a capacidade à medida que se tornam mais populares.

### O que é SSL?

[SSL](https://www.tecmundo.com.br/seguranca/1896-o-que-e-ssl-.htm), é a abreviação de Secure Sockets Layer, é uma família de tecnologias de criptografia que permite aos usuários da Web proteger a privacidade das informações que transmitem pela Internet.

Ao visitar um site seguro, como o Gmail.com, você verá um cadeado ao lado do URL, indicando que suas comunicações com o site estão criptografadas.

Esse bloqueio deve sinalizar que terceiros não poderão ler nenhuma informação que você enviar ou receber. Sob o capô, o SSL faz isso transformando seus dados em uma mensagem codificada que apenas o destinatário sabe como decifrar. Se uma parte mal-intencionada estiver ouvindo a conversa, ela verá apenas uma sequência de caracteres aparentemente aleatória, não o conteúdo de seus e-mails, postagens no Facebook, números de cartão de crédito ou outras informações privadas.

O SSL foi introduzido pela Netscape em 1994. Em seus primeiros anos, era usado apenas em alguns tipos de sites, como sites de bancos online. No início de 2010, Google, Yahoo e Facebook usavam criptografia SSL para seus sites e serviços online. Mais recentemente, houve um movimento para tornar o uso do SSL universal. Em 2015, a Mozilla anunciou que futuras versões do navegador Firefox tratariam a falta de criptografia SSL como uma falha de segurança, como forma de incentivar todos os sites a atualizar. O Google está considerando dar o mesmo passo com o Chrome.

### O que é DNS

O [Domain Name System (DNS)](https://pt.wikipedia.org/wiki/Sistema_de_Nomes_de_Dom%C3%ADnio) é o motivo pelo qual você pode acessar os sites simplesmente digitando seu endereço, www.google.com, por exemplo, em vez de um endereço numérico difícil de lembrar, como 216.146.46.10.

O sistema é hierárquico. Por exemplo, o domínio .com é administrado por uma empresa chamada Verisign. A Verisign atribui subdomínios como google.com e vox.com. Os proprietários desses domínios de segundo nível, por sua vez, podem criar subdomínios como mail.google.com e maps.google.com.

Como os sites populares usam nomes de domínio para se identificarem ao público, a segurança do DNS tornou-se uma preocupação crescente. Criminosos e espiões do governo tentaram comprometer o DNS para se passar por sites populares como facebook.com e gmail.com e interceptar suas comunicações privadas. Um padrão chamado [DNSSEC](https://pt.wikipedia.org/wiki/DNSSEC) busca reforçar a segurança do DNS com criptografia, mas poucas pessoas o adotaram.