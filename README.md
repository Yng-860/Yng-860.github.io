# Oleksandr Tarkanovskyi 1TP
<html>
<table>
<tr>
  <th>Liczba porządkowa</th>
    <th>Nazwa projektu</th>
    <th>Miniaturka</th>
  <th>DATA</th>
</tr>
  <tr>
    <td>1.</td>
    <td>Pierwsza strona</td>
    <td>img src=</td>
    <td>11.09.2024</td>
  </tr>
  <tr>
    <td>2.</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
  <td>3.</td>
    <td></td>
    <td></td>
  <td></td>
  </tr>  
</table>
</html>

1
<html>
    <table cellpadding="10">
        <!-- Pierwszy wiersz -->
        <tr>
            <td rowspan="2">Rowspan</td>
            <td>Komórka 2</td>
            <td>Komórka 3</td>
        </tr>
        <!-- Drugi wiersz -->
        <tr>
            <td>Komórka 2</td>
            <td>Komórka 3</td>
        </tr>
        <!-- Trzeci wiersz -->
        <tr>
            <td>Komórka 1</td>
            <td>Komórka 2</td>
            <td>Komórka 3</td>
        </tr>
    </table>
</html>
2
<html>
    <table cellpadding="10">
        <!-- Pierwszy wiersz -->
        <tr>
            <td>Komórka 1</td>
            <td>Komórka 2</td>
            <td>Komórka 3</td>
            <td>Komórka 4</td>
        </tr>
        <!-- Drugi wiersz -->
        <tr>
            <td>Komórka 1</td>
            <td colspan="2">Połączone komórki</td>
            <td>Komórka 4</td>
        </tr>
        <!-- Trzeci wiersz -->
        <tr>
            <td>Komórka 1</td>
            <td>Komórka 2</td>
            <td>Komórka 3</td>
            <td>Komórka 4</td>
        </tr>
    </table>

</html>
3
<html>
    <table cellpadding="10">
        <!-- Pierwszy wiersz -->
        <tr>
            <td colspan="2">Połączone komórki</td>
            <td>Komórka 3</td>
            <td>Komórka 4</td>
        </tr>
        <!-- Drugi wiersz -->
        <tr>
            <td rowspan="2">Rowspan</td>
            <td>Komórka 2</td>
            <td>Komórka 3</td>
            <td>Komórka 4</td>
        </tr>
        <!-- Trzeci wiersz -->
        <tr>
            <td>Komórka 2</td>
            <td>Komórka 3</td>
            <td>Komórka 4</td>
        </tr>
        <!-- Czwarty wiersz -->
        <tr>
            <td>Komórka 1</td>
            <td>Komórka 2</td>
            <td>Komórka 3</td>
            <td>Komórka 4</td>
        </tr>
    </table>
</html>
<title>Umieszczanie stylów CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Umieszczanie styli CSS</h1>
    <table>
        <tr>
            <td><a href="body.html">1<br>body</a></td>
            <td><a href="head.html">2<br>head</a></td>
            <td><a href="external.html">3<br>zewnętrzny plik</a></td>
        </tr>
    </table>
</body>
</html>
</head>
<body>
    <h2>Umieszczanie stylów w &lt;body&gt;</h2>
    <blockquote>
        <code>
        &lt;style&gt;<br>
        body { background-color: lightblue; }<br>
        &lt;/style&gt;
        </code>
    </blockquote>
    <a href="index.html">Powrót do strony głównej</a>
</body>
</html>
