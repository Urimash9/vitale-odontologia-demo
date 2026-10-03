# AVERO STUDIO — VITALE ODONTOLOGIA
## BUILD 01 — ADAPTAÇÃO ESTRUTURAL + IDENTIDADE PRÓPRIA

REPOSITÓRIO DE DESTINO:
`Urimash9/vitale-odontologia-demo`

BRANCH DE TRABALHO:
`build-01-vitale`

ARQUIVO PRINCIPAL:
`vitale-homepage-build-01.html`

BASE DE REFERÊNCIA — SOMENTE LEITURA:
`Urimash9/pires-pena-odonto-demo`

COMMIT DE REFERÊNCIA DA PIRES PENA:
`2a7a63d7edfdd0f9b3b9b2ed8917b792a6ba30d9`

ARQUIVO DE REFERÊNCIA:
`pires-pena-homepage-v1-2.html`

---

## REGRA ABSOLUTA — PRESERVAÇÃO DA PIRES PENA

NÃO editar, reescrever, renomear, apagar, mover, fazer commit, criar branch de trabalho ou alterar qualquer asset dentro de `Urimash9/pires-pena-odonto-demo`.

A Pires Pena é uma referência permanente da biblioteca AVERO e deve continuar intacta para futuros projetos.

A Vitale é um projeto independente. Reaproveitar somente o que for tecnicamente útil da Pires Pena: arquitetura, lógica de responsividade, padrões maduros de UX, componentes ou comportamentos que façam sentido.

NÃO fazer clone visual literal.
NÃO transformar a Pires Pena em Vitale por simples troca de logo, cores e textos.
NÃO criar dependência entre os dois repositórios.
NÃO referenciar assets da Pires Pena via URL externa no produto final.

---

## OBJETIVO DA BUILD 01

Criar a primeira versão estrutural e visual da homepage da Vitale Odontologia, preservando a maturidade técnica da demo Pires Pena, porém reinterpretando completamente a linguagem visual para a identidade real da Vitale e para a presença central da Dra. Amanda Neves Barbosa.

A Build 01 deve funcionar como uma adaptação autoral, não como um template reciclado.

A Vitale deve comunicar três pilares principais:

1. PRECISÃO
2. NATURALIDADE
3. CUIDADO

O site deve equilibrar autoridade clínica e acolhimento.

Evitar dois extremos:
- luxo dourado genérico / ostentação;
- estética hospitalar fria, excessivamente técnica ou invasiva.

---

## CONTEXTO DE MARCA

Marca principal:
**Vitale Odontologia**

Profissional central / rosto da marca:
**Dra. Amanda Neves Barbosa**

Instagram principal identificado:
`@dra.amandanevesb`
`https://www.instagram.com/dra.amandanevesb`

WhatsApp principal exibido no Instagram:
`(34) 9301-6000`
`https://wa.me/553493016000`

Endereço:
`R. Rui Barbosa, 110A — Centro, Monte Carmelo-MG`

Google Maps fornecido:
`https://maps.app.goo.gl/zNRLqkj5iDmSAQs87`

Existe divergência histórica de telefone entre fontes públicas. Nesta build, usar como CTA principal o WhatsApp exibido pela própria Dra. Amanda no Instagram. Não publicar telefone alternativo sem nova validação.

---

## O QUE APROVEITAR DA PIRES PENA

Reaproveitar conceitualmente e/ou tecnicamente:

- shell / largura máxima da página;
- header sticky e navegação responsiva;
- lógica de âncoras;
- estrutura de Hero em duas zonas quando adequada;
- tratamento responsivo desktop/tablet/mobile;
- lógica de CTAs para WhatsApp;
- organização semântica das seções;
- padrões de acessibilidade já usados;
- comportamento de botões;
- boas práticas de `target="_blank"`, `rel="noopener noreferrer"` e labels;
- organização de tratamentos;
- estrutura base de prova social;
- estrutura base da seção de clínica;
- footer e hierarquia de contato;
- qualquer solução madura de UX que possa ser mantida sem carregar a personalidade da Pires Pena.

A Pires Pena possuía uma seção de dois profissionais e uma narrativa de dupla/equipe. Isso NÃO deve ser mantido como composição equivalente.

---

## O QUE NÃO LEVAR DA PIRES PENA

Remover/reinterpretar completamente:

- verde profundo / sálvia como identidade central;
- assinatura visual da Pires Pena;
- composição de dois profissionais;
- textos e tratamentos não confirmados para a Vitale;
- qualquer imagem da Pires Pena como asset definitivo;
- referências a Coromandel;
- depoimentos da Pires Pena;
- contatos da Pires Pena;
- logo / monograma da Pires Pena;
- animação final inspirada em aparelho/fio ortodôntico;
- linguagem manuscrita usada na Hero da Pires Pena;
- qualquer elemento que faça o resultado parecer uma variação cromática da mesma página.

