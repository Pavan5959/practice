        <!DOCTYPE html>
        <html>
        <head>
                <title>Search Bar</title>
                <script src="https://kit.fontawesome.com/f9e9bca382.js" crossorigin="anonymous"></script>
                <style>
     body{
        margin: 0;
        padding: 0;
        background: #e84118;
    }
    .search-box{
        position: absolute;
        top:50%;
        left:50%;
    transform: translate(-50%,50%);
    background: #2f3640;
    height:40px;
    border-radius:40px;
    padding:10px;
    }
    .search-box:hover > .search-text{
        width: 240px;
        padding: 0 6px;
    }

    .bar{
        position: absolute;
        top:45%;
        left:40%;
    }
    h1:hover{
        background: #2f3640;
        text-transform: initial;
        border-radius: 0%;
        display:flex;
    }
    .search-box:hover > .search-btn{
        background: white;
    

    }
    .search-btn{
        color:  #e84118;
        float:right;
        width:40px;
        height:40px;
        border-radius:50%;
        background: #2f3640;
        display: flex;
        justify-content: center;
        align-items: center;
        transition:0.4s;
    }
    .search-text{
        border:none;
        background: none;
        outline: none;
        float:left;
        padding:0;
        color:white;
        font-size: 16px;
        transition: 0.4s;
        line-height: 40px;
        width: 0px;
    }
                </style>
        </head>
        <body>
        <div class="bar"><h1>Search Bar</h1></div>
            
        <div class="search-box">
            
            <input class="search-text" type="text" name="" placeholder="Type To Search">
            <a class="Search-btn" href="#">
                <i class="fas fa-search"></i>
            </a>
        </div>
        </body>
    </html>
