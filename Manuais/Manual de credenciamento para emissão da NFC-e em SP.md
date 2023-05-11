## Manual de credenciamento para emissão da NFC-e em SP

📄 [Versão do manual em PDF](https://github.com/DinizSoft/Suporte/files/11452640/Manual.de.credenciamento.para.emissao.da.NFC-e.em.SP.pdf)

Para dar início ao processo de credenciamento da NFC-e, tanto em modo de homologação *(sem validade jurídica)*, quanto em modo de produção *(com validade jurídica)*, será necessário o certificado digital da empresa contribuinte.

Com o certificado digital já instalado, acesse o site do [Portal da NFC-e do estado de São Paulo](http://www.nfce.fazenda.sp.gov.br/NFCePortal/), em seguida clique no menu lateral **Credenciamento** > **com validade jurídica** *(produção)*:

*Obs.: Caso queira efetuar testes sem validade jurídica (homologação), opte pela opção **ambiente de testes**.*

![Tela I _ 2](https://user-images.githubusercontent.com/107438505/197561787-f6e1f742-7c0a-464d-b417-e75945103caa.png)


Clique na imagem do cartão, na sequencia será requisitado o *certificado digital* e a senha PIN caso o certificado seja modelo A3 *(cartão ou token)*.

![Tela II](https://user-images.githubusercontent.com/107438505/197561920-51db895a-436e-48d9-9198-361cf1ac5ca1.png)


Na tela do formulário de credenciamento, *selecione a empresa* e *preencha os dados do responsável pelo estabelecimento*, será o contato que a SEFAZ SP utilizará caso necessário. 

Na sequencia, clique no botão **Solicitar Credenciamento**.

*Obs.: é necessário que a empresa tenha no mínimo um equipamento SAT vinculado ao CNPJ, conforme podemos visualizar na coluna **SAT Ativo**.*

![Tela III](https://user-images.githubusercontent.com/107438505/197562361-8955f49d-14fb-4db9-aebd-bd5fc0580f80.png)


Pronto! A solicitação de credenciamento para NFC-e foi efetuada, agora será necessário gerar o **CSC (Código de Segurança do Contribuinte)** para começar a operar. 

Retorne para a tela inicial do [Portal da NFC-e do estado de São Paulo](http://www.nfce.fazenda.sp.gov.br/NFCePortal/) e clique em **Gerenciar Cód Segurança** > **com validade jurídica**, localizado no menu lateral.

![Tela IV](https://user-images.githubusercontent.com/107438505/197562425-af2705a3-fd0f-4b42-b134-468c5a9e550c.png)


Novamente aparecerá a tela com a imagem do cartão para que seja selecionado o certificado digital da empresa:

![Tela V](https://user-images.githubusercontent.com/107438505/197562514-5ea4acef-6faf-419d-9d42-a4af10314d36.png)


Você será encaminhado para a página de **Gerenciamento e Geração de CSC**. 

Para geração do CSC, clique no botão **Novo Cód Segurança**, o código gerado será mostrado na tabela acima. Esse código deverá ser inserido no sistema emissor de cupom fiscal.

*Obs.: Caso já tenha algum CSC cadastrado, ele aparecerá junto de seu ID Token e data de ativação. É possível também revogar credenciamentos já realizados*.

![Tela codigo de segurança II](https://user-images.githubusercontent.com/107438505/197574929-4955c86e-ec70-4f3c-b35b-da0f69535ee2.png)


Processo de credenciamento finalizado na secretaria da fazenda do estado de São Paulo! 

Agora abra o sistema emissor de NFC-e e realize as configurações necessárias para dar início as emissões.
