
# Webpacks & Loaders
## A short intro to React

# Babel e Webpack: 
## para converter novas funcionalidades em JS puro para qualquer navegador

+ `@Babel/core` 
+ `@Babel/preset-env` para alterar as funcionalidades do JS que o navegador nativamente não entende, como import/export
+ `@Babel/preset-react` para fazer com que o Browser entenda funcionalidades do React, ex: JSX
+ `webpack` 
+ `webpack-cli`
+ `webpack-dev-server` para reiniciar o servidor quando tiver alterações no código

# Loaders : 
## para o webpack entender como manipular tipos diferentes de arquivos
+ `Babel-loader` para carregar o babel padrão
+ `style-loader` para loader de estilização css
+ `css-loader` para carregar importações e funcões internas do CSS
+ `file-loader` para arquivos como imagens e etc

# React :
## Dependências do próprio react
+ `react` para usar a lib React
+ `react-dom` (do facebook), para permitir que o react manipule elementos da DOM
+ `prop-types` para validar os tipos das propriedades passadas aos elementos