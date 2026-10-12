# Química em Movimento

Aplicativo educativo de química de Paulo Vicente Rocha Pinto. Reúne reações ilustradas, laboratório virtual, cálculos explicados e desafios para conectar química e desenvolvimento de sistemas.

## Abrir localmente

Abra `index.html` em um navegador moderno. O conteúdo e as interações estão no próprio arquivo; não é necessário instalar bibliotecas.

Para testar a instalação e o cache offline, use um servidor local em vez de abrir o arquivo diretamente:

```sh
python -m http.server 8080
```

Depois acesse `http://localhost:8080`.

## Publicar no GitHub Pages

1. Crie um repositório chamado `quimica-em-movimento`.
2. Envie todos os arquivos desta pasta para a raiz da branch `main`.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/(root)`, e salve.
5. Aguarde o GitHub Pages concluir a publicação. A URL aparecerá nessa tela.

O app não usa bibliotecas remotas, conta de usuário, rastreadores nem serviços externos. O progresso fica salvo no navegador deste dispositivo e pode ser exportado/importado na seção **Sobre o projeto**.

## O que inclui

- Cinco reações ilustradas com equações balanceadas e explicações, incluindo esterificação de Fischer.
- Laboratório virtual com três combinações conhecidas.
- Cálculos de diluição, concentração molar e estequiometria.
- Nove desafios com dicas e resolução comentada.
- Trilhas de estudo, progresso local e preferências de animação.
- Manifesto e service worker para instalação e cache offline após o primeiro acesso por HTTPS.

As simulações são qualitativas e educativas; não substituem procedimentos de laboratório ou orientação técnica.
