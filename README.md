<!DOCTYPE hmtl>
<html>
    <head>
        <title>forms</title>
        <body>

            <form action="/pagina-processa-dados-form" method="post">
                <fieldset>
                    <legend>DADOS GERAIS</legend>
                    <label for="nome">Nome:</label>
                    <input type="text" minlength="3" id="nome"/>

                    <label for="data_nascimento">Data de Nascimento</label>
                    <input type="text" id="data_nascimento"/>

                    <label for="cpf">Cpf</label>
                    <input type="text" minlength="11" id="cpf"/>
                </fieldset>
                <fieldset>
                    <legend>Endereço</legend>

                    <lable for="tipo_endereco">Tipo:</lable>
                    <select id="tipo_endereco">
                        <option valuer="">Selecione</option>
                        <option value="">Rua</option>
                        <option value="">Estrada</option>
                        <option value="">Rodovia</option>
                        <option value="">Outros</option>
                    </select>
                    <label for="logradouro_endereco">Logradouro</label>
                    <input type="text" id="Logradouro_endereco"/>

                    <label for="numero_endereco">Numero</label>
                    <input type="text" id="numero_endereco"/>

                    <label for="complemento_endereco">Complemento</label>
                    <input type="text" id="complemento_endereco"/>
                </fieldset>
                <fieldset>
                    <legend>FALE CONOSCO</legend>

                    <label for="msg">Messagem</label>
                    <textarea type="text" id="msg"></textarea>
                </fieldset>
                <fieldset>
                    <button type="submit">Enviar Menssagem</button>
                    <button type="limpar">limpar formario</button>
                </fieldset>
            </form>
        </body>
    </head>
