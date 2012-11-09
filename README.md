Woese-api
=========

Exchange about Woese API

## Themes
We want to determining a best DSL of Woese Theme
We believe thats good:

Version pt-BR:

 <html>
<head>
    <title><woese:titulo /></title>
</head>		
<body>
    <section>

        <header>
            <h1> <ws:titulo /> </h1>
        </header>

        <aside>
            <ws:menu />
        </aside>

        <div class="conteudo">
            <div class="topo">

                <ws:destaque>
                    <ws:superior>
                        <div class="destaque superior" style="background-image: $imagem_url">
                            <ws:link>
                                <ws:titulo maximo="30">
                            </ws:link>
                        </div>
                    </ws:superior>
                </ws:destaque>

                <ws:destaque>
                    <ws:inferior>
                        <div class="destaque inferior">
                            <ws:link>
                                <ws:imagem>
                                <ws:titulo maximo="60">
                                <ws:texto maximo="120">
                            </ws:link>
                        </div>
                    </ws:inferior>
                </ws:destaque>

            </div>
        </div>

        <footer>
            <ws:rodape />
        </footer>
                        
    <section>
</body>
</html>