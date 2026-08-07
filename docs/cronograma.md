<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Cronograma do Evento</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            font-family: "Merriweather Sans", "Fira Sans" !important, sans-serif, Arial, Helvetica;
            font-size: 14px;
        }
        th, td {
            border: 0.5px solid #ccc;
            padding: 12px;
            text-align: center !important;
            vertical-align: middle !important;
        }
        /* Cabeçalho das Datas */
        .header-24 { background-color: #a0c4df !important; color: #000 !important; font-weight: bold; text-align: center !important;}
        .header-25 { background-color: #7fa9cf !important; color: #000 !important; font-weight: bold; text-align: center !important;}
        .header-26 { background-color: #1d70b8 !important; color: #fff; font-weight: bold; text-align: center !important;}
        
        /* Coluna de Horários */        
        .time-column {
            background-color: #ff6333;
            font-weight: bold;
            vertical-align: middle !important;
            width: 15%;
        }
        
        /* Linha de Intervalo */
        .interval-row {
            background-color: #0d1118;
            color: #fff;
            font-weight: bold;
            padding: 4px;
            text-align: center !important;
            font-size: 12px;
        }
        
        /* Conteúdo das Células */
        .session-title {
            font-weight: bold;
            text-transform: uppercase;
            font-size: 16px;
            margin-bottom: 8px;
            text-align: center !important;
        }
        .mediator {
            font-size: 12px;
            color: #7c0000;
            margin-bottom: 15px;
        }
        .speaker {
            font-size: 15px;
            color: #0f40e4 !important;
            font-weight: bold;
            margin-top: 10px;
        }
        .talk-title {
            font-size: 14px;
            color: #5568a7 !important;
            font-style: italic;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

<table>
    <thead>
        <tr>
            <th style="border: none; background: #fff;"></th>
            <th class="header-24">24.ago.2026<br><span style="font-weight: normal; font-size: 14px;">(segunda-feira)</span></th>
            <th class="header-25">25.ago.2026<br><span style="font-weight: normal; font-size: 14px;">(terça-feira)</span></th>
            <th class="header-26">26.ago.2026<br><span style="font-weight: normal; font-size: 14px;">(quarta-feira)</span></th>
        </tr>
    </thead>
    <tbody>
        <!-- MANHÃ -->
        <tr>
            <td class="time-column">10h00 - 12h00<br><span style="font-weight: normal; font-size: 14px;">(Manhã)</span></td>
            <!-- 24.ago -->
            <td>
                <div class="session-title">ABERTURA e<br>Sessão de Comunicação I</div>
                <div class="mediator">Mediador:<br>Prof. Dr. LUÍS EDUARDO RAMOS DE SOUZA</div>
                
                <div class="speaker">ALINE BRITO</div>
                <div class="talk-title">"Existência e representação: um diálogo entre Kant e a filosofia Sarvāstivāda"</div>
                
                <div class="speaker">ARTHUR SANTOS</div>
                <div class="talk-title">"O argumento de Kant a favor da dependência da prova cosmológica em relação à ontológica"</div>
            </td>
            <!-- 25.ago -->
            <td>
                <div class="session-title">Sessão de Comunicação III</div>
                <div class="mediator">Mediador:<br>Prof. Dr. PEDRO PAULO DA COSTA CORÔA</div>
                
                <div class="speaker">TAILA RIBEIRO</div>
                <div class="talk-title">"Razão e beleza em Kant"</div>
                
                <div class="speaker">MARIA CLARA CABRAL</div>
                <div class="talk-title">"O comentário de Hegel em Fé e Saber à Crítica do Juízo de Kant"</div>
            </td>
            <!-- 26.ago -->
            <td>
                <div class="session-title">Sessão de Comunicação V</div>
                <div class="mediator">Mediador:<br>Prof. Dr. PEDRO PAULO DA COSTA CORÔA</div>
                
                <div class="speaker">PAULO CUNHA</div>
                <div class="talk-title">"Kant e a Fundamentação da Moral: para além do ceticismo"</div>
                
                <div class="speaker">CÁSSIA COSTA</div>
                <div class="talk-title">"Kant e Schiller e uma nova Fundamentação da Estética e da Filosofia da Arte"</div>
            </td>
        </tr>
        
        <!-- INTERVALO -->
        <tr>
            <td class="interval-row"></td>
            <td class="interval-row">INTERVALO</td>
            <td class="interval-row">INTERVALO</td>
            <td class="interval-row">INTERVALO</td>
        </tr>
        
        <!-- TARDE -->
        <tr>
            <td class="time-column" style="background-color: #ff9933;">15h00 - 18h30<br><span style="font-weight: normal; font-size: 14px;">(Tarde)</span></td>
            <!-- 24.ago -->
            <td>
                <div class="session-title">Sessão de Comunicação II</div>
                <br>
                <div class="speaker">LUÍS EDUARDO DE SOUZA</div>
                <div class="talk-title">"Sobre a forma da Crítica da razão pura de Kant"</div>
                
                <div class="speaker">JOHN WALSCH</div>
                <div class="talk-title">"A definir"</div>
            </td>
            <!-- 25.ago -->
            <td>
                <div class="session-title">Sessão de Comunicação IV</div>
                <br>
                <div class="speaker">PEDRO PAULO CORÔA</div>
                <div class="talk-title">"Imaginação radical"</div>
                
                <div class="speaker">HEINER KLEMME</div>
                <div class="talk-title">"A beleza é a liberdade na aparência"</div>
            </td>
            <!-- 26.ago -->
            <td>
                <div class="session-title">Sessão de Comunicação VI</div>
                <div class="mediator">Mediador:<br>Prof. Dr. LUÍS EDUARDO RAMOS DE SOUZA</div>
                
                <div class="speaker">JOSÉ FILHO</div>
                <div class="talk-title">"A natureza do princípio da razão suficiente em Kant: entre a lógica, o transcendental e a metalógica"</div>
                
                <div class="speaker">FABIANA BRASIL</div>
                <div class="talk-title">"O belo e o juízo estético na terceira crítica"</div>
            </td>
        </tr>
    </tbody>
</table>

</body>
</html>


[:fontawesome-regular-house: Retornar à Página Inicial](index.md){ .md-button .md-button--primary }