A animação do fio ortodôntico, em especial, é uma assinatura específica da Pires Pena e NÃO deve aparecer na Vitale.

---

## DIREÇÃO VISUAL VITALE

A identidade observada na clínica e materiais da marca trabalha com:

- off-white quente;
- branco;
- champagne / dourado fosco;
- madeira clara / tons amadeirados quentes;
- iluminação indireta quente;
- vegetação como verde natural, não como cor dominante de interface;
- serifas elegantes;
- sensação de limpeza, organização e sofisticação leve.

Evitar dourado metálico excessivo.
Evitar gradientes chamativos.
Evitar black + gold de estética genérica de luxo.
Evitar excesso de sombras pesadas.
Evitar excesso de cards quadrados.

A sofisticação deve vir da composição, tipografia, espaço, fotografia, ritmo e detalhe.

---

## SISTEMA GRÁFICO AUTORAL

Extrair linguagem da arquitetura real da clínica:

1. Aros orgânicos da luminária da recepção.
2. Ripados verticais em madeira.
3. Iluminação indireta e linhas de luz.
4. Curva/diagonal iluminada do balcão da recepção.
5. Construção orgânica do “V” da marca Vitale.

Esses elementos podem originar:

- linhas finas champagne;
- arcos incompletos;
- elipses sobrepostas;
- recortes editoriais;
- divisores verticais discretos;
- pequenas transições de luz;
- microinterações suaves.

Não usar todos ao mesmo tempo.
A aplicação deve ser controlada e elegante.

---

## TIPOGRAFIA

Usar uma combinação editorial:

- Serif elegante para títulos e momentos institucionais.
- Sans limpa para navegação, corpo, dados e CTAs.

A Build 01 pode usar fontes seguras do sistema / Georgia + sans enquanto os assets e a tipografia oficial não forem confirmados.

Não inventar uma fonte como “oficial” da Vitale sem validação.

---

## ARQUITETURA DA HOME

### 01 — HEADER

Marca Vitale à esquerda.
Navegação curta.
CTA “Agendar avaliação”.
Header sticky com transparência/blur discreto.

Links sugeridos:
- Início
- Tratamentos
- Dra. Amanda
- Clínica
- Contato

Mobile:
- menu compacto;
- CTA não pode esmagar a marca;
- preservar leitura e toque confortável.

---

### 02 — HERO

OBJETIVO:
Apresentar a Vitale como marca e a Dra. Amanda como rosto/autoridade sem transformar o site em uma página pessoal.

Direção:
- composição editorial;
- bastante espaço negativo;
- retrato da Amanda como imagem principal quando o asset oficial entrar;
- marca Vitale institucionalmente dominante;
- elementos gráficos derivados dos aros / V usados de forma sutil.

Copy inicial sugerida:

Eyebrow:
`Vitale Odontologia · Monte Carmelo`

Headline de trabalho:
`Precisão para cuidar. Naturalidade para transformar.`

Texto de apoio:
`Odontologia conduzida com técnica, atenção individual e uma experiência pensada para acolher em cada etapa.`

CTAs:
- `Agendar pelo WhatsApp`
- `Conhecer tratamentos`

Não considerar a copy definitivamente aprovada; ela pode ser refinada sem perder o território verbal.

---

### 03 — PILARES / DIFERENCIAIS

Reaproveitar a função estrutural da faixa de diferenciais da Pires Pena, mas redesenhar visualmente para Vitale.

Pilares:
- Cuidado individual
- Precisão clínica
- Tecnologia aplicada
- Resultados naturais

Não usar ícones genéricos em excesso.
Preferir tipografia + pequenos sinais gráficos.

---

### 04 — POSICIONAMENTO / EXPERIÊNCIA VITALE

Objetivo:
Apresentar a clínica e seu modo de atender antes de entrar em procedimentos.

Território:
`Odontologia que une ciência, precisão e cuidado.`

Usar imagem real da clínica posteriormente.
Na Build 01, reservar corretamente proporções e composição.

Pontos:
- atendimento humanizado;
- ambiente contemporâneo e acolhedor;
- planejamento individualizado;
- Monte Carmelo-MG.

Não inventar números, anos de experiência ou certificações.

---

### 05 — TRATAMENTOS

Serviços identificados na comunicação pública:

- Endodontia
- Cirurgia
- Implantes
- Reabilitação Oral
- Estética Dental
- Sedação

Procedimentos estéticos faciais aparecem no Instagram, porém NÃO devem ganhar protagonismo na arquitetura principal sem validação posterior.

