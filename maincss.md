body {
    width: 100%;
    margin: 0;
    display: inline-block;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

header {
    float: left;
    width: 800px;
    margin-left: calc(50% - 400px);
    margin-top: 30px;
    /* background-color: pink; */
}

header>img {
    float: left;
}

nav {
    float: right;
}

nav>a {
    color: #333;
    text-decoration: none;
    margin-left: 30px;
}

nav>a:first-child {
    margin: 0;
}


main {
    float: left;
    width: 800px;
    margin-left: calc((100% - 800px) / 2);
    margin-top: 60px;
    margin-bottom: 60px;
    /* background-color: greenyellow; */
}

main>div {
    width: 40%;
    float: left;
    margin-top: 20px;
}

h1 {
    margin: 0;
    font-size: 50px;
    font-weight: normal;
}

div>p {
    margin: 0;
    margin-bottom: 40px;
}

div>p:first-of-type {
    font-size: 50px;
    font-weight: bold;
    margin-bottom: 40px;
}

div>p:last-of-type {
    font-size: 20px;
}

main>div>div {
    display: inline-block;
}

main>div>div>a {
    float: left;
    background-color: #554485;
    color: #fff;
    padding: 16px;
    padding-left: 40px;
    padding-right: 40px;
    font-size: 16px;
    line-height: 20px;
    text-transform: uppercase;
    font-weight: bold;
    text-decoration: none;
    border-radius: 30px;
    border: 1px solid #554485;


}

main>a:last-child {
    background-color: #fff;
    color: #554485;
    margin-left: 20px;
}

main>img {
    width: 60%;
    float: right;
}

footer {
    float: left;
    width: 800px;
    margin-left: calc((100% - 800px) / 2);
    background-color: lightcoral;
}

footer>div {
    float: left;
}

footer>p {
    margin: 0;
    float: right;
}