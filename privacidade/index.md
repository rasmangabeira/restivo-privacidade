---
layout: default
title: Política de Privacidade do Restivo
---

# Política de Privacidade do Restivo

**Versão:** 2 · **Vigente desde:** 20 de novembro de 2026 · Versão anterior: 1, de 13 de novembro de 2026

## 1. Quem somos

O Restivo é um app de bem-estar e desempenho que reúne dados dos seus relógios e apps de saúde e mostra a sua evolução comparada só com você mesmo.

O controlador dos seus dados pessoais é Ricardo Mangabeira, pessoa física.

Para qualquer assunto de privacidade, escreva para [privacidade@jamit.digital](mailto:privacidade@jamit.digital). O encarregado pelo tratamento de dados pessoais é Ricardo Mangabeira, no mesmo e-mail.

O Restivo não é um dispositivo médico e não faz diagnóstico. O que ele mostra serve para acompanhar a sua rotina e não substitui orientação profissional.

## 2. Quais dados tratamos

**Conta**
- E-mail e senha ou chave de acesso (passkey), usados só para entrar. A senha fica no nosso servidor de login e nunca é vista pelo app.

**Perfil**, preenchido por você:
- nome;
- data de nascimento;
- sexo;
- altura e peso;
- objetivos, rotina, equipamentos e lesões;
- fuso horário do aparelho.

**Dados de saúde**, lidos do Apple Saúde (iPhone) ou do Health Connect (Android), só nas categorias que você liga:

| Categoria | O que inclui |
|---|---|
| Frequência cardíaca | frequência cardíaca, frequência cardíaca de repouso, variabilidade da frequência cardíaca |
| Sono | sessões de sono e suas fases (na cama, dormindo, acordado, leve, profundo, REM) |
| Sinais vitais | oxigenação do sangue, frequência respiratória, temperatura do pulso, da pele e do corpo |
| Atividade | passos, treinos, calorias ativas, VO₂máx e os treinos de força que você registra no app |
| Corpo | peso |

Junto de cada dado guardamos a origem: o app ou o aparelho que o registrou (por exemplo, o relógio). Assim você sabe de onde veio cada número.

**Dados técnicos:** data e hora das sincronizações e registros de erro. Os registros de erro não contêm dados de saúde.

**Refeições**, só se você ligar a categoria Nutrição (detalhes na seção "Registro de refeições e inteligência artificial", abaixo):
- refeições, itens, quantidades, água e alimentos que você cadastra.

Não coletamos localização, contatos nem dados de outros apps além dos citados. O Restivo não armazena fotos: a foto de uma refeição, quando você usa esse recurso, é enviada ao provedor de IA só para identificar os alimentos e é descartada em seguida.

## 3. Para que usamos

- Mostrar os seus dados e a sua evolução no app.
- Calcular indicadores próprios (como prontidão, carga e sono) comparando você com o seu próprio histórico.
- Gerar recomendações de treino e descanso para você.
- Registrar as suas refeições e a água, e comparar os totais com as suas metas, se você ligar a categoria Nutrição.
- Identificar os alimentos de uma foto ou de um texto, se você ligar a categoria de IA externa.
- Escolher, quando dois aparelhos registram a mesma coisa, qual fonte vale, conforme a prioridade que você define.
- Manter a sua conta funcionando e segura.

Não vendemos os seus dados, não os usamos para publicidade e não os compartilhamos com terceiros para fins próprios deles.

## 4. Base legal

- **Dados de saúde:** o seu consentimento específico e destacado, por categoria (LGPD, art. 11, I). Cada categoria é ligada separadamente, e o app registra a data e a versão do texto que você aceitou.
- **Conta e perfil:** a execução do serviço que você contratou ao criar a conta (art. 7º, V).
- **Registros técnicos e de segurança:** o nosso legítimo interesse em manter o serviço seguro e funcionando (art. 7º, IX).

- **Nutrição e IA externa:** também o seu consentimento específico, cada uma separada (`nutricao` e `ia_externa`). O envio de foto ou texto de refeição ao provedor de IA fora do Brasil se apoia no consentimento `ia_externa` (art. 33, VIII), com a informação prévia de que os dados vão para os Estados Unidos.

Recusar uma categoria não impede o uso do app: só aquela parte fica sem dados. Recusar a IA externa mantém a busca de alimentos e o código de barras.

## 5. Onde os dados ficam e com quem são compartilhados

- **No seu aparelho:** uma cópia local, na área privada do app, para uso sem internet. Ela fica fora do backup do aparelho e é apagada quando você desinstala o app. As credenciais de acesso ficam no armazenamento seguro do sistema (Keychain no iPhone, Keystore no Android).
- **Nos nossos servidores:** na Oracle Cloud, região de São Paulo (Brasil), que atua como operadora de hospedagem. O servidor de login também roda nessa mesma infraestrutura.
- **Na rede:** o tráfego entre o app e os servidores passa pela Cloudflare, que oferece proteção e entrega de rede e pode processar a conexão fora do Brasil. Esse tráfego é criptografado (HTTPS). Essa transferência internacional se apoia no seu consentimento e nas garantias contratuais do fornecedor (art. 33).
- **Anthropic (Estados Unidos), provedor de IA:** se você ligar `ia_externa`, recebe a foto da refeição ou o texto que a descreve, e nada mais: nem nome, e-mail, identificadores ou outros dados de saúde. Os dados enviados pela API não são usados para treinar modelos. Esse envio é uma transferência internacional, apoiada no seu consentimento específico e em destaque (art. 33, VIII).
- **Open Food Facts:** ao ler um código de barras, o servidor consulta esse banco aberto de produtos, enviando só o número do código, que não é dado pessoal. Por isso essa consulta não entra na base de transferência internacional acima.
- **Apple e Google:** o Restivo lê os dados do Apple Saúde e do Health Connect no seu aparelho e não envia nada de volta a eles.