Redesenhar os cards da Pires Pena.
Não apenas trocar verde por dourado.

Direção sugerida:
- tratamento editorial;
- nomes grandes;
- numeração discreta;
- pouca borda;
- movimento suave em hover/touch;
- fotos clínicas podem entrar na Build 02.

---

### 06 — DRA. AMANDA NEVES BARBOSA

Substitui conceitualmente a seção “Nossos profissionais” da Pires Pena.

NÃO criar dois cards.
NÃO duplicar a mesma composição.
NÃO transformar Amanda em um card genérico.

Criar seção editorial própria:
- retrato dominante;
- nome completo;
- breve apresentação;
- áreas de atuação;
- link para Instagram;
- autoridade apresentada com sobriedade.

Território de texto:
`Conhecimento técnico com um olhar atento para cada pessoa.`

Não publicar CRO, especialidade formal ou títulos acadêmicos sem confirmação documental.

---

### 07 — SEÇÃO ASSINATURA
## “PRECISÃO EM CADA DETALHE”

Esta seção deve ser uma das assinaturas exclusivas da Vitale.

Imagem futura ideal:
Dra. Amanda trabalhando com microscópio durante atendimento.

Objetivo:
Mostrar tecnologia + habilidade + cuidado em uma única narrativa.

Copy de trabalho:
`Tecnologia a serviço de decisões mais seguras.`

Temas que podem ser abordados sem exagerar claims:
- Endodontia;
- diagnóstico;
- magnificação;
- planejamento;
- atualização profissional;
- atenção aos detalhes.

A comunicação da Amanda cita tomografia computadorizada e mostra uso de microscópio. Não afirmar que todo equipamento ou exame é necessariamente realizado dentro da Vitale sem confirmação.

Visual:
Pode usar fundo mais escuro/quente de forma pontual para criar contraste, mas evitar transformar todo o site em dark luxury.

---

### 08 — RESULTADOS / NATURALIDADE

Objetivo:
Conectar técnica a resultado sem transformar a homepage em galeria clínica agressiva.

Priorizar posteriormente:
- sorrisos;
- reabilitações visualmente agradáveis;
- antes/depois selecionados;
- estética natural.

Evitar na Home:
- imagens muito invasivas de canal aberto;
- sangue;
- procedimentos cirúrgicos em close;
- sequência técnica pesada.

Esses conteúdos podem existir futuramente em páginas educativas ou de tratamento.

Headline de trabalho:
`Resultados que respeitam cada sorriso.`

---

### 09 — EXPERIÊNCIA / CLÍNICA

Usar posteriormente o banco real já levantado:
- recepção;
- corredor;
- fachada;
- espelho iluminado;
- balcão;
- ripados;
- luminária;
- ambiente de espera;
- detalhes de vegetação e iluminação.

Headline:
`Um espaço pensado para acolher.`

Evitar grid imobiliário genérico.
Preferir composição editorial assimétrica.

No desktop:
uma imagem dominante + duas ou três imagens secundárias.

No mobile:
priorizar ritmo vertical e boa leitura; carrossel somente se realmente melhorar UX.

---

### 10 — PROVA SOCIAL

A Vitale possui reputação forte no Google.

Na Build 01:
- pode mostrar `5,0` se mantido como dado de trabalho;
- o número exato de avaliações deve ser revalidado antes da versão final;
- depoimentos reais devem ser coletados e validados antes da publicação.

NÃO usar depoimentos inventados.
NÃO reutilizar depoimentos da Pires Pena.

Direção:
prova social mais institucional que festiva.

---

### 11 — LOCALIZAÇÃO

Endereço:
`R. Rui Barbosa, 110A — Centro, Monte Carmelo-MG`

Maps:
`https://maps.app.goo.gl/zNRLqkj5iDmSAQs87`

A Build 01 pode reservar o módulo de mapa.
Integração definitiva pode ser refinada depois.

---

### 12 — CTA FINAL

Território sugerido:
`Seu cuidado pode começar aqui.`

CTA:
`Agendar pelo WhatsApp`

WhatsApp:
`https://wa.me/553493016000`

Não reutilizar a animação de aparelho da Pires Pena.
Se houver motion, criar algo derivado da própria Vitale: arco de luz / linha orgânica / anel suave.

Motion deve ser sutil e respeitar `prefers-reduced-motion`.

---

### 13 — FOOTER

Incluir:
- Vitale Odontologia;
- WhatsApp principal;
- endereço;
- Instagram da Dra. Amanda;
- links rápidos.

Não publicar telefone divergente.

---

## ASSETS — REGRA DA BUILD 01

A Build 01 NÃO depende do banco definitivo de imagens.

Usar placeholders neutros e semanticamente identificados onde necessário.

Não usar imagens da Pires Pena como se fossem da Vitale.

