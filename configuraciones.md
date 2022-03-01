# Configuraciones Iniciales

Creando el nombre de usuario: <br>
`git config --global user.name "angel"`

Creando el Email: <br>
`git config --global user.email "johnangelmx@gmail.com" `

Confirmando u modificando informacion:<br>
`git config --global -e`

Para poder cambiar el nombre de la rama principal es de la siguiente manera <br>
`git config --global init.defaultBranch main`

# Alias en Git

Una forma de visualizar de mejor manera los comandos permitiendo la utilidad de ver la informacion
<br> Ejemplos Recomdables<br>
git status:<br>
`git config --global alias.s "status -sb"`
<br> git log: <br>
`git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"`
