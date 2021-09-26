# Life-Vuetify
Explanation how to get it running

#Installation
Installation of the alpha is limited to new cli projects at this time and intended primarily for testing. If you have any questions or run into issues, please reach out to our Discord community.

#vue-cli
In order for the installation to proceed correctly, vue-cli 5.0.0-beta is required. Further instructions are available at vue-cli.

Once installed, generate a project with the following command using the vue-cli 5.0.0-beta:

vue create my-app
When prompted, choose Vue 3 Preview:

? Please pick a preset:
    Default ([Vue 2] babel, eslint)
  > Default (Vue 3 Preview) ([Vue 3] babel, eslint)
    Manually select features
It is recommended to commit or stash your changes at this point, in case you need to rollback the changes.

Next, navigate to your project directory and add Vuetify to your project:

cd my-app
vue add vuetify
Once prompted, choose v3 (alpha):

? Choose a preset: (Use arrow keys)
  Default (recommended)
  Preview (Vuetify 3 + Vite)
  Prototype (rapid development)
> V3 (alpha)
  Configure (advanced)

npm install sass-1.33 

