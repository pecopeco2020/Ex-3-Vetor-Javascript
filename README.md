# Ex-3-Vetor-Javascript
Escreva uma função que verifique se o vetor de habilidades passado possui a habilidade "Javascript" e retorna um booleano true/false caso exista ou não.

<html>
    <head>
    </head>
    <body>
        <script>
            function temHabilidade(skills){
                var n = skills.indexOf("Javascript");
                if(n >= 0){
                    console.log(true);
                }
                    else
                        console.log(false);
            }

            var skills = ["React", "Javascript", "React Native"];
            
            temHabilidade(skills);

            //ps: https://www.w3schools.com/jsref/jsref_indexof.asp link educacional para entender o conceito da ferramenta indexOf
            //usada nesse exercicio.
        </script>
    </body>
</html>