Não usar banco de imagens genérico como solução definitiva.

A próxima rodada será dedicada a assets reais:

**BUILD 02 — IMAGENS OFICIAIS / ASSETS REAIS**

Nessa etapa serão:
- escolhidos frames de vídeos do Instagram;
- tratados screenshots úteis;
- melhorada qualidade quando possível;
- organizados nomes de arquivo;
- definidos crops desktop/mobile;
- substituídos placeholders;
- refinado `object-position` individualmente.

---

## BANCO VISUAL JÁ IDENTIFICADO PARA A BUILD 02

Categorias:

1. INSTITUCIONAL
- retratos profissionais da Dra. Amanda;
- recepção;
- fachada;
- corredores;
- logo aplicado.

2. AUTORIDADE
- Dra. Amanda atuando com microscópio;
- cenas de atendimento;
- formação/aperfeiçoamento quando relevante.

3. RESULTADOS
- antes/depois de sorriso;
- reabilitações;
- estética dental natural.

4. TÉCNICO
- Endodontia em close;
- sequência de tratamento;
- tomografia / diagnóstico;
- instrumentação.

Imagens técnicas invasivas não devem dominar a Home.

---

## RESPONSIVIDADE

A qualidade mobile é obrigatória desde a Build 01.

Referência técnica:
a Pires Pena já possui decisões maduras de responsividade; reaproveitar o aprendizado, não a identidade.

Testar no mínimo:
- 360px;
- 390px;
- 430px;
- 768px;
- 1024px;
- 1366px;
- 1440px.

Garantir:
- nenhuma rolagem horizontal;
- headlines sem quebras ruins;
- botões sem esmagamento;
- fotos com crop coerente;
- cards sem altura excessiva;
- menu utilizável por toque;
- espaçamento vertical consistente;
- tipografia legível;
- CTA sempre claro.

---

## ACESSIBILIDADE E QUALIDADE

Manter:
- HTML semântico;
- contraste suficiente;
- `alt` em imagens reais;
- focus-visible;
- links com contexto;
- `aria-label` quando necessário;
- `prefers-reduced-motion` para animações;
- targets de toque adequados no mobile.

Evitar JavaScript desnecessário.

---

## PERFORMANCE

Nesta Build 01:
- evitar bibliotecas pesadas;
- preservar implementação estática simples se suficiente;
- imagens finais deverão ser otimizadas na Build 02;
- não criar dependências só para efeitos visuais simples;
- manter CSS e JS organizados o suficiente para refinamentos futuros.

---

## COPY E CLAIMS — REGRAS

Pode usar como território verbal:
- precisão;
- cuidado;
- naturalidade;
- atendimento humanizado;
- tecnologia aplicada;
- planejamento individualizado;
- atualização constante.

Não inventar:
- especializações formais;
- número de pacientes;
- anos de mercado;
- equipamentos próprios;
- garantias de resultado;
- títulos acadêmicos;
- CRO;
- números de avaliações sem validação final.

---

## CRITÉRIOS DE ACEITE DA BUILD 01

A Build 01 estará pronta para revisão quando:

1. Abrir corretamente na Vercel pela branch `build-01-vitale`.
2. Nenhum arquivo da Pires Pena tiver sido alterado.
3. A página não parecer uma recoloração da Pires Pena.
4. A Vitale estiver reconhecível pela linguagem off-white/champagne/madeira/luz.
5. Dra. Amanda tiver protagonismo individual, sem lógica de dupla.
6. Existir uma seção exclusiva “Precisão em cada detalhe”.
7. Tratamentos refletirem a atuação identificada da Vitale/Amanda.
8. A seção de clínica estiver preparada para o banco real de imagens.
9. Placeholders estiverem claramente identificados para a Build 02.
10. WhatsApp, Instagram, Maps e endereço apontarem para a Vitale.
11. Nenhum contato, review, nome ou link da Pires Pena permanecer visível.
12. O motion de aparelho/fio ortodôntico da Pires Pena não existir na Vitale.
13. Desktop e mobile estiverem visualmente coerentes.
14. Não houver overflow horizontal ou quebras graves.
15. O site transmitir simultaneamente autoridade técnica e acolhimento.

---

## ENTREGA

Ao finalizar:

- trabalhar SOMENTE na branch `build-01-vitale`;
- NÃO fazer merge na `main`;
- informar commit final;
- resumir arquivos alterados/criados;
- informar URL de preview da Vercel se disponível;
- registrar qualquer dado ainda pendente de validação;
- NÃO tocar no repositório da Pires Pena.

A Build 01 deve ser tratada como uma adaptação autoral da biblioteca AVERO: tecnologia reaproveitada, identidade reconstruída para o novo cliente.
