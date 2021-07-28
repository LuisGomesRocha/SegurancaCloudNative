# SegurancaCloudNative

<h4 align="center"> 
	🚧  Orange Talents  🚀 Em construção...  🚧
</h4>

<p align="center">🚀 Formulário de proposta de solução - Segurança em ambientes Cloud native 🚀 </p>


<h5 align="center">
    <a href="https://www.youtube.com/watch?v=Kzcz-EVKBEQ">🔗Docker em 22 minutos - teoria e prática (Rápido!)</a>
</h5>

<p align="justify"> :robot: Em meio às incertezas quanto à formação da Autoridade Nacional de Proteção de Dados (ANPD) e sobre a data de entrada em vigor da Lei Geral de Proteção de Dados (LGPD), uma coisa é certa: é mandatório todo desenvolvedor deve garantir a privacidade e a proteção dos dados pessoais e dos dados sensíveis que coletam, manipulam, processam e armazenam.  Além das penalidades administrativas e financeiras que as autoridades poderão impor, a empresa pode sofrer prejuízos mercadológicos, falta de credibilidade do mercado e degradação da imagem, entre outros danos.:robot: </p>

<p align="justify"> :robot: Dentro deste contexto é pertinente salientar que dados sensíveis podem ser expostos se forem registrados e não criptografados ou usados com chaves fracas em sua geração e gerenciamento, bem como algoritmos ou técnicas de hashing <a href="https://br.sensedia.com/post/top-10-security-risks-on-the-web-owasp-and-how-to-mitigate-them-with-api-management"> ruins</a>. :robot: </p>

<p align="justify"> :robot: Segundo <a href="http://repositorio.roca.utfpr.edu.br/jspui/bitstream/1/817/1/CT_JAVA_VII_2012_06.PDF"> Marques (2012)</a>, o ofuscamento de código é uma área específica do conhecimento que utiliza técnicas e ferramentas que visam atender às necessidades de proteção à propriedade intelectual presente no coração de qualquer aplicação.:robot: </p>

<p align="justify"> :robot: Sendo assim, alguns tópicos devem serem colocados em nítida necessidade de implementação: Segurança a dados sensíveis em logs da aplicação, autenticação e autorização de acesso, HTTPS e dados persistidos em <a href="HUNTER, Kirsten. Irresistible APIs: Designing web APIs that developers will love. Simon and Schuster, 2016."> banco </a>.:robot: </p>

### Segurança a dados sensíveis em logs da aplicação:

<p align="justify"> :robot: 
De forma geral é utilizado sistemas de logs de uma aplicação como uma ferramenta de encontrar problemas, normalmente indicando os passos ou informações que ajudem a direcionar a resolução desses problemas. Dentro deste contexto sempre que se faz necessário "logar" uma informação que seja passível de identificação de uma pessoa é necessário realizar o ofuscamento do dado. O ofuscamento é uma prática que "embaralha" os caracteres para proteger nossa informação de maneira que se a informação for analisada por qualquer fonte não seja possível identificar o dado.
:robot: </p>

### Autenticação e autorização de acesso: 

<p align="justify"> :robot: 
Uma das formas de se garantir a segurança da comunicação entre aplicações é o Spring Security, que possibilita uma autenticação forte e altamente personalizável e ainda estabelece uma estrutura de controle de acesso que é o padrão de facto para a proteção de aplicativos baseados na framework <a href="http://antigo.unipar.br/~seinpar/2013/artigos/Guilherme%20Baiestero%20Lopes.pdf">Spring </a>.
:robot: </p>

### HTTPS : 

<p align="justify"> :robot: 
Proteja as comunicações entre uma API REST  e um cliente HTTP ao ativar <a href="https://www.alura.com.br/artigos/qual-e-diferenca-entre-http-e-https">HTTPS</a>. É possível ativar HTTPS apenas para criptografia ou também configurar uma <a href="https://www.baeldung.com/spring-boot-https-self-signed-certificate"> API REST </a> para autenticação de cliente (autenticação mútua). Como as APIs REST sempre utilizam o listener HTTP do servidor de integração para o servidor de integração, deve-se configurar o listener HTTP servidor de integração.
:robot: </p>  

### Dados persistidos no banco:

<p align="justify"> :robot: 
A criptografia é uma técnica que pode ser utilizada para manter as informações dos bancos de dados em sigilo, protegidas. Por meio dela, é possível evitar que pessoas não autorizadas tenham acesso aos dados armazenados, pois somente aqueles que possuem a devida chave de criptografia serão capazes de <a href="https://www.devmedia.com.br/introducao-a-criptografia-no-mysql/37179">visualizá-los</a>.
:robot: </p>  







