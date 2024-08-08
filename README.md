# Como Identificar se o hCaptcha é Enterprise Usando a Extensão CapSolver

![](https://assets.capsolver.com/prod/images/post/2024-06-03/995f8bf5-3b94-47a7-bc8c-bcb1fb918538.jpeg)


### Introdução

No cenário da internet de hoje, o CAPTCHA (Teste de Turing Público Completamente Automatizado para Diferenciar Computadores de Humanos) é uma ferramenta crucial para proteger sites contra ataques automatizados. O hCaptcha é uma solução CAPTCHA amplamente utilizada que oferece diferentes níveis de segurança, incluindo uma versão básica gratuita e uma versão empresarial mais avançada. Identificar se um site está usando o hCaptcha Enterprise pode ser importante para entender o nível de segurança e personalização que ele emprega. Este guia irá orientá-lo no processo de determinar se um site usa o hCaptcha Enterprise usando a extensão CapSolver.

### Diferenças Entre hCaptcha Normal e hCaptcha Enterprise

- **hCaptcha Normal**
  **Recursos**:
  - Proporciona proteção básica utilizando desafios que exigem que os usuários resolvam tarefas como reconhecimento de imagens ou quebra-cabeças baseados em texto.
  - Gratuito para uso com um modelo de compartilhamento de receita para proprietários de sites.

- **hCaptcha Enterprise**
  **Recursos**:
  - Modelos avançados de aprendizado de máquina para detectar comportamentos abusivos com maior precisão.
  - Políticas de segurança personalizáveis e tipos de desafios para atender às necessidades específicas.
  - Capacidades detalhadas de análise e relatórios.
  - Acesso à API para integração e controle mais profundos.

### Como Identificar se o hCaptcha é Enterprise Usando a Extensão CapSolver

Além de encontrar a chave do site do hCaptcha, às vezes é necessário determinar se o hCaptcha é Enterprise.

#### Passos para Iniciar a Detecção de Parâmetros do hCaptcha:

1. **Instalação**:
   - Instale a extensão [Captcha Solver Auto Solve](https://chrome.google.com/webstore/detail/captcha-solver-auto-bypas/pgojnojmmhpofjgdmaebadhbocahppod) no seu navegador Chrome.
   - Para usuários do Firefox, instale a extensão [Captcha Solver Auto Solve](https://addons.mozilla.org/en-US/firefox/addon/capsolver-captcha-solver/).

2. **Configuração do CapSolver**:
   - Visite [CapSolver](https://www.capsolver.com/).
   - Pressione a tecla "F12" no seu teclado para abrir as ferramentas de desenvolvedor.
   - Navegue até a aba rotulada **Capsolver Captcha Detector**.
     ![](https://assets.capsolver.com/prod/images/post/2023-10-31/2115f05d-a7eb-40b6-9693-53baa45d39a9.png)

3. **Detecção**:
   - Sem fechar o painel do CapSolver, visite o site onde você pretende acionar o CAPTCHA.
   - Acione o captcha.
   - Lembre-se: **Não feche** o painel do CapSolver antes de acionar o CAPTCHA.

### Detecção de Parâmetros do CAPTCHA:

#### Parâmetros Identificáveis para hCaptcha:
- URL do site
- Chave do site
- Enterprise
- Rqdata necessário

Uma vez que os parâmetros do CAPTCHA tenham sido detectados, o CapSolver retornará um JSON detalhando como você deve enviar os parâmetros do captcha para o serviço deles.
![](https://assets.capsolver.com/prod/images/post/2024-06-03/ac905c03-0ce3-4c81-ad68-681522405f3b.png)

### Como Identificar se o hCaptcha é Enterprise:

1. **Abrir Ferramentas de Desenvolvedor**:
   Pressione `F12` para abrir as ferramentas de desenvolvedor ou clique com o botão direito na página da web e selecione "Inspecionar".
 
2. **Abrir o Painel do CapSolver**:
   Vá para o Painel do Detector de Captcha.

3. **Acionar o hCaptcha**:
   Realize a ação que aciona o hCaptcha na página da web.

4. **Verificar o Painel do CapSolver**:
   Olhe para a aba CapSolver Captcha Detector nas ferramentas de desenvolvedor. Se o parâmetro `Enterprise` estiver definido como `true`, então o hCaptcha no site é Enterprise.
   Se for o hCaptcha Enterprise, aparecerá assim:
![](https://assets.capsolver.com/prod/images/post/2024-06-03/86c02d82-3db3-4309-9305-e42fbf3eb550.png)

Seguindo esses passos, você pode facilmente determinar se o hCaptcha em um site é enterprise.

### Dicas Adicionais e Melhores Práticas

- **Atualizações Regulares**: Certifique-se de que sua extensão CapSolver esteja sempre atualizada para a versão mais recente para se beneficiar dos novos recursos e correções de bugs.
- **Uso Ético**: Sempre use essas ferramentas de forma responsável e ética, respeitando os termos de serviço dos sites com os quais você interage.
- **Suporte**: Para mais assistência, você pode contatar o CapSolver via e-mail em [support@capsolver.com](mailto:support@capsolver.com).

### Conclusão

Identificar se um hCaptcha é Enterprise usando a extensão CapSolver é simples. O CapSolver não só ajuda a encontrar a chave do site, mas também outros parâmetros essenciais, como `isEnterprise`. Compreender essas diferenças pode ajudá-lo a avaliar melhor as medidas de segurança de um site e garantir que suas interações com os sistemas CAPTCHA sejam o mais eficientes possível.
