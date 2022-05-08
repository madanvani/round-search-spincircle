# round-search-spincircle

HTML:=

<!DOCTYPE html>
<html>

<head>
      <link rel="stylesheet" href="madan.css">
</head>
<body>

    <div class="search-box container">

    <input type="text" placeholder="search..." />
    <a href="##" class="icon">
        <i class="fas <i class="fa fa-search"></i>
    </a>
    </div>
    
    <div class="loader">
        <input type="text" placeholder="spin.." />
    </div>
    

    </body>



    </html>
                                               
                                               CSS:=
                                               
                                               
                                    .search-box{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: #2c3441;
    height: 40px;
    border-radius: 40px;
    padding: 10px;
}
.search-box:hover > input{
    width: 200px;
    padding:0 10px;

}
.search-box:hover > .icon{
    background: #536179;
}
.icon:hover{
    transform: rotate(360deg) scale(0.8);
}
input{
    width: 0;
    border: none;
    outline: none;
    padding: 0;
    background: none;
    font-size: 1.1rem;
    transition: 0.5s ease;
    line-height: 40px;
    color: #fff;
}
.container{
    background-color: #5721df ;}
.icon{
    color: #21dfcd;
    float: right;
    width: 40px;
    font-size: 1.3rem;
    height: 40px;
    border-radius: 50%;
    background: #2f3640;
    display: flex;
    justify-content: center;
    transition: 0.4s;
    cursor: pointer;
    text-decoration: none;
}
body{
    margin: 0;
    height: 40vh;
    display: grid;
    place-items: center;
    background-color: #65c1c8;

}
.loader{
    width: 80px;
    height: 80px;
    border: 10px solid rgba(243, 36, 36, 0.8);
    border-top-color:rgb(36, 157, 243);
    border-radius: 75%;
    animation:spin 4.5s linear infinite;
}
@keyframes spin{
    to{
        transform:rotate(360deg) ;}
    }

           
