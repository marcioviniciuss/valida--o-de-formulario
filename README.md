
# Projeto de Validação de Formulário com Captura de Imagem

Este projeto faz parte de um curso da Alura e foi desenvolvido com o objetivo de implementar a validação de formulário e a captura de imagem do usuário. O layout foi fornecido com HTML e CSS prontos, e a funcionalidade foi implementada usando JavaScript.

## Funcionalidades Implementadas

### Validação de Campos
- **Campos Obrigatórios**: Verifica se os campos obrigatórios são preenchidos.
- **Formato de E-mail**: Verifica se o e-mail é válido.
- **Validação de CPF**: Verifica se o CPF inserido é válido e existe.
- **Validação de RG**: Verifica se o RG está no formato correto.
- **Validação de Idade**: Verifica se a data de nascimento indica que o usuário tem mais de 18 anos.
- **Aceitação dos Termos**: Verifica se o usuário aceitou os termos antes de enviar o formulário.

### Captura de Imagem
- O projeto permite ao usuário tirar uma foto usando a câmera do dispositivo.
- A foto é capturada através de um botão e armazenada como uma URL de imagem base64.
- A imagem capturada é armazenada junto com as outras informações do formulário na `localStorage`.

### Fluxo de Cadastro
1. **Preenchimento do Formulário**: O usuário preenche os campos obrigatórios do formulário (nome, e-mail, CPF, RG, data de nascimento).
2. **Validação Automática**: O formulário realiza a validação dos campos ao perder o foco (`blur`) e ao tentar enviar.
3. **Captura de Imagem**: O usuário é convidado a tirar uma foto usando a câmera do dispositivo.
4. **Armazenamento Local**: As informações preenchidas no formulário, junto com a imagem capturada, são armazenadas no `localStorage`.
5. **Redirecionamento**: Após a validação e captura da imagem, o usuário é redirecionado para outra página do formulário.

## Tecnologias Utilizadas

- **HTML**: Estrutura do formulário.
- **CSS**: Estilos fornecidos no projeto base.
- **JavaScript**: Validação de formulário, manipulação de eventos e captura de imagem da câmera.

### PROJETO DISPONIVEL NA VERCEL

## Imagem do Projeto
![monibank](https://github.com/user-attachments/assets/9146704a-be04-465a-93df-92ca51caaf44)
