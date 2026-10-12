# Química em Movimento

Aplicativo educativo de química de Paulo Vicente Rocha Pinto. Reações ilustradas, laboratório virtual, cálculos explicados e desafios para conectar química e desenvolvimento de sistemas.

## Abrir localmente

Abra `index.html` em um navegador moderno. O conteúdo e as interações estão no próprio arquivo; não é necessário instalar bibliotecas.

Para testar a instalação e o cache offline, use um servidor local em vez de abrir o arquivo diretamente:

```sh
python -m http.server 8080
```

Depois acesse `http://localhost:8080`.

## Publicar no GitHub Pages

1. Envie todos os arquivos desta pasta para a raiz da branch `main`.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/(root)`, e salve.
4. Aguarde a publicação. O GitHub mostrará o endereço do site nessa tela.

O app não usa bibliotecas remotas, contas de usuários, rastreadores nem serviços externos. O progresso fica salvo no navegador deste dispositivo e pode ser exportado ou importado na seção **Sobre o projeto**.

## Recursos

- Quatro reações ilustradas com equações balanceadas e explicações.
- Laboratório virtual com três combinações conhecidas.
- Cálculos de diluição, concentração molar e estequiometria.
- Oito desafios com dicas e resoluções comentadas.
- Trilhas de estudo, progresso local e preferência de animações.
- Manifesto e service worker para instalação e cache offline após o primeiro acesso por HTTPS.

As simulações são qualitativas e educativas; não substituem procedimentos de laboratório ou orientação técnica.
