# Internet Explained

## Links Úteis e Bibliografia Utilizada

- [The internet, explained - Vox](https://www.vox.com/2014/6/16/18076282/the-internet)

- [O que é TCP/IP? - Tecmundo](https://www.tecmundo.com.br/o-que-e/780-o-que-e-tcp-ip-.htm)

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

