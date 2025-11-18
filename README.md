# IMPRESSRD-
Programa Java que usa JNA para acessar funções de uma DLL de impressoras Elgin. Permite configurar e abrir conexão, imprimir texto, QR Code, código de barras, XML SAT e cancelamento, além de acionar gaveta e sinal sonoro. Possui menu interativo para executar cada função.


📌 Sobre o Projeto

Este repositório demonstra como integrar Java com impressoras Elgin, utilizando a biblioteca JNA para acessar funções diretamente da DLL E1_Impressora01.dll.
Ele funciona como um painel de testes profissional, permitindo imprimir textos, QR Codes, códigos de barras, XMLs SAT, abrir gaveta, controlar beeps e muito mais — tudo via terminal, usando apenas números.

Ideal tanto para iniciantes quanto para integrações reais em sistemas comerciais.

✨ Funcionalidades
🖨️ Impressão

Texto

QR Code

Código de barras

XML SAT

XML de cancelamento

Corte automático de papel

🔌 Comunicação

Configuração completa de conexão

Abertura e fechamento de porta

Suporte a parâmetros personalizados

💵 Parte Física

Abertura de gaveta

Abertura com parâmetros customizados

Emissão de bip/sinal sonoro

🚀 Primeiros Passos
📦 1. Baixar e Extrair

Você receberá o arquivo:

impressaord.zip


Para extrair:
➡ Botão direito → Extrair aqui / Extrair tudo / Extract
Uma pasta chamada impressaord/ será criada com a estrutura completa.

💡 2. Abrindo no IntelliJ IDEA

Abra o IntelliJ

Clique em Open (Abrir)

Navegue até a pasta extraída

Selecione:

impressaord/
 └── Java-Aluno Graduacao/
      └── Java-Aluno Graduacao/   ← SELECIONAR ESTA PASTA


O IntelliJ irá carregar tudo automaticamente.

▶️ 3. Executando

Abra Main.java

Clique no botão verde ▶ ao lado do main

Certifique-se de que a DLL E1_Impressora01.dll está no caminho configurado dentro do código

🧭 Menu do Programa

Após iniciar, o menu aparece no console.
Digite o número correspondente à ação desejada:

Opção	Função
1	🔧 Configurar impressora
2	🔗 Abrir conexão
3	📝 Imprimir texto
4	📱 Imprimir QR Code
5	🏷️ Imprimir código de barras
6	🧾 Imprimir XML SAT
7	❌ Imprimir XML de cancelamento
8	💵 Abrir gaveta padrão
9	🛠️ Abrir gaveta customizada
10	🔊 Emitir beep
0	🔒 Fechar conexão e encerrar

Retorno 0 = Sucesso
Qualquer outro valor indica erro retornado pela DLL.

🗂️ Estrutura Simplificada
impressaord/
 ├── Java-Aluno Graduacao/
 │    ├── src/
 │    │    ├── Main.java
 │    │    ├── PrinterLib.java
 │    │    └── ...
 │    └── lib/
 │         └── E1_Impressora01.dll
 └── README.md

 
❤️ Conclusão

Este projeto oferece um ambiente completo para testes e integração com impressoras Elgin utilizando Java, servindo tanto como ferramenta didática quanto recurso profissional.

Se quiser, posso adicion