Não compartilhamos dados com mais ninguém, salvo quando a lei ou uma ordem judicial exigir.

## 6. Por quanto tempo guardamos

- **Enquanto a conta existir:** os dados das categorias ligadas.
- **Ao desligar uma categoria:** o app pergunta se você quer apagar o que já foi enviado.
  - Se escolher apagar, os dados daquela categoria saem do servidor e do aparelho na hora.
  - Se escolher manter, o que já foi enviado continua guardado, mas nada novo é lido daquela categoria.
- **Ao excluir a conta:** todos os seus dados são apagados do servidor em até 30 dias. Isso inclui o perfil, os dados de saúde, as refeições, a água e os alimentos que você cadastrou, o histórico de consentimentos e a conta de login (e-mail). Se você usa o mesmo login em outro serviço nosso, só o acesso ao Restivo é removido.
- **Fotos de refeição:** não são guardadas pelo Restivo; passam pela memória do servidor e são descartadas após a análise.
- **Cópias de segurança:** são diárias e guardadas por 14 dias. Um dado apagado pode continuar nessas cópias até elas expirarem, sem uso, e depois desaparece.

## 7. Seus direitos

Você pode, a qualquer momento (art. 18):

- **Ver e levar os seus dados:** Conta → Exportar meus dados gera um arquivo (zip com planilhas CSV) com tudo o que guardamos sobre você, inclusive `refeicoes.csv`, `itens_refeicao.csv`, `agua.csv` e `alimentos_proprios.csv`.
- **Corrigir:** Conta → Editar perfil.
- **Revogar o consentimento:** Conta → Dados que o Restivo lê, categoria por categoria, com a opção de apagar o que já foi enviado.
- **Excluir a conta e os dados:** Conta → Excluir conta.
- **Pedir informações:** sobre o tratamento e o compartilhamento, ou fazer qualquer outro pedido, pelo e-mail da seção 1.

Respondemos em até 15 dias. Você também pode reclamar à Autoridade Nacional de Proteção de Dados (ANPD).

## 8. Segurança

- Conexões criptografadas.
- Login com renovação de credenciais.
- Desbloqueio por biometria opcional no app.
- Acesso aos servidores restrito.
- Registros de sistema sem dados de saúde.

Se acontecer um incidente de segurança que possa trazer risco a você, avisamos você e a ANPD, como a lei exige.

## 9. Idade

O Restivo é para pessoas com 18 anos ou mais.

## 10. Mudanças nesta política

- Quando mudarmos esta política, a data e a versão no topo mudam.
- Se a mudança afetar o que é feito com os dados de uma categoria, o app mostra o texto novo e pede o seu aceite de novo antes de continuar lendo aquela categoria.

## 11. Registro de refeições e inteligência artificial

O Restivo pode registrar o que você come e bebe. Essa parte é opcional e tem duas permissões separadas, que você liga e desliga quando quiser em Conta → Dados que o Restivo lê.

**O que guardamos (categoria `nutricao`)**
- as suas refeições: data, hora e tipo (café da manhã, almoço etc.);
- os itens de cada refeição e as quantidades, em gramas;
- a água que você registra;
- os alimentos que você mesmo cadastra, com os valores nutricionais que você informar.

**Inteligência artificial (categoria `ia_externa`)**
- Você pode fotografar a refeição ou descrevê-la em texto para o app sugerir os itens e as quantidades. As quantidades são estimativas, e você confere e corrige antes de salvar.
- **O que vai para o provedor de IA:** só a foto da refeição ou o texto que descreve a refeição. O provedor é a Anthropic (Estados Unidos).
- **O que nunca vai:** o seu nome, e-mail, qualquer identificador seu, datas ou outros dados de saúde.
- **A foto não é guardada pelo Restivo:** ela passa pela memória do servidor, é enviada para a análise e descartada. No seu aparelho, ela é reduzida e limpa de informações como a localização antes de sair.
- **Sem treino de modelos:** os dados enviados pela API da Anthropic não são usados para treinar modelos.
- Essa transferência para fora do Brasil (Estados Unidos) se apoia no seu consentimento específico e em destaque para a transferência (LGPD, art. 33, VIII), dado na categoria `ia_externa`, com a informação prévia de que os dados vão para os Estados Unidos, que é separada da `nutricao`.
- Recusar ou desligar `ia_externa` não tira nada do app: você continua registrando refeições pela busca de alimentos e pelo código de barras.

**Código de barras**
- Ao ler o código de barras de um produto, o servidor consulta o Open Food Facts, um banco aberto de produtos. Vai só o número do código de barras, sem nenhuma informação sobre você.

**Por quanto tempo e como apagar**
- Os dados de nutrição ficam enquanto a conta existir.
- Ao desligar `nutricao`, o app pergunta se você quer apagar o que já foi enviado. Se escolher apagar, as refeições, os itens, a água e os alimentos que você cadastrou saem do servidor e do aparelho. Desligar `ia_externa` só impede novos envios para a IA.
- Em Conta → Exportar meus dados, o arquivo passa a incluir quatro planilhas novas: `refeicoes.csv`, `itens_refeicao.csv`, `agua.csv` e `alimentos_proprios.csv`.
- Ao excluir a conta, tudo isso é apagado junto, no mesmo prazo da seção 6.
- O Restivo mostra as suas metas e totais de calorias, proteínas, carboidratos, gorduras e água como acompanhamento da rotina, comparando com as suas próprias metas ("abaixo" ou "acima da sua meta"). Não é orientação nutricional nem substitui um profissional.
