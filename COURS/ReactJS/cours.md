# ReactJS  
Npm Install en local  
ça crée les modules dans le dossier node_modules et le dossier package.json

## Portée des variables

var username = "timmy"

La fonction
function myname(param){
    return "je m'appelle" + param
}

Param est une fonction utilisable uniquement dans la fonction

La fonction renvoie je m'appelle Timmy


## Import export  

export function myname(username){
    return "je m'appelle" + username
}
export function rename(username, new_name){...
}


import {myname from 'identity.js}
myname("groot")

dans l'import les {} vont chercher exactement le nom du fichier et pas celui par defaut

Plurasight
LEVEL UP TUTORIALS --> React for EveryOne

