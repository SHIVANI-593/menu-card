//index.html

<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="style.css">
    </head>

<body>
    <div class="header">
        <h1>Reestar</h1>
        <h2>Home|Receipe|Contact</h2>
    </div>

    <div class="products">
        <div class="box">
            <img src="https://source.unsplash.com/220x220/?1">
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Accusamus voluptate voluptatum obcaecati et temporibus ea voluptates amet rerum tempora repudiandae.</p>
            <h3>Order NOW</h3>
        </div>

        <div class="box">
            <img src="https://source.unsplash.com/220x220/?2">
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Accusamus voluptate voluptatum obcaecati et temporibus ea voluptates amet rerum tempora repudiandae.</p>
            <h3>Order NOW</h3>
        </div>

        <div class="box">
            <img src="https://source.unsplash.com/220x220/?3">
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Accusamus voluptate voluptatum obcaecati et temporibus ea voluptates amet rerum tempora repudiandae.</p>
            <h3>Order NOW</h3>
        </div>

        <div class="box">
            <img src="https://source.unsplash.com/220x220/?4">
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Accusamus voluptate voluptatum obcaecati et temporibus ea voluptates amet rerum tempora repudiandae.</p>
            <h3>Order NOW</h3>
        </div>
    </div>
<div class="contact">
    <h1>Contact</h1>
 <div>
       <tr>
        <td>Name:</td>
        <td>
               <input type="text" placeholder="Enter your Name">
        </td>
    </tr>
</div>
<div>
        <tr>
        <td>Age:</td>
        <td>
               <input type="number" placeholder="Enter your Age">
        </td>
    </tr>
</div>
<div>
    <tr>
        <td>Email:</td>
        <td>
               <input type="email" placeholder="Enter your email">
        </td>
    </tr>
</div>
<div class="send">
    <h4>Send</h4>
</div>
</div>
</body>

</html>

//style.css

*{
    margin:0;
    padding:0;
}

.header{
    background-color: black;
    color:white;
    text-align: center;
}
h2{
    color: grey;
}
h3{
    color: white;
    background-color:black;
    border: solid black 2px;
}
.box{
    margin:30px;
    border:solid black 2px;
    display:inline-block;
    width:220px;
    text-align: center;
}
.contact{
    color:white;
    text-align:center;
    background-color: black;
}
.send{
    background-color: yellow;
    border:solid yellow 5px;
    color:black;
    display:inline-block;
    width:150px;
    height:30px;
}
