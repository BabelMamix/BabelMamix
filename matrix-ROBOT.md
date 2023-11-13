# Matrix.org Website

To discuss maintenance of this site, please come talk to the team in [#matrix.org-website:matrix.org](https://matrix.to/#/#matrix.org-website:matrix.org).

### How to build

0. Make sure you have the prerequisites:
   - Node.js and npm
   - `git clone https://github.com/matrix-org/matrix.org && cd matrix.org`
1. `cd gatsby`
2. Run `npm i` to install dependencies
3. `npm run develop` - It will take a while on your first build

Now you can visit the page you want to work on in the browser. For example: http://127.0.0.1:8000/docs/projects/try-matrix-now/

### How to add your project to Try Matrix Now

0. Prerequisites:
   - Text editor or web IDE ([MDX](https://mdxjs.com/) support is nice to have
     but not necessary)
   - `git clone https://github.com/matrix-org/matrix.org && cd matrix.org`
1. `cd gatsby`
1. `cp project-template.mdx content/projects/{bots|bridges|clients|iot|sdks|servers|other}/project-name.mdx`
1. Edit the file to include information about your project
1. To include images in your posting, add them to `gatsby/static/docs/projects/images/`. Avoid linking to images on other websites.
1. To check how the rendered result looks (strongly recommended), follow "How to build" steps.
1. Once it looks good, submit a pull request!



"@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 100;
  src: local('Roboto Thin Italic'), local('Roboto-ThinItalic'), url(s/roboto/v19/KFOiCnqEu92Fr1Mu51QrIzc.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 300;
  src: local('Roboto Light Italic'), local('Roboto-LightItalic'), url(s/roboto/v19/KFOjCnqEu92Fr1Mu51TjARc9.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 400;
  src: local('Roboto Italic'), local('Roboto-Italic'), url(s/roboto/v19/KFOkCnqEu92Fr1Mu52xP.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 500;
  src: local('Roboto Medium Italic'), local('Roboto-MediumItalic'), url(s/roboto/v19/KFOjCnqEu92Fr1Mu51S7ABc9.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 700;
  src: local('Roboto Bold Italic'), local('Roboto-BoldItalic'), url(s/roboto/v19/KFOjCnqEu92Fr1Mu51TzBhc9.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 900;
  src: local('Roboto Black Italic'), local('Roboto-BlackItalic'), url(s/roboto/v19/KFOjCnqEu92Fr1Mu51TLBBc9.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 100;
  src: local('Roboto Thin'), local('Roboto-Thin'), url(s/roboto/v19/KFOkCnqEu92Fr1MmgWxP.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 300;
  src: local('Roboto Light'), local('Roboto-Light'), url(s/roboto/v19/KFOlCnqEu92Fr1MmSU5vAw.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 400;
  src: local('Roboto'), local('Roboto-Regular'), url(s/roboto/v19/KFOmCnqEu92Fr1Me5Q.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  src: local('Roboto Medium'), local('Roboto-Medium'), url(s/roboto/v19/KFOlCnqEu92Fr1MmEU9vAw.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 700;
  src: local('Roboto Bold'), local('Roboto-Bold'), url(s/roboto/v19/KFOlCnqEu92Fr1MmWUlvAw.ttf) format('truetype');
}
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 900;
  src: local('Roboto Black'), local('Roboto-Black'), url(s/roboto/v19/KFOlCnqEu92Fr1MmYUtvAw.ttf) format('truetype');
}"
 https://raw.githubusercontent.com/matrix-org/matrix.org/abe85472e21790db69cd8078689d8b801ccb2226/content/Roboto.css#:~:text=%40font%2Dface%20%7B%0A%20%20font%2Dfamily,KFOlCnqEu92Fr1MmYUtvAw.ttf)%20format(%27truetype%27)%3B%0A%7D
